# json-store

This repo stores json used to represents Level from AlgoGame app.
Full Control list is:
```
  "controls": [	
    "forward",	  // Step forward
    "left",	      // Turn left
    "right",	  // Turn right
    "f1",	      // Play function 1
    "f2",	      // Play function 2
    "f3",	      // Play function 3
    "c1",	      // Action runned if player is on color 1 case
    "c2",	      // Action runned if player is on color 2 case	
    "c3",	      // Action runned if player is on color 3 case	
    "p1",	      // Paint case with color 1
    "p2",	      // Paint case with color 1
    "p3"	      // Paint case with color 1
  ],
```
Map is displayed this way for a 4 column map:
```
 -->  y axis
|
v   0   1   2   3
x
    4   5   6   7
a
x   8   9   10  11
i
s
```
0 represents an empty cell;
1, 2 , 3 are respectively filled cell with colors 1,  2 and 3.

Cursor direction may be:
`EAST WEST SOUTH NORTH `