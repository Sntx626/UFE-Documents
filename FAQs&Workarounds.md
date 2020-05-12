# FAQ & Workarounds - ein Port aus dem Discord channel #faqs-workarounds
###### Ursprünglich erstellt durch Juno_Narrock, überarbeitet durch Sntx626 (Leo)
Dies hier ist unsere Zusammenfassung für alle häufig gestellten Fragen und Bugs. Solltet ihr hier keine Antwort finden, erstellt gerne einen Beitrag in dieser Sektion.

## Fragen

#### Was tun wenn alle Workarounds nicht funktionieren?
Einen kurzen trinken (FSK18) und dann über folgende Vorgehensweise den Account zurücksetzen (Achtung geht nur alle 48h): RobertsSpaceIndustries/Settings/Character Reset

#### Wo finde ich alle Links die ich bei der UFE benötige?
Entweder unter #willkommen-charter (öffentliche Links) oder #deleted-channel (interne Links)

#### Was machen wenn ich Zeit sparen will beim PTU Download?
Gehe in deinen Installationsordner bis du den Ordner "LIVE" vor dir siehst.
Copy & Paste diesen Ordner. ACHTUNG nicht überschreiben!
Umbenennen von "LIVE" zu "PTU".
Launcher öffnen.
Auf "Live" klicken und zu "PTU" wechseln. (Vorher natürlich Account über Settings auf RSI ins PTU kopieren)
Download klicken.

#### Wo findet man das Mining Tool + Attachments?

- Levski
- Area 18
- Lorville
- New Babbage

#### PTU? Was ist das?
Das PTU steht auch für Public Test Universe und ist vorab zum Testen der neuen Patches da. Die Spieler bekommen das nach folgender Reihenfolge freigeschaltet: Evocati (spezielle Tester unter Verschwiegenheitserklärung), Concjerge (Spender), Player (Spieler).
Jede Phase dauert ca. 1-3 Wochen.
Sobald man Zugang erhalten hat, kann man seinen Account ins PTU kopieren auf der RSI Seite unter "Settings/PublicTestUniverse".
Danach im Launcher umstellen von "LIVE" auf "PTU".

#### Gibt es ein SC-Gebet?
"Chris Roberts, der du bist im Verse, geheiligt werde deine Galaxie. Deine Version 4.0 komme, Deine Vision geschehe, wie im PTU, so auch im PU. Unsere täglichen Bugfixes gib uns heute, und vergib uns unsere Ungeduld, wie auch wir vergeben Deine Wipes. Und führe uns nicht in den 30tausender, sondern erlöse uns von den Desyncs. Denn Dein ist der Weltraum und die Planeten und die Monde, in Persistenz. Amen"

