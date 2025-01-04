
These adversaries were created or converted by `@Circle of Noms` on the TOR discord and [itch.io](https://circleofnoms.itch.io/the-one-ring-2e-homebrew-materials).
They were transformed into JSON files using the [Roll20 TOR exporter](https://github.com/bhuesemann/roll20-tor2e-adversary-json-export) and then converted into YAML files to be displayed via the TOR Statblocks plugin.
- TODO: some of the `^Name` links below entries are broken (need to remove special characters)

# Common Adversaries

```tor2e
name: Messenger Of Lugburz
description: Circle of Noms Adversary
features:
- Swift
- Secretive
level: 5
endurance: 20
might: 1
hate: 5
parry: '2'
armour: 2d
proficiencies:
- name: Scimitar
  rating: 3
  damage: 3
  injury: 16
  special: ''
- name: Jagged knife
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
```

^MessengerOfLugburz

```tor2e
name: Snaga Tracker
description: Circle of Noms Adversary
features:
- Swift
- Keen-Eyed
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Bow of horn
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Jagged knife
  rating: 2
  damage: 2
  injury: 14
  special: ''
abilities:
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Craven.|Craven.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^SnagaTracker

```tor2e
name: Black Uruk
description: Circle of Noms Adversary
features:
- Fierce
- Tall
level: 5
endurance: 20
might: 1
hate: 5
parry: '2'
armour: 2d
proficiencies:
- name: Broad bladed sword
  rating: 3
  damage: 5
  injury: 18
  special: ''
- name: Broad headed spear
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
```

^BlackUruk

```tor2e
name: Orcs Of Mount Gram
description: Circle of Noms Adversary
features:
- Vicious
- Stealthy
level: 3
endurance: 12
might: 1
hate: 3
parry: '-'
armour: 2d
proficiencies:
- name: Bent sword
  rating: 3
  damage: 5
  injury: 14
  special: ''
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Hate Sunlight.|Hate Sunlight.]]'
```

^OrcsOfMountGram

```tor2e
name: Orcs Of The White Mountains
description: Circle of Noms Adversary
features:
- Bitter
- Starving
level: 3
endurance: 12
might: 1
hate: 3
parry: '-'
armour: 2d
proficiencies:
- name: Bent sword
  rating: 3
  damage: 5
  injury: 14
  special: ''
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Cowardly.|Cowardly.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
```

^OrcsOfTheWhiteMountains

```tor2e
name: Half-Orcs
description: Circle of Noms Adversary
features:
- Tall
- Ferocious
level: 6
endurance: 24
might: 1
hate: 6
parry: '2'
armour: 3d
proficiencies:
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^Half-Orcs

```tor2e
name: Goblins Of Carn Dum
description: Circle of Noms Adversary
features:
- Vicious
- Stealthy
level: 2
endurance: 8
might: 1
hate: 2
parry: '-'
armour: 2d
proficiencies:
- name: Broad bladed sword
  rating: 3
  damage: 5
  injury: 14
  special: ''
- name: Bow of horn
  rating: 2
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Cowardly.|Cowardly.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
```

^GoblinsOfCarnDum

```tor2e
name: Uruk-Hai Soldiers
description: Circle of Noms Adversary
features:
- Clever
- Swift
level: 6
endurance: 24
might: 1
hate: 6
parry: '2'
armour: 2d
proficiencies:
- name: Broad bladed sword
  rating: 3
  damage: 5
  injury: 18
  special: ''
- name: Bow of horn
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^Uruk-HaiSoldiers

```tor2e
name: Uruk-Hai Captain [E]
description: Circle of Noms Adversary
features:
- Cunning
- Fierce
level: 8
endurance: 42
might: 1
hate: 8
parry: '2'
armour: 3d
proficiencies:
- name: Broad bladed sword
  rating: 4
  damage: 5
  injury: 18
  special: ''
- name: Orc whip
  rating: 3
  damage: 3
  injury: 10
  special: '[[Special Damage Options#Seize|Seize]]'
abilities: []
```

^Uruk-HaiCaptain

```tor2e
name: Goblin-Men
description: Circle of Noms Adversary
features:
- Stealthy
- Keen
level: 3
endurance: 12
might: 1
hate: 4
parry: '1'
armour: 1d
proficiencies:
- name: Jagged knife
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Craven.|Craven.]]'
```

^Goblin-Men

```tor2e
name: Orcish Wolf-Riders
description: Circle of Noms Adversary
features:
- Fierce
- Swift
level: 4
endurance: 16
might: 1
hate: 4
parry: '1'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Bent sword
  rating: 2
  damage: 5
  injury: 14
  special: ''
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Craven.|Craven.]]'
```

^OrcishWolf-Riders

```tor2e
name: Hobgoblins
description: Circle of Noms Adversary
features:
- Cruel
- Large
level: 6
endurance: 24
might: 1
hate: 6
parry: '1'
armour: 3d
proficiencies:
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^Hobgoblins

```tor2e
name: Marsh Hags [E]
description: Circle of Noms Adversary
features:
- Slimy
- Horrible
level: 4
endurance: 26
might: 1
hate: 4
parry: '1'
armour: 2d
proficiencies:
- name: Claws
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^MarshHags

```tor2e
name: Forest Goblin
description: Circle of Noms Adversary
features:
- Cunning
- Subtle
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Stone spear
  rating: 3
  damage: 4
  injury: 12
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Jagged knife
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Mirkwood Dweller.|Mirkwood Dweller.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Cowardly.|Cowardly.]]'
```

^ForestGoblin

```tor2e
name: The Pale Ones
description: Circle of Noms Adversary
features:
- Small
- Feral
level: 4
endurance: 16
might: 1
hate: 4
parry: '1'
armour: 1d
proficiencies:
- name: Bow of horn
  rating: 4
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Jagged knife
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
```

^ThePaleOnes

```tor2e
name: Common Hill Troll
description: Circle of Noms Adversary
features:
- Fierce
- Irritable
level: 5
endurance: 45
might: 2
hate: 5
parry: '-'
armour: 3d
proficiencies:
- name: Club
  rating: 2
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Crush
  rating: 2
  damage: 4
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^CommonHillTroll

```tor2e
name: Hill-Troll Chief [E]
description: Circle of Noms Adversary
features:
- Fierce
- Cruel
level: 8
endurance: 70
might: 2
hate: 8
parry: '-'
armour: 4d
proficiencies:
- name: Club
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Crush
  rating: 2
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Thick Hide.|Thick Hide.]]'
```

^Hill-TrollChief

```tor2e
name: Mountain Troll [E]
description: Circle of Noms Adversary
features:
- Brutish
- Wicked
level: 10
endurance: 80
might: 2
hate: 10
parry: '-'
armour: 5d
proficiencies:
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^MountainTroll

```tor2e
name: Ettins
description: Circle of Noms Adversary
features:
- Keen-Eyed
- Ancient
level: 9
endurance: 70
might: 2
hate: 9
parry: '-'
armour: 3d
proficiencies:
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Tear
  rating: 2
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Two-Headed OR Four-Armed.|Two-Headed OR Four-Armed.]]'
- '[[#Two-Headed.|Two-Headed.]]'
- '[[#Four-Armed.|Four-Armed.]]'
```

^Ettins

```tor2e
name: Fungal Troll
description: Circle of Noms Adversary
features:
- Ugly
- Wild
level: 10
endurance: 80
might: 2
hate: 10
parry: '-'
armour: 3d
proficiencies:
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Crush
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Foul Reek.|Foul Reek.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^FungalTroll

```tor2e
name: Marsh-Ogre
description: Circle of Noms Adversary
features:
- Slimy
- Vicious
level: 9
endurance: 70
might: 2
hate: 9
parry: '-'
armour: 2d
proficiencies:
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^Marsh-Ogre

```tor2e
name: Attercop
description: Circle of Noms Adversary
features:
- Stealthy
- Swift
level: 2
endurance: 8
might: 1
hate: 2
parry: '1'
armour: 2d
proficiencies:
- name: Sting
  rating: 3
  damage: 3
  injury: 12
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Web
  rating: 2
  damage: '-'
  injury: '-'
  special: '[[Special Damage Options#Web|Web]]'
