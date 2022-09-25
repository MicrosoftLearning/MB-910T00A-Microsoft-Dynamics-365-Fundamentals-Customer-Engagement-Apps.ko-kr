---
lab:
  title: '랩 4.2: Dynamics 365 Field Service에서 항목 예약'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
---

<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>모듈 4: Dynamics 365 Field Service의 기본 사항 알아보기
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>연습 랩 4.2 - Dynamics 365 Field Service에서 항목 예약

## <a name="lab-setup"></a>랩 설정

  - **예상 소요 시간:** 20분

  <bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> The Booking Requirements pane cannot be opened in Internet Explorer. Please use Microsoft Edge or Google Chrome to complete this exercise.
  
## <a name="instructions"></a>Instructions

1.  **Dynamics 365 Field Service** 애플리케이션이 아직 열려 있지 않으면 엽니다.  

2.  왼쪽의 탐색 영역에서 **작업 주문**을 선택합니다.

3.  **명령 모음**에서 **새로 만들기** 단추를 선택하여 새 작업 주문을 만듭니다.

4.  다음과 같이 작업 주문 세부 정보를 작성합니다.
    - 서비스 계정: ADatum Corporation
    - 기본 문제 유형: MRI 스캐너 다운
    - 과세 대상: 아니요
    
5.  **저장 후 닫기**를 선택하여 변경 내용을 저장하고 새 작업 주문 작성을 끝냅니다.

6.  On the <bpt id="p1">**</bpt>Command Bar<ept id="p1">**</ept> of the <bpt id="p2">**</bpt>Work Order<ept id="p2">**</ept>, select the <bpt id="p3">**</bpt>Book<ept id="p3">**</ept> button.  This will open the <bpt id="p1">**</bpt>Schedule Assistant<ept id="p1">**</ept>.  

7.  You should be presented with options for scheduling the item.  Select the <bpt id="p1">**</bpt>Ryan Brim<ept id="p1">**</ept> record.

8.  **리소스 예약 만들기** 창에서 **시작 시간**을 **다음 정각 시간**으로 설정합니다.

9.  **종료 시간**은 시작 시간부터 2.5시간 후로 설정합니다.  

10. **예약 및 끝내기** 단추를 선택하여 항목을 예약하고 예약 창을 종료합니다.  

11. 작업 주문으로 돌아와 **명령 모음**에서 **저장 후 닫기** 단추를 클릭합니다.  

12. 왼쪽 탐색 영역에서 **일정 게시판**을 선택합니다.

13. 화면 아래쪽의 요구 사항 패널에서 **예약 취소된 작업 주문**을 선택합니다.

14. Select the <bpt id="p1">**</bpt>Adventure Works<ept id="p1">**</ept> Work Order you created earlier use the work order number you wrote down. From the options that appear select <bpt id="p1">**</bpt>Find Availability<ept id="p1">**</ept>.  

15. 그러면 **일정 도우미**가 열립니다.  

16. You should be presented with options for scheduling the item.  Select the Bob Kozak record.

17. **리소스 예약 만들기** 창에서 **시작 시간**을 **다음 정각 시간**으로 설정합니다.

18. **종료 시간**은 시작 시간부터 2.5시간 후로 설정합니다.
  
19. **예약 및 끝내기** 단추를 선택하여 항목을 예약하고 예약 창을 종료합니다. 

20. At times, you may need to reschedule a work order based on technician conflicts or other items.  This can be easily done by dispatchers leveraging the schedule board.  

21. 일정 게시판(리소스 이름 열 바로 위에 있음)의 리소스 검색 상자를 클릭하고 Ryan을 입력한 다음 오늘 오후로 예약된 Ryan의 작업 주문을 찾습니다.  

22. 작업 주문을 마우스 오른쪽 단추로 클릭하고 표시되는 메뉴에서 **대체 리소스**를 선택한 다음, **대리인 찾기** 단추를 선택합니다.


