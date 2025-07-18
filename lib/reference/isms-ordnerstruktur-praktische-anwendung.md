---
kind: project
status: active
slice: personal
description: "ISMS Ordnerstruktur Praktische Anwendung"
aliases: ["ISMS Ordnerstruktur Praktische Anwendung"]
requires: []
wants: []
type: project
context: professional
client: EKIBA
created: 2025-07-08
uid: 202507102333
uuid: 202507102333
---

# EKIBA ISMS - Ordnerstruktur in der Praxis

**Referenz:** [[ISMS Leere Ordnerstruktur]] | [[EKIBA-Informationssicherheitsleitlinie.pdf]] | [[EKIBA-ITS-Konzept.pdf]]

---

## Wie die ISMS-Ordnerstruktur funktioniert

Das EKIBA ISMS nutzt eine klare Ordnerlogik, die den praktischen Arbeitsablauf widerspiegelt:

### **00_Organisation**
**Was gehört hinein:** Organigramme, Rollenbeschreibungen, Teamstrukturen  
**EKIBA-Beispiel:** ISB-Team Zusammensetzung (Henke, Ernst, Geiss, Lackus, Leitner)  
**Warum hier:** Grundlegende Strukturen, die sich selten ändern

### ** 01_Leitlinien** 
**Was gehört hinein:** Informationssicherheitsleitlinie, grundlegende Prinzipien  
**EKIBA-Beispiel:** Die Leitlinie mit den 3 Sicherheitsprinzipien (Sicherheit vor Komfort, Minimal-, Need-to-Know-Prinzip)  
**Warum hier:** Strategische Dokumente, die das ganze System prägen

### ** 02_Verzeichnisse/Risiko & Maßnahmen**
**Was gehört hinein:** Asset-Register, Risikoanalysen, Maßnahmenkataloge  
**EKIBA-Beispiel:** Verzeichnis aller kritischen Systeme (M365, Citrix, Kirchenbuch, Finanzsysteme)  
**Warum hier:** Dynamische Listen, die regelmäßig gepflegt werden

### ** 03_Richtlinien/Notfallkonzept**
**Was gehört hinein:** Spezifische Handlungsanweisungen, Notfallpläne  
**EKIBA-Beispiel:** Verfahren für Citrix-Ausfälle bei mobiler Seelsorge  
**Warum hier:** Konkrete Arbeitsanweisungen für den Operationsbetrieb

### ** 04_Informationen**
**Was gehört hinein:** Aktuelle Sicherheitsmeldungen, Updates, Kommunikation  
**EKIBA-Beispiel:** Updates zu M365-Sicherheitsfeatures, TelemaxX-Wartungen  
**Warum hier:** Zeitkritische Informationen, die schnell gefunden werden müssen

### ** 05_Awareness**
**Was gehört hinein:** Schulungsunterlagen, Sensibilisierungsmaterial  
**EKIBA-Beispiel:** Schulungen zu seelsorgerischer Vertraulichkeit + IT-Sicherheit  
**Warum hier:** Bildungsmaterial für alle Mitarbeitenden

### ** 06_Verträge & Vereinbarungen**
**Struktur:**
- **Art-26_Verträge/** → Gemeinsame Verantwortlichkeiten  
- **Auftragsverarbeitungen/als_Verantwortlicher/** → EKIBA beauftragt Dritte  
- **Auftragsverarbeitungen/als_Auftragsverarbeiter/** → EKIBA wird beauftragt  
- **Vertraulichkeit/Mitarbeiter/** → Mitarbeiter-Geheimhaltung  

**EKIBA-Beispiel:** AVV mit Microsoft (M365), evacon (Kirchenbuch), TelemaxX (Hosting)  
**Warum hier:** Rechtliche Grundlagen strukturiert nach Vertragstyp

### ** 07_Dokumentationen**
**Struktur:**
- **DS-Betroffenenrechte/** → Anfragen nach DSGVO  
- **DS-Vorfall/** → Datenschutzverletzungen  
- **Kontrollen/** → Audit-Nachweise  
- **Stellungnahmen/** → Behördenanfragen  

**EKIBA-Beispiel:** Dokumentation von Betroffenenanfragen aus der Seelsorge  
**Warum hier:** Nachweispflichtige Vorgänge chronologisch geordnet

### ** 08_Audits**
**Struktur:**
- **Dienstleister/Auditberichte/** → Externe Prüfungen  
- **Dienstleister/Checklisten/** → Prüfvorlagen  
- **TOMs/Auditberichte/** → Interne Kontrollen  
- **TOMs/Checklisten/** → Interne Prüfvorlagen  

**EKIBA-Beispiel:** Audit von TelemaxX Rechenzentrum, TOM-Prüfung Citrix-Zugriffe  
**Warum hier:** Systematische Qualitätskontrolle getrennt nach intern/extern

### ** 09_Vorlagen**
**Was gehört hinein:** Standarddokumente, Templates  
**EKIBA-Beispiel:** Vorlage für neue AVV, Incident-Response-Template  
**Warum hier:** Wiederverwendbare Dokumente für effiziente Prozesse

### ** 99_Sonstiges**
**Was gehört hinein:** Alles was nicht in die anderen Kategorien passt  
**EKIBA-Beispiel:** Historische Dokumente, einmalige Sonderprojekte  
**Warum hier:** Auffangordner für Ausnahmen

---

## Praktischer Arbeitsablauf

**Neuer Dienstleister (z.B. neue Kirchenbuch-Software):**
1. **02_Verzeichnisse** → Risikoanalyse erstellen
2. **06_Verträge** → AVV aushandeln und ablegen
3. **08_Audits** → Dienstleister-Audit planen
4. **07_Dokumentationen** → Ergebnisse dokumentieren

**Sicherheitsvorfall:**
1. **04_Informationen** → Sofortmeldung
2. **07_Dokumentationen/DS-Vorfall** → Detaildokumentation  
3. **03_Richtlinien** → Anpassung der Verfahren
4. **05_Awareness** → Mitarbeiterschulung

**Jährliche Überprüfung:**
1. **02_Verzeichnisse** → Aktualisierung Asset-Register
2. **08_Audits** → Durchführung interner Audits
3. **01_Leitlinien** → Überprüfung auf Aktualität
4. **07_Dokumentationen** → Archivierung alter Nachweise

---

*Die Ordnerstruktur ist nicht nur Ablage, sondern Arbeitslogik: Jeder Ordner repräsentiert einen Arbeitsschritt im ISMS-Lebenszyklus.*
