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

# 4 Status Quo
- Wenn die Seite der Roboterhand als Vorderseite des Roboters verwendet wird, fährt der Roboter geradeaus, dreht sich und fährt rückwärts, je nachdem, wie der Mensch die Steuerung bedient.

- Wenn die Seite mit dem Saugroboter als "Kopf"(oder sog. Vorne) des Roboters verwendet wird, kann der Roboter die Lego-Elemente kehren, die auf dem Boden unter dem Roboter verstreut sind.

# 5 Feedback und Reflexion
Mit diesem Projekt ist es uns gelungen, einen eigenen kleinen Roboter zu bauen. Er konnte die Funktionen erfüllen, die wir uns wünschten, und hatte einige lustige Elemente, wie z. B. das Rufen beim Öffnen und Schließen seiner Pfoten. Dadurch wurde unser kleiner Roboter lebendiger und nicht nur ein einfaches ferngesteuertes Auto oder eine Kehrmaschine, sondern unser Freund.

Wir haben dabei auch viel gelernt, angefangen bei der Mechanik, wie z. B. Gestänge, Getriebe und so weiter. Dann kam der Software-Teil, in dem wir etwas über andere Programmiersoftware als Python wie SPIKE und Mindstorms lernten.

Was wir noch verbessern können, ist das, dass unser kleiner Roboter, wenn er als Kehrmaschine benutzt wird, die Teile nicht auffangen kann, sondern dass sie hinten herauslaufen. Daher müssen wir einen weiteren Staubauffangbeutel für den kleinen Roboter hinzufügen.

Eine weitere Frage, die uns sehr interessiert, ist die bereits erwähnte, ob ein manuell gesteuerter Roboter als Roboter bezeichnet werden kann. Was genau ist die Definition eines Roboters? Auch dieser Frage werden wir in unseren weiteren Studien und Forschungen nachgehen;)

