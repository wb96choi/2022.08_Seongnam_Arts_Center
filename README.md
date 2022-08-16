# Project TEAM Seongnam Art Center

## 3조. 주윤종 김현진 박지훈 최원빈 최홍준

-----------------
성남아트센터 홈페이지를 반응형웹으로 리뉴얼하였습니다.

사이트 링크 : https://asben1.github.io/2022.08_Seongnam_Arts_Center/

Latest Updated Date: 2022.08.16
Project TEAM Seongnam Art Center .version 1.8

-----------------
## 팀 공지사항
- **** pc버전 토글메뉴 리뉴얼했습니다. main-layout.html확인하시고 괜찮으시면 이걸로 수정하겠습니다.
- style.css에 헤더와 메뉴, 그리고 푸터영역 css가 들어가있습니다.
- index에만 main-header.js 넣어주시고 다른 페이지엔 빼주세요~
- 푸터 css변경해주세요
```
- pc버전 토글메뉴 변경점
```c
- app.js에 호버시 .sub내려오는 자바코드를 app_mobile.js로 옮기기
- app.js에 / /토글메뉴버튼 애니메이션 < 수정
- mainlayout.html, css 참고하여 코드 수정하기
- **왠진 모르겠는데 pc토글메뉴창에서 .gnb> li에 호버하면 애니메이션이됨...
```

- 깃허브 업로드시 푸터 이미지 고장나는거
```c
- app.js에 푸터부분에서 ../images이거 ../지우세요
```

-----------------
# 기능 구현

-----------------
**메인프레임**

* 헤더, 푸터, 토글메뉴창이 모든 페이지마다 실행되도록 함
```c
 - 헤더
  - 헤더는 로고, GNB메뉴, 토글메뉴버튼으로 구성되어 있으며 토글메뉴버튼을 누르면 토글메뉴창이 열립니다.
  - 토글메뉴버튼은 클릭시 햄버거아이콘과 닫기버튼으로 변형됩니다.
  - 토글메뉴창 안에는 로그인기능, GNB메뉴가 있습니다.
  - 로그인버튼을 누르면
```

------------------
**메인페이지**

* 사용자를 환영하는 시작페이지
  - 사이트에 접속하면 방문자를 환영하는 문구가 나타나고 스크롤을 내리면 좌우로 사라지며 백그라운드 동영상이 무한재생됩니다.

* 공연 섹션
  - swiper플러그인을 활용하여 공연정보가 담긴 이미지 슬라이드가 나타납니다.

* 전시 섹션
  - AOS플러그인을 활용하여 스크롤에 반응해 양옆에서 전시정보가 나타납니다.

* 대관안내 섹션
  - 3D효과가 들어간 이미지 슬라이드가 나타나며, 클릭시 해당 모달창이 나타나 대관안내페이지로 안내해줍니다.

-------------------
**로그인 창**
 
- 아이디와 비밀번호를 입력하면 '아이디'님 환영합니다! 문구가 들어간 로그인창이 새로나타나고 로그아웃버튼을 누르면 원래대로 돌아옵니다. 


------------------
**제품 페이지**

* 2022.08.16 메모-
1. 각 항목들의 링크를 추가했습니다.
// 현재 구성: 공연(추천, 월간, 연간*) / 전시(추천, 월간, 연간*) //
*연간 = 준비중 사이트로 대체

------------------
**상세 페이지**

* 2022.08.16 메모-
1. 각 항목들의 링크를 추가했습니다.
2. 공연/전시의 포스터와 상세 정보 이미지를 추가했습니다.

------------------
**소개, 오시는길 페이지**

* 구글 맵스 api를 활용하여 실제 지도를 불러내어 줍니다.




## 사용 라이브러리(언어)
|JavaScript|HTML5|CSS3|
|---|---|---|
