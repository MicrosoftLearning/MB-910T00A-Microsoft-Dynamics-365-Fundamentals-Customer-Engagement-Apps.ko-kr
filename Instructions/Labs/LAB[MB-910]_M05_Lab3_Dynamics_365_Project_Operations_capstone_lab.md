---
lab:
    title: '랩 5.3: Dynamics 365 Project Operations 과정 수료 랩'
    module: '모듈 5: Dynamics 365 Project Operations의 기본 사항 파악'
---

모듈 5: Dynamics 365 Project Operations의 기본 사항 파악
========================

## 연습 랩 5.3 - Dynamics 365 Project Operations 과정 수료 랩

## 랩 시나리오

ABC사는 보안 장비 제조, 판매, 설치, 서비스 전문 업체입니다. ABC의 제품으로는 실내 및 실외용 보안 카메라, 수분 및 화재 센서, 모니터링 서비스 등이 있습니다. 

ABC에서는 Dynamics 365 애플리케이션을 사용하여 영업, 서비스 등 회사 내 조직의 다양한 부문에서 모든 고객을 응대하고 있습니다. 

**영업 및 마케팅**

ABC사는 대상 지정 마케팅 캠페인을 통해 개인 고객을 대상으로 직접 마케팅을 진행합니다. 구/군/시를 비롯한 기타 요인을 기준으로 마케팅 대상 고객을 지정합니다. 마케팅 자료는 전자 메일로 전송되며, 고객이 전자 메일과 상호 작용하는 방식에 따라 적절한 안내 정보가 제공됩니다. 

ABC의 소형 제품 중에는 판매점을 통해 판매되는 것도 있지만 대다수 제품은 내부 영업 직원이 소비자에게 직접 판매합니다.

ABC의 주요 고객은 다음의 두 분야에 해당됩니다. 

- **개인 고객:** 대개 개별 구성 요소나 전체 홈 솔루션을 구매하는 고객입니다. 이러한 고객의 경우 대개 영업 주기가 더 짧으며 소셜 미디어, 웹 사이트, 추천, 잠재 고객의 직접 문의 등을 통해 고객을 확보하게 됩니다. 개인 고객은 보통 특정 제품이나 소형 설치 제품을 주로 구매하기 때문에 영업 주기는 일반적으로 며칠이나 몇 주 정도입니다. 

- **기업 고객:** 주로 특수한 맞춤형 비즈니스 솔루션을 구매해야 하는 고객입니다. 기업 대상 영업은 대개 여러 지역에서 진행되며 관련 커뮤니케이션도 함께 진행됩니다. 그리고 프로젝트를 완료하는 데 여러 리소스가 필요한 경우가 많습니다. 일반적으로 기업 고객 대상 영업 주기는 개별 고객보다 더 길며 영업 과정에서 사용되는 리소스도 훨씬 더 많습니다. 

ABC사의 모든 판매자는 주력 영업 영역에 관계없이 고객에게 제품을 판매할 때 필요한 모든 도구, 리소스 및 지침을 활용할 수 있어야 합니다. 

**시스템 설치:**

보안 장비의 설치 프로세스는 해당 장비를 구매한 고객의 유형에 따라 달라집니다. 

- **개인 고객:** 개인 고객이 구매하는 장비 설치는 대개 하루 안에 완료되므로 내부 직원이 설치를 진행합니다. 제품이 판매되면 작업 주문이 작성되며, 그러면 적격 기술자를 확인하여 설치를 예약합니다. 

- **기업 고객:** 기업 고객 대상 장비 배포는 몇 달이 걸릴 수도 있으므로 프로젝트 관리자가 매일 진행되는 작업을 감독해야 합니다. 프로젝트 관리자는 구체적으로 프로젝트 계획 작성, 프로젝트 팀 정의, 리소스 예약 등의 작업을 파악해야 합니다. 

**서비스 및 지원:**

ABC사는 시스템을 설치하고 나면 판매 후 지원을 제공합니다. 고객은 문제 발생 시 고객 지원에 문의할 수 있습니다. 그러면 에이전트가 원격으로 고객을 응대하여 문제 해결을 시도합니다. 원격으로 문제를 해결할 수 없으면 지원 에이전트는 작업 주문으로 문제를 에스컬레이션할 수 있습니다. 그러면 서비스가 예약되어 적격 현장 기술자가 문제 해결 작업을 진행합니다. 
## 목표

