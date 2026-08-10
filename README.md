# wettergeschichtebilder

Bildablage für [wettergeschichte](https://github.com/volkerreichenberger/wettergeschichte).

Die Instagram-API lädt keine Dateien hoch, sondern holt sie von einer
öffentlich erreichbaren URL. Dieses Repository dient genau dazu: `post_daily.sh`
legt das fertige JPEG hier ab, pusht, und übergibt Instagram die GitHub-Pages-URL

    https://volkerreichenberger.github.io/wettergeschichtebilder/<dateiname>.jpg

Die Bilder werden von `post_daily.sh` erzeugt, nicht von Hand.
