---
layout: post
title: "쏘카 QA는 무슨 일을 하고 어떻게 일하나요?"
subtitle: "카밀라의 QA 팀 적응기"
date: 2022-03-18 11:00:00 +0900
category: QA
background: '/assets/images/QA/background_from_unsplash.jpg'
author: camila
comments: true
tags:
  - qa
  - onboarding
---


안녕하세요.  작년 11월에 쏘카 QA 팀에 경력직으로 입사한 카밀라입니다.
 
신입 때 QA 업무는 반복적인 업무를 하는 단순 직무라 생각했었습니다. 하지만 여러 프로젝트들을 진행하며 커버리지를 높이기 위한 활동들과 기본 기능을 지속적으로 검증하기 위한 자동화 테스트 구축 등 계속해서 배워야 할 것들이 많은 직무라는 것을 몸소 깨달았습니다.

이번 글에서는 저의 입사 지원 과정부터 입사 후 3개월간의 수습 기간 동안 경험하며 느꼈던 내용을 공유해 보려고 합니다.

다음과 같은 내용에 관심 있으신 분들이 보시면 도움 될 거라 생각합니다. 🙂

- 쏘카 QA 팀에 어떻게 입사했을까?
- QA가 하는 일?
- 쏘카 QA 팀은 온보딩을 어떻게 진행할까?
- 쏘카의 QA 팀이 어떻게 업무할까?

## 목차

저는 다음 순서에 따라 글을 적어보았습니다.

- QA 팀 입사 지원 과정
    - 쏘카에 지원한 이유
    - 입사 과정
- QA란?
    - QA? 뭐 하는 팀이지?
    - 일반적으로 QA는 무엇을 하나?
    - 이슈를 찾기 위한 QA의 활동들
- 쏘카 QA의 업무
    - 업무 방식
    - 회의
- 쏘카 QA 팀의 온보딩 과정
    - 쏘키에 익숙해지기
    - 업무 경험하기
    - 혼자 프로젝트 진행하기
    - 온보딩을 하며 느낀 점
- QA 직군 지원자를 위한 TIP
- 끝으로

---

## 1. QA 팀 입사 지원 과정

먼저 간략히 쏘카 QA 팀에 입사하게 된 과정에 대해 소개해 보려고 합니다.

### 1.1. 쏘카에 지원한 이유

제가 쏘카에 지원한 이유는 모빌리티 산업에 관심이 많았고 자동차를 좋아해서였습니다. 또한 다음의 기준들을 만족하는지도 중요했습니다.

- 내가 좋아하는 일을 하면서 회사가 성장하고 나도 성장할 수 있는지
- 자체 서비스를 운영하는 회사인지
- 직원 규모가 어느 정도 이상인지(100명 이상)
- 지속적으로 성장하고 있는 회사인지

쏘카는 ‘쏘카 앱'을 기반으로 다양한 서비스를 운영하고 있고, 위와 같은 기준을 충분히 만족하는 회사였습니다. 그리고 채용공고와 커뮤니티 후기에서 QA 팀에서는 ‘주도적인 업무를 진행해 볼 수 있다'라는 부분과 ‘테스팅 자동화'를 진행한다는 부분이 가장 마음에 들었습니다. 쏘카에서는 저의 부족한 부분을 발전시키고 이전과는 다른 업무 경험을 쌓을 수 있을 것이라는 생각이 들었습니다.

### 1.2. 입사 과정

입사 과정은 다음 프로세스로 진행되었습니다.

1. 서류 제출
2. 1차 면접 (기술)
3. 2차 면접 (본부장 면접)
4. 3차 면접 (CTO 면접)

서류를 제출하고 일주일이 지나기 전에 전화로 채용 과정에 대해 안내받았습니다. 1차 면접 전날까지 사전과제를 제출해야 한다는 안내를 받았고 1차 면접이 통과하면 2차, 3차 면접이 있다고 안내받았습니다. 사전과제는 채용공고에도 나와있듯 쏘카의 서비스 중 하나를 선택하여 테스트 케이스를 작성하는 것이었습니다.

1차 면접(기술면접)에 실무진, 쏘카에 입사하면 같이 일하게 될 팀장님과 팀원 두 분이 면접관으로 참여하였습니다. 주로 이력서 위주의 질문이 나왔습니다. 참여했던 프로젝트에서 어떤 업무를 어떤 프로세스와 방식으로 진행했는지에 대한 질문과 업무를 하면서 마주할 수 있는 문제들에 대한 해결 방법을 묻는 질문이었습니다. 제출한 사전과제에 대해 해당 주제를 선택한 이유와 본인이 진행한 과제에 대해 설명하는 시간을 가졌고 마지막으로 입사해서 하고 싶은 업무와 본인의 성격에 대한 질문으로 마무리되었습니다.

1차 면접 후 1주일 안에 합격 연락이 왔고 2차와 3차 면접이 같은 날에 진행될 것이라 안내받았습니다. 2차는 본부장 면접이고 3차는 인사팀과 CTO 면접이라 안내받았습니다.

