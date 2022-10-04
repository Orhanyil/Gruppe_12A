# GRUPPE-12B: FLAGGOPPGAVE

| Fullt navn |	Github |
| -----------| --------- |
| Mathias Ladiszlaidesz |	https://github.com/Mathiasladisz/IND-REPOSITORY.git |
| Benjamin Hole |	https://github.com/Benjamineternity/IND-REPOSITORY.git |
| Martin Steiro |	https://github.com/martinsteiro/IND-REPOSITORY.git |
| Annette Aas Brynhildsen	| https://github.com/annetteab/IND-REPOSITORY.git |
| Henny Rushfeldt |	https://github.com/hennyrush/IND-REPOSITORY.git |
| Orhan Yildirim |	https://git@github.com/Orhanyil/IND-REPOSITORY.git |



**Prosessen for valg av “Github projects” og mal for prosjektadministrasjon**

Vi valgte å gjennomføre flaggoppgaven med metoden Kanban-oppsett. Vi tenkte at dette var mer oversiktlig for en mindre gruppeoppgave enn Scrum både for hvordan vi skal planlegge, jobbe under arbeid og dokumentere. Scrum frameworket ble for komplisert for en liten oppgave slik som vi fikk. Vi valgte også å gi alle muligheten til å kunne "pushe" og "merge" sine endringer. Vi tenkte at dette ga mulighet for alle på gruppa å kunne gjøre endringer selvstendig og for oppgaveindelingen ga det muligheten for de som hadde ansvar for sine oppgaver å laste disse opp til main branch. Videre gjorde det også at vi lærte git og Github på en måte der vi kunne se endringene vi gjorde bli lastet opp selv. Arbeidsoppgavene strukturerte vi i "bord" fordi som tidligere var dette en mindre oppgave der "issues" ikke var svært omfattende som gjorde det mer oversiktig sammenlignet med tabell. 


**Prosessen for valg av arbeidsoppgaver**

Vi brukte prosjekt på Github for å dele opgavene og følge prosesen til oppgaven. Det er 3 deler for oppgavene, pflagg.html (Annette og Henny), cssflagg.html (Benjamin og Mathias),  og canvasflagg.html (Martin og Orhan). Målet var at alle skulle ha kontroll på Github. På denne måten alle gruppemedlemer skulle øve mer om Github. Vi opplevde noen konflikter når vi merged, men det var lett å løse den fordi hver oppgave ble gjort av bare 2 gruppemedlemer. Som nevnt tidligere ga vi også alle rett til å merge som hjalp når vi hadde delt inn oppgavene til forskjellige personer. Videre var den orginale planen var at alle gruppemedlemmer jobbet i sin branch (pflagg ...). Det var ikke slik det endte opp med å bli. Det hendte noen problemer med merging og git når vi prøvde å jobbe i branch. Vi endte opp med å heller jobbe i hver vår "fork" hvor vi pushet endringene fra. 


**A) Pflagg**

Vi lagde først det tyske flagget, i p-elementet går det kun an å ha horisontale flagg, dette ble da bakgrunnen for valget. En ulempe med å lage flagg i dette elementet er at det som sagt kun kan være horisontale, men fordelen med dette er at det er lett om man skal lage flere flagg da det bare er å kopiere koden og endre farger og evt. dimensjonene. 
Vi ble litt usikre om vi skulle ha tre flagg på hver oppgave, så vi lagde to flagg til. Dette var da Litauen og Mauritius. Fikk senere svar fra Janis at det kun var ett flagg per oppgave. Synes da at Mauritius var et mer eksotisk valg og byttet til dette.
Vi valgte som sagt å ha Mauritius' flagg, for å finne rett dimensjon og farge brukte vi Wikipedia sin side, Flag of Mauritius, (Wikipedia, 2022), disse dimensjonene var da 2:3, dette gjør langsida til 300px og kortsida 200px etter litt kjapp matematikk. 

