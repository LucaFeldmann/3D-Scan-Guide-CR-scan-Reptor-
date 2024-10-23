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
  
  Bei erster benutzung an einem neuen Ort, Temperaturschwankungen (um mehr als 10 °C), Änderungen der Luftfeuchtigkeit oder Beleuchtung kann die Leistung des Scanners beeinträchtigt werden wenn dieser nicht neu kalibriert wird.

#### - Bei Vibrationen oder Schlägen:

  Starke vibratione oder Schläge sollten gruntsätzlich vermiden werden und können die Präzision negativ beeinflussen. Im transport sind diese jedoch offtmals unvermeidbar weshalt eine anschliesende Kalibrierung empfohlen wird.

#### - Nach Software Updates: 

#### - Bei aufälligen fehlern / Wartung:
  
   Nach einiger Zeit sollte eine Neue kalibrierung stadfinden auch wenn keiner der zuvor angesprochen punkte erfüllt ist dies sollte auch vorgenommen werden wenn starke Qalitäts eibusen zu erkennen sind.


### Erste schritte und Wie kalibriere ich den Scanner ?

- Der Scanner wird über die beiligenden Kabel mit dem Pc und der externen stromversorgung verbunden ( USB 3 empfohlen um stabiele verbindung zu garantieren)

- Kalibrierungs Board auf schäden und sauberkeit prüfen beides kann die Präzision des Scanners negativ beeinflussen

- Die kalibrierungs funktion findet sich unter dem am oberen bildschirm rand angezeigten reite Divice. Sobald sie diese Starten werden sie mittels schaubilder durch den Kaliebrierungs prozess geführt

- Tipp: Konzentrieren sie sich mehr auf den Bildschirm als auf das brett und das eigentliche geräht. Vorallem die grünen Kreise auf den bildschirm sind wichtig da diese anzeigen wie gut ihre ausrichtung ist.

- Je höher die Punktzahl, desto besser die Genauigkeit. Eine Punktzahl von über 90 wird angestrebt um exakte Ergebnisse zu gewährleisten.

## Scannen

### Scannverfahren:

#### Blaulicht :

- Einsatzgebiete: Kleinteilige Objekte (z.B. Münzen, Bolzen) oder Objekte mit komplexen Geometrien
  
- Merkmale: Hohe Genauigkeit bis zu 0,02 mm, erfordert Marker für scanning prozess 
  
- Vorgehen: Für kleine Objekte können die Marker auf dem Scantisch platziert werden (z.B. beiligende scanning Matte mit Markern) , für größere Objekte sollten die Marker direkt auf der Oberfläche des Objekts angebracht werden

#### Infrarot Scanning 

- Einsatzgebiete: Größere Objekte wie Statuen oder menschliche Körper (150-2000 mm)

- Merkmale: Markerfreies Scannen möglich, unterstützt aber auch das Scannen mit Markern und Texturmerkmalen

- Vorteil: Ideal für Objekte, die schwieriger mit Blau-Licht gescannt werden können, wie beispielsweise sehr dunkle oder metallische Oberflächen

### Scanning einstellungen

- Diese sind je nach zu Scannenden Bauteil einzustellen und grundsätzlich sehr intuitiv. Zudem bietet die Software Viedeos und Voreinstellungen an die diesen Prozess weiter vereinfachen.

- Bei zu Starken Artefakten ( linien oder ähnlich Störungen welche durch den sacanning Prozess selbst entstehen) kann es hilfreich sein die Auflösung herunter zu fahren. Bei einer auflösugn von 0.1 Sollten sich diese bereits sehr kontrolierbar sein.

- In der Nachbereitung sind Störungen oder Fehlscanns beheb bar aber es sollte möglichst darauf geachtet werden diese von beginn an zu vermeiden da die Nachberarbeitung meist Zeit intensiv ist und die Prazison des models stark darunter leiden kann.


### Belichtung 

- Die Belichtung wird auf einem Infrarot bild an der Seite des scanning interfaces angezeigt. Rot steht hierbei für Überbelichtet und Blau für unterbelichtet.

- Für Blaulicht Sacnns sollte darauf geachtet werden das Marker und linien auf dem Infrarotbild gut zu erkennen sind. Die Blaulicht linien dürfen auch rot erscheinen jedoch der rest des bildes sollte sich weiterhin im bereich von Graustufen befinden.

- Diese bezieht sich auf den zu sacnnenden Bereich und Hilfs Marker nicht auf bereiche welche nicht gescannt werden sollen diese sind zu vernachlässigen.

### Abstand 

- Der Passende abstand wird seitlich durch eine Farbige Skala dargestellt und gibt informationen darüber ob man sich zu nah oder Zu weit weg vom objekt befindet


### Scanns Verbinden / Ober und unterseite eines Objekts zusammen Führen

