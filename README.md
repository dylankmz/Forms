# Werkcollege 9

Maak een folder 'les9' waar al je oefeningen voor deze les in terecht komen.

## Responsive

Vertrek met video.html (en css) en maak screenshot video.png na.<br>
Dit is een korte oefening waar 3 technieken oefenen om video/audio bestanden te tonen.<br>

### video
Begin met het `<video>` element. Laad alle bunny video files in met behulp van het `<source>` element. <br>
Gebruik de de benodigde attributen voor:
* De video niet op voorhand te laten laden
* bestuursknoppen aanwezig zijn (play, tijdlijn, ...)
* Een omslagfoto voor de video
* voorkom autoplay

### audio
Begin met het `<audio>` element. Laad alle track audio files in met behulp van het `<source>` element. <br>

### iframe
Een iframe is een stukje code dat je van verschillende websites kan halen o.a. Youtube.<br>
Het doel is om een responsive iframe te maken. Dit wil zeggen dat het iframe moet schalen met de breedte van het schem.
Gebruik volgende HTML code en ga in CSS aan de slag:
````
  <div class="video-container">
    <div class="video-responsive">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/QlY-_UzTU4I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>
````

## Table

Vertrek met table.html (en css) en maak screenshot table.png na.<br>
In table.txt vind je alle text terug die je nodig hebt.<br>
Geef je `table` een `thead` en een `tbody`. <br>
**Let op!** Voor table data in een `thead` gebruiken we het `th` element ipv `td`.
Zorg ervoor dat je minstents 1 x een `colspan` gebruikt en 1x een `rowspan`.

CSS properties die je nodig hebt:
* `border-collapse`
* `border-spacing`

Als je de volledige tabel hebt nagemaakt mag je de oneven rijen een andere kleur geven.
gebruik hiervoor een `nth-child()` pseudo selector.

## form
Vertrek met form.html (en css) en maak screenshot form.png na.<br>

### HTML
Begin eerst met het maken van het formulier in HTML. 
Je geeft je form volgende attributen `action="form.html"` & `method="post"`. <br>
Gebruikt een `label` voor de text die bij een input hoort (geen `p`!).<br>
Alle `inputs` krijgen een `id`, `name` & een `type`. Text inputs geef je een `placeholder`. Radio inputs krijgen een `value`.<br>
Bij de radio buttons heb je een extra titel. Hiervoor kan je een `fieldset` & een `legend` gebruiken.Alle `inputs` krijgen een `id`, `name` & een `type`. Text inputs geef je een `placeholder`. Radio inputs krijgen een `value`.


### CSS
De blauwe rand rond je inputveld kan verwijderen met `outline: none;`.<br>
Probeer ook eens CSS te schrijven met een [attribuut selector](https://www.w3schools.com/css/css_attribute_selectors.asp).

**LET OP!** Je kan een radio button niet stijlen! Je zal met 2 pseudo-elementen moeten werken (`:before` & `:after`). <br>
In CSS kan met de `input:checked` selector gebruiken voor extra aanpassigen.






