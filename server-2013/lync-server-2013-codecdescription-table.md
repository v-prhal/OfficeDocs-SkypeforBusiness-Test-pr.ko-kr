﻿---
title: Lync Server 2013의 CodecDescription 테이블
TOCTitle: Lync Server 2013의 CodecDescription 테이블
ms:assetid: 3598acb8-7ea6-4748-8417-149c971c32a2
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ204797(v=OCS.15)
ms:contentKeyID: 49303273
ms.date: 08/10/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Lync Server 2013의 CodecDescription 테이블

 

_**마지막으로 수정된 항목:** 2015-03-09_

CodecDescription 테이블은 고유 코덱 식별자를 해당 코덱에 매핑합니다. 코덱은 전송 및 브로드캐스트용으로 디지털 신호를 인코딩한 다음 재생용으로 신호를 디코딩하는 데 사용됩니다. 이 테이블은 Microsoft Lync Server 2013에서 도입되었습니다.


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>열</strong></th>
<th><strong>데이터 형식</strong></th>
<th><strong>키/인덱스</strong></th>
<th><strong>세부 정보</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>CodecDescriptionKey</strong></p></td>
<td><p>smallint</p></td>
<td><p>Primary</p></td>
<td><p>코덱에 할당된 고유 식별자입니다.</p></td>
</tr>
<tr class="even">
<td><p><strong>CodecDescription</strong></p></td>
<td><p>varchar(256)</p></td>
<td><p>Unique</p></td>
<td><p>CodecDescriptionKey에 해당하는 코덱의 고유한 설명입니다.</p></td>
</tr>
</tbody>
</table>

