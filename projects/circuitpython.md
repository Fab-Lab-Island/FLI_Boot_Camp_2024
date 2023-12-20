# CircuitPython

Etv förum við yfir CircuitPython á næsta Bootcamp-i


Kóði sem lætur led díóðuna á brettinu blikka

```
# print("Hello World!")


import board
import digitalio
import time

led = digitalio.DigitalInOut(board.LED)
led.direction = digitalio.Direction.OUTPUT

while True:
    led.value = True 
    time.sleep(0.1)    # tími af
    led.value = False
    time.sleep(0.1)    #tími á
```
