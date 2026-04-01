# Movement

## Overview

This diagram describes at high level the ICAO concept of 4D Trajectory.

Key concepts: [`Flight`](https://airm.aero/developers/advanced-search/1.3.0/Flight?model=ConceptualModel)  [`FlightRoute`](https://airm.aero/developers/advanced-search/1.3.0/FlightRoute?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.3.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`TopOfClimb`](https://airm.aero/developers/advanced-search/1.3.0/TopOfClimb?model=ConceptualModel)  [`TrajectoryPointUsage`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryPointUsage?model=ConceptualModel)  [`ExpandedRoute`](https://airm.aero/developers/advanced-search/1.3.0/ExpandedRoute?model=ConceptualModel)  [`RouteTrajectoryElement`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryElement?model=ConceptualModel)  [`FlightEvent`](https://airm.aero/developers/advanced-search/1.3.0/FlightEvent?model=ConceptualModel)  [`RoutePoint`](https://airm.aero/developers/advanced-search/1.3.0/RoutePoint?model=ConceptualModel)  [`ConstraintPoint`](https://airm.aero/developers/advanced-search/1.3.0/ConstraintPoint?model=ConceptualModel)  [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryGroup?model=ConceptualModel)  

![Image](.//media/cm/Movement.png)

## Taxonomies

###  Trajectory Constraints

Key concepts: [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.3.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`TimeConstraint`](https://airm.aero/developers/advanced-search/1.3.0/TimeConstraint?model=ConceptualModel)  [`SpeedConstraint`](https://airm.aero/developers/advanced-search/1.3.0/SpeedConstraint?model=ConceptualModel)  [`VerticalConstraint`](https://airm.aero/developers/advanced-search/1.3.0/VerticalConstraint?model=ConceptualModel)  [`LateralConstraint`](https://airm.aero/developers/advanced-search/1.3.0/LateralConstraint?model=ConceptualModel)  


![Image](.//media/cm/Movement-Hierarchy-Trajectory-Constraints.png)

###  Trajectory Point Usages

Key concepts: [`TrajectoryChangePoint`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryChangePoint?model=ConceptualModel)  [`EndPredictionPoint`](https://airm.aero/developers/advanced-search/1.3.0/EndPredictionPoint?model=ConceptualModel)  [`InitialPredictionPoint`](https://airm.aero/developers/advanced-search/1.3.0/InitialPredictionPoint?model=ConceptualModel)  [`CrossOverAltitudePoint`](https://airm.aero/developers/advanced-search/1.3.0/CrossOverAltitudePoint?model=ConceptualModel)  [`TopOfDescent`](https://airm.aero/developers/advanced-search/1.3.0/TopOfDescent?model=ConceptualModel)  [`TopOfClimb`](https://airm.aero/developers/advanced-search/1.3.0/TopOfClimb?model=ConceptualModel)  [`TrajectoryPointUsage`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryPointUsage?model=ConceptualModel)  [`PrescribedEETReportingPoint`](https://airm.aero/developers/advanced-search/1.3.0/PrescribedEETReportingPoint?model=ConceptualModel)  


![Image](.//media/cm/Movement-Hierarchy-Trajectory-Point-Usages.png)

###  Trajectory Segments

Key concepts: [`TrajectorySegment`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySegment?model=ConceptualModel)  [`DepartureSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/DepartureSurfaceSegment?model=ConceptualModel)  [`ArrivalSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/ArrivalSurfaceSegment?model=ConceptualModel)  [`AirborneSegment`](https://airm.aero/developers/advanced-search/1.3.0/AirborneSegment?model=ConceptualModel)  


![Image](.//media/cm/Movement-Hierarchy-Trajectory-Segments.png)

## Analysis

###  FF-ICE ATM Trajectory Constraint

This diagram describes the concept of ATM Trajectory Constraint.

Key concepts: [`ATCInstruction`](https://airm.aero/developers/advanced-search/1.3.0/ATCInstruction?model=ConceptualModel)  [`ATMTrajectoryConstraint`](https://airm.aero/developers/advanced-search/1.3.0/ATMTrajectoryConstraint?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`ConstraintPoint`](https://airm.aero/developers/advanced-search/1.3.0/ConstraintPoint?model=ConceptualModel)  [`TrajectoryPointUsage`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryPointUsage?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE-ATM-Trajectory-Constraint.png)

###  FF-ICE Arrival Surface Segment

This diagram describes the ICAO FF-ICE concept of Arrival Surface Segment.

Key concepts: [`InBlock`](https://airm.aero/developers/advanced-search/1.3.0/InBlock?model=ConceptualModel)  [`WheelsOn`](https://airm.aero/developers/advanced-search/1.3.0/WheelsOn?model=ConceptualModel)  [`ArrivalOperations`](https://airm.aero/developers/advanced-search/1.3.0/ArrivalOperations?model=ConceptualModel)  [`ArrivalSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/ArrivalSurfaceSegment?model=ConceptualModel)  [`AirportSlot`](https://airm.aero/developers/advanced-search/1.3.0/AirportSlot?model=ConceptualModel)  [`Taxiway`](https://airm.aero/developers/advanced-search/1.3.0/Taxiway?model=ConceptualModel)  [`Runway`](https://airm.aero/developers/advanced-search/1.3.0/Runway?model=ConceptualModel)  [`AircraftStand`](https://airm.aero/developers/advanced-search/1.3.0/AircraftStand?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE-Arrival-Surface-Segment.png)

###  FF-ICE Departure Surface Segment

This diagram describes the ICAO FF-ICE concept of Departure Surface Segment.

Key concepts: [`AirportSlot`](https://airm.aero/developers/advanced-search/1.3.0/AirportSlot?model=ConceptualModel)  [`Taxiway`](https://airm.aero/developers/advanced-search/1.3.0/Taxiway?model=ConceptualModel)  [`Runway`](https://airm.aero/developers/advanced-search/1.3.0/Runway?model=ConceptualModel)  [`AircraftStand`](https://airm.aero/developers/advanced-search/1.3.0/AircraftStand?model=ConceptualModel)  [`StartUp`](https://airm.aero/developers/advanced-search/1.3.0/StartUp?model=ConceptualModel)  [`OffBlock`](https://airm.aero/developers/advanced-search/1.3.0/OffBlock?model=ConceptualModel)  [`WheelsOff`](https://airm.aero/developers/advanced-search/1.3.0/WheelsOff?model=ConceptualModel)  [`DepartureOperations`](https://airm.aero/developers/advanced-search/1.3.0/DepartureOperations?model=ConceptualModel)  [`DepartureSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/DepartureSurfaceSegment?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE-Departure-Surface-Segment.png)

###  FF-ICE Executed 4D Trajectory

This diagram describes the ICAO FF-ICE concept of Executed 4D Trajectory, which corresponds to the trajectory effectively achieved by the flight.

Key concepts: [`AircraftCapability`](https://airm.aero/developers/advanced-search/1.3.0/AircraftCapability?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`Executed4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/Executed4DTrajectory?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE-Executed-4D-Trajectory.png)

###  FF-ICE/R1 Relationship of Route to Trajectory

This diagram shows the three level of granularity that exists when describing the movement of the aircraft, namely Route, Expanded Route &amp; Trajectory

Key concepts: [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryGroup?model=ConceptualModel)  [`ExpandedRoute`](https://airm.aero/developers/advanced-search/1.3.0/ExpandedRoute?model=ConceptualModel)  [`RouteTrajectoryElement`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryElement?model=ConceptualModel)  [`TrajectorySegment`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySegment?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`FlightRoute`](https://airm.aero/developers/advanced-search/1.3.0/FlightRoute?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Relationship-of-Route-to-Trajectory.png)

###  FF-ICE/R1 RouteTrajectoryGroup

This diagram describes the ICAO FF-ICE/R1 concept of RouteTrajectoryGroup.

Key concepts: [`EstimatedTakeOffWeight`](https://airm.aero/developers/advanced-search/1.3.0/EstimatedTakeOffWeight?model=ConceptualModel)  [`PerformanceProfile`](https://airm.aero/developers/advanced-search/1.3.0/PerformanceProfile?model=ConceptualModel)  [`AlongRouteDistance`](https://airm.aero/developers/advanced-search/1.3.0/AlongRouteDistance?model=ConceptualModel)  [`PredictedGroundSpeed`](https://airm.aero/developers/advanced-search/1.3.0/PredictedGroundSpeed?model=ConceptualModel)  [`CruisingLevel`](https://airm.aero/developers/advanced-search/1.3.0/CruisingLevel?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.3.0/TerminalProcedure?model=ConceptualModel)  [`TotalEstimatedElapsedTime`](https://airm.aero/developers/advanced-search/1.3.0/TotalEstimatedElapsedTime?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`ATSRoute`](https://airm.aero/developers/advanced-search/1.3.0/ATSRoute?model=ConceptualModel)  [`RouteTrajectoryElement`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryElement?model=ConceptualModel)  [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryGroup?model=ConceptualModel)  [`SpeedSchedule`](https://airm.aero/developers/advanced-search/1.3.0/SpeedSchedule?model=ConceptualModel)  [`DirectFlightSegment`](https://airm.aero/developers/advanced-search/1.3.0/DirectFlightSegment?model=ConceptualModel)  [`CruisingSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruisingSpeed?model=ConceptualModel)  [`InfrastructurePoint`](https://airm.aero/developers/advanced-search/1.3.0/InfrastructurePoint?model=ConceptualModel)  [`PlannedDelay`](https://airm.aero/developers/advanced-search/1.3.0/PlannedDelay?model=ConceptualModel)  [`RoutePoint`](https://airm.aero/developers/advanced-search/1.3.0/RoutePoint?model=ConceptualModel)  [`PredictedAirspeed`](https://airm.aero/developers/advanced-search/1.3.0/PredictedAirspeed?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-RouteTrajectoryGroup.png)

###  FF-ICE/R1 Trajectory point properties: Carrying out particular operations

This diagram lists the properties of trajectory points associated with particular airspace user operations (e.g. EET reporting) or ATM operations.

Key concepts: [`FlightEvent`](https://airm.aero/developers/advanced-search/1.3.0/FlightEvent?model=ConceptualModel)  [`TrajectoryPointUsage`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryPointUsage?model=ConceptualModel)  [`FlightRules`](https://airm.aero/developers/advanced-search/1.3.0/FlightRules?model=ConceptualModel)  [`EstimatedElapsedTime`](https://airm.aero/developers/advanced-search/1.3.0/EstimatedElapsedTime?model=ConceptualModel)  [`PrescribedEETReportingPoint`](https://airm.aero/developers/advanced-search/1.3.0/PrescribedEETReportingPoint?model=ConceptualModel)  [`CrossOverAltitudePoint`](https://airm.aero/developers/advanced-search/1.3.0/CrossOverAltitudePoint?model=ConceptualModel)  [`EstimatedElapsedTimeReporting`](https://airm.aero/developers/advanced-search/1.3.0/EstimatedElapsedTimeReporting?model=ConceptualModel)  [`EndOfExpectVectors`](https://airm.aero/developers/advanced-search/1.3.0/EndOfExpectVectors?model=ConceptualModel)  [`StartOfExpectVectors`](https://airm.aero/developers/advanced-search/1.3.0/StartOfExpectVectors?model=ConceptualModel)  [`FlightInformationRegion`](https://airm.aero/developers/advanced-search/1.3.0/FlightInformationRegion?model=ConceptualModel)  [`FlightRulesChange`](https://airm.aero/developers/advanced-search/1.3.0/FlightRulesChange?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Trajectory-point-properties-Carrying-out-particular-operations.png)

###  FF-ICE/R1 Trajectory point properties: Change of aircraft dynamics

This diagram lists the properties of trajectory points associated with particular changes of aircraft dynamics.

Key concepts: [`CruisingLevel`](https://airm.aero/developers/advanced-search/1.3.0/CruisingLevel?model=ConceptualModel)  [`CruisingSpeed`](https://airm.aero/developers/advanced-search/1.3.0/CruisingSpeed?model=ConceptualModel)  [`TrajectoryChangePoint`](https://airm.aero/developers/advanced-search/1.3.0/TrajectoryChangePoint?model=ConceptualModel)  [`Heading`](https://airm.aero/developers/advanced-search/1.3.0/Heading?model=ConceptualModel)  [`Course`](https://airm.aero/developers/advanced-search/1.3.0/Course?model=ConceptualModel)  [`Track`](https://airm.aero/developers/advanced-search/1.3.0/Track?model=ConceptualModel)  [`LateralChange`](https://airm.aero/developers/advanced-search/1.3.0/LateralChange?model=ConceptualModel)  [`Altitude`](https://airm.aero/developers/advanced-search/1.3.0/Altitude?model=ConceptualModel)  [`Height`](https://airm.aero/developers/advanced-search/1.3.0/Height?model=ConceptualModel)  [`FlightLevel`](https://airm.aero/developers/advanced-search/1.3.0/FlightLevel?model=ConceptualModel)  [`Level`](https://airm.aero/developers/advanced-search/1.3.0/Level?model=ConceptualModel)  [`CrossBorderArea`](https://airm.aero/developers/advanced-search/1.3.0/CrossBorderArea?model=ConceptualModel)  [`SpeedChange`](https://airm.aero/developers/advanced-search/1.3.0/SpeedChange?model=ConceptualModel)  [`LevelChange`](https://airm.aero/developers/advanced-search/1.3.0/LevelChange?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Trajectory-point-properties-Change-of-aircraft-dynamics.png)

###  FF-ICE/R1 Trajectory point properties: Crossing airspace

This diagram lists the properties of trajectory points associated with the crossing of airspaces.

Key concepts: [`TransitionLayer`](https://airm.aero/developers/advanced-search/1.3.0/TransitionLayer?model=ConceptualModel)  [`ConstrainedAirspaceCrossing`](https://airm.aero/developers/advanced-search/1.3.0/ConstrainedAirspaceCrossing?model=ConceptualModel)  [`ExitIntoConstrainedAirspace`](https://airm.aero/developers/advanced-search/1.3.0/ExitIntoConstrainedAirspace?model=ConceptualModel)  [`EntryIntoConstrainedAirspace`](https://airm.aero/developers/advanced-search/1.3.0/EntryIntoConstrainedAirspace?model=ConceptualModel)  [`ExitFromRestrictedORReservedAirspace`](https://airm.aero/developers/advanced-search/1.3.0/ExitFromRestrictedORReservedAirspace?model=ConceptualModel)  [`AirspaceRestriction`](https://airm.aero/developers/advanced-search/1.3.0/AirspaceRestriction?model=ConceptualModel)  [`EntryIntoAnRestrictedOrReservedAirspace`](https://airm.aero/developers/advanced-search/1.3.0/EntryIntoAnRestrictedOrReservedAirspace?model=ConceptualModel)  [`FlightInformationRegion`](https://airm.aero/developers/advanced-search/1.3.0/FlightInformationRegion?model=ConceptualModel)  [`FIRBoundaryCrossing`](https://airm.aero/developers/advanced-search/1.3.0/FIRBoundaryCrossing?model=ConceptualModel)  [`TransitionAltitude`](https://airm.aero/developers/advanced-search/1.3.0/TransitionAltitude?model=ConceptualModel)  [`TransitionLevel`](https://airm.aero/developers/advanced-search/1.3.0/TransitionLevel?model=ConceptualModel)  [`TransitionAltitudeOrLevelCrossing`](https://airm.aero/developers/advanced-search/1.3.0/TransitionAltitudeOrLevelCrossing?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Trajectory-point-properties-Crossing-airspace.png)

###  FF-ICE/R1 Trajectory point properties: Start or end of flight phases

This diagram lists the properties of trajectory points associated with particular phases of Flight. In particular, this diagram brings together the FF-ICE/R1 semantics for trajectory points and the ICAO ADREP 2000 semantics for flight phases.

Key concepts: [`ClimbToCruisingLevelOrAltitude`](https://airm.aero/developers/advanced-search/1.3.0/ClimbToCruisingLevelOrAltitude?model=ConceptualModel)  [`ChangeOfCruiseLevelPhase`](https://airm.aero/developers/advanced-search/1.3.0/ChangeOfCruiseLevelPhase?model=ConceptualModel)  [`EndStay`](https://airm.aero/developers/advanced-search/1.3.0/EndStay?model=ConceptualModel)  [`StayPhase`](https://airm.aero/developers/advanced-search/1.3.0/StayPhase?model=ConceptualModel)  [`BeginStay`](https://airm.aero/developers/advanced-search/1.3.0/BeginStay?model=ConceptualModel)  [`CruisePhase`](https://airm.aero/developers/advanced-search/1.3.0/CruisePhase?model=ConceptualModel)  [`NormalDescent`](https://airm.aero/developers/advanced-search/1.3.0/NormalDescent?model=ConceptualModel)  [`TopOfDescent`](https://airm.aero/developers/advanced-search/1.3.0/TopOfDescent?model=ConceptualModel)  [`TopOfClimb`](https://airm.aero/developers/advanced-search/1.3.0/TopOfClimb?model=ConceptualModel)  [`TakeOffPhase`](https://airm.aero/developers/advanced-search/1.3.0/TakeOffPhase?model=ConceptualModel)  [`StartOfTakeOffRoll`](https://airm.aero/developers/advanced-search/1.3.0/StartOfTakeOffRoll?model=ConceptualModel)  [`TakeOffRun`](https://airm.aero/developers/advanced-search/1.3.0/TakeOffRun?model=ConceptualModel)  [`WheelsOff`](https://airm.aero/developers/advanced-search/1.3.0/WheelsOff?model=ConceptualModel)  [`LandingRoll`](https://airm.aero/developers/advanced-search/1.3.0/LandingRoll?model=ConceptualModel)  [`EndOfLandingRoll`](https://airm.aero/developers/advanced-search/1.3.0/EndOfLandingRoll?model=ConceptualModel)  [`RunwayDirection`](https://airm.aero/developers/advanced-search/1.3.0/RunwayDirection?model=ConceptualModel)  [`LandingPhase`](https://airm.aero/developers/advanced-search/1.3.0/LandingPhase?model=ConceptualModel)  [`LevelOffTouchdown`](https://airm.aero/developers/advanced-search/1.3.0/LevelOffTouchdown?model=ConceptualModel)  [`WheelsOn`](https://airm.aero/developers/advanced-search/1.3.0/WheelsOn?model=ConceptualModel)  [`HoldingProcedure`](https://airm.aero/developers/advanced-search/1.3.0/HoldingProcedure?model=ConceptualModel)  [`HoldExit`](https://airm.aero/developers/advanced-search/1.3.0/HoldExit?model=ConceptualModel)  [`HoldEntry`](https://airm.aero/developers/advanced-search/1.3.0/HoldEntry?model=ConceptualModel)  [`ApproachHolding`](https://airm.aero/developers/advanced-search/1.3.0/ApproachHolding?model=ConceptualModel)  [`EnRouteHolding`](https://airm.aero/developers/advanced-search/1.3.0/EnRouteHolding?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Trajectory-point-properties-Start-or-end-of-flight-phases.png)

###  FF-ICE/R1 Trajectory point properties: Use of the aerodrome infrastructure

This diagram lists the properties of the trajectory points matching infrastructure points related to aerodromes.

Key concepts: [`AerodromeReferencePoint`](https://airm.aero/developers/advanced-search/1.3.0/AerodromeReferencePoint?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`InfrastructurePoint`](https://airm.aero/developers/advanced-search/1.3.0/InfrastructurePoint?model=ConceptualModel)  [`InfrastructurePointUsage`](https://airm.aero/developers/advanced-search/1.3.0/InfrastructurePointUsage?model=ConceptualModel)  [`LandingThresholdPoint`](https://airm.aero/developers/advanced-search/1.3.0/LandingThresholdPoint?model=ConceptualModel)  

![Image](.//media/cm/Movement-FF-ICE/R1-Trajectory-point-properties-Use-of-the-aerodrome-infrastructure.png)

###  Aircraft Perspective - Aircraft Intent

This diagram describes the ICAO concept of Aircraft Intent.

Key concepts: [`TrajectorySynchronisation`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySynchronisation?model=ConceptualModel)  [`FlightIntent`](https://airm.aero/developers/advanced-search/1.3.0/FlightIntent?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`AircraftIntent`](https://airm.aero/developers/advanced-search/1.3.0/AircraftIntent?model=ConceptualModel)  

![Image](.//media/cm/Movement-Aircraft-Perspective-Aircraft-Intent.png)

###  ICAO Flight Intent

This diagram describes the ICAO concept of Flight Intent which is a representation of the movement of the aircraft computed by the FMS.

Key concepts: [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`AircraftIntent`](https://airm.aero/developers/advanced-search/1.3.0/AircraftIntent?model=ConceptualModel)  [`FlightIntent`](https://airm.aero/developers/advanced-search/1.3.0/FlightIntent?model=ConceptualModel)  

![Image](.//media/cm/Movement-ICAO-Flight-Intent.png)

###  Lateral Constraint

This diagram describes the concept of Lateral Constraint and the required flight events.

Key concepts: [`EnRouteHolding`](https://airm.aero/developers/advanced-search/1.3.0/EnRouteHolding?model=ConceptualModel)  [`ApproachHolding`](https://airm.aero/developers/advanced-search/1.3.0/ApproachHolding?model=ConceptualModel)  [`LateralConstraint`](https://airm.aero/developers/advanced-search/1.3.0/LateralConstraint?model=ConceptualModel)  [`OverPoint`](https://airm.aero/developers/advanced-search/1.3.0/OverPoint?model=ConceptualModel)  

![Image](.//media/cm/Movement-Lateral-Constraint.png)

###  Speed Constraint

This diagram describes the concept of Speed Constraint and the required flight events.

Key concepts: [`SpeedChange`](https://airm.aero/developers/advanced-search/1.3.0/SpeedChange?model=ConceptualModel)  [`OverPoint`](https://airm.aero/developers/advanced-search/1.3.0/OverPoint?model=ConceptualModel)  [`FlightRulesChange`](https://airm.aero/developers/advanced-search/1.3.0/FlightRulesChange?model=ConceptualModel)  [`SpeedConstraint`](https://airm.aero/developers/advanced-search/1.3.0/SpeedConstraint?model=ConceptualModel)  

![Image](.//media/cm/Movement-Speed-Constraint.png)

###  Surface Routing

An overview of the surface parts of a trajectory and its representation in geometrical form used by avionic systems.

Key concepts: [`TrajectorySegment`](https://airm.aero/developers/advanced-search/1.3.0/TrajectorySegment?model=ConceptualModel)  [`AerodromeSurfaceRoutingNetwork`](https://airm.aero/developers/advanced-search/1.3.0/AerodromeSurfaceRoutingNetwork?model=ConceptualModel)  [`Taxiway`](https://airm.aero/developers/advanced-search/1.3.0/Taxiway?model=ConceptualModel)  [`DepartureSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/DepartureSurfaceSegment?model=ConceptualModel)  [`ArrivalSurfaceSegment`](https://airm.aero/developers/advanced-search/1.3.0/ArrivalSurfaceSegment?model=ConceptualModel)  [`GeometricalTaxiRoute`](https://airm.aero/developers/advanced-search/1.3.0/GeometricalTaxiRoute?model=ConceptualModel)  [`AircraftStand`](https://airm.aero/developers/advanced-search/1.3.0/AircraftStand?model=ConceptualModel)  [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  

![Image](.//media/cm/Movement-Surface-Routing.png)

###  Time Constraint

This diagram describes the concept of Time Constraint and the required flight events.

Key concepts: [`OffBlock`](https://airm.aero/developers/advanced-search/1.3.0/OffBlock?model=ConceptualModel)  [`OverPoint`](https://airm.aero/developers/advanced-search/1.3.0/OverPoint?model=ConceptualModel)  [`TimeConstraint`](https://airm.aero/developers/advanced-search/1.3.0/TimeConstraint?model=ConceptualModel)  

![Image](.//media/cm/Movement-Time-Constraint.png)

###  Track

This diagram describes the ICAO concept of Track.

Key concepts: [`4DTrajectory`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectory?model=ConceptualModel)  [`Track`](https://airm.aero/developers/advanced-search/1.3.0/Track?model=ConceptualModel)  

![Image](.//media/cm/Movement-Track.png)

###  Vertical Constraint

This diagram describes the concept of Vertical Constraint and the required flight events.

Key concepts: [`OverPoint`](https://airm.aero/developers/advanced-search/1.3.0/OverPoint?model=ConceptualModel)  [`LevelChange`](https://airm.aero/developers/advanced-search/1.3.0/LevelChange?model=ConceptualModel)  [`VerticalConstraint`](https://airm.aero/developers/advanced-search/1.3.0/VerticalConstraint?model=ConceptualModel)  

![Image](.//media/cm/Movement-Vertical-Constraint.png)

###  Usage of Infrastructure

An overview of how the trajectory and its constituents use elements of the airspace infrastructure.

Key concepts: [`ATSRoute`](https://airm.aero/developers/advanced-search/1.3.0/ATSRoute?model=ConceptualModel)  [`4DTrajectoryPoint`](https://airm.aero/developers/advanced-search/1.3.0/4DTrajectoryPoint?model=ConceptualModel)  [`InfrastructurePointUsage`](https://airm.aero/developers/advanced-search/1.3.0/InfrastructurePointUsage?model=ConceptualModel)  [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryGroup?model=ConceptualModel)  [`SegmentPoint`](https://airm.aero/developers/advanced-search/1.3.0/SegmentPoint?model=ConceptualModel)  [`TerminalProcedure`](https://airm.aero/developers/advanced-search/1.3.0/TerminalProcedure?model=ConceptualModel)  [`AerodromeReferencePoint`](https://airm.aero/developers/advanced-search/1.3.0/AerodromeReferencePoint?model=ConceptualModel)  [`RouteTrajectoryElement`](https://airm.aero/developers/advanced-search/1.3.0/RouteTrajectoryElement?model=ConceptualModel)  [`InfrastructurePoint`](https://airm.aero/developers/advanced-search/1.3.0/InfrastructurePoint?model=ConceptualModel)  [`RoutePoint`](https://airm.aero/developers/advanced-search/1.3.0/RoutePoint?model=ConceptualModel)  

![Image](.//media/cm/Movement-Usage-of-Infrastructure.png)

