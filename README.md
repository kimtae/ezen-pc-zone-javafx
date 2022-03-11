# EZEN PC ZONE

### 시연영상 ( [바로가기](https://www.youtube.com/watch?v=xJC-KUXr47k) )

## 1. 개요
### 1.1. 개발 목적
- 피시방 이용자 및 관리자의 편의성 증진

### 1.2. Target
- 피시방 이용자 (손님)
- 피시방 관리자 (피시방 대표, 아르바이트생)

## 2. 개발 일정
- 기간 : 2021.11.05 ~ 2021.11.21 (총 17일)
- History

|날짜|내용|
|----|----|
|2021.11.05|주제 선정 <br>화면 구조도 초안 작성<br>Front 초안 제작(Scenebuilder)|
|2021.11.08|Logo 구상 및 제작<br>화면 구조도 1차 수정<br>controller 구조도 제작</br>|
|2021.11.09|Database 설계|
|2021.11.10|Scenebuilder 화면전환 구현|
|2021.11.11|Scenebuilder fx:id 명명<br>Database schema 및 table 생성</br>|
|2021.11.12 ~ 2021.11.17|기능 구현(Back-end)|
|2021.11.18 ~ 2021.11.21|프로젝트 연결 및 디버깅|

## 3. 개발인원
- 장용범 (총 1명)

## 4. 개발 환경
- 운영체제 : Windows10
- Front-end : JavaFx, SceneBuilder
- Back-end : Java, Eclipse
- Database : MySQL
- Version Control : Git

## 5. 화면 구조도
<details>
<summary>여기를 눌러주세요</summary>
<div markdown="1">       

![그림1](https://user-images.githubusercontent.com/87436495/148365412-4378dfc2-398c-42bd-a3af-8b385f28f8a9.png)
</div>
</details>



## 6. 폴더 구조
- Project : Total 3EA
<details>
<summary>여기를 눌러주세요</summary>
<div markdown="1">       

![7f5db1d4-9583-4db2-8a17-a0278132a19b](https://user-images.githubusercontent.com/87436495/148635544-fea89a05-15dd-415c-a046-edcad3f96e6a.png)
</div>
</details>

## 7. Database ERD  
- Table : Total 7EA  
<details>
<summary>여기를 눌러주세요</summary>
<div markdown="1">       

![211119_erd](https://user-images.githubusercontent.com/87436495/142559102-8652b249-c012-49e9-bef6-6fde86fbe444.png)</div>
</details>


## 8. 메인기능
- 좌석선택(결제), 자리이동, PC 상태변경 (변경내용 키오스크, 고객, 관리자 프로그램 실시간 동시 연동)
- 일시정지
- 실시간 시간 차감 및 사용 시간 계산 및 화면 출력
- 고객문의(채팅)
- 상품 주문내역 실시간 연동

## 9. 주요 코드 1개
- 기능 : Kiosk 좌석 선택(결제) 시 변동사항 Customer, Admin 실시간 연동
- 순서 : 초기 화면(로그인) -> 좌석 / 시간 선택 -> 초기 화면(변동사항 반영)

<br>1. Kiosk에 로그인을 한다.
<details>
<summary>코드 보기 (여기를 눌러주세요)</summary>
<div markdown="1">       

![untitled (1)](https://user-images.githubusercontent.com/87436495/148914216-6cfc59ef-38ae-4153-83a0-a984791abd0c.png)
</div>
</details>

<br>2. Kiosk에서 좌석 및 시간을 선택 후 결제버튼을 누른다.  
<details>
<summary>코드 보기 (여기를 눌러주세요)</summary>
<div markdown="1">       

![untitled (2)](https://user-images.githubusercontent.com/87436495/148922465-81419dd6-315c-4e67-b680-d44d20047e9a.png)
</div>
</details>

<br>3-1. [결과] 변동사항이 Kiosk 초기화면에 출력된다. - 실시간 연동
- 출력결과 : 선택좌석(붉은색으로 표기), 아이디, 남은시간
<details>
<summary>코드 보기 (여기를 눌러주세요)</summary>
<div markdown="1">   

![untitled (4)](https://user-images.githubusercontent.com/87436495/149105883-a5a61b20-752b-4004-a3ee-d7b5f3f6a97a.png)	
</div>
</details>

<br>3-2. [결과] 변동사항이 Admin 초기화면에 출력된다. - 실시간 연동
- 출력결과 : 선택좌석(붉은색으로 표기), 아이디, 남은시간
<details>
<summary>코드 보기 (여기를 눌러주세요)</summary>
<div markdown="1">   

![untitled (5)](https://user-images.githubusercontent.com/87436495/149112373-56247678-e3b9-4e08-af18-a5e04a55a164.png)
</div>
</details> 

## 10. 보완할 점
- 다수의 인원과 1:1 동시 채팅 구현
- 일시정지 시 DB 미반영
- 제품 등록 시 사진 px 크기 고정 설정
- 사진 업로드 시 업로드 경로 제약받지 않도록 설정
