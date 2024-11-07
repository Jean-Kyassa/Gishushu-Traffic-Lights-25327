# Gishushu-Traffic-Lights-25327
The Gishushu Traffic Lights State Machine is designed to manage the flow of traffic at the Gishushu intersection, ensuring safety and efficiency for both vehicles and pedestrians. The system operates through a series of states that control the traffic lights in different directions.

State Diagram
The state diagram for the Gishushu Traffic Lights includes the following states:

North-South Green Phase:
Vehicles travel north-south.
Pedestrians cross east-west.
North-South Yellow Phase:
North-south traffic prepares to stop.
Pedestrians prepare to stop.
East-West Green Phase:
Vehicles travel east-west.
Pedestrians cross north-south.
East-West Yellow Phase:
East-west traffic prepares to stop.
Pedestrians prepare to stop.
All Red Phase:
All directions are red to clear the intersection before the next green phase.
Specification (Narration)
The Gishushu Traffic Lights system operates in a cyclical manner through the following primary states:

Green Light:
North-South Green Phase: Vehicles are allowed to move in the north-south direction while pedestrians can cross east-west.
East-West Green Phase: Vehicles are allowed to move in the east-west direction while pedestrians can cross north-south.
Yellow Light:
North-South Yellow Phase: Vehicles in the north-south direction prepare to stop, and pedestrians prepare to stop crossing east-west.
East-West Yellow Phase: Vehicles in the east-west direction prepare to stop, and pedestrians prepare to stop crossing north-south.
Red Light:
All Red Phase: All traffic lights are red to ensure the intersection is clear before switching to the next green phase.
The system ensures that only one direction has a green light at any given time to prevent accidents and ensure smooth traffic flow. Each green phase is followed by a yellow phase to alert drivers to prepare to stop, and an all-red phase occurs briefly between each green light phase to clear the intersection.
