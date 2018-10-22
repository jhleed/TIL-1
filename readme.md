# TIL (Today I Learned)

학습 기록

### 2018.10.18 (목)

1. 지난 수업 복습 
- API, N-Screen, MSA

2. TCP/IP 와 UDP 공통점과 차이점
- 공통점
   * 인터넷에서 정보를 주고받는 통신 프로토콜
- 차이점
   * 정보를 주고 받는 방식    
   
TCP/IP | UDP 
---- | ----  
 연결형 | 비연결형 
 3wayhandshake | 
 [참고자료](https://t1.daumcdn.net/cfile/tistory/225A964D52F1BB6917) |

3. http : www상에서 정보를 주고받는 표준 프로토콜
- http의 구조   
   + Header : url, 메소드, 보안정보 등의 정보를 보내는 방식 정의     
   + Body   : 정보를 명시하는 곳 __(Payload)__
- http 정보 전달 방식   
    
  1. GET - 정보를 body에 담을수 없고 url에만 담을 수 있다. 데이터를 읽어오는 방법(DB값을 수정하지 않는다)
  2. POST - 데이터를 등록하는 방법
  3. PUT - 데이터를 수정,업데이트 하는 방법
  4. DELETE - 데이터를 삭제하는 방법

4. 해시 (프로그래머스)
- 해시는 Key-Value로 이루어져있다.
- 해시중에 HashMap은 Key-Value 값에 null을 허용하기 때문에 유용하게 쓰일 수 있다.
- 선언법    
  ```
  Map<String, Integer> pMap = new HashMap<>();  
  ```
- 데이터 저장 문법 : put
  ```
  pMap.put("유진",100);   // 위에 선언한 형식과 일치하도록 String과 Integer으로 데이터 저장
  ```
- 데이터 불러오는 문법 : get
  ```
  System.out.println(pMap.get("유진"));       // 이러면 100출력
  ```
  
