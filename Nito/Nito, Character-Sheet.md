---
Proficiency Bonus: "4"
level: 11
wisMod: 5
---
#sc #nito 

```consumable
items:
  - label: "Inspiration"
    state_key: din_inspiration
    uses: 1
```

```stats
items:
  - label: Name
    value: "Aman'nitoqua"
  - label: Class
    value: Death Cleric
  - label: Level
    value: 11
  - label: XP
    value: "85.500"
  - label: AC
    value: "20"
  - label: Initiative
    value: "+1 (Adv.)"
  - label: "Spell-Save DC"
    value: "17"
  - label: "Spell-Attack"
    value: "+9"

grid:
  columns: 4
```

```badges
items:
  - label: Proficiencies
    value: "Light & Medium Armor | Simple & Martial Weapons | Cooking Tools (5/10 days training)"
  - label: Languages
    value: "Common, Sylvan (Troll), Elf, Orc, Deepspeech (Hive)"
  - label: Speed
    value: "30 ft."
  - label: Senses
    value: "Darkvision 60 ft."
  - label: Revive-DC
    value: 12
  - label: Damage-Resistances
    value: "Non-Magical Slashing, Piercing, Bludgeoning | Necrotic"
  - label: Damage-Vulnerabilities
    value: "Radiant"
  - label: Damage-Immunities
    value: "Poison"
  - label: Condition-Immunities
    value: "Poisoned (by non-magical poison) | non-magical Illnesses"
```

```healthpoints
state_key: din_health
health: 80
hitdice:
  dice: d8
  value: 11
```

```ability
abilities:
  strength: 14
  dexterity: 12
  constitution: 14
  intelligence: 12
  wisdom: 20
  charisma: 8

bonuses:
  - name: "Cloak of Protection"
    target: strength
    value: 1
  - name: "Cloak of Protection"
    target: dexterity
    value: 1
  - name: "Cloak of Protection"
    target: constitution
    value: 1
  - name: "Cloak of Protection"
    target: intelligence
    value: 1
  - name: "Cloak of Protection"
    target: wisdom
    value: 1
  - name: "Cloak of Protection"
    target: charisma
    value: 1

proficiencies:
  - wisdom
  - charisma
```

```skills
proficiencies:
  - history
  - insight
  - persuasion
  - religion
```

### Channel Divinity
```consumable
items:
  - label: ""
    state_key: din_channel_divinity
    uses: 2
```

### Actions

#### Nahkampf Angriff
##### Klauen oder Fänge
+6 | 3 Slashing + 1d6 necr. + 1d8 necr. ([[Divine Strike]]) (+ [[Channel Divinity - Touch of Death]])

##### [[Langschwert, Ehre des Klingenmeisters]]
+7 | 1d8 Slashing + 1 + 1d8 necr. ([[Divine Strike]]) (+ [[Channel Divinity - Touch of Death]]) (+7 Damage bei Crit)


### Spell-Slots

```consumable
items:
  - label: "Level I"
    state_key: din_spells_1
    uses: 4
  - label: "Level II"
    state_key: din_spells_2
    uses: 3
  - label: "Level III"
    state_key: din_spells_3
    uses: 3
  - label: "Level IV"
    state_key: din_spells_4
    uses: 3
  - label: "Level V"
    state_key: din_spells_5
    uses: 2
  - label: "Level VI"
    state_key: din_spells_6
    uses: 1
```

### Traits

![[Reaper]]

![[Channel Divinity - Touch of Death]]

![[Inescapable Destruction]]

![[Nito/Fähigkeiten/Divine Strike|Divine Strike]]

---

[[Spell-List]]
[[Fight Cheat-Sheet]]
## Active Equipment

[[Mithril Halbplatte]] AC (ac::16)
[[Wächterschild]] AC +(ac::2)
[[Umhang des Schutzes]] AC +(ac::1)
[[Umhang des Schutzes]] Rettungswürfe +(saveBonus::1)
[[Wächterschild]] Advantage auf **Initiative**
[[Wächterschild]] Advantage auf **Weisheit (Wahrnehmung)**


