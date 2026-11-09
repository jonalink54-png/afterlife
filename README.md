# AFTERLIFE

Ein Life-Simulator im Browser mit Arcade, Stadt, Chat, Bank, Immobilien und mehr.
Reine Web-App (kein Build nötig), installierbar als PWA.

## Dateien (alle im Hauptordner)
- `index.html` – das komplette Spiel
- `manifest.json` – App-Name, Farben, Icons
- `service-worker.js` – Offline-Modus
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – App-Icons
- `vercel.json` – Einstellungen für Vercel

## Online stellen (iPad)
1. Auf github.com ein neues Repository anlegen und alle Dateien hochladen (Add file > Upload files).
2. Auf vercel.com mit GitHub anmelden, Add New > Project, Repository wählen.
3. Framework Preset: **Other**. Alles andere leer lassen. Auf **Deploy** tippen.
4. Vercel zeigt dir einen Link wie `afterlife.vercel.app`.

## Auf dem Home-Bildschirm installieren
In **Safari** den Link öffnen > Teilen-Symbol > **Zum Home-Bildschirm** > Hinzufügen.

## Hinweise
- Der Spielstand liegt im Browser des Geräts. Sichere ihn über Profil > Export.
- iPhone und iPad haben getrennte Spielstände (Export/Import nutzen).
- Die Chat-NPCs antworten lokal. Eine echte KI braucht ein Backend (noch nicht enthalten).
