<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 2단계: Merge 충돌 해결

_좋은 시작입니다! 이제 merge 충돌에 대해 좀 더 깊게 들어가 봅시다. :mag:_

겁날 수 있지만, 겁먹을 필요는 없습니다. 똑똑한 Git이 merge를 도와주기 때문이죠! Git은 사람에게 오로지 어떻게 해결할 지만 묻습니다. [충돌 해결](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line). 때때로, merge 충돌을 해결하는 최고의 방법은 두 브랜치의 내용을 모두 추가하거나, 심지어는 완전히 새로운 내용을 추가하는 것입니다! 바로 이런 점 때문에 Git이 사람에게 코드를 살펴보게하고, 올바른 수정을 하도록 합니다.

### :keyboard: 작업: merge 충돌을 해결하세요.

1. 여러분이 생성한 Pull request를 열어보세요. merge 충돌을 발생시켜 두었습니다! 겁먹지 마세요!
1. 해당 페이지 아랫 부분에 "This branch has conflicts that must be resolved" 메세지 아래에 **Resolve conflicts** 버튼을 클릭하세요.
1. `<<<<<<< my-resume`로 시작하고 `>>>>>>> main`로 끝나는 부분을 확인해보세요. Git이 충돌이 발생한 부분을 보여주기 위해 표시한 마커입니다.
1. main 브랜치의 모든 수정 사항을 제거하기 위해 `=======`과 `>>>>>>> main` 사이의 모든 내용을 지워줍니다.
1. 이제는 다음과 같은 모든 충돌 마커를 지웁시다. :
   ```
   <<<<<<< my-resume
   =======
   >>>>>>> main
   ```
1. merge 충돌 마커들을 지웠으면, **Mark as resolved**를 클릭합니다.
1. 마지막으로, **Commit merge**를 클릭합니다.
1. 20초 후에 이 페이지를 새로고침 하면, [GitHub Actions](https://docs.github.com/en/actions)이 자동으로 다음 단계로 안내합니다.
