# From Web Sites to Web Applications: The change of the Internet

```
Hochschule der Medien
Fakultät Druck und Medien
Anleitung zum wissenschaftlichen Arbeiten
Leitung: Prof. Dr. Joachim Charzinski
Sommersemester 2016
```

Webseiten wurden über die letzten Jahrzehnte hinweg immer dynamischer und interaktiver. Auch die tatsächliche Funktionalität wuchs. So steht die Web Applikation Google Mail mittlerweile regulären Desktop E-Mail-Clients funktional in nichts mehr nach. Kollaboratives Schreiben von Texten ist mittlerweile genauso möglich, wie das Erstellen von Grafiken, Bearbeiten von Fotos und Audio-Dateien. In dieser Arbeit soll der Entwicklungsverlauf, von den ersten statischen Webseiten, zu dem was man heute Web App nennt nachgezeichnet werden.

## Begriffsklärung
Der Begriff „Web-Applikation“ oder kurz „Web-App“ selbst besitzt kaum Trennschärfe und findet sich daher schon seit den ersten skriptgenerierten Webseiten im regulären Sprachgebrauch wieder. Würde diese Arbeit den Begriff ebenfalls so weit fassen, würde sie der aktuellen Entwicklung zu kurz greifen. In diesem Aufsatz wird dieser Begriff als Analogon zu regulären grafikbasierten Computerprogrammen beziehungsweise vielmehr Handy-Apps verstanden.

