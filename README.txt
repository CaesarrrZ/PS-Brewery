PS BREWERY – GITHUB PAGES INSTALLATION

1. Auf github.com anmelden und ein neues PUBLIC Repository erstellen, z.B. ps-brewery.
2. Auf „Add file“ → „Upload files“ gehen und ALLE Dateien aus diesem Paket (nicht die ZIP-Datei) direkt in das Stammverzeichnis des Repositorys hochladen. Änderungen mit „Commit changes“ speichern.
3. Repository → Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → Folder: /(root) → Save.
4. Die GitHub-Pages-Adresse öffnen: https://DEIN-BENUTZERNAME.github.io/ps-brewery/
5. Auf dem iPhone in Safari öffnen → Teilen → Zum Home-Bildschirm → falls angeboten „Als Web-App öffnen“ aktivieren → Hinzufügen.
6. Die installierte App einmal mit Internet starten und vollständig laden lassen. Danach Flugmodus testen.

HINWEISE
- Das Repository und der HTML-Quellcode sind öffentlich. Deine Einstellungen werden lokal auf dem Gerät gespeichert.
- Offline-Funktion nutzt Service Worker; auf GitHub Pages funktioniert dies über HTTPS.
- iOS kann Offline-Daten löschen, z.B. bei Speichermangel. Ein dauerhaft garantiertes Offline-Archiv ist das nicht.
- Updates: Dateien erneut hochladen. Bei Änderung von index.html die CACHE-Version in sw.js (z.B. ps-brewery-v2) erhöhen, damit das Update geladen wird.
- Die Dateien müssen alle im gleichen Verzeichnis liegen. Nicht nur index.html hochladen.
