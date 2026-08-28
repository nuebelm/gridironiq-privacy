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

### E. Änderungen dieser Datenschutzerklärung
Wir behalten uns vor, diese Datenschutzerklärung anzupassen, damit sie stets den aktuellen rechtlichen Anforderungen entspricht oder um Änderungen unserer Funktionalitäten in der Datenschutzerklärung umzusetzen.
