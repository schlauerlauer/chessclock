# chessclock

A clock for timing chess games.
With integrated time over WiFi and alarm clock.

## Features

- Show current time (over WiFi with NTP)
- Set chess game time
- Set alarm time
- ...

## How to

```mermaid
graph TD
    A[Clock] -->|Single| B(Switch Player)
    A -->|Double| C[Chess playing]
    C -->|Single| B
    C -->|Double| D[Paused]
    D -->|Double| C
```