---
lab:
  title: 연습 제목
  module: Learn module title
---
<!--
Edit the metadata above to manage the list of exercises in the home page of the GitHub site that gets generated.
You can delete the module and edit index.md in the root of the repo to customize the display so that only the exercises are listed
To enable GitHub page publishing, edit the Page settings for the repo and publish from the main branch
-->

# 연습 제목 <!-- match title in metadata above (and Learn Exercise unit and ILT slide)-->

이 연습에서 다음을 수행합니다. <!-- provide a description of what they'll do and why it;s important -->

이 연습을 완료하는 데 약 **XX**분 정도 소요됩니다. <!-- update with estimated duration -->

## 시작하기 전에

<!--
Add steps to get the learner to the starting point" for the exercise.
This might be cloning the repo and running a script or performing some manual steps.
Only include this section if its necessary to do some pre-exercise setup AND the same setup steps are required for self-paced (on Learn) and managed (in hosted ILT lab profiles) scenarios. Otherwise delete this section.
If self-paced /ILT-specific setup steps are required, include them in the Learn "Exercise" unit from where they open this exercise and in the Skillable lab profile instructions before this markdown file is imported.
 -->

이 연습을 시작하기 전에 다음을 수행해야 합니다.

1. 단계 1
1. 2단계
1. 기타

## 작업 <!-- Change to an appropriate task title with an imperative verb phrase (e.g. "Do something") -->

먼저,

1. 1단계
1. 이 단계에는 `inline code formatting`의 예제가 포함되어 있는데, 이는 호스트형 Skillable 환경에서 [T] 링크를 생성하기 때문에 학습자가 무언가(코드뿐만 아니라 무엇이든)를 입력해야 할 때 사용됩니다.
1. 학습자가 웹 사이트를 열어야 하는 경우 링크(HTML GitHub 페이지를 클릭하여 열 수 있도록)와 코드 형식의 URL(호스트형 VM 브라우저에 입력할 수 있도록)을 모두 포함합니다. 예를 들어 "[Bing](https://www.bing.com) 웹사이트를 `https://www.bing.com`에서 엽니다"라고 입력합니다.
1. 학습자가 파일(또는 여러 개의 파일을 zip으로 묶은 파일)을 다운로드해야 하는 경우, 이 리포지토리의 Allfiles 폴더에 파일을 저장하고 다음과 같이 **원시** URL(`https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json`에서 [파일 이름](https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json) 다운로드)을 사용합니다.
1. 또는, 개발자를 대상 그룹으로 하는 경우, 더 적절하다고 판단되면 이 레포지토리를 복제하도록 안내할 수 있습니다.
1. 여러 줄 코드 블록을 포함해야 하는 경우 글머리 기호 목록 들여쓰기와 일치하도록 들여쓰기합니다.

    ```python
    # This is an example of an
    # indented code block.
    ```

1. 스크린샷을 포함해야 하는 경우 적절한 크기로 크기를 조정하세요(부분 스크린샷의 "일반" 형식 텍스트는 이 텍스트와 거의 같은 크기이므로 일반적으로 전체 애플리케이션 창의 스크린샷은 대략 800x600px 크기로 만드세요). 이미지를 **미디어** 하위 폴더에 저장하고 Markdown을 사용하여 페이지에 추가합니다(파일 및 폴더 이름은 대/소문자 구분을 사용한다는 점을 기억하세요). 이미지가 목록에 있는 경우 다음과 같이 들여쓰기합니다.

    ![애플리케이션의 스크린샷.](./Media/edge-copilot.png) 

1. 어떤 작업이 수행되는 이유를 설명하거나 추가 컨텍스트 또는 정보 링크를 제공해야 하는 경우 다음과 같은 메모를 사용합니다.

    > **참고**: 메모입니다.

1. 자기 주도적 랩 환경과 호스트형 랩 환경 간에 다를 수 있는 지침을 제공할 때 유연하게 대처하세요. 예시:
    - "Azure 자격 증명을 사용하여 로그인"(Learn 연습 페이지에서 개인 구독을 사용하거나 평가판을 만드는 Learn 관련 지침과 Skillable 랩 프로필에서 제공된 cloudslice 자격 증명을 사용하는 ILT 관련 지침이 있다고 가정)
    - "기존 리소스 그룹을 선택하거나 새 리소스 그룹을 만듭니다."(Skillable CS-R 클라우드를 사용하는 경우 학습자에게 사용해야 하는 리소스 그룹을 알려주는 메모를 랩 프로필에 포함했다고 가정)
    <!-- The key point is that this markdown file should be environment-agnostic - you need to provide explicit details of things that can vary OUTSIDE of this file (in the Learn exercise page or the Skillable lab profile instructions) -->
1. 기타

## 다음 

이제, ...

1. 단계 1
1. 2단계
1. 기타

## 하위 작업을 사용하는 작업

때로는 더 작은 단위로 작업을 나눌 수도 있습니다.

### 하위 작업 1

1. 단계 1
1. 2단계
1. 기타

### 하위 작업 2

1. 단계 1
1. 2단계
1. 기타

## 정리

<!-- Good practice - especially as self-paced learners will be using their own subscriptions -->
<!-- Delete this section if it is not needed -->

연습을 마쳤으므로 불필요한 리소스 사용을 방지하기 위해 만든 클라우드 리소스를 삭제해야 합니다.

1. 1단계
2. 기타
