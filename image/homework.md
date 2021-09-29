
## 아래 요구사항에 맞게 구현하세요. 
## 깃허브 연동
github 
<br/>
Create a new repository
<br/>
Repository name : Login
<br/>
Description (optional) : 안드로이드 로그인 기능 테스트
<br/>
Add a README file 추가
<br/>

아이콘 다운로드<br/>
<img src="icon.PNG" />
<br/>
<img src="icon2.PNG" />

###  미니프로젝트 만들기
##

New Project
<br/>
Empty Activity<br/>
Name : Login<br/>
Package name :  com.jycom.login<br/>
Language : Java<br/>
<br/>
나머지 설정은 기존과 동일<br/>
<br/>

총 4개 Activity<br/>
1. IntroActivity 시작화면<br/>
### [인트로 화면]
<img src="int.PNG" width="320"/>  
* 이미지 사이즈
 - intro.PNG<br/> 
 -가로 : 200dp, 세로 : 150dp<br/>
* 시작하기 버튼(AppCompatButton) 
 -가로 : 300dp, 세로 : 40dp<br/>
 -배경색상 #878789<br/>
 -텍스트색상 #ffffff<br/>
<br/>  
2. LoginActivity 로그인 화면
### [로그인 화면]
<img src="login.PNG" width="320"/>  
* 이미지 사이즈 
 - icon.PNG<br/>
 -가로 : wrap_content, 세로 : wrap_content<br/>
* EditText
  - hint : 아이디<br/> 
  -가로 : match_parent, 세로 : wrap_content<br/>
* EditText
  - hint : 비밀번호<br/>
  -가로 : match_parent, 세로 : wrap_content<br/>
* 로그인 버튼 (AppCompatButton)
  -가로 : match_parent, 세로 : wrap_content<br/>
  -배경색상 : #E83C77<br/>
  -텍스트색상 : #ffffff<br/>
  -텍스트사이즈 : 15dp<br/>

* 회원가입 버튼 (AppCompatButton)
  -가로 : match_parent, 세로 : wrap_content<br/>
  -배경색상 : #FCD060<br/>
  -텍스트색상 : #000000<br/>
  -텍스트사이즈 : 15dp<br/>
<br/>
3. MainActivity 로그인 후 화면

### [메인 화면]
<img src="main.PNG" width="320"/>  

  - 오늘의 메뉴 & 오늘 수업시간표<br/>
  - 화면보고 비슷하게 작성<br/>
  - 칼라색은 #E83C77, #000000<br/>
<br/>
4. JoinActivity 회원가입 화면

<br/>
### [회원가입 화면]
<img src="join.PNG" width="320"/>  
  - EditText 높이는 45dp 고정<br/>
  * AppCompatButton 버튼 <br/>
    - 공통 배경색 #000000<br/>
    - 텍스트 색상 #FFFFFF<br/>


<br/>
### * 요구사항
- 앱시작시 액티비티 : IntroActivity<br/>
- IntroActivity 시작하기 버튼 클릭시 LoginActivity 실행<br/>
- LoginActivity 로그인 버튼 클릭시<br/>
  아이디 입력 안했을 경우 아이디를 입력해주세요 토스트 문구<br/>
  비밀번호 입력 안했을 경우 비밀번호를 입력해주세요 토스트 문구<br/>
  
  아이디 jycom,  비밀번호 1234 일 경우 MainActivity 실행<br/>
  아이디와 비밀번호가 틀리면 아이디와 비밀번호를 확인해주세요 토스트 문구<br/>
- LoginActivity 회원가입 클릭시 JoinActivity 실행<br/>
- JoinActivity 회원가입 클릭시 다이얼로그 실행<br/>
<br/>
### [팝업 클릭 후]
<img src="popup.PNG" width="320"/>
   
  
  
