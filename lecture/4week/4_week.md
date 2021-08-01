
# 4주차

### 5.2 다이얼로그 page 184
#### 5.2.1 토스트(Toast)

Toast t = Toast.makeToast(this, "종료할려면 한번더 누르세요", Toast.LENGTH_SHORT);
t.show();

#### 5.2.2 알림창(AlertDialog)

AlertDialog.Builer builder = new AlertDialog.Builder(this);

builder.setIcon(android.R.drawable.ic_dialog_alert);
builder.setTitle("알림");
builder.setMessage("정말 종료하시겠습니까?");
builder.setPositiveButton("OK" , null);
builder.setNegativeButton("No" , null);

alertDialog = builder.create();
alertDialog.show();

*setCancelable() 뒤로가기 눌렀을때 창이 닫히지 않게 하기 위해



### UI 그리는 방법
  - xml을 이용해 ui 만들기
  - 자바소스에서 뷰를 그릴수 있다
  - 드래그를 통해서 ui 작성
