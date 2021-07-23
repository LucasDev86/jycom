

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
- 필요한 설계도이며 생성자, 필드, 메소드로 구성되어 있다. 클래스명은 파일명과 동일하다.

##### 클래스
- 설계도 또는 틀이라고 생각하면 된다. 클래스 이름은 처음 시작할때 대문자를 사용하도록 하고, 메소드의 경우에는</br>
- 소문자로 시작한다. 둘의 혼동을 막기 위해서 이 규칙을 지키는 것이 바람직하다.
- 클래스는 생성자, 멤버 변수(=필드)와 멤버 메소드로 구성되어 있으며 합쳐서 멤버라고 부른다.

```
public class Robot {

}
```


##### 객체
- 클래스를 가지고 있으며 new 연산자를 통해 객체를 생성해서 사용할 수 있다.



