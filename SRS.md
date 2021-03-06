# SoftwareRequirements Specification
==수정시작==

#### Version 1.0

#### May 14, 2018

#### Project Team:
  
  <4조>
  
  20131961 김민조
  
  20132569 조성주
  
  20132862 김현빈
  
  20134220 우정현
  
  20134695 김명규
  
  20162379 김성연
  
#### Document Author(s):
  
  김현빈
  
  조성주

### 1      소개(Introduction)

##### 1.1     목적(Purpose)

이 프로젝트의 목적은 파일을 비교하고 병합하는 것이 주요 기능인 SimpleMerge를 구현하는 것이다.

##### 1.2     프로젝트 범위(Project Scope)

설명되고 있는소프트웨어와 그목적에 대해간단하게 설명한다. 소프트웨어를 사용자 또는 기업의 목표, 비즈니스목표, 전략과연계시킨다. 별도의 비전과 범위 문서를 사용할 수 있다면 그 내용을 중복시키지 말고 그것을 참조하게 한다. 진화하는 제품의 특정 버전을 설명하는 SRS는 장기적인 전략적 제품 비전의 하위집합으로 자신만의 범위선언을 가지고 있어야 한다.

##### 1.3     참조(Reference)

WinMerge, WinDiff, BeyondCompare와 같은 유사한 현존하는 제품을 참조한다.

### 2      전체 설명(Overall Description)

##### 2.1     제품기능(ProductFeature)

제품이 가지고있는 주요기능 또는제품이 수행하는중요한 기능을나열한다. 상세한 내용은 SRS의 3번 절에 설명되어 있기 때문에, 여기에서는 추상적인 요약만 하면 된다. 요구사항의 주요 그룹과 그 그룹이 연결되어 있는 방법을설명하는 최상위 데이터 플로우 다이어그램, 유스케이스 다이어그램, 클래스 다이어그램 등이 도움이 된다.

##### 2.2     운영환경(OperationEnvironment)

하드웨어 플랫폼, 운영체계와 버전, 사용자, 서버와 데이터베이스의 지리적 위치 등과 같은 소프트웨어가 동작되는환경을 설명한다. 시스템이아무런 문제없이연동해야 하는다른 소프트웨어컴포넌트 또는애플리케이션을 나열한다.비전과 범위 문서는 추상적인 수준에서 이 정보를 포함하고 있을 수 있다.

##### 2.3     설계 및 구현 제약사항(Design and Implementation constraint)

개발자가 선택할수 있는사항을 제약하는모든 요소와각 제약조건의이유를 설명한다. 제약 조건은 다음과 같다.

l  반드시 사용하거나 피해야 하는 특정 기술, 툴, 프로그래밍 언어와 데이터 베이스

l  사용될 웹 브라우저의 유형과 버전과 같이 제품의 운영환경으로 인한 제약

l  필요한 개발 규칙 또는 표준(예를들면 고객의조직이 소프트웨어를유지보수 할예정이라면, 그 조직은 하청업체가따라야 하는 설계 표기법과 코딩 표준을 명시할 수 있다.)

l  이전 제품과의 호환성

l  비즈니스 규칙에 따른 제약

l  메모리 또는 프로세스의 제약, 크기, 무게, 비용과 같은 하드웨어의 제약

l  기존 제품을 개선하는 경우에 따라야 하는 기존 사용자 인터페이스 규칙

l  XML과 같은 표준 데이터 교환 형식

##### 2.4     사용자 문서(User Documentation)

소프트웨어와 함께제공할 사용자문서를 나열한다. 사용자 문서로는 사용자 매뉴얼, 온라인도움말, 교재 등이 있으며 따라야 하는 문서 전달 형식, 표준 또는 툴이 있다면 그것들을 설명한다.

##### 2.5     가정과 종속관계(Assumptions andDependencies)

가정은 물증또는 확실한지식이 없는경우에 사실이라고믿는 선언으로, 이 가정이 잘못되거나 이것을 공유하지 않는다면 문제가 발생될 수 있기 때문에 어떤 가정은 프로젝트 위험으로 간주된다. SRS를 읽은 사람은 그 제품이 특정 사용자 인터페이스 규칙을 따르고 있다고 가정할 수 있는 반면에, 다른사람은 다른생각을 할수 있다. 개발자는특정 기능들이 사용자 정의로 작성된다고 가정하지만, 분석가는 이것들이 이전의 프로젝트에서 재사용된다고 믿고 있으며 프로젝트 관리자는 상업용 함수 라이브러리를 구매해야 한다고 생각할 수 있다.

운영체계의 다음버전 발표또는 산업표준발표와 같이프로젝트가 통제할수 없는외부 요소에어느정도 종속되는지를설명한다. 다른 프로젝트가 개발하고 있는 어떤 컴포넌트를 시스템에 통합하려고 한다면, 그프로젝트가 해당컴포넌트를 제시간에제공하는 것을기다려야 한다. 이런 종속관계가 프로젝트 계획과 같은 다른 문서에 이미 정리되어 있다면 그 문서들을 참조하도록 한다.

### 3      유스케이스(Usecase)

##### 3.1     Usecase 이름

가       요약시나리오

나       이벤트 흐름

​	①      기본 흐름

​	②      예외흐름

다       사전조건

라       사후조건

