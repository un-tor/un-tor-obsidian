---
cssclasses:
  - character_sheet
  - disable_tracksXXX
  - wideTable
Name: "{{title}}"
Strength: "0"
StrengthTN: "18"
Heart: "0"
HeartTN: "18"
Wits: "0"
WitsTN: "18"
EnduranceMax: "0"
HopeMax: "0"
Parry: "0"
Culture:
  - "[[Dwarves of Durn's Folk|Dwarf]]"
  - "[[Beornings]]"
  - "[[Men of Bree]]"
  - "[[Hobbits of the Shire]]"
  - "[[Hobbits of Bree]]"
  - "[[Elves of Lindon]]"
  - "[[Elves of Mirkwood]]"
  - "[[High Elves of Rivendell]]"
  - "[[Bardings]]"
  - "[[Rangers of the North]]"
  - "[[Woodmen of Wilderland]]"
DistinctiveFeatures:
  - Pick 2 + Calling
Calling:

  - "[[Captain]]"
  - "[[Champion]]"
  - "[[Messenger]]"
  - "[[Scholar]]"
  - "[[Treasure Hunter]]"
  - "[[Warden]]"
StandardOfLiving:
  - Poor
  - Frugal
  - Common
  - Prosperous
  - Rich
Armor: 0d6
Valour: "1"
Wisdom: "1"
ShadowPath: 
Scars: "0"
Treasure: 0
AdventurePoints: 0
SkillPoints: 0
Fellowship: 0
icon: raPlayer
tags:
  - PC
Company:
---

![[DwarfYoung.png| profile+medium center]]


|                                                    |
| -------------------------------------------------- |
| *A short description.*                             |
| **Culture:** `=this.Culture`                       |
| **Calling:** `=this.Calling`                       |
| **Features:** `=this.DistinctiveFeatures`          |
| **Endurance:**  `0` / `=this.EnduranceMax`         |
| **Fatigue:**  ` ` `0`                              |
| **Hope:** ` `  ` ` `0` / `=this.HopeMax`           |
| **Fellowship:** `0` / `=this.Fellowship`           |
| **Shadow/Scars:** `0` / *`=this.scars`*            |
| **Parry/Armor:** *`=this.Parry`* / *`=this.Armor`* |

|                                               |                              |
| --------------------------------------------- | ---------------------------- |
| :RaMuscleUp: **Strength:** *`=this.Strength`* | **TN:** *`=this.StrengthTN`* |
| `0/1` Awe:                                    | `0/6`                        |
| `0/1` Athletics:                              | `0/6`                        |
| `0/1` Awareness:                              | `0/6`                        |
| `0/1` Hunting:                                | `0/6`                        |
| `0/1` Song:                                   | `0/6`                        |
| `0/1` Craft:                                  | `0/6`                        |
| :FasHeart: **Heart:** *`=this.Heart`*         | **TN:** *`=this.HeartTN`*    |
| `0/1` Enhearten:                              | `0/6`                        |
| `0/1` Travel:                                 | `0/6`                        |
| `0/1` Insight:                                | `0/6`                        |
| `0/1` Healing:                                | `0/6`                        |
| `0/1` Courtesy:                               | `0/6`                        |
| `0/1` Battle:                                 | `0/6`                        |
| Valour:                                       | *`=this.Valour`*             |
| :FasBrain: **Wits:** *`=this.Wits`*           | **TN:** *`=this.WitsTN`*     |
| `0/1` Persuade:                               | `0/6`                        |
| `0/1` Stealth:                                | `0/6`                        |
| `0/1` Scan:                                   | `0/6`                        |
| `0/1` Explore:                                | `0/6`                        |
| `0/1` Riddle:                                 | `0/6`                        |
| `0/1` Lore:                                   | `0/6`                        |
| Wisdom:                                       | *`=this.Wisdom`*             |
| :RaBatteredAxe: **Weapons:**                  |                              |
| Axes:                                         | `0/6`                        |
| Bows:                                         | `0/6`                        |
| Spears:                                       | `0/6`                        |
| Swords:                                       | `0/6`                        |

| Weapons | :RaBurstBlob: | :RaDrippingSword: |
| ------- | :-----------: | :---------------: |
| name    |    damage     |      injury       |

| Armor |  :RaVest:  | :LiScale: |
| ----- | :--------: | :-------- |
| name  | protection | weight    |

| Inventory                        |
| -------------------------------- |
| Item (Skill)                     |
| Pony (Vigor X)                   |
| **Treasure:** *`=this.Treasure`* |

| Blessings & Virtues                  |
| ------------------------------------ |
|  XXX            |
|  XXX            |
| Adv. Points: `=this.AdventurePoints` |
| Skill Points: `=this.SkillPoints`    |

| Failings & Conditions|
| ----------------------|
| Shadow Path: `=this.ShadowPath` |
| Flaws: - |
|  `0/1` <abbr title="Gain when Shadow >= Hope. Auto fail on Eye roll.">Miserable</abbr> ` ` `0/1` <abbr title="Gain when Endurance <= Load + Fatigue. Count 1-3 on d6 as 0.">Weary</abbr> |
| `0/1` <abbr title="Gain when failing Protection roll. No Endurance gain during short rest; gain STR worth of Endurance on Prolonged Rest. On second wound, Endurance=0 and player is dying.">Wounded</abbr> ` ` Injury: - |

---