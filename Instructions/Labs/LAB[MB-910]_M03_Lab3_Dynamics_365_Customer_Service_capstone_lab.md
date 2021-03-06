---
lab:
    title: '랩 3.3: Dynamics 365 Customer Service 캡스톤 랩'
    module: '모듈 3: Dynamics 365 Customer Service의 기본 사항 파악'
---

모듈 3: Dynamics 365 Customer Service의 기본 사항 파악
========================

## 연습 랩 3.3 - Dynamics 365 Customer Service 캡스톤 랩

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

고객이 사용하는 장비에서는 문제가 자주 발생합니다. 발생하는 문제는 ABC사의 지원 센터에 보고됩니다. 문제는 여러 가지 방식으로 보고될 수 있습니다. 가령 장비에서 문제를 미리 보고할 수 있습니다. 문제가 보고되면 에이전트는 원격으로 문제 해결을 시도합니다. 원격으로 문제를 해결할 수 없으면 문제 해결을 위해 현장 기술자가 파견됩니다. 최근 작동이 중단된 센서 수리 건이 많이 발생했습니다. 원인을 파악한 결과 소프트웨어 버그 때문임이 확인되었습니다. 그래서 다른 에이전트가 같은 문제를 처리할 때 참조할 수 있는 참조 문서를 만들려고 합니다. 

이 랩에서는 지원 센터 에이전트 역할을 맡아 고객이 보고한 문제 관련 작업을 처리합니다. 최근 Piper Smith 고객이 전화로 시스템의 센서 하나가 작동하지 않는다는 문제를 보고해 왔습니다. 여러분은 Piper 고객의 통화를 로그하고 문제 해결 방법을 찾아야 합니다. 

이 랩에서는 다음 작업을 완료합니다.

- 참조 문서 만들기 

- 고객 서비스 허브를 사용하여 서비스 케이스 관리

- 서비스 케이스 작성 및 로깅 

- 수명 주기 전반에 걸쳐 서비스 케이스 레코드 관리 

## 랩 설정

  - **소요 시간**: 45분

## 지침

## 실습 1: 참조 문서 만들기 및 게시

### 작업 1: 참조 문서 만들기

1. **Dynamics 365 Customer Service 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다. 

2. 화면 왼쪽의 탐색 영역에서 **참조 문서**를 선택합니다. 

3. 각 스테이지의 참조 문서를 쉽게 확인하려면 **내 활성 문서** 옆의 드롭다운 화살표를 선택합니다. 

4. **초안 문서**를 선택합니다. 

5. 보기 선택에서 **승인된 문서**를 선택합니다.  

6. 보기 선택에서 **내 활성 문서**로 다시 전환합니다.

7. **명령 모음**에서 **새로 만들기** 단추를 선택합니다. 세 레코드가 열리면 위쪽의 레코드 머리글에 있는 **상태 설명** 필드 옆의 드롭다운 화살표를 선택합니다. **언어**를 **영어 - 미국**으로 설정합니다.

8. 다음과 같이 문서를 완성합니다.

	- **제목:** 센서 미작동 - 사용자 이니셜

	- **키워드:** 센서, 파손, 미작동

	- **설명:** 센서가 작동하지 않는 상황에 참조할 수 있는 문서입니다. 

9. **콘텐츠 디자이너** 텍스트에 다음 텍스트를 입력합니다.   

	현재 센서가 작동하지 않음

	센서가 제대로 작동하지 않을 때는 다음 단계를 수행합니다.

	1. 디바이스의 배터리를 찾아서 교체합니다. 

	2. 전원 단추를 3초 동안 누릅니다. 

	3. 디바이스가 관리 모드로 열립니다. 

	4. 표시등이 빨간색에서 파란색으로 바뀔 때까지 페어링 단추를 길게 누릅니다. 

	5. 재설정 단추를 누릅니다. 

	디바이스가 다시 부팅된 후 온라인 상태로 다시 설정됩니다. 

10. 콘텐츠 편집기에서 현재 센서가 작동하지 않음 텍스트를 선택합니다.

11. 글꼴 크기를 **22**로 변경하고 **굵게** 단추를 선택합니다. 

12. **명령 모음**의 **저장** 단추를 선택하여 참조 문서를 저장하고 열어 둡니다. 

13. **새 프로세스**에서 **작성자** 스테이지를 선택하고 **문서 제목** 필드의 값을 **서비스**로 설정합니다. 

14. **검토로 표시** 필드의 값을 **완료됨**으로 설정합니다.

15. **다음 스테이지** 단추를 선택하여 **검토** 스테이지로 이동합니다.