ABC사의 기업 고객 담당 판매자는 보안 팀에서 특수한 맞춤형 비즈니스 솔루션을 사용해야 하는 고객을 위주로 영업을 진행합니다. 따라서 기업 대상 영업은 대개 여러 지역에서 진행되며 관련 커뮤니케이션도 함께 진행됩니다. 그리고 프로젝트를 완료하는 데 여러 리소스가 필요한 경우가 많습니다. ABC의 기업 고객 대상 영업 주기는 몇 달이 걸릴 수도 있으며, 프로젝트를 실행하는 데 여러 리소스가 필요한 경우가 많습니다. 

그리고 기업 고객에게 시스템을 판매한 후에도 프로젝트를 구현하는 데 추가로 몇 달이 걸립니다. 각 프로젝트는 프로젝트 관리자에게 할당되며, 프로젝트 관리자는 프로젝트 계획 및 매일 진행되는 작업을 감독합니다. 프로젝트 관리자는 구체적으로 프로젝트 계획 작성, 프로젝트 팀 정의, 리소스 예약 등의 작업을 파악해야 합니다. 

이 연습에서는 기업 고객 담당 판매자 역할을 맡아 고객에게 고급 사용자 지정 보안 솔루션을 판매해야 합니다. 최근 Consolidated Sample이라는 업체에서 전화로 문의를 해 왔습니다. 이 잠재 고객은 모든 지점 위치에 사용할 완전 통합형 보안 솔루션을 구매하고 싶다고 합니다. Consolidated Sample에 해당하는 잠재 고객을 시스템에 입력하고, 이 고객을 대상으로 프로젝트 판매 주기를 진행한 후 해당 프로젝트를 만들어야 합니다. 

이 랩에서는 다음 작업을 완료합니다.

- 프로젝트 영업 기회와 관련된 일상 활동 관리 

- 프로젝트 견적 추가, 작성 및 정의 

- 프로젝트 계약 생성 

- 프로젝트 만들기 및 프로젝트 팀 정의 

## 랩 설정

  - **소요 시간**: 45분

## 지침

## 실습 1: 프로젝트 견적 및 프로젝트 추정 작성

프로젝트 영업 기회를 사용하면 진행 가능성이 있는 프로젝트와 관련된 대략적인 세부 정보를 캡처할 수 있습니다. 프로젝트 관련 세부 정보가 충분히 인되면 프로젝트 견적을 작성할 수 있습니다. 프로젝트 견적에는 다양한 역할, 타임라인, 가격 책정 련 세부 정보가 포함되는 경우가 많습니다. 이렇게 작성된 프로젝트 견적을 고객에게 제공합니다. 또한 프로젝트 견적을 토대로 하여 판매 대상 프로젝트와 연관된 프로젝트 계획도 작성할 수 있습니다. 그러면 프로젝트 판매 후에 시간을 절약할 수 있습니다. 프로젝트와 관련이 있는 대다수 세부 정보가 이미 캡처된 상태이기 때문입니다.

이 연습에서는 프로젝트를 만들고 프로젝트 견적 관련 세부 정보를 정의합니다. 

### 작업 1: 프로젝트 견적 작성  

1. 프로젝트 영업 기회 레코드에서 **견적** 탭을 선택합니다. 

2. 견적 하위 표에서 **새 견적** 단추를 클릭합니다.

3. 새 견적 레코드를 연 후에 견적의 **제품 가격 목록** 필드를 **US 청구 요금**으로 설정합니다. 

4. **견적 라인** 탭을 선택합니다.

5. **시스템 구현** 품목을 선택하여 엽니다. 

6. **프로젝트** 필드에서 **새 프로젝트**를 선택합니다. 

7. **프로젝트 빨리 만들기** 화면에서 다음과 같이 프로젝트를 완성합니다.

	- **이름:** 전 세계 지점 구현 - 사용자 이니셜

	- **프로젝트 관리자:** 자신의 사용자 레코드 선택

	- **일정 템플릿:** 기본 작업 템플릿

	- **계약 단위:** Fabrikam US

	- **예상 시작 날짜:** 오늘부터 1주일 후

	- **예상 노동 비용:** $ 175,000

	- **예상 경비 비용:** $ 50,000

	- **예상 총 비용:** $ 225,000

8. **저장 후 닫기** 단추를 선택합니다.

9. 다음으로는 프로젝트에 할당되는 특정 역할을 대상으로 요금을 청구할 수 있는지 여부를 정의합니다. **청구 가능한 역할** 탭을 선택합니다.

