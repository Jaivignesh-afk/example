# Database Design
```mermaid
flowchart TD
subgraph ETA
A[Feeder] <--ETA--> C{Middleware}
C <--Save--> B[(Database)]
end
```

```mermaid
flowchart LR
subgraph Middleware
A[Feeder] <--> B((Google Map API))
B <--> D{Algorithm}
B -- Route Details --> C[(Database - User)]
end
```
```mermaid
 flowchart LR
 subgraph 
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1Mzk2ODAyNzIsMTY2MzA1ODQyMCwxNz
I2NzA5NzY3XX0=
-->