# NIS2 Erstgespräch-Plan

## Grundsatz: Ampel-System

### Farbcode-Übersicht

| Ampelfarbe | Bedeutung                         |
|------------|-----------------------------------|
| Rot        | NIS2 ist anzuwenden               |
| Gelb       | Nicht Teil der Annex aber         |
| Grün       | Höchstwahrscheinlich nicht betroffen |

---

## NIS2 Ampel-System: 3-Stufen-Schnellcheck für das Erstgespräch (≤ 20 Min.)

### Farbcode-Übersicht

| Farbe                                                  | Bedeutung                                                                                                                                                                                                                                                                    | Entscheidungs-Trigger | Empfohlene Aktion im Call                                                                                                                                                                                                       |
| ------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **GRÜN** („höchstwahrscheinlich nicht betroffen“)      | - Branche/Tätigkeit nicht in Annex I/II<br>- Kein Cloud-, DNS-, TLD-, Trust- oder MSP/MSSP-Service<br>- < 50 MA und ≤ 10 Mio. € Umsatz/Bilanz                                                                                                                                | –                     | - Ergebnis kurz dokumentieren („out of scope – Stand [Datum]“)<br>- Empfehlung: jährlicher Re-Check oder bei Geschäftsmodifikationen                                                                                            |
| **GELB** („Grauzone / vertiefen“)                      | Einer der Punk te trifft zu:<br>1. Branche unklar oder mehrgliedrig (z. B. Installateur & Betreiber)<br>2. Geschäftsmodell Teil eines Annex-Sektors<br>3. Lieferant eines NIS2-pflichtigen Kunden („Flow-down-Clause“)<br>4. ≥ 50 MA oder > 10 Mio. €, Annex-Zuordnung offen | Ja                    | - An Lead/Senior eskalieren<br>- Workshop/Gap-Analyse anbieten<br>- Keine festen Zusagen zu Fristen/Bußgeldern                                                                                                                  |
| **ROT** („klar in-scope – Essential/Important Entity“) | - Branche/Tätigkeit sicher in Annex I/II<br>- Cloud/MSP/MSSP/IX/DNS/Trust-Service<br>- Size-Cap erfüllt:<br>  * ≥ 250 MA oder > 50 Mio. € Umsatz & > 43 Mio. € Bilanz → Essential Entity<br>  * ≥ 50 MA oder > 10 Mio. € Umsatz/Bilanz → Important Entity                    | Ja                    | - Pflichten nennen: 3-Monats-Registrierung, Risikomanagement-Controls, Meldefristen (24h/72h/30d)<br>- GAP-Analyse, Roadmap & Management-Briefing anstoßen<br>- Hinweis auf Bußgelder (bis 2 % Umsatz) & Geschäftsführerhaftung |

> **Hinweis**: Mikro-/Kleinunternehmen (< 50 MA, ≤ 10 Mio. €) können ROT sein, wenn sie digitale Kerndienste erbringen (z. B. TLD-Registry, Trust Service Provider).

---

## Live-Nutzung des Ampel-Systems im Call (≤ 20 Min.)

1. **Einstieg (Min. 0–2)**  
   „Lassen Sie uns per Ampel prüfen, ob und wie NIS2 greift.“
2. **Frageblock 1 – Branche/Tätigkeit**  
   „In welcher Haupttätigkeit sind Sie aktiv? Erzeugen/verteilen Sie Energie? Bieten Sie Cloud- oder Managed-Security-Services an?“  
   → Kein Annex-Sektor → GRÜN, sonst weiter.
3. **Frageblock 2 – Unternehmensgröße**  
   „Wie viele Mitarbeitende? Wie hoch war Ihr Umsatz/Bilanzsumme im letzten Geschäftsjahr?“  
   → Unter Schwelle → ggf. GELB, sonst ROT.
4. **Frageblock 3 – Sonderfälle**  
   „Gibt es Kundenverträge mit Sicherheitspflichten? Betreiben Sie kritische Anlagen?“  
   → Ja → abhängig vom Ergebnis GELB/ROT.
5. **Abschluss (Min. 18–20)**  
   - GRÜN: jährlichen Re-Check & Awareness anbieten.  
   - GELB: Workshop-/Audit-Angebot; Senior für Detailbewertung hinzuziehen.  
   - ROT: sofort GAP-Analyse, Registrierungsdeadline, Kostenschätzung nennen.

---

## Merkhilfen für Junior-Berater:innen

- **„Branche vor Größe“**: Ohne Annex-Treffer bleibt alles GRÜN, egal wie groß.
- **„Bauer ≠ Betreiber“**: Installation/Wartung ≠ Erzeugung/Netzbetrieb → oft GELB statt ROT.
- **„Digitale Kerndienste kippen die Ampel“**: Cloud, DNS, Trust, IX, MSP/MSSP sind immer Annex I – Größe entscheidet nur zwischen Essential/Important.
- **Eskalationssignal**: Jede Unsicherheit → GELB, Übergabe an Lead.

---

Mit dieser strukturierten Ampel haben Ihre Kolleg:innen ein klares Raster, das sie im 20-Minuten-Call anwenden können – ohne sich in juristischen Details zu verlieren.