# Final Team Project
![리틀시네마 메인](https://user-images.githubusercontent.com/84892419/152179495-3a4994da-161a-48db-9ea4-3ae46b553a19.jpg)
- 주제: Spring MVC Model2 패턴을 활용한 영화예매웹사이트
- 기능:
    1. 회원 관리(회원가입, 로그인, 예매내역 확인, 회원정보 수정, 탈퇴)
    2. 영화 정보(상영시간표, 현재 상영 영화 리스트, 상영 예정 영화 리스트, 좌석 배치도, 고객센터)
    3. 예매(영화 선택, 날짜 및 시간 선택, 좌석 선택, 결제)
    
## ERD
![littlecinemaERD](https://user-images.githubusercontent.com/84892419/151753949-d0723838-2bd4-4a62-9bc7-91c464385a2d.jpg)
- 테이블: 회원, 영화, 상영시간, 상영관, 예매, 좌석, 예약된 좌석, 리뷰

## 개발환경
- Language: JAVA, JSP, HTML, CSS, Javascript
- WAS: Tomcat 9.0
- Build Tool: Maven
- Framework: Spring Framework
- Database: Oracle(Mybatis)
- Test: Junit 4.12
- Ajax

## 담당기능
![로그인 페이지](https://user-images.githubusercontent.com/84892419/152180325-8360b337-ddf0-488d-ad22-fe8b6200793c.gif)
[로그인/로그아웃]
- 로그인 시 아이디/패스워드가 기입 되어 있지 않은 경우 입력하라는 문구의 alert
- 아이디와 패스워드가 불일치할 경우 일치하지 않다는 메시지 띄움
- 로그인 페이지와 회원 가입 페이지를 ajax로 한 화면에 처리

![주문 내역 페이지](https://user-images.githubusercontent.com/84892419/152180596-ede960b0-5d88-4547-b611-0a7eaf6f4cc4.gif)
[영화 예매 내역]
- 영화 선택 > 영화 시간 및 좌석 선택 > 결제 이후 영화 예매 내역 출력
- 메인 화면 및 영화 예매 내역 리스트 페이지로 이동 버튼 추가
