# 🤗Room & Boolm (1인용 가구 쇼핑몰)


![image](https://github.com/GAW00/tp_team4/assets/125619374/384351ec-8035-4f30-ac38-4e4bab51893d)

### 증가하는 1인 가구들을 위한 가구 셀렉트샵

제품 등록, 장바구니 추가, 주문하기 등 쇼핑몰의 핵심 서비스를 구현

<br/>

## ⏰ 개발 일정(간트 차트)

![tp_team4_2023-07-04_03 52pm](https://github.com/GAW00/tp_team4/assets/125619374/09f0b865-fd3e-43bc-bbbe-167f696c1a12)

<br/>

## ✅ 서비스 주요 기능

### 💡 회원가입
- 아이디 비밀번호 유효성 검사 수행
- 등록 이메일을 통해 사용자가 매우 많은 id를 소유할 수 없게함
- 카카오 api도입으로 간결한 회원가입
- <details><summary>시연 모습</summary>

  ![image](https://github.com/GAW00/tp_team4/assets/125619374/1694c2ce-e442-4aa9-b5c0-5d00f18948fd)

  </details>

### 💡 로그인
- 소셜로그인 가능
- 아이디 / 비밀번호 찾기 및 수정
- <details><summary>시연 모습</summary>

  ![image](https://github.com/GAW00/tp_team4/assets/125619374/a59e41b9-6709-43ae-8079-57c7bb88fa8a)
  ![image](https://github.com/GAW00/tp_team4/assets/125619374/650579bd-d0c9-4e2b-b35a-acf1454247de)

  </details>

### 💡 홈
- 좌측 카테고리 탭을 통해 카테고리별 제품 열람 가능
- 제품 클릭시 상세정보 열람
- <details><summary>시연 모습</summary>

  ![image](https://github.com/GAW00/tp_team4/assets/125619374/fbe3bbe0-0071-4356-98cf-8bba69066d33)
  ![image](https://github.com/GAW00/tp_team4/assets/125619374/6ad6ff22-8c2f-42c9-9ba9-5956f985f316)

  </details>

### 💡 상세페이지 / 장바구니 / 결제
- 상품 상세정보 열람
- 장바구니에 담기
- 장바구니 리스트 중 선택적으로 구매 가능
- <details><summary>시연 영상</summary>
  
  ![상세주문](https://github.com/GAW00/tp_team4/assets/125619374/6e93225c-afcd-4fd1-96c3-b809a0175d9f)

  </details>

### 💡 구매평
- 상세페이지에서 구매평 작성·수정·삭제
- 해당 상품 구매자만 가능하도록 처리

### 💡 일반 회원 - 정보 관리
- 관리자와 일반사용자를 구분하여 페이지 변환
- 회원의 구매금액에 따른 등급 확인
- 보유 쿠폰 열람 및 사용
- 주문목록 열람 및 수정
- 회원정보변경 및 탈퇴
- <details><summary>시연 영상</summary>

  https://github.com/GAW00/tp_team4/assets/125619374/436ce200-b312-4879-a80d-d49c17d39020

  </details>

### 💡 관리자 - 주문 관리
- 주문 취소 가능
  - 주문이 완전히 삭제되지 않고 '관리자에 의한 취소'로 상태 변경 (데이터 보존)
- 배송상태(배송준비중, 배송중, 배송완료) 변경 가능
  -  배송완료로 변경 후에는 수정 불가
- <details><summary>시연 영상</summary>

  ![공지사항](https://github.com/GAW00/tp_team4/assets/125619374/92a93232-8936-4ac0-977a-ba247df42483)

  </details>

### 💡 관리자 - 상품 관리
- 상품을 추가 및 수정
- multer를 통해 이미지 업로드
- 상품 삭제시, 구매자가 있는 경우에는 상품이 사라지지 않고 '판매중지' 처리됨
- 카테고리가 삭제된 상품은 '미설정' 카테고리에서 확인 가능(데이터 보존)
- <details><summary>시연 영상</summary>

  ![관리자제품](https://github.com/GAW00/tp_team4/assets/125619374/68fd1ac6-38d5-436e-9f8e-5efa48b35303)

  </details>



<br/>

## ✅ 기술스택

![image](https://github.com/GAW00/tp_team4/assets/125619374/682a04ef-73e9-4f7b-9185-dfabb2ffdc4e)

### 프론트엔드

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>

### 백엔드

  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"/> <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"><img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">

### 형상관리

  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">


<br/>
<br/>

## ✅ 기획

### 1. 정보구조도(다이어그램)
![image](https://github.com/GAW00/tp_team4/assets/125619374/37499162-f1d6-4b61-820c-1a0db9435971)

### 2. [와이어 프레임][(https://www.figma.com/file/33a0PITPQ3GaelQ2EgduNK/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8?node-id=1%3A2&t=NXWFCEgiHzGDyfV3-1)](https://www.figma.com/file/7mTVSIZPz6HJyIOl6LjDYd/TP_4%EC%A1%B0-%EC%87%BC%ED%95%91%EB%AA%B0?type=design&node-id=0-1&mode=design&t=p50DF7K2ime0xLu0-0)


<br/>



<br/>

## ✅ 제작자

| 이름   | 담당 업무 |
| ------ | --------- |
| 박동명 | 팀장/BE   |
| 구나현 | BE        |
| 안예주 | BE        |
| 김효진 | BE        |
| 박정훈 | FE        |
| 조은유 | FE        |

<br />
