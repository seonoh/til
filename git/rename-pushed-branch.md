# 이미 push한 브랜치 이름 바꾸기

```sh
git branch -m old-name new-name        # 로컬 이름 변경
git push origin -u new-name            # 새 이름으로 push + upstream 설정
git push origin --delete old-name      # 원격의 옛 브랜치 삭제
```

현재 브랜치라면 `git branch -m new-name`처럼 옛 이름을 생략할 수 있다.
열려 있는 PR은 원격 브랜치를 삭제하면 닫히므로, GitHub 웹의 브랜치 이름 변경 기능을 쓰는 편이 PR을 유지하기 좋다.
