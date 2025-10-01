---
description: 코칭 수업을 진행하고 기록하기 위한 스케줄을 생성하는 방법을 알아봅니다.
---

# 코칭 스케줄 관리

{% hint style="danger" %}
맥가이 사용 가이드 문서가 채널톡으로 이전되었습니다.\
기존 문서는 더 이상 업데이트되지 않으니, 앞으로 최신 가이드는 채널톡에서 확인해 주세요.\
[채널톡 바로가기↗](https://docs.channel.io/macgai-guide/ko/articles/coaching-schedule-management-43b37c9f)
{% endhint %}

자동으로 생성되는 주간 스케줄을 만들거나 학생 개인에게 요일, 시간을 부여하여 일정을 만들 수 있습니다.

## 1. 주간 계획 관리

**이용 메뉴**: 기본메뉴 → 학급관리 → 코칭수업관리&#x20;

{% hint style="info" %}
주간 계획을 만들지 않고 결과만 입력하는 방식으로도 이용할 수 있어요.\
자동 스케줄 관리를 사용하지 않으실 예정이라면 해당 파트(주간 계획 관리)는 건너뛰셔도 무방합니다.
{% endhint %}

주간 단위 스케줄을 만들 수 있어요. 입력 된 주간 스케줄에 맞춰, 매일 자정 마다 당일 포함 1주일 간의 수업을 자동 생성합니다.

우측 상단에 위치한 <img src="../../.gitbook/assets/Btn_코칭수업관리.png" alt="" data-size="line"> 버튼을 눌러 시간 별 정원을 설정할 수 있습니다.&#x20;

<div align="left"><figure><img src="../../.gitbook/assets/주간 스케줄 관리.png" alt="" width="563"><figcaption></figcaption></figure></div>

### 생성 예시

아래와 같은 방식으로 스케줄이 생성됩니다.

<figure><img src="../../.gitbook/assets/스케줄 생성 예시.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**스케줄 지정 시 주의 사항**

* **당일**의 스케줄 및 정원을 **즉시** 변경하려면 개별 날짜의 <img src="../../.gitbook/assets/Btn_정원추가및삭제.png" alt="" data-size="line">를 이용해주세요.
* 오늘 기준, 이전 요일의 스케줄을 수정하게 되면 과거의 스케줄에는 영향을 주지 않고 미래 시점 부터 적용이 됩니다.
  * 오늘이 수요일이라고 가정
  * 화요일의 스케줄 및 정원 정보를 수정 했다면
  * 목요일(내일)에 다음 주 화요일의 수업 정보가 만들어집니다.
{% endhint %}

### 입력 및 수정

요일과 시간이 교차되는 칸을 클릭하면 숫자를 입력하거나 변경할 수 있어요. 입력 완료 후 <img src="../../.gitbook/assets/Btn_저장.png" alt="" data-size="line"> 버튼을 누르면 변경 내용이 적용되고 다음 자정 부터 계획의 인원 정보를 이용해 수업을 생성합니다.

* 시간은 `09:00` 부터 `23:30` 까지 30분 단위로 선택할 수 있어요.
* 각 타임 별, 최대 정원은 `999`명 까지 가능합니다.

### 삭제

* **개별** 입력 값 삭제: 0을 입력하면 입력된 값을 삭제합니다.
* **전체** 입력 값 삭제: <img src="../../.gitbook/assets/Btn_비우기.png" alt="" data-size="line">를 누르면 입력 된 모든 인원정보를 삭제합니다.

{% hint style="info" %}
😵‍💫 **'비우기'를 잘못 누르셨나요?** \
\
<img src="../../.gitbook/assets/Btn_저장.png" alt="" data-size="line"> 버튼을 누르기 전에는 변경 내용이 적용되지 않아요.&#x20;

실수로<img src="../../.gitbook/assets/Btn_비우기.png" alt="" data-size="line">를 눌렀거나 잘못 수정하셨을 경우 <img src="../../.gitbook/assets/Btn_닫기.png" alt="" data-size="line">를 눌러 설정 창을 닫은 후 다시 열어주세요.
{% endhint %}

## 2. 일일 스케줄 관리

일일 스케줄 및 인원 정보를 수정할 수 있어요.&#x20;

{% hint style="success" %}
**꼭 알아두셔야 하는 정보!**

* 스케줄 정보의 **즉시 수정**은 각 날짜의 <img src="../../.gitbook/assets/Btn_정원추가및삭제.png" alt="" data-size="line">를 통해서만 가능합니다.
* 각 스케줄 블럭의 정원은 코칭 수업 계획에 입력 된 값이 가장 우선합니다.
  * 자동 생성 시, 정원이 변경 되어 있다면, 주간 계획에 설정 된 값으로 덮어씁니다.
{% endhint %}

**날짜 오른쪽의** <img src="../../.gitbook/assets/Btn_정원추가및삭제.png" alt="" data-size="line"> **버튼을 누르면 설정 팝업을 호출할 수 있어요.**

<div align="center"><figure><img src="../../.gitbook/assets/정원 추가 및 삭제_1.png" alt=""><figcaption></figcaption></figure></div>

**해당 날짜의 정원을 조정하고 예약 인원을 볼 수 있습니다.**

* 개별 날짜의 정원을 변경해도 주간 계획에는 영향을 주지 않습니다.
* <img src="../../.gitbook/assets/Btn_전부삭제.png" alt="" data-size="line"> 버튼을 누르면 선택 날짜의 정원과 예약 정보를 모두 삭제합니다. 삭제 결과는 되돌릴 수 없으니 신중하게 진행해 주세요!

<div align="center"><figure><img src="../../.gitbook/assets/정원 추가 및 삭제_2.png" alt=""><figcaption></figcaption></figure></div>

## 3. 개별 학생의 코칭 스케줄 지정

주간 스케줄과 별개로 개별 학생의 코칭 스케줄을 지정할 수 있어요.&#x20;

개인 스케줄을 지정하면 매일 자정 마다 정보를 읽어 당일 포함 1주일 분의 수업을 생성합니다.

{% hint style="danger" %}
**개별 학생 스케줄 생성 시 주의 사항**

* 학생 정보에 저장 된 코칭 스케줄은 정원과 무관하게 추가됩니다.
* 스케줄 정보를 변경하고 저장 시, 수업이 즉시 생성되는 것은 아닙니다.
* 생성 예시
  * 오늘이 7월 6일 목요일이라고 가정.&#x20;
  * 이가을 학생의 코칭 스케줄을 목요일 16:30으로 선택하고 저장하면
  * 7월 7일 자정 시점에, 7월 13일(목) 16:30에 학생의 이가을 학생의 수업이 만들어져요.
{% endhint %}

### 학생 관리 메뉴

1. 학생을 검색하여 선택하고 <img src="../../.gitbook/assets/btn_기본정보전체보기 .png" alt="" data-size="line">를 눌러 신상정보 표시 항목을 확장합니다.

<div align="left"><figure><img src="../../.gitbook/assets/개인 스케쥴 지정_1.png" alt=""><figcaption></figcaption></figure></div>

2. 코칭수업 항목에서 요일과 시간을 선택 후 저장합니다.

<div align="left"><figure><img src="../../.gitbook/assets/개인 스케줄 지정_2.png" alt=""><figcaption></figcaption></figure></div>

### 코칭 수업 관리 메뉴

3. 자정에 자동 생성이 완료 되면, 저장한 요일과 시간에 맞게 코칭 수업이 만들어집니다.

<div align="left"><figure><img src="../../.gitbook/assets/생성된 스케줄 확인.png" alt=""><figcaption></figcaption></figure></div>

4. 시간 블럭을 누르면 코칭 수업 상세 팝업이 열립니다. 예약 정보를 확인하고 결과를 기록할 수 있어요.&#x20;

<div align="left"><figure><img src="../../.gitbook/assets/스케줄 상세 보기.png" alt=""><figcaption></figcaption></figure></div>
