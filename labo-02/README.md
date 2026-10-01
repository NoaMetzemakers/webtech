# Labo 2 - reflecties

Naam: Noa Metzemakers

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: #adopteren,#rassen en #uren
- b. `article > p`: alle p elementen binnen article
- c. `.uren li:nth-child(3)`: 'woensdag: 14-18u' wordt geselecteerd
- d. `h2 ~ p`: elke p dat na een h2 zit, wordt geselecteerd
- e. `.rassen li:first-child`: Honden,Herders en herderkruisingen, Staffords, Kleine rassen en Europese korthaar worden geselecteerd

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | green | herkomst | J | |
| 2 | blue | volgorde | J |  |
| 3 | red | specificiteit | J |  |
| 4 | green | specificiteit | NJ |  |
| 5 | blue | herkomst | J |  |
| 6 | blue | specificiteit | J |  |
| 7 | geen kleur | herkomst | NJ |  |
| 8 | red | volgorde | NJ |  |
| 9 | blue | specificiteit | NJ |  |
| 10 |error-geen kleur(; vergeten na de font-size) | / | NJ |  |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
4,7,8,9,10 waren fout

4 was fout omdat ik dacht dat de specificiteit toepasbaar was in dit voorbeeld maar de groene kleur kon geen directe child vinden na .v4 (was onbestaand)

7 was fout omdat ik geen specifieke benoeming van v7 in de class zag dus heb ik geen kleur als voorspelling meegegeven

8 was fout omdat er al in de html een color-prop toegewezen werd dat niet aangepast kon worden in de css

9 was fout omdat de rode kleur als !important werd toegewezen en dus als nummer 1 property wordt gebruikt (het steekt boven iedereen/de ladder uit)

10 was fout omdat er bij mijn color: blue een bewuste error was, maar heb de eerste color: blue niet opgemerkt

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class? 
    a, want het bevat het href keyword dat de effectieve link bevat en is er dus die specifieke a nodig om aanpassingen te doen, class kan je gebruiken om een verzameling van specifieke elementen aan te passen maar zal niet de effectieve tekst/link kunnen aanpassen, want de class zelf bevat het href keyword niet.

- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak? 
    De regels die de line-height property nodig hadden om een correcte witruimte achter te laten, omdat ik meerdere percentages/testen moest uitproberen om de meest correcte lijn hoogte te vinden

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die? 
    --kleur-achtergrond --> om een kleur te hebben voor de achtergrond van de pagina's,
    --lettertype --> om een bepaalde lettertype te implementeren aan mijn site
    --teskgrootte --> om een basisgrootte te hebben voor alle teksten die aanwezig zijn in de site

- Wat verandert er in je site als je één token wijzigt?
    alle properties die die bepaalde token gebruiken krijgen automatisch de nieuwe waarden

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. Het LLM laat weten dat de html-elementen correct zijn gebruikt voor een duidelijke structuur(enkel html) van de pagina
2. Het LLM gebruikt moderne en handige CSS-keywords/variabele zoals :root en het gebruik maken van flexbox dat voor een minimalistische code-structuur zorgt
3. Het LLM geeft een reminder om de mapstructuur en het pad aandachtig te controleren, zodat de browser de stijl.css correct kan toevoegen/inladen
4. Het LLM waarschuwt voor hoofdlettergevoeligheid bij bestandsnamen in GitHub, om het meerdere keren na te kijken
5. Het LLM raad aan om het gebruik van Live Server en het nakijken via DevTools binnen de browser om na te checken of de stijl correct werd geïnplementeerd
