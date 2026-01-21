# Übung 12 - Schleifen


## 1. Aufgabe

Setzen Sie das Spiel "Schere, Stein, Papier" anhand des Klassendiagramms um:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Beschreibung:**
- Der Benutzer spielt gegen den Computer.
- Die Regeln des Spiels:
    - Schere gewinnt gegen Papier
    - Stein gewinnt gegen Schere.
    - Papier gewinnt gegen Stein.
    - Sind die Auswahlen gleich, endet das Spiel unentschieden.
- Die Auswahl des Spielers soll durch eine Konsoleneingabe geschehen. Wird ein 
falscher Wert eingegeben, soll der Benutzer erneut nach einer Eingabe gefragt 
werden.
- Die Auswahl des Computers soll zufällig geschehen.
- Die `spiel()`-Methode gibt den Namen des Spielers zurück, welcher gewonnen hat.
- Nach jedem Spiel soll der Benutzer gefragt werden, ob er noch einmal spielen 
möchte. Wenn ja, wird ein neues Spiel gestartet. Wenn nein, soll das Programm 
beendet werden.


Wägen Sie ab, welche der beschriebenen Punkte in welcher Klasse implementiert werden 
muss. Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm. Verwenden Sie den Scanner!

## 2. Aufgabe

Simulieren Sie die `Kaffeemaschine` aus Übung 8 mit Schleifen. Der Benutzer soll die gesamte 
`Kaffeemaschine` steuern können. Das Programm wird beendet, sobald die `Kaffeemaschine` 
vom Benutzer ausgeschalten wird.
## 3. Aufgabe

Simulieren Sie den `BankAccount` aus Übung 9 mit Schleifen. Der Benutzer soll den gesamten 
`BankAccount` steuern können. Geben Sie dem Benutzer eine Möglichkeit das Programm zu 
beenden.
