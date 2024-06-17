# 탄소 중립과 에너지 절약을 위한 에너지 비교 분석 시스템

- **Front-End**: HTML, CSS, JavaScript, jQuery
- **Back-End**: Spring, Flask

<br>

## 구현 목표
 - **탄소 중립을 위한 에너지 절약을 위한 자신의 전력량을 대전 아파트 평균전력량과 비교**

<br>

## 구현 기능
**데이터 수집, 전처리 및 EDA**
**Kakao Map API 이벤트 처리**
**ApexCharts.js 시각화 처리**
**EasyOCR 활용 고지서 처리**
**SARIMAX 활용 전력량 예측**
**DB 구축 및 연동**

### 아파트 관리 시스템:
 - **공공데이터를 활용하여 대전의 아파트 전력량의 평균 시각화**
 
### 내아파트 보기 기능:
 - **자신의 전력량이 아파트의 평균과 얼마나 차이가 있는지 그래프로 시각화**
 - **Ajax와 같은 비동기 통신 방식을 사용하여 일정 데이터를 동적으로 처리**

### 목표 설정 기능:
 - **개별 사용자와 전체 통계를 차트 제공으로 성과 분석 가능**


### 익명 아파트 게시판:
 - **익명성을 더하여 고객들 간의 자유로운 의사소통 기능**

### 탄소 포인트:
 - **친환경 목적의식을 더욱 갖고자 절약할 시 탄소 포인트 시뮬레이션을 돌려 얻게 되는 혜택 시각화 제공**

### 에너지 뉴스 :
 - **에너지 관련 경각심을 위한 관련 뉴스, 기사 정렬 및 스크랩 기능**

### 로그인 / 회원가입 시스템 구축:
 - **Spring Security를 사용하여 비밀번호의 보안을 강화.**
### 아이디/비밀번호 찾기 시스템 :
 - **아이디는 coolSMS를 사용하였고, 이메일인증은 google API를 활용하여 구현**
### DB 구축 및 연동:
 - **Oracle 데이터베이스를 설계하고, JDBC를 통해 Spring 애플리케이션과 연동했습니다.**
 - **데이터베이스 설계: 대전시의 아파트 평균 전력량 10년 치 데이터베이스 설계**
- **데이터 수집: 공공 데이터 포털에서 제공하는 API를 활용하여 데이터 수집&전처리 후 DB구축**


 

<br> 

## 수상 
<br>

 - **미래융합 교육원 팀프로잭트 우수상 수상**

    

<br>
<hr>
<br>

## 메인화면
<p align="center">
<video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/da14014e-a184-49fd-870a-82471dc714fb" alt="main">
</p>
<br>

- **카카오 맵API를 사용하여 대전의 구를 나누어 시각화하고 각 구의 전력 예측량 모델과 대전광역시 전력량을 시각화하였다.**
<hr>
<br>

## 회원가입 
<p align="center">
<video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/30187f58-196d-4934-8095-45a38074e714" alt="regist">
</p>
<br>

- **아이디 중복체크가 가능하고 아파트명을 검색하면 단지코드가 자동으로 입력됩니다.**
<hr>
<br>

## 내아파트 분석 화면
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/3d27815e-a2e5-4a5d-ae64-3692ddc02540" alt="myapt">
</p>
<br>

- **자신의 아파트의 전력량을 1년 단위로 볼 수 있고 아파트의 다음달 전력량을 예측할 수 있습니다. 고지서입력 버튼을 누르면 EasyOCR을 통하여 고지서의 전력량을 읽어 데이터 베이스로 저장됩니다.**
<hr>
<br>

## 아파트 고지서 분석화면
<p align="center">
  <img src="https://github.com/asder0705/2024_Team_Project/assets/150253403/d508d7f5-0537-4b14-80c2-38c7a2597c86" alt="go">
</p>
<br>

- **자신의 아파트의 평균 전력량과 자신의 전력량과 비교하여 얼마나 차이나는지 알려주고 자신의 전력량을 분석합니다.**
<hr>
<br>


### 아파트 비교화면
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/3d27815e-a2e5-4a5d-ae64-3692ddc02540" alt="apt_compare">
</p>
<br>

- **자신의 아파트와 다른아파트를 선택하여 전력량 비교가능**

<hr>
<br>

### 목표치 계산기
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/7c36909d-5992-40e8-a7e0-8d06363a0037" alt="plan">
</p>
<br>

- **고지서로 입력한 자신의 현재 전력량과 목표치를 설정하여 얼마나 절약하였는지 시각화하여 보여줍니다.**
<hr>
<br>

### 게시판
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/c6dc7b84-9a7f-4f5a-b554-ffb2e695d605" alt="plan">
</p>
<br>

- **단지코드로 아파트별 회원의 커뮤니케이션방을 만들고 다양한 카테고리 안에서 원활한 소통이 가능하고 추천과 댓글기능이 있습니다.**
<hr>
<br>

### 탄소포인트
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/5c4203fb-58a0-4f79-a98d-b6e549b51779" alt="plan">
</p>
<br>

- **자신의 전력량에서 몇퍼센트 절약하였을때 탄소포인트가 늘어나는지 시각화하여 기능 설명**
<hr>
<br>

### 에너지 뉴스
<p align="center">
  <img src="https://github.com/asder0705/2024_Team_Project/assets/150253403/27763e48-605e-420f-94e1-b5b8af2a8ad7" alt="plan">
</p>
<br>

- **아파트 에너지 관련 뉴스를 볼 수 있고 페이지네이션 기능을 구현하고 스크랩기능과 검색기능이 있습니다.**
<hr>
<br>

### 아이디 & 비밀번호 찾기
<p align="center">
  <video src="https://github.com/asder0705/2024_Team_Project/assets/150253403/ea7ca59f-935f-4838-9935-9d0728c0b368" alt="plan">
</p>
<br>

- **아이디는 coolSMS를 사용하였고, 이메일인증은 google API를 활용하여 구현**
<hr>
<br>

## 느낀점 및 보완사항
### 데이터 분야
- **데이터의 한계로 할 수 없었지만 데이터 범위가 넓어진다면 추후 발전가능성으로 난방, 가스 등의 데이터 까지 포함 시켜 아파트 전체 에너지에 대해 일괄적으로 비교분석이 가능하게 발전**

### 모바일
- **아파트 에너지 관련하여 React-Native를 활용해서 모바일 앱으로도 서비스 제공**

### 탄소 포인트
- **포인트만 시뮬레이션 하는 방법이 아니라 직접 신청도 가능 할 수 있도록 발전**