2차 면접에서는 본부장님과의 면접이 이루어졌고 1차와 비슷하게 이력서 위주의 질문들과 기술적인 부분, 인성 관련 질문도 있었습니다. 2차는 30분 정도 진행되었고 2차 면접 종료 후 바로 3차 면접을 진행했습니다. 3차 면접에서는 주로 CTO 님이 질문을 하셨고 딱딱한 질의응답보다는 저의 경험을 바탕으로 자유롭게 대화를 하듯 진행되었습니다. 그리고 조언도 해주셨는데 면접이 종료되고 난 뒤에도 해주신 말씀이 계속 생각나고 질문을 곱씹어 생각할 정도로 여운이 남는 면접이었습니다.

3차 면접 이후로 최종적으로 합격하여 쏘카에서 일하게 되었습니다.

---

## 2. QA란?

먼저 쏘카 QA 업무 설명에 앞서, 일반적으로 QA는 어떤 일을 하는지 먼저 설명해 보고자 합니다.

### 2.1. QA? 뭐 하는 팀이지?

QA에 대해 궁금하고 생소하신 분들도 계시고 왜 필요한지에 대한 의문을 가지는 분들도 많을 겁니다. 먼저 QA는 Quality Assurance의 약자로 ‘품질 보증’ 이란 뜻을 가지고 있습니다. QA 팀은 서비스의 '품질 보증' 관련 업무를 하는 팀으로, **서비스의 기능을 검증하고 관리하기 위한 일련의 활동을 합니다.** 프로젝트, 조직 규모가 작은 경우 개발자나 관리 조직에서 직접 기능 검증을 진행하기도 하지만, 프로젝트와 조직 규모가 커지는 경우 QA를 전담으로 하는 QA 팀을 구성해서 운영하기도 합니다. 

‘QA = Tester’라고 생각하시는 분들이 많습니다. 물론 QA의 활동 중 기능 테스트도 포함되어 있습니다. 하지만 QA는 단순히 서비스의 기능 테스트만 하지 않습니다. QA는 프로젝트의 시작부터 마무리까지 모든 과정에 참여하여 각 단계별로 품질을 저하시키거나 리소스가 낭비될 수 있는 요소를 발견한 뒤, 해당 프로젝트의 품질을 향상시키고 리소스 낭비를 방지하는 것을 목적으로 품질 보증 활동을 합니다.


![img](/assets/images/QA/qa_1.png){: width="50%"}


### 2.2. 일반적으로 QA는 무엇을 하나?

#### 킥오프 참여

회사마다 QA가 투입되는 시기는 다를 수 있지만 주로 QA는 킥오프(Kick-off) 단계부터 참여하게 됩니다. **단순히 버그를 찾기 위한 것이 아니라 프로젝트의 방향성, 목적, 요구사항 등 프로젝트의 근본적인 목적을 명확히 파악해야 올바른 검증을 진행할 수 있기 때문입니다.** 또한 초기 단계에서 발생할 수 있는 오류를 사전에 방지하여 낭비될 수 있는 리소스를 줄일 수 있습니다.

프로젝트가 진행되는 중간에 QA가 참여할 경우 프로젝트의 구성과 기능 파악, 테스트 범위, 검증 항목 선정 등에 더 많은 시간을 소모하게 되고 초기에 발견할 수 있던 문제점이 발견된다면 불필요한 리소스가 낭비될 수 있습니다. 그리고 프로젝트의 기간과 목적에 적합한지, 프로젝트 기간을 고려하여 진행 가능한지, 기간이 얼마나 더 필요한지 등을 제대로 판단할 수 없게 됩니다.

QA는 지속적으로 개발자, 기획자와 소통하며 기획의 목적대로 흘러가고 있는지 업무상 진행되는 과정에서 비효율적인 부분은 없는지 리뷰를 진행하고 개선안을 제시합니다. 또한 유저의 입장에서 발생할 수 있는 불편함은 없는지 확인합니다. 

![img](/assets/images/QA/qa_3.png)
*QA의 업무 단계별 활동과 산출물입니다.*

#### 분석 & QA Plan 작성

킥오프가 진행된 후에는 기획서를 분석하여 프로젝트 수행 시 발생할 수 있는 리스크를 예상해 보고 테스트 전략을 수립합니다.

이후에는 QA Plan 또는 테스트 계획이라고도 하는 문서는 작성합니다. **QA Plan은 테스트를 하기 위해 필요한 리소스들을 요약해놓은 문서로, QA가 정해진 프로세스대로 업무를 수행하기 위한 청사진 역할을 합니다.** 이 안에서 테스트의 명확한 기준을 세워 원하는 방향으로 테스트가 진행될 수 있도록 합니다. 이 문서는 테스트를 수행하는 도중 변경되기도 하는 등 지속적으로 관리됩니다.

QA Plan에는 다음 내용들이 포함됩니다.

```
[프로젝트 명] QA Plan

1. 요약
2. 프로젝트명
3. 프로젝트 자료
    3.1. 기획서
    3.2. 디자인
    3.3. Test case
    3.4. Test data
4. 참여자
5. 배포되는 버전
6. QA 기간
    6.1. Test case 작성 기간
    6.2. 테스트 기간
    6.3. Sign off 날짜
    6.4. 배포 요청일
    6.5. 모니터링
7. 테스트 범위
8. 테스트 제외 범위
9. 품질 목표 설정
10. 테스트 종료 조건 설정
11. 테스트 환경
    11.1. 디바이스
    11.2. OS 버전
12. 테스트 요청사항
```


