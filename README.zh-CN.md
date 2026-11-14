<div align="center">

# Project 1 · 树莓派反应速度游戏

**LED 信号 · 双人游戏 · 反应计时**

一个使用 Python 和 GPIO Zero 的树莓派课程项目，分阶段实现双人按键反应游戏。

[English](./README.md) · **简体中文**

</div>

[查看阶段](#stages) · [硬件与启动](#quick-start)

<a id="stages"></a>
## 项目阶段

| 阶段 | 内容 |
| --- | --- |
| [阶段 1](./Stage1.py) | 让 LED 亮起，并在固定延时后熄灭。 |
| [阶段 2](./Stage2.py) | 加入随机等待和两个按键的回调。 |
| [阶段 3](./Stage3.py) | 加入玩家姓名。存档脚本中的玩家判定逻辑仍未完成。 |
| [阶段 4](https://github.com/Whelve-Autism/Project-1-Raspberry-Pi-Reaction-Game/blob/Fan%27s-branch/Stage4.py) | 在团队分支里尝试多轮游戏、反应计时和计分。 |

<a id="quick-start"></a>
## 硬件与启动

准备树莓派、Python 3 和 `gpiozero`。脚本使用 BCM GPIO 4 驱动 LED，GPIO 14 和 15 连接两个按键。先运行阶段 1 检查 LED 接线。

```bash
python3 Stage1.py
```
