# Chapter 1
```plantuml
@startuml
[*] --> Initial state
Initial state --> ReadSensors(Moisture level and temperature)
ReadSensors --> Idle
Idle --> ReadSensors : Loop
@enduml

```