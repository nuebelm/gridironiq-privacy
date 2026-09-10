# Impressum & Datenschutzerklärung / Legal Notice & Privacy Policy

**GridIron IQ**  
Stand / Effective: **September 2026**  
Operator: Markus Nübel · support@gridiron-iq.de · https://github.com/nuebelm

**Sprache / Language:** Dieses Dokument ist zweisprachig. Die **englische Fassung** beginnt weiter unten unter „EN — Legal Notice“.  
*This document is bilingual. The **English version** starts below under “EN — Legal Notice”.*

---

## DE — Impressum (§ 5 DDG)

**Diensteanbieter**  
Markus Nübel  
Bastionstr. 55  
59555 Lippstadt  
Deutschland

**Kontakt**  
E-Mail: support@gridiron-iq.de  
Website: https://github.com/nuebelm

**Verantwortlich i. S. d. § 18 Abs. 2 MStV**  
Markus Nübel (Anschrift wie oben)

---

## DE — Datenschutzerklärung

### 1. Verantwortlicher

Markus Nübel  
E-Mail: support@gridiron-iq.de

### 2. Grundsatz

GridIron IQ folgt dem Prinzip **Privacy by Design**. Mit **Cloud-Konto** werden Scouting-Notizen, Trade-Flags und Einstellungen auf unserem Server (Supabase) synchronisiert. **Kader- und Ligadaten** stammen von der Sleeper API. **Marktwerte, Rankings und Market Signals** werden aus aggregierten Liga-Daten in der GridIron-IQ-Datenbank berechnet — **nicht** aus Drittanbieter-Marktwert-APIs (z. B. FantasyCalc).

### 3. Welche Daten wir verarbeiten

| Kategorie | Inhalt | Speicherort |
|-----------|--------|-------------|
| **Konto** | E-Mail, Auth-Token (Supabase Auth) | Supabase (EU-Region) |
| **Scouting** | Notizen, Tags, Trade-Flags (profilbezogen) | Gerät + Cloud bei Anmeldung |
| **Sleeper** | Username, Liga-IDs, Roster, Drafts (read-only) | Abruf von Sleeper; Anzeige in der App |
| **Nutzungsstatistik** | Aggregierte NFL-Weekly-Stats, Snaps, Injuries (nflverse) | Unsere Datenbank; kein PII an nflverse |
| **Ultimate / KI** | Komprimierter Spielerkontext an KI-Anbieter | Server-seitig; Scouting-Notizen standardmäßig **nicht** |
| **Abrechnung** | Kaufstatus (RevenueCat / Google Play) | RevenueCat; keine Kreditkartendaten bei uns |

### 4. Drittanbieter

**a) Sleeper API** — öffentliche Liga-, Kader- und Spielerdaten.  
Anbieter: Blitz Studios, Inc. · https://sleeper.com/privacy

**b) Supabase** — Hosting, Authentifizierung, Datenbank. Auftragsverarbeitung gemäß DPA.

**c) nflverse** (CC-BY 4.0) — öffentliche NFL-Statistiken, Injury-Reports, Snap-Counts.  
Quelle: https://github.com/nflverse/nflverse-data · Keine Übermittlung personenbezogener Nutzerdaten an nflverse.

**d) Google Gemini** (nur Ultimate) — komprimierter Spielerkontext für KI-Erklärungen.  
https://policies.google.com/privacy

**e) RevenueCat / Google Play** — Abo-Status. Zahlung über Google; wir erhalten keine vollständigen Zahlungsdaten.

**Nicht mehr verwendet:** FantasyCalc oder vergleichbare Marktwert-APIs in Produktions-Builds.

### 5. Marktwerte (Value Engine)

Marktwerte und Rankings werden serverseitig aus aggregierten Sleeper-Liga-Daten (Draft-Picks, Trades) in unserer Datenbank berechnet. Deine Liga-IDs werden nur zur Anzeige **deiner eigenen** Kader verwendet, nicht an externe Marktwert-Anbieter verkauft oder lizenziert.

### 6. Rechtsgrundlagen (DSGVO)

- Vertragserfüllung (Art. 6 Abs. 1 lit. b) — App-Nutzung, Cloud-Sync, Abo
- Berechtigtes Interesse (Art. 6 Abs. 1 lit. f) — Fehlerdiagnose, Missbrauchsprävention
- Einwilligung (Art. 6 Abs. 1 lit. a) — soweit für KI-Funktionen erforderlich

### 7. Speicherdauer & Löschung

