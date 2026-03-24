<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- HERO BANNER -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" width="840" height="240" viewBox="0 0 840 240">
  <defs>
    <linearGradient id="hbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0c0f"/>
      <stop offset="100%" style="stop-color:#111318"/>
    </linearGradient>
    <linearGradient id="hac" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff4d1c"/>
      <stop offset="100%" style="stop-color:#ff8c42"/>
    </linearGradient>
  </defs>
  <rect width="840" height="240" fill="url(#hbg)" rx="16"/>
  <rect x="0" y="236" width="840" height="4" fill="url(#hac)" rx="2"/>
  <g opacity="0.05" fill="#ff4d1c">
    <polygon points="60,30 80,18 100,30 100,54 80,66 60,54"/>
    <polygon points="110,30 130,18 150,30 150,54 130,66 110,54"/>
    <polygon points="85,60 105,48 125,60 125,84 105,96 85,84"/>
    <polygon points="680,130 700,118 720,130 720,154 700,166 680,154"/>
    <polygon points="730,130 750,118 770,130 770,154 750,166 730,154"/>
    <polygon points="750,30 770,18 790,30 790,54 770,66 750,54"/>
    <polygon points="35,140 55,128 75,140 75,164 55,176 35,164"/>
  </g>
  <!-- Hex icon -->
  <polygon points="420,20 458,42 458,86 420,108 382,86 382,42" fill="url(#hac)"/>
  <polygon points="420,32 448,49 448,83 420,100 392,83 392,49" fill="#0a0c0f"/>
  <text x="420" y="73" font-family="monospace" font-size="22" fill="#ff4d1c" text-anchor="middle" font-weight="bold">CW</text>
  <!-- Title -->
  <text x="420" y="140" font-family="Arial,Helvetica,sans-serif" font-size="28" fill="#e8eaf0" text-anchor="middle" font-weight="800" letter-spacing="3">CIVIC INTELLIGENCE NETWORK</text>
  <!-- Subtitle -->
  <text x="420" y="168" font-family="Arial,Helvetica,sans-serif" font-size="13" fill="#8892a4" text-anchor="middle" letter-spacing="1">The Balangir District Civic AI Platform for Market Integrity &amp; Citizen Protection</text>
  <!-- Tagline -->
  <rect x="250" y="182" width="340" height="24" rx="12" fill="rgba(255,77,28,0.1)" stroke="#ff4d1c" stroke-width="0.5"/>
  <text x="420" y="198" font-family="monospace" font-size="10" fill="#ff8c42" text-anchor="middle" letter-spacing="1">citizens sense · journalists verify · AI analyzes · governments act</text>
  <!-- Version -->
  <rect x="700" y="14" width="120" height="22" rx="11" fill="rgba(0,200,83,0.12)" stroke="#00c853" stroke-width="0.5"/>
  <text x="760" y="29" font-family="monospace" font-size="9" fill="#00c853" text-anchor="middle">v1.0 PROTOTYPE</text>
</svg>

<br/>

