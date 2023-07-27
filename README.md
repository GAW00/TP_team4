# 🤗Room & Boolm (1인용 가구 쇼핑몰)


![image](https://github.com/GAW00/tp_team4/assets/125619374/384351ec-8035-4f30-ac38-4e4bab51893d)

### 증가하는 1인 가구들을 위한 가구 셀렉트샵

제품 등록, 장바구니 추가, 주문하기 등 쇼핑몰의 핵심 서비스를 구현

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


## ✅ 페이지별 화면



<br/>

## ✅ 기술스택

![관리자제품](https://github.com/GAW00/tp_team4/assets/125619374/de0a1f09-d2f0-434f-8bf6-7216f278e8c3)

### 프론트엔드

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>

### 백엔드

  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"/> <img src="https://img.shields.io/badge/express-000000?style=flat-square&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/>
<img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=NGINX&logoColor=white"/> <img src="https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=PM2&logoColor=white"/>


<br/>
<br/>

## ✅ 기획

### 1. 정보구조도(다이어그램)
<img src="https://user-images.githubusercontent.com/104059932/211264767-84d028f1-c96b-448e-972a-ee4e32e51522.png" width="700px" />

### 2. [와이어 프레임](https://www.figma.com/file/33a0PITPQ3GaelQ2EgduNK/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8?node-id=1%3A2&t=NXWFCEgiHzGDyfV3-1)

### 2. [API 명세서](https://jiwoo84.notion.site/API-a1a1b003fbda4db885bebd36d528b7d0)

<br/>

## ✅ 인프라 구조

<img src="https://i.ibb.co/9tGxmx0/image.png" width=500 />

<br/>

## ✅ 폴더 구조

- 프론트: `src/views` 폴더
- 백: src/views 이외 폴더 전체
- 실행: **프론트, 백 동시에, express로 실행**

<br/>

## ✅ 제작자

| 이름   | 담당 업무 |
| ------ | --------- |
| 허혜실 | 팀장/FE   |
| 곽지우 | FE : 관리자 페이지, 마이페이지 정보수정  |
| 박지혜 | FE        |
| 손형석 | BE        |
| 이진희 | BE        |

<br />
