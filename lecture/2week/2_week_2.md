

#### TextView
- textStyle 문자열 효과
- autoLink : 자동링크 
- ex) https://www.naver.com 2@gmail.com 02-1234-3232
- maxLine : 최대 라인수
- ellipas


#### EditText
- innputType 
- hint

#### RadioButton

#### padding , layout_margin

#### visible 속성

#### Relativelayout
-뷰(위젯)간의 관계를 정의하여 뷰의 위치를 배치하는 상대적 레이아웃</br>
-이미 존재하는 뷰를 대상으로 새로운 뷰의 위치를 정하기 때문에 id가 필요하다</br>

layout_toLeftOf	 : 뷰(View)를 기준 뷰(Anchor View)의 왼쪽(Left)에 배치.</br>
layout_above	: 뷰(View)를 기준 뷰(Anchor View)의 위(Above)에 배치.</br>
layout_toRightOf	: 뷰(View)를 기준 뷰(Anchor View)의 오른쪽(Right)에 배치.</br>
layout_below	: 뷰(View)를 기준 뷰(Anchor View)의 아래(Below)에 배치.</br>
layout_toStartOf	: 뷰(View)를 기준 뷰(Anchor View)의 시작(Start)에 배치.</br>
layout_toEndOf	: 뷰(View)를 기준 뷰(Anchor View)의 끝(End)에 배치.</br>
layout_alignParentLeft	: 뷰(View)를 부모(Parent) 영역 내에서 왼쪽(Left)에 배치.</br>
layout_alignParentTop	: 뷰(View)를 부모(Parent) 영역 내에서 위쪽(Top)에 배치.</br>
layout_alignParentRight	: 뷰(View)를 부모(Parent) 영역 내에서 오른쪽(Right)에 배치.</br>
layout_alignParentBottom	: 뷰(View)를 부모(Parent) 영역 내에서 아래쪽(Bottom)에 배치.</br>
layout_centerHorizontal	: 뷰(View)를 부모(Parent) 영역의 가로 방향 가운데 배치.</br>
layout_centerVertical	: 뷰(View)를 부모(Parent) 영역의 세로 방향 가운데 배치.</br>
layout_centerInParent	: 뷰(View)를 부모(Parent) 영역의 정 중앙(center)에 배치.</br>
layout_alignParentStart	: 뷰(View)를 부모(Parent) 영역의 시작 지점(Start)에 배치.</br>
layout_alignParentEnd	: 뷰(View)를 부모(Parent) 영역의 끝 지점(End)에 배치.</br>
layout_alignLeft	: 뷰(View)의 왼쪽(Left)을 기준 뷰(View)의 왼쪽(Left)에 맞춤.</br>
layout_alignTop	: 뷰(View)의 위(Top)를 기준 뷰(View)의 위(Top)에 맞춤.</br>
layout_alignRight	: 뷰(View)의 오른쪽(Right)를 기준 뷰(View)의 오른쪽(Right)에 맞춤.</br>
layout_alignBottom	: 뷰(View)의 아래(Bottom)를 기준 뷰(View)의 아래(Bottom)에 맞춤.</br>
layout_alignBaseline	: 뷰(View)의 폰트 기준선(Baseline)을 기준 뷰(View)의 폰트 기준선(Baseline)에 맞춤.</br>

#### CostraintLayout
- Relativelayout과 비슷하며 개발자가 쉽게 UI를 2016년에 발표한 레이아웃.


### 자바 문법
#### 클래스 개념
- 자바의 기본 단위는 클래스로 이루어져 있고 클래스는 객체를 생성하는데</br>
- 필요한 설계도이며 생성자, 필드, 메소드로 구성되어 있다. 클래스명은 파일명과 동일하다.</br>

##### 클래스
- 설계도 또는 틀이라고 생각하면 된다. 클래스 이름은 처음 시작할때 대문자를 사용하도록 하고, 메소드의 경우에는</br>
- 소문자로 시작한다. 둘의 혼동을 막기 위해서 이 규칙을 지키는 것이 바람직하다.</br>
- 클래스는 생성자, 멤버 변수(=필드)와 멤버 메소드로 구성되어 있으며 합쳐서 멤버라고 부른다.</br>

```
public class Robot {

}
```

클래스 이름이 Robot이며 대문자로 시작한다.</br>
메소드와 다르게 소괄호 ()를 쓰지 않는다.</br>
클래스 앞에 쓰인 public은 다른 클래스에서도 사용할 수 있도록 공개되었다는 뜻이다.</br>

##### 객체
- 클래스를 가지고 있으며 new 연산자를 통해 객체를 생성해서 사용할 수 있다.</br>


