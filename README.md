# first_web

HTML과 CSS만을 이용한 아주 간단한 웹페이지
![K-009](https://user-images.githubusercontent.com/89966178/155881402-7e2c9778-4fb7-4bb0-a5f0-a4fad5748fca.png)
![K-010](https://user-images.githubusercontent.com/89966178/155881406-af902e14-b005-4d12-a70c-90b8828ccfe7.png)

### 배경
공부할 내용이 방대한 프론트엔드 분야에서 가장 효과적으로 공부하는 방법은 '배운 것을 이용하여 눈에 보이는 결과물 만들기'라고 생각한다.
생활코딩 유튜브, 드림코딩 엘리 유튜브 채널에서 html과 css의 기초 문법을 배우고 앨범 형식의 간단한 웹페이지를 만들게 되었다.

### 문제와 해결
1. 아래로 스크롤 시, header가 고정되지 않아 header가 보이지 않는다.
   => position: fixed 로 설정하여 header가 화면에 고정되게 하였다.
2. header와 footer 위로 이미지가 출력되었다.
   => z-index 속성을 이용하여 header와 footer의 z축 값을 body의 z축 값보다 높게 설정하였다.
