## 👩‍🏫PROJECT 소개

---

앞서 JSP Project에서 진행한 book45를 Spring Framework로 개발을 진행한 프로젝트입니다.

교육 내에서 진행된 기술들을 바탕으로 주문, 장바구니 등의 간단한 서비스를 제공하는 온라인 서점을 웹 사이트를 만들어 보았습니다.

프론트엔드는 백엔드기술에 집중하기 위해 기존의 JSP Project를 베이스로 하였고 백엔드는 mvc2 패턴을 활용하여 개발해보았습니다.

RDS 환경에서 Oracledb를 사용하였습니다.


🗓️ 작업 기간 : 2023/02/03 ~ 2023/02/04

👨‍💻 개발 인원 : 3명(비전공자 3)

📒 주요 기능 

- user-service : 사용자에 관한 기능을 제공합니다. 회원 가입, 회원정보 수정, 회원 탈퇴 기능을 담당합니다. (로그인의 경우 jwt를 활용한 스프링 시큐리티를 사용했습니다.)
- catalog-service : 상품에 관한 기능을 제공합니다. 상품 등록, 수정, 삭제할 수 있으며, 작가 이름과 상품 이름으로 검색할 수 있습니다.
- order-service : 상품 주문을 하는 서비스입니다. 주문 시에 kafka를 사용하였고, catalog-service와의 통신을 통하여 주문 성공 시에 상품 수량이 줄어들게 돕니다.
- cart-service : 장바구니를 관리하는 서비스입니다. 상품을 장바구니에 담거나 삭제할 수 있습니다. 이 곳에서 구매하기 버튼을 클릭하여 구매하기 페이지로 갈 수 이동할 수 있습니다.

🌱 기술 스택

프론트엔드 : `React.js`  
백엔드 : `Spring Framework` `JPA` `AWS RDS(Oracledb)`
협업 툴 : `github` `Discode` `slack`  

<br/>

🌱 **구성도**

![image](https://user-images.githubusercontent.com/124012446/225525681-35dd6801-8506-45d5-813b-2c5a19d9afce.png)



