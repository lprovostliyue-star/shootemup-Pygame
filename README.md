# 👾 Shoot 'em Up 

<br>

<img width="2560" height="1440" alt="Menu Screen" src="https://github.com/user-attachments/assets/9fcf35c6-c23c-4212-9f83-d8f610e50c7a" />

## ✨ Key Features & Engine Mechanics

The codebase is highly modularized, containing several advanced mechanics built from scratch:

- **Custom State Machine:** Seamless transitions between `Menu`, `Game`, `Pause`, `Options`, and `GameOver` without overlapping logic.
- **Particle Physics System:** Independent modules for environmental effects (`Fall` for rain/stars), combat impacts (`Spark`), and multi-layered CRT-style `Explosion` generators.
- **Dynamic Wave Manager:** The `FormationManager` autonomously handles enemy spawn patterns (V-Shape, Diagonal, Circle Clusters) based on the escalating level difficulty.
- **Asset Manager:** A centralized cache for sprites, sounds, and `.ttf` fonts, including real-time mathematical generation of neon glow surfaces.
- **Entity Scaling:** Automatic internal resolution handling and full-screen toggling.

---

## 🎮 Controls


| Action              | Keyboard                            | Controller      |
| :------------------ | :---------------------------------- | :-------------- |
| **Move**            | `W` `A` `S` `D` or `Arrow Keys`     | `D-Pad`         |
| **Shoot**           | `Space`                             | `Right Trigger` |
| **Menu Navigation** | `Up` / `Down` and `Enter` / `Space` | `D-Pad` and `A` |
| **Pause / Back**    | `ESC`                               | `Start` / `B`   |

