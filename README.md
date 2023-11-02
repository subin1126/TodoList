# 주제 : 간단한 투두리스트와 캘린더 띄우기 
<br/>
사용 : React,css, fullCalendar 라이브러리, google api (공휴일 연동)
<br/>
<br/>

1. 좌측에는 full Calendar 라이브러리를 사용하여 캘린더를 띄웠습니다.
- 구글 캘린더 api와 연동하여 공휴일을 띄우고, 원하는 날짜에 event를 띄웠습니다.
2. 우측에는 투두리스트를 구현하여 띄웠습니다.
- useState를 사용하여 입력된 할일들을 list로 나타내줄 상태, 입력받는 input 상태를 받습니다.
- useMemo를 사용하여 할일을 8개이상 입력하면 더이상 입력할 수 없게하며, 경고 div를 띄웁니다.
- 완료 버튼을 누르면 할일 내용위로 줄이 그어지는 css를 적용했습니다.
- 다시 완료 버튼을 누르면 그어진 줄이 사라집니다.
- 삭제 버튼을 누르면 list에서 삭제됩니다.


<p align='center'>
  <img src='https://github.com/subin1126/TodoList/assets/137139810/f63683ae-d13f-4e5c-97db-58b74a74b182'>
</p>


<br/>
앞으로 추가하고 싶은 부분
<br/>
1. 사용자가 입력한 투두리스트를 캘린더에 띄우기
<br/>
2. css 보완하기

