**Number of prepared Spells** `$= dv.span(dv.pages('"Nito/Zauber"').where(p => !p.file.name.contains("💀")).where(p => p.Level > 0).where(p => p.Level > 0).where(p => p.prepared).length)` / `=([[Nito, Character-Sheet]].level + [[Nito, Character-Sheet]].wisMod)`
## Spellslots

**Level I**
<input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;"><input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;">

**Level II**
<input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;"><input type="checkbox" style="width: 30px; height: 30px;">

**Level III**
<input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;"><input type="checkbox" style="width: 30px; height: 30px;">

**Level IV**
<input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;"><input type="checkbox" style="width: 30px; height: 30px;">

**Level V**
<input type="checkbox" style="width: 30px; height: 30px;"><input type="checkbox"  style="width: 30px; height: 30px;">

## Combat Spells
```dataview
TABLE
	Level,
	Type,
	Time,
	Range,
	Attack,
	Damage
FROM "Nito/Zauber"
WHERE
	(Type = "Dmg." or Type = "Debuff" or Type = "Buff" or Type = "Summon")
	and (prepared or Level = 0)
SORT Level ASC
```

## Other Spells
```dataview
TABLE
	Level,
	Time,
	Type,
	Range
FROM "Nito/Zauber"
WHERE
	(Type != "Dmg." and Type != "Debuff" and Type != "Buff" and Type != "Summon")
	and (prepared or Level = 0)
SORT Level
```

## Concentration Spells
```dataview
TABLE
	Level,
	Time,
	Type,
	Range
FROM "Nito/Zauber"
WHERE
	(startswith(Duration, "Concentration"))
	and (prepared or Level = 0)
```

---
## All Spells
```dataview
TABLE
	Level,
	Time,
	Rating,
	Type,
	choice(startswith(Duration, "Concentration"), "☑️", "") AS "Concentr.",
	choice(prepared, "☑️", "") AS Prepared
FROM "Nito/Zauber"
SORT Level ASC, Name ASC
```