abilities: []
```

^Attercop

```tor2e
name: Great Spider
description: Circle of Noms Adversary
features:
- Vicious
- Fierce
level: 8
endurance: 32
might: 2
hate: 8
parry: '1'
armour: 3d
proficiencies:
- name: Sting
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Web
  rating: 3
  damage: '-'
  injury: '-'
  special: '[[Special Damage Options#Web|Web]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^GreatSpider

```tor2e
name: Hunter Spider
description: Circle of Noms Adversary
features:
- Swift
- Stealthy
level: 6
endurance: 24
might: 1
hate: 6
parry: '2'
armour: 3d
proficiencies:
- name: Sting
  rating: 4
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Great Leap.|Great Leap.]]'
- '[[#Paralyzing-Poison.|Paralyzing-Poison.]]'
```

^HunterSpider

```tor2e
name: Great Bat
description: Circle of Noms Adversary
features:
- Swift
- Loud
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Claws
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities: []
```

^GreatBat

```tor2e
name: Secret Shadow [D]
description: Circle of Noms Adversary
features:
- Stealthy
- Secretive
level: 7
endurance: 28
might: 1
hate: 7
parry: '2'
armour: 3d
proficiencies:
- name: Bite
  rating: 4
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Claws
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Bewilder.|Bewilder.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^SecretShadow

```tor2e
name: Elder Vampire [E]
description: Circle of Noms Adversary
features:
- Vicious
- Swift
level: 6
endurance: 50
might: 2
hate: 6
parry: '1'
armour: 3d
proficiencies:
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Claws
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Deadly Wound.|Deadly Wound.]]'
```

^ElderVampire

```tor2e
name: Hill-Men Of Rhudaur
description: Circle of Noms Adversary
features:
- Grim
- Bold
level: 5
endurance: 20
might: 1
resolve: 5
parry: '1'
armour: 2d
proficiencies:
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Raven Spirits.|Raven Spirits.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Cowardly.|Cowardly.]]'
```

^Hill-MenOfRhudaur

```tor2e
name: Hill-Men Of Gundabad
description: Circle of Noms Adversary
features:
- Wild
- Fierce
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Short sword
  rating: 2
  damage: 3
  injury: 16
  special: ''
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Hatred (Beornings & Elves).|Hatred (Beornings & Elves).]]'
```

^Hill-MenOfGundabad

```tor2e
name: Gundabad Spirit Wargs
description: Circle of Noms Adversary
features:
- Grim
- Bold
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Great Leap.|Great Leap.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^GundabadSpiritWargs

```tor2e
name: Wild Men Of Mirkwood
description: Circle of Noms Adversary
features:
- Cruel
- Barbaric
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Stone spear
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Mirkwood Dweller.|Mirkwood Dweller.]]'
- '[[#Hatred (Elves).|Hatred (Elves).]]'
- '[[#Thrall (Spiders).|Thrall (Spiders).]]'
- '[[#Craven.|Craven.]]'
```

^WildMenOfMirkwood

```tor2e
name: Dunlending Raiders
description: Circle of Noms Adversary
features:
- Subtle
- Swift
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 2d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Hatred (Men of Rohan).|Hatred (Men of Rohan).]]'
```

^DunlendingRaiders

```tor2e
name: Wulfing Riders
description: Circle of Noms Adversary
features:
- Violent
- Bold
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Hatred (Men of Rohan).|Hatred (Men of Rohan).]]'
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^WulfingRiders

```tor2e
name: Warriors Of The Gaesela
description: Circle of Noms Adversary
features:
- Stern
- Wary
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Axe
  rating: 2
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^WarriorsOfTheGaesela

```tor2e
name: Men Of Isengard
description: Circle of Noms Adversary
features:
- Bold
- Cunning
level: 3
endurance: 12
might: 1
resolve: 4
parry: '1'
armour: 3d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^MenOfIsengard

```tor2e
name: Easterling-Warrior
description: Circle of Noms Adversary
features:
- Fierce
- Tough
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 4d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^Easterling-Warrior

```tor2e
name: Easterling Captain [E]
description: Circle of Noms Adversary
features:
- Tough
- Vicious
level: 6
endurance: 24
might: 1
resolve: 6
parry: '2'
armour: 4d
proficiencies:
- name: Scimitar
  rating: 4
  damage: 4
  injury: 16
  special: ''
- name: Dagger
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fierce Folk.|Fierce Folk.]]'
- '[[#Cruel Stroke.|Cruel Stroke.]]'
```

^EasterlingCaptain

```tor2e
name: Easterling Raider
description: Circle of Noms Adversary
features:
- Swift
- Elusive
level: 5
endurance: 30
might: 1
resolve: 5
parry: '2'
armour: 4d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Deadly Elusiveness.|Deadly Elusiveness.]]'
```

^EasterlingRaider

```tor2e
name: Easterling Sorcerer [D]
description: Circle of Noms Adversary
features:
- Cruel
- Cunning
level: 5
endurance: 30
might: 1
resolve: 5
parry: '2'
armour: 4d
proficiencies:
- name: Black bladed dagger
  rating: 3
  damage: 2
  injury: 14
  special: ''
abilities:
- '[[#Dreadful Spells.|Dreadful Spells.]]'
```

^EasterlingSorcerer

```tor2e
name: Corrupted Dwarf Warrior
description: Circle of Noms Adversary
features:
- Tough
- Maniacal
level: 5
endurance: 30
might: 1
resolve: 5
parry: '1'
armour: 4d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Mattock
  rating: 3
  damage: 7
  injury: 18
  special: ''
abilities: []
```

^CorruptedDwarfWarrior

```tor2e
name: Corrupted Dwarfs
description: Circle of Noms Adversary
features:
- Tough
- Stubborn
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 3d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities: []
```

^CorruptedDwarfs

```tor2e
name: Corrupted Dwarf Veteran [E]
description: Circle of Noms Adversary
features:
- Tough
- Experienced
level: 6
endurance: 34
might: 1
resolve: 6
parry: '2'
armour: 5d
proficiencies:
- name: Axe
  rating: 4
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Mattock
  rating: 4
  damage: 7
  injury: 18
  special: ''
abilities: []
```

^CorruptedDwarfVeteran

```tor2e
name: Spectres
description: Circle of Noms Adversary
features:
- Restless
- Sorrowful
level: null
endurance: null
might: null
parry: ''
armour: null
proficiencies: []
abilities:
- '[[#Ghost Form.|Ghost Form.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Visions of Torment.|Visions of Torment.]]'
```

^Spectres

```tor2e
name: Bog Soldiers [M]
description: Circle of Noms Adversary
features:
- Relentless
- Foul
level: 3
endurance: 12
might: 1
hate: 3
parry: '-'
armour: 2d
proficiencies:
- name: Short sword
  rating: 3
  damage: 3
  injury: 16
  special: ''
- name: Claws
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities: []
```

^BogSoldiers

```tor2e
name: Wood-Wight
description: Circle of Noms Adversary
features:
- Cruel
- Haunted
level: 8
endurance: 42
might: 1
hate: 8
parry: '1'
armour: 4d
proficiencies:
- name: Strangling claws
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Horror of the Wood.|Horror of the Wood.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
```

^Wood-Wight

```tor2e
name: Dead Men Of Dunharrow
description: Circle of Noms Adversary
features:
- Vengeful
- Cruel
level: 6
endurance: 24
might: 1
hate: 6
parry: '-'
armour: 2d
proficiencies: []
abilities:
- '[[#Ghost Form.|Ghost Form.]]'
- '[[#Visions of Torment.|Visions of Torment.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
```

^DeadMenOfDunharrow

```tor2e
name: Grim Hawks
description: Circle of Noms Adversary
features:
- Wild
- Vicious
level: 3
endurance: 12
might: 1
hate: 3
parry: '2'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Craven.|Craven.]]'
```

^GrimHawks

```tor2e
name: Basilisk
description: Circle of Noms Adversary
features:
- Large
- Wild
level: 8
endurance: 32
might: 1
hate: 3
parry: '1'
armour: 4d
proficiencies:
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Hatred (Elves).|Hatred (Elves).]]'
- '[[#Venomous Breath.|Venomous Breath.]]'
```

^Basilisk

```tor2e
name: Huorns.
description: Circle of Noms Adversary
features:
- Ancient
- Vengeful
level: 6
endurance: 60
might: 2
hate: 6
parry: '-'
armour: 4d
proficiencies:
- name: Bough lash
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Hatred (Orcs).|Hatred (Orcs).]]'
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Wrapped in Shadow.|Wrapped in Shadow.]]'
```

