
# 4주차 - 교재참조

### 5.2 다이얼로그 page 184
#### 5.2.1 토스트(Toast)

Toast t = Toast.makeToast(this, "종료할려면 한번더 누르세요", Toast.LENGTH_SHORT);
t.show();

#### 5.2.2 알림창(AlertDialog)

AlertDialog.Builer builder = new AlertDialog.Builder(this);

builder.setIcon(android.R.drawable.ic_dialog_alert);</br>
builder.setTitle("알림");</br>
builder.setMessage("정말 종료하시겠습니까?");</br>
builder.setPositiveButton("OK" , null);</br>
builder.setNegativeButton("No" , null);</br>

alertDialog = builder.create();
alertDialog.show();

*setCancelable() 뒤로가기 눌렀을때 창이 닫히지 않게 하기 위해

## 형상관리란?
### 깃 회원가입
- 회원가입
- 저장소 만들기

### 깃 설정

1. Git 설치
- (https://git-scm.com/downloads)
- (https://coding-factory.tistory.com/245)

### 소스트리 다운로드
- (https://www.sourcetreeapp.com/)
### 소스트리 이용해 소스 커밋


