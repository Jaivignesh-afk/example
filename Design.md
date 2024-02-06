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
 subgraph LiveTracking
 A[Seeker] --> B[]
 end
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTQxODU3ODEwLC0xNTM5NjgwMjcyLDE2Nj
MwNTg0MjAsMTcyNjcwOTc2N119
-->