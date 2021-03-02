# Wartezeiten Bürgeramt

Dieser Datensatz enthält die Wartezeiten des Bürgeramt Heilbronn. Außerdem sind verschiedene andere Ämter aus Heilbronn und einigen anderen Städten enthalten.

Die Daten sind eine CSV (Comma-separated Values) und können mit einem Texteditor wie z.B. Visual Studio Code geöffnet werden.

Das hier ist ein Beispieldatensatz und der Header der CSV Datei

    name,time,circleName,nextCallCount,siteDisplayName,siteName,visitorCount,waitTimeSeconds,waitTimeSecondsRaw
    waittimes,1578270695896971768,Abholung,0,Bürgerbüro Stadt Jülich,buergerbuero-juelich,0,0,

| Spalte | Format | Erklärung
| ------ | --- | --- |
| name | String | Bezeichnung für den Datensatz (im vorliegenden Datensatz immer waittimes)
| time | Integer | Nanoseconds since Unix - fortlaufende Anzahl der Nanosekunden seit dem 1. Januar 1970 - kann z.B. mit https://www.epochconverter.com/ umgewandelt werden
| circleName | String | In einer Behörde können unterschiedliche Nummernkreise enthalten sein
| nextCallCount | Integer | Anzahl der wartenden Tickets ?
| siteDisplayName | String | Anzeigename der Behörde
| siteName | String | Idendifikationsname der Behörde
| visitorCount | Integer | ??
| waitTimeSeconds | Integer | Wartezeit seit dem ziehen des Ticket ?
| waitTimeSecondsRaw | Integer | ??