## Von einfachen Dateien zu Back-End-lastigen Webseiten
Die erste Webseite in der Geschichte des Internets entstand 1990 und wurde von Tim Berners- Lee am CERN in der Schweiz erstellt ([CERN 2016-1](http://home.cern/topics/birth-web)). Über die nächsten Jahre wuchs die Zahl der Server in die Zehntausende ([CERN 2016-2](http://timeline.web.cern.ch/timelines/The-birth-of-the-World-Wide-Web/overlay#1993-04-29%2023:00:00)), die Webseiten blieben aber zunächst eine Ansammlung statischer, für den Konsumenten rein lesbarer Inhalte ([Berners-Lee 1996](https://www.w3.org/People/Berners-Lee/1996/ppf.html)).

### Back-End Skriptsprachen und Datenbanken
Größer werdende Datenmengen machten den Einsatz von Datenbanksystemen und serverseitigen Skripting-Sprachen erforderlich. Im Jahr 1994 wurden sowohl die Sprache PHP ([The PHP Group 2016](http://php.net/manual/en/history.php.php)) als auch die relationale Datenbank MySQL ([opensourcereleasefeed.com, 2009](https://web.archive.org/web/20090313160628/http://www.opensourcereleasefeed.com/interview/show/five-questions-with-michael-widenius-founder-and-original-developer-of-mysql)) entwickelt. Nach ihren Veröffentlichungen, wurde die Kombination zusammen mit weiteren Web-Server-Komponenten unter der Bezeichnung LAMP-Stack (Akronym für: Linux, Apache, MySQL, PHP) populär. Mit ein Grund für den schnellen Popularitätszuwachs war die Tatsache, dass die einzelnen Komponenten als lizenzkostenfreie Open-Source-Software verfügbar waren ([Tsiopanos 2015](https://www.annatech.com/blog/editorials/a-short-unofficial-history-of-the-lamp-stack.html))([Eghbal 2016](https://medium.com/@nayafia/we-re-in-a-brave-new-post-open-source-world-56ef46d152a3#.50om8gol3)).
Der grundlegende Unterschied zur bisherigen Entwicklung bestand darin, dass Websites nicht mehr nur eine Ansammlung statischer HTML-Seiten, sondern dynamisch generierte Zusammenstellungen von Inhalten waren ([Holovaty u.a. 2009: xxxv](https://books.google.de/books?id=Gpr7J7-FFmwC&lpg=PR2&ots=_vXIjoNIRC&dq=Holovaty%2C%20Adrian%2FKaplan-Moss%2C%20Jacob%202009%3A%20The%20Definitive%20Guide%20to%20Django%3A%20Web%20Development%20Done%20Right.%20New%20York%3A%20Springer-Verlag&pg=PR35#v=onepage&q=Holovaty,%20Adrian/Kaplan-Moss,%20Jacob%202009:%20The%20Definitive%20Guide%20to%20Django:%20Web%20Development%20Done%20Right.%20New%20York:%20Springer-Verlag&f=false)).
Auf dieser Grundlage konnten die ersten Content-Management-Systeme, Internet-Foren und Blogs entwickelt werden.

## Der Trend hin zum komplexeren Front-End
Das Generieren von Inhalten auf dem Server (zum Beispiel über PHP) findet seine Grenzen, vor allem bei dynamischen und animierten Inhalten wie Spielen sehr schnell. Auch die Validierung einzelner Felder in Formularen legt eine Verarbeitung direkt auf dem Client nahe, um unnötige Roundtrips zu vermeiden.

### Die Relevanz von Plug-ins
Grosse Popularität erlange das 1996 veröffentliche Flash ([Richter 2016](https://www.statista.com/chart/3796/websites-using-flash/)). Damit war es möglich Raster-, Vektorgrafiken und Videoclips im Browser darzustellen. 2005 startete der Video-Streaming-Dienst Youtube unter Einsatz von Flash ([Rocheleau 2012](https://speckyboy.com/a-history-lesson-on-the-rise-and-fall-of-adobe-flash/)). Weitere Plugins am Markt waren unter anderem Java applets und Silverlight. Obgleich zum Teil heute noch im Einsatz, wurden auch diese Plugins in ihrer Weiterentwicklung eingestellt ([Hoffman 2014](http://www.howtogeek.com/179213/why-browser-plug-ins-are-going-away-and-whats-replacing-them/)).

### Der Ausbau von HTML, CSS und JavaScript
Im Jahr 2014 erfolge der erste Release von HTML5 ([Bright 2014](http://arstechnica.com/information-technology/2014/10/html5-specification-finalized-squabbling-over-who-writes-the-specs-continues/)). Auch CSS und JavaScript wurden bis zu diesem Zeitpunkt in ihrer Funktionalität weiter entwickelt. HTML5 und CSS3 standardisierten viele der Funktionen, die Entwickler entweder eigens programmieren mussten, oder bisher nur als Wunsch äußern konnten (so z.B. der Zugriff auf GPS-Daten des Computers/Handys oder die Umsetzung von Bewegungsanimationen).

Folgende für die weitere Darstellung wichtige Neuerungen brachte HTML5:
- Möglichkeiten zur grafische Ausgestaltung von Seitenelementen wurden ausgebaut ([Anthes, 2012](http://cacm.acm.org/magazines/2012/7/151236-html5-leads-a-web-revolution/fulltext)). HTML5 bietet seither native Möglichkeiten 2D und 3D Grafiken sowie multimediale Inhalte zu gestalten ([Google Inc. 2012-1](https://www.html5rocks.com/en/features/graphics)).
- Möglichkeiten zum Speichern größerer Datenmengen im Browser kamen hinzu ([Google Inc. 2012-2](https://www.html5rocks.com/en/features/storage)).
- Die Kommunikationsmöglichkeiten zwischen Server und Browser wurden verbessert ([Pfleiderer 2011: 21](http://blog.roothausen.de/uploads/documents/sven_pfleiderer-scale_the_realtime_web.pdf)).
- Möglichkeiten für Background-Threads und Offline-Nutzbarkeit wurden geschaffen ([Mozilla Developer Network 2015](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API)).

### JavaScript: architekturelle Verbesserungen
Um mit der zunehmenden Komplexität von JavaScript Programmen besser umgehen zu können wurden verschiedene Frameworks und architekturelle Konzepte entwickelt. Mit AngularJS setzte sich Google das Ziel, die Codebasis neuer Projekte zu verkleinern und die Entwicklungsgeschwindigkeit zu steigern ([Green u.a. 2013: vii](https://books.google.de/books?id=eNExy_X1YYcC&lpg=PR2&ots=wz6dH1LaU4&dq=AngularJS.%20Sebastopol%3A%20O%20%CC%81Reilly%20Media%2C%20Inc.&pg=PR7#v=onepage&q=AngularJS.%20Sebastopol:%20O%20%CC%81Reilly%20Media,%20Inc.&f=false)). Facebooks Flux sollte dabei helfen inkonsistente Zustände innerhalb von Webseiten zu verhindern ([Fisher u.a. 2014](https://facebook.github.io/react/blog/2014/05/06/flux.html)).

## Progressive Web-Apps
Laut Ergebnissen von Google zeichnen sich native Apps für Produzenten im Vergleich zu Webseiten vor allem dadurch aus, dass sie sowohl im Hintergrund laufen als auch dem Nutzer Benachrichtigungen senden können und nach Installation auf dem Home-Screen erscheinen ([Google Inc. 2015: 7m35s](https://www.youtube.com/watch?v=MyQ8mtR9WxI&feature=youtu.be)). Wie bereits beschrieben, sind viele dieser Eigenschaften bereits in der HTML5-Plattform als Möglichkeit angelegt.  
Ab 2014 verbrachten die Verbrauchen in den USA statistisch gesehen mehr ihrer täglichen Medienzeit am Handy als am Computer ([comScore Inc. 2014: 2](https://www.comscore.com/Insights/Presentations-and-Whitepapers/2014/The-US-Mobile-App-Report)). Dennoch wurden im Durchschnitt nur drei Apps pro Monat installiert und das bei einer großen Konzentration der Installationshäufigkeit bei einem kleinen Teil der Nutzer ([comScore Inc. 2014: 6](https://www.comscore.com/Insights/Presentations-and-Whitepapers/2014/The-US-Mobile-App-Report)). Es sprechen daher mittlerweile auch ökonomische Gründe dafür, die System-Integration von Web-Apps zu verbessern ([Google Inc. 2015: 4m30s](https://www.youtube.com/watch?v=MyQ8mtR9WxI&feature=youtu.be)).

## Schluss
Über einen Zeitraum von bald 30 Jahren entwickelten sich Webseiten von statischen, verlinkten Dokumenten zu Applikationen, die regulären nativen Apps nur noch in wenig nachstehen. Ein Trend, begründet in technischen wie ökonomischen Aspekten auch die letzten Unterschiede zu überwinden ist klar erkennbar.
