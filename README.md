# 3D-Scan-Guide-CR-scan-Reptor-

1. PC Anforderungen
2. CR Scan Software
3. Kalibrierung/ erste Schritte 

## 1. PC Anforderungen:

### Empfohlene Konfiguration (Windows):

Prozessor: Intel Core i7-Gen8 oder höher

Grafikkarte: Nvidia-Grafikkarte

RAM: 16 GB oder mehr

### Mindestanforderungen (Windows):

Prozessor: Intel Core i5-Gen8 oder höher

RAM: 8 GB oder mehr

### Empfohlene Konfiguration (macOS):

Prozessor: Apple M1/M2/M3 Serie

RAM: 16 GB oder mehr

macOS Version: 11.7.7 (Big Sur, Monterey, Ventura) oder höher

### Mindestanforderungen (macOS):

Prozessor: Intel Core i5-Gen8 oder höher

RAM: 8 GB oder mehr

macOS Version: 10.15.7 (Catalina, Big Sur, Monterey, Ventura) oder höher

## 2. CR Scan Software 

Hier ist die neuste version von CR Scan zu finden:

https://www.creality.com/pages/download-cr-scan-raptor

## 3. Kalibrierung/ erste Schritte 

### Wann sollte ich den Scanner Kalibrieren ?

#### - Bei Umgebungsveränderungen:
  
  Bei erster Benutzung an einem neuen Ort, bei Temperaturschwankungen (um mehr als 10 °C), Änderungen der Luftfeuchtigkeit oder Beleuchtung kann die Leistung des Scanners beeinträchtigt werden, wenn dieser nicht neu kalibriert wird.

#### - Bei Vibrationen oder Schlägen:

  Starke Vibratione oder Schläge sollten grundsätzlich vermieden werden und können die Präzision negativ beeinflussen. Im Transport sind diese jedoch oftmals unvermeidbar, weshalb eine anschließende Kalibrierung empfohlen wird.

#### - Nach Software Updates: 

#### - Bei aufälligen fehlern / Wartung:
  
   Nach einiger Zeit sollte eine Neue kalibrierung stadfinden auch wenn keiner der zuvor angesprochen punkte erfüllt ist dies sollte auch vorgenommen werden wenn starke Qalitäts eibusen zu erkennen sind.


### Erste schritte und Wie kalibriere ich den Scanner ?

- Der Scanner wird über die beiliegenden Kabel mit dem Pc und der externen Stromversorgung verbunden ( USB 3 empfohlen um stabiele Verbindung zu garantieren)

- Kalibrierungs-Board auf Schäden und Sauberkeit prüfen, beides kann die Präzision des Scanners negativ beeinflussen

- Die Kalibrierungsfunktion findet sich unter dem am oberen Bildschirmrand angezeigten Reiter Device. Sobald sie diese Starten werden sie mittels Schaubildern durch den Kalibrierungsprozess geführt

- Tipp: Konzentrieren Sie sich mehr auf den Bildschirm als auf das Brett und das eigentliche Gerät. Vor allem die grünen Kreise auf den Bildschirm sind wichtig da diese anzeigen, wie gut Ihre Ausrichtung ist.

- Je höher die Punktzahl, desto besser die Genauigkeit. Eine Punktzahl von über 90 wird angestrebt, um exakte Ergebnisse zu gewährleisten.

## Scannen

### Scannverfahren:

#### Blaulicht :

- Einsatzgebiete: Kleinteilige Objekte (z.B. Münzen, Bolzen) oder Objekte mit komplexen Geometrien
  
- Merkmale: Hohe Genauigkeit bis zu 0,02 mm, erfordert Marker für den Scanning-Prozess 
  
- Vorgehen: Für kleine Objekte können die Marker auf dem Scantisch platziert werden (z.B. beiliegende Scanning-Matte mit Markern), für größere Objekte sollten die Marker direkt auf der Oberfläche des Objekts angebracht werden

