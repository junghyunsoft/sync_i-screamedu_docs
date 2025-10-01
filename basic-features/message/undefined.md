---
description: 403 에러가 발생하는 원인을 알아봅시다.
---

# 문자 발송 시 에러 발생할 경우

{% hint style="danger" %}
맥가이 사용 가이드 문서가 채널톡으로 이전되었습니다.\
기존 문서는 더 이상 업데이트되지 않으니, 앞으로 최신 가이드는 채널톡에서 확인해 주세요.\
[**채널톡 바로가기↗**](https://docs.channel.io/macgai-guide/ko/articles/403error-occur-1e8e0943)
{% endhint %}

## 에러 예시

문자 내용에 개발 코드에 사용되는 특수 문자가 포함되는 경우 방화벽 정책에 의해 차단될 수 있어요.

### 403 에러

<figure><img src="../../.gitbook/assets/image (500).png" alt=""><figcaption></figcaption></figure>

## 차단 가능성 문자 목록

### 기본 특수문자

* <mark style="color:red;">`'`</mark> (작은따옴표) - 문자열 구분에 사용, 가장 기본적인 SQL Injection 문자
* <mark style="color:red;">`"`</mark> (큰따옴표) - 일부 데이터베이스에서 문자열 구분에 사용
* <mark style="color:red;">`;`</mark> (세미콜론) - SQL 명령어를 구분하고 여러 쿼리를 연결할 때 사용
* <mark style="color:red;">`--`</mark> (이중 대시) - SQL 주석, 뒤의 코드를 무시하게 만듦
* <mark style="color:red;">`#`</mark> (해시) - MySQL에서 주석으로 사용
* <mark style="color:red;">`/**/`</mark> (블록 주석) - 여러 줄 주석 처리에 사용

### 논리 연산자

* <mark style="color:red;">`=`</mark> (등호) - 비교 연산에 사용
* <mark style="color:red;">`!=`</mark> 또는 <mark style="color:red;">`<>`</mark> - 부정 비교 연산에 사용

### 기타 중요 문자

* <mark style="color:red;">`+`</mark> (더하기) - 문자열 연결에 사용 (특히 MS SQL Server)
* <mark style="color:red;">`||`</mark> (이중 파이프) - 문자열 연결에 사용 (Oracle, PostgreSQL 등)
* <mark style="color:red;">`%`</mark> (퍼센트) - LIKE 연산자와 함께 와일드카드로 사용
* <mark style="color:red;">`_`</mark> (언더스코어) - LIKE 연산자와 함께 단일 문자 와일드카드로 사용
* <mark style="color:red;">`@`</mark>, <mark style="color:red;">`@@`</mark> - 변수 또는 시스템 변수 지정에 사용
* <mark style="color:red;">`)`</mark> (닫는 괄호) - 괄호 불균형을 이용한 공격
* <mark style="color:red;">`UNION`</mark> - 여러 SELECT 쿼리 결합에 사용

## 해결 방법

[#undefined-1](undefined.md#undefined-1 "mention")의 텍스트를 대체 혹은 삭제하여 문자 발송 시 정상 문자 발송이 가능합니다.