^Huorns

```tor2e
name: Bloodstump The Hunter [E]
description: Circle of Noms Adversary
features:
- Vicious
- Hateful
level: 10
endurance: 100
might: 2
hate: 10
parry: '-'
armour: 4d
proficiencies:
- name: Great black mace
  rating: 3
  damage: 8
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hatred (Dunedain).|Hatred (Dunedain).]]'
- '[[#Cruel Stroke.|Cruel Stroke.]]'
```

^BloodstumpTheHunter

# Unique Adversaries

```tor2e
name: The Queen On Castle Hill [E]
description: Circle of Noms Adversary
features:
- Bold
- Cunning
level: 7
endurance: 75
might: 2
hate: 7
parry: '-'
armour: 4d
proficiencies:
- name: Club
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hatred (Dunedain).|Hatred (Dunedain).]]'
```

^TheQueenOnCastleHill

```tor2e
name: Gorgol, Son Of Bolg [E]
description: Circle of Noms Adversary
features:
- Cunning
- Bold
level: 6
endurance: 44
might: 2
hate: 6
parry: '3'
armour: 4d
proficiencies:
- name: Heavy scimitar
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hatred (Dwarves).|Hatred (Dwarves).]]'
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^Gorgol,SonOfBolg

```tor2e
name: The New Great Goblin [E]
description: Circle of Noms Adversary
features:
- Vengeful
- Proud
level: 6
endurance: 60
might: 2
hate: 6
parry: '-'
armour: 4d
proficiencies:
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Broad headed spear
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^TheNewGreatGoblin

```tor2e
name: Maghaz, Orc-Captain [E]
description: Circle of Noms Adversary
features:
- Cruel
- Controlling
level: 5
endurance: 20
might: 1
hate: 5
parry: '2'
armour: 3d
proficiencies:
- name: Bent sword
  rating: 3
  damage: 5
  injury: 14
  special: ''
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Fierce Folk.|Fierce Folk.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^Maghaz,Orc-Captain

```tor2e
name: Nagrhaw, Chief Of The Wargs [E]
description: Circle of Noms Adversary
features:
- Cunning
- Lordly
level: 6
endurance: 24
might: 1
hate: 6
parry: '1'
armour: 3d
proficiencies:
- name: Bite
  rating: 4
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^Nagrhaw,ChiefOfTheWargs

```tor2e
name: Black Warg Of Methedras [E]
description: Circle of Noms Adversary
features:
- Stealthy
- Merciless
level: 5
endurance: 20
might: 1
hate: 5
parry: '2'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities: []
```

^BlackWargOfMethedras[E]

```tor2e
name: Great Boar Of Everholt [E]
description: Circle of Noms Adversary
features:
- Undying
- Huge
level: 7
endurance: 48
might: 2
resolve: 7
parry: '-'
armour: 3d
proficiencies:
- name: Vicious gore
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities: []
```

^GreatBoarOfEverholt

```tor2e
name: Stoneclaws The Bear [E]
description: Circle of Noms Adversary
features:
- Lordly
- Vicious
level: 5
endurance: 40
might: 2
resolve: 5
parry: '-'
armour: 3d
proficiencies:
- name: Maul
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
```

^StoneclawsTheBear

```tor2e
name: Dreorg The Wargling [E]
description: Circle of Noms Adversary
features:
- Savage
- Determined
level: 6
endurance: 24
might: 1
hate: 6
parry: '2'
armour: 3d
proficiencies:
- name: Bite
  rating: 4
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Great Leap.|Great Leap.]]'
```

^DreorgTheWargling

```tor2e
name: Radgul The Orc-Chief [E]
description: Circle of Noms Adversary
features:
- Cunning
- Bold
level: 6
endurance: 34
might: 1
hate: 6
parry: '3'
armour: 4d
proficiencies:
- name: Orc axe
  rating: 4
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hatred (Hobbits).|Hatred (Hobbits).]]'
```

^RadgulTheOrc-Chief

```tor2e
name: The Wight-King [E][D]
description: Circle of Noms Adversary
features:
- Deathless
- Lordly
level: 8
endurance: 52
might: 2
hate: 8
parry: '2'
armour: 2d
proficiencies:
- name: Ancient sword
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Chilling touch
  rating: 3
  damage: 7
  injury: 12
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Black Dread.|Black Dread.]]'
- '[[#Darker than the Darkness.|Darker than the Darkness.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
```

^TheWight-King

```tor2e
name: The Witch-King Of Angmar
description: Circle of Noms Adversary
features:
- Tyrannical
- Merciless
level: 11
endurance: 100
might: 2
hate: 11
parry: '3'
armour: 3d
proficiencies:
- name: Long sword
  rating: 4
  damage: 7
  injury: 16
  special: ''
- name: Claw
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Morgul knife
  rating: 3
  damage: 4
  injury: 20
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Words of Power and Terror.|Words of Power and Terror.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Shadow of Fear.|Shadow of Fear.]]'
- '[[#Prohibition.|Prohibition.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^TheWitch-KingOfAngmar

```tor2e
name: The Sorcerer Of Forod
description: Circle of Noms Adversary
features:
- Cruel
- Indomitable
level: 9
endurance: 70
might: 2
hate: 9
parry: '2'
armour: 2d
proficiencies:
- name: Long sword
  rating: 3
  damage: 5
  injury: 16
  special: ''
- name: Claw
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Morgul knife
  rating: 2
  damage: 4
  injury: 20
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Shadow of Fear.|Shadow of Fear.]]'
- '[[#Terror of Desire.|Terror of Desire.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Bewilder.|Bewilder.]]'
```

^TheSorcererOfForod

```tor2e
name: Lieutenant Of Dol Guldur
description: Circle of Noms Adversary
features:
- Terrifying
- Indomitable
level: 10
endurance: 80
might: 2
hate: 10
parry: '3'
armour: 2d
proficiencies:
- name: Long sword
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
- name: Claw
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^LieutenantOfDolGuldur

```tor2e
name: The Messenger Of Mordor
description: Circle of Noms Adversary
features:
- Terrifying
- Swift
level: 10
endurance: 80
might: 2
hate: 10
parry: '3'
armour: 2d
proficiencies:
- name: Long sword
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
- name: Claw
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Bewilder.|Bewilder.]]'
```

^TheMessengerOfMordor

```tor2e
name: The Ghost Of The Forest
description: Circle of Noms Adversary
features:
- Terrifying
- Cunning
level: 10
endurance: 80
might: 2
hate: 10
parry: '3'
armour: 2d
proficiencies:
- name: Long sword
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
- name: Claw
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Fell Speed.|Fell Speed.]]'
```

^TheGhostOfTheForest

# Oaths of the Riddermark Adversaries
```tor2e
name: The Horse-Eater [E]
description: Circle of Noms Adversary
features:
- Huge
- Ferocious
level: 9
endurance: 90
might: 2
hate: 9
parry: '1'
armour: 3d
proficiencies:
- name: Crush
  rating: 3
  damage: 7
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Bite
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Wicked Cunning.|Wicked Cunning.]]'
```

^TheHorse-Eater

```tor2e
name: Caselwun
description: Circle of Noms Adversary
features:
- Reckless
- Fierce
level: 5
endurance: 20
might: 1
resolve: 5
parry: '1'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^Caselwun

```tor2e
name: Rhonwen
description: Circle of Noms Adversary
features:
- Wary
- Keen-Eyed
level: 5
endurance: 20
might: 1
resolve: 5
parry: '1'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Axe
  rating: 2
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^Rhonwen

```tor2e
name: Blodred
description: Circle of Noms Adversary
features:
- Stern
- Wild
level: 3
endurance: 22
might: 1
resolve: 3
parry: '2'
armour: 4d
proficiencies:
- name: Great spear
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
abilities: []
```

^Blodred

