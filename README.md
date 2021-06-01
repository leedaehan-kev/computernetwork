# 가위바위보 게임
## 주제
2021년 1학기 Network 조별과제로 가위바위보 게임이 가능한 홈페이지 RPSChampion(가명)을 만든다.
## 설치
- 만약 nodejs 모듈이 정상적으로 실행되지 않는다면 nodejs의  express, socketio 모듈을 재설치한다.
## 동작
#### 1. root폴더 터미널에서 다음과 같이 입력한다
```
node main.js
```

#### 2.1. `computernetwork/ngrok/ngrok.exe`를 실행한다
- ngrok이 제대로 실행되지 않을 경우 [이곳](https://ngrok.com/)에서 직접 설치한다. 가입은 필요하지 않다.
#### 2.2. `ngrok http 12000`를 입력한다.
- 포트 번호는 `main.js`에서 변경. 
#### 2.3 제공된 접속주소로 들어간다(Forwarding이라고 적혀있다.)