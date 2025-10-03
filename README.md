# TS Video Host (GitHub Pages)

Diese Vorlage hostet eine `.ts`-Videodatei auf GitHub Pages mit korrektem MIME-Type (`video/mp2t`) und Loop-Wiedergabe.

## Schritte

1. **Repository erstellen** (öffentlich).
2. Diese Dateien hochladen:
   - `index.html`
   - `.gitattributes`
   - **Dein Video** als `abgelaufen.ts` (gleiches Verzeichnis).
3. **GitHub Pages aktivieren**:  
   Repo → **Settings** → **Pages** → Branch: `main`, Folder: `/ (root)` → Save.
4. Die veröffentlichte URL öffnen (z. B. `https://DEINNAME.github.io/REPO/`).  
   Das Video wird im Loop abgespielt.

### Hinweis zu Ton/Autoplay
Browser blockieren Autoplay **mit** Ton. Das Video startet stumm oder benötigt einen Klick/Tap, um den Ton zu aktivieren. Auf Receivern/TVs gilt die Einschränkung in der Regel nicht.

## Dateiname anpassen
Wenn deine Datei anders heißt, ändere in `index.html` den `src`-Wert entsprechend.

