---
title: 온라인 호스팅 지침
permalink: index.html
layout: home
---

# MS-4008: 임원을 위한 Microsoft 365 Copilot 상호 작용 환경 

## 콘텐츠 디렉터리

이 과정의 데모는 액셀러레이터 키트 [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG) 데모를 기반으로 합니다.

이 교육을 제공하기 전에 데모를 숙지하는 것이 중요합니다. 여러 랩의 경우 샘플 문서와 미리 만든 Teams 모임 및 전자 메일을 활용합니다.

- [여기](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles)에서 모든 샘플 문서를 미리 다운로드합니다.
- [여기](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)에 있는 지침에 따라 Teams 모임 및 전자 메일 스레드를 설정합니다.
- 여기에 있는 상호 작용 환경을 숙지합니다.
    - 옵션 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - 옵션 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **NOTE:** 참가자에게 Microsoft 365 Copilot 라이선스가 없는 경우 [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE)에 있는 무료 상업용 버전 환경을 사용할 수 있습니다.

## 과정 설명

Microsoft 365 Copilot이 어떻게 업무 생산성을 높이고 혁신을 가속화하는지 알아봅니다. 오늘날의 비즈니스 리더를 위해 맞춤화된 이 환경은 상황별 Copilot 프롬프트 작성에 대한 인사이트를 제공하고 일상적인 워크플로에 원활하게 통합되는 실용적인 사용 사례 연습을 제공합니다.

이 전달의 주요 목표는 다음과 같습니다.

- 참가자에게 Microsoft 365 Copilot을 소개하고 효과적인 프롬프트 작성 방법을 가르칩니다.
- Office 앱에서 Microsoft 365 Copilot 시연(최대 3개의 데모)
- 상호 작용 환경을 통해 참가자 안내
- 참가자를 초대하여 모바일용 Microsoft Copilot을 다운로드 및 사용해 보도록 합니다.

## 과정 소요 시간(예상) 

| # | 항목                                 | 총 시간      |
|---|---------------------------------------|-----------------|
| 1 | Microsoft 365 Copilot 소개 | 10분    |
| 2 | 효과적인 프롬프트 작성에 대한 임원 가이드 | 30분      |
| 3 | Microsoft 365 Copilot 상호 작용 환경  | 20분      |
|   |                                       | **총 시간 60분** |


아래에는 각 데모의 하이퍼링크 목록이 나와 있습니다.

## 데모

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 데모 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