- Hierzu muss der Zweite Scann aus dem Bearbeitungs bereich de dazugehörigen Ersten Scanns gestartet werden

  ![image](https://github.com/user-attachments/assets/de7d8167-bfd8-4c82-b2bc-70f6a398a29c)

- Die zusammen Führung kann Manuel oder Automatisch durchgeführt werden. Im manuellen modus werden gleichfarbige Kugeln auf den jeweils gleichen überlappenden Stellen der beiden Scanns plazieret.
  
## Nachbearbeitung 

### Nachbearbeitung vereinfachen

- Grundsätzlich sollte darauf geachtet werden das die zu enfehrnenden Bereiche möglichst minimal und Simpel gehalten werden. Z.B ist ein facher Tisch leichter zu enfehnen als Komplexe geometrien weshalb sich im Scannbereich nur die benötigten gegenstände befinden sollten.

- Für Ober- und Unterseiten scans empfhilt sich das zu scannende objdekt auf etwas zustellen das eine kleiner Grundfläche besitzt so ensteht ein spalt zwischen Bauteil und Tisch welches die Entfehrnung des tisches sehr einfach macht. Da die Automatische Entfehrnung der Tisches zum Zeitpunkt der Erstellund dieses Dokumentes nur im Infrarotmodus Funktioniert.

- Zuden ist zu bedenken das mit jeden Nachbearbeitungsschritt immer Präzison verlohren geht.
  
#### Creality scann 

- Lasso / Pinsel hiermit können bereiche makiert werden welche enfehrnt oder erhalten werden sollen

- Optimization Setting hier würd über sie sensiebelität automatich Punkte enfehrnt welche von der Punktwollte zu stark abweichen.

- Mesh Setting hier wird die Punktwollke in ein Mesh umgewandelt, hierbei kann eingestellt werden aus wievielen dreiecken das Model bestehen soll dies beeinflusst stark die Weiter verwendung der bauteils da Modelle mit sehr vielen Flächen sehr viel rechenleistung benötigen. Fusion 360 will für die meisten operationen nicht mehr als 10 000.

#### Instant Meshes 

- Target vertex Count: Hier können wieder die Anzahl der flächen eingestellt werden
- Orientation Field / Position Field : Nehmen anpassungen an der Gitterstruktur vor. Durch welche das bauteil nicht durch dreiecke sonder Vierecke dargestellt wird.

+ Durch das Andere erscheinungs bild ist der Scann in Programmen wie Fusion 360 meist besser zu erkennen und Boulsche operationen sehen sauberer aus.

- Download: https://github.com/wjakob/instant-meshes   ( Anmerkung: Instant Meshes wird nicht weiter entwickelt)

  ![image](https://github.com/user-attachments/assets/64918cb8-f604-4126-bc20-f84c12403246)

#### Meshmixer 

- Analysis: Hier können Scanns auf größse geprüft werden und durch das Feature Inspector löcher werlche im Scann auftretten automatich gefüllt werden um ein abgeschlossenes Modell zu erzeugen.

- Sculpt: dieses Feature eignet sich perfekt um Liniern artefakte oder oberflächen auszubessern. Wichtig ist nur zu beachten sehr vorsichtig mit diesem Feature um zugehn da dies die Präzision wirklich stark belasten kann (weniger ist mehr).

- Download: https://meshmixer.com/download.html
![image](https://github.com/user-attachments/assets/42948e48-080e-412e-838e-dfce3a14a0e7)

#### Fusion 360 

-Unter dem Reiter Netz am oberen Bildschirmrand finden sich einige nützliche Featurs zur weiteren bearbeitung und vorbereitung zu weiteren benutzung in Fusion 360  

##### Reduzieren : 
 ist ein Feature zur reduzierung der Anzahl an fächen aus welchen das Modell besteht. Hier stehen dem nutzer einige verschidene Möglichkeiten zur verfühgung.

Typen :  

         - Toleran (Fächen werden zu einer fläche zusammengeführt ,wenn diese innerhalb der zuvor festgelgten winkel Toleranz zu einander stehen.)
         
         - Proportion  (Die Flächen werden Proportional zu Ursprungsverteilung reduziert )
         
         - Flächenanzahl (reduziert Flächen auf bestimmte Anzahl)

Proportion und FLächenanzahl können entweder Adaptiv (Anzahl der neuen Flächen, in einem Bereich, hängt von detailgrad der Ursprungsmodells ab) oder Einheitlich ausgeführt werden 

![image](https://github.com/user-attachments/assets/4b85f753-7dc0-4244-8ded-75dd0b3309a3)


##### Netz Kovertieren 
Vor diesem Prozess sollte immer gespeichert werden da es durchaus je nach Methode zu abstürzen der Programmes kommen kann!

-Facettiert: Hiermit kommt Fusion 360 im fall eines Scanns ambesten klar. Dieses Feature eignet sich zu erstellen eines Referenzmodels 

-Prismatisch /Organisch: hierbei wird das Netz Modell versucht in ein Model aus Ganzen geometrien zu überführen ( z.B. Zylinder, Würfel)
 dies ist mit einem 3d Scann als basis fast unmöglich und könnte Höchstensbei sehr einfachen geometrien genutz werden.
 Hingegen bei Netzmodellen welche zuvor in CAD entsanden sind (wie die Meisten Thingiversmodelle funktionieret diese sehr gut).

![image](https://github.com/user-attachments/assets/1d57320f-1d1e-4b9e-a6ea-c4ae6ea013ad)


