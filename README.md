# reels

Ablage für die fertigen Hochkant-Videos des Social Post-Planners.

LinkedIn, Instagram und TikTok holen sich ein Video von einer Adresse ab. Sie
brauchen dafür eine Adresse, die wirklich die Bytes ausliefert — kein
Vorschaufenster, keine Zwischenseite, keine Anmeldung. Genau das macht GitHub
Pages. Google Drive kann es nicht: Drive antwortet bei größeren Dateien mit einer
Virenscanner-Seite, und Instagram scheitert schon an der Weiterleitung.

## Adresse einer Datei

Eine Datei `reel-063-adenosin.mp4` in diesem Repo ist erreichbar unter:

```
https://phoeser.github.io/reels/reel-063-adenosin.mp4
```

Diese Adresse kommt im Studio ins Feld **Video**. Im Sheet landet sie als Vermerk
`video=…` in der Notiz-Spalte, zusammen mit einem optionalen `poster=…` für das
Vorschaubild.

## Namensschema

```
reel-<Nummer>-<Stichwort>.mp4      das Video
reel-<Nummer>-<Stichwort>.jpg      das Vorschaubild, optional
```

Die Nummer ist die ID aus Spalte A des Redaktionsplans. Keine Leerzeichen, keine
Umlaute, keine Großbuchstaben — die Adresse muss ohne Umschreibung funktionieren.

## Format

1080 × 1920, MP4 (H.264 / AAC), 15 bis 45 Sekunden. Untertitel eingebrannt, weil
auf allen drei Kanälen ohne Ton geschaut wird.

## Zwei Dinge, die man wissen muss

**Alles hier ist öffentlich.** Wer die Adresse kennt, kann die Datei abrufen. Das
ist der Zweck — die Plattformen müssen ja herankommen. Rohmaterial, Fehlversuche
und alles Ungeprüfte gehören nicht hierher.

**Git vergisst nichts.** Eine gelöschte Datei ist aus dem aktuellen Stand
verschwunden, bleibt aber im Verlauf liegen. Das Repo wächst deshalb nur. Wenn es
zu groß wird, wird es neu aufgesetzt statt aufgeräumt.
