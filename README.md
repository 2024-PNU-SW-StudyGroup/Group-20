### 1. 프로젝트 소개
#### 1.1. 개발배경 및 필요성
 현재 전 세계적으로 환경 문제와 지속 가능성에 대한 관심이 증가하고 있습니다. 탄소 배출량 계산, 환경 인증, 친환경 소비 촉진 등은 개인과 기업이 환경 영향을 줄이는 데 필수적인 도구로 자리 잡고 있습니다.
이 프로젝트는 이러한 사회적 요구에 부응하여 탄소 배출량을 손쉽게 계산하고, 사용자가 친환경 활동을 실천할 동기를 부여하며, 지속 가능한 라이프스타일을 장려하기 위해 탄소 배출량 계산 및 관리 시스템을 개발합니다.
<br/>

#### 1.2. 개발목표 및 주요내용
 이 프로젝트의 목표는 다음과 같습니다.<br/>
1. 사용자 친화적인 탄소 배출량 계산 및 인증 시스템 구축.<br/>
2. 탄소 감축 활동에 대한 보상으로 포인트를 제공하고, 이를 친환경 제품과 교환할 수 있는 플랫폼 개발.<br/>
3. 사용자의 친환경 활동을 독려하고 관련 커뮤니티를 활성화.

 주요 내용은 다음과 같습니다<br/>
1.탄소 배출량 계산 알고리즘 설계 및 구현.<br/>
2.환경 인증 프로세스 및 인증서 발급 기능 개발.<br/>
3.포인트 적립 및 친환경 제품 교환이 가능한 플랫폼 제공.<br/>
4.사용자의 탄소 감축 활동을 기록하고 공유할 수 있는 소셜 기능 추가.
<br/>

#### 1.3. 세부내용
프로젝트 소개: 프로젝트의 배경, 목표, 주요 기능 설명.<br/>
시스템 아키텍처: 주요 기술 스택 및 시스템 구성도 제공.<br/>
사용 방법: 탄소 배출량 계산 방법, 포인트 적립 및 교환 절차 등.<br/>
결과물: 기대 효과 및 주요 성과 공유.
<br/>

#### 1.4. 기존 서비스(상품) 대비 차별성
통합 플랫폼 제공: 단순한 계산을 넘어 인증, 포인트 시스템, 친환경 제품 교환까지 모든 기능을 하나의 플랫폼에서 제공.<br/>
사용자 참여 독려: 환경 기여도를 포인트로 시각화하여 사용자의 동기 부여 강화.<br/>
소셜 기능 연계: 사용자가 자신의 탄소 감축 활동을 기록하고 공유할 수 있도록 지원, 커뮤니티 활성화를 통해 지속 가능성에 대한 인식을 확산.<br/>
<br/>

#### 1.5. 사회적가지 도입 계획
환경 인식 제고: 플랫폼 사용을 통해 사용자들이 자신의 탄소 발자국을 직관적으로 이해하고 줄이는 데 기여.<br/>
지역 사회 활성화: 친환경 제품 교환을 통해 지역 사회의 소규모 친환경 제조업체와의 협력 증진.<br/>
교육적 가치: 탄소 배출량 관리와 지속 가능성에 대한 정보를 사용자에게 제공, 전 세대를 아우르는 환경 교육의 장 마련.<br/>
지속 가능한 경제 구축: 친환경 소비를 장려하여 기업의 지속 가능 경영 확산에 기여.
<br/>


### 2.상세설계
#### 2.1. 시스템 구성도
<img width="600px" alt="시스템 구성도" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/f0e7c7ed-deb1-47ee-8090-32f712fa2b23">
<br/>

#### 2.3. 사용기술
| 이름                  | 버전    |
|:---------------------:|:-------:|
| Python                | 3.8.0   |
| Django                | 3.2.9   |
| Django Rest Framework | 3.12.0  |
| Node.js               | 16.16.0 |
| Vue.js                | 2.5.13  |
<br/>


