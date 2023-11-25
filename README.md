# 쇼핑몰 프로젝트
## 프로젝트 기능 및 설계
- 회원가입 기능
  - 사용자는 회원가입을 할 수 있다. 일반적으로 모든 사용자는 회원가입시 USER 권한 (일반 권한)을 지닌다. 
  - 회원가입시 아이디와 패스워드를 입력받으며, 아이디는 unique 해야한다.

- 로그인 기능
  - 사용자는 로그인을 할 수 있다.
  - 로그인시 회원가입때 사용한 아이디와 패스워드가 일치해야한다.

- 상품명 검색 기능
   - 로그인하지 않은 사용자를 포함한 모든 사용자는 상품명을 조회 할 수 있다.
   - 상품을 클릭하면 상품 주문 페이지로 이동할 수 있다.
   - 상품 목록은 많을 수 있으므로 페이징 처리를 한다.

- 장바구니 담기
  - 로그인하지 않은 사용자는 상품을 담을 수 없다.
  - 상품 담기에 담을 상품명, 옵션, 개수를 선택해야 담을 수 있다.
  

- 장바구니 조회
  - 로그인하지 않은 사용자는 장바구니를 조회할 수 없다.
  - 로그인된 사용자가 담은 모든 상품을 볼 수 있다.
  - 장바구니에 있는 상품을 클릭 시 상품 상세 페이지로 이동 할 수 있다.
  

- 장바구니 상품 삭제
  - 로그인된 사용자가 담은 모든 상품을 삭제 할 수 있다.
  - 전체 삭제 및 일부분만 삭제 가능 할 수 있다.
  

- 결제 하기
  - 장바구니에 담긴 상품을 구매할 수 있다.
  - 결제가 많을 수 있기 때문에 별도의 API로 구성한다.

- 결제 취소
  - 결제 내역을 취소할 수 있다.
 
## 주차별 개발 계획
- 1주차 : 프로젝트 기능 및 구조 설계
- 2주차 : 회원가입, 로그인 기능 구현
- 3주차 : 상품명 검색 기능 구현
- 4주차 : 장바구니 추가, 삭제 기능 구현
- 5주차 : 장바구니 조회, 상품 구매하기 기능 구현

## ERD




## Tech Stack
<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>
