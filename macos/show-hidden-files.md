# Finder에서 숨김 파일 보기

Finder 창에서 단축키로 바로 토글할 수 있다.

```
Cmd + Shift + .
```

항상 보이게 하려면 터미널에서:

```sh
defaults write com.apple.finder AppleShowAllFiles -bool true
killall Finder
```

원래대로 돌리려면 `true`를 `false`로 바꿔 같은 명령을 실행한다.
