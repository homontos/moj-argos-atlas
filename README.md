# 🗺️ Custom ArgosAtlas - Panel OSINT

Automatyczny system wizualizacji danych geopolitycznych oraz ruchu morskiego działający całkowicie bezpłatnie na platformie **GitHub Pages** i **GitHub Actions**.

## 🛰️ Jak działa system?
1. **GitHub Actions** uruchamia wbudowanego bota w Pythonie co 2 godziny.
2. Skrypt `scraper.py` pobiera aktualne lokalizacje kryzysowe i pozycje statków.
3. Dane są zapisywane do pliku `dane_osint.json`.
4. Strona `index.html` automatycznie odświeża widok mapy dla każdego odwiedzającego.
