# GraphQL Movie API
노마드코더 GraphQL Movie API 강좌

GraphQL?
---

- API용 언어
- 데이터베이스에서 SQL 스키마로 DB에 쿼리를 하고 받듯이 `GraphQL`로 서버에 요청하면 그 결과를 돌려줌
- 데이터 형식만 정의하기 때문에 특정 언어나 데이터 형식에 영향을 받지 않는다.
- 개발자가 DB에 원하는 데이터만 요청 가능
- 일반적으로 /user/ GET 할경우 모든 사용자 정보를 불러옴
- `GraphQL` 에서는 URL 체제가 없음

**설치사항**
```javascript
$ mkdir MovieQL // 폴더생성
$ cd MovieQL
$ yarn init
$ yarn add graphql-yoga // 모듈설치
$ yarn -g add nodemon // 실시간 리로드
$ yarn global add babel-cli
$ yarn global add babel-cli --ignore-engines
$ yarn add babel-cli babel-preset-env babel-preset-stage-3 --dev
$ yarn add node-fetch
```

```json
// pakage.json 추가
"scripts": {
    "start": "nodemon --exec babel-node index.js"
}
```

`$ yarn start`





