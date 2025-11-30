# Chapter 1
@startuml
[*] --> Initial state
Initial state --> CheckConditions
CheckConditions --> Watering : Need Water
CheckConditions --> Idle : No Need
Watering --> Idle : Timer Done
Idle --> CheckConditions : Cycle
@enduml