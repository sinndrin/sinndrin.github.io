# Website for www.sinndrin.ch

## Bildformate (Masse in Pixel)

* Angebote:
  * 1 Spalte: 803x100
  * 3 Spalten: 248x100

* Hintergrundwissen:
  * 132x264

* Team:
  * 150x150, rund

* Realisierte Projekte:
  * 248x100

* Blog: 800x310

## Bilder mit Gimp bearbeiten

* Bild zuschneiden
  * Im "Werkzeugkasten" auf Skalpel-Symbol (ausschneiden) dann die benötigten Masse (siehe oben) eingeben. Mit gehaltener "SHIFT"-Taste den Bildausschnitt vergrössern und platzieren. Mit Enter bestätigen.

* Bild auf grösse Skalieren
  * Bild anwählen, im Menü unter Bild -> Bild scalieren wählen und gewünschte Masse eingeben

* Bild exportieren
  * Datei -> exportieren als
  * Für Webseite als jpg abspeichern (Qulität min 85%)

## Icons
[Verfügbare Icons](http://zurb.com/playground/foundation-icon-fonts-3)

# Entwicklungsumgebung

## SASS to CSS compiling by foundation

    cd assets/foundation
    grunt

## run jekyll

    jekyll serve --watch

## Inhalte hinzufügen oder entfernen

###Angebot hinzufügen

1. neue Datei anlegen: /angebote/_posts/
2. Menüeintrag hinzufügen: /_includes_aside_angebote.html
3. Wenn Umlaute oder Sonderzeichen im Titel enthalten, replace in breadcrumbs: /_includes/breadcrumbs.html

## Inhaltsvorgaben

###Team Profil

1. 1-2 Satz "byline" aus der 3. Person geschrieben. Z.B. "Maja Müller mag Mais."
2. Auf der Profilseite kann der Text frei aus der 1. Person ausformuliert werden. Z.B. "Ich interessiere mich für Hunde."

###Einleitungsabsatz bei Angebotskategorien (z.B. "Bildung" oder "Energie")

* Was wollen wir anbieten?
* Warum wollen wir das tun? Was ist unsere Motivation dafür?

## Beispiel für Subnavigation mit mehreren Ebenen

    {% if location[1] == secondPath %}
      <ul class="third">
      {% assign thirdPath = 'theorie-erlebnispfade' %}
      {% assign thirdName = 'Theorie Erlebnispfade' %}
      <li {% if location[2] == thirdPath and location.size == 3 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/">{{thirdName}}</a></li>
      {% if location[2] == thirdPath %}
        <ul class="fourth">
        {% assign fourthPath = 'historische-entwicklung' %}
        {% assign fourthName = 'Historische Entwicklung' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'vom-lehrpfad-zum-erlebnispfad' %}
        {% assign fourthName = 'Vom Lehrpfad zum Erlebnispfad' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'definition-und-abgrenzung-des-erlebnispfades' %}
        {% assign fourthName = 'Definition und Abgrenzung des Erlebnispfades' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'vermittlungsmethoden' %}
        {% assign fourthName = 'Vermittlungs&shy;methoden' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'medien' %}
        {% assign fourthName = 'Medien' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
      </ul>
      {% endif %}
      {% assign thirdPath = 'konzeptschritte-eines-erlebnispfades' %}
      {% assign thirdName = 'Konzeptschritte eines Erlebnispfades' %}
      <li {% if location[2] == thirdPath and location.size == 3 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/">{{thirdName}}</a></li>
      {% if location[2] == thirdPath %}
        <ul class="fourth">
        {% assign fourthPath = 'thema' %}
        {% assign fourthName = 'Thema' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'ziele' %}
        {% assign fourthName = 'Ziele' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'zielgruppe' %}
        {% assign fourthName = 'Zielgruppe' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'wegfuehrung' %}
        {% assign fourthName = 'Wegführung' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
        {% assign fourthPath = 'vermittlungsmethoden' %}
        {% assign fourthName = 'Vermittlungs&shy;methoden' %}
        <li {% if location[3] == fourthPath and location.size == 4 %}class="active" {% endif %}><a href="/hintergrundwissen/{{secondPath}}/{{thirdPath}}/{{fourthPath}}/">{{fourthName}}</a></li>
      </ul>
      {% endif %}
    </ul>
    {% endif %}
