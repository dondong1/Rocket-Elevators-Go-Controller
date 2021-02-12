## 🏢Commercial Controller Go - Commercial_Controller.go
* You can run the code with at the terminal of your preference by typing: **go run Commercial_Controller.go**

    Note that you have to be in the script folder for it to run correctly.

Testing: Commercial_Controller
Uncomment by removing // at the scenario1, scenario2, scenario3, scnenario4 to run the testing. 

SUMMARY:
1- type Battery
    a- Access: public, type name: Battery, instance variables, constructor declaration of type.
    b= 
    c- Methods to create a list: createColumnsList
    d- Methods for logic: calculateamountOfFloorsPerColumn, setColumnValues, initializeBasementColumnFloors, initializeMultiColumnFloors, initializeUniqueColumnFloors
    
    
2- type Column
    a- Access: public, type name: Column, instance variables, constructor declaration of type.
    b= 
    c- Methods to create a list: createElevatorsList, createButtonsUpList, createButtonsDownList
    d- Methods for logic: findElevator, findNearestElevator, manageButtonStatusOn
    e. Entry method: requestElevator
3- type Elevator
    a- Access: public, type name: Column, instance variables, constructor declaration of type.
    b= 
    c- Methods to create a list: createFloorDoorsList, createDisplaysList, createfloorRequestButtonsList
    d- Methods for logic: moveElevator, moveUp, moveDown, manageButtonStatusOff, updateDisplays, openDoors, closeDoors, checkWeight, checkObstruction, addFloorTofloorRequestList, deleteFloorFromList
    e. Entry method: requestFloor
4- type Door
5- type Display
6- ENUMS: special type represents a group of constants 



