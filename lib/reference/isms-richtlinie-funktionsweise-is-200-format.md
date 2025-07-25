---
kind: project
status: active
slice: personal
description: "ISMS Richtlinie Funktionsweise (IS-200 Format)"
aliases: ["ISMS Richtlinie Funktionsweise (IS-200 Format)"]
requires: []
wants: []
type: project
context: professional
client: EKIBA
created: 2025-07-08
uid: 202507102334
uuid: 202507102334
---

# IS-200 - ISMS Richtlinie - EKIBA

**Grundlage:** Vorlage.dotx (Standarddokumentenvorlage EOK)

## 1 Dokumenteninformation

### 1.1 Dokumentendaten

| Typ        | Dokumentenverantwortlicher*in | Version |
| ---------- | ----------------------------- | ------- |
| Richtlinie | ISB (Alfred Ernst)            | V 1.0   |

### 1.2 Dokumentenhistorie

| Letzte Änderung | Bearbeiter*in | Status | Freigabe am | Freigabe durch |
|-----------------|---------------|--------|-------------|----------------|
| 2025-06-30 | ISB | Aktiv | 2025-06-30 | Geschäftsleitende Oberkirchenrätin (Uta Henke) |

### 1.3 Beteiligte Personen

| Name           | E-Mail-Adresse           | Telefonnummer | Rolle                |
| -------------- | ------------------------ | ------------- | -------------------- |
| Alfred Ernst   | Alfred.Ernst@ekiba.de    | 0721-9175-603 | ISB/DSB              |
| Yannick Lackus | Yannick.Lackus@ekiba.de  | 0721-9175-780 | Projektmanagement    |
| Timo Geiss     | Timo.Geiss@ekiba.de      | 0721-9175-603 | Abteilungsleitung IT |
| Robin Leitner  | Robin.leitner@secudor.de | 0721-9175-578 | Externer Berater     |

### 1.4 Mitgeltende Dokumente

- Informationssicherheitsleitlinie EOK
- IT-Sicherheitskonzept EOK

### 1.5 Rechtliche Grundlage

- ISO/IEC 27001:2022 (Informationssicherheits-Managementsysteme)
- DSG-EKD (Datenschutzgesetz der Evangelischen Kirche in Deutschland)  
- ITSVO-EKD (Informations- und Telekommunikations-System-Verordnung)
- EU-DSGVO (soweit anwendbar)

## 2 Allgemeines

### 2.1 Zweck dieses Dokumentes

Als Ergänzung und Konkretisierung der Informationssicherheitsleitlinie werden in dieser Richtlinie grundlegende Arbeitsweisen des ISMS nach ISO/IEC 27001:2022 spezifiziert und die praktische Anwendung der ISMS-Ordnerstruktur erläutert.

### 2.2 Geltungsbereich und Anwender*innen

Der Geltungsbereich dieser Richtlinie erstreckt sich über den gesamten Evangelischen Oberkirchenrat Karlsruhe (EOK) und die EH-Freiburg und ist für alle Mitarbeiter sowie externe Mitarbeitende verbindlich.

### 2.3 Verantwortlichkeiten

Das ISMS wird durch den Informationssicherheitsbeauftragten verwaltet und geprüft auf Aktualität.

### 2.4 Einhaltung

Diese Richtlinie ist für alle Mitarbeitenden des EOK und der EH-Freiburg verpflichtend. Die Geschäftsleitung trägt die Gesamtverantwortung für die Durchsetzung.

### 2.5 Sonderregelungen und Abweichungen

Abweichungen von dieser Richtlinie bedürfen der schriftlichen Genehmigung durch den ISB und die Geschäftsleitung.

## 3 ISMS-Ordnerstruktur und Arbeitsweise

### 3.1 Grundsätze des ISMS

Das ISMS arbeitet nach den folgenden Grundsätzen:

