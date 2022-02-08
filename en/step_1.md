To set the pins for multiple LEDs, use the following code:

--- code ---
---
language: python
filename: mood-check-in.py
line_numbers: false
line_number_start: 1
line_highlights: 
---
led_1 = LED(13)
led_2 = LED(9)
led_2 = LED(5)
--- /code ---

**Tip**: You should give your LED variables a meaningful name. For example, if each LED is a different colour then you could use the following code:

--- code ---
---
language: python
filename: mood-check-in.py
line_numbers: false
line_number_start: 1
line_highlights: 
---
red_led = LED(13)
green_led = LED(9)
pink_led = LED(5)
--- /code ---