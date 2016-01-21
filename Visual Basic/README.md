Beschreibung:
Die Software �berpr�ft die Metadaten einer Datei und schaut ob zwischen der neusten und der Datei danach eine Differenz
von mehr Tagen, als in der Konfiguration eingestellt vorhanden ist. Wenn ja wird eine Warnmeldung ausgegeben.

Konfiguration:
Die Pfade und Differenz-Tage k�nnen durch die Datei "modified-backup.exe.config" angepasst werden.
Die Einstellung "daysDiff" steht f�r die maximal Differenz der Tage (Stundenbasiert) also sind Werte wie 1.3 m�glich.
"path" steht f�r den Dateipfad der Dateien.

<modified_backup.My.MySettings>
	<setting name="daysDiff" serializeAs="String">
		<value>1</value>
	</setting>
	<setting name="path" serializeAs="String">
		<value>C:\Users\dennis.heinrich\Desktop\Datensicherungen</value>
	</setting>
</modified_backup.My.MySettings>