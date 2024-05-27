# Vökvun

_Árni & Katý_

## Kunnugleg vandræði, verkferlar og skipulag

Hver hefur ekki lent í því að vinna í (forritunar) verkefni og: 
  - Gleymt hvernig allt virkar?
  - Týnt forritsbútnum sínum?
  - Týnt rafmagnsteikningunni sinni?
  - Fyllst örvætingu og bræði?

## Lausnir og samvinna

Fyrir ekki svo löngu bjó Katý til kerfi til fyrir sjálfvirka vökvun á pottaplöntu.

Fyrir utan vatnsforðabúr og pottaplöntu, samanstendur verkefnið af eftirfarndi hlutum: 

- Ardunio Micro
- Rakaskynjara
- Vatnshæðarskynjara
- Rafmagnspumpu
- Rafrásarbretti með:
  - "Barreljack" tengi fyrir 5v straumgjafa
  - Mosfet til að straumfæða dæluna
  - LED ljósi til aðvörunar

Virknin var rifjuð upp og verkefnum skipt niður: 

- Katý sá um að finna réttu pinnan og skoða tengingar
- Árni skrifaði nýjan kóða

### Pinnar og tengingar

Katý: Setja inn punkta

Lentum í því að lausir vírar í tengi leiddu saman. Eftir að það var hreinsað, virkaði brettið eðlilega. 

### Kóði

Til að flýta fyrir skrifaði ég nýtt forrit í [Wokwi](https://wokwi.com/projects/398691701299876865). Wokwi hermirinn flýtir gríðarlega fyrir vinnu við Arduino verkefni. Á meðan Katý fann út úr pinnunum, notaði ég aðra pinna til bráðabirgða. 

Forritið 

```
const int soilSensor = A0;
const int floaterPin = A4;
const int ledPin = 13;
const int pumpPin = A5;

int waitTime = 5000;

int waterState = 0;
int motorTime = 3000;

int raki;
int rakaGildi = 250;


void setup() {
  Serial.begin(9600); // open serial port, set the baud rate as 9600 bps
  pinMode(floaterPin, INPUT);
  pinMode(ledPin, OUTPUT);
  pinMode(pumpPin, OUTPUT);
}

void loop() { 
  // Gefið er að ef það er nægt vatn, þá er staðan HIGH/true
  // og kerfið heldur áfram
  // Ef það vantar vatn, þá er staðan LOW/false, kveikt á viðvörunarljósi
  // kerfið bíður eftir næstu vatnsmælingu
  //waterState = digitalRead(floaterPin);
  waterState = 1;
  Serial.println(waterState);
  digitalWrite(ledPin, !waterState);

  if (waterState == true){
    Serial.println("Það er nægt vatn");

    // Athuga rakastig
    raki = analogRead(soilSensor);
    Serial.println(raki);

    // TODO: Aðlaga þetta að rétta skynjaranum!
    if (raki > rakaGildi){
      Serial.println("Litill raki");
      
      // Keyra dælu 
      // ATH: Skoða vel straumþörf á dælu. 
      // Mæli með að nota relay/transistor til að keyra dæluna. 
      Serial.println("Kveiki á dælu");
      digitalWrite(pumpPin, HIGH);
      delay(motorTime);
      Serial.println("Slekk á dælu");
      digitalWrite(pumpPin, LOW);

    } else {
      Serial.println("Nægur raki");
    }
  } else {
    Serial.println("Það vantar vatn");
  }

  // Bið á mili vatnsmælinga
  delay(waitTime);
}
```

Þessi forrits bútur var svo uppfærður með réttum pinnum og nægði til að koma Katý aftur á skrið. 