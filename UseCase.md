# Use-Cases
## Use-Case **Angriff**

| **Geschäftsprozess**          | Gegner angreifen                                                                                              |
|-------------------------------|--------------------------------------------------------------------------------------------------------------|
| **Ziel, Ergebnisse**           | Gegnerische Truppen dezimieren; Gebiete                                                                      |
| **Akteure**                    | Angreifer und Verteidiger                                                                                    |
| **Voraussetzungen**            | - Eigene Truppen im Gebiet vorhanden <br> - Direkte Verbindung zum gegnerischen Land muss vorhanden sein <br> - Land muss im feindlichen Besitz sein |
| **Auslösendes Ereignis**       | Deklarierung des Angriffes                                                                                   |
| **Nachbedingung bei Erfolg**   | Bonuskarte; Eroberung des feindlichen Gebietes                                                               |
| **Nachbedingung bei Fehlschlag** | Truppenverlust                                                                                              |
| **Eingehende Daten**           | Würfelzahl; eingesetzte Armeen                                                                               |
| **Ausgehende Daten**           | Sieger, Verlierer                                                                                           |
| **Ablauf**                     | 1. Angriff deklarieren <br> 2. Anzahl der Armeen wählen <br> 3. Würfeln <br> 4. Auswertung des Angriffes <br> 5. Ausgang: <br> - Sieg: Eroberung des Territoriums; feindliche Armeen werden vernichtet; ziehen einer Karte <br> - Niederlage: Verlust von Truppen |
| **Erweiterungen**              | -                                                                                                            |
| **Alternativen**               | Angriffsabbruch                                                                                              |

## Use-Case Armeen verschieben

| Geschäftsprozess         | Armeen verschieben                                                                 |
|--------------------------|------------------------------------------------------------------------------------|
| Ziel/Ergebnis            | Truppenanzahl auf eigenen Gebieten ausgleichen bzw. stärken, Vorbereitungen auf Angriffszüge oder zur Verteidigung |
| Akteure                  | Spieler der am Zug ist                                                             |
| Vorbedingungen           | Genug Truppen im Umlenk des zu verschiebenden Gebiets; direkte Verbindung zum Zielgebiet |
| Auslösendes Ereignis     | Armeen einteilen                                                                    |
| Nachbedingungen bei Erfolg | Truppenverschiebung ist ausgeführt                                                 |
| Nachbedingungen bei Fehlschlag | Keine Veränderung der Truppenanzahl                                             |
| Eingesetzte Daten        | Gebiete in eigenem Besitz; Truppenanzahl in den verschiedenen Gebieten             |
| Angestoßene Daten        | Truppen                                                                            |
| Ablauf                   | 1. Wahl des Gebiets<br>2. Prüfen der direkten Verbindung zum Zielgebiet<br>3. Verschiebung der Truppen          |
| Erweiterungen            | -                                                                                  |
| Alternativen             | Keine Verschiebung von Truppen                                                     |

## Use-Case Bonuskarten eintauschen

| Geschäftsprozess         | Bonuskarten eintauschen                                                           |
|--------------------------|-----------------------------------------------------------------------------------|
| Ziel/Ergebnis            | Zusatztruppen erhalten                                                            |
| Akteure                  | Spieler der am Zug ist                                                            |
| Vorbedingungen           | Genug verschiedene/gleiche Karten                                                 |
| Auslösendes Ereignis     | Spieler tauscht Karten ein                                                        |
| Nachbedingungen bei Erfolg | Truppenanzahl                                                                   |
| Nachbedingungen bei Fehlschlag | Truppenanzahl bleibt unverändert                                           |
| Eingesetzte Daten        | Karten                                                                            |
| Angestoßene Daten        | Truppen                                                                           |
| Ablauf                   | 1. Spieler bestimmen in Spielrunde/unterschiedliche Karten<br>2. Falls Spieler am Zug ist deklarieren Karten zu tauschen<br>3. Prüfung ob Karten vorhanden sind<br>4. Eintauschen der Karten<br>5. Erhalten der Truppen |
| Erweiterungen            | -                                                                                 |
| Alternativen             | 3 gleiche Karten<br>3 verschiedene Karten                                         |

## Use-Case Spieler handeln

| Geschäftsprozess             | Spielerhandel                                                                 |
|------------------------------|-------------------------------------------------------------------------------|
| Ziel/Ergebnis                | Gründung einer Allianz; Kartentausch; Tausch von Territorien                  |
| Akteure                      | 2 beliebige Spieler                                                           |
| Vorbedingungen               | Bereitschaft zum Tausch; Karten; Territorien                                  |
| Auslösendes Ereignis         | Angebotsphase zum Handel                                                      |
| Nachbedingungen bei Erfolg   | Tausch abgeschlossen                                                          |
| Nachbedingungen bei Fehlschlag | Kein Handel                                                                 |
| Eingesetzte Daten            | Karten; Territorien; Allianzdaten                                             |
| Angestoßene Daten            | Karten; Territorien; Allianzdaten                                             |
| Ablauf                       | 1. Während am Zug stellt Spieler anderen Spieler einen Handel vor<br>2. Anderer Spieler akzeptiert<br>3. Ablehnen des Tauschgeschäfts<br>4. Akzeptieren des Tausches<br>5. Durchführung des Tausches |
| Erweiterungen                | -                                                                             |
| Alternativen                 | Kein Handelsgeschäft                                                          |

## Use-Case Auftrag erfüllen

| Geschäftsprozess             | Auftrag erfüllen                                                               |
|------------------------------|---------------------------------------------------------------------------------|
| Ziel/Ergebnis                | Erfüllung des Auftrags; Gewinn des Spieles                                      |
| Akteure                      | Alle Spieler                                                                    |
| Vorbedingungen               | Aufträge werden random verteilt                                                 |
| Auslösendes Ereignis         | Auftragbedingungen erfüllt                                                      |
| Nachbedingungen bei Erfolg   | SIEG                                                                            |
| Nachbedingungen bei Fehlschlag | Fortführung des Spieles                                                       |
| Eingesetzte Daten            | Auftragsdaten                                                                   |
| Angestoßene Daten            | Spielerstatus                                                                   |
| Ablauf                       | 1. Auftrag werden an Spieler verteilt<br>2. Spieler arbeiten im Geheimen an den Aufträgen<br>3. Spieler erfüllt seinen Auftrag<br>4. WIN |
| Erweiterungen                | -                                                                               |
| Alternativen                 | Spieler muss neuen Auftrag ziehen, da der derzeitige Auftrag nicht zu erfüllen ist |