# Projekt-Tagger

Dieses Repository enthält die Dateien für das statische Hosting deines Outlook-Add-ins auf Vercel.

## Dateien

- `taskpane.html`: Formular zur Projektnummerneingabe und JS für n8n-WebHook.
- `vercel.json`: Vercel-Konfiguration für saubere URLs.
- `README.md`: Diese Anleitung.

## Deployment auf Vercel

1. Repository in GitHub anlegen.
2. Dateien hochladen.
3. In Vercel unter "Import Third-Party Git Repository" URL eingeben.
4. Framework auf "Other" setzen und deployen.

Dann erhältst du die URL `https://<dein-projekt>.vercel.app/taskpane.html`, die du im Outlook-Manifest als `SourceLocation` angibst.
