# Datenanalyse {#head}


## Interpolation
Im Reiter *Interpolation* lassen sich die Daten mehrerer senseBoxen zu einem Phänomen räumlich interpolieren.

Dies ist nützlich um die räumlichen Unterschiede eines Phänomens auf der Karte sichtbar zu machen, oder um ungefähre Werte in Regionen ableiten zu können, in welchen keine Sensoren vorhanden sind.

<img src="https://raw.githubusercontent.com/sensebox/resources/master/images/osem_interpolation.jpg" center width="700px" />

Es wird das Interpolationsverfahren **IDW** (*Inverse Distance Weighting*) verwendet, welches als Parameter einen *power*-Wert hat. Dieser ist der Exponent, mit welchem die Distanz eines Messwerts zu einem Ort der Interpoliert wird gewichtet wird.
Ein niedriger Wert für *power* bezieht also Werte aus größeren Distanzen ähnlich stark wie aus der Nähe ein, während ein hoher *power*-Wert insbesondere Werte aus unmittelbarer Entfernung betrachtet.

Nach Einstellung der Parameter wird die Interpolation auf unserem Server berechnet.
Wenn die Kalkulation abgeschlossen ist, wird das Ergebnis als Heatmap in der Karte angezeigt.
Die Zellgröße der Kalkulation kann auch eingestellt werden um detailliertere Ergebnisse zu erhalten; hierbei ist aber zu beachten dass die Berechnungszeit bei kleineren Zellen sehr stark ansteigt.

