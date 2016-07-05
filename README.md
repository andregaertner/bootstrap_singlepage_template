# Bootstrap SinglePage

<strong>Eingesetze Technologie</strong>

Yoemen
Bower
Gulp
Bootstrap

<strong>Scaffolding</strong>

Ein Einsatz von Scaffolding Yeoman eignet sehr gut, um Projekte schnell erstellen zu können. Der Vorteil dieser Technologie ist das innerhalb von Sekunden eine Arbeitsumgebung geschaffen wird (Ordner- und Dateienstruktur).

----------------------

<strong>Taskrunner</strong>

Taskrunner  sind Programme, die Ihre Arbeit im Hintergrund verrichten und dass automatisieren von Prozessen ermöglichen. Gulp und Grunt sind beispielsweise Taskrunner mit denen man Prozesse auf der Konsole absetzen kann, um bestimmte Arbeiten zu verrichten. Dazu gehören Prozesse wie Assemblierung, Minifizierung, Automatisierung und Kompilierung.  Beispielweise lassen sich SASS-Dateien kompilieren, Veränderungen an Dateien überwachen und Browser aktualisieren.

----------------------

<strong>PackageManager</strong>

PackageManager sind Programme, die Abhängigkeiten von Komponenten verwalten. NPM und Bower sind beispielweise PackageManager. Ihre Aufgabe ist es Abhängigkeiten zu verwalten und die richtigen Versionen der Packete zu installieren.


----------------------

## Dateienstruktur

```
bootstrap/
├── App/
│   ├── fonts
│   ├── images
│   ├── scripts
│   │   └── main.js
│   ├── styles
│   │   └── main.scss
│   ├── apple-touch-icon.png
│   ├── index.html
│   └── robots.txt
├── bower_components/
├── └── ...
├── bower.json
├── dist/
├── └── ...
├── gulpfile.js
├── node_modules/
├── └── ...
├── package.json
├── test/
├── ├── index.html
├── └── spec/
│   │   └──test.js
├── js/
│   ├── bootstrap.js  
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```


Im app Ordner finden Sie die Entwicklungsdateien.  

#Projekt installieren

<strong>Schritt 1</strong>

Downloaden Sie das Repository.

<strong>Schritt 2</strong>

Entpacken Sie das Projekt

<strong>Schritt 3</strong>

Gehen Sie in das Verzeichnis im Terminal.

cd path

<strong>Schritt 4</strong>


Sie müssen NodeJS, NPM, Bower und Gulp installiert haben.

[NodeJS](https://nodejs.org/en/),
[NPM](https://www.npmjs.com/),
[Bower](https://bower.io/  oder https://github.com/bower/bower),
[Gulp](https://github.com/gulpjs/gulp),

Führen Sie nun in dem gleichen Verzeichnis über die Konsole <strong>npm install</strong> aus. Danach müssen Sie noch die Abhängigkeiten für Bower ausführen über <strong>bower install</strong>.  

<strong>Schritt 5</strong>

Nun müsste die Arbeitsumgebung eingerichtet sein. Die Verzeichnisse node_modules und bower_components sollten nun im Verzeichnis erscheinen.

<strong>Schritt 6</strong>

Wenn Sie nun npm start im Terminal ausführen sollte die App starten.

Über den Port 9000 ist die Website erreichbar.

http://localhost:9000/


# License

license (MIT)
