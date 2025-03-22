
## Projektdokumentation: Digitale Bewerbungsplattform

### ![App Logo](screenshots/logo.webp)

### 1. Einleitung
- **Projektname:** Digitale Bewerbungsplattform
- **Zielgruppe:** Bewerber*innen, Quereinsteiger, Studierende, Coaches, HR-Agenturen
- **Motivation:** Die App wurde entwickelt, um klassische, statische PDF-Bewerbungen durch eine moderne, interaktive Weblösung zu ersetzen.

> Die „digitale Bewerbungsplattform“ ermöglicht es, interaktive, KI-gestützte Bewerbungen in Web-App-Form zu erstellen, die weit über klassische Lebensläufe hinausgehen.

---

### 2. Ziele des Projekts
- **Innovation:** Individualisierte Bewerbung mit KI-Personalisierung statt standardisierter Formulare
- **Technische Ziele:** Containerisierte, modulare Architektur; einfache Erweiterbarkeit
- **Strategische Ziele:** Marktpositionierung als flexible White-Label-Lösung für Coaches
- **Vision:** Die Bewerbung von morgen ist digital, flexibel und KI-gestützt

---

### 3. Architektur & Technologiestack
- **Frontend:** React mit Vite oder alternativ Streamlit (Python)
- **Backend:** optional (aktuell kein persistentes Backend erforderlich)
- **Deployment:** Docker-Container, VPS-Hosting, Nginx-Proxy mit SSL
- **Datenhaltung:** Nutzerinputs in Session oder als Datei, optional DB
- **CI/CD:** manuell oder via GitHub Actions

> Optional: Architekturdiagramm einfügen

---

### 4. Funktionalitäten der App
- Bewerbungsformular
- Motivationsschreiben-Generator (Custom Prompt)
- Auswahl & Vorschau von Themes/Designs
- Admin-Ansicht zur Kontrolle & Bearbeitung
- PDF-Export (optional, geplant)

---

### 5. Custom Prompts (KI-Integration)
- Integration lokaler LLMs (Ollama, z. B. LLaMA3) oder OpenAI API
- Prompt-Strategie: Systemprompt + dynamischer Input
- Beispiele:
  - "Formuliere ein Motivationsschreiben auf Basis folgender Daten..."
  - "Fasse folgende Lebenslaufstationen zusammen..."
- Anpassbar nach Branche und Sprache

---

### 6. Marktforschung
- Konkurrenz: Bewerbung.io, Lebenslauf.de, Canva CV Builder
- Schwächen: eingeschränkte Individualisierung, kein KI-Fokus, keine API
- Bedarf bei: Coachs, Bildungsträgern, Jobsuchenden

---

### 7. Business-Plan / Monetarisierung
- **Zielgruppen:** Jobsuchende, Bildungsanbieter, Agenturen
- **Modelle:**
  - Freemium-Version für Bewerber
  - Bezahlfunktion für Export
  - White-Label-Version für Coaches
- **Vertrieb:** Eigene Website, LinkedIn, Affiliate-Partner

---

### 8. Marketingstrategie & SEO
- SEO: Keywords wie "digitale Bewerbung 2025", "AI CV"
- Content-Marketing: Blog, Bewerbungstipps, GPT-Features
- Social Media: LinkedIn, YouTube Shorts
- Lead-Generierung: Gratis-Demo mit E-Mail-Erfassung

---

### 9. Projektstatus & Ausblick
- MVP: Online unter cv.rm-on.de (Docker + Reverse Proxy)
- Noch offen: Nutzerkonten, Admin-Login, Analytics
- Geplant: API, Mehrsprachigkeit, mobile Optimierung

---

### 10. Anhang
- Screenshots & Design-Vorlagen
- Beispielprompts & Konfigurationen (vite.config.js, nginx)
- Docker-Kommandos zur Reproduktion

---

**Letztes Update:** März 2025
