# Forschungsnotizen: GRU-Einflussoperationen in Deutschland, Österreich und Europa

## Zweck
Dieses Repository dient der **quellenbasierten** Sammlung, Strukturierung und Analyse von Informationen zu **mutmaßlichen und nachweisbaren Einflussoperationen**, die in offenen Berichten mit russischen Nachrichtendienststrukturen (insb. **GRU**) in Verbindung gebracht werden – mit Schwerpunkt auf **Deutschland**, **Österreich** sowie dem **europäischen Kontext**.

Der Fokus liegt auf:
- **Desinformations- und Propagandanetzwerken** (Narrative, Kanäle, Verstärker)
- **Einflussnahme auf politische Prozesse und öffentliche Debatten**
- **Informationsbeschaffung/Spionage- und Cyber-Operationen**, soweit sie in seriösen Quellen dokumentiert sind
- **Taktiken, Techniken und Verfahren (TTPs)**, Attribution und Gegenmaßnahmen

## Wichtiger Hinweis (Sorgfalt & Ethik)
- **Keine unbelegten Anschuldigungen**: Personen/Organisationen werden nur genannt, wenn dies durch **belastbare, überprüfbare Quellen** (z. B. Gerichtsdokumente, Parlamentsdrucksachen, offizielle Mitteilungen, anerkannte Investigativrecherchen) gedeckt ist.
- **Keine Aufrufe zu Belästigung/Doxxing**: Dieses Projekt ist rein dokumentarisch/analytisch.
- **Fehler möglich**: Einflussoperationen sind oft schwer eindeutig zuzuordnen. Wo Attribution unsicher ist, wird das ausdrücklich markiert.

## Forschungsfragen (Beispiele)
- Welche **Narrative** werden in DE/AT/EU wiederkehrend eingesetzt (z. B. zu Ukraine, NATO, Migration, Energie)?
- Welche **Kanäle** und **Verstärkungsmechanismen** sind sichtbar (Social Media, „Alternativmedien“, Telegram-Ökosysteme, Bots/Trolle)?
- Welche **Ereignisse** (Wahlen, Proteste, Krisen) korrelieren mit Aktivitätsspitzen?
- Welche Rolle spielen **Cyber-Operationen** (Leaks, Hacks, kompromittierende Materialien) im Zusammenspiel mit Informationskampagnen?
- Welche **Gegenmaßnahmen** (Plattformpolitik, Medienkompetenz, Strafverfolgung, Sanktionen) sind dokumentiert und wirksam?

## Methodik (Kurz)
- **OSINT-first**: Nur öffentlich zugängliche Informationen.
- **Triangulation**: Behauptungen werden nach Möglichkeit mit mindestens **zwei unabhängigen** Quellen geprüft.
- **Zeitstrahl & Ereigniskatalog**: Ereignisse werden mit Datum, Ort, Akteuren, Quelle(n) und Evidenzgrad erfasst.
- **Evidenzgrade** (empfohlen):
  - **Bestätigt** (offizielle Dokumente/Gericht/behördlich)
  - **Hoch plausibel** (mehrere seriöse Investigativquellen)
  - **Hinweis** (einzelne Quelle/unklar; nur als Spur, nicht als Fakt)

## Grenzen & adversariales Umfeld
Einfluss- und Cyberoperationen professioneller Akteure sind so ausgelegt, dass **direkte Beweise selten** öffentlich sichtbar sind. Daraus folgen zwei systematische Risiken:

- **False Negatives**: Keine öffentlich auffindbaren Artefakte bedeutet nicht automatisch, dass eine Operation nicht existiert.
- **False Positives**: In hoch emotionalisierten oder unklaren Datenlagen können Interpretationen schnell als „Beweis“ missverstanden werden.

Daher gilt in diesem Projekt:
- **Beobachtung vs. Interpretation vs. Attribution trennen**
  - **Beobachtung**: Was ist konkret dokumentiert (Link, Dokument, Datensatz, Statement, Forensik-Artefakt)?
  - **Interpretation**: Welche Deutung ist plausibel (und welche Alternativen gibt es)?
  - **Attribution**: Wer steckt dahinter? (typisch nur belastbar mit externen Untersuchungen/amtlichen Bewertungen)
