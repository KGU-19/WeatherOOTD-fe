# WeatherOOTD

### 기능
#### 1. 날씨에 따라 매일매일의 ootd를 추천

- 최근 두 달 내의 인스타그램 게시물이나 뉴스를 참고
- 기간이 너무 먼 경우에는 패션 트렌드에 벗어날 수 있고, 최근에는 매년 동일 월일 대비 온도변화가 매우 커서 과거 자료는 별 도움이 안 됨
- 추후 기간 설정이 가능하도록 업데이트 예정

#### 2. 메인화면에는 3가지 혹은 4가지의 날씨 화면이 넘길 수 있는 가로 스크롤 형태로 보여지게끔
- 오전(7시 ~ 12시), 오후(12시 ~ 5시), 저녁(5시 ~ 10시), 야간(10시 ~ 새벽)으로 외출 시간을 구분
- 각 시간대의 온도를 확인 후 평균 온도로 추천

#### 3. ootd 추천
- 인스타그램의 해시태그 활용 </br>
=> 예를 들어, 2월 3일 오전에 외출을 할 예정이면. </br></br>
  a. 2월 3일의 오전 7시부터 12시의 예상 기온으로 2번을 생성 </br></br>
  b. 두 달 전까지의 날씨 정보를 검색해서 평균값과 유사한 날을 찾기 </br></br>
  c. 찾은 날 올라온 인스타그램 게시물을 검색해서 화면 노충 </br></br>
  d. 게시물 검색은 해시태그를 이용 (#ootd #대학생패션 등등) </br></br>

+@ 직접 해시태그를 입력해 원하는 룩, 장소 등도 검색할 수 있도록 기능 추가 

</br>

## 데이터 구조

<img src="https://github.com/KGU-19/WeatherOOTD-fe/assets/63261054/583772a9-4236-49df-92e9-5dbb2f24accb" width="600" height="300"/>