For å få litt avstand fra toppen av siden til flagget skrev vi inn margin-top i den første p style. 

En fordel med Pflagg er at det er lett leselig og forståelig dersom en er ny i koding. På den andre siden er det begrenset hva en kan gjøre når en skal kode i et større format. Pflagg kan også være forvirrende for personer som bruker text-to-speech, da det er tekst i p element. Dette kan være utfordrende for f.eks. svaksynte som er avhengig av kunstig tale/talesystem. 


**B) Cssflagg**

Vi valgte flagget til Østerriket. For å finne all informasjonen vi trengte angående farge, dimensjoner og proporsjoner brukte vi wikipedia sin nettside «Flag of Austria», (Wikipedia, 2022), der fant vi ut at størrelsesforholdet var 2:3, dette vil da si at det er ett rektangel. Proporsjonene ble da 180px på langsida og 120px på kortsida. Vi måtte sentrifisere det med ```<center></center>``` for å få det i midten. Fargene ble skrevet med hex-kode.


**C) Canvasflagg**

Når vi skulle lage et flagg med canvas API måtte vi først finne ut hvordan en bruker denne funksjonen. Det gjorde vi ved å gå gjennom Canvas API på MDN Web Docs. Her fant vi blant annet ut hva vi måtte skrive i HTML for å vise det på nettsiden: ```<canvas id="blank"></canvas>``` og for å hente id fra HTML i javascript: ```document.getElementById("blank")```. Deretter spesifisere at vi skal tegne i 2d: ```canvas.getContext("2d");``` (MDN Web Docs). Nå kunne vi begynne å tegne flagget, men først måtte vi velge et flagg vi ville lage. Det endte opp med å bli Sverige sitt flagg. Når vi skulle lage Sverige sitt flagg på den korrekte måten, trengte vi riktige dimensjoner og fargekoder. Vi fant riktige dimensjonene og fargene til Sverige sitt flagg på Sveriges flagge loven (Flaggloven, 1982, § 1-4), og  kodene til fargene for javascript på internet (schemecolor, u.å.). Da vi hadde problemer med å flytte flagget til midten av siden etter å ha
laget det, og ved å bruke ```<center></center>``` koden, løste vi dette problemet. Vi synes det er veldig praktisk å bruke koordinatsystemet til javascript for å plassere et gult kors på blå bakgrunn.

Ulempen med Canvas er at for mer kompliserte flagg med tegninger på kan det være vanskeligere å tegne i canvas. Det kan gjøres ved å farge hver eneste piksel, men dette er tidskrevende. Fordelene er derimot sammenlignet med de to andre oppgavene at Canvas har mer frihet til å tegne på alle mulige måter i HTML så lenge det er i 2d. 



**Referanser:**

Flaggloven. *Lag om Sveriges flagga* [1982-269]. Riksdagen. https://www.riksdagen.se/sv/dokument-lagar/dokument/svensk-forfattningssamling/lag-1982269-om-sveriges-flagga_sfs-1982-269

Schemecolor. (u.å). *Sweden Flag Colors Hex, RGB & CMYK Codes*. Hentet 3. oktober 2022 fra https://www.schemecolor.com/sweden-flag-colors.php#:~:text=Sweden%20Flag%20Colors%20Hex%2C%20RGB%20%26%20CMYK%20Codes.,and%20CMYK%20codes%20are%20in%20the%20table%20below.

MDN Web Docs. (2022, 2. september). *Canvas API*. Hentet 3. oktober 2022 fra: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API

Wikipedia. (21. september 2022). *Flag of Mauritius*. Hentet 30. september 2022 fra:
https://en.wikipedia.org/wiki/Flag_of_Mauritius

Wikipedia. (30. september 2022) *Falg of Austira*. Hentet 3 oktober 2022 fra: https://en.wikipedia.org/wiki/Flag_of_Austria

