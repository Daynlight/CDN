<div align=center>

# 🐕 CDN 🐕

</div>

Wymagania:
- [ ] Skonfiguruj serwowanie statycznych zasobów tak, aby strona była szybka i stabilna: reverse proxy + poprawne cache’owanie po stronie przeglądarki.
- [ ] Reverse proxy (np. Nginx/Caddy) przed stroną/aplikacją.
- [ ] Osobne traktowanie zasobów statycznych (np. /assets/*) i HTML.
- [ ] Poprawne nagłówki cache: Cache-Control oraz ETag lub Last-Modified (rewalidacja ma mieć sens).
- [ ] Wersjonowanie assetów (np. hash w nazwie pliku lub inny mechanizm, który rozwiązuje problem „starego JS/CSS po deployu”).
- [ ] Kompresja treści tekstowych (gzip i/lub br).

