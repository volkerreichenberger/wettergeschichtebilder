# wettergeschichtebilder

Bildablage für [wettergeschichte](https://github.com/volkerreichenberger/wettergeschichte).

Die Instagram-API lädt keine Dateien hoch, sondern holt sie von einer
öffentlich erreichbaren URL. Dieses Repository dient genau dazu: `post_daily.py`
legt das fertige JPEG hier ab, pusht, und übergibt Instagram die GitHub-Pages-URL

    https://volkerreichenberger.github.io/wettergeschichtebilder/2026/06/14/<dateiname>.jpg

Die Bilder liegen nach Tagen sortiert, `JJJJ/MM/TT`, nach dem Tag des Laufs, der
sie erzeugt hat — ein Verzeichnis enthält also die Bilder eines Tages. Flach
nebeneinander wären es nach einem Jahr rund 1500 Dateien.

Die Bilder werden von `post_daily.py` erzeugt, nicht von Hand.
