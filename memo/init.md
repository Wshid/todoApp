## init.md
- mac 환경에서 `expo-cli` 환경 설치를 진행한다.

### 기존 node 및 npm update
```bash
brew update
brew upgrade node
npm install -g npm
```

### expo-cli 설치
- https://expo.io/tools
```bash
npm install expo-cli --global
```

### 프로젝트 생성 및 실행
```bash
expo init todoapp
cd todoapp
yarn start
```
- 실행 이후, 터미널 상에 QR 코드 혹은
- 웹 화면으로 내용이 출력됨
