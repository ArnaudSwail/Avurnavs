
# Dates

## 08 AVRIL 2021

```
(?<day>\d\d?)\s+(?<month>(JANVIER|FEVRIER|MARS|AVRIL|MAI|JUIN|JUILLET|AOUT|SEPTEMBRE|OCTOBRE|NOVEMBRE|DECEMBRE))\s+(?<year>\d\d\d\d)
```

Exemple:
```
08 AVRIL 2021
```

## LE 120000 UTC AVR 21

```
(?<day>\d\d)(?<hour>\d\d)(?<min>\d\d)\sUTC\s(?<month>(JAN|FEV|MAR|AVR|MAI|JUI|JUI|AOU|SEP|OCT|NOV|DEV))\s(?<year>\d\d)
```

Exemple:
```
LE 120000 UTC AVR 21
```

## DU 03 AU 08 AVRIL 2021.

```
DU\s+\d\d\s+AU\s+\d\d\s+(?<month>(JANVIER|FEVRIER|MARS|AVRIL|MAI|JUIN|JUILLET|AOUT|SEPTEMBRE|OCTOBRE|NOVEMBRE|DECEMBRE))\s+\d\d\d\d
```

Exemple:
```
DU 03 AU 08 AVRIL 2021.
```

## DE 060915 UTC A 061015 UTC AVRIL 2021

```
DE\s+\d\d\d\d\d\d\s+UTC\s+A\s+\d\d\d\d\d\d\s+UTC\s+(?<month>(JANVIER|FEVRIER|MARS|AVRIL|MAI|JUIN|JUILLET|AOUT|SEPTEMBRE|OCTOBRE|NOVEMBRE|DECEMBRE))\s+(?<year>\d\d\d\d)
```

Exemple:
```
DE 060915 UTC A 061015 UTC AVRIL 2021
```

## DU 08/04/2021 A 20H00 AU 09/04/21 A 03H00 UTC

```
DU\s+(?<day>\d\d)/(?<month>\d\d)/(?<year>\d\d\d\d)\s+A\s+(?<hour>\d\d)H(?<min>\d\d)\s+AU\s+(?<month>\d\d)/(?<year>\d\d\d\d)\s+A\s+(?<hour>\d\d)H(?<min>\d\d)
```

```
DU 08/04/2021 A 20H00 AU 09/04/21 A 03H00 UTC
```

## Fin de validité du message
```
ANNULER CE MSG LE (?<day>\d\d)(?<hour>\d\d)(?<min>\d\d) UTC (?<month3>(JAN|FEV|MAR|AVR|MAI|JUI|JUI|AOU|SEP|OCT|NOV|DEV)) (?<year2>\d\d)
```

```
ANNULER CE MSG LE 110059 UTC AVR 21
```