```tor2e
name: Dunlending-Warriors
description: Circle of Noms Adversary
features:
- Fierce
- Loyal
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 3d
proficiencies:
- name: Cavarun the giant great axe
  rating: 3
  damage: 7
  injury: 20
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Gutun the singer sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
- name: Logwen of the graves spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
- name: Wesun wolfblood great spear
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Lonely onwen spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Cartartun bear shield spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Vecodorun mad mouth axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^Dunlending-Warriors

```tor2e
name: The Barrow-Witch
description: Circle of Noms Adversary
features:
- Mysterious
- Cunning
level: 4
endurance: 16
might: 1
resolve: 4
parry: '-'
armour: 1d
proficiencies: []
abilities:
- '[[#Dark Glamour.|Dark Glamour.]]'
```

^TheBarrow-Witch

```tor2e
name: The Grey Horse [D]
description: Circle of Noms Adversary
features:
- Grim
- Aggressive
level: 8
endurance: 80
might: 2
hate: 8
parry: '-'
armour: 3d
proficiencies:
- name: Bite
  rating: 3
  damage: 7
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities: []
```

^TheGreyHorse

```tor2e
name: Horse-Lords Spectre
description: Circle of Noms Adversary
features:
- Vengeful
- Lordly
level: 6
endurance: 24
might: 1
hate: 6
parry: '2'
armour: 2d
proficiencies: []
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Ghost Form.|Ghost Form.]]'
- '[[#Visions of Torment.|Visions of Torment.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
```

^Horse-LordsSpectre

```tor2e
name: Agents Of Mordor
description: Circle of Noms Adversary
features:
- Brutal
- Greedy
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Scimitar
  rating: 3
  damage: 3
  injury: 16
  special: ''
abilities: []
```

^AgentsOfMordor

```tor2e
name: Bandits From The South
description: Circle of Noms Adversary
features:
- Wicked
- Nervous
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Dagger
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Cowardly.|Cowardly.]]'
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^BanditsFromTheSouth

```tor2e
name: Hirdan, Bandit Leader [E]
description: Circle of Noms Adversary
features: []
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 3d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^HirdanBanditLeader

```tor2e
name: Malthor, The Axe-Bitten [E]
description: Circle of Noms Adversary
features:
- Cunning
- Vicious
level: 5
endurance: 30
might: 1
hate: 5
parry: '2'
armour: 3d
proficiencies:
- name: Black sword
  rating: 4
  damage: 6
  injury: 18
  special: ''
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Hatred (Riders of Rohan).|Hatred (Riders of Rohan).]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
```

^MalthorTheAxe-Bitten

```tor2e
name: Gazhur Three-Deaths [E]
description: Circle of Noms Adversary
features:
- Leadership
- Determined
level: 8
endurance: 42
might: 1
hate: 8
parry: '3'
armour: 3d
proficiencies:
- name: Heavy scimitar
  rating: 4
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Broad headed spear
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Wicked Cunning.|Wicked Cunning.]]'
```

^GazhurThree-Deaths

# Tales from Wilderland Adversaries
```tor2e
name: Thugs-Trio
description: Circle of Noms Adversary
features:
- Sneaky
- Troublemaker
level: 2
endurance: 8
might: 1
resolve: 2
parry: '-'
armour: 1d
proficiencies:
- name: Short sword
  rating: 2
  damage: 3
  injury: 16
  special: ''
abilities:
- '[[#Cowardly.|Cowardly.]]'
```

^Thugs-Trio

```tor2e
name: The Thing In The Well
description: Circle of Noms Adversary
features:
- Mysterious
- Huge
level: 6
endurance: 44
might: 3
hate: 6
parry: '1'
armour: 3d
proficiencies:
- name: Tentacle lash
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Strangle
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Thick Hide.|Thick Hide.]]'
```

^TheThingInTheWell

```tor2e
name: Night-Wight
description: Circle of Noms Adversary
features:
- Swift
- Ghostly
level: 7
endurance: 38
might: 2
hate: 7
parry: '2'
armour: 4d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Strangling claws
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
```

^Night-Wight

```tor2e
name: Valter The Bloody
description: Circle of Noms Adversary
features:
- Vicious
- Determined
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 4d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^ValterTheBloody

```tor2e
name: Outlaws
description: Circle of Noms Adversary
features:
- Cruel
- Rustic
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies: []
abilities: []
```

^Outlaws

```tor2e
name: Faron The Trapper
description: Circle of Noms Adversary
features:
- Cunning
- Grim
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Axe
  rating: 2
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Snake-like Speed.|Snake-like Speed.]]'
```

^FaronTheTrapper

```tor2e
name: Oderic
description: Circle of Noms Adversary
features:
- Brave
- Reckless
level: 5
endurance: 20
might: 1
resolve: 5
parry: '1'
armour: 1d
proficiencies:
- name: Sword
  rating: 3
  damage: 3
  injury: 16
  special: ''
abilities:
- '[[#Savage Assault.|Savage Assault.]]'
```

^Oderic

```tor2e
name: Undead Warriors [M]
description: Circle of Noms Adversary
features:
- Brutal
- Deathless
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Claw
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
```

^UndeadWarriors[M]

```tor2e
name: Easterling Warriors
description: Circle of Noms Adversary
features:
- Greedy
- Fierce
level: 3
endurance: 12
might: 1
resolve: 3
parry: '2'
armour: 2d
proficiencies:
- name: Pike
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Long hafted axe
  rating: 3
  damage: 6
  injury: 18
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
abilities: []
```

^EasterlingWarriors

```tor2e
name: Ghor The Despoiler [E]
description: Circle of Noms Adversary
features:
- Huge
- Cruel
level: 7
endurance: 38
might: 2
hate: 7
parry: '3'
armour: 3d
proficiencies:
- name: Heavy scimitar
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Orc axe
  rating: 3
  damage: 3
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^GhorTheDespoiler

```tor2e
name: Gerold The Beorning
description: Circle of Noms Adversary
features:
- Wild
- Fierce
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 2d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^GeroldTheBeorning

```tor2e
name: Elstan, Captain Of Dale [E]
description: Circle of Noms Adversary
features:
- Lordly
- Bold
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 3d
proficiencies:
- name: Spear
  rating: 4
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Fierce Folk.|Fierce Folk.]]'
```

^Elstan,CaptainOfDale

```tor2e
name: Elstan Followers
description: Circle of Noms Adversary
features:
- Loyal
- Proud
level: 3
endurance: 12
might: 1
resolve: 2
parry: '1'
armour: 2d
proficiencies:
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
abilities: []
```

^ElstanFollowers

```tor2e
name: The Gibbet Kingn [E] [M]
description: Circle of Noms Adversary
features:
- Cruel
- Deathless
level: 9
endurance: 56
might: 2
hate: 9
parry: '-'
armour: 3d
proficiencies: []
abilities:
- '[[#Bewilder.|Bewilder.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Heartless.|Heartless.]]'
- '[[#Feast on Suffering.|Feast on Suffering.]]'
```

^TheGibbetKingn

```tor2e
name: Snow Trolls
description: Circle of Noms Adversary
features:
- Brutish
- Wicked
level: 8
endurance: 70
might: 2
hate: 8
parry: '-'
armour: 3d
proficiencies:
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Bite
  rating: 4
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thick Hide.|Thick Hide.]]'
```

^SnowTrolls

```tor2e
name: Raenar The Cold-Drake [E] [D]
description: Circle of Noms Adversary
features:
- Lordly
- Proud
level: 12
endurance: 120
might: 2
hate: 12
parry: '-'
armour: 6d
proficiencies:
- name: Bite
  rating: 3
  damage: 9
  injury: 18
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Rend
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Tail lash
  rating: 2
  damage: 20
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Poison Blast.|Poison Blast.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Weak Spot.|Weak Spot.]]'
```

^RaenarTheCold-Drake

# ruins of the north adversaries

```tor2e
name: Savage Wolfdogs
description: Circle of Noms Adversary
features:
- Wild
- Fierce
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 2d
proficiencies:
- name: Bite
  rating: 2
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Great Leap.|Great Leap.]]'
```

^SavageWolfdogs

```tor2e
name: The Lurker In The Long Valley
description: Circle of Noms Adversary
features:
- Terrifying
- Nameless
level: 9
endurance: 90
might: 3
hate: 9
parry: '-'
armour: 5d
proficiencies:
- name: Pincer crush
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Blade like leg
  rating: 2
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Weak Spot.|Weak Spot.]]'
- '[[#Thick Hide.|Thick Hide.]]'
```

^TheLurkerInTheLongValley

