# 보강

다음주 (목) 17:00 이후 계속 진행될 예정(18:00 차 타고 갈것)

# software_engineering_week1 (OT)

소프트 웨어

-주문형 소프트웨어: 특정 고객 또는 기업 요구를 만족시키기 위해 제작한 소프트 웨어 ex) LMS 시스템
-패키지 소프트웨어: (usb, cd 기타 장치)패키지화하여 판매되는 소프트웨어 ex) Microsoft사의 기타 소프트웨어, POS 시스템
-임베디드: 하드웨어적인 성향이 강함 주로 기계장치에 이식됨 (메카트로닉스) 

어디에나 존재하는 SW ->IOT, 웨어러블(모바일, 노트북) 장비의 증가로 (유비쿼터스) 프로그램의 의존성 증가   

이러한 모두가 흔히 사용하는 프로그램의 구현에는 체계적인 설계가 필요함 

자료구조, 알고리즘, 기타 CS(Computer Science)에 대한 지식> 하드 코딩 

시스템:
-필요한 기능을 실현시키기 위하여 관련 요소를 어떤 법칙에 따라 조합한 집합체 (기계, 오퍼레이터, 전자회로, 작업절차, 문서)

-시스템은 어떤 특정한 목표를 함께 수행하는 서로 밀접한 관련이 있는 부분, 요소, 처리, 구성성분, 기능들의 집합 ex) 가족도 시스템이 될수 있다. 

-자연적시스템: 우주, 인체, 먹이사슬 
-인위적시스템 == 일반시스템(국가,사회) / 정보시스템(LMS, BMS)

-정보시스템: 데이터, 정보, 프로그램 

ex) 커뮤니케이션, 데이터베이스, 데이터 뱅크, 시스템 패키지  

ex)DBMS-> 보통 데이터베이스가 설치된 컴퓨터를 의미 (보통 운영체제 위에 DB프로그램이 설치 됨) 

But, 네이버의 경우 분리해둔다. 

- ISP(Information Stragetic Planning)

-BRP(업무 재설계)

-ERP(전사적자원관리) : 구매, 제조, 배송 판매 

-CRP(고객관리) 

-SCM(공급망 관리) 공급 업체의 공급 업체, 공급업체, 회사,고객, 고객의 고객

-SAP- 
독일의 소프트웨어 회사로 ERP 프로그램 만듦

-시스템의 기본요소-
입력, 처리, 피드백, 제어

-시스템 개발주기-

소프트웨어 생명주기 -> 소프트웨어 개발에 대한 기술적, 관리적 이슈를 다루는 작업

-개발 모델별 컴포넌트 프로세스, 부프로세스 존재

-서로 다른 목적

-서로 협력하여 전체 목적을 만족 

-시스템 개발 주기: 관리자적 관점 

-소프트웨어 개발 작업

기본활동 

유지보수-> 명세화-> 설계 -> 코딩-> 검증 ->(다시) 유지보수 

개발 특)

-명세화 어려움

-재사용 어려움

-예측 어려움

-유지보수 어려움

-소프트웨어의 위기-
소프트웨어의 수요가 급격히 증가하는것에 비해 기존의 패러다임으로 해결되지 않아 발생하는 문제 

소프트웨어 공학의 정의 
-소프트웨어의 개발과 운영, 유지보수, 소멸에 대한 체계적인 접근방법 
-소프트웨어 개발에 사용되는 방법이 아닌 반복 사용이 가능함 

소프트웨어 공학의 목표 

-복잡도 낮춤
-비용 최소화 
-개발 기간 단축 
-대규모 프로젝트 관리 
-고품질 소프트웨어 
-효율성 

c++ ->제어형 

c#, JAVA -> oop 특화 -> 자바 스프링 웹개발 ㅇㅇ -> 우리나라는 자바공화국이다 ->ㅠㅏ이썬은 대학원으로 ㅠㅠㅠㅠㅠ

따라서, 품질 좋은 소프트웨어를 최소의 비용으로  계획된 일정에 맞추어 개발해야함 

# software_engineering_week2

-프로세스의 중요성-

프로세스 없는 개발: Code-and-fix 
-설계하는 작업의 중요성을 깨닫지 못함 
-무계획 -> 작업 목표가 없다.
-체계적인 테스트 작업이나 풉질 보증 차원의 활동에 대한 필요성의 인식이 없음 

ex) 1학기 때 레고 마인드스톰 NXT V1 모델의 비주얼 프로그램밍으로 dijkstra algorithm을 구현하여 길찾기 로봇을 만들려고 하였다가 관련 정보 부족, 시간 부족으로 망했던 경험. -> 2학기에서 평생 놀림거리였음  

단계적 프로세스: 코딩에 치중하지 않고 요구분석, 설계, 코딩, 테스팅 등 정해진 절차를 따라 작업하는 것 

1.개발계획 

2.분석

3.설계

4.구현

5.테스팅 및 통합

6.유지 보수 

-품질보증: 요구분석 -> 설계 -> 코딩 -> 테스팅 ->유지보수 

프로젝트 관리 

1. 프로젝트 계획 
2. 지원 관리
3. 리스크 관리
4. 프로젝트 수행과 모니터링 ---> 늘어지는 범위에 혹은 기능 구현간 발생하는 개발 지연에 대한 즉각적인 기간 조정 필요  

품질-> 품질 관리 삼각지(시간, 비용, 범위)

프로세스 VS 방법론 

프로세스: 무언가의 대한 과정 -> 결과물 언급이 없음 

방법론: 어떻게 하는가가 중요 -> 프로세스의 구체적인 구현에 이름

# software_engineering_week3



