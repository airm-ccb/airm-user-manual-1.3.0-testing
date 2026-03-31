# EmergencyOperations

## Overview

This diagram now shows an overview of the canonical communication flows in case of an emergency, which are defined by Annex 11 section 5, Annex 12 section 5 and PANS-ATM section 11.4.1

Key concepts: [`SearchAndRescueService`](https://airm.aero/developers/advanced-search/1.3.0/SearchAndRescueService?model=ConceptualModel)  [`AlertMessage`](https://airm.aero/developers/advanced-search/1.3.0/AlertMessage?model=ConceptualModel)  [`EmergencyPhase`](https://airm.aero/developers/advanced-search/1.3.0/EmergencyPhase?model=ConceptualModel)  [`AirTrafficServicesUnit`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficServicesUnit?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`Operator`](https://airm.aero/developers/advanced-search/1.3.0/Operator?model=ConceptualModel)  [`RescueCoordinationCentre`](https://airm.aero/developers/advanced-search/1.3.0/RescueCoordinationCentre?model=ConceptualModel)  [`AirTrafficControlUnit`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficControlUnit?model=ConceptualModel)  [`FlightInformationCentre`](https://airm.aero/developers/advanced-search/1.3.0/FlightInformationCentre?model=ConceptualModel)  [`AlertingService`](https://airm.aero/developers/advanced-search/1.3.0/AlertingService?model=ConceptualModel)  [`LastContact`](https://airm.aero/developers/advanced-search/1.3.0/LastContact?model=ConceptualModel)  [`AirTrafficService`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficService?model=ConceptualModel)  [`LastPositionReport`](https://airm.aero/developers/advanced-search/1.3.0/LastPositionReport?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations.png)

## Taxonomies

###  Emergency phases

Key concepts: [`EmergencyPhase`](https://airm.aero/developers/advanced-search/1.3.0/EmergencyPhase?model=ConceptualModel)  [`DistressPhase`](https://airm.aero/developers/advanced-search/1.3.0/DistressPhase?model=ConceptualModel)  [`AlertPhase`](https://airm.aero/developers/advanced-search/1.3.0/AlertPhase?model=ConceptualModel)  [`UncertaintyPhase`](https://airm.aero/developers/advanced-search/1.3.0/UncertaintyPhase?model=ConceptualModel)  


![Image](.//media/cm/EmergencyOperations-Hierarchy-Emergency-phases.png)

## Analysis

###  GADSS

The diagram provides an overview of the main GADSS functions.

Key concepts: [`SearchAndRescueService`](https://airm.aero/developers/advanced-search/1.3.0/SearchAndRescueService?model=ConceptualModel)  [`PostFlightLocalisation`](https://airm.aero/developers/advanced-search/1.3.0/PostFlightLocalisation?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`EmergencyPhase`](https://airm.aero/developers/advanced-search/1.3.0/EmergencyPhase?model=ConceptualModel)  [`DistressPhase`](https://airm.aero/developers/advanced-search/1.3.0/DistressPhase?model=ConceptualModel)  [`AutonomousDistressTracking`](https://airm.aero/developers/advanced-search/1.3.0/AutonomousDistressTracking?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`AircraftState`](https://airm.aero/developers/advanced-search/1.3.0/AircraftState?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`Operator`](https://airm.aero/developers/advanced-search/1.3.0/Operator?model=ConceptualModel)  [`AircraftTracking`](https://airm.aero/developers/advanced-search/1.3.0/AircraftTracking?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations-GADSS.png)

###  LADR

i>Content: The diagram describes the ground and satellite-based infrastructure components of the GADSS, and the new type of aircraft equipment performing the GADSS ADT function . The notion of accredited ADTServiceProvider is further explained in Subject Stakeholders.

Key concepts: [`SearchAndRescueService`](https://airm.aero/developers/advanced-search/1.3.0/SearchAndRescueService?model=ConceptualModel)  [`AutonomousDistressTrackingServiceProvider`](https://airm.aero/developers/advanced-search/1.3.0/AutonomousDistressTrackingServiceProvider?model=ConceptualModel)  [`DistressTrackingEmergencyLocatorTransmitter`](https://airm.aero/developers/advanced-search/1.3.0/DistressTrackingEmergencyLocatorTransmitter?model=ConceptualModel)  [`PostFlightLocalisation`](https://airm.aero/developers/advanced-search/1.3.0/PostFlightLocalisation?model=ConceptualModel)  [`AutonomousDistressTracking`](https://airm.aero/developers/advanced-search/1.3.0/AutonomousDistressTracking?model=ConceptualModel)  [`LocationOfAnAircraftInDistressRepository`](https://airm.aero/developers/advanced-search/1.3.0/LocationOfAnAircraftInDistressRepository?model=ConceptualModel)  [`SatelliteBasedDistressTrackingSystem`](https://airm.aero/developers/advanced-search/1.3.0/SatelliteBasedDistressTrackingSystem?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations-LADR.png)

###  Last Contact, Last Position report, RadioCommunicationFailure


Key concepts: [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`LastContact`](https://airm.aero/developers/advanced-search/1.3.0/LastContact?model=ConceptualModel)  [`RadioCommunicationFailure`](https://airm.aero/developers/advanced-search/1.3.0/RadioCommunicationFailure?model=ConceptualModel)  [`LastPositionReport`](https://airm.aero/developers/advanced-search/1.3.0/LastPositionReport?model=ConceptualModel)  [`AirTrafficServicesUnit`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficServicesUnit?model=ConceptualModel)  [`AirTrafficService`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficService?model=ConceptualModel)  [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.3.0/AircraftCapability?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations-Last-Contact-Last-Position-report-RadioCommunicationFailure.png)

###  Alert Messages

The diagram describes the information flows in emergency situations as stipulated by ICAO Annex 12 Chapter 5.

Key concepts: [`RescueCoordinationCentre`](https://airm.aero/developers/advanced-search/1.3.0/RescueCoordinationCentre?model=ConceptualModel)  [`AirTrafficServicesUnit`](https://airm.aero/developers/advanced-search/1.3.0/AirTrafficServicesUnit?model=ConceptualModel)  [`AlertMessage`](https://airm.aero/developers/advanced-search/1.3.0/AlertMessage?model=ConceptualModel)  [`EmergencyPhase`](https://airm.aero/developers/advanced-search/1.3.0/EmergencyPhase?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations-Alert-Messages.png)

###  Distress Event

i>Content: The diagram describes the concept of DistressEvent that is central to the LADR operations.

Key concepts: [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`LocationOfAnAircraftInDistressRepository`](https://airm.aero/developers/advanced-search/1.3.0/LocationOfAnAircraftInDistressRepository?model=ConceptualModel)  [`DistressPhase`](https://airm.aero/developers/advanced-search/1.3.0/DistressPhase?model=ConceptualModel)  [`DistressEvent`](https://airm.aero/developers/advanced-search/1.3.0/DistressEvent?model=ConceptualModel)  

![Image](.//media/cm/EmergencyOperations-Distress-Event.png)

