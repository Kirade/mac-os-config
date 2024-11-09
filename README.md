# mac-os-config
Personal configurations for mac os

## Keyboard

### 키 반복 속도 설정
아래의 명령어를 입력한 뒤, 맥북을 재시작하면 적용된다.
숫자 값이 낮을수록 반복 속도가 빠르다.
```
echo "Set a blazingly fast keyboard repeat rate"
defaults write NSGlobalDomain KeyRepeat -int 2
	
echo "Set a shorter Delay until key repeat"
defaults write NSGlobalDomain InitialKeyRepeat -int 12
```