```tor2e
name: Heddwyn [D]
description: Circle of Noms Adversary
features:
- Cruel
- Dominated
level: 6
endurance: 24
might: 1
hate: 6
parry: '1'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Reckless Hate.|Reckless Hate.]]'
```

^Heddwyn

```tor2e
name: Heddwyn As Spirit-Warg
description: Circle of Noms Adversary
features:
- Cruel
- Dominated
level: 4
endurance: 16
might: 1
hate: 4
parry: '2'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Great Leap.|Great Leap.]]'
```

^HeddwynAsSpirit-Warg

```tor2e
name: Sergeant Cyrnan
description: Circle of Noms Adversary
features:
- Rugged
- Ruthless
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 2d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^SergeantCyrnan

```tor2e
name: Ruthless Bandits
description: Circle of Noms Adversary
features:
- Dumb
- Greedy
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^RuthlessBandits

```tor2e
name: Ettin Guardian
description: Circle of Noms Adversary
features:
- Keen-Eyed
- Fierce
level: 8
endurance: 60
might: 2
hate: 8
parry: '-'
armour: 3d
proficiencies:
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Two-Headed.|Two-Headed.]]'
```

^EttinGuardian

```tor2e
name: Captain Mormog [E]
description: Circle of Noms Adversary
features:
- Swift
- Cunning
level: 9
endurance: 90
might: 2
hate: 9
parry: '-'
armour: 3d
proficiencies:
- name: Notched sword
  rating: 3
  damage: 7
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Snake-like Speed.|Snake-like Speed.]]'
```

^CaptainMormog

```tor2e
name: Hobbit Spectres
description: Circle of Noms Adversary
features:
- Ghostly
- Keen-Eyed
level: 4
endurance: 26
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies: []
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
- '[[#Ghost Form.|Ghost Form.]]'
```

^HobbitSpectres

```tor2e
name: Fell Wraith
description: Circle of Noms Adversary
features:
- Heartless
- Deathless
level: 6
endurance: 35
might: 1
hate: 6
parry: '-'
armour: 2d
proficiencies:
- name: Pitted blade
  rating: 3
  damage: 4
  injury: 12
  special: ''
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Wraith-Like.|Wraith-Like.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
```

^FellWraith

```tor2e
name: Caradog, Dunlending Hunter
description: Circle of Noms Adversary
features:
- Swift
- Fierce
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^Caradog,DunlendingHunter

```tor2e
name: Uatach
description: Circle of Noms Adversary
features:
- Mysterious
- Subtle
level: 5
endurance: 20
might: 1
resolve: 5
parry: '-'
armour: 2d
proficiencies:
- name: Jagged knife
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^Uatach

```tor2e
name: Brutal Thugs
description: Circle of Noms Adversary
features:
- Brutal
- Selfish
level: 2
endurance: 8
might: 1
resolve: 2
parry: '-'
armour: 1d
proficiencies:
- name: Dagger
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Craven.|Craven.]]'
```

^BrutalThugs

```tor2e
name: Armed Men
description: Circle of Noms Adversary
features:
- Loyal
- Keen-Eyed
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 1d
proficiencies:
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^ArmedMen

```tor2e
name: Dunlending Warriors
description: Circle of Noms Adversary
features:
- Brutish
- Keen-Eyed
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 2d
proficiencies:
- name: Long hafted axe
  rating: 3
  damage: 6
  injury: 20
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^DunlendingWarriors

```tor2e
name: Armed Villagers
description: Circle of Noms Adversary
features:
- Ruthless
- Bold
level: 3
endurance: 12
might: 1
resolve: 3
parry: '-'
armour: 1d
proficiencies:
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
- name: Spear
  rating: 1
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^ArmedVillagers

```tor2e
name: Elwin
description: Circle of Noms Adversary
features:
- Eager
- True-Hearted
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities: []
```

^Elwin

```tor2e
name: Fay
description: Circle of Noms Adversary
features:
- Keen-Eyed
- Gruff
level: 3
endurance: 12
might: 1
resolve: 3
parry: '2'
armour: 1d
proficiencies:
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^Fay

```tor2e
name: Herbert
description: Circle of Noms Adversary
features:
- Spiteful
- Brutal
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 1d
proficiencies:
- name: Dagger
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities: []
```

^Herbert

```tor2e
name: Folulf And Arnulf
description: Circle of Noms Adversary
features:
- Swift
- Wary
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 2d
proficiencies:
- name: Folulf axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Arnulf bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^FolulfAndArnulf

```tor2e
name: Huldrahir [D]
description: Circle of Noms Adversary
features:
- Ancient
- Spiteful
level: 8
endurance: 32
might: 1
hate: 8
parry: '-'
armour: 2d
proficiencies: []
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Ghost Form.|Ghost Form.]]'
- '[[#Visions of Torment.|Visions of Torment.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
- '[[#Black Dread.|Black Dread.]]'
```

^Huldrahir

```tor2e
name: The Deadly One [E]
description: Circle of Noms Adversary
features:
- Cruel
- Relentless
level: 9
endurance: 46
might: 2
hate: 9
parry: '3'
armour: 3d
proficiencies:
- name: Heavy scimitar
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Broad headed spear
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Deadly Elusiveness.|Deadly Elusiveness.]]'
```

^TheDeadlyOne

```tor2e
name: Goblin Horde
description: Circle of Noms Adversary
features:
- Endless
- Suicidal
level: 3
endurance: 12
might: 1
hate: 3
parry: '-'
armour: 2d
proficiencies:
- name: Broad bladed sword
  rating: 2
  damage: 5
  injury: 18
  special: ''
- name: Bow of horn
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Hatred (Dunedain) and (Elves).|Hatred (Dunedain) and (Elves).]]'
```

^GoblinHorde

```tor2e
name: Thieving Dwarves
description: Circle of Noms Adversary
features:
- Determined
- Greedy
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 3d
proficiencies:
- name: Mattock
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
abilities: []
```

^ThievingDwarves

```tor2e
name: Lofar Light-Finger
description: Circle of Noms Adversary
features:
- Greedy
- Cunning
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 3d
proficiencies:
- name: Mattock
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
```

^LofarLight-Finger

# Bree Adventures Adversaries
```tor2e
name: The Old Troll [E]
description: Circle of Noms Adversary
features:
- Cunning
- Swift
level: 10
endurance: 80
might: 2
hate: 10
parry: '1'
armour: 4d
proficiencies:
- name: Troll knife
  rating: 3
  damage: 5
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Crush
  rating: 3
  damage: 6
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Reckless Hate.|Reckless Hate.]]'
- '[[#Deadly Misfortune.|Deadly Misfortune.]]'
```

^TheOldTroll

```tor2e
name: Brutes Of Bree
description: Circle of Noms Adversary
features:
- Brutish
- Cruel
level: 2
endurance: 8
might: 1
resolve: 2
parry: '1'
armour: 1d
proficiencies:
- name: Spear
  rating: 2
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Craven.|Craven.]]'
```

^BrutesOfBree

```tor2e
name: Gror The Dwarf
description: Circle of Noms Adversary
features:
- Greedy
- Cunning
level: 5
endurance: 20
might: 1
resolve: 5
parry: '2'
armour: 3d
proficiencies:
- name: Mattock
  rating: 3
  damage: 7
  injury: 18
  special: ''