16. **명령 모음**에서 **저장 후 닫기** 단추를 선택하여 변경 내용을 저장한 후 문서를 닫습니다.

 

### 작업 2: 승인 프로세스에서 문서 관리

대다수 조직에서는 문서 작성자가 레코드를 만들고 나면 문서를 실제로 활용하기 전에 승인 프로세스가 진행됩니다. 그리고 대부분의 경우에는 작성자와 다른 사람이 승인 프로세스를 진행합니다. 이 작업에서는 승인자 역할을 맡아 승인 프로세스를 진행합니다. 

1. 참조 문서에서 보기를 **제안 문서**로 전환하여 승인해야 하는 문서를 확인합니다. 

2. 방금 만든 **센서 미작동- 사용자 이니셜** 문서를 엽니다.

3. **새 프로세스**에서 **검토** 스테이지를 선택합니다. **검토** 필드의 값을 **거부됨**으로 설정합니다.

4. 참조 문서 거부 화면에서 **이 단계를 진행하여 문제를 재현할 수 없습니다.** 텍스트를 입력합니다.

5. **거부** 단추를 선택합니다.

6. **저장 후 닫기** 단추를 선택하여 문서 레코드를 닫습니다.

7. **보기 선택**에서 보기를 **내 활성 문서**로 변경합니다. 

8. **센서 미작동- 사용자 이니셜** 레코드를 엽니다.

9. 레코드가 열리면 **요약** 탭을 선택합니다. 

10. 레코드 **타임라인**에 문서가 거부되었다는 내용과 거부 이유를 나타내는 메모가 표시됩니다. 

11. **콘텐츠** 탭을 선택합니다.

12. **콘텐츠** 필드에서 5단계의 **누릅니다**라는 단어 앞에 커서를 놓습니다. 

13. **Enter** 키를 누릅니다. 

14. "확인 단추를 누릅니다."라는 텍스트를 입력합니다. 

15. **명령 모음**에서 **저장 후 닫기** 단추를 선택합니다.

16. **보기 선택**에서 보기를 **제안 문서**로 전환합니다.

17. **센서 미작동- 사용자 이니셜** 문서를 엽니다. 

18. **새 프로세스** 비즈니스 프로세스 흐름에서 **검토** 스테이지를 선택합니다.

19. 상태를 **승인됨**으로 변경합니다. 

20. 문서 승인을 확인하라는 메시지가 표시되면 **확인**을 선택합니다. 


### 작업 3: 참조 문서 승인

문서가 승인되었으므로 서비스 케이스 작업 진행 담당자가 사용할 수 있도록 문서를 게시합니다. 

1. **다음 스테이지** 단추를 선택하여 **게시** 스테이지로 이동합니다. 

2. **제품 연결 설정**을 **완료**로 표시합니다. 

3. **만료 날짜**를 **오늘부터 1년 후 자정**으로 설정합니다. 

4. **마침** 단추를 선택하여 프로세스를 완료합니다. 

5. 문서의 **명령 모음**에서 **게시** 단추를 선택합니다. 

6. 다음 옵션이 선택되어 있는지 확인합니다.

	- **게시:** 지금

	- **게시된 상태:** 게시됨

	- **만료 날짜:** 오늘부터 1년 후 자정

	- **만료 상태:** 만료됨

	- **만료 상태:** 만료됨

7. **게시** 단추를 선택하여 문서를 게시합니다.


## 실습 2: 수명 주기 전반에 걸쳐 지원 케이스 관리


### 작업 1: 서비스 케이스 만들기 및 관리

1. **Dynamics 365 Customer Service 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다. 

2. 화면 왼쪽의 탐색 영역에서 **대시보드**를 선택합니다. 그러면 **계층 1** 대시보드가 열립니다. 

3. **명령 모음**에서 **시각적 필터 표시** 단추를 선택합니다.


4. 추가 대시보드에서 현재 서비스 케이스 로드와 관련된 추가 세부 정보가 제공됩니다. 대시보드 선택 기능을 사용하면 다른 대시보드를 사용할 수 있습니다. 대시보드를 **계층 1 대시보드**에서 **계층 2 대시보드**로 변경합니다. 

 

지금까지 다양한 보기와 대시보드를 살펴보았습니다. 이제 Piper 고객의 문제 해결을 지원하기 위한 새 서비스 케이스 레코드를 만듭니다.

 

10. 화면 왼쪽의 탐색 영역에서 **서비스 케이스**를 선택합니다. 

11. **명령 모음**에서 **새로 만들기** 단추를 선택하여 새 서비스 케이스 레코드를 만듭니다.

