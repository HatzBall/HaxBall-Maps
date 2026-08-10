# HaxBall Maps Collection

A curated collection of custom and competitive HaxBall stadium map files (`.hbs`).

All raw map files are stored in the [`/Maps`](./Maps) directory and are ready to be fetched dynamically by HaxBall headless server bots.

---

## Raw Access URL Pattern

You can fetch any raw map directly via GitHub raw content URL:

```
https://raw.githubusercontent.com/raresmac/HaxBall-Maps/refs/heads/main/Maps/{filename}
```

---

## Maps Directory, Bot Commands & HaxMaps Links

### Futsal Maps
| Map File | Bot Commands | HaxMaps Link |
| :--- | :--- | :--- |
| `futsal_1x1_2x2.hbs` | `!futsal1x1`, `!f1` | [HaxMaps](https://haxmaps.com/map/4545) |
| `futsal_3x3.hbs` | `!futsal3x3`, `!f3` | custom edited |
| `futsal_4x4.hbs` | `!futsal4x4`, `!f4` | [HaxMaps](https://haxmaps.com/map/4544) |

### KafaTopu Maps
| Map File | Bot Commands | HaxMaps Link |
| :--- | :--- | :--- |
| `KafaTopu0.hbs` | `!kafatopu`, `!kt`, `!kt0`, `!kafatopu0` | [HaxMaps](https://haxmaps.com/map/10180) |
| `KafaTopu1.hbs` – `KafaTopu10.hbs` | `!kt1` – `!kt10`, `!kafatopu1` – `!kafatopu10` | custom edited |
| *Random Choice* | `!kafatopu_r`, `!ktr` | — |

### SpaceBounce Maps
| Map File | Bot Commands | HaxMaps Link |
| :--- | :--- | :--- |
| `SpaceBounce.hbs` | `!spacebounce`, `!spb` | [HaxMaps](https://haxmaps.com/map/1) |
| `SpaceBounceV2.hbs` | `!spacebounce_v2`, `!spb2` | [HaxMaps](https://haxmaps.com/map/809) |

### Minigames & Fun Maps
| Map File | Bot Commands | HaxMaps Link |
| :--- | :--- | :--- |
| `8BallPool.hbs` | `!ballpool`, `!bp` | [HaxMaps](https://haxmaps.com/map/6240) |
| `AirHockey.hbs` | `!airhockey`, `!ah` | [HaxMaps](https://haxmaps.com/map/12439) |
| `Basketball.hbs` | `!basketball`, `!bball`, `!bb` | [HaxMaps](https://haxmaps.com/map/12878) |
| `Bowling.hbs` | `!bowling`, `!bowl` | [HaxMaps](https://haxmaps.com/map/34) |
| `Dodgeball.hbs` | `!dodgeball`, `!db` | [HaxMaps](https://haxmaps.com/map/12644) |
| `Fencing.hbs` | `!fencing`, `!fen` | [HaxMaps](https://haxmaps.com/map/11407) |
| `HaxRoulette.hbs` | `!haxroulette`, `!hr` | (?) |
| `Training.hbs` | `!training` | [HaxMaps](https://haxmaps.com/map/1770) |

### 🏟️ Built-in HaxBall Stadiums
| Stadium | Bot Command |
| :--- | :--- |
| Classic | `!classic` |
| Big | `!big` |

---

## 🛠️ Usage with your custom server

To load any map in your server bot, the recommended use is:
* The command shortcut: e.g. `!kt1`, `!f1`, `!spb2`, `!bp`
* The generic map command: `!map <filename>` (e.g. `!map futsal_1x1_2x2`)
