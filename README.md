# Stundenprotokolle 12. Klasse 2. Halbjahr

![bsp greenfoot](Desktop/Arduino_Projekt/Bilder/Stormarnschule_Github.jpg "Stormarnschule")

Stormarnschule 2022

Informatik, Bl

Von Patric Heil und Liam Limberts

## [1. Stunde, 11.01.2023](#1)
## [2. Stunde, 17.01.2023](#2)
## [3. Stunde, 18.01.2023](#3)
## [4. Stunde, 24.01.2023](#4)
## [5. Stunde, 25.01.2023](#5)
## [6. Stunde, 30.01.2023](#6)

### <a name="1"></a> Stunde vom 11.01.2023

In unserer ersten Doppelstunde nach den Winterferien, haben wir uns als aller erstes damit auseinandergesetzt, wie man eine LED, über den Arduino, zum leuchten bekommt. Dafür haben wir uns folgendes Video angeguckt https://www.youtube.com/watch?v=x8Nf0pDyDyQ&t=248. Das Video hat uns dann vermittelt, wie wir welche Komponenten auf dem Steckbrett einstecken müssen und wie man das Steckbrett mit dem Arduino verbindet. Da es danach leider noch nicht so funktionierte wie geplant, haben wir Philipp und Arvid um Hilfe gebeten, da diese ja bereits letztes Jahr mit dem Arduino gearbeitet haben. Mit denen haben wir dann folgenden Code überarbeitet,

#### void setup() {

####  pinMode(8, OUTPUT);
#### }

#### void loop() {
#### digitalWrite(8, HIGH);
####  delay(1000);
#### digitalWrite(8, LOW);
#### delay(1000);
#### }

denn die LED wollte noch nicht leuchten. Philipp und Arvid haben uns dann gesagt, dass die Zahl die man eingibt, beim OUTPUT und beim digitalWrite, mit der Zahl auf dem Arduino übereinstimmen muss,da wo man die Kabel reinsteckt. Danach hatten wir dann den folgenden Code.

#### void setup() {

####  pinMode(13, OUTPUT);
#### }

#### void loop() {
#### digitalWrite(13, HIGH);
#### delay(1000);
####  digitalWrite(13, LOW);
#### delay(1000);
#### }

Durch weiteres ausprobieren kam es dann dazu, dass wir 2 LEDs gleichzeitig zum blinken gebracht haben.
PS: Bei der dritten LED funktionierte es dann nicht mehr.

Am Ende der Doppelstunde haben wir uns dann noch Gedanken darüber gemacht, was wir in den Kommenden Wochen machen wollen. Dabei sind wir zu dem Entschluss gekommen, dass wir einen Helligkeitsmesser programieren wollen.

### <a name="2"></a> Stunde vom 17.01.2023
Heute haben wir uns mit einem Servo Motor beschäftigt. Dabei haben wir es geschafft, dass sich der Propeller dreht. Als wir dies geschafft hatten, haben wir versucht den Propeller schneller zu drehen, indem wir Parameter im Codegeändert haben. Als Hilfe haben wir uns ein Y Gegen Ende haben wir uns dann entschieden, uns mit einem Bewegeungsmelder zu befassen. Nächste Doppelstunde werden wir dann richtig mit unserem Projekt starten. 



Idee für die nächste Stunde: Bewegungsmelder
Unbekannt ist led blinckien lassern

### <a name="3"></a> Stunde vom 18.01.2023

In der heutigen Doppelstunde haben wir angefangen mit dem Bewegungsmelder zu arbeiten. Wir haben dazu verschieden YT-Videos zur Unterstützung hinzugezogen, um einen Sketch schreiben zu können und die einzelnen Komponenten richtig zu verbinden. Dennoch konnten wir am Ende der Doppelstunde keine Erfolge verzeichnen, da die LED, nicht auf Bewegungen reagiert hat bzw. angefangen hat zu leuchten. Dank Hernn Buhl konnten wir erkennen, wann genau der Bewegungsmelder, bewegungen erkennt und wann nicht.

### <a name="4"></a> Stunde vom 24.01.202

Heute haben wir uns weier mit dem Bewegungsmelder auseinander gesetzt. Dabei ging es und darum, den Bewegungsmelder so einzustellen, dass er die Bewegungen erkennt und dann die LED einschaltet. Leider funktionierte das nicht so wie gedacht. Darauf hin haben wir uns dann an Hernn Buhl gewendet, der uns versucht hat weiter zu helfen. Herr Buhl hatte neue Bewegungsmelder bestellt, in der Hoffnung das es mit denen dann funktioniert. Das Resultat, nach dem Versuch mit den neuen Bewegungsmeldern, war, anders als erhofft, dass die Bewegungsmelder immer noch nicht das taten was sie eigentlich sollten. Am Ende der Stunde erklärte sich Herr Buhl dann bereit, sich das ganze noch einmal anzugucken und uns dann am nächsten Tag damiut weiter zuhelfen. 

### <a name="5"></a> Stunde vom 25.01.2023
Der Bewegungsmelder hat zwar funktioniert,jedoch nicht präzise genug, wie wir gehofft hatten, deswegen haben wir uns dazu entschieden, ein anderes Projekt in Angriff zu nehmen. Wir haben uns schlussendlich für einen Radar entschieden, der Gegenstände auf dem Bildschirm abbilden kann. Die Idee dafür habe ich über eine Website (https://all3dp.com/de/1/beste-arduino-projekte/) bekommen, die verschiedene Arduino-Projekte präsentiert. In der zweiten Stunde haben wir dann schonmal den Servomotor, den Entfernungsmesser und das Arduino-Board miteinander verbunden.

### <a name="6"></a> Stunde vom 31.01.2023
fdf

