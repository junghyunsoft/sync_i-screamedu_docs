---
description: 당일 출석 현황을 문자로 발송할 수 있어요.
---

# 출결 문자 발송

{% hint style="danger" %}
맥가이 사용 가이드 문서가 채널톡으로 이전되었습니다.\
기존 문서는 더 이상 업데이트되지 않으니, 앞으로 최신 가이드는 채널톡에서 확인해 주세요.\
[채널톡 바로가기↗](https://docs.channel.io/macgai-guide/ko/articles/send-sms-attendance-21668925)
{% endhint %}

{% hint style="info" %}
![](../../.gitbook/assets/chip_menuonly.svg) 기본메뉴 → 학급관리 → **수업목록**
{% endhint %}

<figure><img src="../../.gitbook/assets/image (254).png" alt=""><figcaption></figcaption></figure>

## 출석 문자 양식 관리

메뉴 우측 상단의 **\[수업문자문구저장]** 을 눌러 등원문자, 하원문자, 미등원문자, 수업결과문자의 전송 양식을 수정할 수 있어요.

<figure><img src="../../.gitbook/assets/image (245).png" alt=""><figcaption></figcaption></figure>

1. **등원문자**
   * **스마트 출결기**를 이용한 등원 체크 시 자동 발송
   * 출석 문자 전송 시 :radio\_button:**등원** 발송에 사용
2. **하원문자**
   * **스마트 출결기**를 이용한 하원 체크 시 자동 발송
3. **미등원문자**
   * 출석 문자 전송 시 :radio\_button:**미등원** 발송에 사용

{% hint style="info" %}
\[관리메뉴 → 학원정보 → **학원정보관리**]에서도 출석 문자 양식을 수정할 수 있어요. 변경 사항은 서로 연동됩니다.
{% endhint %}

## 출석 문자 치환값

출석 문자 발송 시 아래의 \[치환값[^1]]을 사용할 수 있어요.

<table><thead><tr><th width="168">치환값</th><th>가져오는 정보</th></tr></thead><tbody><tr><td><strong>[학원명]</strong></td><td>[학원정보관리] 메뉴의 <strong>학원정보: 학원명</strong>에 입력된 명칭</td></tr><tr><td><strong>[이름]</strong></td><td>전송 대상 학생의 <strong>이름</strong></td></tr><tr><td><strong>[이름이]</strong></td><td>전송 대상 학생의 <strong>이름 + 이</strong></td></tr><tr><td><strong>[시간]</strong></td><td><p>문자 유형에 따라 참조하는 값이 달라집니다.</p><ul><li>등원문자: 등원 체크 시간</li><li>하원문자: 하원 체크 시간</li><li><strong>미등원문자</strong>에는 <mark style="color:red;"><strong>사용할 수 없어요</strong></mark></li></ul></td></tr></tbody></table>

## 출석 문자 전송

학생들의 출결을 입력하고 **\[출석문자전송]** 버튼을 눌러 출결 문자를 발송할 수 있어요. 출결 문자는 수업 당일에만 발송할 수 있습니다.

<figure><img src="../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

1. **문자종류**: 등원 문자와 미등원 안내 문자 중 무엇을 보낼 지 선택합니다.  등원, 미등원 문자 양식은 저장된 값을 이용합니다. 학생의 출결 상태에 따라 등원/미등원이 자동 선택됩니다.
   * :radio\_button: **등원**: 출(출석), 지(지각), 조(조퇴)에 체크된 경우
   * :radio\_button: **미등원**: 통(통보결석), 결(결석)이 체크된 경우
2. **전송선택:** 문자 전송 여부를 선택할 수 있어요. 문자가 전송되지 않았거나 미등원 문자만 발송된 학생은 체크 상태가 기본값입니다.
3. **전송여부**: 출석 문자의 전송 여부를 확인할 수 있어요.

[^1]: 학생 및 기타 정보에 따라 자동으로 변경되어 발송 되는 값&#x20;