#### 테스트 케이스 작성

QA Plan이 작성되었다면 테스트 케이스(TC)를 작성합니다. **테스트 케이스를 작성하는 과정에서 요구사항에 대한 오류를 찾을 수도 있고 고려되지 않았던 부분을 찾아낼 수 있습니다**. 또한 테스트 케이스 리뷰 과정을 통해 팀 구성원들에게 테스트 케이스 적정성을 점검하고 잘못된 이해로 인한 오류도 점검할 수 있습니다.

다음은 테스트 케이스 예시입니다.
   

| ID | Category | Preconditions | Steps | Expected result | Galaxy21 (Android 11) | iPhoneX (iOS 14.4.2) | Comment |
|:---:|:---:|:---|:---|:---|:---:|:---:|:---|
| Socar_001 | 예약하기 | 쏘카 앱에 로그인되어 있는 상태 | 지도에서 쏘카 존을 선택 | 선택한 쏘카 존의 차량 목록이 노출됨 | PASS | N/A | 다른 기종 확인 필요 |

#### 테스트 데이터와 환경 준비

테스트 케이스 작성과 리뷰가 완료되었다면, 본격적으로 테스트에 들어가기에 앞서 테스트 데이터와 환경을 준비해야 합니다. **테스트를 수행하기 위한 기본 데이터들을 정리하고 어떤 환경에서 테스트가 시작될지를 미리 준비하는 과정입니다.** 테스트를 위한 데이터의 예로는 테스트 계정, 계정에 따른 권한 등이 있을 수 있고 테스트 환경은 테스트 서버 설정이 포함됩니다.

#### 테스트 수행 & 버그 리포트 작성

본격적으로 테스트 수행을 시작하게 되면 준비된 테스트 케이스 외에도 **탐색적 테스트, ad-hoc 테스트**를 통해 이슈를 발견할 수 있습니다. 이때 발견한 이슈들을 구두로만 개발자와 주고받게 된다면 히스토리 관리가 힘들어질 수 있습니다. 이런 불편함을 줄이고 프로젝트 이슈들을 관리하기 위해 버그 리포트를 작성합니다. 

버그 리포트에는 다음 내용들이 포함됩니다.

```
[버그리포트 제목]

- 발생 환경(os 버전, 앱/웹 버전, 서버)
- 재현율
- 이슈 설명
- 사전 조건
- 재현 절차
- 예상 결과
- 실제 결과
- 담당 부서
- 우선순위/심각도
- 발생 버전/수정 버전
- 이슈 카테고리
- 첨부파일
```

#### 테스트 결과 공유
        
테스트가 완료되고 나면 결과를 정리하여 프로젝트 구성원들에게 공유합니다. QA Plan에서 정한 품질 목표를 달성하여 **릴리즈가 가능한 상태인지를 알려주고 테스트 수행 결과와 품질 목표 달성에 따른 판단 결과, 테스트 진행하면서 발생한 이슈 현황들에 대한 정보**를 담고 있습니다.

QA가 수행하는 단계마다 산출물이 발생하고 있고 이 산출물들은 QA가 프로젝트를 수행함에 있어 어떤 업무를 수행하고 어떻게 진행해야 하는지 방향을 알려주는 표지판 역할을 하게 됩니다. 수행하는 단계별로 QA 업무에 대해 정리하였지만 사실 ‘여기까지가 QA의 업무입니다'라고 할 수 없습니다. 

사실 유관부서와 협의하에 품질 향상에 도움이 되는 일 중 QA가 할 수 있는 모든 일들을 한다고 생각하시면 QA 업무가 더 쉽게 와닿을 것 같습니다.


### 2.3. 이슈를 찾기 위한 QA의 활동들

"이슈 찾는 활동? 테스트 케이스로만 테스트하고 이슈 찾는 거 아니었나요?"라고 생각하실 수 있습니다.

작성한 테스트 케이스로만 이슈를 찾을 수는 없습니다. 일반적으로 테스트 케이스는 기획서를 기반으로 재현 조건과 기대 결과를 도출하여 기대 결과가 정상적으로 출력되는지 확인하는 긍정 테스트에 가깝습니다. 그럼 부정 테스트 케이스를 추가하면 되지 않을까? 물론 부정 테스트의 방법도 있지만 비정상적인 상황은 너무 다양하기 때문에 모든 것을 다 케이스화하는 것은 현실적으로 불가능합니다. 또한 자주 업데이트가 되는 서비스라면 더욱 힘들 겁니다.

그래서 QA는 각 단계에서 할 수 있는 최선의 활동들을 통해 이슈를 찾아가고 있습니다.

