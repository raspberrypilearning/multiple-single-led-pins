Importeer LED uit de picozero-bibliotheek en stel vervolgens de pinnen in voor meerdere LED's, gebruik de volgende code:

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_numb_start: 1
line_highlights:
---
from picozero import LED

led_1 = LED(13) 
led_2 = LED(8) 
led_3 = LED(5)

--- /code ---

**Tip**: Geef je LED-variabelen een naam die je kunt onthouden. Bijvoorbeeld, als elke LED een andere kleur heeft, kun je de volgende code gebruiken:

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
rood_led = LED(13) 
groen_led = LED(8) 
roze_led = LED(5)

--- /code ---
