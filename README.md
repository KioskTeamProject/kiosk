## 스타벅스 회원 전용 키오스크
========================

<img width="856" alt="Screen Shot 2023-04-14 at 7 03 18 PM" src="https://user-images.githubusercontent.com/122959190/232014926-4b607d95-8c08-4c45-b679-4644c323b672.png">

💻프로젝트 개요
------------------------
- 시중에 일정관리하는 웹캘린더는 많지만, 공부하는 사람들을 위한 스터디플래너는 마땅치 않은 상황에서 아이디어를 모색하기 시작했습니다.
- 모바일에서 사용가능한 스터디플래너 앱은 많지만, 주변에서 공부 중 핸드폰을 사용하니 집중력이 흐트러진다는 불편함을 호소하는 모습을 볼 수 있었습니다. 우리 팀은 이러한 불편함을 개선하고자, 웹을 통해 사용할 수 있는 스터디플래너를 구상하게 되었습니다.
<br/><br/><br/>

🖥 개발 환경
------------------------
![개발환경](/final/source/Stack.png)
<br/><br/><br/>


✏ 주요기능 및 담당
------------------------
> ### Calendar
> ##### 달력
> - 달력 좌, 우 스와이프 기능
> - 미니 캘린더로 날짜 비교 가능

##### 일정 추가 및 조회
- 오늘의 일정 확인 가능
- 이벤트 추가 가능 (일정명, 시간, 장소)
<br/>

### Todo list / Side menu - 조예원
1. 투두리스트의 html, css, js
2. 사이드메뉴의 html, css, js
3. 프레젠테이션
<br/><br/>
> #### 할일 추가
> - 할일 작성 기능 `html` `css`
> - 추가 버튼이나 엔터키를 누르면 작성한 할일이 하단 리스트에 추가되는 기능 `js`

> #### 할일 수정, 삭제
> - 할일 추가 시 우측에 수정, 삭제 버튼이 함께 생성되도록 구현 `css` `js`
> - 이미 작성해놓은 할일을 수정 `js`
> - 완료한 할일은 수정할 수 없음 `js`
> - 삭제 버튼을 눌러 할일을 삭제 `js`
> - 모두삭제 버튼을 통해 할일 리스트를 초기화 `js`

> #### 할일 진행률 표시 바
> - 할일 리스트를 클릭할 때마다, 할일 완료율을 %로 계산하여 프로그레스바가 새로고침됨 `css` `js`
> - 프로그레스바가 100%가 되면 커비가 밥을 먹는 애니메이션 동작 `css` `js`

> #### Side menu
> - 버튼을 클릭하여 사이드메뉴를 숨겼다가 펼치는 기능 `css`
> - 각 메뉴 hover 시 눈에 띄일 수 있는 애니메이션 부여 `css`


#### Reading list
####
- 독서 목록 추가 삭제 목록 가능  
- 목록 내용에 대한 메모 작성 기능
<br/>

#### Timer
####
- 디데이 설정 및 카운트 가능
- 포모도로 타이머 및 오늘의 공부시간 측정 스탑워치 가능
<br/><br/><br/>

👍 중앙 플래너만의 장점
------------------------
#### 효율 UP!
- 공부하는 사람들을 위해 필요한 기능을 한 곳에 모아두어 빠르고 효율적인 사용이 가능합니다.

#### 집중력 UP!
- 사용량이 많지 않거나, 쓸모 없는 기능을 제거했습니다.
- 최소한의 기능을 통해 편의성을 높이고 집중력이 흐트러지는 것을 방지합니다.

#### 심플한 UI
- 전체적인 UI 디자인을 심플하게 구성하여 사용 중의 혼란을 줄이고, 사용자의 경험을 극대화 시켰습니다.
<br/><br/><br/>

🔎 향후 업데이트 계획
------------------------
- 데이터 베이스와 연동하여 로그인 기능 추가
- 환경설정 기능 추가 (다크모드, 음력날짜 보기, 개인 프로필)
- 타이머에 기록된 공부 시간을 캘린더와 연동
- 캘린더와 투두리스트 간 오늘 할일 및 일정을 공유
