---
Inspiration: true
---
#sc #nito 

Klasse (class::Cleric)
Level (level::10)
Proficiency (prof::4)

HP (hp::73/`=8 + this.conMod + (this.level - 1) * (this.hitDieAvg + this.conMod)`)
Hit-Dice (hitDie::d8) ((hitDieAvg::5) Avg.)

Resistenzen: Non-Magical Physical, Necrotic
Immunitäten: Non-Magical Poisons and Illnesses

## Attribute

| Attribut | Stats          | Mod          | Save          |
| -------- | -------------- | ------------ | ------------- |
| **STR**  | (strStat:: 14) | (strMod::2)  | (strSave::3)  |
| **DEX**  | (dexStat::12)  | (dexMod::1)  | (dexSave::2)  |
| **CON**  | (conStat::14)  | (conMod::2)  | (conSave::3)  |
| **INT**  | (intStat::12)  | (intMod::1)  | (intSave::2)  |
| **WIS**  | (wisStat::20)  | (wisMod::5)  | (wisSave::10) |
| **CHA**  | (chaStat::8)   | (chaMod::-1) | (intSave::4)  |
## Skills

| Skill           | Mod                         | Ability |
| --------------- | --------------------------- | ------- |
| Acrobatics      | `=this.dexMod`              | DEX     |
| Animal Handling | `=this.wisMod`              | WIS     |
| Arcana          | `=this.intMod`              | INT     |
| Athletics       | `=this.strMod`              | STR     |
| Deception       | `=this.chaMod`              | CHA     |
| **History**     | `=this.intMod + this.prof`  | INT     |
| **Insight**     | `=this.wisMod + this.prof`  | WIS     |
| Intimidation    | `=this.chaMod`              | CHA     |
| Investigation   | `=this.intMod`              | INT     |
| Medicine        | `=this.wisMod`              | WIS     |
| Nature          | `=this.wisMod`              | WIS     |
| Perception      | `=this.wisMod` (15 passive) | WIS     |
| Performance     | `=this.chaMod`              | CHA     |
| **Persuasion**  | `=this.chaMod + this.prof`  | CHA     |
| **Religion**    | `=this.intMod + this.prof`  | INT     |
| Sleight of Hand | `=this.dexMod`              | DEX     |
| Stealth         | `=this.dexMod`              | DEX     |
| Survival        | `=this.wisMod`              | WIS     |
## Spell Slots

- Level I
	- [ ] 
	- [ ] 
	- [ ] 
	- [ ] 
	
- Level II
	- [ ] 
	- [ ] 
	- [ ] 

- Level III
	- [ ] 
	- [ ] 
	- [ ] 

- Level IV
	- [ ] 
	- [ ] 
	- [ ] 

Spell-Slots:
I: 4x
II: 3x
III: 3x
IV: 3x
V: 2x