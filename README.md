# Project presentation
## 1.1 The idea
We wanted to create a robot with practical use, an interesting little robot that can be used in a person's daily life. In our childhood we used to play with manurelly controlled cars and Switsch etc.. So it sounds like a lot of fun to design and build your own little car and be able to control it with a controller.

Once we had assembled and programmed the body of the car, we were able to make the little robot drive straight, turn and reverse using the controller.

In addition to the basic driving functions, we wanted to add a few useful functions to the little robot, such as gripping. So we added a robot hand to one side of the car, which is also controlled by a controller. Now we can control the little robot to walk to a spot in the room, grab the target and bring it back to us.

Now a new question arises: is a robot that can only be controlled manually a real robot? Or is it just a machine?

For this reason, we have equipped our little robot with an automatic sweeping function. We built a vacuum robot part at the other end of the trolley.

Our little robot can now not only be controlled manually, drive and reach, but also has an automatic sweeping function that collects the LEGO pieces scattered on the floor.

## 1.2 Tasks
- Think about what characteristics a small robot must have and sketch them.
- Build prototypes based on sketches.
- Program the small robot.
- Test the small robot and optimize it.
- Document the process and the results of the work and share them with other participants.
## 1.3 Preparation
- Learn software (through https://stackoverflow.com, https://www.youtube.com)

# 2 Handware:
## 2.1 Materials:
     - LEGO® Education SPIKE™ Prime set (45678)
     - LEGO® Education SPIKE™ Prime expansion set (45681)
     - Controller (Sony PS4)
## 2.2 components used:
     - Elements, a light matrix, a distance sensor, 4 motors and a controller
  
       
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%201.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%202.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%203.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Kontrolle.JPG)

## 2.3 3D model to build
    - [File is in the folder Handware](https://github.com/XueruWang233/Lego/blob/main/Hardware/3D%20Model.io)
## 2.4 Construction
    - Side of the robot hand

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Roboterhand%203.JPG)

    - Side of the vacuum robot

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Sauberroboter%203.JPG)

# 3 Codes
## 3.1 Software
    - Mindstorms 51515 Robot Inventor (https://apps.microsoft.com/detail/9MTQ0N7W1D6X?hl=en-US&gl=DE)
## 3.2 Source file
    - [File is in the Codes folder](https://github.com/XueruWang233/Lego/blob/main/Codes/Projekt%201.lms)
## 3.3 Codes and their functions
- Manually controlled components (with the controller): When the side with the robot hand is used as the "head"(or so-called front) of the robot, the robot performs a series of actions and movements based on the human's use of the controller.
    - When R2 button is pressed, the robot moves forward.
    - When the D-pad left button is pressed, the robot turns left.
    - When the D-pad right button is pressed, the robot turns right.
    - When the R2 button is released, the robot stops.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Fahren(to%20front)%20and%20turn.png)

    - When the L2 button is pressed, the robot moves backwards.
    - If the left cross-control key is pressed, the robot turns left.
    - When the cross control right button is pressed, the robot turns right.
    - When the L2 button is released, the robot stops.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Ru%CC%88ckfahren%20und%20Abbigen.png)

    - Initialization：In the initial state, the manipulator is in the closed state and the Cat Meow sound effect is playing.
    - When triangle button is pressed, the robot hand opens.
    - When the robot hand is detected in an open state, the hand closes automatically or the robot hand grabs the object, and then the Cat Meow sound effect plays.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Initialisierung(closure)%20of%20Robothands.png)
  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Roboterhand%20kontrollieren.png)

- Automated components: When the side with the vacuum robot is used as the "head"(or so-called front) of the robot, the robot can sweep the Lego elements scattered on the floor under the robot.
    - When the circle button is pressed, the robot functions as a vacuum robot or starts sweeping automatically.
    - If the distance sensor detects an obstacle 30 cm away, the robot turns in a different direction to continue sweeping.
    - The Robot Vacuum Cleaner continues to work until the cross button is pressed.

 ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Programmierung_Sauberroboter.png)

# 4 Status Quo
- If the side of the robot hand is used as the front of the robot, the robot moves straight ahead, turns and moves backwards, depending on how the human operates the controls.