**개발 전에 프로젝트의 목적과 기획서를 바탕으로 다양한 시나리오를 생각하는 과정에서 명확히 정의되지 않은 것들을 확인한 뒤, 이해관계에 따라 발생할 수 있는 문제점들을 발견하여 개선될 수 있도록 합니다.** 또한 기획이나 컨텐츠 리뷰를 통해 논리적 오류나 유저에게 잘못 이해될 수 있는 부분, 오타 등을 확인하여 **개발 이후 발생할 수 있는 이슈들을 파악**합니다.

또한 단순히 버그를 찾는 것이 아닌 유저 입장에서 미래에 발생할 수 있는 문제들을 미리 예측해 보는 것도 이슈를 찾는 활동입니다. 실제 유저의 입장에서 서비스를 사용해 보며 유저가 사용할 수 있는 경로는 어떤 것이 있으며 어떤 부분에서 불편함을 느낄 수 있을지에 대한 고민을 합니다. 이때 유저 사용성에 따른 시나리오를 분리하여 테스트를 진행하기도 하는데 앞서 언급한 부정 테스트(Unhappy Path Test)와 긍정 테스트(Happy Path Test) 방법이 있습니다. 부정 테스트는 주어진 소프트웨어가 올바르게 작동하는지 확인하기 위해 잘못된 데이터를 입력하고 잘못된 작업을 수행하도록 구성합니다. 그러면 소프트웨어는 작동되지 않고 **사용자가 이해할 수 있는 오류 메시지를 노출해 주는지 확인합니다.** 반대로 긍정 테스트는 오류가 생성되지 않는 데이터를 입력하여 **소프트웨어가 의도대로 작동하는 것을 확인합니다.**

기존 서비스에 기능이 추가되는 경우 기존 서비스가 정상 동작하는지 확인하기 위해 기본 기능에 대한 체크리스트를 수행하기도 하지만, 반복적으로 진행해야 되는 테스트의 경우 자동화 테스트를 진행하기도 합니다. 자동화 테스트란 자동화 도구로 테스트 스크립트를 개발하여 소프트웨어의 유효성을 검사하는 것입니다. **자동화 테스트를 통해 기존에는 발생하지 않았던 문제점들을 찾아낼 수 있고 변경된 부분을 발견할 수 있습니다.**

이처럼 QA는 테스트 케이스를 활용하는 테스트 외에도 다양한 활동들 가운데 품질 향상을 위해 문제점을 찾고 개선하는 노력을 하고 있습니다.

---

## 3. 쏘카 QA의 업무

이제 쏘카 QA 팀에서는 구체적으로 어떻게 업무하는지에 대해서 설명드리고자 합니다.

### 3.1. 업무 방식

QA라도 회사마다 각기 다른 프로세스에 따라 업무를 진행합니다. 기획과 개발이 다 완료된 상태에서 QA가 투입되는 경우도 있고, 주제만 정하고 기획을 만들어 가는 과정에서 QA가 투입되는 경우, 기획서가 만들어진 후 QA가 투입되는 경우 등 다양한 단계에서 참여가 이루어지고 있습니다. 

![img](/assets/images/QA/qa_2.png)

**쏘카에서는 QA 요청서가 발의되었을 때 QA가 프로젝트에 참여합니다.** QA 요청서는 JIRA를 통해 만들어지고 정해진 양식에 맞춰 프로젝트 리더가 작성하여 요청합니다. 이 요청서에는 기획서가 포함되어 있고 기획, 개발, 디자인 일정이 포함됩니다. 프로젝트별로 상이하긴 하지만 디자인이 완료된 경우 디자인 링크도 포함됩니다. 그리고 프로젝트에 관련된 자료들이 첨부됩니다.

QA 요청서가 발의되면 팀 내에서 **담당자를 정하게 되고 본격적으로 프로젝트에 투입**되어 업무를 하게 됩니다.

**배정된 담당자는 킥오프(Kick-off) 회의에 참여**하여 프로젝트의 규모와 목적을 파악하고 다음 내용들을 **QA Plan에 작성**합니다.
    - 프로젝트 정보
    - QA 일정
    - 테스트 데이터
    - 테스트 기준
    - 테스트 범위
    - 테스트 환경 

QA Plan을 작성할 때 보통 QA 요청서를 참고하고 QA를 진행하면서 필요할 사항들을 수집하고 정리합니다. 프로젝트를 진행하기에 앞서 필요한 전제 조건들과 검증 시 반드시 확인해야 될 사항들, 그리고 검증 진행 방법들도 회의를 통해 확인하고 적어놓습니다. 쏘카의 QA Plan은 초기에 한번 적고 끝나는 것이 아니라 테스트 케이스를 작성하거나 테스트를 수행하면서도 새로운 내용이나 참고할 사항들을 꾸준히 업데이트하게 됩니다.
프로젝트에 관해 설명이 더 필요한 부분이나 의견이 있다면 PM, 개발자, 디자이너 등 프로젝트에 참여하는 인원들과 소통하여 문제를 해결합니다.

