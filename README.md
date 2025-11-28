# Blinkprogram med Arduino IDE

## Översikt
Det klassiska **Blinkprogrammet** är ofta det första steget när man lär sig programmera en mikrokontroller. Programmet får en LED‑lampa att blinka med jämna intervall, vilket visar att koden fungerar på din NodeMCU via Arduino IDE.

## Mikroprocessor
NodeMCU bygger på **ESP8266**, en liten och billig WiFi‑mikroprocessor. Den används ofta i IoT‑projekt (Internet of Things) och kan programmeras via Arduino IDE, ett program med öppen källkod.

## Hämta blinkprogram
Blinkprogrammet finns i Arduino IDE under:  
`File` → `Examples` → `01.Basics` → `Blink`

## De två basfunktionerna i Arduino
- **setup()** – körs en gång när mikrokontrollern startar eller resetas.
- **loop()** – körs om och om igen i en evig loop så länge mikrokontrollern är på.

## Setup och Loop (Strukturfunktioner)
- I **setup()** anger vi vilken port som ska användas.  
- I **loop()** bestämmer vi hur ofta lampan ska blinka.

```cpp
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}
```

```cpp
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // HIGH tänder LED lampan
  delay(1000);                       // Hur lång intervall mellan blinkningar (I detta fallet 1000ms)
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                       // Hur lång intervall mellan blinkningar (I detta fallet 1000ms)
}

```

## Resultat
När programmet körs blinkar LED‑lampan på NodeMCU‑kortet med en sekunds intervall.  
Det visar att koden är korrekt uppladdad och att mikrokontrollern fungerar som den ska.  
