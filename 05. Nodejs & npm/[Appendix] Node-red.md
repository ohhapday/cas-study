# Node-red

## 소개
  - [제타위키](https://zetawiki.com/wiki/Node-RED)
  - 라이센스: 아파치 라이선스 2.0

## 설치
1. 프로젝트 폴더 생성: mkdir node-red-test
2. 설치: git clone https://github.com/node-red/node-red.git
2. 폴더 이동: cd node-red
2. node-red-dashboard 설치: npm i node-red-dashboard
3. npm run build
4. npm run start
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
