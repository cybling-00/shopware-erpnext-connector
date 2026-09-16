# CYBLINGE Shopware-ERPNext Connector

Der CYBLINGE Shopware-ERPNext Connector verbindet Shopware 5 und Shopware 6 mit ERPNext. Er ersetzt fehleranfällige CSV-Exporte durch nachvollziehbare, konfigurierbare Synchronisationen für Shop, Warenwirtschaft und kaufmännische Prozesse.

- Website: [cyblinge.de](https://cyblinge.de/)
- Produktseite: [Shopware-ERPNext Connector](https://cyblinge.de/produkte/shopware-connector/)
- Lizenz, Beratung oder Testversion: [hello@cyblinge.de](mailto:hello@cyblinge.de)

## Unterstützte Systeme

- ERPNext v14, v15 und v16
- Shopware 5 über die REST-API
- Shopware 6 über die Admin-API und OAuth

## Funktionen

### Artikel, Varianten, Preise und Steuern

- Synchronisation von Artikeln in beide Richtungen
- Unterstützung von Varianten und eindeutiger Produktidentität
- Übertragung von SKU, Artikelnummer, EAN, Kategorien, Hersteller, Sichtbarkeit und weiteren konfigurierten Feldern
- Übertragung und Zuordnung von Preisen, Währungen und Preisregeln
- Übertragung von Shopware-Steuerklassen und Steuersätzen, einschließlich 0 %, 7 % und 19 %
- Unterstützung von Shopware-5-Steuer-IDs sowie Shopware-6-Tax-Relations
- Bestandsabgleich mit konfigurierten Lagern und Schutzmechanismen

### Kunden und Adressen

- Synchronisation von Privat- und Geschäftskunden
- Übertragung von Kundengruppen, USt-ID und stabilen externen IDs
- Synchronisation von Rechnungs- und Lieferadressen
- Schutz vor Dubletten durch eindeutige Zuordnungen und idempotente Verarbeitung

### Bestellungen, Status und Retouren

- Import von Shopware-Bestellungen nach ERPNext
- Übertragung von Positionen, Mengen, Rabatten, Gutscheinen, Versandkosten, Steuern und Währungen
- Automatische Kundenzuordnung oder Kundenerstellung
- Statusfilter für Bestell-, Zahlungs- und Lieferstatus
- Konfigurierbares Statusmapping für Shopware 5 und Shopware 6
- Unterstützung für Storno, Retoure und Erstattung
- Bestellexport von ERPNext nach Shopware mit gültiger Kauflizenz

### Synchronisation und Automatisierung

- Delta-Synchronisation mit Cursor, Overlap und Wiederanlauf
- Initialimporte mit Seitenverwaltung und Batchgrößen
- Webhooks für ereignisbasierte Verarbeitung
- Queue-basierte Verarbeitung mit Prioritäten, Claims und Heartbeats
- Idempotenzschutz gegen doppelte Verarbeitung
- Retry-Logik, Backoff, manuelle Wiederaufnahme und kontrolliertes Überspringen
- Konfliktstrategien: ERP Wins, Shopware Wins und Latest Wins
- Scheduler für regelmäßige Synchronisationen, Reconciliation und Bestandsabgleiche

### Betrieb, Sicherheit und Transparenz

- Dashboard mit Lizenzstatus, Queue-Zustand, API-Status, Cursor-Lag und letzten erfolgreichen Synchronisationen
- Health-Snapshots, Dry Runs und Action-Required-Hinweise
- Pausen für Scheduler und Queue-Verarbeitung
- Strukturierte Sync-Logs, Fehlerklassen und datenschutzkonforme Fehlerredaktion
- Schutz von Zugangsdaten durch Passwortfelder
- HTTPS-, URL- und Host-Validierung sowie Schutz vor unsicheren Zieladressen
- Konfigurierbares Feldmapping für Kunden, Artikel, Preise, Steuern, Aufträge und Bestände

## Lizenz und kostenlose Nutzung

Ohne Kauflizenz können pro ERPNext-Site und UTC-Kalendermonat bis zu zehn kombinierte Bestellimporte oder Artikelsynchronisationen genutzt werden.

Eine Kauflizenz wird benötigt für:

- weitere Synchronisationen über das Monatskontingent hinaus
- eigenständige Kundensynchronisationen
- Bestellexporte
- Bestandssynchronisationen
- Commercial Documents und weitere kostenpflichtige Funktionen

Die Nutzung, Änderung, Weitergabe oder Umgehung von Lizenzmechanismen ist ausschließlich im Rahmen der geltenden Lizenzbedingungen zulässig.

## Lizenz oder Testversion anfragen

Für eine Kauflizenz, eine Testversion, Beratung oder Unterstützung bei der Einführung wenden Sie sich an [hello@cyblinge.de](mailto:hello@cyblinge.de).

Weitere Informationen finden Sie auf [cyblinge.de](https://cyblinge.de/) und auf der [Produktseite des Shopware-ERPNext Connectors](https://cyblinge.de/produkte/shopware-connector/).
