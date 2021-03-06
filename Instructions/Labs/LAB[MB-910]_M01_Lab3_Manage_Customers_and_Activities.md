---
lab:
    title: '랩 1.3: 고객 및 활동 관리'
    module: '모듈 1: Dynamics 365 Marketing의 기본 사항 파악'
---

모듈 1: Dynamics 365 Marketing의 기본 사항 파악
========================

## 연습 랩 1.3 - 고객 및 활동 관리

## 목표

Dynamics 365 애플리케이션에서는 계정 및 연락처 레코드를 정의하고 작업하는 것이 가장 일반적인 활동 중 하나입니다. 계정 및 연락처가 생성된 후에는 전화, 작업, 약속 등의 활동이 고객과의 상호 작용을 나타냅니다.

## 랩 설정

  - **소요 시간**: 15분

## 지침

이 연습에서는 모든 Dynamics 365 Customer Engagement 앱에서 사용되는 공통 레코드를 작업하게 됩니다. 

1. **Dynamics 365 영업 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다. 

2. 화면 왼쪽의 탐색 영역에서 **거래처**를 선택합니다. 

3. 화면 상단의 명령 모음에서 **새로 만들기** 단추를 선택합니다.

4. 다음과 같이 거래처 레코드를 완성합니다.

	- **거래처 이름:** Contoso Corporate – 사용자 이니셜

	- **전화:** 888-555-1234

	- **주소 1 나머지 주소 1:** 191 181st Ave N

	- **주소 1 구/군/시:** 시애틀

	- **주소 1 시/도:** WA

	- **주소 1 우편 번호:** 98101

5. 명령 모음에서 **저장 후 닫기** 단추를 선택하여 거래처 레코드를 저장한 후 레코드 작성을 끝냅니다.

6. 명령 모음의 거래처 목록에서 **새로 만들기** 단추를 다시 선택합니다.

7. 다음과 같이 거래처 레코드를 완성합니다.

	- **거래처 이름:** Contoso North America – 사용자 이니셜

	- **전화:** 888-555-4321

	- **주소 1 나머지 주소 1**: 187 11th ST N

	- **주소 1 구/군/시:** 시카고

	- **주소 1 시/도:** IL

	- **주소 1 우편 번호:** 60176

8. **상위 거래처** 필드의 값을 앞에서 만든 거래처인 **Contoso Corporate**로 설정합니다. 

9. **저장** 단추를 선택하여 계정을 저장한 후 열어 둡니다. 

10. 화면 오른쪽에서 **연락처 하위 표**를 찾니다. 

11. **세로 줄임표**를 선택한 후 표시되는 메뉴에서 **새 연락처**를 선택합니다. 

12. **연락처 빨리 만들기** 양식을 사용하여 다음과 같이 연락처를 완성합니다.

	- **이름:** Jackson

	- **성:** Anderson - 사용자 이니셜

	- **직함:** CEO

	- **전자 메일:** Jackson@contososample.com

13. **저장 후 닫기** 단추를 선택합니다.

14. 연락처 하위 표 바로 위의 **주 연락처** 필드를 선택하여 필드 값을 방금 만든 연락처인 **Jackson Anderson**으로 설정합니다. 

15. 화면 가운데 있는 **레코드 타임라인**에서 **+** 아이콘을 선택하여 새 활동 항목을 추가합니다. 

16. 표시되는 메뉴에서 **약속**을 선택합니다.

17. 다음과 같이 약속을 완성합니다.

	- **제목:** Jackson과의 모임

	- **시작 시간:** 오늘 오후 3시

	- **종료 시간:** 오늘 오후 4시

18. **저장 후 닫기** 단추를 선택합니다. 

19. 타임라인이 자동으로 새로 고침될 때까지 기다립니다. 

20. 이제 **타임라인**에 약속에 관한 정보가 표시됩니다. 

21. 거래처를 **저장하고 닫습니다**. 

22. 탐색 창의 **내 작업** 섹션에서 **활동**을 선택합니다.

23. **Jaskson과의 모임** 링크를 선택하여 약속 행을 열고 양식을 표시합니다. 

24. 약속 레코드가 열려 있을 때 **명령 모음**에서 **완료로 표시** 단추를 선택하여 약속을 완료합니다. 

25. 약속이 **내 활동** 보기에 더 이상 나열되지 않습니다. 

26. **내 활동** 보기를 선택하여 **종료된 활동** 보기로 변경합니다. 완료된 **Jason과의 모임** 약속이 표시됩니다.
