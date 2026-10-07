# 마지막 커밋 되돌리기

커밋 내용은 작업 트리에 남기고 커밋만 취소하려면:

```sh
git reset --soft HEAD~1
```

- `--soft`: 변경 사항이 staged 상태로 남는다.
- `--mixed`(기본값): 변경 사항이 unstaged 상태로 남는다.
- `--hard`: 변경 사항까지 모두 버린다. 복구가 어려우니 주의.

이미 push한 커밋이라면 `git revert HEAD`로 되돌리는 커밋을 새로 만드는 편이 안전하다.
