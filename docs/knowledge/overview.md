# AIRM Ontologies

```mermaid
---
title: Strategic Concepts
---
flowchart LR    
  subgraph Traffic
    FLIGHT@{ shape: doc, label: "Flight"}
  end
  subgraph Operations
    ATO@{ shape: doc, label: "Air Traffic Operations"}
  end
  subgraph Stakeholders
    STK@{ shape: doc, label: "Stakeholders"}
  end
  subgraph Infrastructure
    INFRA@{ shape: docs, label: "Aircraft<br>Base infrastructure<br>Airspace infrastructure"}
  end

Traffic -- is enabled by --> Operations
Traffic -- uses --> Infrastructure
Traffic -- is performed by --> Stakeholders
Stakeholders -- own --> Infrastructure
Operations -- are performed by --> Stakeholders
Operations -- are constrained by --> Infrastructure
```

## Traffic

| AIRM Subject | Ontology | Description |
| :- | :- | :-------------------------- |
| `Flight` | Flight | Information about a specific flight. |
| `Flight` | Flight Event | Information about actions, tasks or facts relevant to a specific flight which occur at an instant.|
| `Flight` | Flight Identifier | Information about identifiers of a flight. |
| `Flight` | Flight Phase | Information about period-in-time occurrences during a Flight. |
| `Flight` | Movement | Information about movement of an aircraft both in the air and on the ground including position, time, and at least via calculation, speed and acceleration. |

## Operations

| AIRM Subject | Ontology | Description |
| :- | :- | :-------------------------- |
| `Air Traffic Operations` | Aerodrome Operations | Information about planning, execution and analysis of airport airside activities, including, but not limited to, how the aerodrome operators provide the needed ground infrastructure and precise surface guidance to improve safety and maximize aerodrome capacity in all weather conditions. |
| `Air Traffic Operations` | Airspace Organization and Management | Information about how airspace organizations establish airspace structures in order to accommodate the different types of air activity, volume of traffic and differing levels of service, and about the process by which airspace options are selected and applied to meet the needs of the ATM community. |
| `Air Traffic Operations` | Airspace User Operations | Information about the ATM-related aspect of flight operations. |
| `Air Traffic Operations` | ATM Phases | Information about groupings of related collaborative ATM activities relative to a flight or a group of flights. |
| `Air Traffic Operations` | ATM Service Delivery Management | Information about the balance and consolidation of the decisions of the various other processes/services, as well as the time horizon at which, and the conditions under which, these decisions are made. |
| `Air Traffic Operations` | Cargo Operations | Information on all activities required to enable the safe transport of cargo by air. |
| `Air Traffic Operations` | Conflict Management | Information about a) the strategic conflict management through airspace organization and management, the demand and capacity balancing, and traffic synchronization; b) separation provision; c) and collision avoidance. |
| `Air Traffic Operations` | Demand and Capacity Balancing | Information about the strategic evaluation of the system-wide traffic flows and aerodrome capacities to allow airspace users to determine when, where and how they operate, while mitigating conflicting needs for airspace and aerodrome capacity. |
| `Air Traffic Operations` | Emergency Operations | Information about the activities carried out in case of an emergency. |
| `Air Traffic Operations` | Information Services Products | Information about the products exchanged by information services. |
| `Air Traffic Operations` | Aeronautical Information Product |  |
| `Air Traffic Operations` | Flight Information Product |  |
| `Air Traffic Operations` | Meteorological Information Product |  |
| `Air Traffic Operations` | Coordination |  |

## Stakeholders

| AIRM Subject | Ontology | Description |
| :- | :- | :-------------------------- |
| `Stakeholders` | Organisation, Role and Service | Generic framework for modeling organizations, roles and services. This is to be used for typing. Based on the W3C Organization proposal. |
| `Stakeholders` | Agent | Specific common instances of "Agent" and their specialization relations. |
| `Stakeholders` | Business Services | Specific common instances of "Service" and their specialization relations. |
| `Stakeholders` | Document and Agreement | Description of cross-organizational agreements and documents. |
| `Stakeholders` | Organisation | Specific common instances of "Organisation" and their specialization relations. |
| `Stakeholders` | Role | Specific common instances of "Role" and their specialization relations |

## Infrastructure

| AIRM Subject | Ontology | Description |
| :- | :- | :-------------------------- |
| `Aircraft` | Aircraft | Information about the aircraft. |
| `Airspace Infrastructure` | Airspace | Information about the defined three-dimensional portions of the atmosphere relevant to ATS. |
| `Airspace Infrastructure` | Infrastructure Point | Information about points in an airspace.  |
| `Airspace Infrastructure` | Route and Procedure | Information about the routes and procedures designed for channelling the flow of traffic en-route and while departing and landing. |
| `Base Infrastructure` | Aerodrome Infrastructure | Informaion about the  aerodrome including any installations and equipment. |
| `Base Infrastructure` | Communication Infrastructure | Information about the communication infrastructure. |
| `Base Infrastructure` | Navigation Infrastructure | Information about the navigation infrastructure.  |
| `Base Infrastructure` | Surveillance Infrastructure | Information about the surveillance infrastructure. |
| `Base Infrastructure` | Obstacle | Information about ground based objects that are detrimental to the safe execution of flights. |
| `Base Infrastructure` | Satellite System | Information about satellite systems. |

## Other

| AIRM Subject | Ontology | Description |
| :- | :- | :-------------------------- |
| `Common` | Geometry | Information about ATM-related geometry concepts. |
| `Common` | Geospatial | Information related to land, ice and ocean surfaces and any object with vertical extent above and/or under ground. |
| `Common` | Temporal | Information about ATM-related temporal concepts. |
| `Meteorology` | Meteorology | Information about meteorological observation, forecast, phenomena and any other statement relating to existing or expected meteorological conditions. |