abilities: []
```

^GrorTheDwarf

```tor2e
name: Edoric
description: Circle of Noms Adversary
features:
- Restless
- Subtle
level: 6
endurance: 24
might: 1
resolve: 6
parry: '2'
armour: 2d
proficiencies:
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Bow
  rating: 2
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Defend Ally.|Defend Ally.]]'
```

^Edoric

```tor2e
name: Vogar
description: Circle of Noms Adversary
features:
- Bold
- Furious
level: 6
endurance: 24
might: 1
resolve: 2
parry: 2/6
armour: 4d
proficiencies:
- name: Mattock
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#2-Handed|2-Handed]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Berserk Rage.|Berserk Rage.]]'
```

^Vogar

```tor2e
name: Narvi
description: Circle of Noms Adversary
features:
- Stealthy
- Impatient
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 3d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities: []
```

^Narvi

```tor2e
name: Hirlinion
description: Circle of Noms Adversary
features:
- Secretive
- Loyal
level: 5
endurance: 20
might: 1
resolve: 5
parry: '1'
armour: 1d
proficiencies:
- name: Dagger
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Poisoned Blade.|Poisoned Blade.]]'
- '[[#Bewilder.|Bewilder.]]'
```

^Hirlinion

```tor2e
name: Berelas [E]
description: Circle of Noms Adversary
features:
- Compassionate
- Subtle
level: 3
endurance: 12
might: 1
resolve: 3
parry: '-'
armour: 2d
proficiencies:
- name: Dagger
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Shade Caller.|Shade Caller.]]'
- "[[#Gorlanc\u2019s Poison.|Gorlanc\u2019s Poison.]]"
```

^Berelas

```tor2e
name: The Cold Shade [D]
description: Circle of Noms Adversary
features:
- Deathless
- Heartless
level: 6
endurance: 34
might: 2
hate: 6
parry: '2'
armour: 2d
proficiencies:
- name: Icy touch
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Deathless.|Deathless.]]'
- '[[#Heartless.|Heartless.]]'
```

^TheColdShade

```tor2e
name: White Wolf Of The North [E]
description: Circle of Noms Adversary
features:
- Vicious
- Lordly
level: 5
endurance: 20
might: 1
hate: 5
parry: '2'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Great Leap.|Great Leap.]]'
- '[[#Snake-like Speed.|Snake-like Speed.]]'
```

^WhiteWolfOfTheNorth

```tor2e
name: "Gorlanc\u2019S Warriors"
description: Circle of Noms Adversary
features:
- Swift
- Loyal
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 2d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities: []
```

^Gorlanc’SWarriors

```tor2e
name: Bluebell Wood Oakmen
description: Circle of Noms Adversary
features:
- Stealthy
- Playful
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 1d
proficiencies:
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Hatred (First Foe to Strike Him).|Hatred (First Foe to Strike Him).]]'
- '[[#Craven.|Craven.]]'
```

^BluebellWoodOakmen

```tor2e
name: "Gorlanc\u2019S Followers"
description: Circle of Noms Adversary
features:
- Loyal
- Cruel
level: 3
endurance: 12
might: 1
hate: 3
parry: '1'
armour: 1d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities: []
```

^Gorlanc’SFollowers

```tor2e
name: Gorlanc [D]
description: Circle of Noms Adversary
features:
- Desperate
- Vicious
level: 4
endurance: 16
might: 1
hate: 4
parry: '2'
armour: 1d
proficiencies:
- name: Dagger
  rating: 3
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Yell of Triumph.|Yell of Triumph.]]'
- '[[#Bewilder.|Bewilder.]]'
- '[[#Hatred (Everyone).|Hatred (Everyone).]]'
```

^Gorlanc

# Laughter of Dragons Adversaries
```tor2e
name: Longo
description: Circle of Noms Adversary
features:
- Fair-Spoken
- Subtle
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 2d
proficiencies:
- name: Dagger
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities: []
```

^Longo

```tor2e
name: "Longo\u2019S Lieutenants"
description: Circle of Noms Adversary
features:
- Brutish
- Loyal
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 2d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^Longo’SLieutenants

```tor2e
name: "Gunvar\u2019S Bodyguards"
description: Circle of Noms Adversary
features:
- Loyal
- Fierce
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 3d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
abilities:
- '[[#Reckless Hate.|Reckless Hate.]]'
```

^Gunvar’SBodyguards

```tor2e
name: "Gunvar\u2019S Men-At-Arms"
description: Circle of Noms Adversary
features:
- Vicious
- Brutish
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 3d
proficiencies:
- name: Sword
  rating: 2
  damage: 4
  injury: 16
  special: ''
abilities: []
```

^Gunvar’SMen-At-Arms

```tor2e
name: Firbul, Snaga Tracker [D]
description: Circle of Noms Adversary
features:
- Swift
- Keen-Eyed
level: 4
endurance: 16
might: 1
hate: 4
parry: '3'
armour: 2d
proficiencies:
- name: Deadly bow of horn
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Jagged knife
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Cruel Stroke.|Cruel Stroke.]]'
- '[[#Cowardly.|Cowardly.]]'
```

^FirbulSnagaTracker

```tor2e
name: Cutthroats Of The Dalelands
description: Circle of Noms Adversary
features:
- Ruthless
- Rebellious
level: 3
endurance: 12
might: 1
resolve: 3
parry: '1'
armour: 1d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
- name: Bow
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities: []
```

^CutthroatsOfTheDalelands

```tor2e
name: Silent Vultures [D]
description: Circle of Noms Adversary
features:
- Gigantic
- Silent
level: 5
endurance: 30
might: 1
hate: 5
parry: '1'
armour: 2d
proficiencies:
- name: Talons
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Beak
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Disgorge.|Disgorge.]]'
- '[[#Formidable.|Formidable.]]'
- '[[#Weak Spot.|Weak Spot.]]'
```

^SilentVultures

```tor2e
name: Skarf, Lord Of Brech
description: Circle of Noms Adversary
features:
- Deceiving
- Fearful
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 3d
proficiencies:
- name: Great axe
  rating: 3
  damage: 7
  injury: 20
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
abilities:
- '[[#Great Leap.|Great Leap.]]'
```

^Skarf,LordOfBrech

```tor2e
name: Dwarven Assassin
description: Circle of Noms Adversary
features:
- Stealthy
- Swift
level: 4
endurance: 16
might: 1
resolve: 4
parry: '2'
armour: 3d
proficiencies:
- name: Axe
  rating: 3
  damage: 5
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
- name: Dagger
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Cowardly.|Cowardly.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^DwarvenAssassin

```tor2e
name: Raenar The Plunderer [E] [D]
description: Circle of Noms Adversary
features:
- Bitter
- Greedy
level: 14
endurance: 140
might: 2
hate: 14
parry: '-'
armour: 7d
proficiencies:
- name: Bite
  rating: 4
  damage: 8
  injury: 18
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Rend
  rating: 3
  damage: 7
  injury: 18
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Tail lash
  rating: 1
  damage: 20
  injury: 18
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Foul Reek.|Foul Reek.]]'
- '[[#Fire Breath.|Fire Breath.]]'
- '[[#Weak Spot.|Weak Spot.]]'
```

^RaenarThePlunderer

```tor2e
name: Wrunele The Fiery [E] [D]
description: Circle of Noms Adversary
features:
- Proud
- Cruel
level: 10
endurance: 90
might: 2
hate: 10
parry: '-'
armour: 5d
proficiencies:
- name: Bite
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
- name: Rend
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Tail lash
  rating: 2
  damage: 14
  injury: 16
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities: []
```

^WruneleTheFiery

```tor2e
name: Mud-Man
description: Circle of Noms Adversary
features:
- Fair
- Sinister
level: 4
endurance: 16
might: 1
resolve: 4
parry: '1'
armour: 1d
proficiencies:
- name: Dagger
  rating: 2
  damage: 2
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Bow
  rating: 3
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
- name: Spear
  rating: 3
  damage: 4
  injury: 16
  special: '[[Special Damage Options#Pierce 2-Handed|Pierce 2-Handed]]'
abilities:
- '[[#Strange Venoms.|Strange Venoms.]]'
```

^Mud-Man

```tor2e
name: The Guttermaw
description: Circle of Noms Adversary
features:
- Slimy
- Wild
level: 7
endurance: 28
might: 2
hate: 7
parry: '-'
armour: 2d
proficiencies:
- name: Iron claws
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
```

^TheGuttermaw

```tor2e
name: Wolf Of The Waste [E]
description: Circle of Noms Adversary
features:
- Ferocious
- Stealthy
level: 4
endurance: 16
might: 1
hate: 4
parry: '1'
armour: 2d
proficiencies:
- name: Bite
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Deadly Wound.|Deadly Wound.]]'
```

^WolfOfTheWaste

```tor2e
name: The Devourer [E]
description: Circle of Noms Adversary
features:
- Ancient
- Ferocious
level: 6
endurance: 24
might: 1
hate: 6
parry: '1'
armour: 2d
proficiencies:
- name: Bite
  rating: 4
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Fear of Fire.|Fear of Fire.]]'
- '[[#Deadly Wound.|Deadly Wound.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^TheDevourer