#### Infrarot Scanning 

- Einsatzgebiete: Größere Objekte wie Statuen oder menschliche Körper (150-2000 mm)

- Merkmale: Markerfreies Scannen möglich, unterstützt aber auch das Scannen mit Markern und Texturmerkmalen

- Vorteil: Ideal für Objekte, die schwieriger mit Blau-Licht gescannt werden können, wie beispielsweise sehr dunkle oder metallische Oberflächen

### Scanning einstellungen

- Diese sind je nach zu Scannenden Bauteil einzustellen und grundsätzlich sehr intuitiv. Zudem bietet die Software Viedeos und Voreinstellungen an, die diesen Prozess weiter vereinfachen.

- Bei zu starken Artefakten (Linien oder ähnlich Störungen, welche durch den Scanning-Prozess selbst entstehen) kann es hilfreich sein die Auflösung herunter zu fahren. Bei einer Auflösugn von 0.1 Sollten sich diese bereits sehr kontrolierbar sein.

- In der Nachbereitung sind Störungen oder Fehlscanns beheb bar aber es sollte möglichst darauf geachtet werden, diese von beginn an zu vermeiden da die Nachberarbeitung meist eitintensiv ist und die Präzision des Modells stark darunter leiden kann.


### Belichtung 

- Die Belichtung wird auf einem Infrarotbild an der Seite des Scanning-Interfaces angezeigt. Rot steht hierbei für Überbelichtet, und Blau für unterbelichtet.

- Für Blaulicht Scans sollte darauf geachtet werden, dass Marker und Linien auf dem Infrarotbild gut zu erkennen sind. Die Blaulicht-Linien dürfen auch rot erscheinen, jedoch der Rest des Bildes sollte sich weiterhin im bereich von Graustufen befinden.

- Dies bezieht sich auf den zu sacnnenden Bereich und Hilfsmarker nicht auf Bereiche, welche nicht gescannt werden sollen diese sind zu vernachlässigen.

### Abstand 

- Der passende Abstand wird seitlich durch eine farbige Skala dargestellt und gibt informationen darüber, ob man sich zu nah oder zu weit weg vom objekt befindet


### Scanns Verbinden / Ober und unterseite eines Objekts zusammen Führen

