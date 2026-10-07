# Montagerechner – Lohnzettel Vorrechner

Ein Rechner für Monteure in Österreich, um den Lohnzettel vorab abzuschätzen: Montage- und Bürotage im Kalender eintragen, und der Rechner zeigt Zuschläge, Zulagen, ZA- und Ruhezeit-Topf sowie ein geschätztes Netto.

Eine einzige HTML-Datei ohne Installation und ohne Server. Alle Daten bleiben im eigenen Browser.

## Funktionen

- **Kalender** mit Büro, Homeoffice, Montage, Montage + Reise, Zeitausgleich und Ruhezeit
- **Arbeitsmodelle** 5/2, 10/4, 6/1/4/3 und ein eigenes Modell. Bei 10/4 und 6/1/4/3 zählt das Wochenende als normaler Arbeitstag.
- **Überstunden**: Samstag 50 %, Sonntag §68/1, Feiertag bzw. über 10 h §68/2, 50-h-Wochengrenze
- **ZA-Topf** mit Maximum und Überlauf
- **Ruhezeit-Topf**: Sonntagsstunden kommen 1:1 dazu, und ZA wird zuerst daraus genommen
- **Feiertage** für Österreich sowie pro Montage-Tag für Deutschland (je Bundesland), Schweiz, Frankreich, Italien, Niederlande, Belgien, Luxemburg und Spanien
- **Lehrlinge** mit reduziertem SV-Satz
- **Stundensatz** = Grundgehalt ÷ 143 (Teiler einstellbar)
- Urlaubsgeld (§67 EStG), Prämien und Zuschläge, Taggeld, On-Site-Zulage, Lenkzeit
- **Datensätze** speichern, laden, als Datei exportieren und importieren
- **Einstellungen** für Grundlohn und Standard-Stunden pro Leistungsart
- Hell- und Dunkelmodus

## Rechengrundlagen (Stand 2026)

- **SV-Dienstnehmeranteil** 18,07 %, AV-Anteil bei geringem Einkommen reduziert, gedeckelt bei der Höchstbeitragsgrundlage von 6.930 €/Monat. Bei Sonderzahlungen sind es 17,07 %.
- **Lohnsteuer** nach dem Tarif 2026, inklusive Verkehrsabsetzbetrag (496 €) und Werbungskostenpauschale
- **Steuerfreie Zuschläge (§68 EStG):**
  - Sonn- und Feiertagszuschläge plus Feiertagsarbeitsentgelt bis 400 €/Monat
  - Überstundenzuschläge für die ersten 15 Stunden, höchstens 170 €/Monat
- **Taggeld** steuer- und SV-frei bis zum Inlands- bzw. Auslandsreisesatz des Einsatzlandes, z. B. Deutschland 35,30 €. Der Rest ist steuerpflichtig.
- **Sonderzahlungen** mit 6 % nach Abzug der SV, 620 € Freibetrag, 2.100 € Freigrenze
- Nicht berücksichtigt: Pendlerpauschale, Familienbonus und andere persönliche Absetzbeträge

## Benutzung

- **Online:** über GitHub Pages öffnen (Link rechts unter „About“ bzw. in den Repository-Einstellungen)
- **Offline:** `index.html` herunterladen und im Browser öffnen

## Hinweis

Alle Ergebnisse sind **Näherungswerte**. Sozialversicherung und Lohnsteuer sind vereinfacht berechnet, und Kollektivverträge sowie Betriebsvereinbarungen können abweichen. Das ist keine Lohn- oder Steuerberatung. Verbindlich ist nur der Lohnzettel des Arbeitgebers.

## Lizenz

[MIT](LICENSE)
