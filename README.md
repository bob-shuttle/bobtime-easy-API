# 개요
밥탐이지(bobtime-easy) 서비스의 API 명세입니다.
OpenAPI 3.0 명세를 yaml 형식으로 정의합니다.
Prism을 통해 mocking된 응답을 받아볼 수 있습니다.
서버를 구현하기 전에 테스트가 가능하기 때문에, 즉 병렬적 개발을 위해 사용합니다.

# 사용법
- node.js를 설치해야 실행할 수 있습니다. 설치하지 않아도 실행할 수 있는 환경에 대해 고민해보고 있습니다(동진).
## swagger-ui
- 작성된 파일을 UI로 보여줍니다.
  1. 해당 레포지토리를 클론한 후 `npm i`
  2. `npm run docs` 실행
  3. http://127.0.0.1:3000/api-docs 에서 확인

## Prism
- 작성된 파일 내 예시 데이터를 이용해 API mock 서버를 실행합니다.
  1. 해당 레포지토리를 클론한 후 `npm i`
  2. `npm run prism` 실행
  3. http://0.0.0.0:3000/ 에 엔드포인트를 붙여서 http request를 전송하면 예시 응답 반환