---
Gear:
  - Close-fitting
  - Coat of Mail
  - Helm
  - Long-hafted Axe
  - Buckler
---


### Testing dataviews for armor/weapons
- This works OK, but doesn't have a good way to add things like Keen. Decided to just make manual table instead

```dataview
TABLE without id link("/_Assets/Reference/Weapons#" + Weapon, Weapon) as Weapon, Damage as ":RaBurstBlob:", Injury as ":RaDrippingSword:"
from csv("_Assets/TOR Data - Weapons.csv") 
WHERE econtains(this.Gear, Weapon)
```

```dataview
TABLE without id link("/_Assets/Reference/Armor#" + Armour, Armour) as Armor, Protection as ":RaVest:"
from csv("_Assets/TOR Data - Armor.csv") 
WHERE econtains(this.Gear, Armour)
```