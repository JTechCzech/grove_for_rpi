# Initialization
Initialization command: lcd = __LCD1602(i2c_bus=#bus number, lines=#number of lines, dotsize=#size)__
<br>
For example, for __GPIO 2,3 the bus is 1__
<br>
For a __display which is 16x2__ the __lines will be 2__ and the __size will be 0x08__
# Use
## Display text
Display text: __lcd.print("#your text")__
<br>
or
<br>
To display a variable: __lcd.print(#variable name)__
## Cursor setting
Code to set cursor: __lcd.setCursor(#character,#row)__
<br>
__A character is a line space in the display width__ for example for a 16x2 display will 16 be the last character on the line
