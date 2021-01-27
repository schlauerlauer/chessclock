# chessclock


A clock for timing chess games.
With integrated time over WiFi and alarm clock.

## Features

- Show current time and date (over WiFi with NTP)
- Time a chessgame
- Wake up alarm
- 18650 Battery

## How to

[graph only works in gitlab](http://gitlab.com/schlauerlauer/chessclock)

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

## Media

### Finished Version

![1](media/01.jpeg)
![2](media/02.jpeg)
![3](media/03.jpeg)
![4](media/04.jpeg)

> Warning: With sound. Only works in [gitlab](https://gitlab.com/schlauerlauer/chessclock))

![countdown video](media/video.mp4)

### Build

![prototype 1](media/1.jpg)
![case](media/4.jpg)
![case 2](media/5.jpg)
![build 1](media/2.jpg)
![case 3](media/6.jpg)
![case 4](media/7.jpg)