Cloud-Daten bis zur **Kontolöschung in der App** (Konto → Cloud-Konto → „Konto löschen“) oder auf schriftliche Anfrage an support@gridiron-iq.de. Bei Kontolöschung werden Auth-Konto, Profil, Scouting-Notizen, Tags, Trade-Flags und Einstellungen auf dem Server gelöscht; zugehörige lokale Daten auf dem Gerät werden ebenfalls entfernt. Lokale Gast-Daten ohne Cloud-Konto bis App-Deinstallation oder manueller Datensicherung/Reset. Aggregierte NFL-Statistiken nach interner Retention-Policy (keine personenbezogenen Nutzerdaten).

### 8. Deine Rechte

Auskunft, Berichtigung, **Löschung** (Art. 17 DSGVO — direkt in der App unter Konto → Cloud-Konto → „Konto löschen“, mit E-Mail-Bestätigung), Einschränkung, Widerspruch, Datenübertragbarkeit (Export unter Einstellungen → Datensicherung), Beschwerde bei einer Aufsichtsbehörde (Art. 15–22, 77 DSGVO).  
Kontakt: support@gridiron-iq.de

### 9. Änderungen

Wir können diese Erklärung anpassen. Maßgeblich ist die Fassung mit aktuellem „Stand“-Datum oben.

---

## English version below

*Englische Fassung — see below.*

---

## EN — Legal Notice

**Service provider**  
Markus Nübel  
Bastionstr. 55  
59555 Lippstadt  
Germany

**Contact**  
Email: support@gridiron-iq.de  
Website: https://github.com/nuebelm

**Responsible for content (§ 18 (2) MStV)**  
Markus Nübel (address as above)

---

## EN — Privacy Policy

### 1. Controller

Markus Nübel  
Email: support@gridiron-iq.de

### 2. Overview

GridIron IQ follows a **privacy-by-design** approach. With a **cloud account**, scouting notes, trade flags, and settings sync to our server (Supabase). **Roster and league data** comes from the Sleeper API. **Market values, rankings, and market signals** are computed from aggregated league data in the GridIron IQ database — **not** from third-party valuation APIs (e.g. FantasyCalc).

### 3. Data we process

| Category | Content | Storage |
|----------|---------|---------|
| **Account** | Email, auth token (Supabase Auth) | Supabase (EU region) |
| **Scouting** | Notes, tags, trade flags (profile-scoped) | Device + cloud when signed in |
| **Sleeper** | Username, league IDs, rosters, drafts (read-only) | Fetched from Sleeper; displayed in app |
| **Usage stats** | Aggregated NFL weekly stats, snaps, injuries (nflverse) | Our database; no PII sent to nflverse |
| **Ultimate / AI** | Compressed player context to AI provider | Server-side; scouting notes **not** sent by default |
| **Billing** | Purchase status (RevenueCat / Google Play) | RevenueCat; no card data stored by us |

### 4. Third parties

**a) Sleeper API** — public league, roster, and player data.  
Provider: Blitz Studios, Inc. · https://sleeper.com/privacy

**b) Supabase** — hosting, authentication, database. Processing under DPA.

**c) nflverse** (CC-BY 4.0) — public NFL statistics, injury reports, snap counts.  
Source: https://github.com/nflverse/nflverse-data · No personal user data sent to nflverse.

**d) Google Gemini** (Ultimate only) — compressed player context for AI explanations.  
https://policies.google.com/privacy

**e) RevenueCat / Google Play** — subscription status. Payment via Google; we do not receive full payment details.

**No longer used:** FantasyCalc or comparable market-value APIs in production builds.

### 5. Market values (Value Engine)

Market values and rankings are computed server-side from aggregated Sleeper league data (draft picks, trades) in our database. Your league IDs are only used to display **your own** rosters — not sold or licensed to external valuation providers.

### 6. Legal bases (GDPR)

- Contract performance (Art. 6(1)(b)) — app use, cloud sync, subscriptions
- Legitimate interest (Art. 6(1)(f)) — error diagnostics, abuse prevention
- Consent (Art. 6(1)(a)) — where required for AI features

### 7. Retention & deletion

Cloud data until **in-app account deletion** (Account → Cloud account → “Delete account”) or on written request to support@gridiron-iq.de. Account deletion removes auth account, profile, scouting notes, tags, trade flags, and settings on our server; related local data on the device is removed as well. Local guest data without a cloud account until app uninstall or manual backup/reset. Aggregated NFL statistics per internal retention policy (no personal user data).

### 8. Your rights

Access, rectification, **erasure** (GDPR Art. 17 — in the app under Account → Cloud account → “Delete account”, with email confirmation), restriction, objection, portability (export under Settings → Backup & Restore), complaint to a supervisory authority (Arts. 15–22, 77 GDPR).  
Contact: support@gridiron-iq.de

### 9. Changes

We may update this policy. The version with the current “Effective” date above applies.