#### Wo finde ich den UFE Kalender?
[Google Calendar Link](https://calendar.google.com/calendar?cid=M2hwcWpqbGJsa2RuZ2ZkbXZtcWxsMmxxMjBAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

#### Wo finde ich den Orga Hangar zum Eintragen meiner Schiffe?
[Google Forms Link](https://forms.gle/1Cj4aqw3EpkB46bj7)

#### Wo finde ich die Star Citizen Roadmap?
[Star Citizen Roadmap](https://robertsspaceindustries.com/roadmap/board/1-Star-Citizen)

#### Wo finde ich den DPS Calculator und was macht dieser?
[Erkul DPS Rechner](https://www.erkul.games/calculator)
Hiermit könnt ihr euer Schiffs Loadout planen und kalkulieren.

#### Wo finde ich Handelsrouten und kann diese planen?
[gallog.gg](https://www.gallog.co/)
Hier findet ihr alles zu Handelsrouten, Mining etc...
Alle Trading Routen und Items findet ihr hierin:
[Google Docs Link](https://docs.google.com/spreadsheets/d/1uJia0JCt7sL3bvI_89ed-2TThnITCbMPN2yKbf-veAY/edit#gid=809330379)

#### Hilfe zu Discord findet ihr bei uns auf Spectrum unter:
[Orga Spektrum](https://robertsspaceindustries.com/spectrum/community/CDTC/forum/173439/thread/discord-info-s)

#### Wo kann ich meinen RP Character anlegen, bzw. meine Geschichte ablegen?
Die Charakterdatenbank der UFE findest du hier:
[UFE-Charakterdatenbank](https://robertsspaceindustries.com/spectrum/community/CDTC/forum/176194?page=1&sort=hot)

#### Wo finde ich die Absturzstelle der Javelin auf Daymar?
[Absturzstelle der Javelin auf Daymar](https://sc-workarounds.de/2019/05/17/javelin-wrack-daymar/)

#### Gibt es eine Mining Guide?
[Mining Guide](https://www.space4games.com/star-citizen/star-citizen-der-ultimative-mining-guide/id-1011/)

## Bugs

#### Launcher zeigt keine Buttons
Im Launcher ausloggen und diesen über TaskManager oder die Windows Schnellzugriffleiste schließen (klein Pfeil rechts im Eck). Danach Launcher neu starten und neu anmelden.

#### Spiel bringt beim Start Launcher-Fehler, Fehlermeldung: CigDataPatcher.node not found

1. Windows Suche öffnen
2. "entfernen" eintippen 
3. Programme hinzufügen und entfernen anwählen
4. nach "RSI Launcher" suchen
5. Rechtsklick -> Deinstallieren
6. RSI Homepage neu downloaden + Installieren
7. RSI Launcher starten
8. Settings Library Folder
9. Change (hier dann in den mit der vorhandenen Installation wechseln)
10. Verify (dann downloaded er kurz ein paar Info's und du bist fertig)

#### Fehler-Bild: Charakter unsichtbar | Mobi geht nicht | Black Screen nach InGame Selbstmord
Alle Fahrzeuge die mit anderen Fahrzeugen im Hangar etc. gestored worden sind claimen. Zur Not auf einer anderen Station.
Falls es danach nicht geht, Charakter Geschlecht wechseln (man kann auch hier den Rest claimen falls man anderenfalls ohne Anzug spawned und nicht bis zum Schiff kommt).
Nach claim aller Schiffe/Fahrzeuge das Geschlecht wieder wechseln.

#### Login Fehler nach Logout in Schiffsbett
Kein Workaround bisher - Account resetten per Settings/Character Reset.

#### Gameglass bekommt keine Verbindung
Ursache: Der eingestellte DNS Server kann die GG Server Adressen nicht auflösen (vermutlich da die Adresse eine IPv6 Adresse ist)
Lösung: Unter den Netzwerkadapter Einstellungen unter Eigenschaften - Erweitert - IPv4 - Eigenschaften -> Dort manuell folgende DNS Server eintragen:
Primärer DNS Server: 8.8.8.8
Sekundärer DNS Server: 8.8.4.4

#### Can't join Session because it's full
Fehlercode: 60015.
Spiel neustarten, dann sollte es gehen.

#### Leeres inGame Menü ohne Buttons oder Error 10008
User Folder löschen und Session neu starten.
Gegebenenfalls so oft wiederholen bis es geht.

#### Schiff despawned oder Schiff kann nicht retrieved werden nach 30K Timeout
Schiff im Admin Office beladen (mit egal was und egal wieviel).
Schiff wo anders claimen.
Alle weiteren Schiffe ebenso.
Nach claim Zeit, kann man das Schiff wieder überall spawnen.

#### Neuer Workaround - FPS Mining
Wenn Ihr die kleinen Stücke nicht storen könnt (Stow funktioniert nicht):

- "F" gedrückt halten
- CARRY auswählen
- Das Mineral in der rechten Hand mit gedrückter "F" Taste anschauen
- Jetzt "STOW" auswählen
- Anschließend können die restlichen Stücke gleich wieder mit "STOW" aufgehoben werden, ohne "CARRY"

#### Kein Aufstehen von Toilette auf dem Schiff möglich!
Shift + U / Space (Leertaste) drücken und der Char sollte aufstehen.

#### Pixel Flimmern (Blenden) auf Planeten
Bedingt durch die Grafikkarte, kann ggfs. durch Neuinstallation des GPU Treibers behoben werden.
Bekannte GPU's: GTX 1080
