# SPRING REVERB V2.5 ASSEMBLY REFERENCE
**Thanks for choosing our kits!**
This manual is written taking with the problems that we usually find in our workshops in mind.
Also the order is meant to make assembly as easy as possible.
Some steps are not obvious so even if you're an experienced DIYer, read the steps completely before
taking them.
If this is your first project, please read this article before you start assembling the kit: [www.befaco.org/howto/](http://www.befaco.org/howto/)

**May the luck be with you!**

## Main PCB (The small one)
**Open Main Board Bag A**
### RESISTORS
|Qty|Value|Code|Name on PCB|
|---|-----|----|-----------|
|2 |2.2 OHM|Red, red, black, silver, brown|R17, R18|
|2 |47 OHM |Yellow, violet, black, gold, brown |R57, R65|
|4 |470 OHM |Yellow, violet, black, black, brown |R35, R36, R48, R49|
|2 |560 OHM |Green, blue, black, black, brown |R60, R64|
|4 |680 OHM |Blue, gray, black, black, brown |R34, R38, R43, R46|
|2 |1k |Brown, black, black, brown, brown |R5, R61|
|1 |7k32 |Violet, orange, red, brown, brown |R41|
|11 |10k |Brown, black, black, red, brown |R2, R3, R4, R10, R12, R15, R16, R20, R22, R28, R29|
|4 |15k |Brown, green, black, red, brown |R39, R44, R45, R50|
|3 |47k |Yellow, violet, black, red, brown |R13, R30, R37|
|2 |56K |Green, blue, black, red, brown |R31, R32|
|1 |82k |Gray, red, black, red, brown |R52|
|14 |100k |Brown, black, black, orange, brown |R1, R21, R25, R26, R27, R40, R42, R47, R51, R53, R56, R62, R63, R67|
|3 |120k |Brown, red, black, orange, brown |R7, R54, R55|
|2 |150k |Brown, green, black, orange, brown |R8, R14|
|1 |200k |Red, black, black, orange, brown |R59|
|1 |220k |Red, red, black, orange, brown |R6|
|1 |560K |Green, Blue, Black, Orange, Brown |R11|
|7 |1M |Brown, black, black, yellow, brown |R9, R19, R23, R24, R33, R58, R66|

### DIODES
Solder the diodes respecting the polarity. Black or white line on the diode must be in the same place as white line on diode symbol on PCB silkscreen.

|Qty |Value |Name on PCB|
|----|------|-----------|
|6 |1N4148 |D1, D2, D3, D4, D5, D7|
|1 |1N5231 |D6|
|2 |1N5817 |(black color) D8, D9|

### FERRITE
Solder the two ferrite beads passing trough a recycled resistor leg and proceed as if it were a resistor. Ferrite beads don't have polarity.
The space for ferrites is a bit tight. Leave them a bit separated from the board to make them fit between power connector and diodes.

|Qty |Name on PCB|
|----|-----------|
|2 |FERRITE+, FERRITE|

### ICs
Place the sockets taking care of the orientation and solder them on IC1, IC2, IC3, IC4 and IC5. The orientation must match the PCB's drawing.
Place the five ICs on the sockets taking care of polarity. To do that the mark on front must match the mark on the socket and the PCB's silkscreen.

|Qty |Value |Name on PCB|
|----|------|-----------|
|2 |TL074/84 |IC1, IC5|
|2 |LM13700 |IC3, IC4|
|1 |TL072/82 |IC5|

### CAPACITORS
|Qty |Value |Code |Name on PCB|
|----|------|-----|-----------|
|3 |47p |47 |C5, C12, C17|
|4 |100p |101 |C4, C10, C16, C18|
|1 |330p |331 |C3|
|1 |1n |1n (Polyester) |C9|
|1 |15n| 15n (Polyester) |C8|
|11 |100n |104 |C2, C6, C7, C11, C13, C14, C15, C19, C20, C22, C24|

### ELECTROLYTIC CAPACITORS
Values written at the side of the capacitor. Mind polarity. Check positive terminal on board and make it match with long leg.

|Qty |Value |Code |Name on PCB|
|----|------|-----|-----------|
|3 |10µF |10µF |C1, C21, C23|

### TRANSISTORS
Be sure they are on proper position (same as the silkscreen on the PCB)

|Qty |Value |Name on PCB|
|----|------|-----------|
|1 |2N3904 |T1|
|6 |2N3906 |T2, T3, T4, T5, T6, T7|
|1 |BC517 |Q1|
|1 |BC516 |Q2|

### TRIMMERS
Solder the four 100k trimmers on Offset 1, 2, 3, 4 with the screw facing out of the PCB

### MALE PIN HEADERS
Place and solder the tree Male Pin Headers at silkscreen side, ensuring it is 90º from PCB. Shortest side of the pins is for soldering.

### POWER CONNECTOR
Solder the power connector ensuring the position is correct: it must must be on the silkscreen side with the pins facing out.

### RCA CONNECTORS
Place and solder the RCA connectors (same as the silkscreen on the PCB).

**RCA-OUT pcb (White conector) –--> IN-Tank-Reverb (White conector)
 RCA-IN pcb (Red conector) –--> OUT-Tank-Reverb (Red conector)**

## Control PCB
**Open Control Board Bag A**

### RESISTORS
|Qty |Value |Code |Name on PCB|
|----|------|-----|-----------|
|1 |180 Ohm |Brown, grey, Black,Black,Brown |R109|
|4 |1k |Brown, Black, Black, Brown, Brown |R101, R104, R106, R114|
|1 |2.7k |Red, Purple, Black,Brown,Brown |R102|
|3 |10k |Brown, Black, Black, Red, Brown |R103, R108, R112|
|4 |100k |Brown,Black,Black,Orange,Brown |R100, R110,R111,R113|
|2 |1M |Brown,Black,Black,Yellow,Brown |R105, R107|

### DIODES
Solder diodes respecting the polarity. Black line on the diode must be in the same place as white line on the diode PCB silkscreen.

|Qty |Value |Name on PCB|
|----|------|-----------|
|1 |1N4148 |D100|
|1 |1N5231 |D101|

### ICs
Place the sockets taking care of the orientation and solder them on IC100 and IC101. The orientation must match the PCB's drawing.
Place the five ICs on the sockets taking care of polarity. To do that the mark on front must match the mark on the socket and the PCB's silkscreen.

|Qty |Value |Name on PCB|
|----|------|-----------|
|1 |LM3914N |IC100|
|1 |TL072/82 |IC101|

### CAPACITORS
|Qty |Value |Code |Name on PCB|
|----|------|-----|-----------|
|2 |100n |104 |C101, C102|
|1 |680n |684 |C100|
|1 |10µF |10µF |C103|

### FEMALE PIN HEADERS
Place the three female pin headers and solder them ensuring it is 90º from PCB.

**Open Control Board Bag B**
### FADERS
Solder the faders in the side indicated by the drawing ensuring they are 90º from PCB.

|Qty |Name on PCB|
|----|-----------|
|2| |

### SPACERS
Place the two spacers on the holes using his the male side and facing to the resistor's side of the PCB. Then fix with the two 3mm nuts.

### Front pannel components mounting tips
Now we will proceed to mount Jacks, potentiometers, switches and LEDs. This part of assembly is
CRITICAL. Please be gentle and read carefully the instructions.
These components must NEVER be soldered until they are placed and/or totally screwed to the front panel.
This is so because of two reasons:

* The height of panel components is not exactly the same. Because of this, if not screwed properly
before soldering, they will not stay properly seated to the panel. This might cause mechanical torsions, reducing their life expectancy and in worst cases they will break.
* The second reason is that it is very difficult to hit the holes if panel is not positioned before soldering. In LEDs case they are almost impossible to place to the exact height without reference
of the front panel.

**Open MiniJacks bag**

## MINIJACKS
Place minijacks ensuring they are by the silkscreen side but don't solder them until the front panel is on place and with all nuts screwed to it. This way it's easier to solder them on the right position. Keep in mind that the front panel holes are quite narrow and is almost impossible to place it with all the components already soldered.
Caution: the switch nuts and the jack nuts looks the same but they are not and will not fit in each other's thread so don't mix them!

## POTENTIOMETER
Cut the little ledge on all three pots with cutting pliers as pictured:
Now place potentiometers on the PCB but... **don't solder them**

|Qty |Type |Name on PCB|
|----|-----|-----------|
|2 |Single (3pin) 100K |HPF, MIX|

## LEDs
Put LEDs on place taking care of the polarity. but don't solder them until the front panel is on place. This the only way to solder them on the right position.
Long Leg is the + and short is the minus. In the PCB the square hole is the minus and there is a + symbol to indicate you the right position.

|Qty |Name on PCB|
|----|-----------|
|1 |LED_01 Red|
|2 |LEDs_02. 03 Yellow|
|4 |LEDs_04, 05, 06, 07 Green|
|1 |Duoled|

## FRONT PANEL
Place the front panel moving a little the parts one by one if necessary until you fit them to the top. At this point a sharp tweezers can be helpful.

Screw in the next order: Minijacks and Pots.

Until all of them are flat and touching completely the panel. Then (finally) solder all of them. ; )

