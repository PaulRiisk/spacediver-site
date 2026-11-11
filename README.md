# Space Diver - Website

Statische Seite fuer GitHub Pages. Zweck: Impressum und Datenschutzerklaerung
unter einer festen URL, plus eine kurze Startseite im Look der itch-Seite.

## Platzhalter ausfuellen

Vor dem Veroeffentlichen in allen drei HTML-Dateien ersetzen:

| Platzhalter | Wo | Wert |
|---|---|---|
| `VORNAME NACHNAME` | impressum, datenschutz | Dein buergerlicher Name |
| `MAIL_HIER` | alle drei | Kontakt-E-Mail |
| `USTID_ODER_ZEILE_LOESCHEN` | impressum | USt-IdNr., sonst den ganzen `dt`/`dd`-Block loeschen |
| `STAND_DATUM` | datenschutz | z.B. November 2026 |
| `STEAM_URL_HIER` | index | Steam-Store-Seite (bis dahin Button loeschen) |

Die Anschrift ist bereits die gemietete Adresse in Dietmannsried.

## Veroeffentlichen

1. Auf GitHub ein neues **oeffentliches** Repo anlegen, z.B. `spacediver-site`.
2. Den Inhalt dieses Ordners hochladen (Web-Upload reicht: "uploading an existing file").
3. Repo > Settings > Pages > Source: **Deploy from a branch**, Branch `main`, Ordner `/ (root)`.
4. Nach ein bis zwei Minuten ist die Seite unter
   `https://<benutzername>.github.io/<repo-name>/` erreichbar.

Das Spiel-Repo bleibt davon unberuehrt und privat.

## Dateien

- `index.html` - Startseite
- `impressum.html` - Impressum nach § 5 DDG
- `datenschutz.html` - Datenschutzerklaerung (GitHub Pages, E-Mail, Feedback-Funktion)
- `style.css` - gemeinsame Gestaltung, Farben aus dem itch-Theme
- `assets/` - Banner, Cover, Hintergrund, drei Screenshots
