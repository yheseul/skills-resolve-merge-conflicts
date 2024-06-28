<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 3단계: 충돌을 유발해보세요.

_잘하셨습니다! merge 충돌을 해결하셨군요! :tada:_

충돌을 해결하더라도 pull request가 자동으로 Github에 merge 되지는 않습니다. 대신에, 충돌 해결 상태를 merge commit에 저장하고, 여러분과 여러분 팀이 계속 작업할 수 있도록 합니다. 충돌을 해결하기 위해, Github은 _reverse merge_라는 것을 합니다. 이는 `main` 브랜치의 변경 사항이 `my-resume`에 merge된 것을 말합니다. reverse merge에 의해 오직 `my-resume` 브랜치만 업데이트 됩니다. 이는 main 브랜치에 merge 하기 전에 여러분의 브랜치에서 미리 테스트 해볼 수 있도록 합니다.

이제, 좀 더 악랄하게 해봅시다. (온전히 여러분의 학습을 위해서!!)

### :keyboard: 작업: 직접 충돌을 유발해 봅시다.

현재 상태는 `references.md`라는 파일을 main 브랜치에 push 했지만, `my-resume` 브랜치에는 업데이트 하지 않은 상태입니다.

1. `my-resume` 브랜치를 여세요.
1. `Add file` 드롭다운 메뉴를 누르고 `Create new file`을 클릭합니다.
1. 충돌을 일으키기 위해 파일의 이름을 `references.md`로 합니다.
1. main 브랜치에 있는 `references.md`와 다르게 내용을 자유롭게 작성합니다.
1. `Commit changes`를 클릭하고, commit 메세지를 작성합니다.
1. "Commit directly to the `my-resume` branch" 옵션이 선택되어있는지 확인하고, **Commit changes** 버튼을 클릭합니다.
1. 20초 후에 이 페이지를 새로고침 하면, [GitHub Actions](https://docs.github.com/en/actions) 이 자동으로 다음 단계로 안내합니다.
