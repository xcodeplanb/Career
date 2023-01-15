# career
## 펫핑 앱 -(Android Native Application)
### 담당 : 개발(프로젝트구조,산책,회원 관련 및 기타) 개발 및 유지보수
### 스토어 링크
- https://play.google.com/store/apps/details?id=com.smallticket.petping
### 뷰

### 정의
- 반려견 산책 및 통계
- 산책 리워드를 통한 펫핑샵 구매
### 프로젝트 패키지 구조
<img src="https://user-images.githubusercontent.com/72433232/212527967-55344741-de84-4720-a164-533b2ba49ab0.png" width="40%" height="40%"/>

* Android 권장 앱 아키덱처 레이어에서 도메인 레이어(optional)를 제외한 구조
* Single Activity로 구성되었고 navigation component에 각 프래그먼트가 포함
* 서브메뉴가 있는경우 중첩그래프로 분리하였고 메인액티비티와의 통신은 액티비티 공유 뷰모엘을 통하여 이루어짐

### 애니매이션(motionlayout 토이프로젝트)
![animation](https://user-images.githubusercontent.com/72433232/211143749-2822d13e-64c5-4fe1-b9c3-f6e1fc139342.gif)
* 실제 펫핑앱은 프론트 개발자의 웹소스로 웹뷰위에 구현되었지만 부재로 인하여 
* 네이티브 구현 가능성 테스트 용도
* 7개의 scene xml로 구성
![motionlayout](https://user-images.githubusercontent.com/72433232/211143563-8277f789-7b9b-4cc0-b0b6-a42f6d9415f2.png)

## 아이파킹 앱 -(Android Native Application)
### 담당 : 개발(100%), 운영 및 유지보수
### 스토어 링크
- https://play.google.com/store/apps/details?id=kr.co.iparking.android
### 뷰
![iparking_screenshot](https://user-images.githubusercontent.com/72433232/100401681-84be6100-309d-11eb-8fc8-a244e4d1b2f0.png)
### 정의
- 전국 주차장 정보 제공
- 각종 주차 상품권 구매 및 모바일 주차권 제공
- 다양한 프로모션을 통한 할인 지원
### 메뉴규조도
![iparking_uml1](https://user-images.githubusercontent.com/72433232/100400921-53449600-309b-11eb-9a4d-44d87c29296b.png)
![iparking_uml2](https://user-images.githubusercontent.com/72433232/100400935-59d30d80-309b-11eb-9b0c-c4bde8fce4d4.png)
![iparking_uml3](https://user-images.githubusercontent.com/72433232/100400936-5b043a80-309b-11eb-803b-81e5ecd6c1a0.png)      
***
## 아이파킹 스트리트 (Android Native Application)
### 담당 : 운영 및 유지보수
### 스토어 링크 (없음)
### 뷰
![street_screenshot_1](https://user-images.githubusercontent.com/72433232/100558587-5be2d980-32f2-11eb-9ac5-6f358408a295.jpg)
### 정의
- 노상 주차장의 주차 관리자가 스마트폰을 이용하여 주차 업무를 관리할 수 있도록 다양한 기능을 제공하는 애플리케이션
### 메뉴규조도
![street_uml1](https://user-images.githubusercontent.com/72433232/100403784-26947c80-30a3-11eb-80b5-c2c5a2903ed3.png)
![street_uml2](https://user-images.githubusercontent.com/72433232/100403789-27c5a980-30a3-11eb-800b-84c6c8579d89.png)
![street_uml3](https://user-images.githubusercontent.com/72433232/100403791-27c5a980-30a3-11eb-86ad-31a69e22890e.png)
![street_uml4](https://user-images.githubusercontent.com/72433232/100403793-285e4000-30a3-11eb-9057-7dfe556f52fb.png)
![street_uml5](https://user-images.githubusercontent.com/72433232/100403796-285e4000-30a3-11eb-807b-70cc66a9f2b1.png)
![street_uml6](https://user-images.githubusercontent.com/72433232/100403797-28f6d680-30a3-11eb-9748-f7a74231d7c6.png)
![street_uml7](https://user-images.githubusercontent.com/72433232/100403798-28f6d680-30a3-11eb-8bb3-d51ab7c6d909.png)
![street_uml8](https://user-images.githubusercontent.com/72433232/100403799-2a280380-30a3-11eb-8dc1-8974075b4514.png)
![street_uml9](https://user-images.githubusercontent.com/72433232/100403800-2a280380-30a3-11eb-92e7-d228a8ed04d1.png)
![street_uml10](https://user-images.githubusercontent.com/72433232/100403801-2ac09a00-30a3-11eb-9a46-a1b155060062.png)
![street_uml11](https://user-images.githubusercontent.com/72433232/100403804-2ac09a00-30a3-11eb-9689-b9ecfd6c5f72.png)
![street_uml12](https://user-images.githubusercontent.com/72433232/100403806-2b593080-30a3-11eb-82d1-e3f537c87890.png)
![street_uml13](https://user-images.githubusercontent.com/72433232/100403807-2b593080-30a3-11eb-88a3-79004840a390.png)
![street_uml14](https://user-images.githubusercontent.com/72433232/100403808-2bf1c700-30a3-11eb-88cc-4c3882f0d51d.png)
![street_uml15](https://user-images.githubusercontent.com/72433232/100403809-2bf1c700-30a3-11eb-97fb-50326c4a67d3.png)
![street_uml16](https://user-images.githubusercontent.com/72433232/100403810-2c8a5d80-30a3-11eb-9c68-a2e68a184ab6.png)
***

## 지자체 공영주차장 (Android Native Application)
### 담당 : 운영 및 유지보수
### 스토어 링크
- 고양 : https://play.google.com/store/apps/details?id=kr.co.parkingcloud.goyang
- 용인 : https://play.google.com/store/apps/details?id=kr.co.parkingcloud.yongin
- 대구 : https://play.google.com/store/apps/details?id=kr.co.parkingcloud.daegu
### 뷰
![screenshot](https://user-images.githubusercontent.com/72433232/100708621-fd038a00-33ef-11eb-9f44-fb97da51c048.png)
### 정의
- 지자체 관리 하에 있는 주차장에 한하여 만들어진 아이파킹 미니 버전
- 고양시 주차장 정보 제공 및 정기권 납부
### 메뉴규조도
![local_1](https://user-images.githubusercontent.com/72433232/100708323-72bb2600-33ef-11eb-9f6f-2a1b381f4078.png)
![local_2](https://user-images.githubusercontent.com/72433232/100708324-72bb2600-33ef-11eb-8a97-dd0a7f864dbb.png)
![local_3](https://user-images.githubusercontent.com/72433232/100708325-7353bc80-33ef-11eb-9311-b9d93eaefc0d.png)
![local_4](https://user-images.githubusercontent.com/72433232/100708326-7353bc80-33ef-11eb-97bd-c8729b2a81fc.png)
![local_5](https://user-images.githubusercontent.com/72433232/100708327-73ec5300-33ef-11eb-86e2-f6aecf5dc2c1.png)
![local_6](https://user-images.githubusercontent.com/72433232/100708329-73ec5300-33ef-11eb-8a34-8f36bdc80c39.png)
![local_7](https://user-images.githubusercontent.com/72433232/100708330-7484e980-33ef-11eb-80b3-001512063087.png)
![local_8](https://user-images.githubusercontent.com/72433232/100708331-7484e980-33ef-11eb-9102-a0c2ceb64084.png)
