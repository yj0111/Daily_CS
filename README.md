# Daily_CS 

## Day 1 
### GET 방식과 POST 방식의 차이<br>
질문. GET방식과 POST방식의 차이에 대하여 설명하세요.<br>

답변   
 - GET방식과 POST방식의 가장 큰 차이점은 프론트엔드에서 백엔드로 데이터를 전송할 때 데이터를 헤더에 담아 전달(GET)하느냐 바디에 담아 전달(POST)하느냐의 차이입니다.<br>
 - POST방식의 경우 데이터를 바디에 넣어 보내기 때문에 기본적으로 암호화해서 전달하지만 GET방식은 암호화하지 않습니다.<br>
 - POST방식은 GET방식보다 상대적으로 큰 데이터를 전송할 수 있어서 큰 데이터를 전송할 때에는 POST방식을 사용합니다.<br>


## Day 2 
### HTTP와 HTTPS의 차이<br>
질문. HTTP와 HTTPS의 차이에 대하여 설명하세요.<br>

답변  
 - http와 https의 차이는 서버와 클라이언트 사이에 전송되는 데이터를 암호화 하느냐 그렇지 않느냐의 차이입니다. <br>
 - https는 서버와 클라이언트 사이의 모든 데이터를 암호화 하여 전송하기 때문에 보안에 강합니다.<br>
 - 하지만 암호화하는 시간이 더 걸리기 때문에 상대적으로 속도가 느리다는 단점이 있습니다.<br>

### 정규화<br>
질문. 정규화에 대하여 설명하세요.<br>

답변  
 - 관게형 데이터베이스의 설계에서 중복을 최소화하게 데이터를 구조화하는 프로세스입니다.<br>

### 반정규화<br>
질문. 반정규화에 대하여 간단하게 설명하세요.<br>

답변  
 - 데이터베이스의 성능 향상을 위하여 데이터 중복을 허용하고 조인을 줄이는 데이터베이스 성능향상 방법입니다. <br>
 
## Day 3
### SPA란?<br>
질문. SPA에 대하여 설명하세요.<br>

답변  
 - SPA :Single page application
 - 기존 웹페이지를 개발할 때에는 각각의 페이지마다 뷰(View)파일을 가졌다면 SPA의 구조는  <br>
   하나의 뷰(View)파일에 컴포넌트를 배치하는 방식으로 페이지를 구성하는 개념 입니다. <br>


## Day 4
### ORM이란??<br>
질문. ORM에 대하여 설명하세요.<br>

답변  
 - ORM : Object Relational Mapping의 약자로
 - 기존에는 SQL문을 사용하여 데이터베이스를 제어 하였다면 <br>
    ORM은 객체를 데이터베이스와 직접 맵핑하여 제어하는 개념 <br>

## Day 5
### framework이란?<br>
질문. framework에 대하여 설명하세요.<br>
답변
 - 일반적으로 소프트웨어의 전체적인 구조를 재사용과 확장, 유지보수가 유용하도록 미리 설계해둔 것.<br>

## Day 6
### MVC패턴이란?<br>
질문. MVC패턴에 대하여 설명하세요.<br>
답변
 - MVC패턴이란 애플리케이션의 구조를 Model, View, Controller로 나누어 설계하는 방법을 말합니다. <br>
   Model은 데이터를 처리하는 영역이며, <br>
   View는 사용자에게 보여질 화면을 처리하는 영역이고,<br>
   Controller는 사용자의 요청을 처리하는 영역을 말합니다.<br>

## Day 7
### Rest의 개념이란?<br>
질문. REST에 대해 설명하세요.<br>
답변
  -> REST란 Representational State Transfer의 약자로 자원을 이름으로 구분하여 
  해당 자원의 상태를 주고 받는 것을 말합니다.
  
  HTTP URI를 통해 자원을 명시하고 
  HTTP Method를 통해 해당 자원에 대한 상태를 주고 받는 방식을 말합니다.
 - url : http://www.google.co.kr:80/hakawati/
 - uri : http://www.google.co.kr:80/hakawati/uri.phhp?url=urn=#Rnfwoa


## Day 8
### 프레임워크 vs 라이브러리<br>
질문. Vue(프레임워크)와 React(라이브러리)의 차이에 대해서 설명해 보세요<br>
답변
 > 프레임워크는 소프트웨어의 구조를 설계해둔 것이고 라이브러리는 기능을 구현해둔 것입니다.<br>
   프로임워크는 구조를 설계한 것이기 때문에 개발자가 프레임워크의 구조에 맞게 프로그래밍 해야하지만<br>
   라이브러리는 기능을 구현해둔 것이기 때문에 개발자는 라이브러리를 활용하여 자유롭게 개발할 수 있습니다.<br>