- If the side with the suction robot is used as the "head" (or so-called front) of the robot, the robot can sweep the Lego elements that are scattered on the floor under the robot.





# 1 Projektvostellung
## 1.1 die Idee
Wir wollten einen Roboter mit praktischem Nutzen schaffen, einen interessanten kleinen Roboter, der im täglichen Leben eines Menschen eingesetzt werden kann. In unserer Kindheit haben wir mit manurell kontrollierte Autos und Switsch usw. gespielt. Es klingt also nach einer Menge Spaß, ein eigenes kleines Auto zu entwerfen und zu bauen und es mit einem Controller steuern zu können.

Nachdem wir die Karosserie des Wagens zusammengebaut und programmiert hatten, konnten wir den kleinen Roboter mit Hilfe des Controllers geradeaus fahren, drehen und rückwärts fahren lassen.

Zusätzlich zu den grundlegenden Fahrfunktionen wollten wir dem kleinen Roboter ein paar nützliche Funktionen hinzufügen, wie zum Beispiel das Greifen. Also fügten wir an einer Seite des Wagens eine Roboterhand hinzu, der ebenfalls von einem Controller gesteuert wird. Jetzt können wir den kleinen Roboter so steuern, dass er zu einer Stelle im Raum läuft, das Ziel greift und es zu uns zurückbringt.

Nun stellt sich eine neue Frage: Ist ein Roboter, der nur manuell gesteuert werden kann, ein echter Roboter? Oder ist er nur eine Maschine?

Aus diesem Grund haben wir unseren kleinen Roboter mit einer automatischen Kehrfunktion ausgestattet. Wir haben ein Saugroboter-Teil an das andere Ende des Wagens gebaut. 

Unser kleiner Roboter kann jetzt nicht nur manuell kontolliert werden, zu fahren und greifen, sondern hat auch eine automatische Kehrfunktion, die die auf dem Boden verstreuten LEGO Teile einsammelt.
## 1.2 Aufgaben
- Überlege dir, welche Eigenschaften ein kleiner Roboter haben muss, und skizziere sie.
- Bauen Sie Prototypen anhand von Skizzen.
- Programmieren Sie den kleinen Roboter.
- Teste den kleinen Roboter und optimiere ihn.
- Dokumentieren Sie den Prozess und die Ergebnisse der Arbeit und teilen Sie sie mit anderen Teilnehmern.
## 1.3 Vorbereitung
- Software lernen (durch https://stackoverflow.com, https://www.youtube.com)
# 2 Handware:
## 2.1 Material:
     - LEGO® Education SPIKE™ Prime-Set (45678)
     - LEGO® Education SPIKE™ Prime-Erweiterungsset (45681)
     - Kontroller (Sony PS4)
## 2.2 genutzte Bestandteile:
     - Elemente, eine Lichtmatrix, ein Abstandsensor, 4 Motoren und ein Kontroller
  
       
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%201.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%202.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Standteile%203.png)
![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Kontrolle.JPG)

## 2.3 3D Model zu aufbauen
    - [Datei ist im Ordner Handware](https://github.com/XueruWang233/Lego/blob/main/Hardware/3D%20Model.io)
## 2.4 Konstruktion
    - Seite der Roboterhand

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Roboterhand%203.JPG)

    - Seite des Saugroboters

