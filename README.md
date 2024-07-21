# Pico-Theme-Teaser-Matrix

Dieses Pico Theme ist stark Grafiklastig und stellt die Teaser-Grafiken der Beiträge stärker in den Mittelpunkt der Webseite. Das ist besonders dann sehr nützlich, wenn es nur wenig Text gibt.

![](https://repository-images.githubusercontent.com/831736141/644a6a1c-b521-4073-af5a-40b64c2d25eb)

## Zusätzliche Attribute

Für das Theme können zusätzliche Einstellungen in der Theme-Datei `pico-theme.yml` vorgenommen werden, etwa so:

    social:
        instagram:   https://instagram.com/...
        youtube:     https://youtube.com/...
        mail:        Kontakt@...
        facebook:    ...
        twitch:      ...
        twitter:     ...
        link:        http://xyz.de
        github:      https://github.com/...

    global_author:   Redaktion CMSWorkbench

    logo:
        overlay:     blende-3.png
        weights:     [8,4, 3,6,3, 3,3,6, 5,4,3, 6,6, 3,3,3,3, 3,4,5, ...
        position:    ['center','center','center','center','center', ...

## Logo

Die Einstellungen zu `logo` besitzen ein transparentes `overlay`-Bild, damit Text auf hellen Hintergrundbildern besser lesbar wird. Mit `weights` kann die Gewichtung von 1 bis 12 angepasst werden (Bootstrap Aufteilung). Das Attribut `position` legt in CSS-Notation fest, an welcher Seite des Containers das Beitragsbild ausgerichtet sein soll (center, left, top,...).

## Social

Die Angaben der Social-Bar mit Icon