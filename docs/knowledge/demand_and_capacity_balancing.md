# DemandAndCapacityBalancing

## Overview

An overview of the main concepts related to Demand Capacity Balancing.

Key concepts: [`Capacity`](https://airm.aero/developers/advanced-search/1.2.0/Capacity?model=ConceptualModel)  [`Demand`](https://airm.aero/developers/advanced-search/1.2.0/Demand?model=ConceptualModel)  [`Imbalance`](https://airm.aero/developers/advanced-search/1.2.0/Imbalance?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`RunwayCapacity`](https://airm.aero/developers/advanced-search/1.2.0/RunwayCapacity?model=ConceptualModel)  [`Runway`](https://airm.aero/developers/advanced-search/1.2.0/Runway?model=ConceptualModel)  [`RunwayDirection`](https://airm.aero/developers/advanced-search/1.2.0/RunwayDirection?model=ConceptualModel)  [`DeclaredCapacity`](https://airm.aero/developers/advanced-search/1.2.0/DeclaredCapacity?model=ConceptualModel)  [`TerminalCapacity`](https://airm.aero/developers/advanced-search/1.2.0/TerminalCapacity?model=ConceptualModel)  [`ATFMMeasure`](https://airm.aero/developers/advanced-search/1.2.0/ATFMMeasure?model=ConceptualModel)  [`GroundDelayProgramme`](https://airm.aero/developers/advanced-search/1.2.0/GroundDelayProgramme?model=ConceptualModel)  [`SlotSwapping`](https://airm.aero/developers/advanced-search/1.2.0/SlotSwapping?model=ConceptualModel)  [`MinutesInTrail`](https://airm.aero/developers/advanced-search/1.2.0/MinutesInTrail?model=ConceptualModel)  [`Terminal`](https://airm.aero/developers/advanced-search/1.2.0/Terminal?model=ConceptualModel)  [`FlightRestriction`](https://airm.aero/developers/advanced-search/1.2.0/FlightRestriction?model=ConceptualModel)  [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.2.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`ATFMPhase`](https://airm.aero/developers/advanced-search/1.2.0/ATFMPhase?model=ConceptualModel)  

![Image](.//media/cm/DemandAndCapacityBalancing.png)

## Taxonomies

###  ATFM Phases

Key concepts: [`ATMPlanning`](https://airm.aero/developers/advanced-search/1.2.0/ATMPlanning?model=ConceptualModel)  [`ATFMPhase`](https://airm.aero/developers/advanced-search/1.2.0/ATFMPhase?model=ConceptualModel)  


![Image](.//media/cm/DemandAndCapacityBalancing-Hierarchy-ATFM-Phases.png)

###  Capacities

Key concepts: [`DeclaredCapacity`](https://airm.aero/developers/advanced-search/1.2.0/DeclaredCapacity?model=ConceptualModel)  [`Capacity`](https://airm.aero/developers/advanced-search/1.2.0/Capacity?model=ConceptualModel)  


![Image](.//media/cm/DemandAndCapacityBalancing-Hierarchy-Capacities.png)

###  Strategic ATFM Measures

Key concepts: [`GroundDelayProgramme`](https://airm.aero/developers/advanced-search/1.2.0/GroundDelayProgramme?model=ConceptualModel)  [`ATFMMeasure`](https://airm.aero/developers/advanced-search/1.2.0/ATFMMeasure?model=ConceptualModel)  


![Image](.//media/cm/DemandAndCapacityBalancing-Hierarchy-Strategic-ATFM-Measures.png)

###  Tactical ATFM Measures

Key concepts: [`SlotSwapping`](https://airm.aero/developers/advanced-search/1.2.0/SlotSwapping?model=ConceptualModel)  [`MinutesInTrail`](https://airm.aero/developers/advanced-search/1.2.0/MinutesInTrail?model=ConceptualModel)  [`MilesInTrail`](https://airm.aero/developers/advanced-search/1.2.0/MilesInTrail?model=ConceptualModel)  [`GroundStop`](https://airm.aero/developers/advanced-search/1.2.0/GroundStop?model=ConceptualModel)  [`FixBalancing`](https://airm.aero/developers/advanced-search/1.2.0/FixBalancing?model=ConceptualModel)  [`AirborneHolding`](https://airm.aero/developers/advanced-search/1.2.0/AirborneHolding?model=ConceptualModel)  [`ATFMMeasure`](https://airm.aero/developers/advanced-search/1.2.0/ATFMMeasure?model=ConceptualModel)  


![Image](.//media/cm/DemandAndCapacityBalancing-Hierarchy-Tactical-ATFM-Measures.png)

## Analysis

###  Declared Capacity

The diagram illustrates the concept of declared capacity.

Key concepts: [`Aerodrome`](https://airm.aero/developers/advanced-search/1.2.0/Aerodrome?model=ConceptualModel)  [`SignificantPoint`](https://airm.aero/developers/advanced-search/1.2.0/SignificantPoint?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`AppropriateATSAuthority`](https://airm.aero/developers/advanced-search/1.2.0/AppropriateATSAuthority?model=ConceptualModel)  [`DeclaredCapacity`](https://airm.aero/developers/advanced-search/1.2.0/DeclaredCapacity?model=ConceptualModel)  

![Image](.//media/cm/DemandAndCapacityBalancing-Declared-Capacity.png)

###  Flight Condition Element

This diagram describes the concept of FlightConditionElement. FlightConditionElement groups conditions such as departing from an aerodrome, crossing the border between two airspaces, being able to fly RNAV etc. which, when combined with other FlightConditionElements via a FlightConditionExpression, constitute the FlightConditionCombination which must be satisfied in order for a traffic flow to be subject to the FlowRouting of the owning FlightRestriction.

Key concepts: [`FlightCrewApplicationAndApproval`](https://airm.aero/developers/advanced-search/1.2.0/FlightCrewApplicationAndApproval?model=ConceptualModel)  [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCapability?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`Aerodrome`](https://airm.aero/developers/advanced-search/1.2.0/Aerodrome?model=ConceptualModel)  [`FlightConditionElement`](https://airm.aero/developers/advanced-search/1.2.0/FlightConditionElement?model=ConceptualModel)  

![Image](.//media/cm/DemandAndCapacityBalancing-Flight-Condition-Element.png)

###  Flight Restriction

The diagram describes the concept of FlightRestriction.

Key concepts: [`FlightRestriction`](https://airm.aero/developers/advanced-search/1.2.0/FlightRestriction?model=ConceptualModel)  [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.2.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`FlightRestrictionRoute`](https://airm.aero/developers/advanced-search/1.2.0/FlightRestrictionRoute?model=ConceptualModel)  [`FlightConditionCombination`](https://airm.aero/developers/advanced-search/1.2.0/FlightConditionCombination?model=ConceptualModel)  [`FlightRoutingElement`](https://airm.aero/developers/advanced-search/1.2.0/FlightRoutingElement?model=ConceptualModel)  [`FlightConditionElement`](https://airm.aero/developers/advanced-search/1.2.0/FlightConditionElement?model=ConceptualModel)  

![Image](.//media/cm/DemandAndCapacityBalancing-Flight-Restriction.png)

###  Slot Swapping

An overview of slot swapping.

Key concepts: [`SlotSwapping`](https://airm.aero/developers/advanced-search/1.2.0/SlotSwapping?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.2.0/Flight?model=ConceptualModel)  

![Image](.//media/cm/DemandAndCapacityBalancing-Slot-Swapping.png)

