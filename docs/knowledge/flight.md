# Flight

## Overview

This diagram provides an overview of the main entities stored in the "Flight" Subject and highlights some relationships between Flight and other key ATM concepts modelled in other AIRM Subject: usage of the Infrastructure (Aircraft, Base and Airspace Infrastructure), links to Stakeholders, relationships with ATM phases and air traffic operations, exchange of flight-related information using messages etc...

Key concepts: [`FlightRoute`](https://airm.aero/developers/advanced-search/1.3.0/FlightRoute?model=ConceptualModel)  [`Aerodrome`](https://airm.aero/developers/advanced-search/1.3.0/Aerodrome?model=ConceptualModel)  [`VisualFlightRules`](https://airm.aero/developers/advanced-search/1.3.0/VisualFlightRules?model=ConceptualModel)  [`InstrumentFlightRules`](https://airm.aero/developers/advanced-search/1.3.0/InstrumentFlightRules?model=ConceptualModel)  [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.3.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`DepartureClearance`](https://airm.aero/developers/advanced-search/1.3.0/DepartureClearance?model=ConceptualModel)  [`FlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/FlightPlan?model=ConceptualModel)  [`GloballyUniqueFlightIdentifier`](https://airm.aero/developers/advanced-search/1.3.0/GloballyUniqueFlightIdentifier?model=ConceptualModel)  [`FlightPhase`](https://airm.aero/developers/advanced-search/1.3.0/FlightPhase?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`CrewMember`](https://airm.aero/developers/advanced-search/1.3.0/CrewMember?model=ConceptualModel)  [`Operator`](https://airm.aero/developers/advanced-search/1.3.0/Operator?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`FlightRules`](https://airm.aero/developers/advanced-search/1.3.0/FlightRules?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  

![Image](.//media/cm/Flight.png)

## Taxonomies

###  Airspeeds

Key concepts: [`TrueAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/TrueAirspeed?model=ConceptualModel)  [`IndicatedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/IndicatedAirspeed?model=ConceptualModel)  [`CruisingSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruisingSpeed?model=ConceptualModel)  [`CruiseClimbSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruiseClimbSpeed?model=ConceptualModel)  [`CalibratedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/CalibratedAirspeed?model=ConceptualModel)  [`PredictedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/PredictedAirspeed?model=ConceptualModel)  [`Airspeed`](https://airm.aero/developers/advanced-search/1.3.0/Airspeed?model=ConceptualModel)  


![Image](.//media/cm/Flight-Hierarchy-Airspeeds.png)

###  Flight Rules

Key concepts: [`VisualFlightRules`](https://airm.aero/developers/advanced-search/1.3.0/VisualFlightRules?model=ConceptualModel)  [`InstrumentFlightRules`](https://airm.aero/developers/advanced-search/1.3.0/InstrumentFlightRules?model=ConceptualModel)  [`FlightRules`](https://airm.aero/developers/advanced-search/1.3.0/FlightRules?model=ConceptualModel)  


![Image](.//media/cm/Flight-Hierarchy-Flight-Rules.png)

###  Types of Flight

Key concepts: [`VFRFlight`](https://airm.aero/developers/advanced-search/1.3.0/VFRFlight?model=ConceptualModel)  [`ThroughFlight`](https://airm.aero/developers/advanced-search/1.3.0/ThroughFlight?model=ConceptualModel)  [`SpecialVFRFlight`](https://airm.aero/developers/advanced-search/1.3.0/SpecialVFRFlight?model=ConceptualModel)  [`SearchAndRescueService`](https://airm.aero/developers/advanced-search/1.3.0/SearchAndRescueService?model=ConceptualModel)  [`ScheduledInternationalAirService`](https://airm.aero/developers/advanced-search/1.3.0/ScheduledInternationalAirService?model=ConceptualModel)  [`ReliefFlight`](https://airm.aero/developers/advanced-search/1.3.0/ReliefFlight?model=ConceptualModel)  [`RegionalAirService`](https://airm.aero/developers/advanced-search/1.3.0/RegionalAirService?model=ConceptualModel)  [`PassengerAirService`](https://airm.aero/developers/advanced-search/1.3.0/PassengerAirService?model=ConceptualModel)  [`NonScheduledInternationalFlight`](https://airm.aero/developers/advanced-search/1.3.0/NonScheduledInternationalFlight?model=ConceptualModel)  [`NonScheduledOperation`](https://airm.aero/developers/advanced-search/1.3.0/NonScheduledOperation?model=ConceptualModel)  [`InternationalAirService`](https://airm.aero/developers/advanced-search/1.3.0/InternationalAirService?model=ConceptualModel)  [`IFRFlight`](https://airm.aero/developers/advanced-search/1.3.0/IFRFlight?model=ConceptualModel)  [`ExtendedFlightOverWater`](https://airm.aero/developers/advanced-search/1.3.0/ExtendedFlightOverWater?model=ConceptualModel)  [`DomesticAirService`](https://airm.aero/developers/advanced-search/1.3.0/DomesticAirService?model=ConceptualModel)  [`CrossBorderService`](https://airm.aero/developers/advanced-search/1.3.0/CrossBorderService?model=ConceptualModel)  [`CorporateAviation`](https://airm.aero/developers/advanced-search/1.3.0/CorporateAviation?model=ConceptualModel)  [`AirTaxiService`](https://airm.aero/developers/advanced-search/1.3.0/AirTaxiService?model=ConceptualModel)  [`AirService`](https://airm.aero/developers/advanced-search/1.3.0/AirService?model=ConceptualModel)  [`AcrobaticFlight`](https://airm.aero/developers/advanced-search/1.3.0/AcrobaticFlight?model=ConceptualModel)  [`CargoAirService`](https://airm.aero/developers/advanced-search/1.3.0/CargoAirService?model=ConceptualModel)  [`MilitaryFlight`](https://airm.aero/developers/advanced-search/1.3.0/MilitaryFlight?model=ConceptualModel)  [`NonScheduledRevenueOperation`](https://airm.aero/developers/advanced-search/1.3.0/NonScheduledRevenueOperation?model=ConceptualModel)  [`ScheduledAirService`](https://airm.aero/developers/advanced-search/1.3.0/ScheduledAirService?model=ConceptualModel)  [`StateFlight`](https://airm.aero/developers/advanced-search/1.3.0/StateFlight?model=ConceptualModel)  [`AerialWork`](https://airm.aero/developers/advanced-search/1.3.0/AerialWork?model=ConceptualModel)  [`GeneralAviationOperation`](https://airm.aero/developers/advanced-search/1.3.0/GeneralAviationOperation?model=ConceptualModel)  [`CommercialAirTransportOperation`](https://airm.aero/developers/advanced-search/1.3.0/CommercialAirTransportOperation?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`FlightTrainingInstructionalFlight`](https://airm.aero/developers/advanced-search/1.3.0/FlightTrainingInstructionalFlight?model=ConceptualModel)  [`TrainingCheckFlight`](https://airm.aero/developers/advanced-search/1.3.0/TrainingCheckFlight?model=ConceptualModel)  [`PleasureFlight`](https://airm.aero/developers/advanced-search/1.3.0/PleasureFlight?model=ConceptualModel)  


![Image](.//media/cm/Flight-Hierarchy-Types-of-Flight.png)

## Analysis

###  Aircraft Movement

This diagram describes the aircraft movement concept.

Key concepts: [`AirportSlot`](https://airm.aero/developers/advanced-search/1.3.0/AirportSlot?model=ConceptualModel)  [`AircraftStand`](https://airm.aero/developers/advanced-search/1.3.0/AircraftStand?model=ConceptualModel)  [`Taxiway`](https://airm.aero/developers/advanced-search/1.3.0/Taxiway?model=ConceptualModel)  [`FlightPhase`](https://airm.aero/developers/advanced-search/1.3.0/FlightPhase?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`AircraftMovement`](https://airm.aero/developers/advanced-search/1.3.0/AircraftMovement?model=ConceptualModel)  

![Image](.//media/cm/Flight-Aircraft-Movement.png)

###  Aircraft State

The diagram describes the concept of AircraftState, also known as StateVector or AircraftStateVector, which represents the operational bahaviour or state of the aircraft during the flight.

Key concepts: [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`AircraftState`](https://airm.aero/developers/advanced-search/1.3.0/AircraftState?model=ConceptualModel)  [`GroundSpeed`](https://airm.aero/developers/advanced-search/1.3.0/GroundSpeed?model=ConceptualModel)  [`Airspeed`](https://airm.aero/developers/advanced-search/1.3.0/Airspeed?model=ConceptualModel)  

![Image](.//media/cm/Flight-Aircraft-State.png)

###  Estimated Elapsed Time

This diagram describes the ICAO concept of estimated elapsed time.

Key concepts: [`RoutePoint`](https://airm.aero/developers/advanced-search/1.3.0/RoutePoint?model=ConceptualModel)  [`FlightRoute`](https://airm.aero/developers/advanced-search/1.3.0/FlightRoute?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`TrajectorySegment`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySegment?model=ConceptualModel)  [`EstimatedElapsedTime`](https://airm.aero/developers/advanced-search/1.3.0/EstimatedElapsedTime?model=ConceptualModel)  [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryGroup?model=ConceptualModel)  [`RouteTrajectoryElement`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryElement?model=ConceptualModel)  [`SignificantPoint`](https://airm.aero/developers/advanced-search/1.3.0/SignificantPoint?model=ConceptualModel)  

![Image](.//media/cm/Flight-Estimated-Elapsed-Time.png)

###  FF-ICE/R1 Description of predicted movement

This diagram highlights the Flight Route the 4D Trajectory (in its FF-ICE Step 1 sense) as descriptions of the predicted movement of the aircraft in operation, and highlights their principal constituents.

Key concepts: [`FlightEvent`](https://airm.aero/developers/advanced-search/1.3.0/FlightEvent?model=ConceptualModel)  [`TrajectoryPointUsage`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryPointUsage?model=ConceptualModel)  [`FlightPhase`](https://airm.aero/developers/advanced-search/1.3.0/FlightPhase?model=ConceptualModel)  [`RoutePoint`](https://airm.aero/developers/advanced-search/1.3.0/RoutePoint?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`DepartureSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/DepartureSurfaceSegment?model=ConceptualModel)  [`ArrivalSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/ArrivalSurfaceSegment?model=ConceptualModel)  [`AirborneSegment`](https://airm.aero/developers/advanced-search/1.3.0/AirborneSegment?model=ConceptualModel)  [`TrajectorySegment`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySegment?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`FlightRoute`](https://airm.aero/developers/advanced-search/1.3.0/FlightRoute?model=ConceptualModel)  

![Image](.//media/cm/Flight-FF-ICE/R1-Description-of-predicted-movement.png)

###  Flight Capability

This diagram describes the flight capability which depends on the capabilities of the aircraft and the flight crew.

Key concepts: [`RequiredCommunicationPerformance`](https://airm.aero/developers/advanced-search/1.3.0/RequiredCommunicationPerformance?model=ConceptualModel)  [`RequiredNavigationPerformance`](https://airm.aero/developers/advanced-search/1.3.0/RequiredNavigationPerformance?model=ConceptualModel)  [`AircraftConfiguration`](https://airm.aero/developers/advanced-search/1.3.0/AircraftConfiguration?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`CrewMember`](https://airm.aero/developers/advanced-search/1.3.0/CrewMember?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`FlightCapability`](https://airm.aero/developers/advanced-search/1.3.0/FlightCapability?model=ConceptualModel)  [`FlightCrewMember`](https://airm.aero/developers/advanced-search/1.3.0/FlightCrewMember?model=ConceptualModel)  [`FlightCrewApplicationAndApproval`](https://airm.aero/developers/advanced-search/1.3.0/FlightCrewApplicationAndApproval?model=ConceptualModel)  [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.3.0/AircraftCapability?model=ConceptualModel)  

![Image](.//media/cm/Flight-Flight-Capability.png)

###  Flight Plan

The diagram provides an overview of the interrelations between the many variants of "Flight Plan".

Key concepts: [`Agent`](https://airm.aero/developers/advanced-search/1.3.0/Agent?model=ConceptualModel)  [`AirFiledFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/AirFiledFlightPlan?model=ConceptualModel)  [`CurrentFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/CurrentFlightPlan?model=ConceptualModel)  [`RepetitiveFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/RepetitiveFlightPlan?model=ConceptualModel)  [`OperationalFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/OperationalFlightPlan?model=ConceptualModel)  [`FiledFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/FiledFlightPlan?model=ConceptualModel)  [`FlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/FlightPlan?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`GloballyUniqueFlightIdentifier`](https://airm.aero/developers/advanced-search/1.3.0/GloballyUniqueFlightIdentifier?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`PerformanceProfile`](https://airm.aero/developers/advanced-search/1.3.0/PerformanceProfile?model=ConceptualModel)  [`SpeedSchedule`](https://airm.aero/developers/advanced-search/1.3.0/SpeedSchedule?model=ConceptualModel)  [`FormalOrganisation`](https://airm.aero/developers/advanced-search/1.3.0/FormalOrganisation?model=ConceptualModel)  [`StandardFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/StandardFlightPlan?model=ConceptualModel)  [`FficeFlightPlan`](https://airm.aero/developers/advanced-search/1.3.0/FficeFlightPlan?model=ConceptualModel)  

![Image](.//media/cm/Flight-Flight-Plan.png)

###  Formation Flight

This diagram describes the concept of formation flight, i.e. a flight consisting of more than one aircraft but operating as a single aircraft with regard to navigation and position reporting, as well as clearances issued by ATC.

Key concepts: [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`Mission`](https://airm.aero/developers/advanced-search/1.3.0/Mission?model=ConceptualModel)  [`Airspace`](https://airm.aero/developers/advanced-search/1.3.0/Airspace?model=ConceptualModel)  [`Aircraft`](https://airm.aero/developers/advanced-search/1.3.0/Aircraft?model=ConceptualModel)  [`FormationFlight`](https://airm.aero/developers/advanced-search/1.3.0/FormationFlight?model=ConceptualModel)  

![Image](.//media/cm/Flight-Formation-Flight.png)

###  IAS, CAS, TAS


Key concepts: [`IndicatedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/IndicatedAirspeed?model=ConceptualModel)  [`CalibratedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/CalibratedAirspeed?model=ConceptualModel)  [`TrueAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/TrueAirspeed?model=ConceptualModel)  [`MachNumber`](https://airm.aero/developers/advanced-search/1.3.0/MachNumber?model=ConceptualModel)  [`AirSpeedIndicator`](https://airm.aero/developers/advanced-search/1.3.0/AirSpeedIndicator?model=ConceptualModel)  

![Image](.//media/cm/Flight-IAS-CAS-TAS.png)

###  Speed, Level and Cruising Altitude

The diagram provides an overview of the Aircraft speed and cruising concepts.

Key concepts: [`TrueAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/TrueAirspeed?model=ConceptualModel)  [`ChangeOfCruiseLevelPhase`](https://airm.aero/developers/advanced-search/1.3.0/ChangeOfCruiseLevelPhase?model=ConceptualModel)  [`CruiseClimbSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruiseClimbSpeed?model=ConceptualModel)  [`CruisingSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruisingSpeed?model=ConceptualModel)  [`CruisePhase`](https://airm.aero/developers/advanced-search/1.3.0/CruisePhase?model=ConceptualModel)  

![Image](.//media/cm/Flight-Speed-Level-and-Cruising-Altitude.png)

###  Total Estimated Elapsed Time

This diagram describes the ICAO concept of total estimated elapsed time defined differently for IFR and VRF flights.

Key concepts: [`Aerodrome`](https://airm.aero/developers/advanced-search/1.3.0/Aerodrome?model=ConceptualModel)  [`InstrumentApproachProcedure`](https://airm.aero/developers/advanced-search/1.3.0/InstrumentApproachProcedure?model=ConceptualModel)  [`WheelsOff`](https://airm.aero/developers/advanced-search/1.3.0/WheelsOff?model=ConceptualModel)  [`TotalEstimatedElapsedTime`](https://airm.aero/developers/advanced-search/1.3.0/TotalEstimatedElapsedTime?model=ConceptualModel)  

![Image](.//media/cm/Flight-Total-Estimated-Elapsed-Time.png)