- Das ISMS orientiert sich an der **ISO/IEC 27001:2022** in der jeweils aktuellen Fassung und setzt deren Anforderungen um. Dies stellt eine bewusste Entscheidung dar, die von der allgemeinen Empfehlung der ITSVO-EKD abweicht.
- Es berücksichtigt die für die Organisation relevanten gesetzlichen Vorgaben in Sachen Informationssicherheit (siehe Abschnitt 1.5)
- Sämtliche Sicherheitsmaßnahmen werden nach dem **PDCA-Zyklus** (Plan-Do-Check-Act) koordiniert und kontinuierlich verbessert.

### 3.2 ISMS-Ordnerstruktur

Das ISMS nutzt eine strukturierte Ordnerlogik, die den praktischen Arbeitsablauf widerspiegelt:

#### **00_Organisation**
**Inhalt:** Organigramme, Rollenbeschreibungen, Teamstrukturen, Verantwortungsmatrizen

**Zweck und praktische Anwendung:**
Dieser Ordner enthält die organisatorischen Grundlagen des ISMS und beantwortet die Frage "Wer macht was?". Hier werden alle strukturellen Dokumente abgelegt, die das Fundament für das gesamte Informationssicherheitsmanagement bilden.

**Typische Dokumente:**
- **Organigramm des Informationssicherheitsteams** - Zeigt die Berichtswege und Hierarchien innerhalb der Sicherheitsorganisation
- **Detaillierte Rollenbeschreibungen** - Definiert präzise Aufgaben, Befugnisse und Verantwortlichkeiten für ISB, IT-Leiter, etc.
- Statement of Applicability: Übersicht der aus der ISO27001 geforderten Maßnahmen und der Anwendbarkeit für den EOK.

**Warum hier:** Diese Dokumente ändern sich nur selten und müssen für alle Beteiligten jederzeit schnell auffindbar sein. Sie bilden das strukturelle Rückgrat des ISMS und werden bei Audits als erstes geprüft. 
#### **01_Leitlinien**
**Inhalt:** Informationssicherheitsleitlinie, grundlegende Prinzipien, strategische Vorgaben

**Zweck und praktische Anwendung:**
Dieser Ordner enthält die Grundsatzdokumentation des ISMS und beantwortet die Frage "Was sind unsere Sicherheitsziele und Grundprinzipien?". Hier stehen die übergeordneten Dokumente, die die Richtung für alle anderen Sicherheitsmaßnahmen vorgeben.

**Das zentrale Dokument:**
- **Informationssicherheitsleitlinie** - Das einzige, aber zentrale Strategiedokument, das alle wesentlichen Elemente enthält:
  - Die drei Sicherheitsprinzipien (Sicherheit vor Komfort, Minimal-, Need-to-Know-Prinzip)
  - Messbare Sicherheitsziele für Vertraulichkeit, Integrität und Verfügbarkeit
  - Spezielle Anforderungen für den Umgang mit kirchlichen Daten
  - Management-Commitment und Verantwortlichkeiten
  - Verweis auf die ISMS-Ordnerstruktur und deren Anwendung

**Warum hier:** Die Leitlinie ist das fundamentale Dokument, das die strategische Ausrichtung definiert und nur bei grundlegenden Änderungen der Sicherheitsstrategie angepasst wird. Sie dient als zentrale Referenz für alle operativen Entscheidungen und wird bei der jährlichen Managementbewertung überprüft.

#### **02_Verzeichnisse**
**Inhalt:** Listen, Register und Analysen zur Erfassung aller sicherheitsrelevanten Elemente

**Zweck und praktische Anwendung:**
Dieser Ordner enthält alle strukturierten Listen und Analysen des ISMS und beantwortet die Frage "Was haben wir und welche Risiken bestehen?". Diese Verzeichnisse bilden die Basis für alle Entscheidungen und werden regelmäßig aktualisiert.

