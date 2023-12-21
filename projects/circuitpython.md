# CircuitPython

Etv förum við yfir CircuitPython á næsta Bootcamp-i

- [Circuit python](https://circuitpython.org/) er útgáfa af micropython og er frá Adafruit    
  - [Niðuhald fyrir seeed RP2040](https://circuitpython.org/board/seeeduino_xiao_rp2040/)
    - [wiki.seeedstudio](https://wiki.seeedstudio.com/XIAO-RP2040/) 
- RP2040 er með full native usb port -> 
- [XIAO-RP2040-with-CircuitPython](https://wiki.seeedstudio.com/XIAO-RP2040-with-CircuitPython/)


# Skref 1

- Device manager
  - Skoða hvaða COM port kubburinn er tengdur.

- Farið inn á https://circuitpython.org/board/seeeduino_xiao_rp2040/ 
  -Sækja .uf2 skrána
  -Setja skjölin inn á kubbinn.
- Halda inni B takkanum þegar kubburinn er settur í samband við tölvuna til að geta hlaðið inn nýja Circuit Python firmware-inu
  - Setja inn firmware-ið  (copy og paste)

- Til að forrita opna code.py skrá í gegnum Windows File Explorer með t.d. Notepad eða Visual Studio
  - Og byrja að skrifa kóðann
  - Ekki þarf að flasha neitt heldur dugar að vista .py kóðann
 
- til að sjá hello world er hægt að nota [putty](https://www.putty.org/) og velja rétta COM PORTIÐ sem kubburinn er á (hægt að sjá í Device manager)

## kóði 

Hér er kóði sem lætur led díóðuna á brettinu blikka

```
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
Hér kóði sem segir halló og lætur Led blikka prentar halló Ísland, Akureyri og Ísafjörður.

```
print("Hello Iceland!")


import board
import digitalio
import time

led = digitalio.DigitalInOut(board.LED)
led.direction = digitalio.Direction.OUTPUT

while True:
    led.value = True
    time.sleep(0.8)
    led.value = False
    time.sleep(0.1)

    print("hello Akureyri og Ísafjörður")
 
```


## Annað þessu tengt

- [thonny.org](https://thonny.org/)
- Er ritill

- [codewith.mu](https://codewith.mu/en/download)
   - Mu  editor

- Skoða þetta betur...
  - Opna toml skrána, þar er ekkert inni
  - Þar er hægt að setja inn heiti wifi og aðgang að passwordi


