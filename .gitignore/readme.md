# TIL (Today I Learned)

학습 기록

### 2018.10.06

1. 지난 수업 복습 ( why! git - github 란 무엇인가? )

2. API를 사용하지 않으면 ( why? API를 사용하는 이유)
```
N - Screen 때문 
사용자-DB직접 연결. 
때문에 동일한 프로그램을 사용하는 웹, 어플리케이션, 윈도우 어플리케이션 등 Screen이 늘어날 때마다 로직을 일일이 정의한다.때문에 로직이 수정될 때마다 똑같은 로직인데도 로직이 여러개이므로 같은 수정을 여러번 반복해야함.
```
3. API를 사용하면 
```
사용자-API-DB연결. 
로직을 API에 설정해두고, 여러 Screen에서는 이 API만 호출하여 DB와 연동이 된다. 여러 Screen을 사용해도 로직이 수정되었을때 한번만 수정해도 된다는 간편함이 있다.  
```
3. Rest API
API에는 종류가 많은데 그 중 web API(API 중 약 90프로 차지) 와 RestAPI가 있는데 그 중 RestAPI를 공부할 예정.
기업에서 많이 사용하기 때문!

4. 그럼, http는 무엇일까?
http는 말그대로 p 프로토콜이다. 웹 표준 프로토콜. http의 메소드는 get 방식과 post방식이 있다.
tcp/ip는 통신을 어떻게? 어느 방식으로? 할 것인지에 대하여 규정해 놓은 것.
      
5. MSA란?
기능별로 API를 구분해 놓은 것. 대표적으로 Amazon, google, facebook등이 있다.
서비스 배포시 시간이 적게 걸리는 장점이있다.

6. API 만들어보기
IntelliJ를 이용하여 New - Project - Spring - core(Lombok),Web (web),SQL(mySQL) 순으로 프로젝트 생성

7. 포트폴리오 
