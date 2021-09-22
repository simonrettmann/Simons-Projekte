# Stundenprotokolle 12. Klasse 1. Halbjahr 

Informatik, Bl

David Borgmann, Simon Rettmann

## Stundenübersicht
<td colspan="2"
    
<a href="#Stundevom3.8.2021"> 1. Stunde vom 3.8.2021 </a>

<a href="#Stundevom4.8.2021"> 2. Stunde vom 4.8.2021 </a>

<a href="#Stundevom10.8.2021"> 3. Stunde vom 10.8.2021 </a>

<a href="#Stundevom11.8.2021"> 4. Stunde vom 11.8.2021 </a>

<a href="#Stundevom24.8.2021"> 5. Stunde vom 24.8.2021 </a>

<a href="#Stundevom31.8.2021"> 6. Stunde vom 31.8.2021 </a>

<a href="#Stundevom1.9.2021"> 7. Stunde vom 1.9.2021 </a>

<a href="#Stundevom7.9.2021"> 8. Stunde vom 7.9.2021 </a>

<a href="#Stundevom8.9.2021"> 9. Stunde vom 8.9.2021 <a/>

<a href="#Stundevom14.9.2021"> 10. Stunde vom 14.9.2021 <a/>

<a href="#Stundevom15.9.2021"> 11. Stunde vom 15.9.2021 <a/>
  
<a href="#Stundevom21.9.2021"> 12. Stunde vom 21.9.2021<a/>
 
  </td>

## <p> <h2> <a id="Stundevom3.8.2021"> Stunde vom 3.8.2021 </a> </h2>
In dieser ersten Informatikstunde des Schuljahres wurden die Erwartungen und der Ablauf des Kurses erklärt. Ein "GitHub" Account wurde angelegt und die Grundlagen gelegt. Gegen Ende der Stunde war außerdem noch Zeit vorhanden um sich bereits Gedanken über mögliche Projekte Gedanken zu machen. Allgemeiner Konsens war, dass es sich um ein arduinobasiertes "physical compuing Projekt" handeln soll. Aufgrund eines Roboterkurses waren nämlich schon kleine Mikrocontrollerkenntnisse vorhanden. Diskutierte Ideen waren ein adaptiv gesteuertet Eierkocher, ein regulierbarer und temperaturmessender Gaskocher und die Entwicklung eines Roboters, der Hindernisse wahrnimmt und auf diese reagiert. Nach Rücksprache mit Herrn Buhl wurde der regulierbare Gaskocher mit einigen Unterstufen ins Auge gefasst. Als Nachbereitung der Stunde wurden die Vorkenntnisse aufgefrischt und das bereits vorhandenen Material sortiert. Außerdem begann die Einarbeitungspahse in "GitHub". </p>

## <p> <h2> <a id="Stundevom4.8.2021"> Stunde vom 4.8.2021 </a> <h2>
Diese Informatikstunde startete mit der genaueren Planung und Aufgabenverteilung. Über einen gemeinsamen Leitfaden für die Stundenprotokolle wurde geredet. Anschließend wurden die Arduinokenntnisse weiter aufgefrischt. Die Gruppe startete mit dem Programmieren einer im Intervall blinkenden Lampe und begann an der Programmierung eines Potentiometers. Auch die Auswahl möglicher Gerätschaften stand auf der Tagesordnung. Im Fokus stand vor allem die Auswahl eines Thermometers.</p>
  
Bei der leuchtenden Lampe handelt es sich um eine weiße Leuchtdiode, die durch den Arduino gesteuert wird. Die Lampe ist jeweils eine Sekunde an und anschließend ausgeschaltet. Um eine Zerstörung der Diode zu verhindern, wurde ein Widerstand in den Kreislauf gebaut. 

### <h3> Bildergalerie <h3>
  
#### Programmcode für eine blinkende Leuchtdiode
<img width="270" height="200" alt="Code einer blinkenden Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/129033945-c0ebdcd1-c9e8-44f9-93c0-e8eba41e3662.png">

#### Steckplan für eine blinkende Leuchtdiode
<img width="270" height="200" alt="Steckplan für eine blinkende Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/129034053-222223fa-71a5-4461-b734-7e1efb53467b.png">
 
#### Bild des Versuchsaufbaus mit eingeschalteter Leuchtdiode
<img width="270" height="200" alt="Bild einer blinkenden Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/128383828-eeb82b61-0753-48aa-b36b-35d966454e42.jpg"> 
  
