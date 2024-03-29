# Stundenprotokoll 12. Klasse 2. Halbjahr

![bsp greenfoot](Stormarnschule_Bild.png "Stormarnschule")

Stormarnschule 2023

Informatik, Bl

Von Patric Heil und Liam Limberts

## [1. Stunde, 11.01.2023](#1)
## [2. Stunde, 17.01.2023](#2)
## [3. Stunde, 18.01.2023](#3)
## [4. Stunde, 24.01.2023](#4)
## [5. Stunde, 25.01.2023](#5)
## [6. Stunde, 31.01.2023](#6)
## [7. Stunde, 01.02.2023](#7)
## [8. Stunde, 08.02.2023](#8)
## [9. Stunde, 15.02.2023](#9)
## [10. Stunde, 17.02.2023](#10)
## [11. Stunde, 22.02.2023](#11)
## [12. Stunde, 24.02.2023](#12)
## [13. Stunde, 01.03.2023](#13)
## [14. Stunde, 08.03.2023](#14)
## [15. Stunde, 10.03.2023](#15)



### <a name="1"></a> Stunde vom 11.01.2023

In unserer ersten Doppelstunde nach den Winterferien, haben wir uns als aller erstes damit auseinandergesetzt, wie man eine LED, über den Arduino, zum leuchten bekommt. Dafür haben wir uns folgendes Video angeguckt https://www.youtube.com/watch?v=x8Nf0pDyDyQ&t=248. Das Video hat uns dann vermittelt, wie wir welche Komponenten auf dem Steckbrett einstecken müssen und wie man das Steckbrett mit dem Arduino verbindet. Da es danach leider noch nicht so funktionierte wie geplant, haben wir Philipp und Arvid um Hilfe gebeten, da diese ja bereits letztes Jahr mit dem Arduino gearbeitet haben. Mit denen haben wir dann folgenden Code überarbeitet,

<details>
<summary> alter Code </summary>
  
#### void setup() {

####  pinMode(8, OUTPUT);
#### }

#### void loop() {
#### digitalWrite(8, HIGH);
####  delay(1000);
#### digitalWrite(8, LOW);
#### delay(1000);
#### }
  
</details>

denn die LED wollte noch nicht leuchten. Philipp und Arvid haben uns dann gesagt, dass die Zahl die man eingibt, beim OUTPUT und beim digitalWrite, mit der Zahl auf dem Arduino übereinstimmen muss,da wo man die Kabel reinsteckt. Danach hatten wir dann den folgenden Code.

<details>
<summary> überarbeiteter Code </summary>
  
#### void setup() {

####  pinMode(13, OUTPUT);
#### }

#### void loop() {
#### digitalWrite(13, HIGH);
#### delay(1000);
####  digitalWrite(13, LOW);
#### delay(1000);
#### }
  
</details>

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

In der Stunde am 31.01.2023 haben wir uns weiter mit dem Arduino auseinander gesetzt. Da wir uns bereits in der letzten Stunde umentschieden haben, von einem Bewegungsmelder hin zu einem Radar, welcher uns sagen kann ob da ein Gegenstand direkt vor ihm ist oder nicht. In dem folgenden Video https://www.youtube.com/watch?v=kQRYIH2HwfY , wird uns erklärt wie wir unser Projekt aufzubauen haben. Mit genau diesem Aufbau haben wir uns dann auseinander gesetzt, nachdem wir zu vor getestet haben, ob der Radar auch funktioniert. Den Aufbau wollen wir in der nächsten Stunde zu Ende bringen.

### <a name="7"></a> Stunde vom 01.02.2023

Eigentlich wollten wir heute unseren Aufbau zu Ende bringen und dann den Radar testen. Da Liam heute leider krank gewesen ist, und ich einen Arzttermin hatte, haben wir heute garnichts geschafft.

### <a name="8"></a> Stunde vom 08.02.2023
Heute haben wir uns mit der Installation von dem Entferungsmesser, auf den Servomotor beschäftigt. Der Servomotor, soll sich bestenfalls hin und her bewegen können, in einem 180 Grad Radius, damit der Entferungsmesser nicht nur in eine Richtung die Entferung messen kann. Wir haben also ein Konstrukt aus Pappe und Panzerglas gebastelt, womit die Kabel vom Entferungsmesser festgehalten werden und der entfernungsmesser senkrecht auf den Servomotor montiert wird. Da der Unterricht verspätet angefangen hat, konnten wir in der Stunde leider nicht mehr schaffen.

