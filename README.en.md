# Quantum Breach: Combat・量子突破：战斗模式

> Single-file HTML5 bullet-heaven survival shooter · Zero dependencies · Open and play

Weave between quantum dimensions, detonate phase marks across the entire enemy swarm, and push ever closer to the cross-dimensional BOSS with every upgrade.



***

## Overview

A top-down arena shooter. Weave between the α / β quantum dimensions while dodging bullets, stack **phase marks** on enemies, then detonate them all at once to clear the field.



* **Dimension mechanic**: Press `Space` to switch dimensions and detonate all marks. Detonation clears nearby enemy bullets, grants brief invincibility, and triggers a **2-second fire overload** after the switch. Enemies in other dimensions are visible but can't be hit directly — the BOSS, however, exists in every dimension.

* **Growth loop**: Kill enemies → earn XP → level up → pick one of three permanent upgrades. Each level-up restores 15 HP and grants a short shield.

* **BOSS fights**: Face a cross-dimensional BOSS every 5 levels, with difficulty scaling each time.

## Controls



| Key               | Action                              |
| ----------------- | ----------------------------------- |
| `WASD`            | Move                                |
| Mouse             | Aim                                 |
| Left mouse (hold) | Shoot (stack phase marks)           |
| `Space`           | Switch dimension / detonate marks   |
| `X`               | Phase dash                          |
| `E`               | Dimension nova (unlock via upgrade) |
| `Esc`             | Pause                               |

## Upgrades

On level-up, choose one permanent upgrade from three random options:



| Skill           | Effect                                                    |
| --------------- | --------------------------------------------------------- |
| Firepower       | Base damage +35%                                          |
| Overload        | Faster fire rate (minimum 4 frames)                       |
| Massive Shells  | Projectile radius +3, base damage +12%                    |
| Phase Drive     | Reduced dash cooldown                                     |
| Pulse Resonance | Higher detonation damage, pulse radius +30                |
| Fission Scatter | +2 scatter shots per level, up to 6                       |
| Dimension Nova  | Unlock / enhance E-key cross-dimensional AoE, 6s cooldown |


## Tech Notes



* Pure vanilla HTML5 Canvas + JS — no frameworks, no build step, no external assets

* Fixed-timestep (60 FPS) game loop, scales to window size

* Cyberpunk glitch UI, cyan α / magenta β dimension color coding
