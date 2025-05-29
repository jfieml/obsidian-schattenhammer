---
Proficiency Bonus: "3"
---
```consumable
items:
  - label: "Inspiration"
    state_key: din_inspiration
    uses: 1
```

```stats
items:
  - label: Name
    value: "Heist Rogue"
  - label: Class
    value: 3 Arc. Trick. & 2 Ill. Wiz.
  - label: Level
    value: 5
  - label: Proficiency
    value: "+3"
  - label: AC
    value: "16"
  - label: Initiative
    value: "+3"
  - label: "Spell-Save DC"
    value: "14"
  - label: "Spell-Attack"
    value: "+6"

grid:
  columns: 4
```

```badges
items:
  - label: Proficiencies
    value: "Light Armor | simple weapons, hand crossbows, longswords, rapiers, shortswords | thieves' tools"
  - label: Languages
    value: "Common, Troll"
  - label: Speed
    value: "40 ft."
  - label: Revive-DC
    value: 10
```

```badges
items:
  - label: Sneak Attack
    value: "2d6"
  - label: "Max. prepared spells"
    value: 5
```

```healthpoints
state_key: din_health
health: 31
```

```ability
abilities:
  strength: 8
  dexterity: 16
  constitution: 12
  intelligence: 16
  wisdom: 10
  charisma: 11

proficiencies:
  - dexterity
  - intelligence
```

```skills
proficiencies:
  - acrobatics
  - deception
  - sleight of hand
  - stealth

expertise:
  - stealth
  - sleight of hand
```

### Items

**Rapier**
*Martial melee weapon, finesse*
1d8 piercing damage

**Hand Crossbow**
*Martial ranged weapon (30/120 ft.), light, loading*
1d6 piercing damage

### Spells Known

#### Cantrips
7 Cantrips from the Wizard Spell-List (Mage Hand + 2 from Arcane Trickster, Minor Illusion + 3 from Wizard):
- Mage Hand
- Minor Illusion
- Friends
- Message
- Light
- Prestidigitation
- Booming Blade

#### Level 1
3 from Arcane Trickster (2 of Ench. or Ill. school), always known:
- Silvery Barbs
- Disguise Self
- Mage Armor

6 from Wizard Level 1:
- Alarm (rit.)
- Comprehend Languages (rit.)
- Detect Magic (rit.)
- Find Familiar (rit.)
- Shield (react.)
- Feather Fall (react.)

2 from Wizard Level 2:
- ...
- ...
#### Level 2
From Spellscrolls:
- Invisibility

### Spell-Slots

```consumable
items:
  - label: "Level I"
    state_key: din_spells_1
    uses: 4
  - label: "Level II"
    state_key: din_spells_2
    uses: 2
  - label: "Arcane Recovery"
    state_key: din_arcane_recovery
    uses: 1
```

### Variant Human: Mobile Feat
You are exceptionally speedy and agile. You gain the following benefits:
- Your speed increases by 10 ft.
- When you use the Dash action, difficult terrain doesn't cost you extra movement on that turn
- When you make a melee attack against a creature, you don't provoke opportunity attacks from that creature for the rest of the turn, whether you hit or not.
### Rogue Level 1: Sneak Attack
Beginning at 1st level, you know how to strike subtly and exploit a foe's distraction. Once per turn, you can deal an extra 1d6 damage to one creature you hit with an attack if you have advantage on the attack roll. The attack must use a finesse or a ranged weapon.

