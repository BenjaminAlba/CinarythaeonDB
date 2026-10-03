
```statblock
layout: Basic 5e Layout
image: false,
name: "Bestial Spirit"
size: "Small"
type: "Beast"
alignment: "Neutral"
ac: "11 + the spell's level"
hp: "20 (Air only) or 30 (Land and Water only) + 5 for each spell level above 2"  
speed: "30 ft.; Climb 30 ft. (Land only); Fly 60 ft. (Air only); Swim 30 ft. (Water only)"
stats: [18, 11, 16, 4, 14, 5] 
condition_immunities: "Charmed"
senses: "darkvision 60ft., passive Perception 12"
languages: "understands the languages you know"
cr: -
traits:
  - name: "Proficiency Bonus."
    desc: "This creature's Proficiency Bonus equals your bonus."
  - name: "Flyby (Air only)."
    desc: "The spirit doesn't provoke Opportunity Attacks when it flies out of an enemy's reach."
  - name: "Pack Tactics (Land and Water Only)."
    desc: "The spirit has Advantage on an attack roll against a creature if at least one of the spirit's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition."
  - name: "Water Breathing (Water Only)."
    desc: "The spirit can breathe only underwater."
actions:
  - name: "**Multiattack.**"
    desc: "The spirit makes a number of Rend attacks equal to half this spell's level (round down)."
  - name: "**Rend.**"
    desc: "**Melee Attack Roll**: Bonus equals your spell attack modifier, reach 5 ft. Hit: ld8 + 4 + the spell's level Piercing damage."
```