**Number of prepared Spells** `$= dv.span(dv.pages('"Nito/Zauber"').where(p => !p.file.name.contains("💀")).where(p => p.Level > 0).where(p => p.Level > 0).where(p => p.prepared).length)` / `=([[Nito, Character-Sheet]].level + [[Nito, Character-Sheet]].wisMod)`

## Combat Spells
```dataview
TABLE
	Level,
	Time,
	Range,
	Attack,
	Damage
FROM "Nito/Zauber"
WHERE
	(Type = "Dmg." or Type = "Debuff" or Type = "Buff" or Type = "Summon")
	and (prepared or Level = 0)
SORT Level
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
```

## All Spells
```dataview
TABLE
	Level,
	Rating,
	Type,
	Time,
	choice(prepared, "X", "") AS Prepared
FROM "Nito/Zauber"
```