```tor2e
name: Ravenous Goblins
description: Circle of Noms Adversary
features:
- Wild
- Swift
level: 3
endurance: 12
might: 1
hate: 3
parry: '-'
armour: 2d
proficiencies:
- name: Jagged knife
  rating: 2
  damage: 3
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Bite
  rating: 1
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Craven.|Craven.]]'
```

^RavenousGoblins

```tor2e
name: The Stalker In The Deeps [E]
description: Circle of Noms Adversary
features:
- Ancient
- Stealthy
level: 6
endurance: 50
might: 2
hate: 6
parry: '-'
armour: 4d
proficiencies:
- name: Bite
  rating: 4
  damage: 8
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
abilities:
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Savage Assault.|Savage Assault.]]'
```

^TheStalkerInTheDeeps

# Darkening of Mirkwood Adversaries

```tor2e
name: Servants Of Tyrants Hill
description: Circle of Noms Adversary
features:
- Trained
- Cruel
level: 4
endurance: 16
might: 1
hate: 4
parry: '-'
armour: 2d
proficiencies:
- name: Sword
  rating: 3
  damage: 4
  injury: 16
  special: ''
- name: Savage hound
  rating: 3
  damage: 4
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Beast-Tamer.|Beast-Tamer.]]'
```

^ServantsOfTyrantsHill

```tor2e
name: The Forest Dragon
description: Circle of Noms Adversary
features:
- Cunning
- Stealthy
level: 10
endurance: 90
might: 2
hate: 10
parry: '-'
armour: 4d
proficiencies:
- name: Bite
  rating: 4
  damage: 7
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Crush
  rating: 3
  damage: 6
  injury: 14
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Thick Hide.|Thick Hide.]]'
- '[[#Mirkwood Dweller.|Mirkwood Dweller.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Weak Spot.|Weak Spot.]]'
```

^TheForestDragon

```tor2e
name: Raegenhere
description: Circle of Noms Adversary
features:
- Possessed
- Deathless
level: 9
endurance: 56
might: 2
hate: 9
parry: '1'
armour: 3d
proficiencies:
- name: Great axe
  rating: 3
  damage: 7
  injury: 20
  special: '[[Special Damage Options#Break Shield 2-Handed|Break Shield 2-Handed]]'
- name: Strangling claws
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
- '[[#Deathless.|Deathless.]]'
```

^Raegenhere

```tor2e
name: Valdis The Great Vampire
description: Circle of Noms Adversary
features:
- Shapechanging
- Swift
level: 9
endurance: 80
might: 2
hate: 9
parry: '2'
armour: 3d
proficiencies:
- name: Bite
  rating: 3
  damage: 7
  injury: 14
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Rake
  rating: 3
  damage: 5
  injury: 16
  special: '[[Special Damage Options#Seize|Seize]]'
abilities:
- '[[#Bewilder.|Bewilder.]]'
- '[[#Snake-Like Speed.|Snake-Like Speed.]]'
- '[[#Savage Assault.|Savage Assault.]]'
- '[[#Hate Sunlight.|Hate Sunlight.]]'
- '[[#Denizen of the Dark.|Denizen of the Dark.]]'
- '[[#Fell Speed.|Fell Speed.]]'
- '[[#Enthrall.|Enthrall.]]'
```

^ValdisTheGreatVampire

```tor2e
name: Sarqin, The Mother-Of-All
description: Circle of Noms Adversary
features:
- Large
- Starving
level: 10
endurance: 90
might: 2
hate: 10
parry: '-'
armour: 2d
proficiencies:
- name: Beak
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Stomp
  rating: 3
  damage: 7
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities: []
```

^Sarqin,TheMother-Of-All

```tor2e
name: Tauler The Hunter
description: Circle of Noms Adversary
features:
- Huge
- Stealthy
level: 8
endurance: 60
might: 2
hate: 8
parry: '1'
armour: 2d
proficiencies:
- name: Beak
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Stomp
  rating: 3
  damage: 7
  injury: 12
  special: '[[Special Damage Options#Break Shield|Break Shield]]'
abilities:
- '[[#Horrible Strength.|Horrible Strength.]]'
- '[[#Hideous Toughness.|Hideous Toughness.]]'
```

^TaulerTheHunter

```tor2e
name: Tyulqin The Weaver
description: Circle of Noms Adversary
features:
- Cruel
- Cunning
level: 9
endurance: 70
might: 2
hate: 9
parry: '1'
armour: 2d
proficiencies:
- name: Beak
  rating: 3
  damage: 6
  injury: 16
  special: '[[Special Damage Options#Pierce|Pierce]]'
- name: Ensnare
  rating: 3
  damage: '-'
  injury: '-'
  special: '[[Special Damage Options#Web|Web]]'
abilities:
- '[[#Web.|Web.]]'
- '[[#Thing of Terror.|Thing of Terror.]]'
- '[[#Dreadful Spells.|Dreadful Spells.]]'
- '[[#Webs of Illusion.|Webs of Illusion.]]'
- '[[#Many Poisons.|Many Poisons.]]'
- '[[#Weakened.|Weakened.]]'
- '[[#Sleep.|Sleep.]]'
- '[[#Drowning in Sorrow.|Drowning in Sorrow.]]'
- '[[#Crazed.|Crazed.]]'
```

^TyulqinTheWeaver


## Fell Abilities
### Snake-Like Speed
When targeted by an attack, spend 1 Hate to make the attack roll Ill-favoured.

### Hate Sunlight
The creature loses 1 Hate at the start of each round it is exposed to the full light of the sun.

### Craven
When affected by the Intimidate Foe combat task, the creature also loses 1 hate.

### Horrible Strength
If the creature scored a Piercing Blow with a close combat attack, spend 1 Hate to make the target’s Protection roll Ill-favoured.

### Cowardly
At the start of the round, the adversary flees the battlefield if at zero Hate and is unengaged

### Thing of Terror
At the start of the first round of the battle all Player-heroes in sight gain 3 Shadow points (Dread). Those who fail their Shadow test are daunted and cannot spend Hope for the rest of the fight.

### Denizen of the Dark
All attack rolls are Favoured while in darkness.

### Mirkwood Dweller
When inside Mirkwood, this creature gains +2 Parry.

### Thick Hide
Spend 1 Hate point to gain (2d) on a Protection roll. Thing of Horror. At the start of the first round of the battle all Player-heroes in sight gain 3 Shadow points (Dread). Those who fail their Shadow test are daunted and cannot spend Hope for the rest of the fight. Those who succeed will continue to gain 1 Shadow point (Dread) each round until they fail a Shadow test..

### Savage Assault
When this creature produces at least  on a successful attack roll, they may immediately make a second attack. This can only occur once per round.

### Two-Headed OR Four-Armed
Choose one of the two options.

### Two-Headed
All rolls made to sneak around this creature or ambush them are Ill

### Four-Armed
This creature can Seize two targets at the same time or seize one and still act normally.

### Foul Reek
If any hero engaged in close combat with this creature wishes to take any action other than attacking, they must spend 1 point of Hope (including Combat Tasks).

