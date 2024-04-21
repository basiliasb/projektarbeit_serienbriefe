<p>&nbsp;</p>
<p>&nbsp;</p>
<p>Die folgende Schritt-f&uuml;r-Schritt Anleitung, beschreibt anhand der Beispieldaten im Ordner &laquo;Serienbriefe&raquo; wie mit den grafischen Modellierungen eine Adressliste der betroffenen Anwohner (adressen.model3) und Kartenausschnitte (atlas.model3) erstellt werden. Zum Schluss wird erkl&auml;rt, wie mit diesen beiden Produkten in Word automatisiert Serienbriefe erstellt werden. In dieser Anleitung sind die Arbeitsschritte nummeriert. Aufeinanderfolgende Befehle innerhalb eines Arbeitsschrittes sind mit einem &laquo; &gt; &raquo; getrennt. Die nachgestellte Listenebene mit dem Symbol &laquo; ↪ &raquo; beschreibt jeweils, welche Aktionen durch die Befehle ausgef&uuml;hrt werden und liefern Zusatzinformationen. Pfade sind in kursiv formatiert und zeigen jeweils den Ablageort der verschiedenen Modelle, Stildateien, Layouts und Beispieldaten. Das &laquo;[&hellip;]&raquo; ist der Pfad, wo der Serienbriefordner abgespeichert ist.&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<h1>1 Vorbereitung</h1>
<ol>
<li>QGIS-Projekt &ouml;ffnen unter &laquo;[&hellip;]/serienbriefe/grafische Modellierungen/&raquo; Modell &laquo;adressen.model3&raquo;
<ul>
<li>Im Ordner &laquo;Serienbriefe&raquo; ist bereits ein QGIS Projekt abgespeichert, dass ge&ouml;ffnet werden kann. M&ouml;chte man ein eigenes Projekt erstellen, sollte die Datei ebenfalls in den Ordner <em>&laquo;[&hellip;]serienbriefe</em> abgespeichert werden.</li>
</ul>
</li>
<li>Im Browser-Panel &laquo;Projektverzeichnis&raquo; aufklappen &gt; Beispieldaten aufklappen &gt; Dateien per Drag und Drop auf die Kartenansicht ziehen.
<ul>
<li>Das Projektverzeichnis im Browser-Panel listet den Inhalt des Ordners auf, wo das QGIS-Projekt gespeichert ist. Per Drag und Drop k&ouml;nnen die Beispieldaten (Sch&auml;chte, Liegenschaften und Bodenbedeckungen, Geb&auml;uderegister-Tabelle, Eingangsregister-Tabelle und Wohnregister-Tabellle) dem Projekt hinzugef&uuml;gt werden.</li>
</ul>
</li>
</ol>
<h1>2 Adressliste erstellen und speichern (adressen.model3)</h1>
<p>Mit den Vorbereiteten Datens&auml;tzen kann die Modellierung &laquo;adressen.model3&raquo; ausgef&uuml;hrt werden. Im zuvor definierten Ablageort (4. Schritt) wird eine Adressliste als CSV-Datei gespeichert, die f&uuml;r den Seriendruck in Word als Empf&auml;ngerliste verwendet werden kann.</p>
<ol start="3">
<li>Register: &laquo;Verarbeitung&raquo; &gt; grafische Modellierung ausw&auml;hlen
<ul>
<li>Das Fenster &laquo;Modellentwurf&raquo; wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>In der oberen Taksbar das Ordner Symbol anklicken &gt; unter <em>&laquo;[&hellip;[./serienbriefe/grafische Modellierungen/&raquo; </em>Modell &laquo;<em>model3&raquo; </em>w&auml;hlen.
<ul>
<li>Das Modell wird ge&ouml;ffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.</li>
</ul>
</li>
<li>In der oberen Taskbar das gr&uuml;ne Play-Symbol anklicken
<ul>
<li>Die Eingabemaske wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>In den Eingabefelder die Datens&auml;tze per Drop-Down Menu ausw&auml;hlen. Unter dem Eingabefeld &laquo;adressen&raquo; der Ablageort mit dem Pfad <em>&laquo;[&hellip;]/serienbriefe/adressliste/adressen.csv&raquo; </em>
<ul>
<li>Es kann sein, dass f&uuml;r einige Parameter bereits Datens&auml;tze gew&auml;hlt sind. Diese haben jeweils eine l&auml;ngere Zeichenkette nach dem eigentlichen Layername. Solche Datens&auml;tze k&ouml;nnen f&uuml;r die Modellierung nicht genutzt werden. Deshalb muss jeder Parameter neu bestimmt werden.</li>
<li>Der Ablageort darf keine Datei mit denselben Namen wie die Ausgabedatei enthalten. Da keine Dateien &uuml;berschrieben werden, wird das Modell in diesem Fall nicht ausgef&uuml;hrt.</li>
</ul>
</li>
<li>Klick auf die Schaltfl&auml;che &laquo;Start&raquo;
<ul>
<li>Die Adressliste wird im Ordner <em>&laquo;[&hellip;]/serienbriefe/adressliste&raquo; </em>als &laquo;<em>csv&raquo;</em> gespeichert </li>
</ul>
</li>
</ol>
<h1>3 Kartenausschnitte erstellen und speichern (atlas.model3)</h1>
<p>Das Modell &laquo;atlas.model3&raquo; kann unabh&auml;ngig von &laquo;adressen.model3&raquo; ausgef&uuml;hrt werden. Das Modell speichert Kartenausschnitte von Liegenschaften ab, auf denen mindestens ein Punkt des Schachtlayers liegt. F&uuml;r eine</p>
<p>&nbsp;</p>
<ol>
<li>Register: &laquo;Verarbeitung&raquo; &gt; grafische Modellierung ausw&auml;hlen
<ul>
<li>Das Fenster &laquo;Modellentwurf&raquo; wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>In der oberen Taksbar das Ordner Symbol anklicken &gt; unter <em>&laquo;./serienbriefe/grafische Modellierungen/&raquo; </em>Modell &laquo;<em>model3&raquo; </em>w&auml;hlen.
<ul>
<li>Das Modell wird ge&ouml;ffnet und der Modellbaum wird sichtbar, der bei Bedarf angepasst werden kann.</li>
</ul>
</li>
<li>In der oberen Taskbar das gr&uuml;ne Play-Symbol anklicken
<ul>
<li>Die Eingabemaske wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>In den Eingabefelder die Datens&auml;tze per Drop-Down Menu ausw&auml;hlen. Unter dem Eingabefeld &laquo;adressen&raquo; der Ablageort mit dem Pfad <em>&laquo;[&hellip;]/serienbriefe/kartenausschnitte/&raquo; </em></li>
<li>Klick auf die Schaltfl&auml;che &laquo;Start&raquo;
<ul>
<li>Die Kartenausschnitte werden im Ordner <em>&laquo;[&hellip;]/serienbriefe/kartenausschnitte&raquo; </em>als Bilddateien gespeichert.</li>
</ul>
</li>
</ol>
<h1>4 Serienbrief in Word erstellen</h1>
<p>Mit der Wordvorlage &laquo;serienbrief.docx&raquo; kann der Seriendruck erstellt werden. Dazu m&uuml;ssen die beiden Modell vorg&auml;ngig ausgef&uuml;hrt worden sein.</p>
<p>&nbsp;</p>
<ol>
<li>Die Wordvorlage <em>&laquo;serienbriefe/serienbrief.docx&raquo;</em> &ouml;ffnen.
<ul>
<li>Der Text kann nun beliebig ge&auml;ndert werden. Die Feldfunktionen sollten dabei unver&auml;ndert bleiben</li>
</ul>
</li>
<li>Register: &laquo;Sendungen&raquo; &gt; Gruppe &laquo;Seriendruck starten&raquo; Schaltfl&auml;che: &laquo;Empf&auml;nger ausw&auml;hlen&raquo; &gt; &laquo;Vorhanden Liste verwenden&hellip;&raquo; w&auml;hlen.
<ul>
<li>Der Dateiexplorer wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>Die Adressliste mit dem Ablageort <em>&laquo;[..]/serienbriefe/adressliste/adressen.csv&raquo; </em>w&auml;hlen.
<ul>
<li>Das Fenster &laquo;Dateikonvertierung&raquo; wird ge&ouml;ffnet.</li>
</ul>
</li>
<li>Die Option &laquo;andere Codierung&raquo; anw&auml;hlen &gt; in der Liste den Eintrag &laquo;Unicode (UTF-8)&raquo; w&auml;hlen &gt; Klick auf Schaltfl&auml;che &laquo;Ok&raquo;
<ul>
<li>Die CSV-Datei wird mit der Empf&auml;ngerliste verbunden.</li>
</ul>
</li>
<li>Mit der Tastenkombination CTRL + A den gesamten Text markieren &gt; Taste FN9 dr&uuml;cken
<ul>
<li>Die Seriendurckfelder werden aktualisiert. Wom&ouml;glich erscheint eine Warnmeldung die mit &laquo;Ja&raquo; best&auml;tigt werden kann. Damit k&ouml;nnen die Kartenschnitte als externe Dateien in Word integriert werden.</li>
<li>Mit den Pfeil Tasten in der Gruppe &laquo;Vorschau und Ergebnisse&raquo; kann zwischen den Empf&auml;nger navigiert werden. Der Inhalt der Seriendruckfelder im Text sollte w&auml;hrend dem Navigieren &auml;ndern. Normalerweise werden die Kartenausschnitte nicht aktualisiert. Daf&uuml;r muss jeweils der Kartenausschnitt bzw. das Seriendruckfeld ausgew&auml;hlt und mit der Bet&auml;tigung der F9 Taste aktualisiert werden.</li>
</ul>
</li>
<li>Register Sendungen &gt; &laquo;Fertig stellen und zusammenf&uuml;hren&raquo; w&auml;hlen &gt;</li>
</ol>
<p>&nbsp;</p>
<p>&nbsp;</p>
