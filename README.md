<div align="center">

# Project 1 · Raspberry Pi Reaction Game

**LED signal · Two players · Reaction timing**

A Raspberry Pi coursework project that builds a two-player button game in stages with Python and GPIO Zero.

**English** · [简体中文](./README.zh-CN.md)

</div>

[Stages](#stages) · [Hardware](#quick-start)

<a id="stages"></a>
## Stages

| Stage | What it explores |
| --- | --- |
| [Stage 1](./Stage1.py) | Switch an LED on and off after a fixed delay. |
| [Stage 2](./Stage2.py) | Add a random delay and callbacks for two buttons. |
| [Stage 3](./Stage3.py) | Introduce player names. The archived script still has unfinished player-selection logic. |
| [Stage 4](https://github.com/Whelve-Autism/Project-1-Raspberry-Pi-Reaction-Game/blob/Fan%27s-branch/Stage4.py) | Prototype multiple rounds, reaction time, and scores on a team branch. |

<a id="quick-start"></a>
## Hardware and quick start

Use a Raspberry Pi with Python 3 and `gpiozero`. The scripts use BCM GPIO 4 for the LED and GPIO 14 and 15 for the two buttons. Start with Stage 1 to check the LED wiring.

```bash
python3 Stage1.py
```
