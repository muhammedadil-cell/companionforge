# CompanionForge

Turn any organisation's documents into a ready-to-use AI companion.

## Problem
Colleges and small businesses answer the same questions again and again (fees, dates, timings). Building a chatbot normally needs a developer. CompanionForge lets a non-technical person create one in a minute.

## How it works
1. Add the organisation name and paste or upload its FAQs/documents.
2. Choose the companion's name, tone and language (English, Malayalam or Manglish).
3. The app builds a system prompt from the knowledge and persona.
4. The AI model answers only from that knowledge, and says so when it does not know.

## AI tools used
- **Claude**: designed and built the app (code, prompt design, UI).
- **Groq (Llama) or Gemini API**: power the companion's answers and the suggested starter questions. The provider can be switched in the app.

## Run it
Open `index.html` in a browser, choose a provider, paste its API key, press **Load sample**, then **Forge companion**.
The key stays in your browser and is never stored in this repository.

## Next steps
PDF upload, multi-document knowledge bases, voice, and an embeddable chat widget for websites.
