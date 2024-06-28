<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Merge 충돌 해결

_충돌 원인과 해결 방법에 대해 배워 봅시다._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## 반갑습니다.

Merge 충돌은 Github에서 두 사람이 같은 파일을 변경 할 때 발생하고, 이는 협업에서 아주 흔한 일입니다. 충돌을 해결하기 위해서는 어느정도 수고가 필요하지만, 두려워 할 일은 아닙니다. 이 연습은 단계적 학습을 통해 여러분이 merge 충돌 해결 방법을 배울 수 있도록 도와드립니다.

- **누구를 위한 연습인가요?**: 주니어 개발자, Github 처음 사용자, Git 처음 사용자, 학생, 관리자, 팀.
- **여러분이 배울 것**: merge 충돌에 대해서, merge 충돌 해결 방법, merge 충돌을 줄이는 방법.
- **여러분이 만들게 될 것**: 우리는 짧은 이력서 마크다운 파일을 사용할 것입니다.
- **전제 조건**: 이 연습을 진행하기 전에, 이 과정을 숙지하시기 바랍니다. [Introduction to GitHub](https://github.com/skills/introduction-to-github)
- **얼마나 걸리나요?**: 이 연습은 30분 이내로 완료할 수 있습니다.

이 연습에서 당신은:

1. Pull request를 생성하고
2. Merge 충돌을 해결하고
3. Merge 충돌을 유발하고
4. Pull request를 merge 할 것입니다.

### 이 연습을 시작하는 방법.

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'resolve-merge-conflicts',
  owner: '@me',
  name: 'skills-resolve-merge-conflicts',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![Start course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=ohjayho&template_name=resolve-merge-conflicts&owner=%40me&name=skills-resolve-merge-conflicts&description=My+clone+repository&visibility=public)

1. Start Course 버튼을 마우스 오른쪽 버튼으로 클릭하고, 새로운 탭으로 엽니다.
2. 열린 새 탭에서 여러분은 새로운 repo를 생성하게 됩니다.
   - 개인 계정이나, organization에서 repo를 자유롭게 생성해주세요.
   - repo는 private으로 생성 시 과금이 되기 때문에, public으로 생성하시길 권장드립니다. [Github Action 과금](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - 설정이 끝나셨으면 **Create repository** 버튼을 눌러 생성을 완료합니다.
4. Repo가 생성 된 후 약 20초 뒤에, 해당 페이지에서 새로고침을 합니다. 새로고침을 하게 되면 README의 내용이 바뀌게 되고, README의 내용에 따라 연습을 진행하시면 됩니다.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/resolve-merge-conflicts) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
