## ifAreYouT 프로젝트 소개

- 티켓팅 서비스 프로젝트

### 개발 인원 및 기간

- 개발기간 : 2023/10/09 ~ 2023/10/27
- 개발 인원 : 프론트엔드 3명(이주은, 조영준, 김종완), 백엔드 5명(이현진, 이준호, 이재훈, 김정연, 남수한)

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React.js, Sass
> - Back-End : Node.js, express.js, typeORM, bcrypt, JWT, MySQL
> - Common : RESTful API

### convention

파일명은 PascalCase를 따릅니다.

import 순서
1.Hook
2.components
3.variable
4.scss
순으로 import합니다.

변수명에 따른 네이밍 규칙

#기본적으로는 camelCase를 따르지만 .env등 부득이하게 대문자로 export 해야할 경우에는 명사 사이에 \_ 를 사용하여 SNAKE_CASE를 사용합니다.

### scss ,css

className은 camelCase를 따릅니다.

css 속성 선언 순서는 Daum Site css 속성 선언 순서를 따릅니다.
<https://uxkm.io/publishing/css/03-cssMiddleclass/10-css_attr_rule#gsc.tab=0>

### branch

브랜치 이름은 기능 및 컴포넌트로 명합니다.

feature/기능요약
ex) feature/Login, feature/Main

깃 PR시 commit mesaage

// commit 메시지는 아래와 같이 나눠 작성합니다.
[feat] 제목 // 기능 추가
[fix] 제목 // 버그 수정
[refact] 제목 // 리팩토링
[style] 제목 // UI 수정
[etc] 제목 // 기타 수정 사항
