# Labo 2 - reflecties

Naam: Remo

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: attributen in de unorderd list binnen het nav element in de header
- b. `article > p`: de paragraaf als kind van artikel
- c. `.uren li:nth-child(3)`: het derde kind in de lijst van de class uren
- d. `h2 ~ p`: alle paragraven die na h2 komen
- e. `.rassen li:first-child`: het eerst kind in de lijst van de class rassen

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|-------|---------------------------|-------------------|------------------------|--------|
|   1   | Green                     | specifiteit       | Green                  |   ✓    |
|   2   | Blue                      | specifiteit       | Blue                   |   ✓    |
|   3   | Blue                      | Volgorde          | Red                    |   X    |
|   4   | Red                       | Volgorde          | Red                    |   ✓    |
|   5   | Blue                      | specifiteit       | Blue                   |   ✓    |
|   6   | Blue                      | specifiteit       | Blue                   |   ✓    |
|   7   | Black                     | herkomst          | Red                    |   X    |
|   8   | Blue                      | herkomst          | Blue                   |   ✓    |
|   9   | Red                       | !Important        | Red                    |   ✓    |
|   10  | Black                     | herkomst          | Green                  |   X    |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
vraag #3    : ik dacht dat de volgorde een hogere prioriteit had dan de specificatie.
vraag #7    : Ik dacht dat .v7 niet voldoende was om de class aan te spreken en dat deze hierdoor de aanpassing niet ging overnemen en terug naar de default instelling ging gaan.
vraag #10   : ik dacht dat bij eender welke fout binnen in de opmaak van één item dat deze dan volledig zou genegeerd worden en ook hier dus weer over zou gaan naar de default setting.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
* nav a
* omdat de styling voor de links binnen de nav allemaal hetzelfde zijn en deze opzich al een duidelijke specificatie is, toch zeker voor de hoeveelheid links die er maar zitten in de nav.

- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?


## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
kleuren, letterypes, lettergrootte: Deze waardes worden vaak herhaald op de site, waarbij ik deze hier heb gebundeld en ze dus gemakkelijk hier kan aanpassen moest ik dat willen. ook zijn de benamingen bij de waardes van de kleuren gemakkelijker te lezen dan hun RGB waarde.

- Wat verandert er in je site als je één token wijzigt?
Dan veranderen alle elementen naar de wijziging die deze token gebruiken als waarde.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
