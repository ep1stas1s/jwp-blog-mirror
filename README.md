# My Blog

## 1. 기능 구현

### 1.1. 게시판

### TODO
- 게시판 생성 기능
    - Article 유효성 확인

- 회원 등록/조회 기능
    - 회원가입페이지(signup.html)에서 POST /users 로 요청
    - Spring Data JPA를 이용하여 DB에 user 정보를 저장
    - 생성 후 로그인 화면으로 이동
    - 회원가입 시 아래의 회원가입 규칙을 지켜야 하고, 위반 시 사용자에게 알려준다.
    - 동일한 email로 중복가입을 할 수 없다.
    - 이름은 2~10자로 제한하며 숫자나 특수문자가 포함될 수 없다.
    - 비밀번호는 8자 이상의 소문자, 대문자, 숫자, 특수문자의 조합이다.
    - 비밀번호 확인 기능이 동작해야 한다.

- 회원 로그인 기능

- 회원정보 수정/탈퇴 기능

### DONE
- 게시판 생성 기능
    - Article 정의
    - Article-Edit 페이지 이동
    - Article 객체 생성
    - Article DB에 저장
    - Article 페이지 이동
    
- 게시글 조회 기능
    - ArticleId을 통한 페이지 조회 

- 게시글 수정 기능
    - ArticleId을 통해 조회한 정보를 수정

- 게시글 삭제 기능
    - ArticleId을 통해 조회된 글 삭제