# Labo 4 - reflecties

Naam: Noa Metzemakers

## 1. Drie kolommen

- Op welk element staat `display: flex`, en op welke elementen staat `flex`?
    Ik heb `display: flex` toegepast op de `main` want dat is het moederelement van de drie divelementen en zal dus als display flex bevatten, de kinderen van `main` zijn de drie divs en zullen elk flex 1 of 2 bevatten, `div:nth-child(1)` en `div:nth-child(3)` zullen de waarde 1 bevatten omdat ze dezelfde breedte en hoogte hebben, `div:nth-child(2)` zal de waarde 2 bevatten.
    
- Waarom staan die twee niet op hetzelfde element?
    Omdat `dipslay: flex` de 'display zelf' (gericht op het moederelement) van het element aanmaakt/beschrijft en `flex: ...` de plaats van het element aanwijst.

## 2. Navigatiebalk

- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas?
    `justify-content` verdeelt de ruimte langs de hoofdas en `align-items` verdeelt de ruimte langs de kruisas.
- Wat gebeurt er met de links als je `gap` vervangt door `margin-right` op elke `li`?
    - Dan worden de gaps/spaties tussen elke link gereset en krijgt enkel het uiteinde van de verzameling waarin de links in zitten genaamd de ul een spatie aan de rechterkant van 1rem,
    - gap praat tegen de kinderen van het gekozen element, margin(-right) praat direct tegen het kozen element.

## 3. Mondriaan

- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier?
    Ik heb de vlakken van `.geel` en `.marine` op een vaste rij gezet a.d.h.v. `grid-row` en `grid-column` omdat ze op een specifieke plaats in de grid moesten zitten en de andere 4 vlakken kregen hun plek automatisch
- Waarom is `gap` hier beter dan een border op elk vlak?
    gap maakt een gemeenschappelijk afstand tussen alle elementen aan binnen de grid/tussen de child-elementen, bij het gebruik van border worden de elementen (visueel) verkleint doordat de randen van de elementen een bepaalde plaats moeten innemen van dat element en dus heeft vooral het element een effect en niet de omgeving rond dat element.

## 4. Trap

- Wat zie je als je de `grid-row`-declaraties weghaalt, en waarom?
    Alle tredes worden langs elkaar geplaatst omdat de grid by default alle elementen op één row plaatst/zoals ze oorspronkelijk stonden zonder row.
- Wat betekent `grid-column: 4 / -1` voor de laatste trede, en waarom werkt het hier ook?
    Omdat kolom 4 de laatste kolom is van de grid, 4 / -1 betekent dat het gekozen element vanaf kolom 4 begint en tot het effectieve einde (-1) van de grid doorloopt wat in dit geval 4 is en blijft.

## 5. Dierenasiel Zonnehoek

- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?
    Deze pagina telt 3 layoutcontainers, de body gebruikt een grid, de header gebruikt een flexbox en de kaartenlijst gebruikt ook een grid.
- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost?
    De vaste/fixed hoogtes en breedtes drukken worden in elkaar 'gepropt' en passen niet meer op het scherm, het volgende hoofdstuk (5) zal dit probleem verder oplossen.

## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
