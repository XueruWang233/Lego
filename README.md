
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
    - Mindstorms
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


