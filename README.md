# Board-Sample(게시판 샘플)

<div>
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white" />
</div>

 ## 요구사항
- [ ] Spring Boot를 사용하는 백엔드 게시판
  - [ ] 스프링 부트 JPA
  - [ ] 스프링 부트 JWT 보안(미구현)
  - [ ] 외부 REST 서비스(SNS Login)(미구현)
- [ ] html 프론트엔드(구현중)

#### 구현기능

- 게시물등록

- 게시물조회

- 게시물수정

- 게시물삭제

- 파일 첨부
  - 파일이름
  - 파일경로
  - 파일크기
  - 파일타입

- 댓글
  - 댓글 ID
  - 작성자 이름
  - 내용

- DB에 저장
  - 게시물 ID
  - 게시물 제목
  - 게시물 내용
  - 작성자 이름
  - 최초작성시간
  - 최종수정시간

- ######  미구현항목은 현재 작업중
[프론트가 아닌 백엔드이기에 눈으로 보이는건 감안해 주시기 바랍니다.]

---

#### __● 제작 과정에 필요했던 지식__

1. CRUD 의 개념
- 엔티티 등록
- DB(MySQL)에 저장
- CRUD 구현 클래스 작성

<br>
2. 스프링부트 어노테이션 사용

- RequestPharam, Model 등의 데이터 공유방안
- CRUD구현 클래스에 사용되는 어노테이션(@Controller , @Service, @Data....)

<br> 3. HTML과 스프링부트 간의 데이터 공유

<br>
 4. 자바 문법
 - 데이터 타입
 - 예외처리
 - 람다식 활용
 <br>...

 ---
###  추가 예정