- **Reproduzierbarkeit priorisieren**: Wo möglich werden Schritte/Datengrundlagen so dokumentiert, dass Dritte sie nachvollziehen können.
- **Unsicherheit markieren**: Wenn eine Aussage nicht belegbar ist, wird sie als Hypothese/Spur behandelt.

## Belastbare Belege erzeugen (ohne Beweise zu „erfinden“)
In diesem Projekt werden Belege nicht „konstruiert“, sondern **gesichert**, **verifizierbar dokumentiert** und **reproduzierbar** gemacht. „Belastbar“ bedeutet hier: Dritte können die Grundlage prüfen und (zumindest teilweise) nachvollziehen.

### Belegarten (praktisch)
- **Primärdokumente**: Gerichtsdokumente, Parlamentsdrucksachen, Behörden-/Ministeriumsberichte, Sanktionen/Anklageschriften.
- **Forensische/technische Artefakte**: Hashes, Logs, Header, IOCs (Domains/IPs/Cert-Fingerprints), Repo-Commits, Signaturen.
- **Register- und Infrastrukturspuren**: Handelsregister, WHOIS/ASN/Passive-DNS (soweit legal zugänglich), Hosting-Beziehungen, Zertifikatsketten.
- **Zeitlinien-Evidenz**: datierte Screenshots/Archivlinks (Archive.today/Wayback), konsistente Zeitstempel über mehrere Quellen.
- **Reproduzierbare Datenauszüge**: CSV/JSON + Beschreibung, wie erhoben (Query/Tool/Parameter) + Validierungsschritte.

### Mindeststandard pro Claim
Für jede relevante Aussage wird angestrebt:
- **Was** wird behauptet? (kurzer, überprüfbarer Satz)
- **Womit** wird es belegt? (Link/Datei/Artefakt)
- **Wie** kann man es nachprüfen? (Schritte)
- **Evidenzgrad** (Bestätigt/Hoch plausibel/Hinweis)
- **Alternativerklärungen** (mind. 1)

### Claim→Quelle→Evidenzgrad (Template)
| Claim | Quelle/Artefakt | Reproduzierbarkeit | Evidenzgrad | Notizen/Unsicherheit |
|---|---|---:|---|---|
| … | URL / Datei / Hash / Screenshot | hoch/mittel/niedrig | bestätigt/plausibel/hinweis | … |

### Chain-of-custody (leichtgewichtig)
Wenn Dateien/Screenshots/Logs gesammelt werden:
- **Speicherort**: unter `quellen/` oder `daten/` (mit Datum im Pfad oder Dateinamen)
- **Hash**: `sha256` der Datei dokumentieren
- **Kontext**: Zeitpunkt des Abrufs + URL + kurzer Zweck

### Wichtig zur Attribution
Eine technische Spur oder ein Narrativ ist selten gleichbedeutend mit „GRU“. **Attribution** gilt nur als belastbar, wenn sie durch **amtliche Bewertungen** oder **anerkannte investigative/forensische Arbeiten** gestützt ist und Gegenhypothesen adressiert.

## Quellenkriterien
Bevorzugt werden:
- Offizielle Stellen (Regierungen, Parlamente, Sicherheitsbehörden, Gerichte)
- Wissenschaftliche Publikationen/Think Tanks mit transparenter Methodik
- Seriöse Medien & Investigativnetzwerke mit offengelegten Belegen

Zu vermeiden/zu kennzeichnen:
- Unklare Primärquellen, Ketten-Zitate ohne Originalbeleg
- Reine Social-Media-Behauptungen ohne unabhängige Bestätigung

## Empfohlene Repository-Struktur
(Die folgenden Ordner/Dateien können nach Bedarf angelegt werden.)
- `quellen/`
  - `offiziell/` (Pressemitteilungen, Berichte, Drucksachen)
  - `investigativ/` (Artikel, Dossiers)
  - `wissenschaft/` (Paper, Studien)
