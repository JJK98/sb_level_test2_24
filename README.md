## 1차 요구사항 구현
- [X] 유저가 루트 url로 접속시에 게시글 리스트 페이지(http://주소:포트/article/list)가 나온다.
- [X] 리스트 페이지에서는 등록 버튼이 있고 버튼을 누르면 http://주소:포트/article/create 경로로 이동하고 등록 폼이 나온다.
- [X] 게시글 등록을 하면 http://주소:포트/article/create로 POST 요청을 보내어 DB에 해당 내용을 저장한다.
- [X] 게시글 등록이 되면 해당 게시글 리스트 페이지로 리다이렉트 된다. 페이지 URL 은 http://주소:포트/article/list 이다.
- [X] 리스트 페이지에서 해당 게시글을 클릭하면 상세페이지로 이동한다. 해당 경로는 http://주소:포트/article/detail/{id} 가 된다.
- [X] 게시글 상세 페이지에는 목록 버튼이 있다. 목록 버튼을 누르면 게시글 리스트 페이지로 이동하게 된다.

# 2차 요구사항
- [X] 게시글 상세페이지(http://주소:포트/article/detail/{id})에 수정 버튼이 있다. 수정 버튼을 누르면 게시글을 수정 할 수 있는 폼이나 오고 수정이 가능하다.
- [X] 게시글 상세페이지에 삭제 버튼이 있다. 삭제 버튼을 누르면 게시글이 삭제가 된다. 삭제 후 리스트 페이지로 리다이렉트 된다.
- [X] 모든 페이지 상단에 루트 디렉토리로 이동하는 버튼이 있다.(예: 로고)
- [X] 모든 페이지 상단에 로그인 상태 표시하는 버튼이 있다.(예: 로그인 / 로그아웃) 
- [X] 모든 페이지 회원가입 버튼이 있다. 버튼을 누르면 회원가입 폼으로 이동한다.
	- [X] 회원가입 폼은 유저ID, 닉네임, 비빌번호, 비밀번호 확인으로 구성된다. 회원가입 버튼을 누르면 데이터 검증 후 회원가입이 된다.
- [X] 로그인 버튼을 누르면 로그인 폼으로 이동한다. 
	- [X] 로그인 페이지는 사용자 유저ID과 비밀번호를 입력하는 폼으로 구성되고 로그인 버튼을 누르면 데이터 검증 후 로그인이 된다.
- [X] 로그아웃 버튼을 누르면 로그아웃이 된다.
- [X] 유저가 게시글 작성 및 수정  접근시 로그인 여부를 검사하고 본인 글에 대해서만 수정 / 삭제가 가능하다.
- [ ] (선택)메인페이지에 검색 기능이 구현되어야 한다. input 박스에 내용을 적고 검색 버튼을 누르면 해당 문자가 포함된 게시글이 리스트업 되어야 한다.
본인 글에 대해서만 수정 / 삭제가 가능하다.

## 미비사(선택)항 or 막힌 부분
- ...

## UI/UX (화면 캡처본을 복사 붙여 넣기, url 주소 나오도록)
- 게시글 리스트 페이지
- ![스크린샷(4)](https://github.com/user-attachments/assets/52aae78e-62f6-49cf-81cc-b8ca62cd9927)

- 게시글 등록 폼 페이지
- ![스크린샷(5)](https://github.com/user-attachments/assets/4e667b6d-b5f3-40df-9082-11c54f674f60)

- 게시글 상세 페이지
- ![image](https://github.com/user-attachments/assets/a7edab0f-93a9-4669-b90b-a0d9a45fe91d)
- ![image](https://github.com/user-attachments/assets/c90027a8-bfaa-4189-9ff5-13535271de34)

- 로그인 페이지
- ![image](https://github.com/user-attachments/assets/701c21f5-6d70-42de-a467-0316898244ff)

- 회원가입 페이지
- ![image](https://github.com/user-attachments/assets/7e9e5651-27ad-444d-9383-fc22b88f1e7f)

- (선택) 검색 페이지