## <p> <h2> <a id="Stundevom10.8.2021"> Stunde vom 10.8.2021 </a> <h2>
In dieser Doppelstunde wurden die ersten Arduinocodes auf dem Weg zum Projekt geschrieben. Fokussiert wurde sich auf die Temperaturmessung und anschließende Steuerung einer Leuchtdiode. Besonders bei diesem Teilschritt war die Abhängigkeit von zwei nötigen Bedingungen für das leuchten der Lampe: Das Thermometer musste einen höheren Wert als 30 °C messen und zusätzlich musste der Knopf gedrückt werden. 

Als nächsten Schritt wurde eine Servosteuerung programmiert. Auch die Rotation des Servo-Motors war erneut von dem Thermometer und dem Drücken des Knopfes abhängig. Zudem wurde ein arduinofähiges Thermoelement, welches besonders hohe Temperatur messen kann, bestellt. Die selbstgewählte Hausaufgabe war sich mit einem "Stepper Motor" auseinanderzusetzen. Dieses Einlesen soll Grundlage für die nächste Stunde sein. </p>
  

### <p> <h3> Bildergalerie </h3>
  
 #### Code einer Lampe mit zwei Bedingungen
  
  <img width="500" heigt="400" alt="Code Lampe mit 2 Bedingungen" align="left" src="https://user-images.githubusercontent.com/88385654/130635486-6a00e8b1-9567-4570-9895-76ba36357181.png">
  
#### Code der Servosteuerung mit zwei Bedingungen
  <img width="470" height="370" alt="Servosteuerung mit 2 Bedingungen" align="right" src="https://user-images.githubusercontent.com/88385654/130635862-4d983326-5c70-45b5-9170-a137690f4cbd.png">
  </p>
  
  ## <p> <h2> <a id="Stundevom11.8.2021"> Stunde vom 11.8.2021 </a> <h2>
Obwohl diese Informatikstunde leider aufallen musste, wurde diese dennoch genutz, um das Projetk nach vorne zu bringen. Um die Schaltpläne übersichtlicher darzustellen entschied sich das Team die Software "Fritzing" für die Erstelung digitaler Schaltpläne zu kaufen. "Fritzing" ermöglicht die Erstellung auf den Arduino zugeschnitte Schaltplanerstellung und hat viele Teile zu Verfügung. Die Einarbeitung in dieses Programm begann und die Schaltung der blinkenden Lampe und der Servoschaltung wurden digitalisiert.
Der Rest der Zeit wurde genutzt um einen Schrittmotor zu verstehen und anzusteuern. Für erste Programmierungsversuche reichte die Zeit leider nicht auf. Dieser nächste Schritt soll von zu Hause erreicht werden.
  </p> 
  
 #### <h4> Screenshot von Fritzing <h4>
<img width="300" alt="Fritzing - Software zur Erstellung von digitalen Schaltplänen" align="left" src="https://user-images.githubusercontent.com/88385654/129033788-4786fe85-1819-4c0e-94bd-8bf5a4296798.png">
  
  ## <p> <h2> <a id="Stundevom24.8.2021"> Stunde vom 24.8.2021 </a> <h2>