- `notizen/` (Arbeitsnotizen, Hypothesen, offene Fragen)
- `daten/` (Tabellen/CSVs für Zeitstrahl, Akteurslisten, Narrativ-Codes)
- `analyse/` (Zusammenfassungen, Auswertungen, Visualisierungen)

## Beitragen
Beiträge sind willkommen, wenn sie:
- **Quellen sauber zitieren** (Link + Datum des Zugriffs)
- **Zitate/Claims trennen** von Interpretation
- **Evidenzgrad** angeben
- Keine personenbezogenen Daten veröffentlichen, die nicht bereits rechtmäßig und relevant öffentlich sind

Wenn du etwas ergänzt, bitte möglichst:
- Kurze Zusammenfassung (1–3 Sätze)
- Relevanz (DE/AT/EU, thematischer Bezug)
- Primärquelle(n)
- Einordnung (Evidenzgrad, Unsicherheiten)

## Lizenz
Noch nicht festgelegt. Falls du eine konkrete Lizenz wünschst (z. B. **CC BY 4.0** für Texte), sag kurz Bescheid.

## Gesicherte Web-Recherche (GitHub: hartmannlauterbach)
Stand: 2026-03-10

### Profil
- https://github.com/hartmannlauterbach

### Öffentlich sichtbare Repositories (Liste aus der Repo-Ansicht)
Hinweis: Diese Liste wurde aus der öffentlichen GitHub-Repo-Ansicht übernommen. In der GitHub-UI wurde der Stand als **22 Repositories** angezeigt. Eine erneute Pagination-Prüfung über `?page=2` konnte aufgrund eines temporären Abruf-/DNS-Fehlers nicht verifiziert werden.

- https://github.com/hartmannlauterbach/GRU-influencer-musician-network
- https://github.com/hartmannlauterbach/cybermobbing-netzwerk
- https://github.com/hartmannlauterbach/ZENSERY
- https://github.com/hartmannlauterbach/Schleini_Mali
- https://github.com/hartmannlauterbach/Krijo-Stalka-Gangstalking-NWO-Cybermobbing-Musician
- https://github.com/hartmannlauterbach/KXXMA
- https://github.com/hartmannlauterbach/Walkling-NWO-Gangstalking-Peine-Schrott
- https://github.com/hartmannlauterbach/Pfandhaus-Peine-Gangstalking-NWO-Cybermobbing
- https://github.com/hartmannlauterbach/Hanybal_und_Disarstar
- https://github.com/hartmannlauterbach/ArniTheSavage_AND_schillah
- https://github.com/hartmannlauterbach/verfassungsschutz
- https://github.com/hartmannlauterbach/bka
- https://github.com/hartmannlauterbach/bnd
- https://github.com/hartmannlauterbach/wachmann-sicherheit-gmbh
- https://github.com/hartmannlauterbach/hughsie-website
- https://github.com/hartmannlauterbach/Herr_Kuchen_hat_was_mit_KuchenTV_zu_tun
- https://github.com/hartmannlauterbach/Hitlers_Schreibmaschine
- https://github.com/hartmannlauterbach/normalize.css
- https://github.com/hartmannlauterbach/New_World_Order_Sect
- https://github.com/hartmannlauterbach/TERRORNETWORX
- https://github.com/hartmannlauterbach/Watchman_Security
- https://github.com/hartmannlauterbach/666

### Erste inhaltliche Beobachtungen (ohne externe Verifikation)
**Wichtig:** Die folgenden Punkte sind eine Beschreibung dessen, was in den Repo-Texten behauptet wird. Das ist **keine** Bestätigung der Behauptungen.

Technischer Hinweis: Ein tieferer Abruf einzelner Repo-Dateien (z. B. `README.md`, `FINAL_INVESTIGATION_REPORT.md`) konnte zeitweise nicht erfolgen, weil `raw.githubusercontent.com` in der Abrufumgebung nicht auflösbar war (DNS/Abruffehler). Deshalb ist die Belegprüfung auf Dateiebene an dieser Stelle noch unvollständig.