You don't need advantage on the attack roll if another enemy of the target is within 5 feet of it, that enemy isn't [incapacitated](https://5e.tools/conditionsdiseases.html#incapacitated_phb), and you don't have disadvantage on the attack roll.

The amount of the extra damage increases as you gain levels in this class, as shown in the Sneak Attack column of the Rogue table.

### Rogue Level 1: Thieves' Cant
During your rogue training you learned thieves' cant, a secret mix of dialect, jargon, and code that allows you to hide messages in seemingly normal conversation. Only another creature that knows thieves' cant understands such messages. It takes four times longer to convey such a message than it does to speak the same idea plainly.

In addition, you understand a set of secret signs and symbols used to convey short, simple messages, such as whether an area is dangerous or the territory of a thieves' guild, whether loot is nearby, or whether the people in an area are easy marks or will provide a safe house for thieves on the run.

### Rogue Level 2: Cunning Action
Starting at 2nd level, your quick thinking and agility allow you to move and act quickly. You can take a bonus action on each of your turns in combat. This action can be used only to take the [Dash](https://5e.tools/actions.html#dash_phb), [Disengage](https://5e.tools/actions.html#disengage_phb), or [Hide](https://5e.tools/actions.html#hide_phb) action.

### Rogue Level 3: Arcane Trickster
Some rogues enhance their fine-honed skills of stealth and agility with magic, learning tricks of enchantment and illusion. These rogues include pickpockets and burglars, but also pranksters, mischief-makers, and a significant number of adventurers.
#### Spellcasting
When you reach 3rd level, you gain the ability to cast spells. See [chapter 10](https://5e.tools/book.html#PHB,10) for the general rules of spellcasting and [chapter 11](https://5e.tools/book.html#PHB,11) for the [wizard spell list](https://5e.tools/spells.html#blankhash,flstclass:wizard=1).

Cantrips. You learn three cantrips: [mage hand](https://5e.tools/spells.html#mage%20hand_phb) and two other cantrips of your choice from the wizard spell list. You learn another wizard cantrip of your choice at 10th level.

Spell Slots. The Arcane Trickster Spellcasting table shows how many spell slots you have to cast your [wizard spells](https://5e.tools/spells.html#blankhash,flstclass:wizard=1) of 1st level and higher. To cast one of these spells, you must expend a slot of the spell's level or higher. You regain all expended spell slots when you finish a long rest.

For example, if you know the 1st-level spell [charm person](https://5e.tools/spells.html#charm%20person_phb) and have a 1st-level and a 2nd-level spell slot available, you can cast [charm person](https://5e.tools/spells.html#charm%20person_phb) using either slot.

Spells Known of 1st-Level and Higher. You know three 1st-level wizard spells of your choice, two of which you must choose from the enchantment and illusion spells on the wizard spell list.

The Spells Known column of the Arcane Trickster Spellcasting table shows when you learn more wizard spells of 1st level or higher. Each of these spells must be an enchantment or illusion spell of your choice, and must be of a level for which you have spell slots. For instance, when you reach 7th level in this class, you can learn one new spell of 1st or 2nd level.

The spells you learn at 8th, 14th, and 20th level can come from any school of magic.

Whenever you gain a level in this class, you can replace one of the wizard spells you know with another spell of your choice from the wizard spell list. The new spell must be of a level for which you have spell slots, and it must be an enchantment or illusion spell, unless you're replacing the spell you gained at 3rd, 8th, 14th, or 20th level from any school of magic.

Spellcasting Ability. Intelligence is your spellcasting ability for your wizard spells, since you learn your spells through dedicated study and memorization. You use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a wizard spell you cast and when making an attack roll with one.

**Spell save DC** = 8 + Intelligence modifier + Proficiency Bonus
**Spell attack modifier** = Intelligence modifier + Proficiency Bonus

#### Mage Hand Legermain
Starting at 3rd level, when you cast [mage hand](https://5e.tools/spells.html#mage%20hand_phb), you can make the spectral hand [invisible](https://5e.tools/conditionsdiseases.html#invisible_phb), and you can perform the following additional tasks with it:

- You can stow one object the hand is holding in a container worn or carried by another creature.
- You can retrieve an object in a container worn or carried by another creature.
- You can use [thieves' tools](https://5e.tools/items.html#thieves'%20tools_phb) to pick locks and disarm traps at range.

You can perform one of these tasks without being noticed by a creature if you succeed on a Dexterity (Sleight of Hand) check contested by the creature's Wisdom (Perception) check.

In addition, you can use the bonus action granted by your Cunning Action to control the hand.

### Rogue Level 3: Steady Aim
As a bonus action, you give yourself advantage on your next attack roll on the current turn. You can use this bonus action only if you haven't moved during this turn, and after you use the bonus action, your speed is 0 until the end of the current turn.

### Wizard Level 1: Arcane Recovery
You have learned to regain some of your magical energy by studying your spellbook. Once per day when you finish a short rest, you can choose expended spell slots to recover. The spell slots can have a combined level that is equal to or less than half your wizard level (rounded up), and none of the slots can be 6th level or higher.

For example, if you're a 4th-level wizard, you can recover up to two levels worth of spell slots. You can recover either a 2nd-level spell slot or two 1st-level spell slots.

### Wizard Level 1: Spellcasting
As a student of arcane magic, you have a spellbook containing spells that show the first glimmerings of your true power. See [chapter 10](https://5e.tools/book.html#PHB,10) for the general rules of spellcasting and [chapter 11](https://5e.tools/book.html#PHB,11) for the [wizard spell list](https://5e.tools/spells.html#blankhash,flstclass:wizard=1).

#### Cantrips

At 1st level, you know three cantrips of your choice from the wizard spell list. You learn additional wizard cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Wizard table.

#### Spellbook

At 1st level, you have a spellbook containing six 1st-level [wizard spells](https://5e.tools/spells.html#blankhash,flstclass:wizard=1) of your choice. Your spellbook is the repository of the wizard spells you know, except your cantrips, which are fixed in your mind.

#### Preparing and Casting Spells

The Wizard table shows how many spell slots you have to cast your wizard spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell's level or higher. You regain all expended spell slots when you finish a long rest.

You prepare the list of wizard spells that are available for you to cast. To do so, choose a number of wizard spells from your spellbook equal to your Intelligence modifier + your wizard level (minimum of one spell). The spells must be of a level for which you have spell slots.

For example, if you're a 3rd-level wizard, you have four 1st-level and two 2nd-level spell slots. With an Intelligence of 16, your list of prepared spells can include six spells of 1st or 2nd level, in any combination, chosen from your spellbook. If you prepare the 1st-level spell [magic missile](https://5e.tools/spells.html#magic%20missile_phb), you can cast it using a 1st-level or a 2nd-level slot. Casting the spell doesn't remove it from your list of prepared spells.

You can change your list of prepared spells when you finish a long rest. Preparing a new list of wizard spells requires time spent studying your spellbook and memorizing the incantations and gestures you must make to cast the spell: at least 1 minute per spell level for each spell on your list.

#### Spellcasting Ability

Intelligence is your spellcasting ability for your wizard spells, since you learn your wizard spells through dedicated study and memorization. You use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a wizard spell you cast and when making an attack roll with one.

**Spell save DC** = 8 + Intelligence modifier + Proficiency Bonus

**Spell attack modifier** = Intelligence modifier + Proficiency Bonus

#### Ritual Casting

You can cast a wizard spell as a ritual if that spell has the ritual tag and you have the spell in your spellbook. You don't need to have the spell prepared.

#### Spellcasting Focus

You can use an [arcane focus](https://5e.tools/items.html#arcane%20focus_phb) as a spellcasting focus for your wizard spells.

#### Learning Spells of 1st Level and Higher

Each time you gain a wizard level, you can add two wizard spells of your choice to your spellbook. Each of these spells must be of a level for which you have spell slots, as shown on the Wizard table. On your adventures, you might find other spells that you can add to your spellbook (see "Your Spellbook").
##### Your Spellbook

The spells that you add to your spellbook as you gain levels reflect the arcane research you conduct on your own, as well as intellectual breakthroughs you have had about the nature of the multiverse. You might find other spells during your adventures. You could discover a spell recorded on a scroll in an evil wizard's chest, for example, or in a dusty tome in an ancient library.

A spellbook doesn't contain cantrips.

Copying a Spell into the Book. When you find a wizard spell of 1st level or higher, you can add it to your spellbook if it is of a spell level you can prepare and if you can spare the time to decipher and copy it.

Copying a spell into your spellbook involves reproducing the basic form of the spell, then deciphering the unique system of notation used by the wizard who wrote it. You must practice the spell until you understand the sounds or gestures required, then transcribe it into your spellbook using your own notation.

For each level of the spell, the process takes 2 hours and costs 50 gp. The cost represents material components you expend as you experiment with the spell to master it, as well as the fine inks you need to record it. Once you have spent this time and money, you can prepare the spell just like your other spells.

Copying from a Spell Scroll. A wizard spell on a spell scroll can be copied just as spells in spellbooks can be copied. When you copy a spell from a spell scroll, you must succeed on an Intelligence (Arcana) check with a DC equal to 10 + the spell's level. If the check succeeds, the spell is successfully copied. Whether the check succeeds or fails, the spell scroll is destroyed.

Replacing the Book. You can copy a spell from your own spellbook into another book—for example, if you want to make a backup copy of your spellbook. This is just like copying a new spell into your spellbook, but faster and easier, since you understand your own notation and already know how to cast the spell. You need spend only 1 hour and 10 gp for each level of the copied spell.

If you lose your spellbook, you can use the same procedure to transcribe the spells that you have prepared into a new spellbook. Filling out the remainder of your spellbook requires you to find new spells to do so, as normal. For this reason, many wizards keep backup spellbooks in a safe place.

The Book's Appearance. Your spellbook is a unique compilation of spells, with its own decorative flourishes and margin notes. It might be a plain, functional leather volume that you received as a gift from your master, a finely bound gilt-edged tome you found in an ancient library, or even a loose collection of notes scrounged together after you lost your previous spellbook in a mishap.

### Wizard Level 2: School of Illusion
You focus your studies on magic that dazzles the senses, befuddles the mind, and tricks even the wisest folk. Your magic is subtle, but the illusions crafted by your keen mind make the impossible seem real. Some illusionists—including many gnome wizards—are benign tricksters who use their spells to entertain. Others are more sinister masters of deception, using their illusions to frighten and fool others for their personal gain.

#### Illusion Savant
Beginning when you select this school at 2nd level, the gold and time you must spend to copy an illusion spell into your spellbook is halved.

#### Improved Minor Illusion
When you choose this school at 2nd level, you learn the [minor illusion](https://5e.tools/spells.html#minor%20illusion_phb) cantrip. If you already know this cantrip, you learn a different wizard cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

When you cast [minor illusion](https://5e.tools/spells.html#minor%20illusion_phb), you can create both a sound and an image with a single casting of the spell.