Die Ansteuerung des Schrittmotors klappte zu Beginn der Stunde. Mit einer passenden Library gelang es den Schrittmotor in verschiedenen Geschwindigkeiten sich um 360° zu drehen und anschließend in die andere Richtung zu drehen, bis der Startpunkt wieder erreicht wurde. 
Nach einiger Zeit wurde bemerkt, dass der Motor fühlbar sehr warm wurde. Nach einiger Recherche stellte sich heraus, dass der Motor auch ohne Bewegung Strom verwendet. Ein dementsprechender Sketch, als "if-Bedingungen", um den Motor von der Stromversorgung zu trennen, wurde versucht zu schreiben. In der Zeit der Stunde gelang dies allerdings nicht. Die Lösung dieses Problems soll nun von zu Hause gelöst werden. 
Eine weitere Problematik die sich eröffnete war die Ansteuerung des Servo Motors im Hinblick auf das weitere Profjekt. Um einen Gaskocher zu regulieren erfordert es mehr als eine Umdrehung. Problematisch ist, dass der Schrittmotor nur die Information des "Weiter" oder "Zurück" kennt, jedoch nicht seine genaue Position. In irgendeiner Form wird daher eine mathematische Lösung erfordert, die den Nullpunkt des Schrittmotors als Startpunkt definiert, von welchem aus dann Befehle im oder gegen den Uhrzeigersinn gegeben werden. Wie dieses Problem konkret gelöst werden kann ist bisher unklar. 
</p>
  
 #### <h4> Screenshot von Fritzing <h4>
  <img width="300" height="400" alt="Ansteuerung des Schrittmotors" align="left" src="https://user-images.githubusercontent.com/88385654/131680996-f6043d89-9102-4a8f-9ab9-bbe43314acf3.png">


  ## <p> <h2> <a id="Stundevom31.8.2021"> Stunde vom 31.8.2021 </a> <h2>
  Zu Beginn der Stunde, wurde das bestellte Thermometer angeschlossen. Die Gruppe entschied sich für ein auf Amazon erhätliches Thermometer, das für extrem hohe Temperaturen geeignet ist. Die Wahl fiel auf das "MAX6675". Link von Amazon: https://www.amazon.de/ANGEEK-MAX6675-thermocouple-Temperature-arduino/dp/B07X41RG6K/ref=sr_1_2_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=max6675&qid=1630502970&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE3WkxHNEVaR0RIODUmZW5jcnlwdGVkSWQ9QTAzODIyOTMxVUI3TVFJTVk4VzNZJmVuY3J5cHRlZEFkSWQ9QTA2ODY3NDQxUTUxRVNaSlU2QTdSJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== 
  
  Mit der Integration einer passenden Library für das Bauteil MAX6675, konnten im seriellen Monitor Temperaturwerte abgelesen werden. Damit die Funktion getestet werden konnte, gab es einen Extremtest mit einem Teelicht. Der Test war erfolgreich und die Werte stiegen, bzw. fielen je nachdem ob das Thermometer in die Flamme gehalten wurde oder nicht. 
 Anschließend arbeitete das Team an einem Code, der eine Temperaturbedingungen, mämlich ein Wert kleiner als 30 °C mit einer Bewegung des Steppmotors koppelte. Ziel für die nächste Stunde war es diesen Code fertigzustellen. 
  
  ## <p> <h2> <a id="Stundevom1.9.2021"> Stunde vom 1.9.2021 </a> <h2>
  Leider gelang die Fertigstellung nicht. Bei diesem recht anspruchsvollen Code, der einen wichtigen Teilschritt für das Projekt darstellt, ergaben sich viele kleinere Probleme. Teilweise waren dies Flüchtigkeitsfehler, wie die Auslassung eines Kommas, teilweise jedoch auch schwererwiegende Probleme, die innerhalb der Stunde nicht gelöst werden konnten. 
  Außerdem wurde noch der Versuchsaufbau als Schaltplan der Ansteuerung des Schrittmotors digitalisiert und zu den Protokollen hinzugefügt. 

  ## <p> <h2> <a id="Stundevom7.9.2021"> Stunde vom 7.9.2021 </a> <h2>
  Auch diese Doppelstunde am Nachmittag stand ganz im Fokus des "Debugging". Gemeinsam mit Herrn Buhl wurde nach Fehlern gesucht. Relativ frustrierend war es zu sehen, dass sich an immer neuen Stellen Probleme ergaben mit denen die Gruppe am Anfang nicht gerechnet hat. 
  Um die Fehlerquellen besser identifizieren und zu beheben können, erfolgte ein Rückschritt. Die Codes wurden wieder voneinander getrennt und einzeln auf Fehler abgesucht. Am Ende der Stunde klappte immerhin das Ansteuerung des Schrittmotors, der aber aus noch unerfindlichen Gründen zu wenig Kraft besaß. 
  
  ## <p> <h2> <a id="Stundevom8.9.2021"> Stunde vom 8.9.2021 </a> <h2>
  In dieser Stunde konnten nun alle Fehlerquellen endgültig behoben werden, sodass der Code nun in seiner endgültigen From vorliegt. 
  Erklärung der auftretenden Probleme:
    - Das Problem, dass eine der vier Spulen des Schrittmotors nicht angesteuert wurde, sodass ein "Zucken" des Motors zwar sichtbar war, dieser sich aber nicht drehte, ergab sich durch einen Defintionsfehler in der Syntaxschreibweise der Library. Ein Komma, welches zwei Parameter trennte, wurde vergessen.
    - Des Weiteren trat das Phänomen eines schwachen Drehmoments auf. Der Motor arbeitete wie gewünscht, jedoch wurden Leerschritte gemacht, sobald Kraft auf den Motor wirkte. Beheben lies sich das Problem, indem die Einstellung der Schrittart von einem "Fullstep" auf einen "Halfstep" umgestellt wurde. Da nun in acht Zwischenschritten, statt in vier Zwischenritten pro Schritt gearbeitet wird, hat der Motor mehr Kraft und das Risiko für einen Leerschritt wird gesenkt. 
    - Die Erwärumung des Motors wurde durch eine Veränderung im Code verhindert: Dazu wurde im "main loop" eine Bedingung hinzugefügt, welche überprüft, ob der Stepper arbeitet. 
    - Das Projekt eines arduinogesteuerten Gaskochers erfodert das Festlegen eine Startposition. Das liegt daran, dass der Gaskocher nur einen begrenzten Drehradius hat. Außerdem kennt der Schrittmotor nicht die beiden Zustände des Kochers, mämlich ob Gas fließt oder nicht. Damit dieses Problem behoben werden kann, muss ein Startpunkt definiert werden. Bei dem von uns verwendeten "move"-Befehls speicherte der Schrittmotor jedoch weder seine Startposition noch seine aktuelle Position. Lediglich die Anzahl der Schritte wurde vorgegeben. Durch einen neuen "moveTo"-Befehl, wurde diese Problematik gelöst. Nun wird sowohl der Startpunkt als auch die aktuelle Position gespeichert und die Distanz zu dem angesteuerten Ziel berechnet.
    
