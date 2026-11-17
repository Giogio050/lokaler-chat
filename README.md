# Lokaler Chat

Eine einzelne HTML-Datei, die im Browser mit abliterierten Sprachmodellen chattet.

**Am iPhone diesen Link in Safari oder Chrome öffnen** (nicht über die Datei-App):

https://htmlpreview.github.io/?https://raw.githubusercontent.com/Giogio050/lokaler-chat/main/index.html

Die Datei-App / Quick Look führt JavaScript oft gar nicht aus.

- **Server-Modus (Standard):** spricht kostenlose Hugging-Face-Spaces über die Gradio-REST/SSE-API an. Kein Konto, keine ES-Module, funktioniert auch als lokale Datei in einem Desktop-Browser.
- **Im Browser:** optionales WebGPU-Modell (Transformers.js), eher für den Desktop.
- **Eigene API:** OpenAI-kompatibler Endpunkt, Schlüssel trägst du selbst ein.

Quelle: [index.html](index.html) im gleichen Repo.
