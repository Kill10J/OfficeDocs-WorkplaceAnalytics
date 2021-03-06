---
# Metadata Sample
# required metadata

ROBOTS: NOINDEX,NOFOLLOW
title: Call participants metrics for Workplace Analytics Data export
description: One row for each collaboration event
author: paul9955
ms.author: v-pascha
ms.date: 06/26/2019
ms.topic: article
ms.prod: wpa
---

# CallParticipants (.csv)


This file includes one row for each participant in a call with the following metrics:

  
|Column name|Data type|Description|      
|-----------------|---------------|-----------------|      
| CallRecordId | string | Unique identifier for each call (including scheduled calls); primary key  |
| PersonHistoricalId | string | Unique value for a participant any time an HR attribute changes; foreign key matching [PersonHistorical](./PersonHistorical.md) table |
| IsOrganizer | boolean | True if this participant organized the call |
| LocalStartTime | datetime | Start time of the call in the participant's local time |
| LocalEndTime | datetime | End time of the call in the participant's local time |

## Related topics

[Data export](./data-access.md)
