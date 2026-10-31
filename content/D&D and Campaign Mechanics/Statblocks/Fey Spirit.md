
```statblock
layout: Basic 5e Layout
image: false,
name: "Fey Spirit"
size: "Small"
type: "Fey"
alignment: "Neutral"
ac: "12 + the spell's level"
hp: "30 + 10 for each spell level above 3"  
speed: "30 ft., Fly 30 ft."
stats: [13, 16, 14, 14, 11, 16] 
condition_immunities: "Charmed"
senses: "darkvision 60ft., passive Perception 10"
languages: "Sylvan, understands the languages you know"
cr: -
traits:
  - name: "Proficiency Bonus."
    desc: "This creature's Proficiency Bonus equals your bonus."
actions:
  - name: "**Multiattack.**"
    desc: "The spirit makes a number of Fey Blade attacks equal to half this spell's level (round down)."
  - name: "**Fey Blade.**"
    desc: "**Melee Attack Roll**: Bonus equals your spell attack modifier, reach 5 ft. Hit: 2d6 + 3 + the spell's level Force damage."
bonus_actions:
  - name: "**Fey Step**"
    desc: "The spirit magically teleports up to 30 feet to an unoccupied space it can see. Then one of the following effects occurs, based on the spirit's chosen mood:"
  - name: "**Fuming**."
    desc: "The spirit has Advantage on the next attack roll it makes before the end of this turn."
  - name: "**Mirthful**."
    desc: "**Wisdom Saving Throw**: DC equals your spell save DC, one creature the spirit can see within 10 feet of itself. **Failure**: The target i5 Charmed by you and the spirit for l minute or until he target takes any damage."
  - name: "**Tricksy**."
    desc: "The spirit fills a 10-foot Cube within 5 feet of it with magical Darkness, which lasts until the end of its next turn."
```

