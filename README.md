# ⚫ GO - 기업연계 프로젝트

목차
------------
- 프로젝트 소개
- 개발기간
- 개발환경
- 배포주소
- 역할
- 상세페이지
- 프로젝트 후기

프로젝트 소개
------------
- GO는 바둑 교육 사이트 입니다.
- 국내 바둑인구 중 31% 이상은 60대 이상, 바둑학습을 가로막는 주요 요인으로는 '배울 기회가 없다', '규칙이 어렵다' 라고 합니다.
- 이러한 배경을 통해 바둑 대중화를 위한 학습인프라 구축이 필요하다 생각이 들어 만들게 되었습니다.
  
개발기간
------------
- 전체개발기간 : 2024.03.18 ~ 2024.04.23

개발환경
------------
- HTTP & CSS , JavaScript, JQuery, BootStrap
- Java, StringBoot, Thymeleaf, MyBatis
- MySql, RDS
- AWS EC2(ubuntu), Putty
- Github
  
배포주소
------------
15.164.10.145:8282/

역할
------------
- AWS EC2를 이용한 배포, RDS 설계
- 커뮤니티, 학습자 프로세스를 담당했습니다.

상세페이지
------------
### 커뮤니티 페이지
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/37fd03b7-c61d-4dd5-9a26-2aceb1f21f35)
- 커뮤니티 페이지 입니다.
- 최신순, 댓글순, 조회순 페이지 필터링이 가능하고, 검색을 통해 제목,작성자로 검색이 가능합니다
- 페이지네이션 기능
- 등록하기 버튼을 누르면 등록화면으로 갑니다.

### 커뮤니티 등록
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/243cf82e-ed26-4c18-bc26-a99437593f45)
- 커뮤니티 등록 페이지입니다.
- 작성자는 로그인한 사용자 시큐리티 권한에서 가져와서 사용했습니다.
- 파일업로드가 가능하고, 업로드 시 밑에 파일명이 보이게 했습니다.

### 커뮤니티 상세
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/89951a46-1c8d-4ea0-8cc2-a1e083aa838b)

- 커뮤니티 상세페이지 입니다.
- 조회수는 쿠키로 중복처리를 방지했습니다. (단순한 페이지 조회 번호를 쿠키로 사용해서 보안에 상관없다고 생각해 쿠키로 사용했습니다.)

### 파일다운로드
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/2da1caf7-2271-404b-969d-cf1eb49136d5)

- 업로드한 파일이 보이고 클릭시 다운로드가 가능합니다.

### 댓글
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/c55e1c41-cbee-41e1-a179-fffb2629f0a7)

- 댓글이 작성한 페이지 입니다.
- 댓글에는 답글이 작성가능합니다 (답글 작성시 부모댓글을 기억)
- 댓글 삭제시 답글이 있을경우 '삭제된 댓글 처리' (삭제 시 답글이 있을 경우 댓글상태를 변경)

### 그룹 신청 내역
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/57883b6d-45df-4f3a-bca1-f013bd5dca3b)

- 학습자가 신청한 그룹 신청 내역입니다. 교육자가 승낙시 'Y'로 변경이 되고 'Y'일 경우 그룹상세페이지로 접근이 가능합니다.

### 그룹 상세
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/bb89acd7-33f7-4e1a-9682-2fc36811a7e1)

- 그룹 상세 정보와 숙제, 자신의 질문내역을 확인이 가능합니다.

### 숙제제출
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/c1b25650-5122-4441-bacf-3595572834a0)

- 숙제가 생성시 내역에서 확인이 가능하고 제출이 가능합니다.

### 질문하기
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/ffb6c56f-3d5e-4d58-b7bc-52194c1a2668)

- 교육자에게 질문이 가능합니다.
- 교육자가 답변시 답변완료로 변경이 되고, 답변에 접근이 가능합니다.

### 답변보기
![image](https://github.com/kohyeonjin/project-wizian/assets/154486596/18f46849-54b4-42ac-897b-df55fccae055)

- 교욱자 답변 확인이 가능합니다.

프로젝트후기
------------
- 로컬에서만 개발을 하다가 서버 배포를 할 수 있어서 좋았다.
- 하지만 배포 과정에서 오류가 많이 발생해 고치느라 시간이 좀 소요가 됐다.
- 저번 프로젝트에서는 UI를 직접 제작을 했는데 이번에는 BootStrap을 커스터마이징을 해서 사용했다.
- 아직 Ajax 비동기처리를 사용해보지 못했다가 , 이번 프로젝트에서 적용을 할 수 있어서 좋았다.
- 저번 프로젝트에서는 Git 합치는 과정에서 문제가 많았는데, 이번에는 중간 중간 계속 합쳐보고 협업컨벤션을 정해놓고 해서 수월하게 진행이 됐다.
- 기능적인 부분에서 좀 더 추가를 했으면 하는 아쉬움이 있다.
