# Welcome to the AIRM User Manual

Welcome to the AIRM User Manual.

`TODO`

## What do you want to do?

```mermaid
---
  config:
    class:
      hideEmptyMembersBox: true
---
classDiagram
   class AIRM
   class AIRM_Knowledge["AIRM Knowledge"]
   class AIRM_Rulebook["AIRM Rulebook"]
   class AIRM_API["AIRM API"]
   class AIRM_Search["AIRM Search"]
   %% class AIRM_Contextual_Model["AIRM Contextual Model"]
   %% class AIRM_Conceptual_Model["AIRM Conceptual Model"]
   %% class AIRM_Logical_Model["AIRM Logical Model"]

   %% class AIRM_User_Manual["AIRM User Manual"]

   AIRM_Rulebook --> AIRM : provides rules for developing
   AIRM_Knowledge --> AIRM : exposes ontologies from
   AIRM <-- AIRM_Search : provides online access to
   AIRM <-- AIRM_API: enables to connect software to 

  click AIRM_Rulebook href "https://airm-ccb.github.io/airm-user-manual-1.3.0-testing/#/guidance/airm_rulebook" "Browse the AIRM Rulebook"
  click AIRM_Knowledge href "https://airm-ccb.github.io/airm-user-manual-1.3.0-testing/#/knowledge/aircraft)" "Discover the AIRM ontologies"
  click AIRM_Search href "https://airm.aero/dictionary/1.2.0/search" "Search for ATM terms, abbreviations and concepts"
  click AIRM_API href "https://airm.aero/developers/api" "Connect your software"
```

```mermaid
timeline
    title History of AIRM
    section  R&D
      2009-2019 : NEXTGEN NAS-EA-OV7
                : SESAR AIRM
    section  ICAO deployment
      2019-2022 : AIRM 1.0.0, AIRM 1.1.0
      2024      : AIRM 1.2.0, CURRENT VERSION ENDORSED BY ICAO
      Coming soon (Q1 2025) : AIRM 1.3.0
```_
