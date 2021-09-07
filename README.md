# Stundenprotokolle 12. Klasse 1. Halbjahr 

Informatik, Bl

David Borgmann, Simon Rettmann

## Stundenübersicht

<a href="#Stundevom3.8.2021"> 1. Stunde vom 3.8.2021 </a>

<a href="#Stundevom4.8.2021"> 2. Stunde vom 4.8.2021 </a>

<a href="#Stundevom10.8.2021"> 3. Stunde vom 10.8.2021 </a>

<a href="#Stundevom11.8.2021"> 4. Stunde vom 11.8.2021 </a>

<a href="#Stundevom24.8.2021"> 5. Stunde vom 24.8.2021 </a>

<a href="#Stundevom31.8.2021"> 6. Stunde vom 31.8.2021 </a>

<a href="#Stundevom1.9.2021"> 7. Stunde vom 1.9.2021 </a>

<a href="#Stundevom7.9.2021"> 8. Stunde vom 7.9.2021 </a>

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
  
 #### Screenshot von Fritzing
<img width="300" alt="Fritzing - Software zur Erstellung von digitalen Schaltplänen" align="left" src="https://user-images.githubusercontent.com/88385654/129033788-4786fe85-1819-4c0e-94bd-8bf5a4296798.png">
</p>
  
  ## <p> <h2> <a id="Stundevom24.8.2021"> Stunde vom 24.8.2021 </a> <h2>
Die Ansteuerung des Schrittmotors klappte zu Beginn der Stunde. Mit einer passenden Library gelang es den Schrittmotor in verschiedenen Geschwindigkeiten sich um 360° zu drehen und anschließend in die andere Richtung zu drehen, bis der Startpunkt wieder erreicht wurde. 
Nach einiger Zeit wurde bemerkt, dass der Motor fühlbar sehr warm wurde. Nach einiger Recherche stellte sich heraus, dass der Motor auch ohne Bewegung Strom verwendet. Ein dementsprechender Sketch, als "if-Bedingungen", um den Motor von der Stromversorgung zu trennen, wurde versucht zu schreiben. In der Zeit der Stunde gelang dies allerdings nicht. Die Lösung dieses Problems soll nun von zu Hause gelöst werden. 
Eine weitere Problematik die sich eröffnete war die Ansteuerung des Servo Motors im Hinblick auf das weitere Profjekt. Um einen Gaskocher zu regulieren erfordert es mehr als eine Umdrehung. Problematisch ist, dass der Schrittmotor nur die Information des "Weiter" oder "Zurück" kennt, jedoch nicht seine genaue Position. In irgendeiner Form wird daher eine mathematische Lösung erfordert, die den Nullpunkt des Schrittmotors als Startpunkt definiert, von welchem aus dann Befehle im oder gegen den Uhrzeigersinn gegeben werden. Wie dieses Problem konkret gelöst werden kann ist bisher unklar. 
<p>
 <p> #### Screenshot von Fritzing
  <img width="300" height="400" alt="Ansteuerung des Schrittmotors" align="left" src="https://user-images.githubusercontent.com/88385654/131680996-f6043d89-9102-4a8f-9ab9-bbe43314acf3.png"> </p>


  ## <p> <h2> <a id="Stundevom31.8.2021"> Stunde vom 31.8.2021 </a> <h2>
  Zu Beginn der Stunde, wurde das bestellte Thermometer angeschlossen. Die Gruppe entschied sich für ein auf Amazon erhätliches Thermometer, das für extrem hohe Temperaturen geeignet ist. Die Wahl fiel auf das "MAX6675". Link von Amazon: https://www.amazon.de/ANGEEK-MAX6675-thermocouple-Temperature-arduino/dp/B07X41RG6K/ref=sr_1_2_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=max6675&qid=1630502970&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE3WkxHNEVaR0RIODUmZW5jcnlwdGVkSWQ9QTAzODIyOTMxVUI3TVFJTVk4VzNZJmVuY3J5cHRlZEFkSWQ9QTA2ODY3NDQxUTUxRVNaSlU2QTdSJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== 
  
  Mit der Integration einer passenden Library für das Bauteil MAX6675, konnten im seriellen Monitor Temperaturwerte abgelesen werden. Damit die Funktion getestet werden konnte, gab es einen Extremtest mit einem Teelicht. Der Test war erfolgreich und die Werte stiegen, bzw. fielen je nachdem ob das Thermometer in die Flamme gehalten wurde oder nicht. 
 Anschließend arbeitete das Team an einem Code, der eine Temperaturbedingungen, mämlich ein Wert kleiner als 30 °C mit einer Bewegung des Steppmotors koppelte. Ziel für die nächste Stunde war es diesen Code fertigzustellen. 
  
  ## <p> <h2> <a id="Stundevom1.9.2021"> Stunde vom 1.9.2021 </a> <h2>
  Der in der letzten Stunde begonne Code wurde fertiggestellt. (Bild vom Code)
  Außerdem wurde noch der Versuchsaufbau als Schaltplan der Ansteuerung des Schrittmotors digitalisiert und zu den Protokollen hinzugefügt. 

  ## <p> <h2> <a id"Stundevom7.9.2021"> Stunde vom 7.9.2021 </a> <h2>
  
