# Lebenslauf – David Rybinski

Passwortgeschützte Online-Version meines Lebenslaufs (GitHub Pages).

Die lesbare Quelle (`src/cv.html`) liegt **nicht** im Repo. Veröffentlicht wird nur die verschlüsselte `index.html`
(AES-256-GCM, Schlüssel per PBKDF2-SHA256 aus dem Passwort, Entschlüsselung im Browser).

```bash
CV_PASSWORD='…' node tools/encrypt.mjs src/cv.html index.html
```
