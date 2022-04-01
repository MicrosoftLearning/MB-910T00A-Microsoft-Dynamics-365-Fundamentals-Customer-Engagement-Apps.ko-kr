---
lab:
  title: '랩 1.1: 랩 환경 유효성 검사'
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: 6b800444cadb1a2de0750594fea3e19e4f9a5bde
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909045"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>모듈 1: Dynamics 365 마케팅의 기본 사항 알아보기
========================

## <a name="practice-lab-11---validate-lab-environment"></a>연습 랩 1.1 - 랩 환경 유효성 검사 

이 랩에서는 강의용 테넌트가 정상적으로 작동하는지 유효성을 검사합니다. 개인 자격 증명에 액세스하고 "별칭"을 기록하며 과정 전반에 걸쳐 사용할 Dynamics 365 모델 기반 애플리케이션을 엽니다. 

**중요 정보:** 이 랩에서는 이 과정에서 사용할 Power Platform 애플리케이션에 대한 실제 Dynamics 365 테넌트 및 라이선스를 제공합니다. Power Platform이 항상 진화하고 있다는 점에 유의해 주세요. 문서의 지침은 실제 테넌트에서 경험할 내용과 다를 수 있습니다. 가상 머신이 네트워크 연결을 통해 랩을 시작하기까지 몇 분 정도 지연이 발생할 수도 있습니다.

<a name="exercise-1---access-the-dynamics-365-application"></a>연습 1 - Dynamics 365 애플리케이션에 액세스
---------------------------------------------------

### <a name="task-1--log-into-the-power-platform-admin-center"></a>작업 1 – Power Platform 관리 센터에 로그인

1.  사용자 자격 증명을 사용하여 <https://admin.Powerplatform.microsoft.com>에 액세스하고 로그인합니다.

2. 사용자 자격 증명에서 **@** 기호까지 종이나 메모장에 기록합니다. 이것은 공유 Dynamics 365 조직 내에서 사용자가 만든 데이터를 구분하는 데 사용할 랩 별칭입니다. 

**중요:** 이 테넌트 및 Dynamics 365 조직은 교실의 다른 학생들과 공유됩니다. 이는 직원들이 조직 소유의 Dynamics 365 인스턴스를 사용할 때 테넌트를 공유하는 것과 같습니다. 레코드를 만들 때 PII(개인 식별이 가능한 정보)를 사용하지 마세요. 또한 만든 모든 레코드, 데이터, 앱, 흐름 등의 앞에 사용자 이름을 접두사(예: **mollyc**)로 붙이는 것도 좋습니다.

3. Power Platform 관리 센터를 마음껏 탐색하되 **아무것도 변경해서는 안 됩니다**.

### <a name="task-2--access-the-dynamics-365-application"></a>작업 2 – Dynamics 365 애플리케이션에 액세스

1.  화면 왼쪽 상단에서 **Power Platform 관리 센터 바로 왼쪽에 있는 앱 론처 도미노 단추를 펼칩니다. Dynamics 365 **Marketing** 앱을 선택하여 시작합니다.

2.  왼쪽에 있는 탐색 창을 살펴봅니다. 창 하단에 있는 단추를 통해 영역을 변경할 수 있습니다. 현재 **마케팅** 영역을 보고 있습니다. 

3.  탐색 창 하단에서 **마케팅** 을 선택하고 **이벤트** 영역을 선택합니다. 탐색 창의 **이벤트** 영역을 살펴봅니다.  

4. 몇 분 동안 애플리케이션을 살펴본 후에 **마케팅** 영역으로 돌아갑니다.
