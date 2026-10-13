# Jacob Glathe & Team — High-End Web Platform

Ein meisterhafter, extrem performanter und visuell makelloser Webauftritt für Jacob Glathe und sein Entwickler-Team, strikt orientiert an der Design-Philosophie, Materialität und Typografie von Apple.com.

> [!IMPORTANT]
> **Strikte Datenschutz- & Anonymisierungsvorgabe:**
> - **GitHub-Nutzername / Handle ist STRENG VERBOTEN:** Der GitHub-Nutzername (weder Handles noch Pseudo-Namen) darf zu KEINER Zeit auf der Website, im UI, in Labels, Tooltips, Texten oder sichtbaren Links auftauchen.
> - **Ausschließliche Namensnennung:** Nur "Jacob Glathe" bzw. "Jacob Glathe & Team".
> - **Links zu Open-Source-Quellen:** Werden neutral als "Open Source", "Code Repository" oder "GitHub" beschriftet, ohne dass der Account-Handle im sichtbaren Text erscheint.
> - **Hardware- & IoT-Fokus:** Open-Source Multi-Tool auf ESP32-Basis (zugängliche Flipper-Zero-Alternative) & Linux-Server-Ökosystem in professioneller LinkedIn-Tonalität.

---

## 1. Overview & Core Concept

- **Was die Plattform leistet:** Repräsentiert Jacob Glathe & Team an der Schnittstelle von hardwarenaher Entwicklung (Embedded Systems, ESP32, Cyber-Physical Tools), Linux-Server-Infrastruktur und modernen Web- & KI-Systemen.
- **Tonalität (High-End & LinkedIn-Leadership):** 
  - *Positionierung:* "Demokratisierung von Hardware-Security & IoT-Edge-Computing durch zugängliches Engineering."
  - *Projekt-Storytelling:* Fokus auf Problem-Lösung-Impact: Wie hochmoderne Multi-Tools durch intelligente ESP32-Firmware und Linux-Server-Orchestrierung kosteneffizient und quelloffen für Entwickler und Sicherheitsforscher realisiert werden.
- **Vollständige Anonymität externer Benutzerkonten:** Nur der reale Name "Jacob Glathe" und die Domain-Präsenz werden kommuniziert.

---

## 2. User Experience & Visual Design

### Key User Flows
1. **Hero Section:** Apple-typischer Minimalismus mit Fokus auf Jacob Glathe (Lead Engineer & Hardware/Software Architect) und sein Team. Saubere CTAs: "Projekte entdecken" & "Kontakt aufnehmen".
2. **Interactive Bento Showcase:**
   - **Feature Card 01 (Groß - Flaggschiff):** *Open Multi-Tool: Accessible Hardware Security (ESP32)*
     - *LinkedIn Pitch:* "Hardware-Sicherheitsforschung neu gedacht: Entwicklung eines extrem zugänglichen Open-Source Multi-Tools auf ESP32-Basis, gekoppelt mit Linux-Server-Diensten."
     - *Metriken & Specs:* `< 25 € Hardware-BOM · Open-Source Firmware · Sub-GHz / NFC / IR · Realtime Linux Telemetrie`.
   - **Feature Card 02:** *ESP32 Distributed Linux Mesh & Edge Hub* — Smarte Microcontroller-Flottenverwaltung mit Linux-Server-Daemon und WebSocket-Streaming.
   - **Feature Card 03:** *Modern High-Performance Web & Full-Stack Systems* — Responsive Plattformen nach Apple-Designprinzipien.
   - **Feature Card 04:** *Autonomous AI & Automation Pipelines* — Intelligente Workflows für Entwickler.
3. **Bento Card Micro-Interaktionen:**
   - Soft Elevation & Hairline Border: `border border-white/10 dark:border-white/10` bzw. `border-black/5` in Light.
   - Motion Hover: Glatte Bézier-Transition (`transition-all duration-300 ease-out hover:scale-[1.015] hover:shadow-2xl hover:border-white/20`).
   - Bildbereich: 16:9 / 4:3 Bildslot mit professionellem Hardware- / UI-Asset und SVG/Gradient-Mesh Fallback.
   - Unboxed Metadaten: `ESP32 · Linux Server · C++ / FreeRTOS · Open Source` getrennt durch elegante Mittelpunkte `·` (Anti-Slop: keine bunten Pill-Badges).
4. **Detail Modal:** Klick auf eine Bento-Card öffnet die vollständige technische Analyse (Architektur, Pinout/BOM, Software-Stack, Open-Source-Verlinkung ohne Handle-Anzeige).
5. **Team & Philosophie:** 3-Spalten-Karten mit Jacob Glathe und Ingenieurskollegen, verlinkt mit Socials/E-Mail.