10. **로봇 엔지니어** 역할을 선택하여 열고 대금 청구 유형을 청구 불가능으로 설정합니다.

11. **명령 모음**에서 **저장 후 닫기** 단추를 선택합니다.

12. **견적 라인 세부 정보** 탭을 선택합니다.

13. 하위 표에서 **새 견적 라인 세부 정보** 단추를 클릭합니다.

14. 다음과 같이 **견적 라인 세부 정보** 항목을 완성합니다.

	- **설명:** 통신 라인 실행 - 사용자 이니셜

	- **거래 클래스:** 시간

	- **역할:** 네트워크 기술자

	- **범주:** 시간

	- **시작 날짜:** 오늘부터 1개월 후

	- **종료 날짜:** 오늘부터 2개월 후

	- **리소스 조달 단위:** Fabrikam US

	- **단위:** 시간


15. **저장 후 닫기** 단추를 선택하여 라인 세부 정보 항목을 닫습니다. 

16. **명령 모음**에서 **저장 후 닫기** 단추를 선택합니다. 


**참고:** 다음 작업에서 사용할 수 있도록 프로젝트 견적을 열어 두세요. 


### 작업 2: 프로젝트 견적 종료 및 프로젝트 계약 만들기

이 작업에서는 앞에서 만든 프로젝트 견적을 종료하고 프로젝트 계약을 변환합니다. 프로젝트 계약은 프로젝트 실행 중에 활용할 수 있습니다. 


1. **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트 견적 레코드가 열린 상태로 명령 모음에서 **성공으로 종료** 단추를 선택합니다. 

2. **견적을 종료하시겠습니까?** 화면에서 **확인**을 선택합니다.

3. 견적이 종료되면 새로 작성된 **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트 계약이 표시됩니다. 

 

**참고:** 다음 작업에서 사용할 수 있도록 프로젝트 계약을 열어 두세요. 

## 실습 2: 프로젝트 관리

Project Operations의 프로젝트 판매 기능을 활용하는 경우의 이점 중 하나는 영업 프로세스 중에 프로젝트를 만들 수 있다는 것입니다. 이렇게 만든 프로젝트는 프로젝트 견적, 프로젝트 계약 등의 다양한 영업 관련 레코드에서 액세스할 수 있습니다. 

이 연습에서는 프로젝트 세부 정보 정의, 프로젝트 팀 정의, 대략적인 프로젝트 작업 결정 등 프로젝트와 관련된 몇 가지 초기 작업을 관리합니다. 


### 작업 1: 기본 프로젝트 데이터 관리 

1. **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트 계약이 열린 상태로 **관련 항목** 탭을 선택합니다. 

2. 표시되는 메뉴에서 **프로젝트**를 선택합니다.

3. **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트를 엽니다. 

4. **프로젝트 서비스** 비즈니스 프로세스 흐름에서 **신규** 스테이지를 선택하고 **다음 스테이지** 단추를 선택하여 **견적** 스테이지로 이동합니다. 

5. **견적** 스테이지에서 **예상 완료 날짜** 필드의 값을 **오늘부터 6개월 후**로 설정합니다. 

6. **다음 스테이지** 단추를 선택하여 **계획** 스테이지로 이동합니다. 

 
### 작업 2: 프로젝트 팀 만들기

각 프로젝트에는 프로젝트 실행을 지원할 구성원이 소속된 팀이 할당됩니다. 이 작업에서는 프로젝트 팀 구성원으로 추가할 리소스를 정의합니다. 

 
1. **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트 레코드가 열린 상태로 **팀** 탭을 선택합니다.

2. **모든 팀 구성원** 하위 표에서 **+ 새로 만들기** 단추를 선택합니다.

3. 다음과 같이 팀 구성원 레코드를 구성합니다.

	- **위치 이름:** 로봇 엔지니어 – 사용자 이니셜

	- **예약 가능한 리소스:** Allison Dickson

	- **역할:** 로봇 엔지니어

4. 저장 후 닫기 단추 옆의 화살표를 선택합니다. 표시되는 메뉴에서 **저장 및 새로 만들기**를 선택합니다.

5. 다음과 같이 다음 구성원 레코드를 구성합니다.

	- **위치 이름:** 소프트웨어 엔지니어 – 사용자 이니셜

	- **예약 가능한 리소스:** Bob Kozak

	- **역할:** 소프트웨어 엔지니어

