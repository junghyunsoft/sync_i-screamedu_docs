---
description: 지정된 회차에 맞게 계산되는 수강료를 설정할 수 있어요.
---

# 회차 수강료 설정

## **수납 항목 횟수 사용 설정**

{% hint style="warning" %}
회차 수강료를 사용하려면 해당 설정이 반드시 선행되어야 합니다.
{% endhint %}

수납항목관리[^1] 팝업을 열어 새로운 수납 항목을 생성하거나 기존 항목을 수정 시 **횟수 사용**을 체크합니다. 횟수 사용이 체크 된 수납 항목은 회차 설정 적용을 받습니다.

* **금액**: 횟수 사용 항목이 체크되면 **금액 X 회차** 로 최종 수강료가 산정되므로 1회차 당 금액을 입력해주셔야 해요.

<div align="left"><figure><img src="../../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure></div>

## **회차 적용하기**

회차 수강료는 2가지 방법으로 사용할 수 있어요.&#x20;

### 1. 고정 회차 사용

{% hint style="info" %}
고정 회차 사용 시 월 수강료`= 금액 X 고정된 횟수`
{% endhint %}

1. 횟수 사용이 체크된 수납항목을 학급의 수납항목으로 가져옵니다.
2. **기본횟수**에 숫자를 입력하고 저장하면 수납항목의 **금액 \* 기본 횟수**가 매월 수강료가 됩니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure></div>

\[참고] 횟수 사용을 체크하지 않은 수납 항목은 기본 횟수 변경에 영향을 받지 않아요&#x20;

<figure><img src="../../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

### 2. 가변 회차 사용

{% hint style="info" %}
가변 회차 적용 시 월 수강료 `= 금액 X 수업 계획에 따라 산정된 횟수`
{% endhint %}

#### **가변 회차 적용 방법**

1. 수납항목의 횟수 사용을 체크합니다
2. \[항목추가]를 눌러 수납항목을 학급 수납항목으로 추가합니다.
3. 기본횟수를 비워두고 저장 시 가변 회차가 적용됩니다.

<figure><img src="../../.gitbook/assets/image (445).png" alt=""><figcaption></figcaption></figure>

#### **적용 시 주의 사항**

* 휴일은 회차 산정에서 제외됩니다.
* 예정 계획을 기반으로 하므로 [수업의 생성 여부](#user-content-fn-2)[^2]와는 무관합니다.

#### **가변 회차 적용 예시**&#x20;

매주 수요일 마다 진행되는 수업이라고 가정. 휴일은 고려하지 않음. 회차 금액은 5만원. &#x20;

<div align="left"><figure><img src="../../.gitbook/assets/image (442).png" alt=""><figcaption></figcaption></figure></div>

1️⃣ **9월**: 수요일이 4회 포함 → 9월 수강료 = **4 X 50,000 =&#x20;**<mark style="color:red;">**200,000**</mark>

<div align="left"><figure><img src="../../.gitbook/assets/image (439).png" alt="" width="563"><figcaption></figcaption></figure></div>

**2️⃣ 10월**: 수요일이 5회 포함 →  10월 수강료 = **5 X 50,000 =&#x20;**<mark style="color:red;">**250,000**</mark>

<div align="left"><figure><img src="../../.gitbook/assets/image (446).png" alt="" width="563"><figcaption></figcaption></figure></div>

## 수납예정항목 수정

회차가 적용된 수납예정항목은 횟수를 수정해 예정금액을 변경할 수 있어요. 수납 전 학생 또는 학원의 사정으로 회차 수가 변경된 경우 사용할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure>

[^1]: 학생관리 또는 학급관리 메뉴를 통해 접근할 수 있습니다.

[^2]: 전체 시간표 또는 수업 목록에서 수업이 확인되면 수업이 생성된 것입니다.
