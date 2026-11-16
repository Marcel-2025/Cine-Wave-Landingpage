# CineWave – Premium Landingpage

Responsive, statische Landingpage für das CineWave Video Player & Movie Collection Designkonzept.

## Start

`index.html` im Browser öffnen. Für lokale Pfade, Content Security Policy und Tests besser einen lokalen Server im Verzeichnis starten:

```bash
python -m http.server 8000
```

Danach http://localhost:8000 öffnen. Für GitHub Pages/Vercel das gesamte Verzeichnis hochladen.

## Inhalt

- `index.html` – Landingpage mit Film-Slider, Original-Screenshots, Icons, Geräte-Demo, Themenswitcher, Poster-/Banner-Galerie, Premium und FAQ.
- `css/styles.css` – Farbsystem, 3D-Design, Responsivität, reduzierte Bewegung.
- `js/app.js` – ohne externe Abhängigkeiten: Menü, Filmwechsel, Screenshot-Carousel, Geräte- und Themenswitcher, Bild-Lightbox.
- `assets/` – **alle 36 Bilddateien** aus dem vorherigen CineWave-Designset: 4 Icons in 1024x1024, 4 in 512x512, 9 Android-Screenshots, Desktop + Tablet, 7 Poster, 7 Backdrops, 3 Marketing-Vorschaubilder.
- `datenschutz.html` und `impressum.html` – bearbeitbare **Entwürfe**; Angaben vor Veröffentlichung prüfen und vervollständigen.
- `DESIGNSET_QUELLE.md` – Informationen zum zugrunde liegenden Designset.

## Wichtige Hinweise

- Es sind **Designkonzepte**, keine Screenshots einer fertigen, im Store veröffentlichten App.
- Beispiel-Filmtitel (z. B. *Neon Horizon*) sind fiktiv.
- Keine externen Skripte, Fonts, Analytics, Tracking- oder Video-Einbettungen.
- Kein funktionierender App-Download und keine aktiven Käufe; Call-to-Actions führen daher nur zu internen Abschnitten.
- Die verwendeten Illustrationen sind die im früheren CineWave-Paket bereitgestellten eigenen Demo-Assets.
- App-Demo, Dateiupload, Cloud-Synchronisierung, bezahlte Funktionen und Lizenzfragen müssen bei einem tatsächlichen Produkt separat entwickelt/geprüft werden.

## Deployment-Checkliste

1. Vollständiges Impressum eintragen (Anbieter, ladungsfähige Anschrift, Kontakt).
2. Datenschutz auf verwendeten Hoster, Server-Logs, Löschfristen und ggf. weitere Dienste abstimmen.
3. Falls veröffentlicht, App-Download-Links mit tatsächlich existierenden Store-Seiten ersetzen.
4. Screenshots an die echte implementierte App anpassen, bevor sie als Store-Nachweis genutzt werden.
5. Produktnamen auf Markenverfügbarkeit prüfen.

Stand: 16. November 2026.