```
┌──────────────────────────────────────────────────────────────────────────────┐
│  Jacob Glathe & Team    [Showcase]  [Hardware & IoT]  [Team]  [Kontakt] DE|EN ☼│
├──────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│             ENGINEERING THE FUTURE OF EMBEDDED & CLOUD SYSTEMS               │
│                                                                              │
│    From bare-metal ESP32 microcontrollers to distributed Linux servers       │
│    and high-end web platforms. Led by Jacob Glathe & Team.                   │
│                                                                              │
│          [ Open-Source Projekte ↗ ]       [ Ausgewählte Arbeiten ↓ ]         │
│                                                                              │
├──────────────────────────────────────────────────────────────────────────────┤
│  BENTO SHOWCASE (APPLE SQUIRCLE 28px RADIUS)                                 │
│  ┌────────────────────────────────────────────────┬─────────────────────────┐│
│  │ 01. Open Multi-Tool: Flipper Alternative (ESP32)│ 02. Linux Edge Node Hub ││
│  │ Accessible hardware security & sub-GHz analysis│ Linux Daemon & IoT Mesh ││
│  │ ESP32 · FreeRTOS · Sub-GHz · Open Source       │ C++ · Rust · WebSockets ││
│  └────────────────────────────────────────────────┴─────────────────────────┘│
│  ┌────────────────────────┬────────────────────────┬────────────────────────┐│
│  │ 03. High-Performance Web│ 04. Linux Server Infra │ 05. AI Agent Systems   ││
│  │ Apple-grade UX & Speed │ Automated CI/CD & APIs │ Autonomous Pipelines   ││
│  └────────────────────────┴────────────────────────┴────────────────────────┘│
├──────────────────────────────────────────────────────────────────────────────┤
│  FOOTER: jcob.glathe@gmail.com · Open Source Repositories · Apple Minimalist │
└──────────────────────────────────────────────────────────────────────────────┘
```

---

## 3. Key Product Decisions & Trade-Offs

- **Entscheidung 1: Striktes Handle-Masking & Datenmodell**
  - *Ansatz:* Konfiguration in `src/data/projects.ts` und `src/data/team.ts` verwendet keine persönlichen Nicknames/Handles. Sichtbare Labels heißen ausschließlich "Open Source Code", "Repository" oder "GitHub", ohne den Benutzernamen preiszugeben.
  - *Vorteil:* Vollständige Wahrung der Privatsphäre bei gleichzeitig maximaler technischer Glaubwürdigkeit.

- **Entscheidung 2: Bento Card als hochmodulare UI-Komponente (`BentoCard.tsx`)**
  - *Ansatz:* Eine eigenständige, wiederverwendbare `BentoCard`-Komponente in `src/components/ui/BentoCard.tsx` mit konfigurierbarem Span (`col-span-1` vs `col-span-2`), Bild-Asset, Typografie, Tech-Tags und Klick-Handler.
  - *Vorteil:* Erfüllt exakt den Nutzerauftrag und kann überall im Projekt eingesetzt werden.

- **Entscheidung 3: Visuelle Assets für Hardware & IoT**
  - *Ansatz:* Generierung von studio-beleuchteten, fotorealistischen Hardware-Assets (ESP32 Devboard mit OLED & Antenne im Apple-Produktfotografie-Stil) via `generate_image`.

---

## 4. Technical Architecture & Dateistruktur

```
src/
├── types/
│   └── index.ts                 # Project, TechStack, TeamMember, i18n Types
├── data/
│   ├── projects.ts              # Flipper Zero Alternative, ESP32 Linux Hub, etc.
│   ├── team.ts                  # Jacob Glathe & Teammitglieder
│   └── content.ts               # Mehrsprachige Texte (DE/EN)
├── context/
│   └── AppContext.tsx           # Language & Theme State
├── components/
│   ├── ui/
│   │   ├── BentoCard.tsx        # Apple-Style Bento Grid Card (Hover, Image, Specs)
│   │   ├── ProjectModal.tsx     # Tiefgehende Projektanalyse im Modal
│   │   └── ThemeLanguageToggle.tsx
│   ├── layout/
│   │   ├── Navbar.tsx           # Apple Frosted Glass Top Bar
│   │   └── Footer.tsx           # Minimalistischer Footer ohne Handle-Nennung
│   └── sections/
│       ├── HeroSection.tsx      # Typografie, Vision, Action CTAs
│       ├── BentoShowcase.tsx    # Filterbares Bento-Grid mit BentoCard-Instanzen
│       ├── TeamSection.tsx      # Team & Philosophie
│       └── ContactSection.tsx   # Kontakt & Social Links
```
