## Goin-one 프로젝트 Front-End 소개

- 거래액 전세계 47위 암호화폐 거래소, 국내 최초로 이더리움 클래식을 상장, 사이버배상책임 보험 계약을한 거래소[코인원](https://coinone.co.kr/) 클론 프로젝트

### 개발 인원 및 기간

- 개발기간 : 2020/3/9 ~ 2020/3/20
- 개발 인원 : 프론트엔트 2명, 네이티브 1명,백엔드 1명
- [백엔드 github](https://github.com/wecode-bootcamp-korea/GoinOne-backend)
- [네이티브 github](https://github.com/wecode-bootcamp-korea/GoinOne-app)

### 목적

- 가상화폐 거래소의 특징은 실시간 통신이라는 점이 매력적인 포인트, 코인원은 암호화폐 거래소 중 실시간 채팅이라는 기능을 가지고 있는 특징을 가지고 있음
- 그에 따른 실시간 통신을 어떠한 방법으로 할 지 시행착오를 겪음
- 뿐만 아니라 가상화폐 거래소인 만큼 데이터 시각화에 따른 그래프데이터를 사용자에게 보다 쉽게 보여줘야 함

### 데모 영상(이미지 클릭)

업로드 예정


<br/>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React, hooks, Redux, Styled components, highcharts, Socket IO(express), 
> - Back-End : Python, Django web framework, Beautifulsoup, Bcrypt, My SQL, Email Authorization
> - Common : AWS(EC2,RDS), RESTful API

</br>

### 구현 기능

#### 공통

- 이메일 인증 / 로그인
- 소켓통신을 이용한 실시간 채팅
- 정규식을 이용한 이메일 및 비밀번호 검사
- 코인 별 데이터 시각화(그래프)

</br>

#### 로그인 및 회원가입

- 이메일 인증 구현
- 회원가입란 정규식 5가지를 이용하여 조건 충족

</br>

#### 메인 및 거래소 페이지

- 코인 거래 데이터를 highchart에 적용해 데이터 시각화
- express를 이요한 소켓통신 구현(실시간 채팅)
- 매수 기능 구현
- 코인 별 데이터 뿌리기

</br>

### 정리

- 1차 프로젝트에 비해 새로운 개념(redux,hooks,style component)를 이용해 구현하려고 하여 개발속도가 지체됐고, 구현하기 어려운 페이지임에도 불구하고 팀원이 너무 적어 기능 구현을 많이 이뤄내지 못함
- 하지만 새로운 개념(redux, hooks,style component)에 익숙해지고 활용할 수 있어서 좋은 경험을 함

**추후에 계속 수정해 나갈 예정**
