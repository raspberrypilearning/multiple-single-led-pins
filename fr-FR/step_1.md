Importe LED de la bibliothèque picozero puis définis les broches pour plusieurs LED, en utilisant le code suivant :

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

**Astuce** : Tu dois donner un nom significatif à tes variables LED. Par exemple, si chaque LED est d'une couleur différente, tu peux utiliser le code suivant :

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
rouge_led = LED(13) 
vert_led = LED(8) 
rose_led = LED(5)

--- /code ---
