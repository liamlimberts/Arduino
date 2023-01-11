# Stundenprotokolle 12. Klasse 2. Halbjahr

![bsp greenfoot](Desktop/Arduino_Projekt/Bilder/Stormarnschule_Github.jpg "Stormarnschule")

Stormarnschule 2022

Informatik, Bl

Von Patric Heil und Liam Limberts

## [1. Stunde, 11.01.2023](#1)
## [2. Stunde, 18.01.2023](#2)

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

### <a name="2"></a> Stunde vom 18.01.2023