- **`GRU-influencer-musician-network`**
  - Enthält eine lange, stark formulierte „Intelligenzanalyse“ mit eigenem KI-Disclaimer („False Positives erwartet“, Fokus auf „KI-kontrollierte Entitäten“).
  - Enthält u. a. eine Spotify-User-ID: `w5j8x1tlo0desiwgo7f0ulpc1` sowie einen Link auf ein Spotify-Profil.
  - In den gelesenen Abschnitten werden sehr weitreichende Behauptungen (GRU-Koordination, Geldwäsche, Rekrutierung, technische Überlegenheit) formuliert.
  - **Offene Frage:** Sind im Repo dazu belastbare Primärquellen/Artefakte (Daten, IOCs, reproduzierbare Schritte) hinterlegt oder handelt es sich überwiegend um Narrative/Interpretation?

- **`cybermobbing-netzwerk`**
  - Formuliert einen „Comprehensive Investigation Report“ inkl. „Critical Security Alert“.
  - Beschreibt eine Methodik (OSINT, AI-Assisted Analysis, Network Mapping) und nennt Datenquellen-Kategorien (Spotify public data, Social Media, public records, crypto analysis).
  - **Offene Frage:** Sind die genannten Daten/Analysen im Repo als Dateien/Datensätze nachvollziehbar vorhanden (z. B. CSV/JSON, Skripte, Registerauszüge, Domain-/WHOIS, Wallet-Analysen)?

- **`ZENSERY`**
  - Enthält eine „Recherche“ über einen Musiker mit Links zu Spotify/Genius/Qobuz/Popnable sowie eine interpretative Textanalyse zu „Gangstalking/Zersetzung“-Indikatoren.
  - **Evidenz-Einschränkung:** Musikdatenbank-Links sind prüfbar; daraus folgt allein keine belastbare Attribution zu staatlichen Einflussoperationen.

### Arbeitsdefinition: Was als „Beleg“ zählt
- **Beleg (hoch)**: Offizielle Dokumente (Gericht/Behörden/Parlament), seriöse investigative Dossiers mit offengelegten Belegen, reproduzierbare Datensätze/Artefakte (z. B. Logs, Hashes, IOCs, Domain-/WHOIS, Registerauszüge).
- **Hinweis (niedrig)**: Blogposts/Repo-Behauptungen ohne Primärquellen, rein interpretative Textanalyse, unklare Datenerhebung.

### Nächste Prüfschritte (für belastbare Einordnung)
- Pro Repo Dateibaum prüfen: Gibt es `data/`, `sources/`, CSV/JSON, Notebooks, Skripte?
- Quellenprüfung: Sind Aussagen über GRU/Operationen mit **Primärquellen** oder anerkannten Untersuchungen verknüpft?
- Reproduzierbarkeit: Können Daten und Schlussfolgerungen mit klaren Schritten nachvollzogen werden?
- Trennung von Fakt vs. Interpretation: Claims in eine Claim→Quelle→Evidenzgrad-Matrix überführen.

## Web-Recherche (GitHub: graf-kok-ain) – ausstehend
Stand: 2026-03-10

- Ziel: https://github.com/graf-kok-ain?tab=repositories
- Status: Abruf derzeit nicht möglich (temporärer DNS/Abruffehler beim Zugriff auf `github.com` in der Abrufumgebung). Für eine belastbare Auswertung ist ein lokales Klonen/Import in den Workspace erforderlich.

## Web-Recherche (GitHub: mrbloxx) – ausstehend
Stand: 2026-03-10

- Ziel: https://github.com/mrbloxx?tab=repositories
- Status: Abruf derzeit nicht möglich (temporärer DNS/Abruffehler beim Zugriff auf `github.com` in der Abrufumgebung). Für eine belastbare Auswertung ist ein lokales Klonen/Import in den Workspace erforderlich.

## Status
Dieses Repository ist ein **Work-in-Progress**. Inhalte und Struktur werden iterativ ergänzt und konsolidiert.