### <a name="9"></a> Stunde vom 15.02.2023
In der heutigen Einzelstunde habne wir versucht usn weiter mit unserme Projekt auseinander zu setzen nd die Fehler in unserem Programm zu beheben. Aufgrund der miserablen Hardware der Schule, gelang es uns jedoch leider nicht dieses Vorhaben umzusetzen. Kurz gesagt, wir spind nicht voran gekommen und haben somit nichts geschafft in dieser Stunde :(. 

### <a name="10"></a> Stunde vom 17.02.2023
Die Doppelstunde am 17.02.2023 ist aufgrund des Projektages leider ausgefallen.

### <a name="11"></a> Stunde vom 22.02.2023
Heute konnten wir mit unserem Projekt fortfahren, da Herrn Buhl freundlicherweise unseren Fehler mit dem Servomotor behoben hat. Jetzt dreht sich der Servomotor etwas schneller und ohne zwischendurch anzuhalten. Die restliche Stune haben wir versucht einen Fehler im Code zu beheben

### <a name="12"></a> Stunde vom 24.02.2023
In der Stunde am 24.02.2023 haben wir uns dazu entschieden, nach längeren rumprobieren, dass es besser wäre nocheinmal neu, mit einem neuen Code, anzufangen. Daher haben wir unsere bisherigen Erfolge gelöscht und unter https://www.electronics-lab.com/project/using-sg90-servo-motor-arduino/ und https://elektro.turanis.de/html/prj121/index.html neue Codes geunden, mit welchen wir arbeiten können. Nach einer kurzen Feinjustierung der Codes, sodass sie zusammen funktionieren, hat es dann auch endlich funktioniert. Jetzt dreht sich der Servo-Motor 180 Grad nach links und anschließend dann nach rechts. Und nun funktioniert auch der Entfernungsmesser, der uns jetzt Zentimetergenau sagen kann wie weit ein Objekt, von dem Messgerät entfernt ist. Unser Ziel istes in den nächsten Stunden, die Funktionen der einzelnen Komponenten zu kombinieren, um ein funktionierendes Radar zu kreieren. 

### <a name="13"></a> Stunde vom 01.03.2023
In unser heutigen einzelstunde haben wir uns damit auseinander gesetzt wie wir ein Radar vom Cuputer zeichnen lassen können, sodass dieses uns am Ende anzeigt, wo gerade was vom Sensor erkannt wird. Da wir leider nicht erfolgreich waren, werden wir uns am kommenden Freitag weiter damit auseinander setzten.

### <a name="14"></a> Stunde vom 08.03.2023
Am 08.03.2023 haben wir haben wir versucht unsere Fehler weiter zu verringern, leider jedoch mit wenig Erfolg. Wir haben versucht einen Radar zu programmieren und diesen Radar dann kompatibel mit unseren bisherigen Code zusammen zu fügen, sodass das dann beides Parallel zu einander laufen kann. Das hat leider nicht funktioniert, weshalb wir dann am Ende der Stunde uns dazu entschieden haben die Idee mit dem Radar komplett zu verwerfen und uns auf eine Digitakeanzeige zu konzentrieren. 
Das werden wir jetzt in de rnächsten Stunde ins Visiert nehmen und versuchen schnellst möglich umzusetzen.

### <a name="15"></a> Stunde vom 10.03.2023
In der Doppelstunde am 10.03.2023 haben wir, wie bereits am 08.03.2023 erwähnt, damit begonnen uns damit auseinander zusetzten wie wir ein LCD Display mit dem Arduino und dem Entfernungsmesser verbinden können. Bevor wir uns damit jedoch auseinander setzen konnten, mussten wir erst mal einen Weg finden wie wir Arduino starten können. Dafür haben wir dann unter folgendem Link https://docs.arduino.cc/software/ide-v1/tutorials/PortableIDE Arduino Portable heruntergeladen, um dann im nachhinein erstmal ewig warten zu dürfen bis Arduino heruntergeladen war. Währenddessen haben wir bereits den Aufbau ohne Entfernungsmesser fertiggestellt. Den Aufbau haben wir unter folgendem Link gefunden https://polluxlabs.net/arduino-tutorials/ein-lcd-display-am-arduino-anschliessen/.
