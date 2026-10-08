# 터미널과 클립보드 주고받기

```sh
pbcopy < ~/.ssh/id_ed25519.pub   # 파일 내용을 클립보드로
git log -1 --format=%H | pbcopy  # 명령 출력을 클립보드로
pbpaste > snippet.txt            # 클립보드 내용을 파일로
pbpaste | wc -l                  # 클립보드 줄 수 세기
```

출력 끝 줄바꿈까지 복사되니, 필요하면 `tr -d '\n'`을 사이에 끼운다.
