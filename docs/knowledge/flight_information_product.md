# FlightInformationProduct

## Overview


Key concepts: [`CoordinationMessage`](https://airm.aero/developers/advanced-search/1.2.0/CoordinationMessage?model=ConceptualModel)  [`EmergencyMessage`](https://airm.aero/developers/advanced-search/1.2.0/EmergencyMessage?model=ConceptualModel)  [`MovementMessage`](https://airm.aero/developers/advanced-search/1.2.0/MovementMessage?model=ConceptualModel)  [`FiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlan?model=ConceptualModel)  [`ChangeMessage`](https://airm.aero/developers/advanced-search/1.2.0/ChangeMessage?model=ConceptualModel)  [`CancellationMessage`](https://airm.aero/developers/advanced-search/1.2.0/CancellationMessage?model=ConceptualModel)  [`DelayMessage`](https://airm.aero/developers/advanced-search/1.2.0/DelayMessage?model=ConceptualModel)  [`DepartureMessage`](https://airm.aero/developers/advanced-search/1.2.0/DepartureMessage?model=ConceptualModel)  [`ArrivalMessage`](https://airm.aero/developers/advanced-search/1.2.0/ArrivalMessage?model=ConceptualModel)  [`AlertMessage`](https://airm.aero/developers/advanced-search/1.2.0/AlertMessage?model=ConceptualModel)  [`RadioCommunicationFailureMessage`](https://airm.aero/developers/advanced-search/1.2.0/RadioCommunicationFailureMessage?model=ConceptualModel)  [`CurrentFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/CurrentFlightPlan?model=ConceptualModel)  [`AcceptanceMessage`](https://airm.aero/developers/advanced-search/1.2.0/AcceptanceMessage?model=ConceptualModel)  [`CDNMessage`](https://airm.aero/developers/advanced-search/1.2.0/CDNMessage?model=ConceptualModel)  [`FlightArrivalMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightArrivalMessage?model=ConceptualModel)  [`FlightDepartureMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightDepartureMessage?model=ConceptualModel)  [`FlightCancellationMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightCancellationMessage?model=ConceptualModel)  [`CoordinationAndTransfer`](https://airm.aero/developers/advanced-search/1.2.0/CoordinationAndTransfer?model=ConceptualModel)  [`FlightPlanUpdateMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightPlanUpdateMessage?model=ConceptualModel)  [`FiledFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlanMessage?model=ConceptualModel)  [`FficeFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FficeFlightPlan?model=ConceptualModel)  [`StandardFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/StandardFlightPlan?model=ConceptualModel)  [`EmergencyPhase`](https://airm.aero/developers/advanced-search/1.2.0/EmergencyPhase?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct.png)

## Taxonomies

###  Emergency Messages

Key concepts: [`FreeTextEmergencyMessage`](https://airm.aero/developers/advanced-search/1.2.0/FreeTextEmergencyMessage?model=ConceptualModel)  [`RadioCommunicationFailureMessage`](https://airm.aero/developers/advanced-search/1.2.0/RadioCommunicationFailureMessage?model=ConceptualModel)  [`AlertMessage`](https://airm.aero/developers/advanced-search/1.2.0/AlertMessage?model=ConceptualModel)  [`EmergencyMessage`](https://airm.aero/developers/advanced-search/1.2.0/EmergencyMessage?model=ConceptualModel)  


![Image](.//media/cm/FlightInformationProduct-Hierarchy-Emergency-Messages.png)

## Analysis

###  Hierarchy - Movement and Coordination Messages

This diagram describes the taxonomy of the messages defined in PANS-ATM.

Key concepts: [`LogicalAcknowledgementMessage`](https://airm.aero/developers/advanced-search/1.2.0/LogicalAcknowledgementMessage?model=ConceptualModel)  [`AcceptanceMessage`](https://airm.aero/developers/advanced-search/1.2.0/AcceptanceMessage?model=ConceptualModel)  [`CDNMessage`](https://airm.aero/developers/advanced-search/1.2.0/CDNMessage?model=ConceptualModel)  [`EstimateMessage`](https://airm.aero/developers/advanced-search/1.2.0/EstimateMessage?model=ConceptualModel)  [`CurrentFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/CurrentFlightPlan?model=ConceptualModel)  [`CoordinationMessage`](https://airm.aero/developers/advanced-search/1.2.0/CoordinationMessage?model=ConceptualModel)  [`ArrivalMessage`](https://airm.aero/developers/advanced-search/1.2.0/ArrivalMessage?model=ConceptualModel)  [`DepartureMessage`](https://airm.aero/developers/advanced-search/1.2.0/DepartureMessage?model=ConceptualModel)  [`CancellationMessage`](https://airm.aero/developers/advanced-search/1.2.0/CancellationMessage?model=ConceptualModel)  [`ChangeMessage`](https://airm.aero/developers/advanced-search/1.2.0/ChangeMessage?model=ConceptualModel)  [`DelayMessage`](https://airm.aero/developers/advanced-search/1.2.0/DelayMessage?model=ConceptualModel)  [`MovementMessage`](https://airm.aero/developers/advanced-search/1.2.0/MovementMessage?model=ConceptualModel)  [`FiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlan?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-Hierarchy-Movement-and-Coordination-Messages.png)

###  Coordination Messages - Communication 

The diagram describes the pattern of ATC - ATC coordination information exchanges using messaging.

Key concepts: [`ReceivingUnitOrController`](https://airm.aero/developers/advanced-search/1.2.0/ReceivingUnitOrController?model=ConceptualModel)  [`AcceptingUnitOrController`](https://airm.aero/developers/advanced-search/1.2.0/AcceptingUnitOrController?model=ConceptualModel)  [`SendingUnitOrController`](https://airm.aero/developers/advanced-search/1.2.0/SendingUnitOrController?model=ConceptualModel)  [`TransferringUnitOrController`](https://airm.aero/developers/advanced-search/1.2.0/TransferringUnitOrController?model=ConceptualModel)  [`CoordinationMessage`](https://airm.aero/developers/advanced-search/1.2.0/CoordinationMessage?model=ConceptualModel)  [`CoordinationAndTransfer`](https://airm.aero/developers/advanced-search/1.2.0/CoordinationAndTransfer?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-Coordination-Messages-Communication-.png)

###  FF-ICE/R1 Messages

The diagram provides an overview of FF-ICE Messages exchanged by the FF-ICE Services.

Key concepts: [`FilingService`](https://airm.aero/developers/advanced-search/1.2.0/FilingService?model=ConceptualModel)  [`PlanningService`](https://airm.aero/developers/advanced-search/1.2.0/PlanningService?model=ConceptualModel)  [`TrialService`](https://airm.aero/developers/advanced-search/1.2.0/TrialService?model=ConceptualModel)  [`FiledFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlanMessage?model=ConceptualModel)  [`FlightDataRequestService`](https://airm.aero/developers/advanced-search/1.2.0/FlightDataRequestService?model=ConceptualModel)  [`PublicationService`](https://airm.aero/developers/advanced-search/1.2.0/PublicationService?model=ConceptualModel)  [`NotificationService`](https://airm.aero/developers/advanced-search/1.2.0/NotificationService?model=ConceptualModel)  [`PreliminaryFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/PreliminaryFlightPlanMessage?model=ConceptualModel)  [`FlightPlanUpdateMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightPlanUpdateMessage?model=ConceptualModel)  [`FlightCancellationMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightCancellationMessage?model=ConceptualModel)  [`SubmissionResponseMessage`](https://airm.aero/developers/advanced-search/1.2.0/SubmissionResponseMessage?model=ConceptualModel)  [`PlanningStatusMessage`](https://airm.aero/developers/advanced-search/1.2.0/PlanningStatusMessage?model=ConceptualModel)  [`FilingStatusMessage`](https://airm.aero/developers/advanced-search/1.2.0/FilingStatusMessage?model=ConceptualModel)  [`TrialRequestMessage`](https://airm.aero/developers/advanced-search/1.2.0/TrialRequestMessage?model=ConceptualModel)  [`TrialResponseMessage`](https://airm.aero/developers/advanced-search/1.2.0/TrialResponseMessage?model=ConceptualModel)  [`FlightDataRequestMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightDataRequestMessage?model=ConceptualModel)  [`FlightDataResponseMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightDataResponseMessage?model=ConceptualModel)  [`FlightDepartureMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightDepartureMessage?model=ConceptualModel)  [`FlightArrivalMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightArrivalMessage?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-FF-ICE-R1-Messages.png)

###  FF-ICE/R1 Messages - RouteTrajectory Content

This diagram explains how the different RouteTrajectory groups are exchanged in the FF-ICE/R1 messages.

Key concepts: [`TrialRequestMessage`](https://airm.aero/developers/advanced-search/1.2.0/TrialRequestMessage?model=ConceptualModel)  [`PreliminaryFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/PreliminaryFlightPlanMessage?model=ConceptualModel)  [`TrialResponseMessage`](https://airm.aero/developers/advanced-search/1.2.0/TrialResponseMessage?model=ConceptualModel)  [`DesiredRouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.2.0/DesiredRouteTrajectoryGroup?model=ConceptualModel)  [`FiledFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlanMessage?model=ConceptualModel)  [`AgreedRouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.2.0/AgreedRouteTrajectoryGroup?model=ConceptualModel)  [`NegotiatingRouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.2.0/NegotiatingRouteTrajectoryGroup?model=ConceptualModel)  [`PlanningStatusMessage`](https://airm.aero/developers/advanced-search/1.2.0/PlanningStatusMessage?model=ConceptualModel)  [`FilingStatusMessage`](https://airm.aero/developers/advanced-search/1.2.0/FilingStatusMessage?model=ConceptualModel)  [`RouteTrajectoryGroup`](https://airm.aero/developers/advanced-search/1.2.0/RouteTrajectoryGroup?model=ConceptualModel)  [`FlightPlanUpdateMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightPlanUpdateMessage?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-FF-ICE-R1-Messages-RouteTrajectory-Content.png)

###  Flight Plan - Message view


Key concepts: [`StandardFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/StandardFlightPlan?model=ConceptualModel)  [`FficeFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FficeFlightPlan?model=ConceptualModel)  [`FlightDataRequestService`](https://airm.aero/developers/advanced-search/1.2.0/FlightDataRequestService?model=ConceptualModel)  [`FlightDataResponseMessage`](https://airm.aero/developers/advanced-search/1.2.0/FlightDataResponseMessage?model=ConceptualModel)  [`TrialService`](https://airm.aero/developers/advanced-search/1.2.0/TrialService?model=ConceptualModel)  [`FilingService`](https://airm.aero/developers/advanced-search/1.2.0/FilingService?model=ConceptualModel)  [`TrialRequestMessage`](https://airm.aero/developers/advanced-search/1.2.0/TrialRequestMessage?model=ConceptualModel)  [`PlanningService`](https://airm.aero/developers/advanced-search/1.2.0/PlanningService?model=ConceptualModel)  [`FiledFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlanMessage?model=ConceptualModel)  [`PreliminaryFlightPlanMessage`](https://airm.aero/developers/advanced-search/1.2.0/PreliminaryFlightPlanMessage?model=ConceptualModel)  [`FiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlan?model=ConceptualModel)  [`AirFiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/AirFiledFlightPlan?model=ConceptualModel)  [`CurrentFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/CurrentFlightPlan?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-Flight-Plan-Message-view.png)

###  Filed Flight Plan - Communication

The diagram describes the Flight Plan filing roles and artefacts.

Key concepts: [`AirTrafficServicesReportingOffice`](https://airm.aero/developers/advanced-search/1.2.0/AirTrafficServicesReportingOffice?model=ConceptualModel)  [`AirTrafficServicesUnit`](https://airm.aero/developers/advanced-search/1.2.0/AirTrafficServicesUnit?model=ConceptualModel)  [`Operator`](https://airm.aero/developers/advanced-search/1.2.0/Operator?model=ConceptualModel)  [`FlightOperationsOfficerOrFlightDispatcher`](https://airm.aero/developers/advanced-search/1.2.0/FlightOperationsOfficerOrFlightDispatcher?model=ConceptualModel)  [`PilotInCommand`](https://airm.aero/developers/advanced-search/1.2.0/PilotInCommand?model=ConceptualModel)  [`Flight`](https://airm.aero/developers/advanced-search/1.2.0/Flight?model=ConceptualModel)  [`AirFiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/AirFiledFlightPlan?model=ConceptualModel)  [`FlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FlightPlan?model=ConceptualModel)  [`FiledFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/FiledFlightPlan?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-Filed-Flight-Plan-Communication.png)

###  Current Flight Plan

An overview of the current flight plan.

Key concepts: [`FlightDeck`](https://airm.aero/developers/advanced-search/1.2.0/FlightDeck?model=ConceptualModel)  [`RatedAirTrafficController`](https://airm.aero/developers/advanced-search/1.2.0/RatedAirTrafficController?model=ConceptualModel)  [`CurrentFlightPlan`](https://airm.aero/developers/advanced-search/1.2.0/CurrentFlightPlan?model=ConceptualModel)  

![Image](.//media/cm/FlightInformationProduct-Current-Flight-Plan.png)