### 3. 개발결과
[코딩역량강화플랫폼 Online Judge](http://10.125.121.115:8080/)를 예시로 작성하였습니다.
#### 3.1. 전체시스템 흐름도
- 유저 플로우 차트
  > 코딩 역량강화 플랫폼의 회원가입 부분만 작성했습니다. <br/>
  > 사용자의 행동 흐름을 도식화하여 보여줍니다.
  <img width="400px" alt="유저 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/c8de7c98-efd8-4f64-a39a-720faabccd78" />

- 테스크 플로우 차트
  > 코딩 역량강화 플랫폼의 로그인 부분만 작성했습니다. <br/>
  > 주요 테스크의 프로세스를 도식화하여 보여줍니다.
  <img width="400px" alt="테스크 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/b83502a9-032d-4453-8687-428d54643610" />

- 시스템 플로우 차트
  > 코딩 역량강화 플랫폼의 로그인 부분만 작성했습니다. <br/>
  > 테스크의 흐름에 따른 데이터 처리를 도식화하여 보여줍니다.
  <img width="600px" alt="시스템 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/1bfb66f0-446c-4450-8a81-a78bfe5ac9ce" />

  
- IA(Information Architecture)
  > 정보나 시스템의 구조를 도식화하여 보여줍니다. <br/>
  <img width="600px" alt="IA" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/07d842fe-fb73-4079-97a3-58b2495ff331" />

<br/>

#### 3.2. 기능설명
##### ` 메인 페이지 `
-메인 페이지<br/>
탄소 배출량 계산기<br/>

사용자가 입력한 데이터(교통, 에너지 소비 등)를 바탕으로 탄소 배출량을 계산.<br/>
계산 결과와 절감 목표를 그래프로 시각화.<br/>
환경 인증 및 포인트<br/>

환경 인증서를 발급받은 사용자는 포인트를 적립.<br/>
포인트는 대시보드에서 확인 가능.<br/>
친환경 제품 교환 섹션<br/>

사용 가능한 포인트에 따라 선택 가능한 제품 목록 제공.<br/>
제품 선택 후 교환 프로세스를 진행.<br/>
기능 페이지 상세화<br/>
탄소 감축 목표 관리<br/>

사용자가 연간 목표를 설정하고, 이를 달성하기 위한 제안 제공.<br/>
소셜 기능<br/>

사용자의 인증 활동을 공유할 수 있는 커뮤니티 제공.<br/>
다른 사용자와 비교하거나 응원할 수 있는 기능 포함.
<br/>


#### 3.3. 기능명세서

|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 탄소 배출량 계산기        |  - 사용자 데이터 기반 탄소 배출량 산출       |
| S2  | 환경 인증 발급            |- 탄소 감축 활동에 따라 인증서 발급          |
| S3  | 포인트 적립               | 	- 인증 활동에 따른 포인트 자동 적립        |
| S4  | 친환경 제품 교환          |- 적립된 포인트로 제품 교환 가능             |
| S5  | 커뮤니티 공유             | - 사용자 활동을 공유하고 응원 기능 제공      |
| S6  | 데이터 시각화             | - 그래프 및 차트를 통해 사용자 데이터를 분석 |


<br/>

#### 3.4. 디렉토리 구조
```
├── build/                      # webpack 설정 파일
├── config/                     # 프로젝트 설정 파일
├── deploy/                     # 배포 설정 파일
├── src/                        # 소스 코드
│   ├── assets/                 # 이미지, 폰트 등의 정적 파일
│   ├── pages/                  # 화면에 나타나는 페이지
│   │   ├── HomePage/           # 홈 페이지
│   │   ├── CalculatorPage/     # 탄소 계산기 페이지
│   │   ├── ExchangePage/       # 제품 교환 페이지
│   │   ├── components/         # 여러 페이지에서 공통적으로 사용되는 컴포넌트
│   ├── router/                 # 라우터
│   ├── store/                  # global state store
│   ├── styles/                 # 스타일
│   ├── utils/                  # 유틸리티 함수
├── static/                     # 정적 파일

```
<br/>


### 4. 설치 및 사용 방법
**필요 패키지**
- 위의 사용 기술 참고

```bash
$ git clone https://github.com/test/test.git
$ cd test/frontend
$ npm i
$ export NODE_ENV="development" # windows: set NODE_ENV=development
$ npm run build:dll
$ export TARGET="http://localhost:8000"  # windows: set NODE_ENV=http://localhost:8000
$ npm run dev
```
<br/>


### 5. 소개 및 시연영상
[<img width="700px" alt="소개 및 시연영상" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/162132cd-9af5-4154-9b9a-41c96cf5e8fd" />](https://www.youtube.com/watch?v=EfEgTrm5_u4)

<br/>

### 6. 팀 소개
| MEMBER1 | MEMBER2 | MEMBER3 |
|:-------:|:-------:|:-------:|
|<img width="100px" alt="MEMBER1" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/f5b5df2a-e174-437d-86b2-a5a23d9ee75d" /> | <img width="100px" alt="MEMBER2" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/fe4e8910-4565-4f3f-9bd1-f135e74cb39d" /> | <img width="100px" alt="MEMBER3" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/675d8471-19b9-4abc-bf8a-be426989b318" /> |
| member1@pusan.ac.kr | member2@gmail.com | member3@naver.com |
| 프론트앤드 개발 | 인프라 구축 <br/> 백앤드 개발 | DB 설계 <br/> 백앤드 개발 |


<br/>

















