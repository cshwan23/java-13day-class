# java-13day-class1
클래스 구조

>
30대초반 부터 공부시작
쉬는날 토요일 무조건 나갔다 회사출근 한번도 안 빠졌다.
젊었을 때 공부하란 얘기.
 
>
밥솥을 쌌는데 열로 쌀을데워서 회로 데이터의 흐름을 배운 것.(7일)
이제부터 배우는건
밥솥의 메뉴얼을 배우는 것과 똑같다
법칙이다. 다 암기다. 암기끼리 연결.
여기서부터 밀려버리면 끝난다.
 
>
착각)-로직에서 패턴으로 바꼈다. 패턴암기다.
암기력이 좋으면 개발을 더 잘할 수 있다. 수십억이 오가는 프로젝트에
자바기본서적이 올라가있으면 안된다. 구글링 홈페이지 접속 못한다. 
클라스 수업 들어가고 메모리 공간에 올라가야한다 이걸 객체라고 한다. 
 
>
자바에서 클라스란 속성변수와 메소드를 정의해놓은 일종의 틀.
클래스를 실행하면(객체화) 메모리에 올라간다.
(RAM 메모리공간이 클수록 많은 실행파일을 올려놓고 실행할 수 있으니까.)
그때부턴 클라스라 부르지 않고 객체라고 한다.
클라스(=객체의 전신) 객체와 클래스는 구조가 똑같다.
객체로 올라가면서 메모리 주소를 던져준다.
클래스는 파일로 존재 객체는 메모리공간으로 존재.
클래스였을땐 개발자가 주어진 데이터. 
클래스-객체 =저장공간이 다르다. (클래스 = 파일로존재 / 객체 = 메모리공간으로 존재)
클래스가 객체화하면서 개발자가 데이터를 메모리공간에 던져준다.
 
객체가 생성되는 목적은 메소드 호출이다. 그안의 로직(실행구문)들이 다 숨어있기 때문에
메소드를 호출.
최종목적은 그안의 메소드 호출이다(이득을 얻기위해 객체화)(그안의 실행구문이 숨어있다)
객체의 생성의 목적은 메소드 호출이다.
 
>
배열의 객체는 다량의 데이터를 관리하는것 
2차원배열을 대신하여 컬렉션을 많이 쓴다.
 
>
모든언어의 기본적인 문법.
오늘부터 배우는게 헌법이다. 메뉴얼끼리의 연관관계 .
상당히 어려운게 많다.외워야할 것 많다. 막상 쓰이는건 한정되어있다. 다 안쓴다.
솔루션회사는 자바를 시험문제 내면. 문법을 깊숙히 물어본다. 결론은 하란얘기.
실무를 하기위한게 아니라. 입사문제.
다포기하더라도 실무적인건 남겨놔야한다.
개발자가 갑이다. 초봉도 많이 올랐다. 개발자가 없어서.
 
>
생성자는 데이터를 주는 통로 = 생성자다.
주로 생성자를 통해서 갖고가는 . 이걸 초기화라고 한다.
 
클래스를 구성하는 2대멤버( 속성변수와 메소드)
3대맴버 (+생성자)
4대멤버 (+ 내부클라스)(=클래스 안의 또다른 클래스가 들어갈 수있다.)
 
>프레임웤 쓰는 최고의 목적
=> 유지보수
=>프로그램의 흐름의 주도권을 프레임워크가 갖고있는거야.
 
>
메소드 안에 선언된 변수 = 지역변수
속성변수는= 클래스 안 메소드 밖에 클라스 안에 선언된 변수.
속성변수와 지역변수의 차이점
서로의 위치가 다르다.(메소드안/메소드밖)
공통점은 기본형과 참조형 데이터를 갖고있다.

 