- Hierzu muss der zweite Scan aus dem Bearbeitungsbereich de dazugehörigen Ersten Scanns gestartet werden

  ![image](https://github.com/user-attachments/assets/de7d8167-bfd8-4c82-b2bc-70f6a398a29c)

- Die Zusammenführung kann manuell oder Automatisch durchgeführt werden. Im manuellen Modus werden gleichfarbige Kugeln auf den jeweils gleichen überlappenden Stellen der beiden Scanns platziert.
  
## Nachbearbeitung 

### Nachbearbeitung vereinfachen

- Grundsätzlich sollte darauf geachtet werden, dass die zu entfernenden Bereiche möglichst minimal und simpel gehalten werden. Z.B ist ein facher Tisch leichter zu enfehnen als komplexe geometrien weshalb sich im Scan-Bereich nur die benötigten Gegenstände befinden sollten.

- Für Ober- und Unterseiten scans empfhilt sich das zu scannende Objekt auf etwas zu stellen das eine kleiner Grundfläche besitzt so ensteht ein spalt zwischen Bauteil und Tisch welcher die Entfernung des tisches sehr einfach macht. Da die Automatische Entfehrnung der Tisches zum Zeitpunkt der Erstellung dieses Dokuments nur im Infrarotmodus Funktioniert.

- Zudem ist zu bedenken das mit jeden Nachbearbeitungsschritt immer Präzision verlohren geht.
  
#### Creality scann 

- Lasso / Pinsel hiermit können Bereiche markiert werden welche entfernt oder erhalten werden sollen

- Optimization Setting: Hier wird über die Sensibilität automatisch Punkte entfernt welche von der Punktwolke zu stark abweichen.

- Mesh Setting hier wird die Punktwollke in ein Mesh umgewandelt, hierbei kann eingestellt werden aus wie vielen Dreiecken das Model bestehen soll dies beeinflusst stark die Weiterverwendung der bauteils da Modelle mit sehr vielen Flächen sehr viel rechenleistung benötigen. Fusion 360 möchte für die meisten Operationen nicht mehr als 10 000.

#### Instant Meshes 

- Target Vertex Count: Hier können wieder die Anzahl der Flächen eingestellt werden
- Orientation Field / Position Field : Nehmen anpassungen an der Gitterstruktur vor. Durch welche das Bauteil nicht durch Dreiecke, sondern Vierecke dargestellt wird.

+ Durch das Andere erscheinungs bild ist der Scann in Programmen wie Fusion 360 meist besser zu erkennen und Boolsche operationen sehen sauberer aus.

- Download: https://github.com/wjakob/instant-meshes   ( Anmerkung: Instant Meshes wird nicht weiter entwickelt)

  ![image](https://github.com/user-attachments/assets/64918cb8-f604-4126-bc20-f84c12403246)

#### Meshmixer 

- Analysis: Hier können Scanns auf Größse geprüft werden und durch das Feature Inspector löcher welche im Scan auftreten, automatisch gefüllt werden um ein abgeschlossenes Modell zu erzeugen.

- Sculpt: dieses Feature eignet sich perfekt um Linienartefakte oder oberflächen auszubessern. Wichtig ist nur zu beachten sehr vorsichtig mit diesem Feature umzugehen da dies die Präzision wirklich stark belasten kann (weniger ist mehr).

- Download: https://meshmixer.com/download.html
![image](https://github.com/user-attachments/assets/42948e48-080e-412e-838e-dfce3a14a0e7)

#### Fusion 360 

-Unter dem Reiter Netz am oberen Bildschirmrand finden sich einige nützliche Features zur weiteren Bearbeitung und Vorbereitung zur weiteren Benutzung in Fusion 360  

##### Reduzieren : 
 ist ein Feature zur reduzierung der Anzahl an fächen aus welchen das Modell besteht. Hier stehen dem nutzer einige verschidene Möglichkeiten zur verfühgung.

Typen :  

- Toleran (Fächen werden zu einer fläche zusammengeführt ,wenn diese innerhalb der zuvor festgelgten winkel Toleranz zu einander stehen.)

- Proportion  (Die Flächen werden Proportional zu Ursprungsverteilung reduziert )
         
- Flächenanzahl (reduziert Flächen auf bestimmte Anzahl)

Proportion und Flächenanzahl können entweder Adaptiv (Anzahl der neuen Flächen, in einem Bereich, hängt von detailgrad der Ursprungsmodells ab) oder Einheitlich ausgeführt werden 

![image](https://github.com/user-attachments/assets/4b85f753-7dc0-4244-8ded-75dd0b3309a3)


##### Netz Kovertieren 
Vor diesem Prozess sollte immer gespeichert werden da es durchaus je nach Methode zu Abstürzen des Programms kommen kann!

-Facettiert: Hiermit kommt Fusion 360 im fall eines Scanns am besten klar. Dieses Feature eignet sich zu erstellen eines Referenzmodels 

-Prismatisch /Organisch: hierbei wird das Netz Modell versucht in ein Model aus Ganzen geometrien zu überführen ( z.B. Zylinder, Würfel)
Dies ist mit einem 3D-Scan als basis fast unmöglich und könnte Höchstensbei sehr einfachen geometrien genutz werden.
 Hingegen bei Netzmodellen welche zuvor in CAD entsanden sind (wie die Meisten Thingiversmodelle funktioniert diese sehr gut).

![image](https://github.com/user-attachments/assets/1d57320f-1d1e-4b9e-a6ea-c4ae6ea013ad)