12. 다음과 같이 새 서비스 케이스 레코드를 완성합니다.

	- **서비스 케이스 제목:** 센서 미작동 - 사용자 이니셜

	- **고객:** Piper Smith

	- **확보 경로:** 전화

	- **설명:** Piper 고객이 수령한 센서 하나가 정상 작동하지 않는다는 문제를 보고해 왔습니다. 

13. **저장** 단추를 선택하여 레코드를 저장한 후 열어 둡니다. 

14. **레코드 타임라인**에서 **더하기 기호 아이콘**을 선택하여 새 활동을 만듭니다. 

15. 표시되는 메뉴에서 **전화 통화**를 선택합니다.

16. **빨리 만들기: 전화 통화** 양식에서 다음과 같이 활동을 완성합니다.

	- **제목:** Piper 고객에게 다시 전화

	- **방향:** 발신

	- **전화 번호:**  888 555-1762

	- **기간:** 15분.

17. **저장 후 닫기** 단추를 선택합니다. 

18. **전화 - 서비스 케이스 프로세스**에서 **식별** 스테이지를 선택합니다.

19. **다음 스테이지** 단추를 선택하여 **조사** 스테이지로 이동합니다. 

20. 계속 작업할 수 있도록 **조사** 스테이지 플라이 아웃 창에서 **X**를 선택하여 창을 제거합니다. 

21. **레코드 타임라인**에서 **더하기 기호 아이콘**을 선택하여 새 활동을 만듭니다. 

22. 표시되는 메뉴에서 **작업**을 선택합니다.

23. **빨리 만들기: 전화 통화** 양식에서 다음과 같이 활동을 완성합니다.

	- **제목:** Piper 고객의 문제 조사

	- **설명:** 기술 자료를 활용하여 Piper 고객의 문제를 조사합니다. 

	- **기간:** 30분.

24. **저장 후 닫기** 단추를 선택합니다. 

25. 서비스 케이스 화면 오른쪽에서 책 모양 **지식** 아이콘을 선택합니다. (이 아이콘은 렌치 아이콘 바로 아래에 있습니다.)

26. 서비스 케이스 제목이 검색 텍스트로 자동 사용됩니다. 앞에서 만든 **센서 미작동- 사용자 이니셜** 문서를 찾아서 선택합니다. 

27. 문서의 전체 내용이 표시됩니다. 문서 아래쪽의 **좋아요** 아이콘을 선택하여 이 문서가 도움이 되었음을 표시합니다. 

28. **이 문서를 현재 레코드에 연결합니다.** 아이콘을 선택합니다. **서비스 케이스에 연결됨** 텍스트가 표시되는지 확인합니다. 

 

### 작업 2: 서비스 케이스 종료

고객 문제를 해결하는 방법을 파악했으므로 이제 서비스 케이스를 해결할 수 있습니다. 서비스 케이스를 종료하는 첫 단계에서는 해당 케이스와 연결되어 있는 시작된 활동을 모두 종료합니다. 

1. 서비스 케이스 레코드 **타임라인**에서 앞에서 만든 **Piper 고객의 문제 조사** 작업 위에 커서를 올립니다. 완료로 표시 **확인 표시 아이콘**을 선택하여 활동을 완료합니다. 

2. **작업 종료** 화면에서 상태가 완료됨인지 확인하고 **종료** 단추를 선택합니다. 작업 상태가 **종료됨**으로 표시되어야 합니다. 

3. 앞에서 만든 **Piper 고객에게 다시 전화** 전화 통화 위에 커서를 올립니다. 완료로 표시 **확인 표시 아이콘**을 선택하여 활동을 완료합니다. 

4. **전화 통화 종료** 화면에서 **상태**가 **완료됨**이며 **상태**가 **수행함**인지 확인합니다. **종료** 단추를 선택합니다. 타임라인에서 활동이 종료됨으로 표시되는지 확인합니다. 

5. **전화 - 서비스 케이스 프로세스**에서** 조사 **스테이지를 선택하고 **다음 스테이지**를 선택하여 **해결**스테이지로 이동합니다. 

6. **해결** 스테이지에서 **마침** 단추를 선택하여 프로세스 흐름을 완료합니다. 

7. 서비스 케이스 레코드의 **명령 모음**에서 **서비스 케이스 해결** 단추를 선택합니다.

8. **서비스 케이스 해결** 창에서 **해결** 필드의 값을 **참조 문서**로 설정합니다. 

9. **총 시간** 및 **청구 가능 시간** 필드의 값이 **45분**(레코드에 추가한 전화 통화 및 작업 활동에 소요된 총 시간을 나타냄)으로 설정되어 있는지 확인합니다. 

10. **해결** 단추를 선택하여 프로세스를 완료합니다. 

