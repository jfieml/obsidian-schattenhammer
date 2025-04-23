#nito 

**Platin**: `=sum(nonnull(map(this.file.lists.text, (x) => number(regexreplace(x, "(.*([+-][0-9]+)P.*)|.*", "$2")))))` P
**Gold**: `=sum(nonnull(map(this.file.lists.text, (x) => number(regexreplace(x, "(.*([+-][0-9]+)G.*)|.*", "$2")))))` G
**Silber**: `=sum(nonnull(map(this.file.lists.text, (x) => number(regexreplace(x, "(.*([+-][0-9]+)S.*)|.*", "$2")))))` S
**Kupfer**: `=sum(nonnull(map(this.file.lists.text, (x) => number(regexreplace(x, "(.*([+-][0-9]+)C.*)|.*", "$2")))))` C
## Einnahmen/Ausgaben

- +90G +23S +8C : Initial
- +500P +1000G : Drachenhort (Belohnung)
- -110G : Sunburst Pendant
- -250G : 4 Elfenbeinstreifen für [[Legend Lore]]
- -500G : Räucherwerk für [[Legend Lore]]
- -8C : Essen + Trinkgeld
- +100P : Schulden aufgenommen von [[Leyla]]
- +125P : Schulden aufgenommen von [[Soe]]
- +350G : Verkauf meiner alten Rüstung
- -720P -400G : Kauf von [[Mithril Halbplatte]], Eilanfertigung im Wert von 7600 Gold
- -50G : Eine Arbeitswoche Kochkurs bei Tom