# Impressum & Datenschutzerklärung / Privacy Policy

## 1. IMPRESSUM (LEGAL NOTICE)

### Angaben gemäß § 5 DDG (Digital-Dienste-Gesetz)

**Diensteanbieter / Entwickler:**
Markus Nübel
Bastionstr. 55
59555 Lippstadt
Deutschland

**Kontakt:**
E-Mail: support@gridiron-iq.de
Website: https://github.com/nuebelm

**Verantwortlich für den Inhalt nach § 18 Abs. 2 MStV:**
Markus Nübel (Adresse wie oben)

---

## 2. DATENSCHUTZERKLÄRUNG (PRIVACY POLICY)

**Stand:** August 2026

Wir freuen uns über dein Interesse an der mobilen Anwendung **GridironIQ** (nachfolgend "App"). Der Schutz deiner personenbezogenen Daten ist uns ein wichtiges Anliegen. Nachfolgend informieren wir dich ausführlich über den Umgang mit deinen Daten.

### A. Verantwortlicher
Verantwortlich für die Datenverarbeitung im Sinne der Datenschutz-Grundverordnung (DSGVO) ist:

**Markus Nübel**
E-Mail: [Deine E-Mail-Adresse]
GitHub: https://github.com/nuebelm

---

### B. Grundsatz der clientseitigen Verarbeitung (Serverless)
GridironIQ arbeitet nach dem Prinzip **"Privacy by Design"**. Die App nutzt keine eigenen Server zur Zwischenspeicherung deiner Kaderdaten, Chatverläufe oder eingegebenen Schnittstellen-Schlüssel (API-Keys). Die gesamte Verarbeitungslogik und Datenaufbereitung findet lokal auf deinem Endgerät statt.

---

### C. Datenerhebung und Schnittstellen (APIs)

#### 1. Lokale Speicherung deines KI-Schlüssels (BYOK-Modell)
- **Verarbeitete Daten:** API-Keys für Drittanbieter-Services (z. B. Google Gemini API, Groq API).
- **Zweck:** Ermöglichung der KI-gestützten Analyse deiner Dynasty- und Trade-Daten.
- **Speicherort:** Die Schlüssel werden ausschließlich lokal im gesicherten Speicher deines Endgeräts (`AsyncStorage` / `SecureStore`) hinterlegt.
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung zur Bereitstellung der App-Funktionalität).

#### 2. Zugriff auf die Zwischenablage (Clipboard)
- **Verarbeitete Daten:** Auslesen der Zwischenablage beim Wechsel in die App.
- **Zweck:** Automatisches Erkennen von kopierten API-Schlüsseln (z. B. Beginnend mit `AIzaSy...` oder `gsk_...`), um dir das manuelle Einfügen zu ersparen.
- **Hinweis:** Der Inhalt der Zwischenablage wird ausschließlich lokal im Arbeitsspeicher deines Geräts analysiert und niemals an externe Server gesendet oder dauerhaft gespeichert.
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO (Berechtigtes Interesse an einer benutzerfreundlichen Bedienung).

#### 3. Drittanbieter-Schnittstellen (Sleeper, LLM-Provider & FantasyCalc)
Wenn du Analysen oder Marktwerte in der App abrufst, baut dein Endgerät direkte Verbindungen zu folgenden Drittanbietern auf:

a) **Sleeper API (Roster & Liga-Daten)**
- **Daten:** Öffentlich zugängliche Sleeper-User-IDs, Liga-IDs, Kader und Draft-Picks.
- **Anbieter:** Blitz Studios, Inc. (Sleeper)
- **Datenschutzerklärung:** https://sleeper.com/privacy

b) **Google Gemini API / Groq API**
- **Daten:** Anonymisierte/komprimierte Spielerdaten (Position, Alter, Depth-Chart) sowie dein lokaler API-Key. Es werden keine Klarnamen oder personenbezogenen Nutzerprofil-Daten übertragen.
- **Anbieter:** Google Ireland Limited / Groq, Inc.
- **Datenschutzerklärung:** https://policies.google.com/privacy (Google) / https://groq.com/privacy-policy/ (Groq)

c) **FantasyCalc API (Marktwerte & Trade-Daten)**
- **Daten:** Abruf von aggregierten Spieler-Marktwerten und Trade-Ranglisten. Es werden hierbei **keinerlei personenbezogene Daten** der App-Nutzer an FantasyCalc übermittelt; es handelt sich um einen reinen Download von allgemeinen Marktwert-Listen.
- **Anbieter:** FantasyCalc.com
- **Hinweis zur Attribution:** Spielerwerte und Marktwerte bereitgestellt von FantasyCalc.com.

---

