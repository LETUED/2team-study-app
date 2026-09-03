# members

브랜치 → PR → 검사 → 승인 → 병합이 잘 되는지 확인하는 자리입니다. 초대를 수락했다면 이 폴더에 자기소개 파일을 올려서 흐름을 한 번 완주해보세요.

## 하는 법

```bash
git switch main
git pull

git switch -c docs/intro-<영문이름>
```

`members/<영문이름>.md` 파일을 만들어 아래 내용을 채웁니다.

```markdown
# <이름>

- GitHub: <계정명>
- 담당: <02_역할배분.md 기준 담당 번호와 흐름>
- 한마디:
```

```bash
git add members/<영문이름>.md
git commit -m "docs: <이름> 자기소개 추가"
git push -u origin docs/intro-<영문이름>
```

push 후 GitHub에서 **Compare & pull request**로 PR을 만듭니다. `pull_request_template.md`가 자동으로 채워집니다.

## 확인할 것

- [ ] main에 직접 push하면 거부되는지 (`GH006` / `GH013` 계열 에러 뜨는지)
- [ ] PR을 만들면 `check` 워크플로가 자동으로 도는지
- [ ] 팀원 1명 이상의 Approve가 있어야 Merge 버튼이 활성화되는지
- [ ] 병합 후 `git pull`로 로컬에 반영되는지

파일명 규칙: `<영문이름>.md` (예: `dh.md`, `yj.md`). 실명 대신 영문 이니셜만 써도 됩니다.
