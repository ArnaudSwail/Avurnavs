# Position

## 48-29.549N, 002-00.086W
```
(?<latDeg>\d\d)[-\s](?<latMin>\d\d)[,.](?<latSec>\d\d?\d?)(?<latHem>[NS]),? (?<lonDeg>\d?\d\d)[-\s](?<lonMin>\d\d)[,.](?<lonSec>\d\d?\d?)(?<lonHem>[WE])
```

Exemple: 
```
PSN: 48-29.549N, 002-00.086W
```

## DU 4420N AU 4428N DE LA COTE AU 00122W

```
(?<lat>\d\d\d\d[NS])|(?<lon>\d\d\d\d\d?[EW])
```

Exemple:
```
DU 4420N AU 4428N DE LA COTE AU 00122W
```
## ZONEX

```
(ZONEX (?<zone>\d\d\c?)[-\d\d\c*]+) 
```

```
(ZONEX 10-11) 
```