**Place the LEDs** in the panel holes making sure they are on the right level and proceed to solder them.

**Plug the PCB1 on the PCB2** using the pin headers and ensuring the two 3mm holes match the spacers. Screw both boards using two screws.

**Put the knobs** on the potentiometers and the caps on the switches/faders

**Plug the power ribbon cable**: The blue wire (negative) correspond to the pin number one of the connectors. The pin number one is indicated with a small triangle and usually with a line in your power bus.

## ADJUSTMENT PROCEDURE
We are going to calibrate the offset of the VCAs . Like this we will avoid CV signal to leak into audio signal.
To follow this procedure we will use an audio cable to connect to a sound system (not headphones) and listen how much CV signal is leaking into our audio. Then we will use trimmers to reduce this leaking to minimum.

Unplug all cables from front panel. Plug power connector. Connect “MIX” to your sound system (Turn the volume up after connecting, as the signal is pretty low. Be careful when connecting/disconnecting, you might damage your speakers).

### CV In calibration
  1. Plug an oscillator into “IN 1 CV”. Set Fader to max and DRY/WET pot to wet position. Turn the trimmer above TP1 until you find the setup with the minimum volume of the oscillator.
  2. Plug an oscillator into “IN 2 CV”. Set Fader to max and DRY/WET pot to wet position. Turn the trimmer above TP2 until you find the setup with the minimum volume of the oscillator.

### DRY/WET Calibration
This will be an iterative procedure between DRY and WET Positions. We will set each of them to get the minimum CV signal leaking, going back and forth until we get the best setup.

Plug an oscillator in “MIX CV”.

1. Set DRY/WET Potentiometer to DRY position. Turn the trimmer above TP3 until you find the setup with the minimum volume of the oscillator.
2. Set DRY/WET Potentiometer to WET position. Turn the trimmer above TP4 until you find the setup with the minimum volume of the oscillator.
3. Repeat steps 1 and 2 until you get the minimum volume in both of them.
4. Move DRY/WET potentiometer to check if you get louder leaking in any position. If so, gently tweak TP3 and TP4 until you get rid of it or minimize it.

**Enjoy!**
