# n8n Suisse Security Report AI Agent

AI agent built with **n8n + Telegram + OpenAI** to generate professional Swiss-style security incident reports in French.

Designed for security agents working in Switzerland (AMIG / Protectas style reporting).

---

## Features

- Telegram voice or text input
- Automatic transcription
- AI report generation
- Strict Swiss-style report structure
- French-only official format
- Anti-hallucination rules
- No information invention

---

## Workflow

Telegram → Transcription → AI Agent → Structured Security Report → Telegram reply

---

## Example Output

Ce jour,

LIEU : CHC – La Praille  
LOCALISATION INTERNE : 2ème étage chambre 14  

PERSONNES CONCERNÉES :  
- Carlos Mendes, né le 12.04.1988, nationalité portugaise  

DESCRIPTION DES FAITS :  
Une altercation a eu lieu entre deux individus.

MESURES PRISES :  
1) Police appelée à 22:10, arrivée à 22:18.  

SITUATION FINALE :  
La situation est revenue au calme. Rapport établi.

---

## Installation

1. Install n8n
2. Import the workflow JSON
3. Configure:
   - Telegram Bot
   - OpenAI API key
4. Activate the workflow

---

## Author

Security automation project built in Switzerland.
