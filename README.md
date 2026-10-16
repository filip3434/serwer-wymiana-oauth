# Serwer Wymiana — strona informacyjna OAuth

Publiczna statyczna strona informacyjna aplikacji OAuth Google Drive używanej do prywatnej wymiany plików przez rclone.

## Zawartość

- `index.html` — publiczna strona aplikacji
- `privacy.html` — polityka prywatności
- `style.css` — arkusz stylów
- `.nojekyll` — statyczny hosting bez generatora Jekyll

Docelowy adres: `https://oauth.strex.top/` (wymaga skonfigurowania DNS w OVH i powiązania z GitHub Pages).

Projekt nie zawiera tokenów OAuth, sekretów ani lokalnej konfiguracji Serwera. To wyłącznie statyczna strona informacyjna, bez wykonywania transferów.
