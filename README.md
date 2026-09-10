# Morse-Code-Keyboard
A keyboard that types with one button, using morse code!

I started this project to make the most useless keyboard in existence >:) It uses Hack Club's very own CH32X035 devboard, a push button, an LED, and a 128x64 OLED to type letters into your computer using Morse Code. When it's not in typing mode, it acts as a Morse Code trainer!

The Morse Code Keyboard is assembled on a 20x80mm perfboard. The CH32X035 devboard reads the input from the button (long and short presses) and turns that into letters in Morse Code. The on-board LED lights up when the button is pressed to confirm the inputs. The 128x64 OLED displays the inputs (dots and dashes) the CH32X035 believes to have read and the translated letters. I may update to a 0.91" OLED in the future to make the design slimmer. 
