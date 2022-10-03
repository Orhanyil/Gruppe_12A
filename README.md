# GRUPPE-12B SIN FLAGGOPPGAVE

| Fullt navn |	Github |
| -----------| --------- |
| Mathias Ladiszlaidesz |	https://github.com/Mathiasladisz/IND-REPOSITORY.git |
| Benjamin Hole |	https://github.com/Benjamineternity/IND-REPOSITORY.git |
| Martin Steiro |	https://github.com/martinsteiro/IND-REPOSITORY.git |
| Annette Aas Brynhildsen	| https://github.com/annetteab/IND-REPOSITORY.git |
| Henny Rushfeldt |	https://github.com/hennyrush/IND-REPOSITORY.git |
| Orhan Yildirim |	https://git@github.com/Orhanyil/IND-REPOSITORY.git |

**a)  en beskrivelse av prosessen for valg av “Github projects” og mal for prosjektadministrasjon, samt en beskrivelse av strukturering av “bord” eller “tabell” i “Github projects” (relater til Kanban, Scrum, Scrumban eller annen type metode)**

Vi valgte å gjennomføre flaggoppgaven med metoden Kanban-oppsett. Vi tenkte at dette var mer oversiktlig for en mindre gruppeoppgave enn Scrum. Dette strukturerte vi i "bord" fordi som tidligere var dette en mindre oppgave der "issues" ikke var svært omfattende som gjorde det mer oversiktig med "bord. 

**b) en beskrivelse av prosessen for valg av relevante arbeidsoppgaver (se nedbryting i Karlsen)**

....

**c) en beskrivelse med definisjoner og refleksjon rundt prosessen for implementering av de 3 løsningene og en analyse av forskjeller, fordeler og ulemper med de tre løsningene 4a), 4b) og 4c)**


4a)
Vi lagde først det tyske flagget, i p-elementet går det kun an å ha horisontale flagg, dette ble da bakgrunnen for valget. En ulempe med å lage flagg i dette elementet er at det som sagt kun kan være horisontale, men fordelen med dette er at det er lett om man skal lage flere flagg da det bare er å kopiere koden og endre farger og evt. dimensjonene. 
Vi ble plutselig litt usikre om vi skulle ha tre flagg på hver oppgave, så vi lagde to flagg til. Dette var da Litauen og Mauritius. Fikk senere svar fra Janis at det kun var ett flagg per oppgave. Synes da at Mauritius var et mer eksotisk valg og byttet til dette.
Vi valgte som sagt å ha Mauritius' flagg, for å finne rett dimensjon og farge brukte vi Wikipedia sin side, Flag of Mauritius, (Wikipedia, 2022), disse dimensjonene var da 2:3, dette gjør langsida til 300px og kortsida 200px etter litt kjapp matematikk. 

For å få litt avstand fra toppen av siden til flagget skrev vi inn margin-top i den første p style. 

4b)
*Benjamin og Mathias*

4c)

Når vi skulle lage et flagg med canvas API måtte vi først finne ut hvordan en bruker denne funksjonen. Det gjorde vi ved å gå gjennom Canvas API på MDN Web Docs. Her fant vi blant annet ut hva vi måtte skrive i html for å vise det på nettsiden: ```<canvas id="blank"></canvas>```
og for å hente id fra html i javascript: ```document.getElementById("blank")```. Deretter spesifisere at vi skal tegne i 2d: ```canvas.getContext("2d");``` (MDN Web Docs). Nå kunne vi begynne å tegne flagget, men først måtte vi velge et flagg vi ville lage. Det endte opp med å bli Sverige sitt flagg. Når vi skulle lage Sverige sitt flagg på den korrekte måten, trengte vi riktige dimensjoner og fargekoder. Vi fant riktige dimensjonene og fargene til Sverige sitt flagg på Sveriges flagge loven (www.riksdagen.se), og  kodene til fargene for javascript på internet (www.w3schools.com ). Da vi hadde problemer med å flytte flagget til midten av siden etter å ha
laget det, og ved å bruke ```<center></center>``` koden, løste vi dette problemet. Vi synes det er veldig praktisk å bruke koordinatsystemet til javascript for å plassere et gult kors på blå bakgrunn.


Referanser:  

Flaggloven. *Lag om Sveriges flagga* [1982-269]. Riksdagen. https://www.riksdagen.se/sv/dokument-lagar/dokument/svensk-forfattningssamling/lag-1982269-om-sveriges-flagga_sfs-1982-269

Farge kodene: https://www.w3schools.com/colors/colors_picker.asp

MDN Web Docs. (2022, 2. september). *Canvas API*. Hentet 3. oktober 2022 fra: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API

Wikipedia. (21. september 2022). *Flag of Mauritius*. Hentet 30. september 2022 fra:
https://en.wikipedia.org/wiki/Flag_of_Mauritius