프로젝트에 대해 파악되었다면 **테스트 케이스 혹은 체크리스트를 작성**합니다. 프로젝트의 규모가 크지 않거나 빠르게 확인해야 프로젝트의 경우, 확인해야 될 주요 항목을 간략하게 적어서 정상적으로 수행이 되는지를 판단하기 위해 체크리스트를 작성하게 됩니다. 체크리스트와 다르게 테스트 케이스의 경우에는 전제조건과 수행하는 절차 그리고 수행함으로 인해 기대되는 결과가 포함되기 때문에 체크리스트보다 더 세밀하게 기능을 테스트를 진행할 수 있습니다. 쏘카에서는 테스트 케이스 관리를 웹 기반 테스트 관리 시스템인 [Testlink](https://testlink.org/)로 하고 있습니다. 테스트 케이스는 작성하는 사람에 따라 다르겠지만 주어진 형식은 맞추되 작성하는 건 본인 성향에 따라 작성하고 있습니다. 어떤 사람은 오타와 띄어쓰기 하나까지 세세하게 테스트 케이스로 작성할 수 있고 어떤 사람은 기능만 위주로 작성하여 차이가 나지 않을까 우려할 수 있지만 테스트 케이스를 작성한 후 팀 내에서 리뷰를 진행하고 피드백을 통해 맞춰가고 있습니다. 또한 필요에 따라 **팀 내에서 테스트 케이스 리뷰가 진행된 후 프로젝트 내에서도 테스트 케이스 리뷰**를 진행합니다.

개발이 완료되고 나면 개발 환경에서 테스트를 수행할 수 있게 **테스트 서버를 띄워 QA를 수행**합니다. 작성한 테스트 케이스를 바탕으로 테스트를 수행하는 데 프로젝트에 따라서 앱 또는 웹 테스트를 진행합니다. 데이터를 확인해야 되는 프로젝트라면 DB를 조회해서 테스트를 진행할 수도 있고 실제 차량에 들어가는 장비를 가지고 테스트를 진행하기도 합니다. 또한 일정에 따라 실제 차량으로 테스트를 진행하는 등 다양한 테스트 활동을 추가로 진행하기도 합니다. **테스트를 수행하면서 발견되는 이슈들은 JIRA에 등록**합니다. 

**QA가 완료된 후에 팀과 프로젝트 내에 프로젝트가 종료되었다는 의미로 Sign off**를 합니다. 프로젝트 수행 내용을 간략하게 전달하고 서버나 웹 관련 프로젝트라 배포까지 완료되었다면 모니터링에 대한 내용도 포함하여 공유합니다. 

그 후에는 **프로젝트를 수행하면서 알게 된 내용이나 공유할 내용, 남겨야 되는 주요 토픽 등에 대해 자유롭게 문서 정리**를 합니다. QA Plan에 내용을 추가하여 정리하는 경우도 있지만 규모와 히스토리가 긴 프로젝트의 경우엔 컨플루언스에 따로 페이지를 만들어서 작성합니다.

프로젝트별로 QA가 완료되고 나면 **하나의 버전으로 배포하기 위해 검토를 한 후 빌드 요청**을 합니다. 빌드 된 앱의 회귀 테스트(Regression test)를 진행한 후 앱 심사를 요청하고 **심사가 완료되고 난 뒤 QA 팀에서 마켓 배포를 수행합니다.**
    


### 3.2. 회의

쏘카 QA 팀에서 정기적으로 진행되는 회의는 2개가 있는데 그중 하나는 **매일 아침 10시에 업무공유를 위한 회의**입니다. 각자 당일에 진행할 업무에 대해 공유하고 전달사항을 공유 받는 회의입니다. 또한 새로운 업무가 생겼을 때 담당자를 지정하는 것도 아침 회의 시간에 주로 진행됩니다.
 
또 다른 하나는 **매주 금요일 오후 2시에 진행하는 회고**입니다. 한주를 돌아보며 자유롭게 이야기하고 의견을 나누는 시간입니다. 한 주 동안 업무를 하면서 좋았던 점과 아쉬웠던 점에 대해 이야기를 하고 진행하고 있는 프로젝트나 팀 내에서 논의하고 싶은 내용에 대해 주제를 정해 이야기하기도 합니다. 처음에는 회고라 해서 무겁고 딱딱한 분위기일 수도 있겠다라 생각이 들었지만, 실제로 해보니  편하게 수다 떨듯 얘기하면서도 진지한 얘기를 할 때는 진지하게 의견을 나누기도 했습니다. 참여하기 전에는 무슨 얘기를 해야 될지, 이런 얘기도 해도 되나? 하는 걱정이 들었지만 생각보다 2시간이 훌쩍 지나가곤 합니다. 회고 시간을 통해 팀원들과 다 같이 얘기하는 시간을 갖고 업무에 대한 조언과 도움도 받을 수 있습니다. 또한 우리 팀이 나아 갈 방향과 진행할 업무들 그리고 개선할 점들을 토론하며 각자가 QA 팀의 일원으로서 함께 팀을 만들어나가는 의미 있는 시간이라 생각합니다.

이 외에 한 달에 한 번 쏘카의 전 직원들이 참여하는 **Town Hall 이라는 회의**가 있고 각자가 속한 **프로젝트에서 진행하는 회의**가 있습니다. 팀 내에서 갑자기 생긴 논의사항이나 전달사항이 있을 경우에도 회의가 생기기도 합니다.

---

## 4. 쏘카 QA 팀의 온보딩 과정

다음으로 QA 팀에 합류한 이후 온보딩 과정의 경험을 공유해 보려 합니다.

### 4.1. 쏘카에 익숙해지기

채용 프로세스가 끝나고 드디어 쏘카 입사 첫날! 로비로 가는 것부터 지하를 뱅글뱅글 돌고 물어보고서야 찾아갈 수 있었습니다. 팀 내에서 진행되는 온보딩은 4주 과정으로 계획되어 있었지만 일정상 5주간 진행되었습니다.

재택근무를 시행하고 있어 동료들을 많이 만나진 못했지만 화상회의로 또는 종종 사무실에 출근하시는 분들과 인사하고 같이 점심을 먹거나 티타임을 가졌습니다. 팀 온보딩을 진행하는 동안 저는 사무실 출근을 했고 사무실 투어도 하고 근처 맛집들을 가보기도 하며 종종 서울숲 산책도 했습니다. 그동안 미로 같던 회사 길도 이리저리 잘 찾아다닐 수 있게 되었고 예약도 찾기도 어렵던 회의실도 척척 예약하고 찾아갈 수 있게 되었습니다.

PX(People Experience) 팀에서 진행하는 온보딩은 입사 후 일주일 뒤에 하루 일정으로 진행되었습니다. 같은 날 입사한 동료들과 온보딩에 참여하여 자연스럽게 서로에 대해 알아가며 점심도 같이 먹으며 친해질 수 있었습니다. 또한 쏘카의 히스토리와 문화를 액티비티를 통해 몸으로 익히며 알 수 있었습니다. 온보딩을 같이한 동료들과는 팀이 달라 자주는 아니지만 종종 만나서 점심을 먹기도 하고 티타임을 갖고 있습니다. 입사 후 몇 번의 만족도 조사를 시행했는데 신규 입사자가 쏘카에 적응할 수 있도록 지속적으로 돕는 프로세스가 정말 잘 되어있다고 느꼈습니다.


### 4.2. 업무 경험하기

QA 팀에서 진행된 온보딩은 5주 동안 진행되었고 입사 후 첫 주는 주로 PC 세팅과 업무에 필요한 장비와 계정을 등록했습니다. 업무 파악을 위해 각종 회의에 참여하기도 했습니다. 2주에 걸쳐 팀장님에게 업무 프로세스와 쏘카 앱에 대한 설명과 히스토리에 대해 교육을 받았습니다. 이후에는 쏘카 앱을 직접 사용해 보는 시간을 가졌고 각 서비스들을 담당했던 팀원들과 같이 해당 서비스를 살펴보는 시간을 가졌습니다. 3주 차엔 테스트 케이스 관리 툴의 사용법을 익혔습니다. 쏘카 앱 체크리스트를 직접 수행하면서 교육받은 내용을 리마인드하고 모르는 부분을 체크하는 시간도 가졌습니다. 마지막으로 4주 차, 5주 차에는 팀원과 같이 프로젝트에 참여하여 실제 업무를 익혔습니다. 해당 프로젝트 종료 후에는 혼자 프로젝트에 참여하여 직접 QA 업무를 수행할 수 있었습니다.


#### 문서 작성은 중요해

쏘카에 입사 후 놀랐던 것 중 하나가 신규 입사자가 볼 수 있는 자료가 많다는 것이었습니다.
회사와 업무에 대해 궁금한 것들을 찾아볼 수 있게 자료들이 잘 정리되어 있습니다.
신규 입사자들이 쏘카의 업무방식과 쏘카에 대한 이야기, 그리고 업무지원 및 요청 가이드 등을 알 수 있도록 ‘SOCAR 백과사전’ 이라는 것이 있고 노션(Notion)과 컨플루언스(Confluence)에 각 팀별, 프로젝트 별로 문서가 정리되어 있습니다.

신규 입사자를 위한 것뿐 아니라 쏘카의 모든 직원들을 위한 자료도 많았습니다. 저도 입사 후 온보딩을 진행하면서 필요하다고 생각되는 문서들은 직접 만들거나 기존 문서를 업데이트하기도 했습니다.
이 문서들은 한 번에 일괄적으로 작성되는 것은 아니고, 업무를 하는 동안 본인이 수행한 업무를 리마인드하고 히스토리를 관리하기 위해 작성되곤 했습니다. 이렇게 모인 자료들은 쏘카의 모든 직원들에게 공유될 수 있었습니다. 저는 본인이 수행한 일을 문서로 남기는 것은 실제 업무를 수행하는 것만큼이나 중요하다고 생각하는데, 이게 생각과 다르게 지속되기란 쉽지 않은 문제입니다. 그런데 쏘카에서는 많은 동료들이 본인이 진행한 업무뿐만 아니라, 다른 동료들에게 필요할 수 있는 정보들을 문서화하고 지속적인 업데이트를 통해 관리해나가고 있는 것을 볼 수 있어서 인상 깊었습니다.


#### 같이하는 프로젝트 진행 경험하기

온보딩 4주 차에는 팀원과 같이 프로젝트에 참여하여 실제 업무를 하며 익히는 시간을 가졌습니다. 업무에 익숙한 팀원과 같이 프로젝트를 진행하면서 쏘카의 업무를 알아가도록 도와주는 과정이었습니다. 저는 팀 동료 에이미와 같이 프로젝트에 참여하였는데, 어느 단계에서 무엇을 해야 하는지, 다음 순서는 무엇인지, 제가 수행할 수 있는 업무는 직접 해볼 수 있게 에이미가 도와주셨고, 처음 해보는 것은 같이 수행하면서 업무에 적응할 수 있도록 도와주셨습니다. 물론 프로젝트마다 참여하는 인원은 다르지만 담당자와 어떻게 소통을 해야 하는지, 어떤 방식으로 업무가 진행되는지에 대해서도 배울 수 있는 시간이었습니다.


#### 모르는 건 질문하기

새로운 회사에 경력직으로 입사를 하더라도 새로운 회사의 업무방식에 맞춰 기존에 알던 것도 다시 보고 사용하던 도구들도 다시 배우게 됩니다. "경력직이니까 이런 건 당연히 알겠지?"라고 생각하시는 분들이 종종 있기 때문에, 입사 전에 심적으로 꽤 큰 부담이 있었습니다. 하지만 걱정했던 게 무색할 정도로 쏘카에 첫 출근하는 날 모두들 "모르는 거 궁금한 거 언제든 물어보세요"라고 먼저 말씀해 주셨습니다. 저도 마음을 조금 내려놓고 정말 많이 질문했는데 다들 하나같이 친절하게 알려주셨습니다. 시간 날 때마다 계속 신경 써주시고 알려주셔서 업무를 익히고 적응하는 데 도움이 되었습니다.


![img](/assets/images/QA/qa_4.png){: width="50%"}
![img](/assets/images/QA/qa_5.png){: width="50%"}
*팀 채널에 궁금한 사항을 남기면 팀원 분들이 친절하게 알려주십니다.*

또한 회사 뒤편에 서울숲이 있어 점심을 먹고 가볍게 산책하면서 소소한 이야기를 나누기도 합니다. 회사가 카페가 많은 성수동에 있어, 커피를 종종 마시면서 수다를 떨면서 자연스럽게 모르는 걸 묻기도 하고, 팀원들 간에 서로 일상을 공유하는 시간을 가지기도 합니다.

![img](/assets/images/QA/qa_6.jpeg){: width="50%"}
*성수동엔 이쁜 카페가 많습니다.*

![img](/assets/images/QA/qa_7.jpeg){: width="50%"}
*가을에 서울숲에 꼭 가보시길 추천드립니다.*


### 4.3. 혼자 프로젝트 진행하기

같이 프로젝트를 진행해 본 후 혼자서 프로젝트에 참여하게 되었습니다. 쏘카의 QA로서 처음 맡은 업무였습니다. 

참여하게 된 프로젝트는 일부 기능 변경이 있는 작은 규모였습니다. 하지만 당혹스럽게도 팀 동료 에이미와 함께 진행했던 프로젝트와는 일하는 방식이 달랐습니다. 팀원들에게 조언을 구하며 업무를 진행했고, 예상치 못한 문제들이 발생하여 일정이 기존에 계획했던 것보다 딜레이가 되었지만 결과적으로는 잘 마무리를 할 수 있었습니다. 프로젝트가 종료된 후에는 진행한 업무에 대해 문서 정리를 하고, 이해관계자들과 논의하는 자리를 마련하여 개선되었으면 하는 부분과, 정리가 아직 안 된 부분에 대해 정리하였습니다.

### 4.4. 온보딩을 하며 느낀 점

쏘카에 와서 처음부터 지금까지 너무 좋다고 생각하는 부분은 모두가 자유롭게 의견을 내고 듣는 사람들도 편견 없이 들어주고 같이 고민하고 개선하려 한다는 것입니다. 적극적이고 쏘카의 서비스를 쏘카의 모든 직원들이 같이 만들어나가고 있다는 느낌을 받았고 제가 그런 쏘카의 직원이라는 게 자랑스럽게 느껴졌습니다. 개개인이 아닌 쏘카라는 하나의 목표를 향해 나아간다는 느낌을 들었고 그것이 누군가의 강요가 아닌 모두의 자발적인 모습에서 비롯된 것이라는 점이 인상 깊었습니다.

한편 온보딩을 하는 동안 좀 더 개선하면 좋겠다고 생각한 것은 ‘회의가 너무 많아서 줄었으면 좋겠다’ 이었습니다. 어떤 날은 정말 하루 종일 점심시간을 제외하고 회의에 참석한 날도 있었으니까요. 하지만 조직 개편 후에는 정기적으로 진행되던 많은 회의들이 사라졌고 본인 업무에 직접적인 연관이 있는 회의로 많이 축소되었습니다. 맡은 업무에 따라 여전히 많은 회의를 참석하는 날도 있지만 그만큼 할 수 있는 일이 늘었다는 것에 한편으로는 정말 쏘팸이 된 걸 느끼게 됩니다.

---

## 5. QA 직군 지원자를 위한 TIP

이번에는 QA 직군 지원자분들을 위한 저만의 팁에 대해 공유드리려 합니다.

QA는 꼼꼼해야 해, 커뮤니케이션이 능숙해야 해, 대처법을 잘 알아야 해, 문제를 많이 찾을 수 있어야 해, 남들과 다른 관점에서 볼 줄 알아야 해 등 QA 직무에 대해 물어보면 주로 들을 수 있는 말입니다. 하지만 모든 QA가 저런 특성을 가지진 않습니다. 커뮤니케이션이 약한 사람도 있고 꼼꼼하지 못한 사람도 많습니다. 저런 부분은 각 사람의 성향에 해당하는 것이기 때문에 저런 성향을 가지신 분들이라면 좋겠지만 저는 다음 세 가지가 더 중요하다 생각합니다.

**먼저 QA를 하고 싶다면 QA가 사용하는 기본적인 용어를 알고 있어야 된다 생각합니다.** 왜 그런 걸 알아야 하지? 몰라도 할 수 있지 않나? 하고 생각하실 수 있습니다. 물론 모르셔도 업무는 할 수 있습니다. 하지만 해당 직군에서 사용하는 용어들을 알고 있으면 본인 업무에 대한 이해와 수행할 수 있는 업무의 폭을 넓혀줄 수 있다 생각합니다. QA 채용공고를 보면 우대 항목에 ‘ISTQB 자격증’ 이 있습니다. 자격증이 있어야 된다는 것은 아닙니다. 하지만 QA에 대한 지식이 없다면 ISTQB 책을 한 번 정도는 읽어보면 업무를 이해하는 데 도움이 될 것입니다.

두 번째로는 **QA 프로세스를 알고 있어야 된다 생각합니다.** 여기서 말하는 프로세스는 단순히 ‘QA Plan을 작성하고 테스트 케이스를 만들어 테스트를 한다’가 아닌 프로젝트에 투입된 순간부터 QA가 각 단계별로 수행할 수 있는 업무와 만들어지는 산출물들의 구성을 파악하고 있는지를 말합니다. 회사별로 프로젝트 진행은 다르더라도 QA가 수행하는 기본 프로세스는 동일합니다. 해당 직무의 업무 순서와 정의를 알고 있다면 어떤 프로젝트에 참여하던지 흔들리지 않고 본인의 역할을 해낼 수 있다 생각합니다.

마지막으로는 **스스로 나아가려는 의지가 필요합니다.** 알아서 모든 일을 하라는 의미가 아니고 품질 개선을 위해 스스로 다양한 방법을 시도하고 업무를 찾아서 할 수 있어야 한다는 의미입니다. 글을 시작할 때 언급했던 바와 같이 QA 업무는 결코 단순하지 않습니다. 소프트웨어 개발 환경이 발전함에 따라 품질을 높이기 위한 방법들도 다양해지고 빠르게 변화하고 있습니다. 틀에 박힌 테스트 방식이 아닌 새로운 방법들을 스스로 해보고 발전시키려는 의지가 필요하다 생각합니다.

위의 세 가지는 제가 면접관일 때나 지원자일 때 중요하게 생각하는 부분입니다. 그래서 면접을 보기 전에 QA 용어와 프로세스에 대해 다시 리마인드를 하고, 항상 배우려는 마인드 셋을 갖추려고 합니다. 저의 팁이라고 하기엔 거창한 거 같지만 이 팁이 QA 지원을 준비하거나 생각하시는 분들에게 작은 도움이라도 되길 바랍니다.

---

## 6. 끝으로

처음 쏘카 블로그 글 제안을 받았을 때 걱정이 앞섰습니다. 글을 잘 쓰는 것도 아니고 누군가에게 설명하는 것도 잘하지 못해 글 순서를 정하는 것부터 쉽지 않았습니다. 글도 생각한 것처럼 써지지 않아 다시 읽을 때마다 수정하고 있고, 글의 마지막을 작성하는 지금도 다시 읽을 때마다 계속 지웠다 썼다를 반복하고 있습니다. 여전히 이 글이 어떻게 보일까 걱정은 되지만 최선을 다해 글을 썼고,  제가 쏘카에서 보낸 3개월을 돌아보며 QA로서 스스로도 다시 한번 돌아 볼 수 있는 뜻깊은 시간이었습니다. 쏘카 블로그 글 작성을 제안해 주신 팀장님 감사드리고 응원해 주신 팀원들도 감사합니다. 

![img](/assets/images/QA/qa_8.png){: width="30%"}
*쏘카 10주년 기념으로 키카쿠브를 받았어요*

---

## * 참고 

- [https://brunch.co.kr/@210a51cb29764cb/2](https://brunch.co.kr/@210a51cb29764cb/2)
- [http://blog.illunex.com/202010105-2/](http://blog.illunex.com/202010105-2/)
- [https://neklo.com/what-is-quality-assurance-testing/](https://neklo.com/what-is-quality-assurance-testing/)
- [https://tech.devsisters.com/posts/not-enough-testcase/](https://tech.devsisters.com/posts/not-enough-testcase/)
- [https://brunch.co.kr/@hsoochun/13](https://brunch.co.kr/@hsoochun/13)
