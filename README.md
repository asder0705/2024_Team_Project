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
<hr>
<br>

## 옷 등록 화면
<p align="center">
  <img src="https://github.com/asder0705/SpringCloset/assets/150253403/5544b476-322f-4bec-b748-dfc4564c96e2" alt="closetupView">
</p>
<br>
- 대분류 중분류를 통하여 옷을 검색 할 수 있고 옷 등록 버튼을 통해 데이터베이스에 추가하 수 있고 아코디언 버튼을 클릭하여 상세정보 설명을 볼 수 있다.
<hr>
<br>

### 나의 옷장 화면
<p align="center">
  <img src="https://github.com/asder0705/SpringCloset/assets/150253403/d808ebdd-0c7e-4491-8030-9b59cd89e642" alt="create_plan1">
</p>
<br>
- 등록된 옷들을 볼 수 있고 삭제가 가능하다.
<hr>
<br>

### 옷장 코디 화면
<p align="center">
  <img src="https://github.com/asder0705/SpringCloset/assets/150253403/d95c6709-fd00-4acd-902c-d12baa70b0b5" alt="edit_plan1">
</p>
<br>
-- 선택된 옷들의 이미지를 slide로 한번에 볼 수 있고 drag and drop 을 통하여 옷을 선택하여 매치 한 후 파일 형태로 저장 할 수 있다.
<hr>
<br>

- **옷 텍 정보 easyOCR로 찾아오기** 
<p align="center">
  <img src=https://github.com/asder0705/SpringCloset/assets/150253403/89bf39b1-7ae9-4994-ac40-2d1468bf8121"" alt="edit_plan2">
</p>
<p align="center">
  <img src="https://github.com/asder0705/SpringCloset/assets/150253403/1d4e3126-c8fe-4f5e-81ee-7341a33f5af5" alt="edit_plan2">
</p>
<br>
-- fileupload를 한 뒤 flack를 통하여 이미지 분류 후 네이버API키를 활용해 상품들을 나열한다.
<hr>


## 느낀점 및 보완사항
### css
- **기능에 신경 쓰다 보니 화면이 매끄럽지 못했고 화면 간격이나 margin에 대한 이해가 부족하여 비율이 잘 맞지 못했다. 이런 부분에 있어서 고객이 원하는 바가 있을 수 있으므로 더 공부해야겠다.**

### 디버깅
- **오류를 해결하는 과정에서 디버깅을 통해 코드를 다시 짜보고 실행해보는 과정에서 성장을 많이 한 것 같다.반복해서 같은 부분이라도 뭐가 들어왔는지 보고 오류를 찾아내서 해결하는 부분에서 문제 해결 능력이 상승하는 것을 느낄 수 있었다.**



