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
	(Type = "Dmg." or Type = "Debuff" or Type = "Buff")
	and (prepared or Level = 0)
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
	(Type != "Dmg." and Type != "Debuff" and Type != "Buff")
	and (prepared or Level = 0)
```

## All Spells
```dataview
TABLE
	Level,
	Type,
	Time,
	choice(prepared, "X", "") AS Prepared
FROM "Nito/Zauber"
```
