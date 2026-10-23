Solitär als App (PWA)

1. Den ganzen Ordner auf einen Webspace mit HTTPS legen (z. B. Netlify Drop,
   GitHub Pages oder der eigene Server). Wichtig: index.html, manifest.webmanifest,
   sw.js und beide Icons müssen im selben Ordner liegen.
2. Die Adresse auf dem Android-Handy in Chrome öffnen.
3. Menü (drei Punkte) > "App installieren" oder "Zum Startbildschirm hinzufügen".

Danach startet das Spiel wie eine App im Vollbild und läuft auch offline.
Der Spielstand liegt nur auf dem jeweiligen Gerät.

Nach Änderungen an index.html in sw.js die Zahl in CACHE ('solitaer-v1') erhöhen,
damit Handys die neue Version laden.
