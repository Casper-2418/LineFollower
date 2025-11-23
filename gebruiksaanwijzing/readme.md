# Gebruiksaanwijzing

### opladen / vervangen batterijen
Batterijen worden opgeladen met een lader die specifiek ontworpen is voor 18650 (Lithium) batterijen.
Voor de batterijen kunnen worden ingestoken of verwijderd moet er gecontroleerd worden of de hoofdschekelaar van de pcb uitstaat (naar buitenste stand van de schekalaar)

### draadloze communicatie
#### verbinding maken
We gebruiken een Hc-08, deze kan een signaal spanning aan van 3,2-6V op zijn TX & RX pinnen. En 3,2-6V op zijn VCC. 

Een Hc-08 werkt op BLE (Bluetooth low energy), deze is dus compatible voor zowel android als iphone apparaten.

De applicatie die gebruikt werdt om de commandos te sturen is "serial bluetooth terminal", is beschikbaar op de google playstore en zou ook op de iphone app store beschikbaar moeten zijn.

#### commando's
debug : debug
start : run on
stop  : zolang je een niet bekend commande typed zal hij stoppen
set cycle [µs]  : set cycle ...
set power [0..255]  : set power ...
set diff [0..1]  : set diff ...
set kp [0..]  set kp ...
set ki [0..]  set ki ...
set kd [0..]  set kd ...
calibrate black  : calibrate black
calibrate white  : calibrate white

### kalibratie
uitleg kalibratie  

### settings
De robot rijdt stabiel met volgende parameters: 
| KP | KI | KD | diff | Power | snelheid |
| 30 | 0.1 | 0.35 | 0.6 | 130 | 0.63m/S |

### start/stop button
uitleg locatie + werking start/stop button
