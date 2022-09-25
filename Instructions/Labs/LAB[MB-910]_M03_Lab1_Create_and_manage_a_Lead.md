---
lab:
  title: '랩 3.1: Dynamics 365 Sales에서 잠재 고객 만들기 및 관리'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Sales'
---

<a name="module-3-learn-the-fundamentals-of-dynamics-365-sales"></a>모듈 3: Dynamics 365 Sales의 기본 사항 학습
========================

## <a name="practice-lab-31---create-and-manage-a-lead-in-dynamics-365-sales"></a>연습 랩 3.1 - Dynamics 365 Sales에서 잠재 고객 만들기 및 관리

## <a name="objectives"></a>목표

During this exercise, you will be capturing a sales lead for Suzanne Burke. She recently reached out to you and is interested in some of your organization’s products and services. Not only will you be capturing the lead in the system, but you will be using the tools available in Dynamics 365 Sales to work the lead through the qualification process.


## <a name="lab-setup"></a>랩 설정

  - **예상 소요 시간:** 15분

## <a name="instructions"></a>Instructions

1. **Dynamics 365 영업 허브** 애플리케이션이 아직 열려 있지 않으면 엽니다. 

2. 화면 왼쪽의 탐색 영역에서 **잠재 고객**을 선택합니다. 

3. **내 시작된 잠재 고객** 보기에서 명령 모음의 **새로 만들기** 단추를 선택합니다.

4. 다음과 같이 새 잠재 고객 레코드를 완성합니다.

    - **토픽:** 새 장비 구매 예정 - 사용자 이니셜

    - **이름:** Suzanne

    - **성:** Burke

    - **직함:** CFO

    - **근무지 전화:** 888 555-8715

    - **메일:** Suzanne@contososample.com

    - **회사:** Contoso - Washington

    - **나머지 주소 1:** 1989 Smith Ave

    - **구/군/시:** 시애틀

    - **시/도:** WA

    - **우편 번호:** 98001 

5. 명령 모음의 **저장** 단추를 선택하여 새 잠재 고객을 저장한 후 열어 둡니다.

6. Notice the <bpt id="p1">**</bpt>Lead to Opportunity<ept id="p1">**</ept> Business Process Flow at the top of the record. Click the <bpt id="p1">**</bpt>Qualify Stage<ept id="p1">**</ept> to select it. Complete the stage as follows:

    - **구매 시간 프레임:** 현재 분기

    - **예상 예산:** 25000 

    - **구매 프로세스:** 개인

    - **의사 결정자 식별:** 완료됨

7. 화면 가운데의 **레코드 타임라인**으로 이동한 다음 **더하기 기호** 아이콘을 클릭하여 새 활동을 추가합니다. 

8. 표시되는 메뉴에서 **전화 통화**를 선택합니다.

9. **전화 통화 빨리 만들기** 화면에서 **제목** 필드의 값을 **최초 전화 통화**로 설정하고 나머지 정보는 그대로 둡니다. 

10. **저장 후 닫기** 단추를 클릭합니다.

11. Notice the <bpt id="p1">**</bpt>Initial Phone Call<ept id="p1">**</ept> activity is now displayed on the <bpt id="p2">**</bpt>Record Timeline<ept id="p2">**</ept>. Hover over the activity and select the close activity <bpt id="p1">**</bpt>Check Mark Icon<ept id="p1">**</ept> to mark the phone call as completed. 

12. **전화 통화 종료** 창에서 **종료** 단추를 선택합니다. 

13. Next you will qualify the lead record.  This will create a related Opportunity record and move to the next stage of the Lead to Opportunity sales process.  On the Command Bar, select the Qualify button.  

14. After the system qualifies the lead, a new <bpt id="p1">**</bpt>Opportunity<ept id="p1">**</ept> record will be created, and the business process will advance to the <bpt id="p2">**</bpt>Develop<ept id="p2">**</ept> stage.  Select the <bpt id="p1">**</bpt>Qualify<ept id="p1">**</ept> stage to view the original lead record. 

15. **개발** 스테이지를 선택하여 영업 기회로 돌아갑니다.

