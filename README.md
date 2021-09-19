 TTGO_wetterboard
Hucke Pack Leiterplatte für das TTGO32 Beam ab Version 1.0 zur Implementation von Wetter Sensoren

implementiert ist das DHT11/22,BMP280 oder BME280, UV Sensor VELM6070,Blitzsensor AS3935 Modul.
Ein 128x 96 OLED Display dient zur Anzeige der Messwerte. 2 Tasten dienen der Menu Steuerung.
Eine NF Buchse kann zur Ein /Ausgabe externe Geräte benutzt werden. 

Installation 


Löte als erstes auf der Boardoberseite die Kondensatoren C1 und C2 Smd 0805 22nf ein.
Löte R1 , R2 und R3 SMD 0805 10 Kohm ein.
Löte die Schottky Dioden D1,D2,D3. Achtung !! Polung beachten Anode zeigt zum Header hin.
Löte am Header J3 eine 3 polig Stiftleiste von rechts beginnend ein. Lasse 4 Lötaugen aus 
 und löte eine 6 polige Stiftleiste ab Pin 8 ein. 
Löte an J4 ein 13 polige Stiftleiste ein. Alle Stiftleisten werden von unten gesteckt und oben gelötet
Bereite das Display vor.Löte ein 4 polige Stiftleiste am Display an, falls noch nicht vorhanden. Achtung !!
das Display muss am linken Stift VDD haben am 2. von links GND. Es gibt auch Displays wo es anders herum ist.
Ziehe anschließend das schwarze Distanzstück von der Stiftleiste so das nur noch 4 blanke Stifte am Display sind.
Isoliere die beiden Bohrlöcher vom Display rechts und links von der Stiftleiste an der Displayunterseite.
Stecke das Display von oben durch das Wetterboard und verlöte es von unten. Das Display ist dabei soweit wie möglich
nach unten zu drücken.
Nehme ein Multimeter, messe auf den Pins VDD GND auf Durchgang. Ist kein Durchgang vorhanden kann ein erster Test gemacht werden.
Stecke das Weatherboard auf das TTGO32 Beam und schalte das TTGO ein. Jetzt müsste auf dem Display der Startvorgang zu sehen 
sein. Schalte das TTGO aus und ziehe das Wetterboard ab.
Löte jetzt noch die beiden Tasten SW1 und SW2 auf, und anschließend das DHT22 Modul auf der Oberseite, wie auf der Platine gezeichnet.
Löte danach noch die beiden Module BME280 und das UV-A Sensormodul VEML6070 auf. Ziehe auch auch hier bei beiden Modulen das schwarze
Distanzstück von der Stiftleiste ab so das die die Module Plan auf den Wetterboard aufliegen.
Wer die Ausgabe der empfangenen LoRa Station in Morsetelegrafie haben möchte kann noch an J5 einen Miniaturlautsprecher anlöten. Diesen
kann man leicht in alten Smartphones oder DECT Telefonen  ausbauen.
 
Alle anderen Bauteile sind nicht zu bestücken und dienen nur zukünftige Entwicklung und sind noch in Arbeit 
