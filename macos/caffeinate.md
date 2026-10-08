# 잠자기 방지: caffeinate

긴 빌드나 다운로드 중 맥이 잠들지 않게 하려면:

```sh
caffeinate -dims          # Ctrl+C 할 때까지 유지
caffeinate -i make build  # 명령이 끝날 때까지만 유지
caffeinate -t 3600        # 1시간 동안 유지
```

- `-d`: 디스플레이 잠자기 방지
- `-i`: 시스템 유휴 잠자기 방지
- `-m`: 디스크 잠자기 방지
- `-s`: 전원 연결 시 시스템 잠자기 방지
