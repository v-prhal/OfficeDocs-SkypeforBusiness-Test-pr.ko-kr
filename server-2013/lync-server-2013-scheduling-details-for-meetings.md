﻿---
title: 일정 정보
TOCTitle: 일정 정보
ms:assetid: 39ca6fff-2c15-4347-9f1f-6c8687a39a49
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ204823(v=OCS.15)
ms:contentKeyID: 49303347
ms.date: 08/10/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# 일정 정보

 

_**마지막으로 수정된 항목:** 2012-10-04_

요청을 처리하는 대규모 모임 지원 담당자는 요청된 시간에 다른 모임이 예약되어 있지 않은지 확인한 후에 대규모 모임 풀에서 모임을 예약합니다. Lync Server 2013 클라이언트와 함께 설치되는 Lync용 온라인 모임 추가 기능을 사용하여 이 작업을 수행하며, 이때 전용 대규모 모임 풀에서 Lync Server를 사용하도록 설정된 사용자의 자격 증명을 사용합니다.

최적의 사용자 환경을 보장하려면 모임 이끌이의 요구에 적합한 적절한 모임 설정 및 액세스 수준을 사용하여 대규모 모임을 예약해야 합니다. Lync 모임 옵션에 구성된 다음 예약 설정을 사용하는 것이 좋습니다.

  - 전용 모임 공간을 다시 사용하는 대신 각각의 대규모 모임용으로 새 모임 공간을 만듭니다.

  - 모임 액세스 수준을 다음과 같이 지정합니다.
    
      - 초대 대상자 중 한 명 이상이 조직 외부에 있으면 모임 액세스 유형을 **모두(제한 없음)**로 설정합니다. 그러면 모임이 진행 중일 때 대규모 대기실을 관리할 필요가 없습니다.
    
      - 내부 전용 모임의 경우에는 모임 액세스 유형을 **조직 구성원 모두**로 설정합니다.
        

        > [!NOTE]
        > 모임 액세스 유형으로 <STRONG>내 회사에서 초대한 사용자</STRONG> 설정을 사용하는 경우 이끌이가 모든 사용자 전자 메일 주소를 초대 대상자 목록에 추가해야 하며 메일 그룹은 초대할 수 없으므로, 모임 액세스 유형을 이렇게 설정하지 마십시오.<BR>모임 액세스 유형으로 <STRONG>나만, 모임 이끌이</STRONG> 설정을 사용하는 경우 발표자를 비롯한 모든 모임 참가자가 모임 실행 시 대기실에서 기다려야 하므로 모임 액세스 유형을 이렇게 설정하지 마십시오. 이 설정을 사용하는 경우에는 대규모 모임을 진행하는 사람이 대기실 명단을 지속적으로 모니터링하여 대기실에 있는 새 사용자를 허용해야 합니다.



  - **발신자 바로 입장** 설정을 선택하여 전화를 통해 전화 접속하는 사용자가 모임에 자동으로 입장하도록 허용합니다.

  - 다음 사용자를 명시적으로 초대합니다.
    
      - 모임 이끌이 및 대리인(요청자)
    
      - 모임 요청자가 제공하는 발표자 목록
    

    > [!NOTE]
    > 모임 액세스 유형을 <STRONG>내가 선택한 사용자</STRONG>로 설정하는 경우에는 대규모 모임의 각 참가자를 명시적으로 모임 초대 대상자로 추가해야 합니다.



  - 발표자 옵션을 자동 승격 값 중 하나로 설정하는 대신 발표자를 명시적으로 관리합니다. 다음과 같은 사용자를 발표자로 추가해야 합니다.
    
      - 모임 이끌이 및 대리인(요청자)
    
      - 대규모 모임 요청자가 제공하는 발표자 목록
    

    > [!NOTE]
    > 발표자를 명시적으로 관리하면 발표자 수를 제어할 수 있으므로 대규모 모임을 효율적으로 유지하는 데 충분하도록 발표자 수를 적게 제한할 수 있습니다. 대부분의 모임 참가자에게 참석자 역할이 지정되면 실수로 사용자들에게 프레젠테이션 제어권을 부여하거나, PowerPoint 프레젠테이션을 삭제하거나, 발표자를 음소거/음소거 해제하고 기타 이유로 모임을 중단할 가능성이 낮아집니다.



  - **모든 참석자 음소거** 설정을 선택하여 발표자만 모임에 오디오를 브로드캐스트할 수 있도록 합니다.

  - **참석자의 비디오 차단**을 선택하여 발표자만 모임에 비디오를 브로드캐스트할 수 있도록 합니다.

다음 그림에서는 Lync용 온라인 모임 추가 기능에 대한 권장 설정을 보여 줍니다.

![모임 회의 옵션](images/JJ204823.54e4e70d-06b0-45cd-8d94-bab649cd5dc0(OCS.15).jpg "모임 회의 옵션")

