# <Resume>

## **Channel**

**Github** : [https://github.com/Ko-udon](https://github.com/Ko-udon) ,[https://github.com/ehddn](https://github.com/ehddn)

## **Contact**

**Phone :** 010-7231-9001

**Email :** ehddn2202@gmail.com

## Project

### 위시마켓

원하는 선물로 고가의 상품을 펀딩 형식으로 제공하는 이커머스 프로젝트

2023.01.26 ~ 2023.03.09

https://github.com/WishMarket/WishMarket-BE

[WishMarket ](https://www.notion.so/WishMarket-08dd0910390a4256b20a9327771bf4ec) - 노션 정리 페이지

- 개발 인원 :  6명 (백엔드4 + 프론트2)
- 역할 : 백엔드 개발[상품  CRUD, 스케줄러 처리, 상품 펀딩 기능]
- Back-end :
    - `Java11, OpenJDK17.0.2`
    - `Spring Boot, Spring Batch, Spring Security, Spring Data JPA`
    - `Querydsl, Hibernate`
    - `Junit5, Mockito`
    - `Gradle`
    - `IntelliJ`
- Database : `MariaDB, Redis, H2`

- 개발 기간 : 2023.01.26 ~ 2023.03.09
- 성과 및 결과 :
    - 프론트엔드와 직접적인 협업과 다양한 백엔드 기술을 활용
    - AWS EC2, AWS RDS, AWS S3, Docker를 활용한 배포
    - Github Action을 통한 CI, CD 구축
    - Spring Batch, Spring Scheduler 활용한 주기적 데이터 처리
    - Redis를 활용한 데이터 캐시화
- 맡은 주요 기능 :
    - 정해진 시간에 베스트 상품 업데이트, 펀딩 만료 판단
        - 스프링 배치, 스케줄러 기능을 활용하여 매일 새벽 2시에 베스트 상품 목록을 업데이트
        - 매 정각마다 진행중인 펀딩들의 기간만료여부를 파악해 펀딩 실패 여부 업데이트
    - 사용자 찜목록 기능
        - 찜목록 추가, 조회, 삭제
        - 특정 유저의 찜목록 조회 기능
    - 다양한 상품 조회 기능
        - 카테고리별 상품 조회
        - 베스트 상품 조회
    
    - 펀딩 기능 구현
        - 펀딩 시작하기, 참여하기(이미 진행중인 펀딩에 대해서), 상세 정보 조회 등 기본적인 기능 구현
        - 특정 유저에 대한 무작위 펀딩 내역 조회
            - 몇몇 유저들은 인기유저(인플루언서)로 구분하여 해당 유저들을 대상으로 진행중인 펀딩을 조회시 매번 랜덤한 결과값을 반환함
    - 간단한 관리자 페이지
        - 상품 데이터를 db에 일일이 넣기에는 다소 무리가 있다고 생각
        - 상품 데이터를 직접 넣는 기능과 관리자 페이지를 추가, 작업 효율성 상승

## **Experience**

### 이벤트 플러스 추천 알고리즘 개발

2021.08.03 ~ 2021.10.01

- 행사 기획안을 토대로 대행사를 추천해주는 알고리즘 개발
- 맡은 역할 : 행사 기획서 자료를 정형 데이터화, 데이터 전처리, 추천 알고리즘 개발
- 기술 :`Python`  `R-Studio`
- 내용 : 행사 주최측과 대행사를 컨텍해주는 업체 ‘이벤트플러스’에서 그간 쌓인 데이터를 기반으로 주최측이 행사 견적을 입력시, 자동으로 대행사를 추천해주는 프로그램을 제작하였습니다. 처음 해보는 분야다 보니 사전에 추천 알고리즘에 대한 지식과 `R-Studio`  를 활용해 데이터 전처리를 해본 좋은 경험이였습니다.

### 데이터야놀자

2021.09.04 ~ 2021.10.17

- 데이터를 활용한 자유로운 주제의 발표회
- 맡은 역할 : 공공데이터 수집, 데이터 시각화, 기획, 팀장
- 기술 : `ElasticSearch` `Tableau`  `R-studio`
- 내용 : 공교육과 사교육에 관련된 공공데이터를 수집 및 활용하여 데이터 시각화와 지역구별 교육 현황에 관한 분석을 하여 시각화를 나타냈습니다. 최종적으로 지역구별 교육 만족도를 분석해 만족도 상승을 위한 교육과정 추천을 하였습니다. 처음으로 직접 팀장을 맡아 기획, 파트 배분 및 운영을 해보니 생각보다 쉽지 않았고 시각화 과정에서 어려워 하는 팀원의 일을 도와 세부 테스크 및 일정 조율을 하였습니다.
- 

[https://www.youtube.com/watch?v=QDV19lPrMGU&feature=youtu.be&themeRefresh=1](https://www.youtube.com/watch?v=QDV19lPrMGU&feature=youtu.be&themeRefresh=1)

### 학교 홈페이지 게임 제작, 운영

2022.03.18 ~ 2022.04.20

https://github.com/Ko-udon/Sumong_WebGame

- 학교 마스코트 캐릭터를 활용한 홍보용 게임 제작
- 맡은 역할 : 프로그래밍, 기획, QA
- 기술 : `Unity`  `WebGL`
- 내용 : 캐릭터를 사용해 캠퍼스 지도를 따라 이동하며 해당 학과, 전공에 대한 퀴즈를 푸는 형식의 게임을 제작하였습니다. 텍스트 박스와 객관식 퀴즈 로직, 그리고 직소 퍼즐 게임을 맡았습니다. 게임 초안을 자바스크립트 언어로 간단하게 제작 후 Unity 엔진에 WebGL라이브러리를 사용하였습니다.

## Work **Experience**

### 해피투씨유

어린이 핀테크 어플리케이션을 통해 어린이 금융 생활의 시작을 함께해주는 서비스 제공

2022.07.04 ~ 2022.08.26

ICT 영업부 / 인턴

- 서비스의 QA, 간단한 기능 개발
- MySQL 데이터베이스 조작, 앱 테스트케이스 작성 및 테스트 진행
- 정규 표현식을 사용한 비밀번호 설정 부분 개발

## **Skils**

- Language: `Java` `Python`  `C#` `C++`
- Backend :  `Spring` `Spring Batch` `Spring Scheduler` `Spring Data JPA` `Junit5, Mockito`
- Database : `MySQL` `MariaDB` `Redis`
- Infra :  `Elasticsearch`
- Tool : `Git`  `IntelliJ`  `Unity`  `UnrealEngine` `Rstudio` `Tableau` `Kibana`

### **Education**

- 배명고등학교 졸업
    
    (2014.03.03 ~ 2017.02.08)
    
- 상명대학교 게임학과 졸업
    
    (2017.03.01 ~ 2023.02.21)
    

### **Certificate**

- 정보처리기능사
    
    (2020.12.31 / 한국산업인력공단)
    
- 정보처리기사
    
    (2022.06.17 / 한국산업인력공단)
