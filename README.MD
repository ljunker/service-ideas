# Docker-Service-Ideen

## Umgesetzt

* **QR-Code Service** - [GitHub](https://github.com/ljunker/qr-code-service) · [Service](https://qr.kryptikk.de)
* **Temporary File Drop & Tiny Pastebin & One-Time Secret** - [GitHub](https://github.com/ljunker/pasty) · [Service](https://pasty.kryptikk.de)

## Ideen

* [ ] **Webhook Inspector** — Nimmt beliebige Webhooks entgegen, speichert Header und Body und zeigt sie in einer kleinen Weboberfläche an. Praktisch zum Testen und Debuggen externer Dienste.

* [ ] **Dead Man’s Switch** — Andere Systeme pingen regelmäßig einen Endpoint. Bleibt ein erwarteter Ping aus, meldet der Service einen Fehler per Mail, ntfy, Discord oder einem anderen Kanal.

* [ ] **Certificate Watcher** — Überwacht TLS-Zertifikate mehrerer Domains und warnt bei baldiger Ablaufzeit, geändertem Issuer oder ungültigen Hostnamen.

* [ ] **HTTP Change Detector** — Überwacht Webseiten oder einzelne CSS-Selektoren und erkennt Änderungen an Texten, Preisen oder Statusinformationen.

* [x] **One-Time Secret** — Speichert kurze Geheimnisse und erzeugt Links, die nur einmal oder innerhalb einer festgelegten Zeit verwendet werden können.

* [x] **Temporary File Drop** — Dateien werden hochgeladen, erhalten einen temporären Link und werden nach einer bestimmten Zeit automatisch gelöscht.

* [x] **Tiny Pastebin** — Ein kleiner Pastebin-Service für Text und Code mit Syntax Highlighting, Ablaufdatum und optionalem Passwortschutz.

* [x] **QR-Code Service** - Kleiner Service zum Erstellen von QR-Codes

* [ ] **JSON Bin** — Eine einfache REST-API zum Speichern und Abrufen beliebiger JSON-Dokumente. Optional mit Versionierung und API-Keys.

* [ ] **Cron Dashboard** — Cronjobs melden sich nach erfolgreichem Lauf beim Service. Das Dashboard zeigt, wann ein Job zuletzt erfolgreich ausgeführt wurde und welche Jobs überfällig sind.

* [ ] **Docker Image Update Reporter** — Prüft regelmäßig verwendete Docker-Images und zeigt an, ob sich der Remote-Digest geändert hat oder neuere Versionen verfügbar sind.

* [ ] **Port Monitor** — Überwacht TCP-Ports oder HTTP-Endpunkte und zeigt Status, Antwortzeit, Uptime und letzte Fehler an.

* [ ] **Personal URL Shortener** — Erzeugt kurze URLs für häufig verwendete Links. Optional mit Statistik, QR-Code und Ablaufdatum.

* [ ] **Screenshot Service** — Erstellt mit Playwright Screenshots oder PDFs beliebiger Webseiten und liefert diese per API zurück.

* [ ] **OpenGraph Preview Generator** — Analysiert Webseiten und extrahiert Titel, Beschreibung, Favicon und OpenGraph-Bilder für Link-Vorschauen.

* [ ] **Read-it-later Service** — Speichert Webseiten oder Artikel lokal, extrahiert den eigentlichen Inhalt und stellt eine einfache Leseoberfläche bereit.

* [ ] **RSS Builder** — Überwacht Webseiten ohne eigenen RSS-Feed und erzeugt anhand bestimmter Seitenelemente automatisch einen Feed.

* [ ] **Universal Converter API** — Bietet kleine Konvertierungsfunktionen wie Einheiten, Unix-Zeit, Base64, UUIDs, Farben und Byte-Größen über eine API und Weboberfläche an.

* [ ] **Regex Playground** — Erlaubt das Testen regulärer Ausdrücke gegen beliebige Texte und visualisiert gefundene Matches und Gruppen.

* [ ] **JWT Inspector** — Dekodiert JWTs und zeigt Header, Payload und Ablaufzeit an. Optional können Signaturen gegen hinterlegte Schlüssel geprüft werden.

* [ ] **JSON Schema Validator** — Validiert JSON-Daten gegen JSON-Schemas und stellt dafür sowohl eine kleine Weboberfläche als auch einen REST-Endpunkt bereit.

* [ ] **Mock API Server** — Erzeugt einfache Fake-APIs anhand einer Konfigurationsdatei und liefert feste, zufällige oder verzögerte Responses zurück.

* [ ] **Feature Flag Service** — Ein kleiner zentraler Service zum Aktivieren und Deaktivieren von Features für verschiedene Anwendungen und Umgebungen.

* [ ] **Maintenance Page Controller** — Verwaltet den Maintenance-Status mehrerer Anwendungen und stellt eine API bereit, die Reverse Proxies oder Anwendungen abfragen können.

* [ ] **Tiny Audit Log** — Andere Anwendungen können Events wie Logins, Deployments oder Konfigurationsänderungen an den Service schicken. Diese werden zentral gespeichert und durchsuchbar gemacht.

* [ ] **API Dashboard** — Zeigt eine zentrale Übersicht aller eigenen APIs inklusive URL, Healthcheck, Version, Dokumentation und Antwortzeit.

* [ ] **Random Data API** — Generiert Testdaten wie Namen, UUIDs, Datumswerte, Adressen oder frei konfigurierbare JSON-Strukturen für Entwicklung und Tests.

* [ ] **Markdown Renderer** — Nimmt Markdown entgegen und erzeugt daraus HTML oder PDF. Optional mit Templates, Syntax Highlighting und Mermaid-Diagrammen.

* [ ] **Website Metadata Archive** — Überwacht Webseiten und speichert historische Informationen wie HTTP-Status, IP-Adresse, TLS-Daten, Header und Antwortzeiten.

* [ ] **Minimal Queue Service** — Eine kleine HTTP-basierte Message Queue mit Endpoints zum Einstellen und Abholen von Nachrichten. Später erweiterbar um ACKs, Retries und Dead-Letter-Queues.

