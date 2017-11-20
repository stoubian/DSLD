# Dual Segment LED Display (DSLD)
A lib for arduino to display numbers on a ten pins dual segment LED display with common cathode

## Use
#### `initializeDSLD()`
Call the function `initializeDSLD()` when you want to initialize your arduino for pin configuration.
Typically it is done in the `setup()` method of your arduino project but can be called elsewhere.

#### `printValue(42)`
Now in your code when you want to send your number to the display you can use the `printValue(42)` function.
The value attended in that function is an integer.

#### Wiring layout
The pins used for the DSLD are :

| Pin |   Segment   |
|-----|-------------|
|  2  |      A      |
|  3  |      B      |
|  4  |      C      |
|  5  |      D      |
|  6  |      E      |
|  7  |      F      |
|  8  |      G      |
|  9  |  gnd1(left) |
| 11  | gnd2(right) |

You can modify it according to your needs.
The dot of the display is not used.

## Other
Feel free to contribute, fork, open issues & PRs.
This is my first C++ program.

## License
WTFPL

<a href="http://www.wtfpl.net/">
  <img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png" width="80" height="15" alt="WTFPL" />
</a>

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                  Version 2, December 2004 

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

 Everyone is permitted to copy and distribute verbatim or modified 
 copies of this license document, and changing it is allowed as long 
 as the name is changed. 

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

  0. You just DO WHAT THE FUCK YOU WANT TO.
