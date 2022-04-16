# ESLint

- 코드 작성 규칙을 정의하고 관리를 도와주는 라이브러리
- 코드의 포맷 뿐만 아니라 코드의 오류도 찾아낼 수 있다
  - `no-undef`, ts type error 등등
- 코드의 품질 유지에 관련된 규칙을 사용할 수 있다
  - `no-unused-vars`, `no-console`
- airbnb 규칙 등등 널리 사용되는 규칙들을 쉽게 적용할 수 있음

```sh
# 설치
npm install eslint --save-dev
# 프로젝트에 세팅하기
npx eslint --init
```

# Prettier

- 코드를 규칙에 맞게 고쳐주는 code formatting tool
- 코드의 semantic은 고려하지 않고 오직 코드의 모양만 고려함
- 코드 작성만하고 저장하면 바로 format 해주기 때문에 널리 사용됨
- VSCode에서는 extension 으로 설치할 수 있음

# 공부해볼 것

- commit, push 전에 코드 확인하도록 하려면 어떻게 해야하지?
- eslint 커스터마이즈를 도전해보자!