**Typische Dokumente (nicht abschließend):**
- **Dienstleisterliste des EOK** - Übersicht aller externen Partner und deren Sicherheitsrelevanz
- **Admin-Accounts Dokumentation** - Register privilegierter Benutzerkonten und deren Verwaltung
- **Gefährdungsanalysen** - Systematische Bewertung von Sicherheitsbedrohungen nach ISO 27001
- **KPIs (Key Performance Indicators)** - Messgrößen zur Bewertung der ISMS-Leistung
- **Schutzbedarfslisten** - Klassifizierung der Informationen und Systeme nach Schutzbedarf
- **Auditpläne** - Terminplanung für interne und externe Audits

**Warum hier:** Diese Verzeichnisse sind die "lebenden Dokumente" des ISMS, die kontinuierlich gepflegt werden müssen. Sie bilden die Grundlage für Risikoentscheidungen, Auditplanung und die Überwachung der Sicherheitsleistung.

#### **03_Richtlinien**
**Inhalt:** Spezifische Handlungsanweisungen, Verfahrensanweisungen und Notfallkonzepte

**Zweck und praktische Anwendung:**
Dieser Ordner enthält alle operativen Richtlinien des ISMS und beantwortet die Frage "Wie wird etwas konkret gemacht?". Diese Dokumente übersetzen die strategischen Vorgaben aus den Leitlinien in praktische, umsetzbare Arbeitsanweisungen für den täglichen Betrieb.

**Zielgruppenorientierte Struktur:**

**Anwenderrichtlinien:**
- Regelungen für Mitarbeitende (E-Mail-Sicherheit, Arbeitsplatz-Sicherheit, mobiler Zugriff)

**Adminrichtlinien:** 
- Spezifische Vorgaben für IT-Verantwortliche (Systemkonfiguration, Rechtevergabe, Monitoring)

**Einzelfallrichtlinien:**
- **Change-Richtlinie** - Verfahren für Systemänderungen und deren Genehmigung
- **Notfallplan** - Strukturierte Abläufe für Sicherheitsvorfälle und Notfallsituationen  
- **Zugangsrichtlinie** - Regelungen für die Vergabe und Verwaltung von Systemzugängen

**Warum hier:** Diese Richtlinien sind die operativen Umsetzungsdokumente, die Mitarbeitende in konkreten Situationen anwenden. Sie werden bei Änderungen der Technik, neuen Bedrohungen oder nach Sicherheitsvorfällen aktualisiert und müssen für alle Beteiligten leicht auffindbar sein.

#### **04_Informationen**
**Inhalt:** Zusätzliche Informationen, Pläne und Prozessbeschreibungen zur Unterstützung der ISMS-Prozesse

**Zweck und praktische Anwendung:**
Dieser Ordner enthält ergänzende Dokumentationen und Hilfsmittel, die die Richtlinien unterstützen und beantwortet die Frage "Welche zusätzlichen Informationen benötigen die Verantwortlichen?". Diese Dokumente liefern den Kontext und die Details für die praktische Umsetzung der Sicherheitsmaßnahmen.

**Typische Dokumente (nicht abschließend):**
- **Gebäudepläne** - Physische Sicherheitsstrukturen und Zugangswege für Notfallplanung
- **Vorfallsprozessbeschreibungen** - Detaillierte Ablaufdiagramme für verschiedene Incident-Szenarien
- **Netzpläne** - Technische Infrastrukturdokumentation für IT-Sicherheitsanalysen
- **Change-Prozess PDFs** - Ergänzende Dokumentation zu Änderungsverfahren mit Formularen und Checklisten
- **Technische Sicherheitskonzepte** - Detaildokumentationen für komplexe IT-Systeme
- **Schulungsunterlagen** - Präsentationen und Handbücher zur Unterstützung der Awareness-Maßnahmen

**Warum hier:** Diese Informationen sind wichtige Arbeitshilfen, die über die reinen Richtlinien hinausgehen. Sie werden als Referenz für die praktische Umsetzung benötigt und müssen den Verantwortlichen schnell zugänglich sein.

#### **05_Awareness**
**Inhalt:** Schulungsunterlagen, Sensibilisierungsmaterial und Kommunikationsmaßnahmen

