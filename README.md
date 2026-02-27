# PascalABC Modules by WasWolienTrinken 🎯

## 📦 Beep 1.2
Sound library for PascalABC.NET with notes and effects!

### 🎵 How to use:
1. Download `.pcu` file
2. Put it in your project folder (where your .pas program is)
3. Add `uses Beep;` at the beginning of your program
4. Enjoy the sounds!

### 📋 Command list:
| Procedure | Description | Parameters | Example |
|-----------|-------------|------------|---------|
| `Do1` | Play note Do (523 Hz) | none | `Do1;` |
| `Re` | Play note Re (587 Hz) | none | `Re;` |
| `Mi` | Play note Mi (659 Hz) | none | `Mi;` |
| `Fa` | Play note Fa (698 Hz) | none | `Fa;` |
| `Sol` | Play note Sol (784 Hz) | none | `Sol;` |
| `La` | Play note La (880 Hz) | none | `La;` |
| `Ti` | Play note Ti (988 Hz) | none | `Ti;` |
| `Do2` | Play note Do2 (1047 Hz) | none | `Do2;` |
| `Do3` | Play note Do3 (2093 Hz) | none | `Do3;` |
| `Win` | Victory sound | none | `Win;` |
| `RSound` | Relax sound | none | `RSound;` |
| `NSound` | Noisy sound | none | `NSound;` |
| `Lose` | Defeat sound | none | `Lose;` |
| `Error` | Error sound | none | `Error;` |
| `LevelUp` | Level up sound | none | `LevelUp;` |
| `Expl` | Explosion sound | none | `Expl;` |
| `Sad` | Sad sound | none | `Sad;` |
| `Happy` | Happy sound | none | `Happy;` |
| `Angry` | Angry sound | none | `Angry;` |
| `Bored` | Bored sound | none | `Bored;` |
| `Notify` | Notification sound | none | `Notify;` |
| `ClTick` | Clock tick | repeats | `ClTick(3);` |
| `Alert` | Alarm sound | repeats | `Alert(3);` |
| `DmgSound` | Damage sound | none | `DmgSound;` |
| `HealSound` | Healing sound | none | `HealSound;` |
| `JumpSound` | Jump sound | none | `JumpSound;` |
| `CoinSound` | Coin sound | none | `CoinSound;` |
| `GltSound` | Glitch sound  | none | `GltSound;` |
| `GSSound` | GunShot sound | none | `GSSound;` |
| `DCSound` | DoorCreak sound | none | `DCSound;` |
| `HBSound` | HeartBeat sound | repeats | `HBSound(3);` |
| `RainSound` | Rain sound | repeats | `RainSound(3);` |
| `Bau` | Bau sound | repeats | `Bau(3);` |
| `BauRa` | BauRa sound | none | `BauRa;` |
| `CBeep` | Classic beep | none | `CBeep;` |
| `SCBeep` | Custom beep | freq, duration | `SCBeep(500, 300);` |
| `FBeep` | Fast beep | freq | `FBeep(600);` |
| `RndmBeep` | Random beep | none | `RndmBeep;` |
| `EchoBeep` | Echo effect | freq, duration | `EchoBeep(600, 300);` |
| `NBeep` | Noisy beep | none | `NBeep;` |
| `RBeep` | Relax beep | none | `RBeep;` |
| `RepBeep` | Repeating beep | repats, freq, duration | `RepBeep(3, 800, 350);` |
| `ReBeep` | Re?beep | freq, duration| `ReBeep(800, 350);` |
### 🎮 Example:
```pascal
uses Beep;

begin
  Do1; Re; Mi; Fa; Sol; La; Ti; Do2;  // Play scale
  Win;  // Victory!
end.
