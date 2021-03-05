# Wartezeiten Bürgeramt

Dieser Datensatz enthält die Wartezeiten des Bürgeramt Heilbronn. Außerdem sind verschiedene andere Ämter aus Heilbronn und einigen anderen Städten enthalten.

Die Daten sind eine CSV (Comma-separated Values) und können mit einem Texteditor wie z.B. Visual Studio Code geöffnet werden.

Das hier ist ein Beispieldatensatz und der Header der CSV Datei

    name,time,circleName,nextCallCount,siteDisplayName,siteName,visitorCount,waitTimeSeconds,waitTimeSecondsRaw
    waittimes,1608212932158342579,Spontankunden,2,Bürgeramt Heilbronn,buergeramt-heilbronn,2,81,81

| Spalte | Format | Erklärung
| ------ | --- | --- |
| name | String | Bezeichnung für den Datensatz (im vorliegenden Datensatz immer waittimes)
| time | Integer | Nanoseconds since Unix - fortlaufende Anzahl der Nanosekunden seit dem 1. Januar 1970 - kann z.B. mit https://www.epochconverter.com/ umgewandelt werden
| circleName | String | In einer Behörde können unterschiedliche Wartekreise enthalten sein
| nextCallCount | Integer | Anzahl der nächsten aufgerufenen Tickets (vmtl. irrelevant)
| siteDisplayName | String | Anzeigename der Behörde
| siteName | String | Identifikationsname der Behörde
| visitorCount | Integer | Anzahl der wartenden Personen
| waitTimeSeconds | Integer | Aktuelle Wartezeit in Sekunden
| waitTimeSecondsRaw | Integer | Aktuelle Wartezeit in Sekunden, unabhängig von aktuell wartenden Personen (vmtl. irrelevant)