```
void moveRight(){

}
```
메소드의 이름은 소문자로 시작하며, 메소드 앞에는 메소드가 리턴하는 자료형태를 적어야 한다.</br>
void는 텅 빙어있다는 뜻으로 moveRight 메소드는 반환값이 없다는 뜻이다.</br>
메소드는 메소드 이름 다음에 소괄호를 사용해야 하고, 클래스 안에서 사용한다.</br>

##### 한눈에 보는 클래스 구조
- class 키워드 다음에 대문자로 시작하는 클래스 이름을 적는다.</br>
- 메소드와는 달리 클래스 이름 뒤에는 소괄호를 사용하지 않고 중괄호를 바로 사용해서 클래스를 만든다.</br>
- 클래스는 생성자, 멤버변수(=필드) 그리고 멤버 메소드로 구성된다.

```
public class Robot {
  // 멤버변수, 전역변수
  int x,y;
  int power;
  int price;
  Strinng name;
  
    // 생성자 - 멤버 변수 초기화시 사용, 처음 객체 생성시 한번 실행
    Robot(int x, int y, int price, String name) {
      this.x = x;
      this.y = y;
      this.price = price;
      this.name = name;
    }

    // 멤버 메소드 : 객체의 동작을 나타낸다. 메소드 따로 사용은 불가능하며 클래스 안에서만 사용가능
    void moveRight() {
        x += 5; // x 값을 5만큼 증가시키기
    }
    
    void moveLeft() {
        x -= 5; // x 값을 5만큼 감소시키기
    }
}
```

- 클래스는 필드와 메소드들의 집합이라고 정의할 수 있다.</br>
- 멤버 변수는 자료형과 변수 이름으로 이루어져 있으며, 변수에 자료값을 담을 수 있다.</br>
- 예를 들어 멤버 변수 int x = 3; 이라고 적으면 x라는 변수에 3이라는 값이 저장된다.</br>
- int는 자료형을 의미하며 모든 문장의 끝은 세미콜론(;)으로 끝난다.
- //은 주석으로서 코두 설명을 돕는 것으로 프로그램에 영향을 주지 않는다.

#### 메소드 이해하기
- c언어 사용하는 함수는 메소드와 유사하다.</br>
- 메소드의 경우는 클래스 안에서 사용된다는 점에서 차이가 있다.</br>
- 변수는 어떤 값(속성)으르 저장하는 것이라면 메소드는 어떤 기능(동작)을 한다고 생각하면 된다.</br>
- 메소드는 입력을 받아서 처리결과를 반환하는 역할을 한다(입력 값이 없을 수도 있고 반환되는 처리결과 값도 없을 수도 있다.)</br>
```
  int add(int x, int y){
    return x+y;
  }
  
  add(100,200);
```
  
- add라는 이름을 가진 메소드는 앞에 int가 존재한다.</br>
- 이 메소드는 반환하는 데이터가 존재하고 그 데이터가 정수형이라는 것을 의미하며,</br>
- return을 사용해서 int형 값을 반환한다. 만약 반환하는 값이 없는 경우 return이 필요가 없으며 반환 타입 int</br>
- 대신에 반환하는 값이 없다는 void(비어있는)를 메소드명 앞에 적으면 된다.</br>

#### 메소드 구조
```
int showMe(int x, int y){
  return x+y;
}
```

- return 값이 없는 경우 반환 타입에 void를 써야 한다. 반환 타입이 void가 아닌 경우에</br>
- 메소드 안에는 return이 반드시 들어가야 한다.

#### 변수
- 변수는 데이터를 저장하는 그릇이라고 생각하면 된다.</br>
- 변수 타입에 따라 변수는 다양한 데이터를 담을 수 있다. 예를 들어 정수를 담을 수 있는 변수 타입에는</br>
- byte, short, int, long이 있다.
- int (변수 타입 = 자료형) x(변수 이름(=변수명));
- 변수명이 x인 변수 선언

#### 변수의 초기화
```
  int x=10; // 변수 x에 10을 넣는다.
            // x = 는 대입연산자로서 오른쪽에 있는 값을 왼쪽에 넣는다.
            
```

- == 는 같다는 의미이고, = 는 오른쪽에 있는 값을 왼쪽에 대입하라는 뜻이다.

#### 변수의 종류
</br>

##### 문자형
- char : 한글자만 입력 가능
- String : 여러글자 (문자열) 입력 가능
</br>

##### 정수형
- byte : -127 ~ 127까지 입력 가능
- short : -32768에서 32767까지 입력 가능
- int : 약 -21억에서 약 21억까지 입력 가능
- long : -2(63) 에서 2(62) -1 까지 입력 가능(매우 큰 수)
</br>

##### 실수형
- float : 실수를 입력
- double : float 형보다 많이 쓰이며 더 정확한 실수를 처리 가능
</br>

##### 불리언형
- boolean : true or false
-
