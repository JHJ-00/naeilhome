# 내일의집

**제작 기간** : 2025.03.03 ~ 2025.04.25  
**참여 인원** : 5명 (이민주, 송현오, 박찬희, 임현규, 정희준)

![Image](https://github.com/user-attachments/assets/15f34efe-e0e8-4e70-9799-c70f66d2bf8b)

## 프로젝트 개요
소비자들이 자신만의 독특한 인테리어를 구현하기 위해 다양한 제품을 손쉽게 찾고 구매할 수 있는 플랫폼

## 개발 배경
장래 인구 및 가구 추계 자료를 바탕으로 1인 가구 비율의 증가를 예상하며, 이에 따라 커뮤니티 "내집 소개" 컨텐츠 내 제품을 쇼핑몰과 연동하여 손쉽게 인테리어 할 수 있는 플랫폼을 기획하기로 하였습니다.

## 개발 도구
- **Web** : Spring Boot, MyBatis, Maven
- **DB** : Oracle
- **Front** : HTML5, CSS3, JSP, JavaScript, JQuery, JSTL, Tiles
- **Server** : Apach Tomcat9.0, AWS EC2, Docker

## 주요 기능
**1. 본인인증 방식**
- 카카오, 네이버 구글 회원가입/로그인 API
- 이메일 인증(SMIP기반 이메일로 인증코드를 통해 회원가입 및 회원 이메일 수정)

**2. 회원가입**
- 이메일 인증으로 본인인증
- ID, 닉네임 중복확인 AJAX 구현
- 주소 검색(Daum 주소 검색 API)

**3. 커뮤니티 게시판 기능 구현**
- Drag & Drop API를 이용한 썸네일 등록
- SummerNote 에디터를 이용한 게시판 CRUD 구현
- AJAX를 이용한 댓글 및 대댓글 구현
- 페이지네이션 및 필터링 정렬

**4. 쇼핑몰 기능**
- 장바구니 결제, 포인트 사용, 주문내역 확인 기능
- 배송지 기존 선택과 신규 선택 기능(Daum 주소 검색 API)
- 상품 구매 후 리뷰 작성과 리뷰 모아보기

## 프로젝트 URL
[http://www.naeilhome.kro.kr/](http://www.naeilhome.kro.kr/)
