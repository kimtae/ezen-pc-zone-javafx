# EZEN PC ZONE

## URL : https://www.youtube.com/watch?v=xJC-KUXr47k

## 1. 개요
### 1.1. 개발 목적
- 피시방 이용자 및 관리자의 편의성 증진

### 1.2. 선정 배경

### 1.3. Target
- 피시방 이용자 (손님)
- 피시방 관리자 (피시방 대표, 아르바이트생)

## 2. 개발 일정
- 기간 : 2021.11.05 ~ 2021.11.21 (총 17일)
- History

|날짜|내용|
|----|----|
|2021.11.05|주제 선정 <br>화면 구성 1차 논의 및 화면 구조도 작성<br>Front 초안 제작(Scenebuilder)</br>|
|2021.11.08|Logo 제작 및 논의<br>화면 구성 2차 논의<br>controller 구조도 제작</br>|
|2021.11.09|Database 설계|
|2021.11.10|Scenebuilder 화면전환 구현|
|2021.11.11|문서화(화면구조, controller 구조, DB구조)<br>Scenebuilder fx:id 명명<br>최종 역할분담 <br>Database schema 및 table 생성</br>|
|2021.11.12 ~ 2021.11.17|개인 작업|
|2021.11.18 ~ 2021.11.21|프로젝트 연결 및 오류 수정|
|2021.11.22|프로젝트 발표|

## 3. 개발인원  

## 4. 개발 환경
- 운영체제 : Windows10
- Front-end : JavaFx 3.7.0, SceneBuilder 17.0.0
- Back-end : JDK 11, Eclipse IDE for Java Developers 2021-09
- Database : MySQL 8.0
- Version Control : Git

## 5. Controller 구조도  

## 6. Database ERD  
- Table : Total 7EA  
![211119_erd](https://user-images.githubusercontent.com/87436495/142559102-8652b249-c012-49e9-bef6-6fde86fbe444.png)

## 7. 주요기능 : 멀티스레드
### 적용
#### 7.1 로그인 및 로그아웃 시 키오스크, 고객, 관리자 프로그램에서 실시간 확인 가능
#### 관리자가 PC 상태 변경 시 PC 사용 불가 여부확인
#### 7.2 실시간 시간 차감
#### 7.3 고객 문의(채팅)
#### 7.4 상품 주문 시 관리자 주문 리스트에 실시간 업로드

## 8. 보완할 점
- 다수의 인원과 1:1 동시 채팅 구현
- 일시정지 멀티스레드 작동
- 게임 및 문서 실행 기능 추가
- 제품 등록 시 사진 px 크기 자동 조정
- 사진 업로드 시 경로 제약받지 않도록 (서버가 없어서 img폴더에 사진이 없으면 이미지 못불러옴)
- 코드 리팩토링


## 9. 후기
프로젝트 진행 시 어려웠던 

배운 것

아쉬운 것
