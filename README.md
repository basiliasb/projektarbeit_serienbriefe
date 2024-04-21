<p>&nbsp;</p>
<p>&nbsp;</p>
<p>Die folgende Schritt-Schritt Anleitung, beschreibt anhand der Beispieldaten im Ordner &laquo;Serienbriefe&raquo; wie mit den grafischen Modellierungen eine Adressliste der betroffenen Anwohner (adressen.model3) und Kartenausschnitte (atlas.model3) erstellt werden. Zum Schluss wird erklärt, wie mit diesen beiden Produkten in Word automatisiert Serienbriefe erstellt werden. In dieser Anleitung sind die Arbeitsschritte nummeriert. Aufeinanderfolgende Befehle innerhalb eines Arbeitsschrittes sind mit einem &laquo; &gt; &raquo; getrennt. In der zweiten Listenebene sind Zusatzinformationen zum jeweiligen Arbeitsschritt beschrieben. Pfade sind in kursiv formatiert und zeigen jeweils den Ablageort der verschiedenen Modelle, Stildateien, Layouts und Beispieldaten. Das &laquo;[&hellip;]&raquo; ist der Pfad, wo der Serienbriefordner abgespeichert ist.&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<h1>1 Vorbereitung</h1>
<ol>
<li>QGIS-Projektöffnen unter &laquo;[&hellip;]/serienbriefe/grafische Modellierungen/&raquo; Modell &laquo;adressen.model3&raquo;
<ul>
<li>Im Ordner &laquo;Serienbriefe&raquo; ist bereits ein QGIS Projekt abgespeichert, dass geöffnet werden kann. Möchte man ein eigenes Projekt erstellen, sollte die Datei ebenfalls in den Ordner <em>&laquo;[&hellip;]serienbriefe</em> abgespeichert werden.</li>
</ul>
</li>
<li>Im Browser-Panel &laquo;Projektverzeichnis&raquo; aufklappen &gt; Beispieldaten aufklappen &gt; Dateien per Drag und Drop auf die Kartenansicht ziehen.
<ul>
<li>Das Projektverzeichnis im Browser-Panel listet den Inhalt des Ordners auf, wo das QGIS-Projekt gespeichert ist. Per Drag und Drop können die Beispieldaten (Schächte, Liegenschaften und Bodenbedeckungen, Gebäuderegister-Tabelle, Eingangsregister-Tabelle und Wohnregister-Tabellle) dem Projekt hinzugefügt werden.</li>
</ul>
</li>
</ol>
<h1>2 Adressliste erstellen und speichern (adressen.model3)</h1>
<p>Mit den Vorbereiteten Datensätzen kann die Modellierung &laquo;adressen.model3&raquo; ausgeführt werden. Im zuvor definierten Ablageort (4. Schritt) wird eine Adressliste als CSV-Datei gespeichert, die für den Seriendruck in Word als Empfängerliste verwendet werden kann.</p>
<ol start="3">
<li>Register: &laquo;Verarbeitung&raquo; &gt; grafische Modellierung auswählen
<ul>
<li>Das Fenster &laquo;Modellentwurf&raquo; wird geöffnet.</li>
</ul>
</li>
<li>In der oberen Taksbar das Ordner Symbol anklicken &gt; unter <em>&laquo;[&hellip;[./serienbriefe/grafische Modellierungen/&raquo; </em>Modell &laquo;<em>model3&raquo; </em>wählen.
<ul>
<li>Das Modell wird geöffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.</li>
</ul>
</li>
<li>In der oberen Taskbar das grüne Play-Symbol anklicken
<ul>
<li>Die Eingabemaske wird geöffnet.</li>
</ul>
</li>
<li>In den Eingabefelder die Datensätze per Drop-Down Menu auswählen. Unter dem Eingabefeld &laquo;adressen&raquo; der Ablageort mit dem Pfad <em>&laquo;[&hellip;]/serienbriefe/adressliste/adressen.csv&raquo; </em>
<ul>
<li>Es kann sein, dass für einige Parameter bereits Datensätze gewählt sind. Diese haben jeweils eine längere Zeichenkette nach dem eigentlichen Layername. Solche Datensätze können für die Modellierung nicht genutzt werden. Deshalb muss jeder Parameter neu bestimmt werden.</li>
<li>Der Ablageort darf keine Datei mit denselben Namen wie die Ausgabedatei enthalten. Da keine Dateien überschrieben werden, wird das Modell in diesem Fall nicht ausgeführt.</li>
</ul>
</li>
<li>Klick auf die Schaltfläche &laquo;Start&raquo;
<ul>
<li>Die Adressliste wird im Ordner <em>&laquo;[&hellip;]/serienbriefe/adressliste&raquo; </em>als &laquo;<em>csv&raquo;</em> gespeichert </li>
</ul>
</li>
</ol>
<h1>3 Kartenausschnitte erstellen und speichern (atlas.model3)</h1>
<p>Das Modell &laquo;atlas.model3&raquo; kann unabhängig von &laquo;adressen.model3&raquo; ausgeführt werden. Das Modell speichert Kartenausschnitte von Liegenschaften ab, auf denen mindestens ein Punkt des Schachtlayers liegt. Für eine</p>
<p>&nbsp;</p>
<ol>
<li>Register: &laquo;Verarbeitung&raquo; &gt; grafische Modellierung auswählen
<ul>
<li>Das Fenster &laquo;Modellentwurf&raquo; wird geöffnet.</li>
</ul>
</li>
<li>In der oberen Taksbar das Ordner Symbol anklicken &gt; unter <em>&laquo;./serienbriefe/grafische Modellierungen/&raquo; </em>Modell &laquo;<em>model3&raquo; </em>wählen.
<ul>
<li>Das Modell wird geöffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.</li>
</ul>
</li>
<li>In der oberen Taskbar das grüne Play-Symbol anklicken
<ul>
<li>Die Eingabemaske wird geöffnet.</li>
</ul>
</li>
<li>In den Eingabefelder die Datensätze per Drop-Down Menu auswählen. Unter dem Eingabefeld &laquo;adressen&raquo; der Ablageort mit dem Pfad <em>&laquo;[&hellip;]/serienbriefe/kartenausschnitte/&raquo; </em></li>
<li>Klick auf die Schaltfläche &laquo;Start&raquo;
<ul>
<li>Die Kartenausschnitte werden im Ordner <em>&laquo;[&hellip;]/serienbriefe/kartenausschnitte&raquo; </em>als Bilddateien gespeichert.</li>
</ul>
</li>
</ol>
<h1>4 Serienbrief in Word erstellen</h1>
<p>Mit der Wordvorlage &laquo;serienbrief.docx&raquo; kann der Seriendruck erstellt werden. Dazu müssen die beiden Modell vorgängig ausgeführt worden sein.</p>
<p>&nbsp;</p>
<ol>
<li>Die Wordvorlage <em>&laquo;serienbriefe/serienbrief.docx&raquo;</em>öffnen.
<ul>
<li>Der Text kann nun beliebig geändert werden. Die Feldfunktionen sollten dabei unverändert bleiben</li>
</ul>
</li>
<li>Register: &laquo;Sendungen&raquo; &gt; Gruppe &laquo;Seriendruck starten&raquo; Schaltfläche: &laquo;Empfänger auswählen&raquo; &gt; &laquo;Vorhanden Liste verwenden&hellip;&raquo; wählen.
<ul>
<li>Der Dateiexplorer wird geöffnet.</li>
</ul>
</li>
<li>Die Adressliste mit dem Ablageort <em>&laquo;[..]/serienbriefe/adressliste/adressen.csv&raquo; </em>wählen.
<ul>
<li>Das Fenster &laquo;Dateikonvertierung&raquo; wird geöffnet.</li>
</ul>
</li>
<li>Die Option &laquo;andere Codierung&raquo; anwählen &gt; in der Liste den Eintrag &laquo;Unicode (UTF-8)&raquo; wählen &gt; Klick auf Schaltfläche &laquo;Ok&raquo;
<ul>
<li>Die CSV-Datei wird mit der Empfängerliste verbunden.</li>
</ul>
</li>
<li>Mit der Tastenkombination CTRL + A den gesamten Text markieren &gt; Taste F9 drücken
<ul>
<li>Die Seriendurckfelder werden aktualisiert. Womöglich erscheint eine Warnmeldung die mit &laquo;Ja&raquo; bestätigt werden kann. Damit können die Kartenschnitte als externe Dateien in Word integriert werden.</li>
<li>Mit den Pfeil Tasten in der Gruppe &laquo;Vorschau und Ergebnisse&raquo; kann zwischen den Empfänger navigiert werden. Der Inhalt der Seriendruckfelder im Text sollte während dem Navigieren ändern. Normalerweise werden die Kartenausschnitte nicht aktualisiert. Dafür muss jeweils der Kartenausschnitt bzw. das Seriendruckfeld ausgewählt und mit der Betätigung der F9 Taste aktualisiert werden.</li>
</ul>
</li>
<li>Register Sendungen &gt; &laquo;Fertig stellen und zusammenführen&raquo; wählen &gt;</li>
</ol>
<p>&nbsp;</p>
<p>&nbsp;</p>
