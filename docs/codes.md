# Codes

## СЭП выстрел

[Header] - [0ppppppp] - [ttdddd]
The 0 signies a shot packet, ppppppp is replaced with the 7-bit player ID, tt
is replaced with the team ID, and dddd is replaced with the damage value from
the lo okup table (see App endix A).


```
Raw result in microseconds - with leading gap rawData[30]: 
 -123850
 +2450,- 550
 + 600,- 600 + 600,- 550 + 650,- 550 + 650,- 550
 + 650,- 550 + 650,- 550 +1200,- 600 + 600,- 550
 + 650,- 550 + 650,- 550 + 650,- 550 + 650,- 550
 + 600,- 600 + 600
Sum: 19700
```
```
0, 0, 0, 0,
0, 0, 1, 0,
0, 0, 0, 0,
0, 0
```