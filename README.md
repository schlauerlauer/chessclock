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
    A{Clock} -->|Single| B(Switch Player)
    A -->|Double| C
    C{Chess playing} -->|Single| B
    C -->|Hold 1s| A
    C -->|Double| D
    D{Paused} -->|Double| C
    D -->|Hold 1s| A
    F{From Anywhere} -->|Hold 4s| E(Toggle Alarm)
    F -->|Single| U(Stop alarm sound)
    A -->|Hold 1s| G
    G{Settings} -->|Single| H(Increase Chess time)
    G -->|Double| I{Set alarm time}
    I -->|Hold| K(Increase alarm time)
    I -->|Double| G
    G -->|Hold 1s| A
```

## Images

### Finished Version

![finished version](images/3.jpg)

### Build

![prototype 1](images/1.jpg)

> first prototype

![case](images/4.jpg)

> planning the case

![case 2](images/5.jpg)

> building the case

![build 1](images/2.jpg)

> final programming