# RouteAndProcedure

## Overview

The diagram provides an overview of the Routes (ATS Routes / North Atlantic Tracks / ...) and Procedures (SID/STAR/Appr) and serves as introduction to the content of AIRM package RouteAndProcedure.

Key concepts: [`SegmentLeg`](https://airm.aero/developers/advanced-search/1.2.0/SegmentLeg?model=ConceptualModel)  [`ProcedureTransition`](https://airm.aero/developers/advanced-search/1.2.0/ProcedureTransition?model=ConceptualModel)  [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/InstrumentApproachProcedure?model=ConceptualModel)  [`ATSRoute`](https://airm.aero/developers/advanced-search/1.2.0/ATSRoute?model=ConceptualModel)  [`StandardInstrumentDeparture`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentDeparture?model=ConceptualModel)  [`StandardInstrumentArrival`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentArrival?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.2.0/HoldingProcedure?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`SegmentPoint`](https://airm.aero/developers/advanced-search/1.2.0/SegmentPoint?model=ConceptualModel)  [`RouteLayout`](https://airm.aero/developers/advanced-search/1.2.0/RouteLayout?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure.png)

## Taxonomies

###  Routes

Key concepts: [`AreaNavigationRoute`](https://airm.aero/developers/advanced-search/1.2.0/AreaNavigationRoute?model=ConceptualModel)  [`ATSRoute`](https://airm.aero/developers/advanced-search/1.2.0/ATSRoute?model=ConceptualModel)  


![Image](.//media/cm/RouteAndProcedure-Hierarchy-Routes.png)

###  Terminal Procedures

Key concepts: [`PointInSpaceApproach`](https://airm.aero/developers/advanced-search/1.2.0/PointInSpaceApproach?model=ConceptualModel)  [`ApproachProcedureWithVerticalGuidance`](https://airm.aero/developers/advanced-search/1.2.0/ApproachProcedureWithVerticalGuidance?model=ConceptualModel)  [`PrecisionApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/PrecisionApproachProcedure?model=ConceptualModel)  [`NonPrecisionApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/NonPrecisionApproachProcedure?model=ConceptualModel)  [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/InstrumentApproachProcedure?model=ConceptualModel)  [`StandardInstrumentArrival`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentArrival?model=ConceptualModel)  [`StandardInstrumentDeparture`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentDeparture?model=ConceptualModel)  [`VisualApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/VisualApproachProcedure?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  


![Image](.//media/cm/RouteAndProcedure-Hierarchy-Terminal-Procedures.png)

###  Holding Procedures

Key concepts: [`UnplannedHolding`](https://airm.aero/developers/advanced-search/1.2.0/UnplannedHolding?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.2.0/HoldingProcedure?model=ConceptualModel)  


![Image](.//media/cm/RouteAndProcedure-Hierarchy-Holding-Procedures.png)

## Analysis

###  ATS Route

The diagram describes the ICAO concept of ATS Route.

Key concepts: [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`Airway`](https://airm.aero/developers/advanced-search/1.2.0/Airway?model=ConceptualModel)  [`StandardInstrumentDeparture`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentDeparture?model=ConceptualModel)  [`StandardInstrumentArrival`](https://airm.aero/developers/advanced-search/1.2.0/StandardInstrumentArrival?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`ATSRoute`](https://airm.aero/developers/advanced-search/1.2.0/ATSRoute?model=ConceptualModel)  [`RouteLayout`](https://airm.aero/developers/advanced-search/1.2.0/RouteLayout?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-ATS-Route.png)

###  DME/DME Navigation infrastructure

The diagram describes the infrastructure enabling DME/DME navigation.

Key concepts: [`SegmentLeg`](https://airm.aero/developers/advanced-search/1.2.0/SegmentLeg?model=ConceptualModel)  [`DME`](https://airm.aero/developers/advanced-search/1.2.0/DME?model=ConceptualModel)  [`RoutePortion`](https://airm.aero/developers/advanced-search/1.2.0/RoutePortion?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-DME/DME-Navigation-infrastructure.png)

###  Route Layout

The diagram describes the concept of Route Layout.

Key concepts: [`ATSRoute`](https://airm.aero/developers/advanced-search/1.2.0/ATSRoute?model=ConceptualModel)  [`AirTrafficControlService`](https://airm.aero/developers/advanced-search/1.2.0/AirTrafficControlService?model=ConceptualModel)  [`SegmentPoint`](https://airm.aero/developers/advanced-search/1.2.0/SegmentPoint?model=ConceptualModel)  [`RouteSegment`](https://airm.aero/developers/advanced-search/1.2.0/RouteSegment?model=ConceptualModel)  [`RoutePortion`](https://airm.aero/developers/advanced-search/1.2.0/RoutePortion?model=ConceptualModel)  [`RouteLayout`](https://airm.aero/developers/advanced-search/1.2.0/RouteLayout?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Route-Layout.png)

###  Aerial Refuelling

The diagram describes the concept of Aerial Refuelling.

Key concepts: [`RouteLayout`](https://airm.aero/developers/advanced-search/1.2.0/RouteLayout?model=ConceptualModel)  [`Geometry`](https://airm.aero/developers/advanced-search/1.2.0/Geometry?model=ConceptualModel)  [`SegmentPoint`](https://airm.aero/developers/advanced-search/1.2.0/SegmentPoint?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`AerialRefuelling`](https://airm.aero/developers/advanced-search/1.2.0/AerialRefuelling?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Aerial-Refuelling.png)

###  Holding Procedure

The diagram describes the concept of Holding Procedure.

Key concepts: [`UnplannedHolding`](https://airm.aero/developers/advanced-search/1.2.0/UnplannedHolding?model=ConceptualModel)  [`HoldingFix`](https://airm.aero/developers/advanced-search/1.2.0/HoldingFix?model=ConceptualModel)  [`TM_Duration`](https://airm.aero/developers/advanced-search/1.2.0/TM_Duration?model=ConceptualModel)  [`Distance`](https://airm.aero/developers/advanced-search/1.2.0/Distance?model=ConceptualModel)  [`Geometry`](https://airm.aero/developers/advanced-search/1.2.0/Geometry?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`AirTrafficControlService`](https://airm.aero/developers/advanced-search/1.2.0/AirTrafficControlService?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.2.0/HoldingProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Holding-Procedure.png)

###  Terminal Procedure

The diagram describes the concept of Terminal Procedure.

Key concepts: [`MinimumSectorAltitude`](https://airm.aero/developers/advanced-search/1.2.0/MinimumSectorAltitude?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`FlightCrewApplicationAndApproval`](https://airm.aero/developers/advanced-search/1.2.0/FlightCrewApplicationAndApproval?model=ConceptualModel)  [`TouchDownLiftOff`](https://airm.aero/developers/advanced-search/1.2.0/TouchDownLiftOff?model=ConceptualModel)  [`RunwayDirection`](https://airm.aero/developers/advanced-search/1.2.0/RunwayDirection?model=ConceptualModel)  [`NavigationAidInfrastructure`](https://airm.aero/developers/advanced-search/1.2.0/NavigationAidInfrastructure?model=ConceptualModel)  [`AircraftCategory`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCategory?model=ConceptualModel)  [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCapability?model=ConceptualModel)  [`Obstacle`](https://airm.aero/developers/advanced-search/1.2.0/Obstacle?model=ConceptualModel)  [`AirTrafficControlService`](https://airm.aero/developers/advanced-search/1.2.0/AirTrafficControlService?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.2.0/HoldingProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure.png)

###  Terminal Procedure - IAP

The diagram describes the decomposition of an instrument approach procedure into approach segments with their respective start and end points.

Key concepts: [`Minima`](https://airm.aero/developers/advanced-search/1.2.0/Minima?model=ConceptualModel)  [`Threshold`](https://airm.aero/developers/advanced-search/1.2.0/Threshold?model=ConceptualModel)  [`MissedApproachHoldingFix`](https://airm.aero/developers/advanced-search/1.2.0/MissedApproachHoldingFix?model=ConceptualModel)  [`MissedApproachPoint`](https://airm.aero/developers/advanced-search/1.2.0/MissedApproachPoint?model=ConceptualModel)  [`LandingThresholdPoint`](https://airm.aero/developers/advanced-search/1.2.0/LandingThresholdPoint?model=ConceptualModel)  [`FinalApproachFix`](https://airm.aero/developers/advanced-search/1.2.0/FinalApproachFix?model=ConceptualModel)  [`IntermediateFix`](https://airm.aero/developers/advanced-search/1.2.0/IntermediateFix?model=ConceptualModel)  [`InitialApproachFix`](https://airm.aero/developers/advanced-search/1.2.0/InitialApproachFix?model=ConceptualModel)  [`MissedApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/MissedApproachProcedure?model=ConceptualModel)  [`FinalApproachSegment`](https://airm.aero/developers/advanced-search/1.2.0/FinalApproachSegment?model=ConceptualModel)  [`IntermediateApproachSegment`](https://airm.aero/developers/advanced-search/1.2.0/IntermediateApproachSegment?model=ConceptualModel)  [`InitialApproachSegment`](https://airm.aero/developers/advanced-search/1.2.0/InitialApproachSegment?model=ConceptualModel)  [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/InstrumentApproachProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure---IAP.png)

###  Terminal Procedure - IAP - Final Approach Segment

The diagram describes the Final Approach Segment of an instrument approach procedure, highlighting its lateral and vertical components that are commonly provided by the navigation aid infrastructure.

Key concepts: [`RunwayCentreLine`](https://airm.aero/developers/advanced-search/1.2.0/RunwayCentreLine?model=ConceptualModel)  [`Threshold`](https://airm.aero/developers/advanced-search/1.2.0/Threshold?model=ConceptualModel)  [`LandingThresholdPoint`](https://airm.aero/developers/advanced-search/1.2.0/LandingThresholdPoint?model=ConceptualModel)  [`FictitiousThresholdPoint`](https://airm.aero/developers/advanced-search/1.2.0/FictitiousThresholdPoint?model=ConceptualModel)  [`FlightPathAlignmentPoint`](https://airm.aero/developers/advanced-search/1.2.0/FlightPathAlignmentPoint?model=ConceptualModel)  [`NavigationAidInfrastructure`](https://airm.aero/developers/advanced-search/1.2.0/NavigationAidInfrastructure?model=ConceptualModel)  [`FinalApproachTrack`](https://airm.aero/developers/advanced-search/1.2.0/FinalApproachTrack?model=ConceptualModel)  [`VerticalPathAngle`](https://airm.aero/developers/advanced-search/1.2.0/VerticalPathAngle?model=ConceptualModel)  [`GlidePath`](https://airm.aero/developers/advanced-search/1.2.0/GlidePath?model=ConceptualModel)  [`FinalApproachSegment`](https://airm.aero/developers/advanced-search/1.2.0/FinalApproachSegment?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure---IAP---Final-Approach-Segment.png)

###  Terminal Procedure - IAP - Other Parts

The diagram lists the segments of an instrument approach procedure for which no specific "Analysis" diagram is created in the AIRM.

Key concepts: [`MissedApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/MissedApproachProcedure?model=ConceptualModel)  [`FinalApproach`](https://airm.aero/developers/advanced-search/1.2.0/FinalApproach?model=ConceptualModel)  [`CirclingApproach`](https://airm.aero/developers/advanced-search/1.2.0/CirclingApproach?model=ConceptualModel)  [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/InstrumentApproachProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure---IAP---Other-Parts.png)

###  Terminal Procedure - Procedure Encoding

The diagram provides a description of terminal procedures (and holding procedures) from a "Procedure Encoding" view point. It essentially describes the decomposition of terminal procedures into procedure transitions and segment legs.

Key concepts: [`DME`](https://airm.aero/developers/advanced-search/1.2.0/DME?model=ConceptualModel)  [`RadioNavigationAid`](https://airm.aero/developers/advanced-search/1.2.0/RadioNavigationAid?model=ConceptualModel)  [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCapability?model=ConceptualModel)  [`AircraftCategory`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCategory?model=ConceptualModel)  [`SegmentPoint`](https://airm.aero/developers/advanced-search/1.2.0/SegmentPoint?model=ConceptualModel)  [`SegmentLeg`](https://airm.aero/developers/advanced-search/1.2.0/SegmentLeg?model=ConceptualModel)  [`ProcedureTransition`](https://airm.aero/developers/advanced-search/1.2.0/ProcedureTransition?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.2.0/HoldingProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure---Procedure-Encoding.png)

###  Terminal Procedure - DA/DH and MDA/MDH

The diagram describes the ICAO concepts of Decision Altitude/Height and Minimum Descent Altitude/Height associated with approach procedures.

Key concepts: [`AircraftCategory`](https://airm.aero/developers/advanced-search/1.2.0/AircraftCategory?model=ConceptualModel)  [`DecisionHeight`](https://airm.aero/developers/advanced-search/1.2.0/DecisionHeight?model=ConceptualModel)  [`DecisionAltitude`](https://airm.aero/developers/advanced-search/1.2.0/DecisionAltitude?model=ConceptualModel)  [`MinimumDescentHeight`](https://airm.aero/developers/advanced-search/1.2.0/MinimumDescentHeight?model=ConceptualModel)  [`MinimumDescentAltitude`](https://airm.aero/developers/advanced-search/1.2.0/MinimumDescentAltitude?model=ConceptualModel)  [`PrecisionApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/PrecisionApproachProcedure?model=ConceptualModel)  [`ApproachProcedureWithVerticalGuidance`](https://airm.aero/developers/advanced-search/1.2.0/ApproachProcedureWithVerticalGuidance?model=ConceptualModel)  [`NonPrecisionApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/NonPrecisionApproachProcedure?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Terminal-Procedure---DA/DH-and-MDA/MDH.png)

###  TAA

The diagram describes the ICAO concept of Terminal Arrival Altitude.

Key concepts: [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.2.0/InstrumentApproachProcedure?model=ConceptualModel)  [`IntermediateFix`](https://airm.aero/developers/advanced-search/1.2.0/IntermediateFix?model=ConceptualModel)  [`InitialApproachFix`](https://airm.aero/developers/advanced-search/1.2.0/InitialApproachFix?model=ConceptualModel)  [`TerminalArrivalAltitude`](https://airm.aero/developers/advanced-search/1.2.0/TerminalArrivalAltitude?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-TAA.png)

###  MEA, MOCA

The diagram describes the ICAO concepts of Minimum EnRoute Altitude and Minimum Obstacle Clearance Altitude.

Key concepts: [`Obstacle`](https://airm.aero/developers/advanced-search/1.2.0/Obstacle?model=ConceptualModel)  [`MinimumObstacleClearanceAltitude`](https://airm.aero/developers/advanced-search/1.2.0/MinimumObstacleClearanceAltitude?model=ConceptualModel)  [`MinimumEnRouteAltitude`](https://airm.aero/developers/advanced-search/1.2.0/MinimumEnRouteAltitude?model=ConceptualModel)  [`Geometry`](https://airm.aero/developers/advanced-search/1.2.0/Geometry?model=ConceptualModel)  [`RouteSegment`](https://airm.aero/developers/advanced-search/1.2.0/RouteSegment?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-MEA-MOCA.png)

###  MSA

The diagram describes the concept of Minimum Sector Altitude.

Key concepts: [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.2.0/TerminalProcedure?model=ConceptualModel)  [`SignificantPoint`](https://airm.aero/developers/advanced-search/1.2.0/SignificantPoint?model=ConceptualModel)  [`Heliport`](https://airm.aero/developers/advanced-search/1.2.0/Heliport?model=ConceptualModel)  [`Aerodrome`](https://airm.aero/developers/advanced-search/1.2.0/Aerodrome?model=ConceptualModel)  [`MinimumSectorAltitude`](https://airm.aero/developers/advanced-search/1.2.0/MinimumSectorAltitude?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-MSA.png)

###  Obstruction

The diagram describes the concept of Obstruction.

Key concepts: [`Terrain`](https://airm.aero/developers/advanced-search/1.2.0/Terrain?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.2.0/Airspace?model=ConceptualModel)  [`Obstacle`](https://airm.aero/developers/advanced-search/1.2.0/Obstacle?model=ConceptualModel)  [`VerticalStructure`](https://airm.aero/developers/advanced-search/1.2.0/VerticalStructure?model=ConceptualModel)  [`Obstruction`](https://airm.aero/developers/advanced-search/1.2.0/Obstruction?model=ConceptualModel)  

![Image](.//media/cm/RouteAndProcedure-Obstruction.png)

