# I. Hamming_code
 berechnet die Paritätsbits für Codes
# Wie funktioniert das?
## 1.Man nimmt den Code von der Klausuraufgabe
## 2.Entferne die Lüchen(Leeretasten)
## 3.in Zeile 15 eingeben
String eingabe ="0100001011011011";
## 4. Resultat von Console nehmen
## 5. Schreib jeweils in die entsprechenden Lücken. 1.2.4.8.16.
## 6. Den Rest schreibt man so wie in der Aufgabestellung steht und auf die restlichen Lücken.

# II. Wie prüft der Rechner ob Fehler in Hamming-Code auftauchen?
## Bei Übung 8 gibt es eine Aufgabe, in der man die Fehler suchen muss:
100010010010110011011
## 1.man entfernt die paritätsbits
**10**0**0**100**1**0010110**0**11011
## 2.bekommt den rest
0100 0010 1101 1011
## 3. Gibt so den Code wie in ``I`` gezeigt, bekommt man:
p1: 1 <br />
p2: 1 <br />
p3: 1 <br />
p4: 1 <br />
p5: 0 <br />
## 4.Schreibe die neu berechneten Paritätsbits zurück:
**11**0**1** 100**1** 0010 110**0** 1101 1
## 5. Vergleiche man mit der Aufgabe
1**1**0**1**  1001 0010 1100 1101 1 <br />
1**0**0**0** 1001 0010 1100 1101 1
## 6. Das 2.und 4. Bit sind falsch übertragen worden
2+4=6
## 7. Das 6. Bit ist zu invertieren
10001**1**010010110011011
