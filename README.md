# Die Rationale - Website

Dies ist der Quellcode für die offizielle Website der politischen Partei "Die Rationale". Die Website wird mit Jekyll erstellt und auf GitHub Pages gehostet.

## Lokale Entwicklung

Um die Website lokal zu entwickeln, benötigen Sie Jekyll. Installation und Start:

1. Stellen Sie sicher, dass Ruby installiert ist (Version 2.5.0 oder höher empfohlen)
2. Installieren Sie Jekyll und Bundler:
   ```
   gem install jekyll bundler
   ```
3. Klonen Sie dieses Repository:
   ```
   git clone https://github.com/[username]/dierationale.github.io.git
   cd dierationale.github.io
   ```
4. Installieren Sie die Abhängigkeiten:
   ```
   bundle install
   ```
5. Starten Sie den lokalen Entwicklungsserver:
   ```
   bundle exec jekyll serve
   ```
6. Öffnen Sie http://localhost:4000 in Ihrem Browser

## Struktur

- `_config.yml`: Konfigurationsdatei für Jekyll
- `index.md`: Startseite
- `ueber-uns.md`: Über uns Seite
- `positionen.md`: Unsere politischen Positionen
- `kontakt.md`: Kontaktinformationen
- `assets/css/style.scss`: Hauptstylesheet

## Beitragen

Wenn Sie zur Website beitragen möchten, erstellen Sie bitte einen Pull Request.

## Lizenz

Der Inhalt dieser Website steht unter [LICENSE NAME] Lizenz.