![](https://github.com/XueruWang233/Lego/blob/main/Hardware/Sauberroboter%203.JPG)

# 3 Codes
## 3.1 Software
    - Mindstorms 51515 Robot Inventor (https://apps.microsoft.com/detail/9MTQ0N7W1D6X?hl=en-US&gl=DE)
## 3.2 Source Datei
    - [Datei ist im Ordner Codes](https://github.com/XueruWang233/Lego/blob/main/Codes/Projekt%201.lms)
## 3.3 Codes und deren Funktionen
- Manuell kontrollierte Komponenten (mit dem Kontroller): Wenn die Seite mit der Roboterhand als "Kopf"(oder sog. Vorne) des Roboters verwendet wird, führt der Roboter eine Reihe von Aktionen und Bewegungen aus, die auf der Benutzung des Kontrollers durch den Menschen basieren.
    - Wenn R2-Taste gedrückt wird, fährt der Roboter vorwärts.
    - Wenn Steuerkreuz-links-Taste gedrükt wird, biegt der Roboter links ab.
    - Wenn Steuerkreuz-rechts-Taste gedrükt wird, biegt der Roboter rechs ab.
    - Wenn R2-Taste losgelassen wird, stoppt der Roboter.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Fahren(nach%20vorne)%20und%20Abbiegen.png)

    - Wenn L2-Taste gedrückt wird, fährt der Roboter rückwärts.
    - Wenn Steuerkreuz-links-Taste gedrükt wird, biegt der Roboter links ab.
    - Wenn Steuerkreuz-rechts-Taste gedrükt wird, biegt der Roboter rechs ab.
    - Wenn L2-Taste losgelassen wird, stoppt der Roboter.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Ru%CC%88ckfahren%20und%20Abbigen.png)

    - Initialisierung：Im Ausgangszustand befindet sich der Manipulator im Schließzustand und Soundeffekt Cat Meow abspielt.
    - Wenn Dreieck-Taste gedrückt wird, öffnet die Roboterhand.
    - Wenn die Roboterhand in einem offenen Zustand erkannt wird, schließt sich die Hand automatisch bzw. greift der Roboterhand die Sache.Dann spielt Soundeffekt Cat Meow ab.

  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Initialisierung(Verschluss)%20des%20Roboterhands.png)
  ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Roboterhand%20kontrollieren.png)

- automatisierte Komponenten: Wenn die Seite mit dem Saugroboter als "Kopf"(oder sog. Vorne) des Roboters verwendet wird, kann der Roboter die Lego-Elemente kehren, die auf dem Boden unter dem Roboter verstreut sind.
    - Wenn Kreis-Taste gedrückt wird, funktioniert der Roboter als ein Saugroboter bzw. beginnt der Roboter automatisch zu kehren.
    - Wenn der Abstandssensor ein 30 cm entferntes Hindernis erkennt, dreht sich der Roboter in eine andere Richtung, um weiter zu kehren.
    - Der Saugroboter arbeitet so lange, bis die Kreuz-Taste gedrückt wird.

 ![](https://github.com/XueruWang233/Lego/blob/main/Codes/Programmierung_Sauberroboter.png)

# 4 Status Quo
- Wenn die Seite der Roboterhand als Vorderseite des Roboters verwendet wird, fährt der Roboter geradeaus, dreht sich und fährt rückwärts, je nachdem, wie der Mensch die Steuerung bedient.

- Wenn die Seite mit dem Saugroboter als "Kopf"(oder sog. Vorne) des Roboters verwendet wird, kann der Roboter die Lego-Elemente kehren, die auf dem Boden unter dem Roboter verstreut sind.

# 5 Feedback und Reflexion
Mit diesem Projekt ist es uns gelungen, einen eigenen kleinen Roboter zu bauen. Er konnte die Funktionen erfüllen, die wir uns wünschten, und hatte einige lustige Elemente, wie z. B. das Rufen beim Öffnen und Schließen seiner Pfoten. Dadurch wurde unser kleiner Roboter lebendiger und nicht nur ein einfaches ferngesteuertes Auto oder eine Kehrmaschine, sondern unser Freund.

Wir haben dabei auch viel gelernt, angefangen bei der Mechanik, wie z. B. Gestänge, Getriebe und so weiter. Dann kam der Software-Teil, in dem wir etwas über andere Programmiersoftware als Python wie SPIKE und Mindstorms lernten.

Was wir noch verbessern können, ist das, dass unser kleiner Roboter, wenn er als Kehrmaschine benutzt wird, die Teile nicht auffangen kann, sondern dass sie hinten herauslaufen. Daher müssen wir einen weiteren Staubauffangbeutel für den kleinen Roboter hinzufügen.

Eine weitere Frage, die uns sehr interessiert, ist die bereits erwähnte, ob ein manuell gesteuerter Roboter als Roboter bezeichnet werden kann. Was genau ist die Definition eines Roboters? Auch dieser Frage werden wir in unseren weiteren Studien und Forschungen nachgehen;)

