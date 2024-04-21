 

 

Die folgende Schritt-für-Schritt Anleitung, beschreibt anhand der Beispieldaten im Ordner «Serienbriefe» wie mit den grafischen Modellierungen eine Adressliste der betroffenen Anwohner (adressen.model3) und Kartenausschnitte (atlas.model3) erstellt werden. Zum Schluss wird erklärt, wie mit diesen beiden Produkten in Word automatisiert Serienbriefe erstellt werden. In dieser Anleitung sind die Arbeitsschritte nummeriert. Aufeinanderfolgende Befehle innerhalb eines Arbeitsschrittes sind mit einem « > » getrennt. Die nachgestellte Listenebene mit dem Symbol « ↪ » beschreibt jeweils, welche Aktionen durch die Befehle ausgeführt werden und liefern Zusatzinformationen. Pfade sind in kursiv formatiert und zeigen jeweils den Ablageort der verschiedenen Modelle, Stildateien, Layouts und Beispieldaten. Das «[…]» ist der Pfad, wo der Serienbriefordner abgespeichert ist.  

 
1 Vorbereitung

    QGIS-Projekt öffnen unter «[…]/serienbriefe/grafische Modellierungen/» Modell «adressen.model3»
        Im Ordner «Serienbriefe» ist bereits ein QGIS Projekt abgespeichert, dass geöffnet werden kann. Möchte man ein eigenes Projekt erstellen, sollte die Datei ebenfalls in den Ordner «[…]serienbriefe abgespeichert werden.
    Im Browser-Panel «Projektverzeichnis» aufklappen > Beispieldaten aufklappen > Dateien per Drag und Drop auf die Kartenansicht ziehen.
        Das Projektverzeichnis im Browser-Panel listet den Inhalt des Ordners auf, wo das QGIS-Projekt gespeichert ist. Per Drag und Drop können die Beispieldaten (Schächte, Liegenschaften und Bodenbedeckungen, Gebäuderegister-Tabelle, Eingangsregister-Tabelle und Wohnregister-Tabellle) dem Projekt hinzugefügt werden.

2 Adressliste erstellen und speichern (adressen.model3)

Mit den Vorbereiteten Datensätzen kann die Modellierung «adressen.model3» ausgeführt werden. Im zuvor definierten Ablageort (4. Schritt) wird eine Adressliste als CSV-Datei gespeichert, die für den Seriendruck in Word als Empfängerliste verwendet werden kann.

    Register: «Verarbeitung» > grafische Modellierung auswählen
        Das Fenster «Modellentwurf» wird geöffnet.
    In der oberen Taksbar das Ordner Symbol anklicken > unter «[…[./serienbriefe/grafische Modellierungen/» Modell «model3» wählen.
        Das Modell wird geöffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.
    In der oberen Taskbar das grüne Play-Symbol anklicken
        Die Eingabemaske wird geöffnet.
    In den Eingabefelder die Datensätze per Drop-Down Menu auswählen. Unter dem Eingabefeld «adressen» der Ablageort mit dem Pfad «[…]/serienbriefe/adressliste/adressen.csv»
        Es kann sein, dass für einige Parameter bereits Datensätze gewählt sind. Diese haben jeweils eine längere Zeichenkette nach dem eigentlichen Layername. Solche Datensätze können für die Modellierung nicht genutzt werden. Deshalb muss jeder Parameter neu bestimmt werden.
        Der Ablageort darf keine Datei mit denselben Namen wie die Ausgabedatei enthalten. Da keine Dateien überschrieben werden, wird das Modell in diesem Fall nicht ausgeführt.
    Klick auf die Schaltfläche «Start»
        Die Adressliste wird im Ordner «[…]/serienbriefe/adressliste» als «csv» gespeichert 

3 Kartenausschnitte erstellen und speichern (atlas.model3)

Das Modell «atlas.model3» kann unabhängig von «adressen.model3» ausgeführt werden. Das Modell speichert Kartenausschnitte von Liegenschaften ab, auf denen mindestens ein Punkt des Schachtlayers liegt. Für eine

 

    Register: «Verarbeitung» > grafische Modellierung auswählen
        Das Fenster «Modellentwurf» wird geöffnet.
    In der oberen Taksbar das Ordner Symbol anklicken > unter «./serienbriefe/grafische Modellierungen/» Modell «model3» wählen.
        Das Modell wird geöffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.
    In der oberen Taskbar das grüne Play-Symbol anklicken
        Die Eingabemaske wird geöffnet.
    In den Eingabefelder die Datensätze per Drop-Down Menu auswählen. Unter dem Eingabefeld «adressen» der Ablageort mit dem Pfad «[…]/serienbriefe/kartenausschnitte/»
    Klick auf die Schaltfläche «Start»
        Die Kartenausschnitte werden im Ordner «[…]/serienbriefe/kartenausschnitte» als Bilddateien gespeichert.

4 Serienbrief in Word erstellen

Mit der Wordvorlage «serienbrief.docx» kann der Seriendruck erstellt werden. Dazu müssen die beiden Modell vorgängig ausgeführt worden sein.

 

    Die Wordvorlage «serienbriefe/serienbrief.docx» öffnen.
        Der Text kann nun beliebig geändert werden. Die Feldfunktionen sollten dabei unverändert bleiben
    Register: «Sendungen» > Gruppe «Seriendruck starten» Schaltfläche: «Empfänger auswählen» > «Vorhanden Liste verwenden…» wählen.
        Der Dateiexplorer wird geöffnet.
    Die Adressliste mit dem Ablageort «[..]/serienbriefe/adressliste/adressen.csv» wählen.
        Das Fenster «Dateikonvertierung» wird geöffnet.
    Die Option «andere Codierung» anwählen > in der Liste den Eintrag «Unicode (UTF-8)» wählen > Klick auf Schaltfläche «Ok»
        Die CSV-Datei wird mit der Empfängerliste verbunden.
    Mit der Tastenkombination CTRL + A den gesamten Text markieren > Taste FN9 drücken
        Die Seriendurckfelder werden aktualisiert. Womöglich erscheint eine Warnmeldung die mit «Ja» bestätigt werden kann. Damit können die Kartenschnitte als externe Dateien in Word integriert werden.
        Mit den Pfeil Tasten in der Gruppe «Vorschau und Ergebnisse» kann zwischen den Empfänger navigiert werden. Der Inhalt der Seriendruckfelder im Text sollte während dem Navigieren ändern. Normalerweise werden die Kartenausschnitte nicht aktualisiert. Dafür muss jeweils der Kartenausschnitt bzw. das Seriendruckfeld ausgewählt und mit der Betätigung der F9 Taste aktualisiert werden.
    Register Sendungen > «Fertig stellen und zusammenführen» wählen >

 

 
