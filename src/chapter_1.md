# Chapter 1
```plantuml
@startuml
[*] --> Init
Init --> ReadSensors
ReadSensors --> UpdateGVL
UpdateGVL --> ReadSensors : Loop
@enduml

```