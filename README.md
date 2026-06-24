# 天穹前线 1944

一款单文件 HTML 竖版街机空战游戏。玩家可以选择不同战机，在复古街机风格的战场中推进关卡、收集补给、升级火力，并迎战多段装甲首领。

## 特性

- 单文件运行：直接打开 `index.html` 即可游玩，无需构建步骤或外部依赖。
- 多种战机：包含隼式、雷电、巨神、彗星、火神、野马，每架战机都有不同属性和专属技能。
- 多地图战场：阿登森林、珍珠港、柏林、莫斯科、斯大林格勒。
- 多难度选择：普通、困难、炼狱。
- 战役与训练：战役模式推进关卡并触发首领战，训练模式用于持续练习移动、火力、技能、炸弹和暂停升级。
- 多输入支持：键盘鼠标、手柄、触屏。
- 复古街机表现：Canvas 渲染、弹幕、补给、爆炸、震屏、音效和首领登场演出。

## 运行方式

直接在浏览器中打开：

```text
index.html
```

也可以用任意静态文件服务器托管本目录。

## 操作

键盘：

- 移动：`W` `A` `S` `D` 或方向键
- 主炮：`J`
- 副武器：`K`
- 专属技能：`L`
- 炸弹：`;`
- 暂停：`P`

手柄：

- 移动：左摇杆或方向键
- 主炮：`A`
- 副武器：`X`
- 专属技能：`Y`
- 炸弹：`B`
- 暂停：`Start`

触屏：

- 左手拖动飞机移动
- 右下角按钮控制主炮、副武、技能和炸弹

## 文件结构

```text
.
├── index.html
├── README.md
└── .gitignore
```

## 隐私与依赖

项目不包含后端服务、账号系统、远程接口、密钥或第三方资源引用。所有游戏逻辑、样式和资源绘制都位于 `index.html` 中。

---

# Skyfront 1944

A single-file vertical arcade shooter built with HTML Canvas. Choose a fighter, advance through retro-styled battlefields, collect supplies, upgrade firepower, and fight multi-part armored bosses.

## Features

- Single-file gameplay: open `index.html` directly in a browser, with no build step or external dependency.
- Multiple fighters: Falcon, Raiden, Atlas, Comet, Vulcan, and Mustang, each with distinct stats and a unique skill.
- Multiple battlefields: Ardennes Forest, Pearl Harbor, Berlin, Moscow, and Stalingrad.
- Difficulty options: Normal, Hard, and Inferno.
- Campaign and training modes: campaign mode advances stages and boss fights, while training mode lets players practice movement, weapons, skills, bombs, and pause upgrades.
- Multiple input modes: keyboard and mouse, gamepad, and touch controls.
- Retro arcade presentation: Canvas rendering, bullet patterns, pickups, explosions, screen shake, sound effects, and boss intro sequences.

## How to Run

Open this file in a browser:

```text
index.html
```

You can also host the directory with any static file server.

## Controls

Keyboard:

- Move: `W` `A` `S` `D` or arrow keys
- Main cannon: `J`
- Secondary weapon: `K`
- Unique skill: `L`
- Bomb: `;`
- Pause: `P`

Gamepad:

- Move: left stick or D-pad
- Main cannon: `A`
- Secondary weapon: `X`
- Unique skill: `Y`
- Bomb: `B`
- Pause: `Start`

Touch:

- Drag the plane with the left hand
- Use the lower-right buttons for main cannon, secondary weapon, skill, and bomb

## Project Structure

```text
.
├── index.html
├── README.md
└── .gitignore
```

## Privacy and Dependencies

The project has no backend service, account system, remote API, secrets, or third-party asset references. All game logic, styling, and rendered assets live in `index.html`.