### Dreadful Spells
Spend 1 Hate to make a player-hero gain 2 Shadow points (Sorcery. If the hero fails their Shadow Test, they fall under the thrall of of Tyulqin and walk straight into the nearest web. The hero loses their next action.

### Great Leap
Spend 1 Hate to attack any Player-hero, in any combat stance, including Rearward

### Paralyzing-Poison
If this creature applies its Poison effect, the victim also falls to the ground paralyzed until the Poison is cured.

### Bewilder
Spend 1 Hate to reduce the Parry score of a player-hero by –2 for one turn.

### Deadly Wound
Wounded targets make an Ill-Favoured Feat die roll to determine the severity of their injury.

### Raven Spirits
When the first Hill-man dies in a combat, ravens swoop down and reduce the Parry rating of all player heroes by –2.

### Fear of Fire
The creature loses 1 Hate at the start of each round it is engaged in close combat with an adversary wielding a torch or other burning item.

### Hatred (Beornings & Elves)
When targeting the subject of their hate, all attacks are Favoured.

### Hatred (Elves)
When this creature is fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Thrall (Spiders)
This creature is a thrall of another. When its master is on the field, this creature may spend 1 Hate point to sacrifice itself to absorb an attack for its master. If its master is not on the field this creature loses 1 Hate and becomes

### Hatred (Men of Rohan)
When fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Fierce Folk
Spend 1 Resolve point to gain (1d) on an attack and to make the roll Favoured.

### Cruel Stroke
When this creatures scores a Piercing Blow, spend 1 Hate to raise the Injury Rating of the weapon by 4.

### Deadly Elusiveness
This creature can only be attacked in Close Combat by a character in Forward Stance.

### Ghost Form
The creature is incorporeal and partially, if not completely, invisible. It cannot normally harm nor can be harmed physically by the living. When this creatures Hate score is reduced to 0, it disappears and reappears the next night with its hate score refilled. Weapons that do not possess Enchanted qualities cannot affect this creature.

### Visions of Torment
Spend 1 Hate point to give a player-hero 1 point of Shadow (Dread). If the hero fails their Shadow Test, they also lose a number of Endurance points equal to twice their current Shadow total.

### Horror of the Wood
If this creature is encountered in Mirkwood, all BATTLE rolls made to gain combat advantages or remove combat complications are Ill-Favoured.

### Venomous Breath
Spend a point of Hate to force all characters in close-combat with this creature to make a Protection Test against TN 14 or be Poisoned.

### Hatred (Orcs)
When this creature is fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Wrapped in Shadow
Spend 1 Hate to summon a mist that forces all player heroes to succeed on a Shadow Test (Sorcery) or lose (2d) on all attack rolls and suffer –2 Parry in this combat. Torches or other sources of light do not help.

### Hideous Toughness
When an attack inflicts damage to this  creature that would cause it to go to zero Endurance, it causes a Piercing Blow. Then, if the creature survives even after failing the Protection Test, they return to full Endurance. Thing of Horror. At the start of the first round of the battle all Player-heroes in sight gain 3 Shadow points (Dread). Those who fail their Shadow test are daunted and cannot spend Hope for the rest of the fight. Those who succeed will continue to gain 1 Shadow point (Dread) each round until they fail a Shadow test.

### Hatred (Dunedain)
When fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Hatred (Dwarves)
When fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Yell of Triumph
Spend 1 Hate to restore 1 Hate to all other followers in the fight.

### Hatred (Hobbits)
When this creature is fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Deathless
Spend 1 Hate to cancel a Wound. When an attack inflicts damage to the creature that would cause it to go to zero Endurance, spend 1 Hate to bring the creatures back to full Endurance instead. This ability is ineffective against Player-heroes wielding a magical weapon enchanted with spells for the Bane of the Undead.

### Heartless
The creature is not affected by the Intimidate Foe combat task, unless a Magical success is obtained.

### Black Dread
All Shadow tests made against this creature’s abilities are Ill-Favoured.

### Darker than the Darkness
Spend 1 Hate to force all player-heroes to succeed on a Shadow Test (Sorcery) or lose (-2d) on all attack rolls and suffer –2 Parry for the rest of the combat.

### Words of Power and Terror
Whenever a player-hero spends a point of Hope to gain dice or invoke a virtue, spend 1 Hate to negate it.

### Shadow of Fear
The hero is made an agent of Shadow. They will follow the orders of the wraith for up to a month. If another hero can succeed on an AWE roll (or another appropriate personality skill) with at least  generated on the roll, they may break this spells effects.

### Prohibition
The hero is stricken dumb and loses their next turn. If the hero failed with a , any non-magical weapon they are currently holding is shattered.

### Terror of Desire
Hero is caught up in fantasies. Each round, the hero must roll a Feat Die until the hero breaks the spell by rolling a , or suffers a bout of madness by rolling a .

### Fell Speed
At the beginning of each turn, this creature can choose which hero it engages regardless of restrictions, or it can abandon combat entirely.

### Wicked Cunning
Spend 1 point of Hate to gain +4 Parry for a single round.

### Dark Glamour
Spend 1 Resolve to vanish into the mists or bewilder an opponent and make them Weary.

### Hatred (Riders of Rohan)
When targeting player-heroes of the cultures hated by this creature, its attacks are Favoured.

### Snake-like Speed
When targeted by an attack, spend 1 Hate to make the attack roll Ill-Favoured.

### Feast on Suffering
Whenever a player-hero is Wounded or is reduced to 0 Endurance, this creature gains 1 Hate.

### Poison Blast
The creature spends 1 point of hate to spew forth a jet of poisonous fumes. Anyone in Close Combat with the creature must make a Protection Test against TN 16 or be utterly destroyed. A success deals 2 success dice of Endurance Damage to the target (-1 die per  produced on the roll).

### Weak Spot
. Whenever the dragon spends a point of Hate, it exposes a weak spot on its underbelly for the duration of a single attack. When a player-hero scores a Piercing Blow on the dragons weak spot, the dragon’s Armor is reduced to 1 for the Protection Test.

### Reckless Hate
Spend 1 Resolve to recover 4 Endurance points.

### Wraith-Like
The creature can be Wounded only by weapons possessing Enchanted Qualities.

### Hatred (Dunedain) and (Elves)
When targeting player-heroes of the cultures hated by this creature, its attacks are Favoured.

### Deadly Misfortune
When a player-hero rolls a  near or within the lair of the Old Troll, the troll may spend 1 point of Hate to cause bones to fall onto that hero. The troll then gains (2d) against that hero for his next attack.

### Defend Ally
Spend 1 Resolve to redirect an attack aimed at an ally to this creature instead.

### Berserk Rage
If provoked, or if anyone rolls a  in combat, Vogar flies into a rage. He gains 4 Resolve, and may spend 1 Resolve to continue to fight for another round even if he has been reduced to 0 Endurance.

### Poisoned Blade
Whenever this creature strikes an enemy with a weapon attack, he may spend 1 Resolve to force the target to make a Protection Test against the weapons Injury Rating or be Poisoned.

### Shade Caller
Instead of attack, Berelas may call the cold-shade who appears the next round.

### Gorlanc’s Poison
If Berelas deals a wound with her weapons, the target is poisoned. In addition to the normal effects, all of the poisoned targets rolls become Ill-Favoured for 6 rounds.

### Hatred (First Foe to Strike Him)
When fighting hated enemies, all of this creature’s  attack rolls are Favoured.

### Hatred (Everyone)
When fighting hated enemies, all of this creature’s attack rolls are Favoured.

### Disgorge
When a vulture has seized a victim, it may attack them with its beak or spend 1 Hate to regurgitate its stomach contents onto them. If the Silent Vulture regurgitates its stomach onto its victim, that victim must roll a Protection test against TN 14. If the victim fails their Protection test, they are Poisoned and suffer (2d) Endurance damage.

### Formidable
All attacks with Talons are Favoured.

### Fire Breath
Spend 1 point of Hate to spew forth flames. Anyone in a close combat stance against the dragon suffers 24 Endurance damage  (Reduce damage by 2 if the hero is in Open Stance, or by 4 if the Hero is in Defensive Stance) and suffer a Piercing Blow (Injury Rating 18).

### Strange Venoms
Spend 1 Resolve on a successful attack to force a hero to make a Protection Test  against the weapon or be Poisoned. While Poisoned,  all of the heroes rolls are Ill-Favoured.

### Beast-Tamer
Spend 1 point of Hate to make a Savage Hound attack in addition to a normal attack. In addition, if a player-hero scores a Piercing Blow against this enemy, they may sacrifice their Hound instead of suffering the injury themselves.

### Enthrall
Any player-heroes that become Miserable in this combat are immediately enthralled by this creature. Each turn, that player-hero

### Web
If and attack with the Web quality successfully hits a target, that target is webbed and unable to move. The webbed target cannot change stance and suffers –4 to their Parry rating. The webbed target may free themselves by succeeding on an ATHLETICS roll.

### Webs of Illusion
Spend 1 Hate to immediately move to engage a chosen player-hero and attack them as if attacking from ambush.

### Many Poisons
If this creatures attack results in a Wound, the target is also poisoned.  In addition, apply one of the following effects:    Despair. The victim is now considered Miserable until the poison is cured.

### Weakened
This victim is now considered Weary until the poison is cured.

### Sleep
The victim falls unconscious until the poison is cured.

### Drowning in Sorrow
The victim gains 1 Shadow point (Sorcery) each day until the poison is cured.

### Crazed
The victim displays all of the flaws of their Shadow Path until the poison is cured.

Credits: These adversaries were created or converted from TOR 1E by Circle of Noms on the TOR discord.
