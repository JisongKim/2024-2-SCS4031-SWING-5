![header](https://capsule-render.vercel.app/api?type=waving&color=7686DB&section=header&text=가족연동%20기반%20시니어%20건강관리%20플랫폼%20(WIN;C)&fontSize=35&customColorList=2&height=170)


# 2024-2 융합캡스톤디자인 SWING
| 구분 | 성명 | 학번 | 소속학과 | 이메일 | 깃헙아이디
| --- | --- | --- | --- | --- | --- |
| 팀장 | 김지송 | 2021112431 | 산업시스템공학과 | jisong1222@naver.com | [@JisongKim](https://github.com/JisongKim) |
| 팀원 | 김지우 | 2020110269 | 통계학과 | kjw01024@naver.com | [@jouju3585](https://github.com/jouju3585) |
| 팀원 | 박나영 | 2018111743 | 의생명공학과 | skdud025@naver.com | [@nayoung601](https://github.com/nayoung601) |
| 팀원 | 이종주 | 2021112456 | 산업시스템공학과 | tlzhsh2@naver.com  | [@LJongJoo](https://github.com/LJongJoo) |
- 지도교수: 동국대학교 SW교육원 신연순 교수님, 박효순 교수님
- 멘토: 김도현 개발자님(카카오뱅크)

  <br>

# 📑 Project
- **가족 연동기반 시니어 건강케어 플랫폼 '윙크'(WIN;C)**
- 고령화 사회에서 액티브 시니어(특히 5060 세대)의 꾸준한 건강관리를 지원하며, 가족 간의 소통과 상호작용을 통해 건강 관리를 보다 효과적으로 수행할 수 있도록 돕는것을 목표로 함
  <br>
  <br>

##  🚩프로젝트 개요 
### 가. 개발 동기 및 목적
- 대한민국은 2025년 초고령사회로 진입할 예정이며, 이에 따라 5060대의 중장년층
을 대상으로 한 실버산업의 중요성 또한 크게 증가할 것으로 예상됨
- 동시에, 해마다 스마트 기기에 대한 의존도가 높아지고 있으며 그로 인한 가족간의
소통시간도 점점 줄어들고 있음. 이러한 사회적 변화를 기반으로 본 프로젝트는
가족 간 스마트기기를 ‘건강 관리’라는 긍정적 목적으로서 적극 활용하고자 함

### 나. 개발 목표 및 범위
-  액티브-시니어를 대상으로 그들의 라이프 스타일 개선을 돕는 통합적인 플랫
폼을 개발하는 것을 거시적 목표로 설정
- 다른 건강관리 플랫폼과의 차별성을
갖기 위해 가족 간의 연동기능을 구현하여 건강관리 뿐만 아니라 가족 간의 유대감
을 강화할 수 있는 ‘소통하는 건강플랫폼’을 개발함
 <br>
 <br>

##  🚩필요성
- 현재 시중에는 다양한 건강관리 어플이 출시되어 있지만, 대부분의 어플이 사용자가 직접 건강 정보를 기록하는 방식에 의존하고 있음. 특히 의약품 복용과 같은 중요한 정보는 사용자의 기록에만 의존하기엔 한계가 있음. 
- 위와 같은 문제를 해결하기 위해, 자신의 몸을 보다 더 신경써줄 수 있는 보호자와 연동하여 건강 상태를 관리할 수 있는 플랫폼의 필요성을 느낌.  이를 통해 가족 간 서로의 건강 상태를 직관적으로 파악, 기록이나 복약 시간을 놓치는 상황을 예방함으로써 보다 체계적인 건강관리를 가능하게 함.
- ‘가족과 소통하는 건강플랫폼’은 가족 구성원 간의 정보를 실시간으로 공유하고, 알림 기능을 제공함으로써 가족 단위의 지속적인 건강관리를 지원하고자 함. 또한 개인 맞춤형 관리와 더불어 가족의 건강 상태를 종합적으로 관리할 수 있어 고령화 사회에서의 새로운 헬스 케어 솔루션으로 자리 잡을 수 있을 것으로 기대됨
 <br> 
 <br>

## 🚩선행기술 및 사례 분석
### 가. 기존 유사 시스템
#### [1] 파프리카 케어 
- 처방전/약봉투를 촬영 및 처방내역 직접 입력을 통해 의료기록 관리
- 처방 약에 대한 ‘설명, 약제특성, 처방질병, 주의사항’ 정보 제공
- 복용 알람 및 의료 일정 관리
- 한 계정에 가족을 등록하는 형태로 가족 회원 대리 관리만 가능          
→ 해당 서비스의 가족 관리 기능의 경우, 유아 혹은 노인을 대상으로 보호자가 대리 관리할 시 적합할 수 있으나, 보다 디지털에 익숙한 5060 세대의 부모님에게는 적합하지 않은 형태  
→ 5060 세대의 경우 독립적으로 지속적인 건강관리를 펼쳐 나가야 하기 때문에 가족 간 양방향 상호작용을 통한 건강관리가 더 효과적임  
→ 처방 약에 대한 정보는 상세히 제공되지만, 개인 맞춤형 의료정보나 통합적인 건강관리에 대한 기능 부족

#### [2] 헬피
- 앱테크를 메인으로 활용하는 건강루틴 형성 플랫폼
- 복약 및 검진결과 관리기능 포함
- 건강 미션을 통한 포인트 적립 및 쇼핑 기능 제공 (각종 기프티콘 형태)
- 자녀 등록을 통한 대리 관리만 가능  
→ 앱테크를 통한 건강관리 동기부여를 통해 일정 부분 관리 지속성을 향상시킬 수는 있으나 가족 간 상호작용이 전혀 포함되지 않은 개인적인 수준에서만 이루어짐  
→ 가족 간 상호 건강정보 공유 및 공동 목표 설정 기능 부재  
→ 앱테크를 통해 적립된 포인트는 기프티콘이나 쇼핑 등의 사용으로 국한되어 있어, 실질적 건강 개선보다는 보상에 집중되는 경향이 있음

#### [3] 캐시워크
- 걸음 수에 따라 캐시가 적립되어 실생활에 활용할 수 있는 앱테크 플랫폼
- 소비 칼로리, 움직인 거리/시간 계산  
→ 건강관리의 범위가 단순 ‘걷기’ 에만 집중되어 있으므로, 폭넓은 전반적 건강관리 필요  
→ 사용자가 실질적인 건강관리를 목표로 행동 변화를 이루기보다는, 단순히 캐시 적립을 위한 단기적인 습관 형성에 그치는 등, 장기적인 건강관리 습관 형성에는 어려움이 있음

### 나. '윙크(WIN;C)'만의 차별성
**(1) 5060 액티브시니어 세대를 위한 가족 간 양방향 상호작용 제공**  
- 가족 개개인의 독립적 건강관리와 더불어, 가족 구성원 간 상호작용을 통해 지속적 건강관리의 동기부여 제공  

**(2) 가족 간 건강정보 공유 기능 제공**
- 가족 구성원이 각자의 건강 정보와 복약 기록을 세부적으로 카테고리화 하여 공유함으로써 개인의 건강관리를 넘어 가족 전체의 상호 간 건강관리를 실현  
- 가족 구성원에게 상세한 복약 및 건강 정보를 제공하면서 동시에 사용자 본인이 공개 여부를 설정할 수 있어 연동된 가족이더라도 공개하고 싶지 않은 개인정보는 철저히 보안됨  

**(3) 의료기록 및 복약, 병원 일정 관리 뿐 아니라 통합 헬스 케어 플랫폼으로서 작용**
- 전반적인 건강관리를 위한 의료 정보, 관리기능 제공  


 <br> 
 <br>

## 🚩서비스 핵심 기능
### **(1) OCR 기반 복약 관리**  
- 약봉투/처방전 스캔을 통해 복약 정보를 자동으로 등록
- 사용자 맞춤형 복약 알림(시간, 횟수) 설정 및 연동 가족 공개 여부 설정 가능
- 복약 시간에 맞춰 사용자에게 알림이 전송되며, 복약 여부 기록을 통해 복약이력 관리
- 가족 구성원이 복약 상태를 실시간으로 확인 가능하며, 미복약 시 추가 알림 전송

### **(2) 건강데이터 관리**
- 혈압, 혈당 등의 건강 데이터를 사용자가 직접 입력하고, 날짜와 시간 정보를 기반으로 기록 관리
- 입력된 건강 데이터는 그래프 형태로 시각화되어 건강 상태 변화를 쉽게 파악 가능
- 가족 구성원이 함께 데이터를 확인하며 협력적으로 건강 상태를 관리 가능

### **(3) 건강 캘린더**
- 사용자의 복약 일정, 혈당/혈압 기록, 건강 일정을 한눈에 확인할 수 있는 직관적인 건강 캘린더 제공
- 가족 구성원 간 일정 공유를 통해 서로의 건강 스케줄을 확인하며 협력적 관리 가능
- 개인 일정은 사용자가 직접 수정하며, 다른 가족 구성원에게는 읽기 전용으로 표시되어 데이터 보호 강화.

### **(4) 가족 연동**
- 가족 구성원을 초대하여 그룹을 생성하고, 구성원 간 건강 데이터 및 일정 공유 가능
- 초대 코드를 통해 손쉽게 가족 구성원 추가 및 기존 그룹과 연동 가능
- 구성원 간 데이터 공유는 사용자가 설정한 권한에 따라 관리되어 안전성과 협력 제공
- 연동 가족 간 채팅방을 통해, 건강 알림 제공 및 건강관련 소통을 강화


 <br>
 <br>

## 🚩최종 결과물 구현 화면
##### (1) 플랫폼 기본 화면 : 로그인 및 홈 화면, 건강정보 등록 옵션 화면 
![image](https://github.com/user-attachments/assets/47d4bb57-9a12-4234-937d-ef87e4d6a106)
##### (2) 복약관리 관련 화면
![image](https://github.com/user-attachments/assets/3a19f298-5809-4548-a6fb-7d2537c54576)
##### (3) 건강 데이터 등록 화면 (영양제/혈압혈당/스케줄 등록)
![image](https://github.com/user-attachments/assets/0259c49e-2d2b-4729-9380-fd5aebcb20c4)
##### (4) 건강 캘린더 화면 및 리워드 제공 화면
![image](https://github.com/user-attachments/assets/1be5654a-5873-4d08-96e2-4c27e55cdde3)
##### (5) 연동 가족 관련 화면
![image](https://github.com/user-attachments/assets/8078c98c-67db-4cec-b62d-6f452e8a17d5)

 <br>
 <br>

# 🎞️ 시연 동영상
[SWING 링크영상] (https://youtube.com/shorts/XkRm3YBgkGA?feature=share)  </br> 

 <br>
 <br>

# 💻 실행방법 
### 1) Frontend 실행 방법
Front 경로로 이동하여 모듈 설치
```
npm i
```
expo 앱 실행
```
npx expo start
```
### 2) Backend 실행 방법
JDK 17 버전 이용

IntelliJ IDEA 사용

Back/swingback 경로에서 의존성 다운로드
```
./gradlew build
```
```
Back/swingback/src/main/resources 경로
application.yml 에 batch,Oauth2 ,fcm, chatgpt 설정파일을 차례대로 설정
FCM 설정 SDK파일(firebase-notice.json)을 해당경로에 저장 

SwingbackApplication 실행
```
 <br>
 <br>


## 🔧 기술 스택
<img src="https://img.shields.io/badge/expo-%23000020.svg?&style=for-the-badge&logo=expo&logoColor=white" /> <img src="https://img.shields.io/badge/notion-%23000000.svg?&style=for-the-badge&logo=notion&logoColor=white" /> <img src="https://img.shields.io/badge/python-%233776AB.svg?&style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/react-%2361DAFB.svg?&style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/typescript-%233178C6.svg?&style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/spring-%236DB33F.svg?&style=for-the-badge&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/mysql-%234479A1.svg?&style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/amazon%20aws-%23232F3E.svg?&style=for-the-badge&logo=amazon%20aws&logoColor=white" /> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