6. 저장 후 닫기 단추 옆의 화살표를 선택합니다. 표시되는 메뉴에서 **저장 및 새로 만들기**를 선택합니다.

7. 다음과 같이 팀 구성원 레코드를 구성합니다.

	- **위치 이름:** 네트워크 기술자 – 사용자 이니셜

	- **예약 가능한 리소스:** Dianna Woodward

	- **역할:** 네트워크 기술자

8. **저장 후 닫기** 단추를 선택합니다.


### 작업 3: 프로젝트 일정 정의

프로젝트를 정의할 때 수행하는 또 다른 중요한 작업으로는 프로젝트 작업 및 일정 정의가 있습니다. 이 작업에서는 프로젝트 작업을 몇 개 추가하고 각기 다른 역할과 연결합니다. 


1. **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트가 열린 상태로 **일정** 탭을 선택합니다. 

2. 일정 하위 표의 도구 모음에서 **+ 추가** 단추를 선택합니다. 

3. 표시되는 행에서 **이름** 필드의 값을 **시스템 개발**로 설정합니다.

4. 일정 하위 표의 도구 모음에서 **+ 추가** 단추를 다시 선택하여 다른 항목을 추가합니다. 

5. 다음과 같이 항목을 구성합니다.

	- **이름:** 시스템 레이아웃 만들기

	- **작업량:** 25

6. 일정 하위 표의 도구 모음에서 **+ 추가** 단추를 다시 선택하여 다른 작업을 추가합니다. 

7. 다음과 같이 항목을 구성합니다.

	- **이름:** 카메라 디자인

	- **선행 업무:** 시스템 레이아웃 만들기

	- **작업량:** 50

8. 일정 하위 표의 도구 모음에서 **+ 추가** 단추를 다시 선택하여 마지막 작업을 추가합니다. 

9. 다음과 같이 항목을 구성합니다.

	- **이름:** 디자인 확인 및 승인

	- **선행 업무:** 카메라 디자인

	- 작업량: 8 

 
**참고:** 다음 작업에서 옵션을 추가로 수정할 것이므로 일정 탭을 계속 표시해 두세요. 


### 작업 4: 프로젝트와 리소스 연결

프로젝트 일정 정의 과정에서 인력 배치 요구 사항을 충족하는 데 사용할 리소스 유형을 지정할 수 있습니다. 실제로 명명된 리소스를 지정할 수도 있고, 나중에 명명된 리소스로 바꿀 일반 리소스를 지정할 수도 있습니다. 이 작업에서는 앞에서 만든 프로젝트 작업용으로 명명된 리소스와 일반 리소스를 모두 정의합니다. 

1. 필요한 경우 **전 세계 지점 보안 구현 - 사용자 이니셜** 프로젝트를 열고 **일정** 탭을 선택합니다. 

2. 앞서 추가한 **시스템 레이아웃 만들기** 작업을 찾고 **리소스** 필드를 선택합니다. 

3. 표시되는 메뉴에서 **만들기**를 선택합니다. 

4. 다음과 같이 다음 프로젝트 팀 구성원을 구성합니다.

	- **위치 이름:** 일반 로봇 엔지니어 – 사용자 이니셜

	- **예약 가능한 리소스:** 일반 리소스

	- **역할:** 로봇 엔지니어

5. **저장 후 닫기** 단추를 선택합니다. 

6. **일반 로봇 엔지니어 - 사용자 이니셜** 리소스가 리소스 필드에 추가되었는지 확인합니다. 

7. **카메라 디자인** 작업을 찾아서 **리소스** 필드를 선택합니다. 

8. 표시되는 메뉴에서 **만들기**를 선택합니다. 

9. 다음과 같이 다음 프로젝트 팀 구성원을 구성합니다.

	- **위치 이름:** 일반 로봇 엔지니어 – 사용자 이니셜

	- **예약 가능한 리소스:** 일반 리소스

	- **역할:** 로봇 엔지니어

10. **저장 후 닫기** 단추를 선택합니다. 

11. **디자인 확인 및 승인** 작업을 찾아서 **리소스** 필드를 선택합니다. 

12. 표시되는 메뉴에서 **Allison dickson**을 선택합니다. 


축하합니다. Dynamics 365 Project Operations에서 프로젝트를 판매하고 만드는 과정을 완료했습니다. 이제 프로젝트 관리자가 리소스 예약, 프로젝트 일정 모니터링, 시간과 경비 관리 등 프로젝트의 다양한 측면을 관리할 수 있습니다. 

 

 
