# 🎄 AsperAstra Christmas Hackathon 2025 - AI Mentor Template

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

## 📄 Licenza

MIT - Usa, modifica e condividi liberamente!

---

Made with ❤️ per il Christmas Hackathon AsperAstra 2025