**Zweck und praktische Anwendung:**
Dieser Ordner enthält alle Materialien zur Förderung des Sicherheitsbewusstseins und beantwortet die Frage "Wie werden Mitarbeitende für Informationssicherheit sensibilisiert?". Diese Dokumente unterstützen die kontinuierliche Schulung und Bewusstseinsbildung aller Beteiligten.

**Typische Dokumente (nicht abschließend):**
- **Präsentationen für Mitarbeiterschulungen** - Interaktive Schulungsunterlagen zu aktuellen Sicherheitsthemen
- **Sicherheitsleitfäden** - Praxisnahe Anleitungen für den sicheren Umgang mit IT-Systemen
- **Phishing-Awareness-Material** - Beispiele und Erklärungen zu aktuellen E-Mail-Bedrohungen
- **Sicherheitstipps und Newsletter** - Regelmäßige Kommunikation zu Sicherheitsthemen
- **Onboarding-Checklisten** - Sicherheitsschulungen für neue Mitarbeitende
- **Incident-Response-Karten** - Schnellreferenzen für den Umgang mit Sicherheitsvorfällen

**Warum hier:** Awareness-Materialien müssen aktuell, verständlich und leicht zugänglich sein. Sie werden regelmäßig überarbeitet, um neue Bedrohungen und veränderte Arbeitsweisen zu berücksichtigen.

#### **06_Verträge & Vereinbarungen**
**Inhalt:** Vertragsvorlagen und ISB-Kommentierungen zu externen Verträgen

**Zweck und praktische Anwendung:**
Dieser Ordner enthält vertragliche Hilfsmittel und Bewertungen und beantwortet die Frage "Welche Vertragsvorlagen gibt es und wie bewertet der ISB externe Verträge?". Diese Sammlung unterstützt die Vertragsgestaltung und -bewertung aus Informationssicherheitssicht.

**Typische Dokumente (nicht abschließend):**
- **Vertragsvorlagen für IT-Dienstleister** - Standardisierte Sicherheitsklauseln und Anforderungen
- **NDA-Vorlagen (Geheimhaltungsvereinbarungen)** - Muster für Vertraulichkeitsvereinbarungen mit Externen
- **SLA-Templates** - Vorlagen für Service Level Agreements mit Sicherheitsanforderungen
- **ISB-Kommentare zu Dienstleisterverträgen** - Bewertungen und Empfehlungen zu eingegangenen Verträgen
- **Checklisten für Vertragsverhandlungen** - Prüfpunkte für Informationssicherheitsaspekte
- **Rechtliche Referenzdokumente** - Musterklauseln und juristische Orientierungshilfen

**Warum hier:** Vertragsvorlagen standardisieren Sicherheitsanforderungen und ISB-Kommentare dokumentieren Bewertungen für spätere Referenz. Diese Dokumente werden bei neuen Dienstleisterbeziehungen und Vertragsverhandlungen benötigt.

#### **07_Dokumentationen**
**Inhalt:** Nachweisdokumentationen und chronologische Aufzeichnungen

**Zweck und praktische Anwendung:**
Dieser Ordner enthält alle Dokumentationen zur Nachweispflicht und beantwortet die Frage "Was ist wann passiert und wie wurde darauf reagiert?". Diese Aufzeichnungen dienen der Compliance und als Grundlage für Verbesserungsmaßnahmen.

