# 참여 규칙

## 브랜치

  <타입>/<작업내용>

  feat  기능 추가
  fix   결함 수정
  docs  문서
  chore 설정 · 정리

## 커밋 메시지

  <타입>: <내용>

  feat     기능 추가
  fix      결함 수정
  docs     문서
  chore    설정 · 빌드
  refactor 동작 변경 없는 개선
  test     테스트
  style    형식만 변경

## PR

- main 에는 직접 push 불가. 브랜치를 만들어 PR 로 요청
- PR 본문은 `.github/pull_request_template.md` 양식을 채움
- 병합 전 자동 검사(check) 통과 + 승인 1명 필요
- 관련 이슈가 있으면 본문에 `Closes #번호` 기재

## 리뷰

- 대상은 사람이 아니라 코드
- 근거를 남김 (취향이 아니라 이유)
- 이 PR 의 목적 범위 안에서만 의견
- 질문 형태로 남기는 것을 우선함 (예: "이 경우엔 어떻게 동작하나요?")
