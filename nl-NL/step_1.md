Importeer LED uit de picozero-bibliotheek en stel vervolgens de pinnen in voor meerdere LED's, gebruik de volgende code:

--- code ---
---
language: python filename: line_numbers: false line_numb_start: 1
line_highlights:
---
from picozero import LED

led_1 = LED(13) led_2 = LED(8) led_3 = LED(5)
--- /code ---

**Tip**: Geef je LED-variabelen een naam die je kunt onthouden. Bijvoorbeeld, als elke LED een andere kleur heeft, kun je de volgende code gebruiken:

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
red_led = LED(13) green_led = LED(8) pink_led = LED(5)
--- /code ---

***
Dit project werd vertaald door vrijwilligers:

[name]

[name]

[name]

Dankzij vrijwilligers kunnen we mensen over de hele wereld de kans geven om in hun eigen taal te leren. Jij kunt ons helpen meer mensen te bereiken door vrijwillig te starten met vertalen - meer informatie op [rpf.io/translate](https://rpf.io/translate).