<!-- BADGE ROW 1 -->
[![Live Demo](https://img.shields.io/badge/▶_LIVE_DEMO-ff4d1c?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ab-aswini.github.io/civic-intelligence-network)
[![Architecture](https://img.shields.io/badge/🏗_ARCHITECTURE-2196f3?style=for-the-badge)](https://ab-aswini.github.io/civic-intelligence-network/architecture.html)
[![MIT License](https://img.shields.io/badge/📄_MIT_LICENSE-00c853?style=for-the-badge)](./LICENSE)

<!-- BADGE ROW 2 -->
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Zero_Dependencies-111318?style=flat-square)
![Single File](https://img.shields.io/badge/Single_File_App-ff8c42?style=flat-square)
![Open Source](https://img.shields.io/badge/Open_Source-00c853?style=flat-square&logo=github&logoColor=white)
![Balangir](https://img.shields.io/badge/Balangir,_Odisha-ff4d1c?style=flat-square)

<br/>

**LPG cylinders at ₹939 MRP are sold for ₹2,500 in Balangir. Citizens can't verify, report, or fight back.**
**CivicWatch is the civic intelligence layer that turns scattered complaints into structured, blockchain-logged,**
**AI-drafted formal complaints that authorities must publicly respond to — or be permanently scored.**

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- TABLE OF CONTENTS -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📑 Table of Contents

| | Section | Description |
|:---:|:---|:---|
| 🔥 | [The Problem](#-the-problem) | Why this exists — the Balangir crisis |
| 🧠 | [How It Works](#-how-it-works) | The 5-actor pipeline from citizen to authority |
| 🏛 | [System Architecture](#-system-architecture--governance-model) | Multi-tier governance model with data flow |
| 🔄 | [End-to-End Flow](#-end-to-end-data-flow) | 9-step signal-to-authority pipeline |
| 📊 | [Case Lifecycle](#-case-lifecycle--state-machine) | State machine for case progression |
| 🛡 | [Trust Model](#-trust--verification-model) | Signal strength algorithm and partner tiers |
| 🖥 | [6 Screens](#-platform-screens--6-views) | All platform views explained |
| 💰 | [Market Data](#-live-market-data) | Commodity prices: official vs black market |
| 💡 | [Ideation Journey](#-ideation-journey) | From SupplySentinel to Civic Intelligence Network |
| 🗺 | [Roadmap](#-future-vision--roadmap) | Q2 2026 → Q2 2027+ development plan |
| ⚡ | [Quick Start](#-quick-start) | Run locally in 10 seconds |
| 🤝 | [Contributing](#-how-to-contribute) | 6 ways to help — all skill levels welcome |
| 🔒 | [Security & Privacy](#-security--privacy) | Anonymity architecture and data protection |
| 📜 | [License](#-license) | MIT — free forever |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- THE PROBLEM -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🔥 The Problem

<table>
<tr>
<td width="120" align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100">
  <rect width="100" height="100" fill="#0a0c0f" rx="14"/>
  <circle cx="50" cy="42" r="30" fill="none" stroke="#ff1744" stroke-width="2.5" stroke-dasharray="4,3"/>
  <text x="50" y="36" font-size="24" text-anchor="middle">🔥</text>
  <text x="50" y="56" font-family="monospace" font-size="14" fill="#ff1744" text-anchor="middle" font-weight="bold">₹2,500</text>
  <line x1="28" y1="72" x2="72" y2="72" stroke="#ff1744" stroke-width="1" opacity="0.4"/>
  <text x="50" y="86" font-family="monospace" font-size="10" fill="#4a5568" text-anchor="middle">MRP ₹939</text>
  <text x="50" y="96" font-family="monospace" font-size="8" fill="#ff1744" text-anchor="middle">+166%</text>
</svg>

</td>
<td>

### The Balangir LPG Crisis

**LPG cylinders with an official MRP of ₹939 are being sold at ₹2,500 on the black market** in Balangir, Odisha — a 166% markup affecting thousands of families.

The same pattern repeats across commodities: mustard oil (+45%), toor dal (+42%), onions (+63%).

**Why nothing works today:**
- Individual complaints = noise. Authorities ignore them.
- No way to verify if prices are actually inflated or rumored.
- Evidence is scattered across WhatsApp groups, phone calls, verbal reports.
- Zero public accountability for government response (or lack of it).

> **CivicWatch turns 47 scattered complaints into 1 structured, AI-drafted, blockchain-logged formal case** that the District Collector must respond to within 72 hours — or his 31% response rate becomes a permanent public record.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- HOW IT WORKS -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🧠 How It Works

> **5 actors. 1 pipeline. Every step verified. Every action logged.**

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="840" height="140" viewBox="0 0 840 140">
  <rect width="840" height="140" fill="#0a0c0f" rx="14"/>
  <!-- Flow line -->
  <line x1="130" y1="52" x2="720" y2="52" stroke="#1e2530" stroke-width="2"/>
  <line x1="130" y1="52" x2="720" y2="52" stroke="url(#pipeGrad)" stroke-width="2" stroke-dasharray="8,4"/>
  <defs>
    <linearGradient id="pipeGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff4d1c"/><stop offset="50%" style="stop-color:#ffd740"/><stop offset="100%" style="stop-color:#00c853"/>
    </linearGradient>
  </defs>
  <!-- 1 Citizen -->
  <circle cx="84" cy="52" r="32" fill="#181c24" stroke="#ff4d1c" stroke-width="2.5"/>
  <text x="84" y="50" font-size="20" text-anchor="middle">👤</text>
  <text x="84" y="64" font-family="monospace" font-size="7" fill="#ff4d1c" text-anchor="middle">STEP 1</text>
  <text x="84" y="104" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">CITIZEN</text>
  <text x="84" y="118" font-family="Arial,sans-serif" font-size="8" fill="#8892a4" text-anchor="middle">Anonymous Signal</text>
  <text x="84" y="130" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">30 sec · no login</text>
  <!-- Arrow label -->
  <text x="168" y="46" font-family="Arial,sans-serif" font-size="7" fill="#4a5568" text-anchor="middle">confirms pile up →</text>
  <!-- 2 Journalist -->
  <circle cx="252" cy="52" r="32" fill="#181c24" stroke="#ffd740" stroke-width="2.5"/>
  <text x="252" y="50" font-size="20" text-anchor="middle">📰</text>
  <text x="252" y="64" font-family="monospace" font-size="7" fill="#ffd740" text-anchor="middle">STEP 2</text>
  <text x="252" y="104" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">JOURNALIST</text>
  <text x="252" y="118" font-family="Arial,sans-serif" font-size="8" fill="#8892a4" text-anchor="middle">Field Verification</text>
  <text x="252" y="130" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">sealed · independent</text>
  <text x="336" y="46" font-family="Arial,sans-serif" font-size="7" fill="#4a5568" text-anchor="middle">strength grows →</text>
  <!-- 3 AI -->
  <circle cx="420" cy="52" r="32" fill="#181c24" stroke="#2196f3" stroke-width="2.5"/>
  <text x="420" y="50" font-size="20" text-anchor="middle">🤖</text>
  <text x="420" y="64" font-family="monospace" font-size="7" fill="#2196f3" text-anchor="middle">STEP 3</text>
  <text x="420" y="104" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">AI ENGINE</text>
  <text x="420" y="118" font-family="Arial,sans-serif" font-size="8" fill="#8892a4" text-anchor="middle">Pattern + Draft</text>
  <text x="420" y="130" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">ECA 1955 · 91% conf</text>
  <text x="504" y="46" font-family="Arial,sans-serif" font-size="7" fill="#4a5568" text-anchor="middle">complaint ready →</text>
  <!-- 4 Admin -->
  <circle cx="588" cy="52" r="32" fill="#181c24" stroke="#ff4d1c" stroke-width="2.5"/>
  <text x="588" y="50" font-size="20" text-anchor="middle">🔒</text>
  <text x="588" y="64" font-family="monospace" font-size="7" fill="#ff4d1c" text-anchor="middle">STEP 4</text>
  <text x="588" y="104" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">ADMIN</text>
  <text x="588" y="118" font-family="Arial,sans-serif" font-size="8" fill="#8892a4" text-anchor="middle">Review &amp; Authorize</text>
  <text x="588" y="130" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">blockchain logged</text>
  <text x="672" y="46" font-family="Arial,sans-serif" font-size="7" fill="#4a5568" text-anchor="middle">filed to govt →</text>
  <!-- 5 Authority -->
  <circle cx="756" cy="52" r="32" fill="#181c24" stroke="#00c853" stroke-width="2.5"/>
  <text x="756" y="50" font-size="20" text-anchor="middle">🏛</text>
  <text x="756" y="64" font-family="monospace" font-size="7" fill="#00c853" text-anchor="middle">STEP 5</text>
  <text x="756" y="104" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">AUTHORITY</text>
  <text x="756" y="118" font-family="Arial,sans-serif" font-size="8" fill="#8892a4" text-anchor="middle">72hr Response</text>
  <text x="756" y="130" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">public scorecard</text>
</svg>

</div>

<br/>

> Every task flows: **Citizen → Dedup Gate → Score → Verify → AI Draft → Admin Review → File → Track**

| Step | Actor | What Happens | Output |
|:---:|:---:|:---|:---|
| `1` | **Citizen** | Anonymously reports an overpriced commodity in their area | Signal with tracking ID (e.g. `CIN-2026-BLG-067-OIL`) |
| `2` | **Journalist** | Claims signal, visits location, verifies prices independently | Strength score jumps (+28 pts for Master verifier) |
| `3` | **AI Engine** | Detects hoarding patterns, drafts formal ECA 1955 complaint | Legal letter with evidence summary |
| `4` | **Admin** | Reviews AI draft, edits if needed, authorizes filing | Case filed to District Collector |
| `5` | **Authority** | Receives complaint, 72-hour public response timer starts | Action taken — or escalation to State level |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ARCHITECTURE — THE ORG CHART -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏛 System Architecture — Governance Model

<div align="center">

### The CivicWatch Org Chart

<svg xmlns="http://www.w3.org/2000/svg" width="840" height="860" viewBox="0 0 840 860">
  <defs>
    <linearGradient id="obg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0c0f"/>
      <stop offset="100%" style="stop-color:#0d1017"/>
    </linearGradient>
    <marker id="ad" markerWidth="10" markerHeight="7" refX="5" refY="7" orient="auto"><polygon points="0 0, 10 0, 5 7" fill="#4a5568"/></marker>
    <marker id="au" markerWidth="10" markerHeight="7" refX="5" refY="0" orient="auto"><polygon points="0 7, 10 7, 5 0" fill="#2196f3"/></marker>
  </defs>
  <rect width="840" height="860" fill="url(#obg)" rx="16"/>
  <rect x="1" y="1" width="838" height="858" fill="none" rx="16" stroke="#1e2530" stroke-width="1"/>

  <!-- ═══ TITLE ═══ -->
  <line x1="220" y1="32" x2="620" y2="32" stroke="#2a3040" stroke-width="1"/>
  <text x="420" y="26" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="800" letter-spacing="4">CIVICWATCH GOVERNANCE MODEL</text>
  <line x1="220" y1="42" x2="620" y2="42" stroke="#2a3040" stroke-width="1"/>

  <!-- ═══ TOP: CITIZEN (Owner) ═══ -->
  <rect x="310" y="62" width="220" height="52" rx="26" fill="#00c853"/>
  <text x="396" y="86" font-size="18" text-anchor="middle">👤</text>
  <text x="436" y="94" font-family="Arial,sans-serif" font-size="16" fill="#fff" text-anchor="middle" font-weight="800">CITIZEN (Reporter)</text>

  <!-- Arrow down -->
  <line x1="420" y1="114" x2="420" y2="148" stroke="#4a5568" stroke-width="2" marker-end="url(#ad)"/>
  <text x="460" y="136" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" font-style="italic">submits a signal</text>

  <!-- ═══ TIER 1 — CORE PIPELINE ═══ -->
  <rect x="40" y="152" width="760" height="110" rx="12" fill="none" stroke="#2a3040" stroke-width="1.5" stroke-dasharray="6,4"/>
  <text x="66" y="172" font-family="monospace" font-size="10" fill="#8892a4" font-weight="700" letter-spacing="2">TIER 1 — CORE PIPELINE</text>

  <!-- 4 boxes -->
  <rect x="60" y="186" width="160" height="58" rx="10" fill="#181c24" stroke="#ff4d1c" stroke-width="1.5"/>
  <text x="140" y="207" font-family="Arial,sans-serif" font-size="10" fill="#8892a4" text-anchor="middle">Signal Engine</text>
  <text x="140" y="225" font-family="monospace" font-size="11" fill="#ff4d1c" text-anchor="middle" font-weight="700">SE-001</text>
  <text x="140" y="239" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">DEDUP + INTAKE</text>

  <rect x="240" y="186" width="160" height="58" rx="10" fill="#181c24" stroke="#ffd740" stroke-width="1.5"/>
  <text x="320" y="207" font-family="Arial,sans-serif" font-size="10" fill="#8892a4" text-anchor="middle">Verification Hub</text>
  <text x="320" y="225" font-family="monospace" font-size="11" fill="#ffd740" text-anchor="middle" font-weight="700">VH-001</text>
  <text x="320" y="239" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">TRUST + SCORING</text>

  <rect x="420" y="186" width="160" height="58" rx="10" fill="#181c24" stroke="#2196f3" stroke-width="1.5"/>
  <text x="500" y="207" font-family="Arial,sans-serif" font-size="10" fill="#8892a4" text-anchor="middle">AI Analyst</text>
  <text x="500" y="225" font-family="monospace" font-size="11" fill="#2196f3" text-anchor="middle" font-weight="700">AI-001</text>
  <text x="500" y="239" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">PATTERN + DRAFT</text>

  <rect x="600" y="186" width="180" height="58" rx="10" fill="#181c24" stroke="#ff1744" stroke-width="1.5"/>
  <text x="690" y="207" font-family="Arial,sans-serif" font-size="10" fill="#8892a4" text-anchor="middle">Case Manager</text>
  <text x="690" y="225" font-family="monospace" font-size="11" fill="#ff1744" text-anchor="middle" font-weight="700">CM-001</text>
  <text x="690" y="239" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">ADMIN + FILE + TRACK</text>

  <!-- Arrow down + label -->
  <line x1="420" y1="262" x2="420" y2="295" stroke="#4a5568" stroke-width="2" marker-end="url(#ad)"/>
  <text x="460" y="282" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" font-style="italic">delegates work</text>

  <!-- ═══ TIER 2 — 9 SPECIALIZED MODULES ═══ -->
  <rect x="40" y="298" width="760" height="155" rx="12" fill="none" stroke="#2a3040" stroke-width="1.5" stroke-dasharray="6,4"/>
  <text x="66" y="318" font-family="monospace" font-size="10" fill="#8892a4" font-weight="700" letter-spacing="2">TIER 2 — 9 SPECIALIZED MODULES</text>

  <!-- Row 1: 5 modules -->
  <rect x="55" y="332" width="126" height="38" rx="8" fill="#ff4d1c" fill-opacity="0.2" stroke="#ff4d1c" stroke-width="1"/>
  <text x="68" y="352" font-size="10">📡</text>
  <text x="84" y="357" font-family="Arial,sans-serif" font-size="10" fill="#ff4d1c" font-weight="600">Dedup</text>
  <text x="160" y="357" font-family="monospace" font-size="7" fill="#8892a4">engine</text>

  <rect x="193" y="332" width="126" height="38" rx="8" fill="#ff8c42" fill-opacity="0.2" stroke="#ff8c42" stroke-width="1"/>
  <text x="206" y="352" font-size="10">⚡</text>
  <text x="222" y="357" font-family="Arial,sans-serif" font-size="10" fill="#ff8c42" font-weight="600">Strength</text>
  <text x="298" y="357" font-family="monospace" font-size="7" fill="#8892a4">scorer</text>

  <rect x="331" y="332" width="126" height="38" rx="8" fill="#ffd740" fill-opacity="0.2" stroke="#ffd740" stroke-width="1"/>
  <text x="344" y="352" font-size="10">🛡</text>
  <text x="360" y="357" font-family="Arial,sans-serif" font-size="10" fill="#ffd740" font-weight="600">Rumor</text>
  <text x="436" y="357" font-family="monospace" font-size="7" fill="#8892a4">buster</text>

  <rect x="469" y="332" width="126" height="38" rx="8" fill="#2196f3" fill-opacity="0.2" stroke="#2196f3" stroke-width="1"/>
  <text x="482" y="352" font-size="10">💰</text>
  <text x="498" y="357" font-family="Arial,sans-serif" font-size="10" fill="#2196f3" font-weight="600">Price</text>
  <text x="574" y="357" font-family="monospace" font-size="7" fill="#8892a4">oracle</text>

  <rect x="607" y="332" width="180" height="38" rx="8" fill="#00c853" fill-opacity="0.2" stroke="#00c853" stroke-width="1"/>
  <text x="620" y="352" font-size="10">📝</text>
  <text x="636" y="357" font-family="Arial,sans-serif" font-size="10" fill="#00c853" font-weight="600">Complaint</text>
  <text x="766" y="357" font-family="monospace" font-size="7" fill="#8892a4">drafter</text>

  <!-- Row 2: 4 modules -->
  <rect x="55" y="380" width="160" height="38" rx="8" fill="#9c27b0" fill-opacity="0.2" stroke="#9c27b0" stroke-width="1"/>
  <text x="68" y="400" font-size="10">🔗</text>
  <text x="84" y="405" font-family="Arial,sans-serif" font-size="10" fill="#9c27b0" font-weight="600">Blockchain</text>
  <text x="196" y="405" font-family="monospace" font-size="7" fill="#8892a4">logger</text>

  <rect x="227" y="380" width="140" height="38" rx="8" fill="#e91e63" fill-opacity="0.2" stroke="#e91e63" stroke-width="1"/>
  <text x="240" y="400" font-size="10">🔔</text>
  <text x="256" y="405" font-family="Arial,sans-serif" font-size="10" fill="#e91e63" font-weight="600">Notification</text>
  <text x="346" y="405" font-family="monospace" font-size="7" fill="#8892a4">svc</text>

  <rect x="379" y="380" width="140" height="38" rx="8" fill="#00bcd4" fill-opacity="0.2" stroke="#00bcd4" stroke-width="1"/>
  <text x="392" y="400" font-size="10">📊</text>
  <text x="408" y="405" font-family="Arial,sans-serif" font-size="10" fill="#00bcd4" font-weight="600">Analytics</text>
  <text x="498" y="405" font-family="monospace" font-size="7" fill="#8892a4">dash</text>

  <rect x="531" y="380" width="140" height="38" rx="8" fill="#8892a4" fill-opacity="0.15" stroke="#8892a4" stroke-width="1"/>
  <text x="544" y="400" font-size="10">🌐</text>
  <text x="560" y="405" font-family="Arial,sans-serif" font-size="10" fill="#8892a4" font-weight="600">i18n</text>
  <text x="650" y="405" font-family="monospace" font-size="7" fill="#4a5568">EN / ଓଡ଼ିଆ</text>

  <!-- Processing flow -->
  <rect x="120" y="430" width="600" height="16" rx="4" fill="#111318"/>
  <text x="420" y="441" font-family="monospace" font-size="8" fill="#4a5568" text-anchor="middle">📡 Submit → ✅ Dedup → ⚡ Score → 📰 Verify → 🤖 AI Draft → 🔒 Admin → 📧 File → 📊 Track</text>

  <!-- Bidirectional arrows to Tier 3 -->
  <line x1="220" y1="458" x2="220" y2="510" stroke="#2196f3" stroke-width="1.5" stroke-dasharray="4,3" marker-end="url(#ad)"/>
  <text x="240" y="488" font-family="Arial,sans-serif" font-size="8" fill="#2196f3" font-style="italic">context sync ↕</text>

  <line x1="620" y1="458" x2="620" y2="510" stroke="#ffd740" stroke-width="1.5" stroke-dasharray="4,3" marker-end="url(#ad)"/>
  <text x="640" y="488" font-family="Arial,sans-serif" font-size="8" fill="#ffd740" font-style="italic">design data ↕</text>

  <!-- ═══ TIER 3 — META + SHARED INTELLIGENCE ═══ -->
  <rect x="60" y="515" width="320" height="72" rx="12" fill="none" stroke="#2a3040" stroke-width="1.5" stroke-dasharray="6,4"/>
  <text x="80" y="532" font-family="monospace" font-size="9" fill="#8892a4" font-weight="700" letter-spacing="1">TIER 3 — META</text>
  <rect x="76" y="540" width="290" height="35" rx="8" fill="#e91e63" fill-opacity="0.12" stroke="#e91e63" stroke-width="1"/>
  <text x="86" y="558" font-size="10">🔗</text>
  <text x="100" y="563" font-family="Arial,sans-serif" font-size="10" fill="#e91e63" font-weight="600">Blockchain + State + Audit Trail + Permissions</text>

  <rect x="460" y="515" width="320" height="72" rx="12" fill="none" stroke="#ffd740" stroke-width="1.5" stroke-dasharray="6,4"/>
  <text x="480" y="532" font-family="monospace" font-size="9" fill="#ffd740" font-weight="700" letter-spacing="1">SHARED INTELLIGENCE</text>
  <rect x="476" y="540" width="290" height="35" rx="8" fill="#ffd740" fill-opacity="0.12" stroke="#ffd740" stroke-width="1"/>
  <text x="486" y="558" font-size="10">🌐</text>
  <text x="500" y="563" font-family="Arial,sans-serif" font-size="10" fill="#ffd740" font-weight="600">Gov APIs + IOCL + FCI/PDS + Mandi (8 sources)</text>

  <!-- Arrow to Output -->
  <line x1="420" y1="592" x2="420" y2="625" stroke="#4a5568" stroke-width="2" marker-end="url(#ad)"/>

  <!-- ═══ OUTPUT: AUTHORITY ACCOUNTABILITY ═══ -->
  <rect x="100" y="630" width="640" height="62" rx="12" fill="none" stroke="#00c853" stroke-width="2"/>
  <text x="420" y="650" font-family="monospace" font-size="9" fill="#00c853" text-anchor="middle" font-weight="700" letter-spacing="2">OUTPUT — AUTHORITY ACCOUNTABILITY LAYER</text>
  <rect x="120" y="660" width="175" height="24" rx="8" fill="#ff1744" fill-opacity="0.12" stroke="#ff1744" stroke-width="1"/>
  <text x="207" y="676" font-family="Arial,sans-serif" font-size="9" fill="#ff1744" text-anchor="middle" font-weight="600">DC Balangir — 31% ❌</text>
  <rect x="310" y="660" width="220" height="24" rx="8" fill="#00c853" fill-opacity="0.12" stroke="#00c853" stroke-width="1"/>
  <text x="420" y="676" font-family="Arial,sans-serif" font-size="9" fill="#00c853" text-anchor="middle" font-weight="600">CSO Balangir — 72% ✓</text>
  <rect x="545" y="660" width="180" height="24" rx="8" fill="#ffd740" fill-opacity="0.12" stroke="#ffd740" stroke-width="1"/>
  <text x="635" y="676" font-family="Arial,sans-serif" font-size="9" fill="#ffd740" text-anchor="middle" font-weight="600">State Commissioner ⏳</text>

  <!-- ═══ BOTTOM STATS BAR ═══ -->
  <rect x="60" y="720" width="720" height="120" rx="14" fill="#111318" stroke="#1e2530" stroke-width="1"/>

  <text x="420" y="748" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="800">8 Commodities · 8 Areas · 3 Tiers · 9 Modules · 5 Actors</text>
  <text x="420" y="768" font-family="Arial,sans-serif" font-size="10" fill="#4a5568" text-anchor="middle">Every signal flows: Citizen → Dedup → Score → Verify → AI → Admin → File → Track</text>

  <!-- Feature pills -->
  <rect x="100" y="785" width="130" height="30" rx="15" fill="#00c853" fill-opacity="0.1" stroke="#00c853" stroke-width="1"/>
  <text x="165" y="804" font-family="Arial,sans-serif" font-size="10" fill="#00c853" text-anchor="middle" font-weight="600">Zero Login</text>

  <rect x="250" y="785" width="130" height="30" rx="15" fill="#9c27b0" fill-opacity="0.1" stroke="#9c27b0" stroke-width="1"/>
  <text x="315" y="804" font-family="Arial,sans-serif" font-size="10" fill="#9c27b0" text-anchor="middle" font-weight="600">Tamper-Proof</text>

  <rect x="400" y="785" width="130" height="30" rx="15" fill="#2196f3" fill-opacity="0.1" stroke="#2196f3" stroke-width="1"/>
  <text x="465" y="804" font-family="Arial,sans-serif" font-size="10" fill="#2196f3" text-anchor="middle" font-weight="600">AI-Powered</text>

  <rect x="550" y="785" width="150" height="30" rx="15" fill="#ffd740" fill-opacity="0.1" stroke="#ffd740" stroke-width="1"/>
  <text x="625" y="804" font-family="Arial,sans-serif" font-size="10" fill="#ffd740" text-anchor="middle" font-weight="600">Open Source</text>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- END-TO-END DATA FLOW -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🔄 End-to-End Data Flow

> Every signal follows a **9-step deterministic path** from anonymous citizen report to formal government complaint. Every step is blockchain-logged.

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="840" height="1060" viewBox="0 0 840 1060">
  <defs>
    <marker id="fa" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#ff4d1c"/></marker>
    <marker id="fg" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#00c853"/></marker>
    <marker id="fy" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#ffd740"/></marker>
    <marker id="fb" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#2196f3"/></marker>
    <marker id="fr" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#ff1744"/></marker>
  </defs>
  <rect width="840" height="1060" fill="#0a0c0f" rx="16"/>
  <text x="420" y="32" font-family="Arial,sans-serif" font-size="14" fill="#e8eaf0" text-anchor="middle" font-weight="800" letter-spacing="2">END-TO-END SIGNAL PROCESSING PIPELINE</text>
  <text x="420" y="50" font-family="Arial,sans-serif" font-size="9" fill="#4a5568" text-anchor="middle">Every step is blockchain-logged · Deterministic flow · No manual gaps</text>

  <!-- Blockchain sidebar label -->
  <text x="34" y="550" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" transform="rotate(-90 34 550)" letter-spacing="3">BLOCKCHAIN AUDIT TRAIL — EVERY STEP CRYPTOGRAPHICALLY CHAINED</text>

  <!-- ═══ STEP 1 ═══ -->
  <rect x="260" y="70" width="320" height="65" rx="14" fill="#181c24" stroke="#ff4d1c" stroke-width="2"/>
  <circle cx="290" cy="96" r="14" fill="#ff4d1c" fill-opacity="0.2"/><text x="290" y="101" font-size="14" text-anchor="middle">👤</text>
  <text x="420" y="92" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">1. CITIZEN SUBMITS SIGNAL</text>
  <text x="420" y="112" font-family="monospace" font-size="9" fill="#ff4d1c" text-anchor="middle">Anonymous · No account · 30 seconds</text>
  <text x="420" y="124" font-family="monospace" font-size="8" fill="#4a5568" text-anchor="middle">Select area + commodity + price seen → submit</text>

  <line x1="420" y1="135" x2="420" y2="168" stroke="#ff4d1c" stroke-width="2" marker-end="url(#fa)"/>

  <!-- ═══ STEP 2: DEDUP ═══ -->
  <polygon points="420,175 530,215 420,255 310,215" fill="#181c24" stroke="#ff8c42" stroke-width="2"/>
  <text x="420" y="210" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0" text-anchor="middle" font-weight="700">2. DEDUP CHECK</text>
  <text x="420" y="224" font-family="monospace" font-size="8" fill="#ff8c42" text-anchor="middle">area + commodity match?</text>

  <!-- YES branch -->
  <line x1="310" y1="215" x2="175" y2="215" stroke="#00c853" stroke-width="1.5" marker-end="url(#fg)"/>
  <text x="242" y="207" font-family="Arial,sans-serif" font-size="8" fill="#00c853" font-weight="700">MATCH</text>
  <rect x="65" y="193" width="110" height="46" rx="8" fill="#181c24" stroke="#00c853" stroke-width="1.5"/>
  <text x="120" y="212" font-family="Arial,sans-serif" font-size="9" fill="#e8eaf0" text-anchor="middle" font-weight="600">Merge Signal</text>
  <text x="120" y="228" font-family="monospace" font-size="9" fill="#00c853" text-anchor="middle">Strength +3</text>

  <!-- NO branch -->
  <line x1="420" y1="255" x2="420" y2="290" stroke="#ff4d1c" stroke-width="2" marker-end="url(#fa)"/>
  <text x="450" y="276" font-family="Arial,sans-serif" font-size="8" fill="#ff8c42" font-weight="700">NEW</text>

  <!-- ═══ STEP 3 ═══ -->
  <rect x="260" y="295" width="320" height="65" rx="14" fill="#181c24" stroke="#ff4d1c" stroke-width="2"/>
  <circle cx="290" cy="321" r="14" fill="#ff4d1c" fill-opacity="0.2"/><text x="290" y="326" font-size="14" text-anchor="middle">📡</text>
  <text x="420" y="317" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">3. SIGNAL CREATED</text>
  <text x="420" y="337" font-family="monospace" font-size="9" fill="#ff4d1c" text-anchor="middle">CIN-2026-BLG-067-OIL · Strength: 1/100</text>
  <text x="420" y="350" font-family="monospace" font-size="8" fill="#4a5568" text-anchor="middle">Tracking ID assigned · Timeline started</text>
  <!-- Blockchain -->
  <rect x="620" y="302" width="180" height="48" rx="8" fill="#111318" stroke="#9c27b0" stroke-width="1"/>
  <text x="710" y="320" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" font-weight="600">BLOCKCHAIN #1</text>
  <text x="710" y="336" font-family="monospace" font-size="9" fill="#8892a4" text-anchor="middle">a3f9c2d1... ✓</text>
  <text x="710" y="346" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">Signal created</text>
  <line x1="580" y1="327" x2="620" y2="327" stroke="#9c27b0" stroke-width="1" stroke-dasharray="3,2"/>

  <line x1="420" y1="360" x2="420" y2="395" stroke="#ff8c42" stroke-width="2" marker-end="url(#fa)"/>

  <!-- ═══ STEP 4 ═══ -->
  <rect x="260" y="400" width="320" height="55" rx="14" fill="#181c24" stroke="#ff8c42" stroke-width="2"/>
  <circle cx="290" cy="421" r="14" fill="#ff8c42" fill-opacity="0.2"/><text x="290" y="426" font-size="14" text-anchor="middle">👥</text>
  <text x="420" y="420" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">4. CITIZEN CONFIRMATIONS</text>
  <text x="420" y="440" font-family="monospace" font-size="9" fill="#ff8c42" text-anchor="middle">47 confirms over 8 hours → Strength: 35/100</text>
  <rect x="620" y="405" width="180" height="40" rx="8" fill="#111318" stroke="#9c27b0" stroke-width="1"/>
  <text x="710" y="422" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" font-weight="600">BLOCKCHAIN #2</text>
  <text x="710" y="438" font-family="monospace" font-size="9" fill="#8892a4" text-anchor="middle">b7d4e1f2... ✓</text>
  <line x1="580" y1="427" x2="620" y2="427" stroke="#9c27b0" stroke-width="1" stroke-dasharray="3,2"/>

  <line x1="420" y1="455" x2="420" y2="490" stroke="#ffd740" stroke-width="2" marker-end="url(#fy)"/>

  <!-- ═══ STEP 5 ═══ -->
  <rect x="240" y="495" width="360" height="72" rx="14" fill="#181c24" stroke="#ffd740" stroke-width="2"/>
  <circle cx="270" cy="524" r="14" fill="#ffd740" fill-opacity="0.2"/><text x="270" y="529" font-size="14" text-anchor="middle">📰</text>
  <text x="420" y="518" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">5. JOURNALIST VERIFIES</text>
  <text x="420" y="536" font-family="Arial,sans-serif" font-size="9" fill="#ffd740" text-anchor="middle">Ramesh Panda (Master · 94% accuracy · ×1.6 weight)</text>
  <text x="420" y="552" font-family="monospace" font-size="9" fill="#ffd740" text-anchor="middle">+28 strength → Total: 63/100</text>
  <rect x="620" y="505" width="180" height="48" rx="8" fill="#111318" stroke="#9c27b0" stroke-width="1"/>
  <text x="710" y="522" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" font-weight="600">BLOCKCHAIN #3-4</text>
  <text x="710" y="538" font-family="monospace" font-size="9" fill="#8892a4" text-anchor="middle">c2a8f789... ✓</text>
  <text x="710" y="548" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">Primary + Supporting</text>
  <line x1="600" y1="530" x2="620" y2="530" stroke="#9c27b0" stroke-width="1" stroke-dasharray="3,2"/>

  <line x1="420" y1="567" x2="420" y2="598" stroke="#00c853" stroke-width="2" marker-end="url(#fg)"/>

  <!-- ═══ STEP 6 ═══ -->
  <rect x="260" y="603" width="320" height="55" rx="14" fill="#181c24" stroke="#00c853" stroke-width="2"/>
  <circle cx="290" cy="624" r="14" fill="#00c853" fill-opacity="0.2"/><text x="290" y="629" font-size="14" text-anchor="middle">🏢</text>
  <text x="420" y="623" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">6. NGO CO-SIGNATURE</text>
  <text x="420" y="643" font-family="monospace" font-size="9" fill="#00c853" text-anchor="middle">PRADAN Balangir · 14 households · +15 → 83/100</text>
  <rect x="620" y="608" width="180" height="40" rx="8" fill="#111318" stroke="#9c27b0" stroke-width="1"/>
  <text x="710" y="625" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" font-weight="600">BLOCKCHAIN #5</text>
  <text x="710" y="641" font-family="monospace" font-size="9" fill="#8892a4" text-anchor="middle">e5f1a2b3... ✓</text>
  <line x1="580" y1="628" x2="620" y2="628" stroke="#9c27b0" stroke-width="1" stroke-dasharray="3,2"/>

  <line x1="420" y1="658" x2="420" y2="690" stroke="#2196f3" stroke-width="2" marker-end="url(#fb)"/>

  <!-- ═══ STEP 7 ═══ -->
  <rect x="260" y="695" width="320" height="55" rx="14" fill="#181c24" stroke="#2196f3" stroke-width="2"/>
  <circle cx="290" cy="716" r="14" fill="#2196f3" fill-opacity="0.2"/><text x="290" y="721" font-size="14" text-anchor="middle">🤖</text>
  <text x="420" y="715" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">7. AI DRAFTS COMPLAINT</text>
  <text x="420" y="735" font-family="monospace" font-size="9" fill="#2196f3" text-anchor="middle">91% confidence · ECA 1955 · Formal complaint letter</text>

  <line x1="420" y1="750" x2="420" y2="782" stroke="#ff1744" stroke-width="2" marker-end="url(#fr)"/>

  <!-- ═══ STEP 8 ═══ -->
  <rect x="260" y="787" width="320" height="55" rx="14" fill="#181c24" stroke="#ff1744" stroke-width="2"/>
  <circle cx="290" cy="808" r="14" fill="#ff1744" fill-opacity="0.2"/><text x="290" y="813" font-size="14" text-anchor="middle">🔒</text>
  <text x="420" y="807" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="700">8. ADMIN AUTHORIZES &amp; FILES</text>
  <text x="420" y="827" font-family="monospace" font-size="9" fill="#ff1744" text-anchor="middle">+6 → Total: 89/100 · Filed to DC Balangir</text>
  <rect x="620" y="792" width="180" height="40" rx="8" fill="#111318" stroke="#9c27b0" stroke-width="1"/>
  <text x="710" y="809" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle" font-weight="600">BLOCKCHAIN #6-7</text>
  <text x="710" y="825" font-family="monospace" font-size="9" fill="#8892a4" text-anchor="middle">f3c7d9e1... ✓</text>
  <line x1="580" y1="812" x2="620" y2="812" stroke="#9c27b0" stroke-width="1" stroke-dasharray="3,2"/>

  <line x1="420" y1="842" x2="420" y2="878" stroke="#00c853" stroke-width="2.5" marker-end="url(#fg)"/>

  <!-- ═══ STEP 9 ═══ -->
  <rect x="210" y="883" width="420" height="75" rx="16" fill="#181c24" stroke="#00c853" stroke-width="3"/>
  <circle cx="245" cy="914" r="16" fill="#00c853" fill-opacity="0.2"/><text x="245" y="919" font-size="16" text-anchor="middle">🏛</text>
  <text x="420" y="907" font-family="Arial,sans-serif" font-size="14" fill="#e8eaf0" text-anchor="middle" font-weight="800">9. AUTHORITY TRACKED</text>
  <text x="420" y="928" font-family="Arial,sans-serif" font-size="10" fill="#00c853" text-anchor="middle">72-hour public response window · Accountability scorecard</text>
  <text x="420" y="948" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">No response in 96h? → Auto-escalate to State Civil Supplies Commissioner</text>

  <!-- Bottom summary -->
  <rect x="170" y="980" width="500" height="60" rx="12" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <text x="420" y="1003" font-family="Arial,sans-serif" font-size="10" fill="#e8eaf0" text-anchor="middle" font-weight="700">RESULT: 47 scattered complaints become 1 structured case</text>
  <text x="420" y="1020" font-family="monospace" font-size="8" fill="#ff4d1c" text-anchor="middle">89/100 strength · 7 blockchain entries · AI 91% confidence · 72hr timer</text>
  <text x="420" y="1034" font-family="monospace" font-size="8" fill="#4a5568" text-anchor="middle">DC response rate: 31% — permanent public record</text>
</svg>
</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- CASE LIFECYCLE -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📊 Case Lifecycle — State Machine

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="840" height="300" viewBox="0 0 840 300">
  <defs><marker id="la" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto"><polygon points="0 0, 8 3, 0 6" fill="#4a5568"/></marker></defs>
  <rect width="840" height="300" fill="#0a0c0f" rx="14"/>
  <text x="420" y="28" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="800" letter-spacing="2">CASE LIFECYCLE STATE MACHINE</text>
  <text x="420" y="44" font-family="monospace" font-size="8" fill="#4a5568" text-anchor="middle">Every transition is blockchain-logged · Immutable · Publicly verifiable</text>

  <!-- Main flow -->
  <rect x="25" y="70" width="110" height="55" rx="12" fill="#181c24" stroke="#ff4d1c" stroke-width="2"/>
  <text x="80" y="92" font-family="Arial,sans-serif" font-size="11" fill="#ff4d1c" text-anchor="middle" font-weight="700">SIGNAL</text>
  <text x="80" y="108" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">1-35 pts</text>

  <line x1="135" y1="97" x2="185" y2="97" stroke="#4a5568" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="160" y="89" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">claims</text>

  <rect x="190" y="70" width="130" height="55" rx="12" fill="#181c24" stroke="#ffd740" stroke-width="2"/>
  <text x="255" y="92" font-family="Arial,sans-serif" font-size="11" fill="#ffd740" text-anchor="middle" font-weight="700">INVESTIGATING</text>
  <text x="255" y="108" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">journalist claimed</text>

  <line x1="320" y1="97" x2="370" y2="97" stroke="#4a5568" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="345" y="89" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">verified</text>

  <rect x="375" y="70" width="110" height="55" rx="12" fill="#181c24" stroke="#00c853" stroke-width="2"/>
  <text x="430" y="92" font-family="Arial,sans-serif" font-size="11" fill="#00c853" text-anchor="middle" font-weight="700">VERIFIED</text>
  <text x="430" y="108" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">70+ pts</text>

  <line x1="485" y1="97" x2="535" y2="97" stroke="#4a5568" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="510" y="89" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">admin OK</text>

  <rect x="540" y="70" width="100" height="55" rx="12" fill="#181c24" stroke="#2196f3" stroke-width="2"/>
  <text x="590" y="92" font-family="Arial,sans-serif" font-size="11" fill="#2196f3" text-anchor="middle" font-weight="700">FILED</text>
  <text x="590" y="108" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">72hr timer</text>

  <line x1="640" y1="97" x2="695" y2="97" stroke="#4a5568" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="668" y="89" font-family="monospace" font-size="7" fill="#4a5568" text-anchor="middle">action</text>

  <rect x="700" y="70" width="110" height="55" rx="12" fill="#00c853" fill-opacity="0.15" stroke="#00c853" stroke-width="2.5"/>
  <text x="755" y="95" font-family="Arial,sans-serif" font-size="12" fill="#00c853" text-anchor="middle" font-weight="800">RESOLVED ✓</text>

  <!-- Branch: COUNTER -->
  <line x1="80" y1="125" x2="80" y2="170" stroke="#9c27b0" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="105" y="153" font-family="monospace" font-size="7" fill="#9c27b0">disputed</text>
  <rect x="25" y="175" width="110" height="45" rx="10" fill="#181c24" stroke="#9c27b0" stroke-width="1.5"/>
  <text x="80" y="197" font-family="Arial,sans-serif" font-size="10" fill="#9c27b0" text-anchor="middle" font-weight="700">COUNTER</text>
  <text x="80" y="212" font-family="monospace" font-size="7" fill="#8892a4" text-anchor="middle">evidence required</text>

  <!-- Branch: ESCALATED -->
  <line x1="590" y1="125" x2="590" y2="170" stroke="#ff1744" stroke-width="1.5" marker-end="url(#la)"/>
  <text x="620" y="153" font-family="monospace" font-size="7" fill="#ff1744">no response 96h</text>
  <rect x="535" y="175" width="110" height="45" rx="10" fill="#181c24" stroke="#ff1744" stroke-width="2"/>
  <text x="590" y="197" font-family="Arial,sans-serif" font-size="10" fill="#ff1744" text-anchor="middle" font-weight="700">ESCALATED</text>
  <text x="590" y="212" font-family="monospace" font-size="7" fill="#8892a4" text-anchor="middle">→ state level</text>

  <!-- Legend -->
  <rect x="100" y="245" width="640" height="36" rx="8" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="120" y="253" width="70" height="20" rx="4" fill="#00c853" fill-opacity="0.12"/><text x="155" y="267" font-family="monospace" font-size="8" fill="#00c853" text-anchor="middle">VERIFIED</text>
  <rect x="200" y="253" width="90" height="20" rx="4" fill="#ffd740" fill-opacity="0.12"/><text x="245" y="267" font-family="monospace" font-size="8" fill="#ffd740" text-anchor="middle">INVESTIGATING</text>
  <rect x="300" y="253" width="70" height="20" rx="4" fill="#8892a4" fill-opacity="0.12"/><text x="335" y="267" font-family="monospace" font-size="8" fill="#8892a4" text-anchor="middle">PENDING</text>
  <rect x="380" y="253" width="70" height="20" rx="4" fill="#9c27b0" fill-opacity="0.12"/><text x="415" y="267" font-family="monospace" font-size="8" fill="#9c27b0" text-anchor="middle">COUNTER</text>
  <rect x="460" y="253" width="80" height="20" rx="4" fill="#ff1744" fill-opacity="0.12"/><text x="500" y="267" font-family="monospace" font-size="8" fill="#ff1744" text-anchor="middle">ESCALATED</text>
  <rect x="550" y="253" width="80" height="20" rx="4" fill="#2196f3" fill-opacity="0.12"/><text x="590" y="267" font-family="monospace" font-size="8" fill="#2196f3" text-anchor="middle">FILED</text>
  <rect x="640" y="253" width="80" height="20" rx="4" fill="#00c853" fill-opacity="0.15"/><text x="680" y="267" font-family="monospace" font-size="8" fill="#00c853" text-anchor="middle">RESOLVED</text>
</svg>
</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- TRUST MODEL -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🛡 Trust &amp; Verification Model

### Signal Strength Algorithm

> How a signal goes from **0 to 89/100** — the math behind credibility.

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="840" height="260" viewBox="0 0 840 260">
  <rect width="840" height="260" fill="#0a0c0f" rx="14"/>
  <text x="420" y="25" font-family="monospace" font-size="10" fill="#8892a4" text-anchor="middle" font-weight="600" letter-spacing="1">SIGNAL STRENGTH COMPOSITION — CIN-2026-BLG-047-LPG</text>

  <text x="60" y="62" font-family="Arial,sans-serif" font-size="10" fill="#8892a4">Citizens (47 confirms)</text>
  <rect x="240" y="48" width="420" height="20" rx="5" fill="#181c24"/>
  <rect x="240" y="48" width="252" height="20" rx="5" fill="#ff4d1c" fill-opacity="0.6"/>
  <text x="502" y="62" font-family="monospace" font-size="10" fill="#ff4d1c" font-weight="700">+35 pts</text>
  <text x="690" y="62" font-family="monospace" font-size="8" fill="#4a5568">max 35 · diminishing returns after 20</text>

  <text x="60" y="100" font-family="Arial,sans-serif" font-size="10" fill="#8892a4">Primary Verifier (Master)</text>
  <rect x="240" y="86" width="420" height="20" rx="5" fill="#181c24"/>
  <rect x="240" y="86" width="201" height="20" rx="5" fill="#ffd740" fill-opacity="0.6"/>
  <text x="451" y="100" font-family="monospace" font-size="10" fill="#ffd740" font-weight="700">+28 pts</text>
  <text x="690" y="100" font-family="monospace" font-size="8" fill="#4a5568">weight = accuracy × tier multiplier</text>

  <text x="60" y="138" font-family="Arial,sans-serif" font-size="10" fill="#8892a4">Supporting (independent)</text>
  <rect x="240" y="124" width="420" height="20" rx="5" fill="#181c24"/>
  <rect x="240" y="124" width="144" height="20" rx="5" fill="#2196f3" fill-opacity="0.6"/>
  <text x="394" y="138" font-family="monospace" font-size="10" fill="#2196f3" font-weight="700">+20 pts</text>
  <text x="690" y="138" font-family="monospace" font-size="8" fill="#4a5568">independent confirmation bonus ×1.3</text>

  <text x="60" y="176" font-family="Arial,sans-serif" font-size="10" fill="#8892a4">NGO + Admin</text>
  <rect x="240" y="162" width="420" height="20" rx="5" fill="#181c24"/>
  <rect x="240" y="162" width="43" height="20" rx="5" fill="#00c853" fill-opacity="0.6"/>
  <text x="293" y="176" font-family="monospace" font-size="10" fill="#00c853" font-weight="700">+6 pts</text>
  <text x="690" y="176" font-family="monospace" font-size="8" fill="#4a5568">institutional endorsement</text>

  <line x1="60" y1="196" x2="780" y2="196" stroke="#1e2530" stroke-width="1"/>
  <text x="240" y="216" font-family="monospace" font-size="9" fill="#8892a4">Filing threshold: 70/100</text>
  <text x="660" y="216" font-family="monospace" font-size="13" fill="#00c853" font-weight="800">TOTAL: 89/100 ✓</text>

  <rect x="60" y="230" width="720" height="18" rx="4" fill="#111318"/>
  <text x="420" y="243" font-family="monospace" font-size="8" fill="#ff4d1c" text-anchor="middle">MFI = Violation Rate (40%) + Avg Price Deviation (35%) + Severity Index (15%) + Report Volume (10%)</text>
</svg>
</div>

### Partner Verification Tiers

| Tier | Requirements | Weight | Example |
|:---|:---|:---:|:---|
| **MASTER** ★ | 200+ verifications · 93%+ accuracy | `×1.6` | Ramesh Panda, Sambad |
| **SENIOR** | 50+ verifications · 90%+ accuracy | `×1.3` | Sunita Kar, OTV Digital |
| **NGO PARTNER** | Institutional registration | `×1.2` | PRADAN Balangir |
| **ACTIVE** | 10+ verifications · 85%+ accuracy | `×1.0` | Biswajit Rath, Dharitri |
| **NEW** | Less than 10 verifications | `×0.5` | Amrita Kulkarni, Freelance |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- 6 SCREENS -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🖥 Platform Screens — 6 Views

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="840" height="350" viewBox="0 0 840 350">
  <rect width="840" height="350" fill="#0a0c0f" rx="14"/>
  <!-- Screen 1 -->
  <rect x="20" y="20" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="20" y="20" width="250" height="5" rx="3" fill="#ff1744"/>
  <text x="145" y="55" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">01</text>
  <text x="145" y="78" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Dashboard</text>
  <text x="145" y="96" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Crisis alerts · MFI scores · AI insights</text>
  <text x="145" y="112" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Live signals · Rumor buster · Hotspots</text>
  <text x="145" y="132" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Official price reference table</text>
  <text x="145" y="152" font-family="monospace" font-size="10" fill="#ff1744" text-anchor="middle" font-weight="700">MFI: 38/100 CRITICAL</text>
  <!-- Screen 2 -->
  <rect x="295" y="20" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="295" y="20" width="250" height="5" rx="3" fill="#00c853"/>
  <text x="420" y="55" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">02</text>
  <text x="420" y="78" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Citizen Report</text>
  <text x="420" y="96" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Anonymous · 30-second submit</text>
  <text x="420" y="112" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Smart dedup · Live price diff calc</text>
  <text x="420" y="132" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Confirmation flow · Strength animation</text>
  <text x="420" y="152" font-family="monospace" font-size="10" fill="#00c853" text-anchor="middle" font-weight="700">NO ACCOUNT REQUIRED</text>
  <!-- Screen 3 -->
  <rect x="570" y="20" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="570" y="20" width="250" height="5" rx="3" fill="#2196f3"/>
  <text x="695" y="55" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">03</text>
  <text x="695" y="78" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Case Board</text>
  <text x="695" y="96" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Filtered case list · Live countdowns</text>
  <text x="695" y="112" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Authority accountability scorecards</text>
  <text x="695" y="132" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Status pills · Resolution tracking</text>
  <text x="695" y="152" font-family="monospace" font-size="10" fill="#2196f3" text-anchor="middle" font-weight="700">DC RESPONSE: 31%</text>
  <!-- Screen 4 -->
  <rect x="20" y="185" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="20" y="185" width="250" height="5" rx="3" fill="#ff8c42"/>
  <text x="145" y="220" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">04</text>
  <text x="145" y="243" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Case Detail</text>
  <text x="145" y="261" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Evidence timeline · Contributor cards</text>
  <text x="145" y="277" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Blockchain audit trail verification</text>
  <text x="145" y="293" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Live countdown to authority deadline</text>
  <text x="145" y="317" font-family="monospace" font-size="10" fill="#ff8c42" text-anchor="middle" font-weight="700">7 CHAIN ENTRIES</text>
  <!-- Screen 5 -->
  <rect x="295" y="185" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="295" y="185" width="250" height="5" rx="3" fill="#ffd740"/>
  <text x="420" y="220" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">05</text>
  <text x="420" y="243" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Journalist Panel</text>
  <text x="420" y="261" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Signal queue · Sealed verification</text>
  <text x="420" y="277" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Gamified badges · Track 2 publishing</text>
  <text x="420" y="293" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Points · Accuracy · Leaderboard</text>
  <text x="420" y="317" font-family="monospace" font-size="10" fill="#ffd740" text-anchor="middle" font-weight="700">MASTER: 94% ACCURACY</text>
  <!-- Screen 6 -->
  <rect x="570" y="185" width="250" height="140" rx="10" fill="#111318" stroke="#1e2530" stroke-width="1"/>
  <rect x="570" y="185" width="250" height="5" rx="3" fill="#ff1744"/>
  <text x="695" y="220" font-family="monospace" font-size="12" fill="#ff4d1c" text-anchor="middle" font-weight="700">06</text>
  <text x="695" y="243" font-family="Arial,sans-serif" font-size="15" fill="#e8eaf0" text-anchor="middle" font-weight="700">Admin Dashboard</text>
  <text x="695" y="261" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Critical alerts · AI complaint drafter</text>
  <text x="695" y="277" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Formal complaint filing modal</text>
  <text x="695" y="293" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Weekly digest · Partner management</text>
  <text x="695" y="317" font-family="monospace" font-size="10" fill="#ff1744" text-anchor="middle" font-weight="700">AI CONFIDENCE: 91%</text>
</svg>
</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- MARKET DATA -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 💰 Live Market Data

> Mock data for Balangir District — real prices, real pain.

| | Commodity | Official MRP | Black Market | Deviation | Status |
|:---|:---|---:|---:|:---:|:---|
| 🔥 | **LPG Cylinder (14.2kg)** | ₹939 | ₹2,500 | **+166%** | 🔴 Critical |
| 🫘 | **Toor Dal (1kg)** | ₹155 | ₹220 | **+42%** | 🟠 High |
| 🧅 | **Onion (1kg)** | ₹40 | ₹65 | **+63%** | 🟠 High |
| 🫙 | **Mustard Oil (1L)** | ₹145 | ₹210 | **+45%** | 🟠 High |
| 🍚 | **Sugar (1kg)** | ₹42 | ₹58 | **+38%** | 🟡 Watch |
| 🌾 | **Wheat Atta (1kg)** | ₹35 | ₹36 | +3% | 🟢 Safe |
| 🌾 | **Rice (1kg)** | ₹38 | ₹38 | 0% | 🟢 Safe |
| ⛽ | **Petrol (1L)** | ₹105 | ₹105 | 0% | 🟢 Safe |

### Hotspot Areas — Balangir District

| Area | Active Signals | Threat Level |
|:---|:---:|:---|
| Gandhi Chowk | **18** | 🔴 **Critical** |
| Bus Stand Area | **14** | 🟠 **High** |
| Cantonment Road | **11** | 🟠 **High** |
| Court Road | 7 | 🟡 Medium |
| Titilagarh Road | 6 | 🟡 Medium |
| Sargipali | 2 | 🟢 Low |
| Bibhutipara | 1 | 🟢 Low |
| Nehru Nagar | 1 | 🟢 Low |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- IDEATION JOURNEY -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 💡 Ideation Journey

> From personal pain to civic platform — every phase solved a real problem discovered in the previous one.

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="840" height="440" viewBox="0 0 840 440">
  <rect width="840" height="440" fill="#0a0c0f" rx="14"/>
  <text x="420" y="28" font-family="Arial,sans-serif" font-size="13" fill="#e8eaf0" text-anchor="middle" font-weight="800" letter-spacing="2">FROM PERSONAL PAIN TO CIVIC PLATFORM</text>

  <line x1="80" y1="55" x2="80" y2="420" stroke="#1e2530" stroke-width="3"/>

  <!-- Phase 0 -->
  <circle cx="80" cy="75" r="12" fill="#ff1744" stroke="#ff1744" stroke-width="2"/>
  <text x="80" y="79" font-family="Arial,sans-serif" font-size="9" fill="#fff" text-anchor="middle" font-weight="800">0</text>
  <text x="106" y="70" font-family="monospace" font-size="10" fill="#ff1744" font-weight="700">THE SPARK</text>
  <text x="106" y="86" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0">Paid ₹2,500 for a ₹939 LPG cylinder in Balangir.</text>
  <text x="106" y="100" font-family="Arial,sans-serif" font-size="9" fill="#8892a4">No system to verify, report, or fight back.</text>
  <rect x="580" y="62" width="230" height="44" rx="8" fill="#181c24" stroke="#ff1744" stroke-width="1"/>
  <text x="695" y="80" font-family="monospace" font-size="8" fill="#ff1744" text-anchor="middle" font-weight="700">INSIGHT</text>
  <text x="695" y="96" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">One angry citizen = ignored.</text>

  <!-- Phase 1 -->
  <circle cx="80" cy="145" r="12" fill="#ff8c42" stroke="#ff8c42" stroke-width="2"/>
  <text x="80" y="149" font-family="Arial,sans-serif" font-size="9" fill="#fff" text-anchor="middle" font-weight="800">1</text>
  <text x="106" y="140" font-family="monospace" font-size="10" fill="#ff8c42" font-weight="700">SUPPLYSSENTINEL v0.1</text>
  <text x="106" y="156" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0">Built an LPG-only price tracker. Single commodity, single district.</text>
  <text x="106" y="170" font-family="Arial,sans-serif" font-size="9" fill="#8892a4">Problem: Citizen reports alone are unverifiable.</text>
  <rect x="580" y="132" width="230" height="44" rx="8" fill="#181c24" stroke="#ff8c42" stroke-width="1"/>
  <text x="695" y="150" font-family="monospace" font-size="8" fill="#ff8c42" text-anchor="middle" font-weight="700">PROBLEM FOUND</text>
  <text x="695" y="166" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Reports without verification = noise.</text>

  <!-- Phase 2 -->
  <circle cx="80" cy="218" r="12" fill="#ffd740" stroke="#ffd740" stroke-width="2"/>
  <text x="80" y="222" font-family="Arial,sans-serif" font-size="9" fill="#111" text-anchor="middle" font-weight="800">2</text>
  <text x="106" y="213" font-family="monospace" font-size="10" fill="#ffd740" font-weight="700">VERIFICATION LAYER</text>
  <text x="106" y="229" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0">Added journalist + NGO verification with trust scoring.</text>
  <text x="106" y="243" font-family="Arial,sans-serif" font-size="9" fill="#8892a4">Signal Strength algorithm born: citizens + verifiers = credible evidence.</text>
  <rect x="580" y="205" width="230" height="44" rx="8" fill="#181c24" stroke="#ffd740" stroke-width="1"/>
  <text x="695" y="223" font-family="monospace" font-size="8" fill="#ffd740" text-anchor="middle" font-weight="700">BREAKTHROUGH</text>
  <text x="695" y="239" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Structured evidence > angry emails.</text>

  <!-- Phase 3 -->
  <circle cx="80" cy="292" r="12" fill="#2196f3" stroke="#2196f3" stroke-width="2"/>
  <text x="80" y="296" font-family="Arial,sans-serif" font-size="9" fill="#fff" text-anchor="middle" font-weight="800">3</text>
  <text x="106" y="287" font-family="monospace" font-size="10" fill="#2196f3" font-weight="700">AI + BLOCKCHAIN</text>
  <text x="106" y="303" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0">AI drafts formal legal complaints. Blockchain makes records immutable.</text>
  <text x="106" y="317" font-family="Arial,sans-serif" font-size="9" fill="#8892a4">Authority accountability scores: public, permanent, irrefutable.</text>
  <rect x="580" y="279" width="230" height="44" rx="8" fill="#181c24" stroke="#2196f3" stroke-width="1"/>
  <text x="695" y="297" font-family="monospace" font-size="8" fill="#2196f3" text-anchor="middle" font-weight="700">KEY DECISION</text>
  <text x="695" y="313" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Accountability, not confrontation.</text>

  <!-- Phase 4 -->
  <circle cx="80" cy="365" r="12" fill="#00c853" stroke="#00c853" stroke-width="2"/>
  <text x="80" y="369" font-family="Arial,sans-serif" font-size="9" fill="#fff" text-anchor="middle" font-weight="800">4</text>
  <text x="106" y="360" font-family="monospace" font-size="10" fill="#00c853" font-weight="700">CIVIC INTELLIGENCE NETWORK (NOW)</text>
  <text x="106" y="376" font-family="Arial,sans-serif" font-size="11" fill="#e8eaf0">Multi-commodity, multi-area. 8 commodities. 8 areas. Odia support.</text>
  <text x="106" y="390" font-family="Arial,sans-serif" font-size="9" fill="#8892a4">Full 6-screen interactive prototype. Open source. Ready for contributors.</text>
  <rect x="580" y="352" width="230" height="44" rx="8" fill="#181c24" stroke="#00c853" stroke-width="1"/>
  <text x="695" y="370" font-family="monospace" font-size="8" fill="#00c853" text-anchor="middle" font-weight="700">STATUS</text>
  <text x="695" y="386" font-family="Arial,sans-serif" font-size="9" fill="#8892a4" text-anchor="middle">Prototype live on GitHub Pages.</text>

  <!-- Bottom -->
  <rect x="120" y="410" width="600" height="20" rx="6" fill="#111318"/>
  <text x="420" y="424" font-family="monospace" font-size="8" fill="#ff4d1c" text-anchor="middle">SupplySentinel → Verification Layer → AI + Blockchain → Civic Intelligence Network</text>
</svg>
</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ROADMAP -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🗺 Future Vision &amp; Roadmap

> Every milestone is an opportunity to contribute. We're building in public.

| Phase | Timeline | Status | What's Being Built |
|:---|:---|:---:|:---|
| **Prototype** | Q2 2026 | ✅ Done | Single-file app, 6 screens, all interactions, mock data |
| **Backend** | Q3 2026 | 🟡 Next | Node.js API, PostgreSQL, real price APIs, WhatsApp/SMS reporting |
| **AI/ML** | Q4 2026 | ⬜ Planned | GPT/Claude complaint drafting, anomaly detection, rumor NLP |
| **Multi-District** | Q1 2027 | ⬜ Vision | All 30 Odisha districts, 100+ journalists, state-level dashboard |
| **National** | Q2 2027+ | ⬜ Vision | Open-source template for any district in India |

### What Each Phase Needs

| Phase | Skills Needed |
|:---|:---|
| **Backend** | Node.js / Python · PostgreSQL · REST APIs · Twilio · Blockchain (Polygon/Solana) |
| **AI/ML** | Claude API · Anomaly detection · NLP · Supply chain prediction |
| **Expansion** | District coordinators · Journalist partnerships · Policy advisors |
| **National** | Localization (Hindi, Telugu, Bengali) · Government relations · Funding |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- QUICK START -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Quick Start

```bash
# Clone
git clone https://github.com/Ab-aswini/civic-intelligence-network.git
cd civic-intelligence-network

# Open directly — no build step, no npm, no dependencies
open index.html            # macOS
start index.html           # Windows
xdg-open index.html        # Linux

# Or use any static server
npx serve .
python -m http.server 8000
```

### Project Structure

```
civic-intelligence-network/
├── index.html            ← Complete app (all 6 screens, single file)
├── architecture.html     ← Interactive architecture diagrams
├── README.md             ← This file
├── LICENSE               ← MIT License
└── .claude/
    └── launch.json       ← Dev server config
```

### Tech Stack

```
Pure HTML5 + CSS3 + Vanilla JavaScript (ES6+)
No frameworks · No build step · No npm · Zero dependencies
Google Fonts CDN (Syne, IBM Plex Sans, Space Mono)
Hosted on GitHub Pages
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- CONTRIBUTING -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🤝 How to Contribute

We welcome contributors at every skill level. Pick what matches you:

| Role | What You'd Work On | Skills |
|:---|:---|:---|
| **Frontend** | UI/UX polish, animations, mobile, accessibility, PWA | HTML · CSS · JS |
| **Backend** | REST API, database, real price API integration | Node.js · Python · PostgreSQL |
| **AI/ML** | Anomaly detection, complaint drafting, rumor NLP | Python · Claude API · TensorFlow |
| **Blockchain** | On-chain audit logging, verification | Solidity · Polygon · Solana |
| **Domain** | Legal (ECA 1955), gov filing, supply chain economics | Policy · Law |
| **Localization** | Odia, Hindi, Telugu, Bengali translations | i18n · Linguistics |
| **Community** | Bug reports, testing, outreach, journalist connections | Advocacy |

### Steps

```bash
# 1. Fork → 2. Clone → 3. Branch → 4. Code → 5. PR
git checkout -b feature/your-feature
# Make changes — test by opening index.html in browser
git commit -m "feat: description of change"
git push origin feature/your-feature
# Open a Pull Request on GitHub
```

### Rules

1. **Issues first** — open or claim an issue before starting
2. **Small PRs** — one feature/fix per PR
3. **No frameworks** — prototype stays as a single HTML file
4. **Test locally** — all 6 screens must work
5. **Odia support** — include `data-or` translations for new text

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- SECURITY & PRIVACY -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🔒 Security &amp; Privacy

| Principle | Implementation |
|:---|:---|
| **Anonymous by default** | No login, no account, no tracking. Citizens can never be identified. |
| **Sealed verification** | Journalists verify independently — they cannot see each other's notes. |
| **Blockchain immutability** | Every entry is cryptographically chained. Tampering breaks the chain. |
| **Public accountability** | Authority response rates are permanent public records. |
| **No PII stored** | Signals contain commodity + area + price only. No personal data. |
| **Open source** | All code is public. No hidden data collection. MIT licensed. |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- 5 MINUTE DEMO -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🎬 5-Minute Demo Flow

```
MIN 1  │  Dashboard     →  38/100 MFI · Crisis banner · "FALSE" rumor card
       │                   "This is what a citizen in Balangir sees right now."
       │
MIN 2  │  Submit Report →  Gandhi Chowk + LPG → Dedup fires → YES → 89→92
       │                   "30 seconds. No account. The case got stronger."
       │
MIN 3  │  Case Detail   →  Evidence timeline → [Verify Integrity] → hashes ✓
       │                   "47 citizens. 2 journalists. 1 NGO. Tamper-proof."
       │
MIN 4  │  Admin Panel   →  [Review & File] → Complaint letter → [Authorize]
       │                   "1 structured report. Not 47 separate complaints."
       │
MIN 5  │  Case Board    →  DC Balangir: 31% response rate scorecard
       │                   "Permanent. Public. Irrefutable. This is accountability."
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- LICENSE -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📜 License

**MIT License** — Copyright 2026 Aswini Behera

Free to use, modify, and distribute. See [LICENSE](./LICENSE) for full text.

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- FOOTER -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<br/>

**Built by [Aswini Behera](https://github.com/Ab-aswini)** · Balangir, Odisha, India · [aswinibehera666@gmail.com](mailto:aswinibehera666@gmail.com)

<sub>

[GitHub](https://github.com/Ab-aswini/civic-intelligence-network) · [Live Demo](https://ab-aswini.github.io/civic-intelligence-network) · [Architecture](https://ab-aswini.github.io/civic-intelligence-network/architecture.html) · MIT License

</sub>

<br/>

<sub>Built for Balangir, Odisha. Designed for the world. Open source forever.</sub>

<sub>Because citizens are paying ₹2,500 for a ₹939 LPG cylinder right now.</sub>

</div>
