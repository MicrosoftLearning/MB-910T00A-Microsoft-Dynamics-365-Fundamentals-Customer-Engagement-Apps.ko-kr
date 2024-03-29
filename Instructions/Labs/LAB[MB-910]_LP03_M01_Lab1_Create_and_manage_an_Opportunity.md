---
lab:
  title: '학습 경로 3 - 랩 3.1: Dynamics 365 Sales에서 영업 기회 생성 및 관리'
  learning path: Explore the fundamentals of Microsoft Dynamics 365 Sales
  module: Explore Dynamics 365 Sales
---


학습 경로 3 - 모듈 1: Dynamics 365 Sales 살펴보기
========================

## 연습 랩 3.1 - Dynamics 365 Sales에서 영업 기회 생성 및 관리 

## 목표

이 연습에서는 곽지현 잠재 고객을 수동으로 만들어 봅니다. 곽지현은 **ABC Consulting**이라는 회사에서 일합니다. 여러분은 시스템에서 잠재 고객 정보를 캡처한 다음 Dynamics 365 Sales의 도구를 사용하여 잠재 고객을 영업 기회로 전환하고 영업 기회가 종료될 때까지 관리합니다.

## 랩 설정

  - **예상 소요 시간:** 20분

## Instructions

1. **Dynamics 365 영업 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다.

2. 화면 왼쪽의 탐색 영역에서 **잠재 고객**을 선택합니다.

3. **내 시작된 잠재 고객** 보기에서 **새로 만들기** 단추를 선택하여 새 잠재 고객을 만듭니다.

4. 다음과 같이 **잠재 고객** 정보를 작성합니다.

    - **토픽:** 기존 장비를 업그레이드하려고 함(이니셜)

    - **이름:** 지현

    - **성:** 곽(사용자 이니셜)

    - **직함:** CEO

    - **직장 전화:** 888-555-6767

    - **이메일:** JaneA(이니셜)@sample.com

    - **회사:** ABC 컨설팅(이니셜)

    - **주소 1**: 테헤란로 131

    - **구/군/시:** 강남구

    - **주/도:** 서울

    - **우편 번호:** 06133

5. **저장** 단추를 선택하여 잠재 고객을 저장하고 열어 둡니다.

6. **잠재 고객에서 영업 기회로** 영업 프로세스에서 **우량으로 선별** 스테이지를 선택합니다.

7. 다음과 같이 완료합니다.

    - **구매 기간:** 즉시

    - **예상 예산:** $50,000

    - **구매 프로세스:** 위원회

8. **예선** 스테이지 플라이아웃을 닫습니다.

9. **명령 모음**에서 **우량으로 선별** 단추를 선택합니다.

    > **참고:** 예선 단추가 표시되지 않으면 **기타 명령** 단추를 선택합니다(세로 점 3개 모양).

    **잠재 고객** 레코드가 닫히고 새 **영업 기회** 레코드가 생성됩니다. **잠재 고객에서 영업 기회로** 비즈니스 프로세스 흐름이 자동으로 **개발** 스테이지로 넘어간 것을 볼 수 있습니다.

10. 레코드 맨 위쪽 **영업 기회 머리글**에서 **소유자** 필드 옆의 아래쪽 화살표를 선택합니다.

11. 다음과 같이 완료합니다.

    - **예상 예상 종료 날짜:** 오늘부터 2일 후

    - **예상 매출:** $50,000

12. **이해 관계자** 하위 그리드에서 **곽지현**(사용자 이니셜)이 이미 이해 관계자로 정의되어 있는 것을 볼 수 있습니다.

13. **영업 팀** 하위 그리드에서 **세로 방향 줄임표**를 선택합니다. 표시되는 메뉴에서 **새 연결**을 선택합니다.

14. 사용자 레코드를 검색하여 선택합니다. 완료되면 **추가** 단추를 선택합니다.

15. **경쟁 업체** 하위 그리드에서 **세로 방향 줄임표**(세로 점 3개 모양)를 선택합니다. 표시되는 메뉴에서 **기존 경쟁 업체 추가**를 선택합니다.

16. **레코드 조회** 화면에서 **새 레코드**를 선택한 다음 **경쟁 업체**를 선택합니다.

17. **경쟁 업체 빨리 만들기** 양식에서 **이름** 필드의 값을 **Coho Technologies(사용자 이니셜)** 로 설정합니다.

18. **저장 후 닫기** 단추를 선택합니다.

19. 조회 레코드 창에 **Coho Technologies**가 선택되어 있어야 합니다. **추가** 단추를 클릭하여 경쟁 업체 추가를 완료합니다.

20. **잠재 고객에서 영업 기회로** 비즈니스 프로세스 흐름에서 **개발** 스테이지를 선택합니다.

21. 다음과 같이 완료합니다.

    - **이해 관계자 식별**: 완료

    - **경쟁 업체 식별:** 완료

22. **다음 스테이지** 단추를 선택하여 **제안** 스테이지로 이동합니다.

23. **제안** 스테이지에서 4개 작업을 모두 **완료**로 표시합니다. **다음 스테이지**를 선택합니다.

24. **종료** 스테이지에서 모든 작업을 **완료**로 표시합니다.

25. 비즈니스 프로세스 흐름의 **완료** 단추를 선택합니다.

이제 비즈니스 프로세스를 완료했으므로 영업 기회를 종료해야 합니다.

26. 영업 기회의 **명령 모음**에서 **성공으로 종료** 단추를 선택합니다.

27. **영업 기회 종료** 대화에서 **확인** 단추를 선택하여 영업 기회 레코드 종료하기를 마칩니다.
