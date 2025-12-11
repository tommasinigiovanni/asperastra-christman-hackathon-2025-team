# 🎄 AsperAstra Christmas Hackathon 2025 - AI Mentor Template

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Gemini CLI](https://img.shields.io/badge/Powered%20by-Gemini%20CLI-4285F4?logo=google&logoColor=white)](https://github.com/google-gemini/gemini-cli)
[![Made with AI](https://img.shields.io/badge/Made%20with-AI%20%E2%9D%A4%EF%B8%8F-ff69b4)](https://evoseed.io)
[![Hackathon](https://img.shields.io/badge/Event-Christmas%20Hackathon%202025-red?logo=christmas-tree)](https://www.eventbrite.it/e/christmas-hackathon-tickets-1963193523677)
[![Location](https://img.shields.io/badge/Location-Trieste%20🇮🇹-green)](https://asperastra.com)

Template per hackathon con **AI Mentor** integrato basato su Gemini CLI. Guida il tuo team dalla formazione dell'idea alla validazione con metodologia Pretotyping.

🔗 **Repository:** https://github.com/tommasinigiovanni/asperastra-christman-hackathon-2025-team

---

## 🚀 Quick Start

### 1. Clona il repository

```bash
git clone https://github.com/tommasinigiovanni/asperastra-christman-hackathon-2025-team.git
cd asperastra-christman-hackathon-2025-team
```

### 2. Installa i prerequisiti

#### Gemini CLI

**macOS:**
```bash
brew install gemini-cli
```

**Windows:**
```bash
choco install gemini-cli
```

**Linux:**
```bash
# Segui le istruzioni su https://github.com/google-gemini/gemini-cli
```

#### Autenticazione Gemini

1. Ottieni una API key da [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Esporta la chiave nel terminale:
```bash
export GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
```

> 📖 Guida completa: [Gemini CLI Authentication](https://github.com/google-gemini/gemini-cli/blob/main/docs/get-started/authentication.md#use-gemini-api-key)

#### MCP Nanobanana (per generazione immagini)

```bash
gemini extensions install https://github.com/gemini-cli-extensions/nanobanana
```

---

## 👥 Configura il tuo Team

Prima di avviare l'AI Mentor, **sostituisci i profili di esempio** con quelli del tuo team reale.

### Struttura file team umano

```
team/human/
├── Giovanni_Tommasini.md   # ← Sostituisci con il tuo profilo
├── Federico_Vitiello.md    # ← Sostituisci con il tuo profilo
├── Emanuele_Ciccone.md     # ← Sostituisci con il tuo profilo
└── Alessandro_Pretz.md     # ← Sostituisci con il tuo profilo
```

### Formato consigliato per ogni profilo

```markdown
# Nome Cognome

## Ruolo
Il tuo ruolo principale (es. Developer, Designer, Product Manager)

## Contatti
- **LinkedIn:** https://linkedin.com/in/tuoprofilo
- **Email:** tua@email.com

## Descrizione
Breve bio professionale (2-3 frasi)

## Aree di Competenza
- Competenza 1
- Competenza 2
- Competenza 3

## Lingue
- Italiano (Madrelingua)
- Inglese (Livello)
```

> 💡 **Tip:** Più dettagli inserisci, meglio l'AI Mentor potrà suggerire ruoli AI complementari!

---

## ▶️ Avvia l'AI Mentor

Una volta configurato il team, avvia Gemini CLI nella cartella del progetto:

```bash
gemini
```

L'AI Mentor leggerà automaticamente il file `GEMINI.md` e inizierà a guidarti attraverso gli step:

1. **Step 1:** Analisi del team e creazione AI Personas
2. **Step 2:** Brainstorming dell'idea (orientato al making/FabLab)
3. **Step 3:** Validazione con Lean Canvas, Pretotipo e XYZ Hypothesis
4. **Step 4:** Kickoff con TO DO LIST
5. **Step 5:** Generazione foto del team

---

## 📁 Struttura del Progetto

```
.
├── GEMINI.md                    # Istruzioni AI Mentor (system prompt)
├── README.md                    # Questo file
├── doc/
│   ├── descrizione-hackathon.md # Descrizione evento
│   ├── regolamento-hackathon.md # Regolamento ufficiale
│   └── evoseed-metodologia.mmd  # Metodologia Evoseed
├── team/
│   ├── human/                   # Profili team umano (da personalizzare)
│   └── ai/                      # Profili AI Personas (generati dall'AI)
├── step-by-step.md              # Progress tracker (generato dall'AI)
└── summary.md                   # Riepilogo finale (generato dall'AI)
```

---

## 📝 File Generati dall'AI

Durante la sessione, l'AI Mentor creerà automaticamente:

| File | Descrizione |
|------|-------------|
| `team/ai/*.md` | Profili delle AI Personas create |
| `step-by-step.md` | Tracker dei progressi step-by-step |
| `summary.md` | Riepilogo finale con TO DO LIST |

---

## 🎯 Filosofia

> *"Pretotipare prima di prototipare. Fatto è meglio che perfetto."*

> *"Usiamo l'AI per l'efficienza, ma l'autenticità deve rimanere umana."*

---

## 👨‍💻 Autore

<a href="https://www.linkedin.com/in/giovannitommasini/">
  <img src="https://img.shields.io/badge/LinkedIn-Giovanni%20Tommasini-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://www.giovannitommasini.it/">
  <img src="https://img.shields.io/badge/Website-giovannitommasini.it-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
</a>
<a href="https://evoseed.io">
  <img src="https://img.shields.io/badge/Company-Evoseed.io-00C853?style=for-the-badge&logo=seedling&logoColor=white" alt="Evoseed">
</a>
<a href="https://instagram.com/tommasini.giovanni">
  <img src="https://img.shields.io/badge/Instagram-giovannitommasini-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
</a>
<a href="https://t.me/tommasinigiovanni">
  <img src="https://img.shields.io/badge/Telegram-giovannitommasini-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
</a>

**Giovanni Tommasini** - Telco & AI DevOps Expert | Mentor & Strategy

> *"Enthusiastic Seeker"* 🔍 - Ottimizzazione processi per MSP e System Integrator attraverso automazione e AI.

---

## 📄 Licenza

MIT - Usa, modifica e condividi liberamente!

---

Made with ❤️ by [Giovanni Tommasini](https://linkedin.com/in/giovannitommasini) per il Christmas Hackathon AsperAstra 2025
