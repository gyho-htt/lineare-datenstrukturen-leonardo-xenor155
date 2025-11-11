# Arbeitsauftrag
Beobachte das Objektspiel zum *second hand shop* und beantworte folgende Fragen:
1. Wie entwickelt sich die Länge der Datenstruktur? Spielt die Länge der Datenstruktur eine Rolle zur Verwaltung der Elemente?

-Sie wird immer länger wenn man etwas hinzufügt(Schlange)
-> Array nicht sinnvoll, da die Länge dynamisch sein muss, von 0 - 3,

-Die Länge der Datenstruktur spielt keine große Rolle für die Verwaltung der Elemente, da gewisse Operationen auch funktionieren, wenn es eine beliebige Anzahl an Personen gibt.
- was ist bei 0 Personen mit beispielsweise der Methode verlassen

2. Wie werden neue Elemente hinzugefügt?

-Sie werden hinter dem letzten Element eingefügt

3. Auf welche Elemente wird Zugegriffen?

-Auf das vorderste Element

4. Welche Beziehungen der Elemente gibt es untereinander?

- alle Elemente kennen das VorgängerElement
- Jedes ELement kennt seinen Inhalt (hier: Bestellbestätigung)

5. Welche Elemente müsste ein Verwaltungselement kennen?

das erste und das Letzte Element

6. Nach welchem Prinzip arbeitet die Datenstruktur? Wie nennt man eine solche Datenstruktur?
(Warte-)
Sie arbeitet nach dem FIFO-prinzip: First in First out
-> evtl Schlange

7. Welche (Verwaltungs)Operationen sind für diese Datenstruktur sinnvoll?

-anstellen
-entfernen
-Wissen ob die Schlange leer ist
-gib das erste Element
