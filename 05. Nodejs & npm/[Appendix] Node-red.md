# Node-red

## 소개
  - [제타위키](https://zetawiki.com/wiki/Node-RED)
  - 라이센스: 아파치 라이선스 2.0

## 설치
1. 프로젝트 폴더 생성: mkdir node-red-test
2. 윈도우에서 실행법 https://nodered.org/docs/platforms/windows
2. 설치: npm install -g --unsafe-perm node-red
3. 실행: node-red
---
1. setting.js 수정
    - C:\Users\{사용자}}\.node-red
    - 81줄 `userDir: 'C:\\{임의폴더}\node-red-test'`
2. node-red-dashboard 설치: npm i node-red-dashboard
4. 실행: node-red
4. localhost:1880 접속 확인
3. localhost:1880/ui 접속 확인
---
1. inject 추가 > Repeat interval 5
3. function 추가 > Random number > `msg.payload = Math.round(Math.random()*100)`
4. chart 추가 > 추가 new ui_group > Name: Chart1 > Tab 추가 > X-axis 5 minutes
5. Deploy
6. localhost:1880/ui 접속 확인
6. gauge 추가 > Range Max 100
7. localhost:1880/ui 접속 확인

- #### 50% 먹고 개발 시작
