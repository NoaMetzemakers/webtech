# Labo 3 - reflecties

Naam: Noa Metzemakers

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
    - De bolletjes die aanwezig waren in elk li-element (met list-style: none).
    - De padding aan de linkerkant van het ul element (met padding: 0).
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
    De hoogte van de li-elementen worden groter, de breedte en lettergrootte van de h2 en p elementen blijven ongewijzigd

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
    Voor het centreren van de tekst is de property text-align:center; toegepast.
    Voor de kolom zijn de properties: max-width: 40rem; en margin: 0 auto; toegepast.
- Waarom werkte de padding op de knop pas na `display: inline-block`?

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?
    De visuele breedte van het tabblad is 15rem, omdat er in de reset.css de property box-sizing op border-box werd ingesteld voor alle elementen.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
    height: 70%; werkt hier omdat de main een fixed hoogte heeft van 90vh, zonder die vaste hoogte van de main werken de percentages niet voorde cirkel/h1.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
    De breedte.

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
    Ik gaf de main een min-height omdat de hero minstens 80% van de 'vensterhoogte' moet bevatten, met min-height kan de inhoud groter worden maar niet lager dan 80%/80vh.
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
    Als er regeleinde tussen de twee elementen komt wordt de width geen 100% meer en gaat de rechter element onderaan liggen doordat het in een inline-block ligt.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 3.5 Het LLM(AI) gaf voor de pagina een vaste width en voor de teskblokken een vaste height, ik heb het naar max-width:800px; veranderd met margin:0 auto;
2. 3.6 Het LLM gebruikte random marges aan alle kanten. Ik heb dit aangepast door alleen met margin-bottom te werken en de andere marges te koppelen aan verschillende CSS-variabelen.
3. 
