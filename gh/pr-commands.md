# gh CLI로 PR 다루기

```sh
gh pr create -t "제목" -b "본문"      # PR 생성
gh pr status                         # 내 PR과 리뷰 요청 한눈에 보기
gh pr checkout 123                   # PR 브랜치로 바로 전환
gh pr diff 123                       # 변경 내용 보기
gh pr merge 123 --squash --delete-branch
```

여러 저장소에 걸친 내 PR은 `gh search prs --author @me --state open`으로 찾는다.
