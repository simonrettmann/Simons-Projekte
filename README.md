# Stundenprotokolle 12. Klasse 1. Halbjahr 

Informatik, Bl

David Borgmann, Simon Rettmann

## Stundenübersicht

<a href="#Stundevom3.8.2021"> 1. Stunde vom 3.8.2021 </a>

<a href="#Stundevom4.8.2021"> 2. Stunde vom 4.8.2021 </a>

<a href="#Stundevom10.8.2021"> 3. Stunde vom 10.8.2021 </a>

<a href="#Stundevom11.8.2021"> 4. Stunde vom 11.8.2021 </a>

<a href="#Stundevom24.8.2021"> 5. Stunde vom 24.8.2021 </a>


## <p> <h2> <a id="Stundevom3.8.2021"> Stunde vom 3.8.2021 </a> </h2>
In dieser ersten Informatikstunde des Schuljahres wurden die Erwartungen und der Ablauf des Kurses erklärt. Ein "GitHub" Account wurde angelegt und die Grundlagen gelegt. Gegen Ende der Stunde war außerdem noch Zeit vorhanden um sich bereits Gedanken über mögliche Projekte Gedanken zu machen. Allgemeiner Konsens war, dass es sich um ein arduinobasiertes "physical compuing Projekt" handeln soll. Aufgrund eines Roboterkurses waren nämlich schon kleine Mikrocontrollerkenntnisse vorhanden. Diskutierte Ideen waren ein adaptiv gesteuertet Eierkocher, ein regulierbarer und temperaturmessender Gaskocher und die Entwicklung eines Roboters, der Hindernisse wahrnimmt und auf diese reagiert. Nach Rücksprache mit Herrn Buhl wurde der regulierbare Gaskocher mit einigen Unterstufen ins Auge gefasst. Als Nachbereitung der Stunde wurden die Vorkenntnisse aufgefrischt und das bereits vorhandenen Material sortiert. Außerdem begann die Einarbeitungspahse in "GitHub". </p>

## <p> <h2> <a id="Stundevom4.8.2021"> Stunde vom 4.8.2021 </a> <h2>
Diese Informatikstunde startete mit der genaueren Planung und Aufgabenverteilung. Über einen gemeinsamen Leitfaden für die Stundenprotokolle wurde geredet. Anschließend wurden die Arduinokenntnisse weiter aufgefrischt. Die Gruppe startete mit dem Programmieren einer im Intervall blinkenden Lampe und begann an der Programmierung eines Potentiometers. Auch die Auswahl möglicher Gerätschaften stand auf der Tagesordnung. Im Fokus stand vor allem die Auswahl eines Thermometers.</p>
  
Bei der leuchtenden Lampe handelt es sich um eine weiße Leuchtdiode, die durch den Arduino gesteuert wird. Die Lampe ist jeweils eine Sekunde an und anschließend ausgeschaltet. Um eine Zerstörung der Diode zu verhindern, wurde ein Widerstand in den Kreislauf gebaut. 

### <h3> Bildergalerie <h3>
  
#### Programmcode für eine blinkende Leuchtdiode
<img width="250" height="200" alt="Code einer blinkenden Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/129033945-c0ebdcd1-c9e8-44f9-93c0-e8eba41e3662.png">

#### Steckplan für eine blinkende Leuchtdiode
<img width="250" height="200" alt="Steckplan für eine blinkende Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/129034053-222223fa-71a5-4461-b734-7e1efb53467b.png">
 
#### Bild des Versuchsaufbaus mit eingeschalteter Leuchtdiode
<img width="250" height="200" alt="Bild einer blinkenden Lampe" align="left" src="https://user-images.githubusercontent.com/88385654/128383828-eeb82b61-0753-48aa-b36b-35d966454e42.jpg">
  
  

## <p> <h2> <a id="Stundevom10.8.2021"> Stunde vom 10.8.2021 </a> <h2>
In dieser Doppelstunde wurden die ersten Arduinocodes auf dem Weg zum Projekt geschrieben. Fokussiert wurde sich auf die Temperaturmessung und anschließende Steuerung einer Leuchtdiode. Besonders bei diesem Teilschritt war die Abhängigkeit von zwei nötigen Bedingungen für das leuchten der Lampe: Das Thermometer musste einen höheren Wert als 30 °C messen und zusätzlich musste der Knopf gedrückt werden. Als nächsten Schritt wurde eine Servosteuerung programmiert. Auch die Rotation des Servo-Motors war erneut von dem Thermometer und dem Drücken des Knopfes abhängig. Zudem wurde ein arduinofähiges Thermoelement, welches besonders hohe Temperatur messen kann, bestellt. Die selbstgewählte Hausaufgabe war sich mit einem "Stepper Motor" auseinanderzusetzen. Dieses Einlesen soll Grundlage für die nächste Stunde sein. </p>

  
  ## <p> <h2> <a id="Stundevom11.8.2021"> Stunde vom 11.8.2021 </a> <h2>
Obwohl diese Informatikstunde leider aufallen musste, wurde diese dennoch genutz, um das Projetk nach vorne zu bringen. Um die Schaltpläne übersichtlicher darzustellen entschied sich das Team die Software "Fritzing" für die Erstelung digitaler Schaltpläne zu kaufen. "Fritzing" ermöglicht die Erstellung auf den Arduino zugeschnitte Schaltplanerstellung und hat viele Teile zu Verfügung. Die Einarbeitung in dieses Programm begann und die Schaltung der blinkenden Lampe und der Servoschaltung wurden digitalisiert.
Der Rest der Zeit wurde genutzt um einen Schrittmotor zu verstehen und anzusteuern. Für erste Programmierungsversuche reichte die Zeit leider nicht auf. Dieser nächste Schritt soll von zu Hause erreicht werden.
<img width="300" alt="Fritzing - Software zur Erstellung von digitalen Schaltplänen" align="right" src="https://user-images.githubusercontent.com/88385654/129033788-4786fe85-1819-4c0e-94bd-8bf5a4296798.png">
<p>
  
  ## <p> <h2> <a id="Stundevom24.8.2021"> Stunde vom 24.8.2021 </a> <h2>
Die Ansteuerung des Schrittmotors klappte zu Beginn der Stunde. Nach einiger Zeit wurde bemerkt, dass der Motor fühlbar sehr warm wurde. Nach einiger Recherche stellte sich heraus, dass der Motor auch ohne Bewegung Strom verwendet. Ein dementsprechender Sketch, als "if-Bedingungen", um den Motor von der Stromversorgung zu trennen, wenn er nicht in Verwendung ist, wurde geschrieben. 
<p>
