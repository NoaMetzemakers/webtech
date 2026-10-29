# Labo 6 - reflecties

Naam: Noa Metzemakres

Getest op dit echte toestel (merk, browser): 
Lenovo E14 Laptop, gebruikte browser Google Chrome

## 1. Kleurvlakken

- Wat gebeurt er als je de twee queries van plaats verwisselt, en waarom?
    Dan worden de patronen verwisselt tussen de twee media queries(breedtes).
- Waarom `100svh` en niet `100vh`?
    Omdat 100vh net te groot is voor de mobiele versie, met vh wordt de adresbalk van de browser meegerekend binnen de vh.

## 2. Dashboard

- Waarom staat `grid-column: 1 / -1` in de query van 50rem en niet in de basis, en waarom hoef je het in de query van 75rem niet te herhalen?
    Het moet niet in de basis omdat er in de basis alles onder elkaar staat dus is er maar 1 kolom van toepassing, het is voor 75rem niet nodig te herhalen want CSS de vorige verandering/instelling onthoud dankzij het gebruik van min-width bij @media.
- Wat betekent `-1`, en wat gebeurt er als je bij de grafiek `grid-row: 2 / 4` vergeet?
    Dat wijst de allerlaatste lijn van de grid aan (het uiteinde van de grid), als je het vergeet dan weet de browser niet dat het element twee blokken moet innemen/uitsmeren op de rijen.

## 3. Scheldekaai Festival

- Wat is de h1 met `clamp(2rem, 5vw + 1rem, 4rem)` op 400 px, op 800 px en op 1280 px?
    Op 400px is de h1 ongeveer 2rem, op 800px is het ongeveer 2.5rem en op 1280px is het maximum 4rem.
- Waarom staat er een rem-term in het midden?
    Het zorgt ervoor dat de tekst mee kan groeien met het scherm.
- Waarom twee breekpunten voor de header, en niet één?
    Bij 50rem gaan de koppen(h1,h2) langs elkaar geplaatst worden en bij 75rem schuift het logo bnaar de linkerkant.

## 4. Tribune

- Waarom hoef je in de query geen `grid-row` te schrijven?
    Omdat de rijen al (verticaal) in volgorde staan in de html. 
- Zou je deze tribune ook met `repeat(auto-fit, minmax())` kunnen bouwen? Waarom wel of niet?
    Nee, want auto-fit maakt automatisch gelijke kolommen aan die zich aanpassen aan de breedte van het scherm/browser terwijl de rijen in de tribune elk een unieke startpositie hebben in de grid-column.

## 5. Affiche

- Waarom zou `width: 28rem` op een telefoon een horizontale schuifbalk geven, en hoe vind je zo'n saboteur met DevTools?
    Omdat width:28rem breder is dan het scherm van een gsm/telefoon, in Devtools kan je zien welke elementen uit de randen steken.
- Wat doet `top: auto` in de query, en wat gebeurt er als je het weglaat?
    Het verwijderd de top-waarde vanuit de base-weergave/waarde, wanneer je het weglaat, blijft de base-waarde stoten/botsen met een nieuw ingestelde bottom waardoor de stickers niet correct geplaatst worden.


## Thuis: B6.1 (met AI of zonder AI)

Welke route koos je? De AI-route.
Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. Ontbrekend gebruik van clamp: Het LLM gebruikte geen clamp dat wel werd gevraagd in de prompt. 
2. Het LLM paste twee nog niet behandelde odnerwerpen namelijk transition en transform, die ik weggelaten heb in de tweede prompt/ gevraagd om te verwijderen voor de nieuwe output.
3. ?
