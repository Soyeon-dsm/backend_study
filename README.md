# java

『final』

​	final의 정의는 entity(객체)가 딱 한 번 할당될 수 있음을 의미한다.

​	상수와 비슷한 개념으로, c의 const와 유사하다.

​	final 필드(변수와 유사한 개념) : final (타입) (변수이름) 으로 선언한다. 꼭 초기화 해줘야한다.

​	final 메소드 :  (접근제어) final (반환형) (이름) 으로 선언한다. 상속받은 자식이 재정의할 수 없다.

​	final 클래스 : final class (이름)으로 선언한다. 

『interface』

​	일종의 추상 클래스이다. 추상 클래스보다 추상화 정도가 높음.

​	추상클래스와 달리 일반메소드와 일반 멤버 변수를 포함할 수 없다.

​	메소드는 public abtract, 변수는 public static final이어야 함. 생략가능

​	단,  static 메소드와 default 메소드 사용 가능.

​	abtract : 추상메소드, 자식클래스에서 무조건 재정의 해야함.

​	default : 기본제공메소드, 자식클래스에서 재정의 하지 않아도 사용 가능, 재정의 해도 됨.

​	static : 객체의 생성없이 접근 가능한 메소드, static이 없는 변수에는 접근 불가능하다.

『생성자』

​	c++과 같이 리턴값 x, 반환형 x, 이름이 클래스와 같음, 오버로딩가능.

​	c++과 다른점 : 소멸자x(jvm에서 자동으로 해줌)

​	lombok의 생성자 어노테이션 

​	 -@NoArgsConstructor : 기본생성자

​	 -@RequiredArgsConstructor : 초기화 되지 않은 변수를 포함한 생성자생성

​	 -@AllArgsCOnstructor : 모든 변수를 포함한 생성자생성

『』

『』

『』

『』
