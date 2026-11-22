# Labo 7 - reflecties

Naam: Noa Metzemakers

De telling van mijn eigen site vóór dit labo (7.1): font-sizes ... / marges en paddings ... / kleuren ...

## 1. Tintenladder

- Wat is de contrastratio van het label op de vijfde band, en op de zesde? Wat gebeurt er als je de wissel van inkt naar papier één band later legt?
    De vijfde band staat als inkt en de zesde band staat als papier,?
- Je verandert `--hue` in 25: hoeveel regels paste je aan, en wat zegt dat over 7.6?
    Ik paste één regel aan namelijk --hue naar 25 en alle 10 tredes kregen in één keer een nieuwe kleur, de verandering lukt omdat er in hsl een eerste getal is dat namelijk hue bevat.

## 2. Leespagina

- Waarom is de kolom op 1280 px zo'n 674 px breed en niet 65 keer 16 px?
    De ch is niet gericht op pixels maar op de breedte van de nul van de huidige letter.
- Wat verandert er als je de ratio op 1.2 zet, en hoeveel regels pas je daarvoor aan?
    De regels liggen dan dichter bij elkaar en maakt de pagina 'platter', ik heb 6 token waarden in de :root aangepast.
- Hoeveel verschillende waarden voor `margin` en `padding` staan er in je bestand, en komen ze allemaal uit de schaal?
    Vijf van xs tot xl, ze komen uit de schaal er komen geen losse afstanden voor op de pagina.

## 3. Frituur 't Pleintje

- Hoeveel declaraties staan er in je donkere query? Als het er meer dan vijf zijn: welke kleur ontsnapte?
    Vijf, alleen de vijf kleuren die in de :root liggen.
- Het label "nieuw": wat zijn de ratio's in het licht en in het donker, en welke is de krapste?
    ?
- Waarom staat de tekst van het label in `--color-surface` en niet in `white`?
    ?

## 4. De kaaien

- Waarom staat de foto als achtergrond en niet als `img`?
    Omdat de foto enkel als decoratie dient.
- Zonder de achtergrondkleur van `.paneel`: wat is de contrastratio van de titel op het lichtste deel van de foto?
    ?
- Wat doet `background-repeat: no-repeat` met de voet, en `contain` in plaats van `cover` met de held?
    no-repeat zorgt ervoor dat de golfbeweging/patroon oneindig blijft doorlopen/herhalen, contain zorgt ervoor dat de afbeelding zichtbaar blijft binnen het kader maar laat witruimte rondom de kader

## 5. Fietsatelier Noord

- Staat er in `stijl.css` nog een letterlijke kleur, letter of maat buiten `:root`? Welke, en waarom ontsnapte ze?
    Ja, er staan letterlijke lettertypes zoals Georgia en Verdana en de kleur transparent buiten de :root.
- Hoeveel regels telt `thema.css` zonder de `@font-face`-blokken?
    Het telt 14 lijnen.
- Wat betekent dat voor B7.1 en je eigen site?
    Als alle CSS-waarde in tokens geïmplementeerd worden, als je een dark mode voor je pagina gaat implementeren, zul je maar een paar lijnen van :root moeten veranderen 

## Thuis: B7.1 (met AI of zonder AI)

Welke route koos je? De twee screenshots van de tokenwissel staan in `site/review/`. Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
