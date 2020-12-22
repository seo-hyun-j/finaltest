# 취지 & 설명
- For My Day는 일정을 관리하고, 그날의 일정을 todolist로 보여주고 그날의 일기까지 쓸 수 있는 페이지이다.
- 홈페이지에서 일정 추가하기가 가능하며 이는 캘린더와 todo list에 표시된다.
- 그날의 일기는 모달을 통해서 쓸 수 있다.

# 기술 설명
- 프론트엔드 : HTML, CSS, Java Script, Bootstrap
- 백엔드 : node js
- fullcalendar javascript를 이용하여 캘린더를 구현하고, bootstrap을 이용하여 반응형 웹을 구현하였다.

# 어려웠던 점
- 이 페이지는 DB와 연동되어 일정을 추가하고 이 추가된 일정이 저장되어야 유용한데 DB연결을 시도하는 와중에 어려움이 존재하여 해당 부분까지는 나가지 못하였다.
- 일정 추가하는 부분에 있어서도 입력을 주고 DB에 업로드해주고 받아오는 방식으로 해주어야 하는데 일정의 타이틀을 줌에 있어서 어려움을 겪었다.
- 해당 날짜마다 클래스를 주어 background-color를 주었는데 캘린더의 core css가 우선순위로 적용되어 !important로 강제로 했음에도  나타나지않았다.

# 추후에 보완할 것들
- DB연동 스케줄 관리
- 다이어리 게시판 페이지 구성 
- 로그인과 회원가입을 이용한 기능 추가
