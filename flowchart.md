```mermaid
graph TB
    start([START]) --> robot[GET robots.txt]
    robot --> info[PRINT allowed links]
    info --> sleep[SET crawler delay]
    sleep --> To-Do


```