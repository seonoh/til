# 새 파일까지 stash 하기

`git stash`는 기본적으로 추적 중인 파일만 저장한다. 새로 만든(untracked) 파일까지 넣으려면:

```sh
git stash -u        # --include-untracked
git stash -a        # --all, .gitignore 대상까지 포함
```

메시지를 붙여 두면 나중에 찾기 쉽다:

```sh
git stash push -u -m "로그인 폼 작업 중"
git stash list
```