마       쟁점

바       현실화

### 4      시스템 특징(System Feature)

##### 4.1     시스템특징 X

3.X 철자확인과 같은몇 단어만으로특징을 설명한다. 각각의 시스템 특징에 대해서는 3.x.1 에서 3.x.3까지의 하위절을 반복한다.

###### 가       설명과 우선순위(Description and Priority)

​	기능에 대해간단하게 설명하고그것이 높은우선순위인지 낮은우선순위인지를 나타낸다. 우선순위는 프로젝트 중에변할 수 있는 동적인 것으로, 요구사항관리 툴을사용한다면 요구사항특성의 우선순위를정의한다.

###### 나       자극/응답 순서(Stimulus/Response Sequence)

​	입력 자극(사용자 행동, 외부 장비의 신호 또는 다른 자극)의순서와 이기능에 대한동작을 정의하는시스템 반응을나열한다. 이 자극들은 유스케이스의 초기 대화단계 또는 외부 시스템 이벤트에 해당한다.

###### 다       기능요구사항(Functional requirement)

​	이 기능과관련된 상세한기능 요구사항을항목으로 나열한다. 이것들은 사용자가 기능의 서비스를 수행하기 위해또는 유스케이스를 수행하기 위해 사용하는 소프트웨어의 기능들이다. 제품이 예상되는 에러 상황, 무효한입력과동작에대해 어떻게응답해야 하는지를 설명한다. 각각의 기능 요구사항에 유일한 레이블을 붙인다.

### 5      외부 인터페이스 요구사항(External InterfaceRequirement)

##### 5.1     사용자 인터페이스

l  시스템이 요구하는 각각의 사용자 인터페이스의 논리적인 특징을 설명한다. 따라야 할 GUI표준또는 제품스타일가이드에대한 참조

l  폰트, 아이콘, 버튼 레이블, 이미지, 색상 체계, 필드탭 순서, 공통으로 사용되는 컨트롤 등에 대한 표준

l  화면 레이아웃 또는 해상도 제약 조건

l  도움말 버튼과 같이 모든 화면에 나타나는 표준 버튼, 기능 또는 탐색 링크

l  단축키

l  메시지 표시 규칙

l  소프트웨어 번역을 원활하게 하는 레이아웃 표준

l  시각장애자를 위한 기능

사용자 인터페이스의설계 상세내용은 SRS가 아닌 별도의 사용자 인터페이스 명세에 문서로 정리한다.

##### 5.3     소프트웨어 인터페이스(Software Interface)

이 제품과다른 소프트웨어컴포넌트(데이터베이스, 운영체제, 툴, 라이브러리, 통합 상업용 컴포넌트)간의 연결을설명한다. 소프트웨어 컴포넌트 간에 교환되는 메시지, 데이터와컨트롤 항목을설명한다. 외부 소프트웨어 컴포넌트가 요구하는 서비스와 컴포넌트 간의 통신 성격을 설명하고 소프트웨어 컴포넌트들이 공유할 데이터를 파악한다.

=> Jnuit 및 EasyMock를 이용하여 프레임워크 테스트를 한다. GUI 구성요소를 MVT 아키텍처 패턴을 사용하여 설계한다.

### 6      기능 이외의 다른 요구사항(Other Nonfunctional Requirement)

##### 6.1     성능 요구사항(PerformanceRequirement)

다양한 시스템운영에 대한특정 성능요구사항을 설명한다. 개발자들이 적합한 설계를 선택할 수 있게 만든 논리를설명한다. 예를 들면 엄격한 데이터 베이스 응답시간 때문에 설계자들은 여러 위치에 데이터베이스를 미러링 하거나 더 빠른 질의응답을 위해 데이터베이스 테이블의 정규화를 해제시킬 수 있다. 지원되어야 하는 초당 트랜잭션수, 응당 시간, 연산의정확도와 실시간시스템의 속도조절관계를 명시한다. 또한 메모리와 디스크 공간 요구사항,동시 사용자 부하 또는 데이터베이스 테이블에 저장되는 최대 row 수를 명시한다.

성능 요구사항은가능한 분명하게계량적으로 표현한다. 예를 들면 “MS XP에서 1GHz P4환경에서 메모리가 60%의여유가 있는 상태에서 데이터 베이스의 질의 중 95%가 3초 내에 완료된다” 는 식으로 표현한다.

### 7      다른 요구사항(Other Requirement)

SRS의다른 부분에서는다루지 않는모든 요구사항을정의한다. 예로 들면 국제화 요구사항, 법적 요구사항 등이 있다. 제품설치, 구성, 시작과종료, 복구와 장애극복, 로깅과 모니터링 운영에 대한 요구사항을 다루는 운영, 관리와유지보수에 대한 내용을 추가할 수 있다.

### 8   부록 : 문제 목록(Issues List)

해결되어야할 남아있는 요구사항문제들의 동적인 목록이다. 문제들로 TBD, 미결정, 필요한 정보, 해결이 필요한충돌등으로 표시된항목들이 포함된다. 이것이반드시 SRS의일부가 될 필요는없지만, 일부 기업들은 SRS에항상 TBD목록을첨부한다. 이 문제들을적극적으로 해결해서 고품질의 SRS의기본 사항을 결정하는데 방해가 되지않게 해야 한다