<details> 
    
    <summary> Arduino Code </summary>
    
```c
#include <AccelStepper.h>
#include "max6675.h"

int soPin = 4;
int csPin = 5;
int sckPin = 6;

float Temp;
int durchlaeufe;

int KnopfPin = 2;
bool Knopfzustand;
 
#define HALFSTEP 8
 
#define motorPin1 9
#define motorPin2 10
#define motorPin3 11
#define motorPin4 12

AccelStepper stepper1(HALFSTEP, motorPin1, motorPin3, motorPin2, motorPin4);

MAX6675 thermo(sckPin, csPin, soPin);
 
void setup()
{
  pinMode(KnopfPin, INPUT);
  Knopfzustand = digitalRead(KnopfPin);
  
  Serial.begin(9600);
  Serial.println("Start der Auslese");
  delay(1000);
  
  stepper1.setCurrentPosition(0);
  stepper1.setMaxSpeed(1000.0);
  stepper1.setAcceleration(1000.0);
  stepper1.setSpeed(1000);
} 
 
void loop()
{
  Knopfzustand = digitalRead(KnopfPin);
  Serial.println(Knopfzustand);
  
  float Temp = thermo.readCelsius();
  Serial.print("Temperatur in C =");
  Serial.println(Temp);

delay(300);

   if(Knopfzustand == 1) {
    stepper1.move(500);
    stepper1.runToPosition();
    stepper1.disableOutputs();
   }
         
 if(thermo.readCelsius() >= 50){
  stepper1.moveTo(0);
  stepper1.runToPosition();
  stepper1.disableOutputs();
  }
}
    
```
    
    </details>
        
  ## <p> <h2> <a id="Stundevom14.9.2021"> Stunde vom 14.9.2021 </a> <h2>
  Diese Informatikstunde musste leider ausfallen. Nachdem der Code in der letzten Stunde fertiggestellt wurde, hat sich die Gruppe dazu entschieden an anderer Stelle das Projekt nach vorne zu bringen. Es wurde sich darauf verständigt die Woche über ein Brainstorming zur Hardware des Gaskochers zu starten. Dieses Brainstorming sollte getrennt passieren, damit mögichst viele unterschiedlichen Ideen und Ansätze bei der Besprechung in der nächsten Woche vorgetragen werden. 
  
  ## <p> <h2> <a id="Stundevom15.9.2021"> Stunde vom 15.9.2021 </a> <h2>
  Diese Informatikstunde musste leider ausfallen. Das Brainstorming zur Hardware wurde, wie in der letzten Stunde festgelegt, von den Gruppenteilnehmern von zu Huase aus durchgeführt. 
  
  ## <p> <h2> <a id="Stundevom21.9.2021"> Stunde vom 21.9.2021 </a> <h2>
  In dieser Stunde wurde ein Brainstorming zu den verschiedenen Ideen zur technischen Durchsetzung des Projektes durchgeführt. Zu diesem Zwecke wurde eine MindMap erstellt. 
    
 <h4> MindMap zum arduinogesteuerten Gaskocher <h4>
    
<img alt="MindMap zum arduinogesteurten Gaskocher" src="https://user-images.githubusercontent.com/88385654/134305833-4a90c295-e816-4e00-a15e-3394e86445d0.png">

