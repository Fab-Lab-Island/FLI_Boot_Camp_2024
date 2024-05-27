# CircuitPython

Á þessari kynningu var farið yfir CircuitPython, kosti og galla. Einnig var farið yfir [lampaverkefni](https://github.com/Fab-Lab-Akureyri/Lampi) sem er í vinnslu hjá Fab Lab Akureyri. 

# Skref 1

- Device manager
  - Skoða hvaða COM port kubburinn er tengdur.

- Farið inn á https://circuitpython.org/board/seeeduino_xiao_rp2040/ 
  
  -Sækja .uf2 skrána

- Halda inni B(Boot) takkanum þegar kubburinn er settur í samband við tölvuna.
  - USB drif ætti að birtast
  - Setja inn firmware (copy & paste)
  - USB drif ætti að birtast eftir endurræsingu

- Til að forrita opna `code.py` skrána af USB drifinu í gegnum Windows File Explorer með t.d. Notepad eða Visual Studio Code
  - Byrjið að skrifa kóða
  - Vistið skrána og hún hleðst sjálfkrafa á kubbnum
 
- Fyrir samskipti við kubbinn á Windows má nota [Putty](https://www.putty.org/). Veljið rétt COM port (`Device manager -> Ports`) og hakið við `Serial`.

## Kóðabútur

Hér er kóði sem lætur NeoPxel díóðuna á brettinu (RP2040) blikka

```
import board
import digitalio
import time

led = digitalio.DigitalInOut(board.LED)
led.direction = digitalio.Direction.OUTPUT

while True:
    led.value = True 
    time.sleep(1)    # tími af
    led.value = False
    time.sleep(1)    #tími á

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
    time.sleep(1)
    led.value = False
    time.sleep(1)

    print("hello Akureyri og Ísafjörður")
 
```

## Hlekkir

- [CircuitPython](https://circuitpython.org/)
  - [Seeed XIAO RP2040](https://circuitpython.org/board/seeeduino_xiao_rp2040/)
  - [Seeed XIAO ESP32C3](https://circuitpython.org/board/seeed_xiao_esp32c3/)

- [Thonny](https://thonny.org/)
  - Python ritill

- [codewith.mu](https://codewith.mu/en/download)
   - Python ritill

- [Lampaverkefni](https://github.com/Fab-Lab-Akureyri/Lampi)

- Seeed XIAO ESP32C3

Er ekki með USB stuðningi, því þarf aðrar leiðir til að vinna með hann. Það er hægt í gegnum Mu & Thonny, sem og í gegnum [Web Workflow](https://learn.adafruit.com/getting-started-with-web-workflow-using-the-code-editor/overview)


