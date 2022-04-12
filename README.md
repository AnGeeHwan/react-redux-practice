# webpack

- entry 지정된 자바스크립트 파일에서 부터 입력 읽어들임 ex) es6 파일
- module ex) es5로 변환해주는 Transpiler 셋팅
- plugins ex) console.log 와 주석등 제거하는 plugin 셋팅
- bundling 하면 순차적으로 실행 됨.
- output 구조로 출력시켜 줌

### webpack.config.js

- node 문법으로 작성해야함
- nodule.exports 를 기본적으로 사용하고 기본적인것들은 가이드해줌
- entry 어떤 자바스크립트 파일에서 시작할 거다라는 명시
- output 출력은 여러가지 정보들이 필요하여 객체로
- module
- plugins

## Babel

- bundle.js -React is not defined 에러 발생 이유
- 변환시에 React 기능을 사용하기 때문에 상단에
- /_ @jsx createElement _/ 예시처럼 추가해주면 정상동작한다.
