# Lokaler Chat

Eine einzelne HTML-Datei, die im Browser mit abliterierten Sprachmodellen chattet.

- **Server-Modus (Standard):** spricht kostenlose Hugging-Face-Spaces über die Gradio-REST/SSE-API an. Kein Konto, keine ES-Module, funktioniert auch, wenn du die Datei lokal öffnest.
- **Im Browser:** optionales WebGPU-Modell (Transformers.js), eher für den Desktop.
- **Eigene API:** OpenAI-kompatibler Endpunkt, Schlüssel trägst du selbst ein.

## Nutzen

Am einfachsten über diesen Link (nach dem ersten Commit, jsDelivr kann ein paar Minuten brauchen):

- GitHub: https://github.com/Giogio050/lokaler-chat
- Datei direkt: öffne `index.html` in Chrome oder Safari.

Am iPhone die Datei-App / Quick Look oft **kein** JavaScript aus. Dann den https-Link in Safari oder Chrome öffnen, nicht die heruntergeladene Datei.
