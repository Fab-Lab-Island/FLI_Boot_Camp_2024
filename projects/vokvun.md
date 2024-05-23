# Vökvun

Katý, vökvun

https://wokwi.com/projects/398691701299876865

```
const int soilSensor = 0;
const int floaterPin = 2;
const int ledPin = 4;
const int pumpPin = 8;

int waitTime = 5000;

int waterState = 0;
int motorTime = 3000;

int raki;
int rakaGildi = 500;


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
  waterState = digitalRead(floaterPin);
  digitalWrite(ledPin, !waterState);

  if (waterState == true){
    Serial.println("Það er nægt vatn");

    // Athuga rakastig
    raki = analogRead(soilSensor);

    // TODO: Aðlaga þetta að rétta skynjaranum!
    if (raki < rakaGildi){
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