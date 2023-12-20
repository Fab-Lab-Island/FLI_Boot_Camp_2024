# CircuitPython

Etv förum við yfir CircuitPython á næsta Bootcamp-i
##Skref##
Device manager
Circuit python.  -https://circuitpython.org/
Er útgáfa af micropython og er frá Adafruit

https://thonny.org/
Er ritill


https://circuitpython.org/downloads   
https://circuitpython.org/downloads?q=seeed

https://wiki.seeedstudio.com/XIAO-RP2040/ 
RP2040 er með full native usb port -> 

Farið inn á https://circuitpython.org/board/seeeduino_xiao_rp2040/ 

Sækja .uf2 skrána

Setja skjölin inn á kubbinn.

Setja inn firmware-ið 

Opna toml skrána, þar er ekkert inni
Þar er hægt að setja inn heiti wifi og aðgang að passwordi


Til að forrita opna code.py skrá 
Og byrja að skrifa

Ekki þarf að flasha neitt
https://wiki.seeedstudio.com/XIAO-RP2040-with-CircuitPython/





Kóði sem lætur led díóðuna á brettinu blikka

```
print("Hello World!")


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


til að sjá hello world er hægt að nota [putty](https://www.putty.org/)
