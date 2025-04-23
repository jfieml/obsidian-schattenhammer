---
Inspiration: true
---
#sc #nito 

**Name** (name::Nito, Aman'nitoqua)
**Klasse** (class::Cleric)
**Level** (level::10)
**Proficiency** +(prof::4)
**Proficiencies**: Leichte+Mittlere Rüstung, All Weapons, *Cooking Tools* (5/10 days Training)
**Features**: Dunkelsicht

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

| Skill           | Mod                                                  | Ability |
| --------------- | ---------------------------------------------------- | ------- |
| Acrobatics      | `=this.dexMod`                                       | DEX     |
| Animal Handling | `=this.wisMod`                                       | WIS     |
| Arcana          | `=this.intMod`                                       | INT     |
| Athletics       | `=this.strMod`                                       | STR     |
| Deception       | `=this.chaMod`                                       | CHA     |
| **History**     | `=this.intMod + this.prof`                           | INT     |
| **Insight**     | `=this.wisMod + this.prof`                           | WIS     |
| Intimidation    | `=this.chaMod + [[Mithril Halbplatte]].intimidation` | CHA     |
| Investigation   | `=this.intMod`                                       | INT     |
| Medicine        | `=this.wisMod`                                       | WIS     |
| Nature          | `=this.wisMod`                                       | WIS     |
| Perception      | `=this.wisMod` + **Adv.** (20 passive)               | WIS     |
| Performance     | `=this.chaMod`                                       | CHA     |
| **Persuasion**  | `=this.chaMod + this.prof`                           | CHA     |
| **Religion**    | `=this.intMod + this.prof`                           | INT     |
| Sleight of Hand | `=this.dexMod`                                       | DEX     |
| Stealth         | `=this.dexMod`                                       | DEX     |
| Survival        | `=this.wisMod`                                       | WIS     |
## Basis Werte

**HP** (hp::66/`=8 + this.conMod + (this.level - 1) * (this.hitDieAvg + this.conMod)`)
**Hit-Dice** (hitDie::d8) ((hitDieAvg::5) Avg.)

**AC** `=sum(this.ac) + this.dexMod`
**Initiative** +`=this.dexMod + " (Advantage)"`
**Speed** (speed::9 Meter)

**Verwundbarkeiten**: Radiant
**Resistenzen**: All Physical, Necrotic
**Immunitäten**: Non-Magical Poisons and Illnesses

[[Spell-List]]
[[Fight Cheat-Sheet]]
## Active Equipment

[[Mithril Halbplatte]] AC (ac::16)
[[Wächterschild]] AC +(ac::2)
[[Umhang des Schutzes]] AC +(ac::1)
[[Umhang des Schutzes]] Rettungswürfe +(saveBonus::1)
[[Wächterschild]] Advantage auf **Initiative**
[[Wächterschild]] Advantage auf **Weisheit (Wahrnehmung)**