### D. Betroffenenrechte
Nach der DSGVO stehen dir folgende Rechte zu:
- **Recht auf Auskunft** (Art. 15 DSGVO)
- **Recht auf Löschung** (Art. 17 DSGVO) – Du kannst jederzeit alle Daten löschen, indem du den App-Speicher auf deinem Smartphone zurücksetzt oder die App deinstallierst.
- **Recht auf Einschränkung der Verarbeitung** (Art. 18 DSGVO)
- **Recht auf Beschwerde** bei einer Datenschutz-Aufsichtsbehörde (Art. 77 DSGVO).

---

### E. Änderungen dieser Datenschutzerklärung
Wir behalten uns vor, diese Datenschutzerklärung anzupassen, damit sie stets den aktuellen rechtlichen Anforderungen entspricht oder um Änderungen unserer Funktionalitäten in der Datenschutzerklärung umzusetzen.

---

# Legal Notice & Privacy Policy

## 1. LEGAL NOTICE (IMPRESSUM)

### Information pursuant to § 5 DDG (Digital Services Act)

**Service Provider / Developer:**
Markus Nübel
Bastionstr. 55
59555 Lippstadt
Germany

**Contact:**
E-Mail: support@gridiron-iq.de
Website: https://github.com/nuebelm

**Responsible for content according to § 18 Abs. 2 MStV:**
Markus Nübel (Address as above)

---

## 2. PRIVACY POLICY

**Effective Date:** August 2026

Thank you for your interest in the mobile application **GridironIQ** (hereinafter referred to as the "App"). Protecting your personal data is of utmost importance to us. Below, we inform you in detail about how your data is handled.

### A. Controller
The party responsible for data processing within the meaning of the General Data Protection Regulation (GDPR) is:

**Markus Nübel**
E-Mail: support@gridiron-iq.de
GitHub: https://github.com/nuebelm

---

### B. Principle of Client-Side Processing (Serverless)
GridironIQ operates on the **"Privacy by Design"** principle. The App does not use its own servers to store your roster data, chat history, or entered API keys. The entire processing logic and data preparation takes place locally on your end device.

---

### C. Data Collection and Interfaces (APIs)

#### 1. Local Storage of Your AI Key (BYOK Model)
- **Processed Data:** API keys for third-party services (e.g., Google Gemini API, Groq API).
- **Purpose:** Enabling AI-powered analysis of your dynasty and trade data.
- **Storage Location:** Keys are stored exclusively in the secure local storage of your device (`AsyncStorage` / `SecureStore`).
- **Legal Basis:** Art. 6 Abs. 1 lit. b GDPR (Performance of a contract for providing app functionality).

#### 2. Clipboard Access
- **Processed Data:** Reading the clipboard when switching into the App.
- **Purpose:** Automatic detection of copied API keys (e.g., starting with `AIzaSy...` or `gsk_...`) to save you manual pasting.
- **Note:** The contents of the clipboard are analyzed exclusively in your device's local memory and are never sent to external servers or permanently stored.
- **Legal Basis:** Art. 6 Abs. 1 lit. f GDPR (Legitimate interest in user-friendly operation).

#### 3. Third-Party Interfaces (Sleeper, LLM Providers & FantasyCalc)
When you run analyses or fetch market values within the App, your device establishes direct connections to the following third-party providers:

a) **Sleeper API (Roster & League Data)**
- **Data:** Publicly accessible Sleeper user IDs, league IDs, rosters, and draft picks.
- **Provider:** Blitz Studios, Inc. (Sleeper)
- **Privacy Policy:** https://sleeper.com/privacy

b) **Google Gemini API / Groq API**
- **Data:** Anonymized/compressed player data (position, age, depth chart) as well as your local API key. No real names or personal user profile data are transmitted.
- **Provider:** Google Ireland Limited / Groq, Inc.
- **Privacy Policies:** https://policies.google.com/privacy (Google) / https://groq.com/privacy-policy/ (Groq)

c) **FantasyCalc API (Market Values & Trade Data)**
- **Data:** Retrieval of aggregated player market values and trade rankings. No personal data of app users is transmitted to FantasyCalc; this is strictly a download of general market value lists.
- **Provider:** FantasyCalc.com
- **Attribution Note:** Player values and market data powered by FantasyCalc.com.

---

### D. Data Subject Rights
Under the GDPR, you have the following rights:
- **Right of access** (Art. 15 GDPR)
- **Right to erasure** (Art. 17 GDPR) – You can delete all data at any time by resetting the app storage on your smartphone or uninstalling the App.
- **Right to restriction of processing** (Art. 18 GDPR)
- **Right to lodge a complaint** with a supervisory authority (Art. 77 GDPR).

---

### E. Changes to This Privacy Policy
We reserve the right to amend this Privacy Policy to ensure it always complies with current legal requirements or to reflect changes to our functionalities in the policy.

### E. Änderungen dieser Datenschutzerklärung
Wir behalten uns vor, diese Datenschutzerklärung anzupassen, damit sie stets den aktuellen rechtlichen Anforderungen entspricht oder um Änderungen unserer Funktionalitäten in der Datenschutzerklärung umzusetzen.