**Struktur und typische Dokumente:**
- **Kontrollen/** - Audit-Nachweise und Prüfungsergebnisse interner Kontrollen
- **Stellungnahmen/** - Offizielle Antworten auf Behördenanfragen und externe Prüfungen
- **Vorfallsdokumentation/** - Detaillierte Aufzeichnungen zu Sicherheitsvorfällen und deren Behandlung
- **Compliance-Nachweise/** - Dokumentation der Einhaltung gesetzlicher und vertraglicher Anforderungen
- **Managementbewertungen/** - Protokolle und Ergebnisse der jährlichen ISMS-Reviews
- **Korrekturmaßnahmen/** - Dokumentation von Verbesserungsmaßnahmen und deren Umsetzung

**Warum hier:** Diese Dokumentationen sind rechtlich und operativ erforderlich. Sie werden chronologisch geführt und dienen als Nachweis für Auditoren, Behörden und das Management zur Bewertung der ISMS-Wirksamkeit.

#### **08_Audits**
**Inhalt:** Auditplanungen, Durchführungsunterlagen und Ergebnisse

**Zweck und praktische Anwendung:**
Dieser Ordner enthält alle auditbezogenen Dokumente und beantwortet die Frage "Wie wird die Wirksamkeit des ISMS systematisch überprüft?". Diese Materialien unterstützen sowohl die Planung als auch die Durchführung und Nachverfolgung von Audits.

**Struktur und typische Dokumente:**
- **Dienstleister/Auditberichte/** - Ergebnisse externer Prüfungen von IT-Dienstleistern und Partnern
- **Dienstleister/Checklisten/** - Standardisierte Prüfvorlagen für externe Audits
- **TOMs/Auditberichte/** - Ergebnisse interner Kontrollen technischer und organisatorischer Maßnahmen
- **TOMs/Checklisten/** - Prüfvorlagen für interne Audit-Aktivitäten
- **Auditplanung/** - Jahresauditpläne und Terminkoordinationen
- **Follow-up-Dokumentation/** - Nachverfolgung von Audit-Findings und Korrekturmaßnahmen

**Warum hier:** Audits sind das zentrale Instrument zur Bewertung der ISMS-Wirksamkeit. Die strukturierte Trennung nach intern/extern erleichtert die Planung und das Reporting an verschiedene Stakeholder.

#### **99_Sonstiges**
**Inhalt:** Historische Dokumente, einmalige Sonderprojekte und sonstige Materialien

**Zweck und praktische Anwendung:**
Dieser Ordner dient als Auffangbereich für alle Dokumente, die nicht in die anderen Kategorien passen und beantwortet die Frage "Wo kommen Dokumente hin, die nirgendwo anders hingehören?". Diese Sammlung bewahrt wichtige Informationen auf, die nicht in die Standardstruktur passen.

**Typische Dokumente (nicht abschließend):**
- **Historische ISMS-Versionen** - Archivierte Versionen von Leitlinien und Richtlinien
- **Einmalige Projektdokumentationen** - Sonderprojekte wie ISMS-Einführung oder große Systemmigrationen
- **Externe Studien und Berichte** - Relevante Branchenstudien oder Sicherheitsberichte zur Orientierung
- **Lieferantendokumentationen** - Technische Dokumentationen, die nicht zu aktuellen Verträgen gehören
- **Temporäre Arbeitsunterlagen** - Entwürfe und Arbeitsversionen während Überarbeitungsphasen
- **Rechtliche Archivdokumente** - Alte Verträge oder rechtliche Dokumente mit Aufbewahrungspflicht

**Warum hier:** Nicht alles passt in die strukturierte ISMS-Logik, muss aber aufbewahrt werden. Diese Kategorie verhindert, dass wichtige Dokumente verloren gehen oder die Hauptstruktur verwässern.

### 3.3 Arbeitsabläufe

#### Neuer Dienstleister
1. **02_Verzeichnisse** → Risikoanalyse erstellen
2. **06_Verträge** → AVV aushandeln und ablegen
3. **08_Audits** → Dienstleister-Audit planen
4. **07_Dokumentationen** → Ergebnisse dokumentieren

#### Sicherheitsvorfall
1. **04_Informationen** → Sofortmeldung
2. **07_Dokumentationen/Vorfallsdokumentation** → Detaildokumentation
3. **03_Richtlinien** → Anpassung der Verfahren
4. **05_Awareness** → Mitarbeiterschulung

#### Jährliche Überprüfung
1. **02_Verzeichnisse** → Aktualisierung Asset-Register
2. **08_Audits** → Durchführung interner Audits
3. **01_Leitlinien** → Überprüfung auf Aktualität
4. **07_Dokumentationen** → Archivierung alter Nachweise
