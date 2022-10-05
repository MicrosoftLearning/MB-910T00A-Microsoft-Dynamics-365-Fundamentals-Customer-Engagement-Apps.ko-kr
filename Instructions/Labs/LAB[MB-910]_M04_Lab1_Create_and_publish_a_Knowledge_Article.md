---
lab:
  title: '랩 4.1: Dynamics 365 Customer Service에서 참조 문서 만들기 및 게시'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
---

<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>모듈 4: Dynamics 365 Customer Service의 기본 사항 학습
========================

## <a name="practice-lab-41---create-and-publish-a-knowledge-article-in-dynamics-365-customer-service"></a>연습 랩 4.1 - Dynamics 365 Customer Service에서 참조 문서 만들기 및 게시

## <a name="lab-setup"></a>랩 설정

  - **예상 소요 시간:** 15분

## <a name="instructions"></a>Instructions

1. **Dynamics 365 Customer Service 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다. 

2. 화면 왼쪽의 탐색 영역에서 **참조 문서**를 선택합니다. 

3. 각 스테이지의 참조 문서를 쉽게 확인하려면 **내 활성 문서** 옆의 드롭다운 화살표를 선택합니다. 

4. **초안 문서**를 선택합니다. 

5. Select <bpt id="p1">**</bpt>Approved Articles<ept id="p1">**</ept>. You should see at least one approved article.  

6. **내 활성 문서**로 다시 전환합니다.

7. **명령 모음**에서 **새로 만들기** 단추를 선택합니다. 

8. After the new record opens, select the drop-down arrow next to the <bpt id="p1">**</bpt>Status reason<ept id="p1">**</ept> field in the record header at the top. Set <bpt id="p1">**</bpt>Language<ept id="p1">**</ept> to <bpt id="p2">**</bpt>English - United States<ept id="p2">**</ept>.

9. 다음과 같이 문서를 완성합니다.

    - **제목:** 도착 시 상품 손상 - 사용자 이니셜

    - **키워드:** 항목 손상, 파손, 반품

    - **설명:** 도착한 항목이 파손된 상태일 때 문제를 해결하는 데 참조할 수 있는 정보를 제공합니다. 

10. 콘텐츠 디자이너 텍스트에 다음 텍스트를 입력합니다.   
‎  
‎   도착한 항목 파손

    도착한 항목이 파손 상태이면 다음 단계를 수행합니다.

    1. 웹 포털을 엽니다.

    2. 주문 레코드를 찾습니다.

    3. 항목 반품을 선택합니다.

    4. 이유로 파손을 선택합니다.

    5. 인쇄를 선택합니다.

    파손된 반품 항목을 수령했으므로 계좌에 구매 금액이 환불됩니다.

    **참고:** 원하는 경우 텍스트에 서식을 추가할 수 있습니다. 

11. **명령 모음**의 **저장** 단추를 선택하여 참조 문서를 저장하고 열어 둡니다. 

12. **새 프로세스**에서 **작성자** 스테이지를 선택하고 **문서 제목** 필드의 값을 **배달**(서비스 아래에 있음)로 설정합니다. 

13. **검토로 표시** 필드의 값을 **완료됨**으로 설정합니다.

14. **다음 스테이지** 단추를 선택하여 **검토** 스테이지로 이동합니다.

15. **명령 모음**에서 **저장 후 닫기** 단추를 선택하여 변경 내용을 저장한 후 문서를 닫습니다.

After the author initially creates the record, it will generally go through an approval process before it is live. Next, we will act as an approver and approve the article. 

16. 참조 문서에서 보기를 **제안 문서**로 전환하여 승인해야 하는 문서를 확인합니다. 

17. 방금 만든 **도착 시 상품 손상 - 사용자 이니셜** 문서를 엽니다.

18. On the <bpt id="p1">**</bpt>New Process<ept id="p1">**</ept>, select the <bpt id="p2">**</bpt>Review<ept id="p2">**</ept> stage. Set the <bpt id="p1">**</bpt>Review<ept id="p1">**</ept> field to <bpt id="p2">**</bpt>Approved<ept id="p2">**</ept>.

19. 문서 승인을 확인하라는 메시지가 표시되면 **확인**을 선택합니다. 

20. **다음 스테이지** 단추를 선택하여 **게시** 스테이지로 이동합니다. 

21. On the <bpt id="p1">**</bpt>Command Bar<ept id="p1">**</ept> at the top of the article, select the <bpt id="p2">**</bpt>vertical ellipsis<ept id="p2">**</ept> at the left of the command bar. From the menu that appears, select <bpt id="p1">**</bpt>Relate Product<ept id="p1">**</ept>. 

22. **제품 연결** 창에서 **기업용 Office 365(샘플)** 를 선택합니다.

23. **연결** 단추를 선택합니다. 

24. **새 프로세스**에서 **게시** 스테이지를 선택합니다. 

25. **제품 연결 설정**을 **완료**로 표시합니다. 

26. **만료 날짜**를 **오늘부터 1년 후 자정**으로 설정합니다. 

27. **마침** 단추를 선택하여 프로세스를 완료합니다. 

28. 문서의 **명령 모음**에서 **게시** 단추를 선택합니다. 

29. 다음 옵션이 선택되어 있는지 확인합니다.

    - **게시:** 지금

    - **게시된 상태:** 게시됨

    - **만료 날짜:** 오늘부터 1년 후 자정

    - **만료 상태:** 만료됨

    - **만료 상태:** 만료됨

    - **승인된 번역 게시:** 아니요
    
30. **게시** 단추를 클릭하여 문서를 게시합니다.


