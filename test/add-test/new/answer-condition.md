---
description: 채점 조건을 설정해 복수 정답, 다답형, 올답 등의 특수한 정답 조건을 처리할 수 있어요.
---

# 채점 조건 세부 설정

{% hint style="danger" %}
맥가이 사용 가이드 문서가 채널톡으로 이전되었습니다.\
기존 문서는 더 이상 업데이트되지 않으니, 앞으로 최신 가이드는 채널톡에서 확인해 주세요.\
[채널톡 바로가기↗](https://docs.channel.io/macgai-guide/ko/articles/scoring-condition-set-f4988137)
{% endhint %}

{% hint style="info" %}
이용 메뉴: 기본메뉴 → 수업관리 → 시험관리
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (402).png" alt=""><figcaption></figcaption></figure>

## **사용 방법**

### **선다형 문항, 숫자답안 문항**

**<조건 선택>**&#x20;

`and`, `or`, `all` 중 하나를 선택할 수 있어요

* **and** : 입력한 정답과 모두 일치하게 마킹했을 때에만 정답으로 인정&#x20;
* **or** : 입력한 정답 중 한 개 이상을 일치하게 마킹했을 때에는 정답으로 인정&#x20;
* **all** : 입력한 정답과 상관 없이 모두 정답 처리 됩니다.

1️⃣ 복수의 정답이 있는 경우 컴마(`,`)로 구분하여 입력할 수 있고 (예를 들어 1번과 3번이 정답인 경우에는 1,3 이라고 입력합니다)  2️⃣ 단수의 정답 문항인 경우에는 and 와 or 중 어느 것을 선택해도 입력한 정답과 동일하게 마킹해야 정답으로 인정됩니다.

### **점수입력 문항**

`없음` 또는 `all` 을 선택 할 수 있어요.

* **없음** : 입력한 점수로 채점됩니다
* **all** : 입력한 점수와 상관 없이 모두 배점과 동일하게 득점 처리 됩니다.

### **샘플 엑셀 파일 이용 시 주의점**

{% hint style="info" %}
[샘플 엑셀 파일을 이용해 문항 정보 입력하는 방법 → ](./#step-3)
{% endhint %}

**샘플 엑셀 파일**을 이용해 문항 정보를 입력하는 경우 채점조건을 제외한 나머지 열만 붙여 넣을 수 있습니다.

문제 형태 우측에 채점 조건을 입력한 후 복사 > 붙여넣기를 진행해도 **채점조건** 열의 내용은 변경되지 않습니다.

<figure><img src="../../../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>

## **문제 형태 별 설정 예시**

### **선다형**

<figure><img src="../../../.gitbook/assets/image (146).png" alt=""><figcaption><p>선다형 형태의 정답 설정</p></figcaption></figure>

### **숫자답안**

<figure><img src="../../../.gitbook/assets/image (147).png" alt=""><figcaption><p>숫자답안 형태의 정답 설정</p></figcaption></figure>

### **점수입력**

<figure><img src="../../../.gitbook/assets/image (148).png" alt=""><figcaption><p>점수입력 형태의 정답 설정</p></figcaption></figure>
