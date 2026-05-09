# PUBG-UNREAL

An Unreal Engine 4 battle royale prototype focused on gameplay systems built with Blueprints and C++.

## Overview

This project recreates core PUBG-style mechanics in UE4, with an emphasis on character movement, item interaction, inventory management, and weapon handling. It is currently a single-player prototype and does not include multiplayer support.

Engine version: `UE 4.26.2`  
Project start: `May 2021`

## Features

- Three locomotion states: stand, crouch, and prone
- Speed changes for walking and running
- Loot pickup and interaction flow
- Equipment system for helmets, vests, and backpacks
- Inventory UI with drag-and-drop interactions
- Weapon switching, firing, reload, recoil, and aiming states
- First-person aiming and scope views

## Controls

| Action | Key |
| --- | --- |
| Move | `W A S D` |
| Look around | Mouse |
| Jump | `Space` |
| Crouch | `C` |
| Prone | `Z` |
| Walk | `Left Ctrl` |
| Run | `Left Shift` |
| Fire | `Left Mouse Button` |
| Open sight | `Right Mouse Button` |
| Normal aim | `Hold Right Mouse Button` |
| Reload | `R` |
| Change fire mode | `B` |
| Switch left weapon | `1` |
| Switch right weapon | `2` |
| Drop current weapon | `G` |
| Re-equip current weapon | `X` |
| Interact with item | `F` |
| Show inventory | `Tab` |
| Freelook | `Hold Left Alt` |
| Toggle map | `M` (planned) |

## Tech Stack

- Unreal Engine 4
- UE4 Blueprints
- C++

## Visuals

### Item system diagram

![Item UML diagram](https://user-images.githubusercontent.com/59629632/120907046-5319ea00-c62c-11eb-9c6e-663f3ed8eb8a.png)

### Inventory view

![Inventory UI](https://user-images.githubusercontent.com/59629632/120907225-d556de00-c62d-11eb-8831-cc69852b1bf3.png)

### Blueprint sample

![Blueprint sample](https://user-images.githubusercontent.com/59629632/120907255-09ca9a00-c62e-11eb-9fae-0875ad5c4759.png)

### Command center

![Command center](https://user-images.githubusercontent.com/59629632/120908813-54531300-c63c-11eb-9b45-fa0e40834948.png)

### Scope view

![Scope view](https://user-images.githubusercontent.com/59629632/120908816-6339c580-c63c-11eb-9d4d-f03be0eb5acf.png)

### Character pose state machine

![Locomotion state machine](https://user-images.githubusercontent.com/59629632/120908905-46ea5880-c63d-11eb-9773-c523fec6a675.png)

## Requirements

To open or extend the project, use Unreal Engine `4.26.2`. General UE4 hardware requirements apply; a quad-core CPU, dedicated GPU, and at least `8 GB` RAM are recommended for a smoother editor experience.

## Current Scope

- Single-player prototype
- Focused on gameplay systems rather than live-service features
- Multiplayer is not implemented yet

## Contributing

Contributions are welcome:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a pull request

## Contact

Zhenxiao Yu  
`zyu347@uwo.ca`

Project link: <https://github.com/zhenxiao-yu/PUBG-UNREAL>
