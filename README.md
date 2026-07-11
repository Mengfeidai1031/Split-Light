<div align="center">

# Split Light

### An Escape-Room game where two linked characters race the clock across themed planets

![Godot](https://img.shields.io/badge/Godot-4.4-478cbf?logo=godotengine&logoColor=white)
![GDScript](https://img.shields.io/badge/language-GDScript-355570)
![Multiplayer](https://img.shields.io/badge/multiplayer-client--server-6aa84f)
[![Contributors](https://img.shields.io/badge/contributors-6-orange)](https://github.com/Mengfeidai1031/Split-Light/graphs/contributors)

<img src="https://raw.githubusercontent.com/SkinnyDevi/Split-Light-Metadata/refs/heads/master/Icons/SplashScreen.png" alt="Split Light splash screen" width="600">

</div>

## Table of Contents

- [Description](#description)
- [Screenshots](#screenshots)
- [Gameplay Preview](#gameplay-preview)
- [Behind the Scenes](#behind-the-scenes)
- [Controls](#controls)
- [Multiplayer](#multiplayer)
- [Design Boards](#design-boards)
- [Project Board](#project-board)
- [Tech Stack](#tech-stack)
- [Developers](#developers)
- [Acknowledgements](#acknowledgements)

## Description

Split Light is an Escape Room-style game in which two players possess unique
characteristics that are key to solving challenging puzzles within a maximum
time limit.

Navigate the Split Light universe, jumping between diverse planets with unique
themes alongside creative, challenging puzzles that require thinking outside
the box.

## Screenshots

<table>
<tr>
<td align="center" width="33%">
<img src="docs/readme/screenshots/controls-menu.png" width="280"><br>
<sub>Controls menu</sub>
</td>
<td align="center" width="33%">
<img src="docs/readme/screenshots/level-complete.png" width="280"><br>
<sub>Level completed screen</sub>
</td>
<td align="center" width="33%">
<img src="docs/readme/screenshots/multiplayer-connect.png" width="280"><br>
<sub>Connecting to a co-op session</sub>
</td>
</tr>
</table>

## Gameplay Preview

📹 [Watch a short gameplay clip](docs/readme/video/gameplay-demo.mov) *(~10 MB,
opens in GitHub's file viewer)*

## Behind the Scenes

A look at how the game's art and systems came together during development.

<table>
<tr>
<td align="center" width="50%">
<img src="docs/readme/dev-process/map-design-top.png" width="420"><br>
<sub>Map design — surface biome, inspired by California redwoods, Hawaiian
tikis and Easter Island moai</sub>
</td>
<td align="center" width="50%">
<img src="docs/readme/dev-process/map-design-bottom.png" width="420"><br>
<sub>Map design — underground biome, inspired by Mexican cave crystals and
water lilies</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="docs/readme/dev-process/spritesheets.png" width="420"><br>
<sub>Generated spritesheets for both playable characters</sub>
</td>
<td align="center" width="50%">
<img src="docs/readme/dev-process/multiplayer-architecture.png" width="420"><br>
<sub>Multiplayer client-server architecture and connection flow</sub>
</td>
</tr>
</table>

## Controls

<img src="docs/readme/screenshots/controls-menu.png" width="450" align="right">

| Action | Key |
| --- | --- |
| Move left / right | `Left` / `Right` arrow |
| Jump | `W` |
| Switch player | `Tab` |
| Interact | `E` |
| Take / Drop item | `F` / `Q` |
| Inventory slots 1-3 | `1` `2` `3` |
| Reset timer | `R` |
| Pause | `Escape` |

All bindings above are remappable in-game from the Controls menu.

<br clear="right">

## Multiplayer

Split Light supports co-op play over a **client-server** network
architecture: one player hosts the session and the other joins with the
host's IP and port.

Since the game isn't hosted on dedicated servers, playing with a friend
remotely requires one of:

- A virtual LAN tool such as [Hamachi](https://vpn.net/), or
- Manually forwarding a port on the host's router (default port `49359`,
  range `49152`-`65535`)

## Design Boards

[![Figma](https://img.shields.io/badge/Figma-View%20designs-F24E1E?logo=figma&logoColor=white)](https://www.figma.com/design/VT0UKK87N6LZgI05aA2SI9/Vistas---Split-Light?node-id=0-1&t=OkTcRE2eOXmAB1ab-1)

All designs and mockups made so far, from complete screens to individual
elements.

## Project Board

[![Trello](https://img.shields.io/badge/Trello-Project%20board-0052CC?logo=trello&logoColor=white)](https://trello.com/b/3kcMWzsV/split-light)

The complete task log to date, with all pending features to develop, those in
progress, and those ready for production.

## Tech Stack

This project is built with [Godot 4.4](https://godotengine.org/), a game
engine with extensive capabilities for 2D games and broad support for 3D.

Godot has its own programming language (GDScript), which is easy to learn,
with a low learning curve, and capable of providing a fast workflow in a short
time.

## Developers

- Meng Fei Dai
- Félix Miguel Velásquez
- Daniel Gutiérrez Recio
- Mario García Abellán
- Juan Carlos Rodríguez Ramírez
- Ian Samuel Trujillo Gil

## Acknowledgements

- Planet Generation: [PixelPlanets](https://deep-fold.itch.io/pixel-planet-generator)
- Godot Game Engine: [Godot](https://godotengine.org/)
- Isometric TileSets: [Isometric TileSets](https://scrabling.itch.io/pixel-isometric-tiles)
