---
Title: Load
Description: Load
Template: analysis
---

Laddningstid och användbarhet
==================

Urval
-----------------------
Jag har valt att analysera tre webbsidor: Filmstaden, Zara och JSPS Stockholm. För det första valde jag webbplatserna som använder flera bilder. 

Filmstaden är en hemsida för biobolag så jag tyckte det var intressant att se hur de visar bilder i bra kvalitet samtidigt undvika att vara tung och långsam hemsida.

Zara kan ha liknande intentioner som Filmstaden eftersom de är en klädbutik och deras hemsidas syfte kan vara att visa olika kläder med bra bilder.

JSPS Stockholm är min tidigare arbetsplats och ett ganska litet kontor utan IT-avdelning. Syftet med denna webbplats är att informera om organisationen och deras verksamhet och de är inte ett privata foretag. Jag inkluderade den här webbplatsen eftersom den har en annan karaktär än andra två webbplatser.


Metod
-----------------------
Jag använde verktyg PageSpeed Insights och Firefox Devtools för tre sidor av valda tre webbplatserna. Från PageSpeed Insights fick jag betyg för respektiva Mobile och Desktop sidor. Med hjälp av Firefox devtools mät jag laddningstid, requests och sidstorlek och det genomsnittliga värdet av uppmätt tre gånger är visas i tabellen. 


Resultat
-----------------------
<div class="result-sheet">
<iframe title="Loading time report" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRZxNC-v6AzYvA0InVsgyv28SQh_d0PTkGBVn00F-jABRE6kHhFvK92QUQre8ZvaHOmUG6rxSxwLM49/pubhtml?gid=0&single=true"></iframe>

</div>

### Filmstaden
![me image](%assets_url%/img/filmstaden.png "Filmstaden")

Webbplatsen har många bilder, men sidstorleken är inte större än jag förväntade mig, och laddningstiden för alla tre sidorna är mindre än 2 sekunder. Om man tittar på resultaten av Firefox Devtool verkar det vara bra webbplatsen, men ingen av PageSpeed ​​​​Insights-poängen överstiger 50, och betyget är inte särskilt bra.
Webbplatsen kan förbättras med minskning av oanvända JavaScript och CSS, och eliminering av renderingsblockerande resurser. Dessutom kan filmer&Trailer sidan förbättras genom lazy-loading som undvika att ladda ner bilder på en gång.

### ZARA
![me image](%assets_url%/img/zara.png "ZARA")

Trots de höga sidstorlekarna och många request är laddningstiden cirka 2 sekunder eller mindre. Speciellt, även om sidstorleken överstiger 7MB, verkar laddningstiden på 1,3 sekunder vara ett utmärkt resultat. PageSpeeds betyg är inte mindre än 50 för datorer, och det har ett bra betyg.
Webbplatsen kan förbättras med minskning av oanvända JavaScript och CSS, och eliminering av renderingsblockerande resurser. Enlight PageSpeed Insights kan användning av andra filformat som WebP och AVIF vara bättre än PNG eller JPEG med snabbare laddning och mindre datasammansättning.


### JSPS Stockholm
![me image](%assets_url%/img/jsps.png "JSPS")

Framför allt var sidladdningstiden mycket lång, 8 till 15 sekunder. Å andra sidan var sidstorleken mindre än andra webbplatser. Märkligt nog var ändå betyg i PageSpeed ​​​​Insights inte dåligt.
Långsam webbplatsen verkar bero på den dåliga serverns svarstid. Användning av lämplig storlek av bilder kan också förbättra laddningstiden.

Analys
-----------------------

Filmstaden och Zaras förbättringsåtgäder tenderade att vara liknande, med fokus på JavaScript-relaterat innehåll. Å andra sidan hade JSPS ett problem med serversvar och skilde sig från de andra två webbplatserna.
När det gäller användning av bilderna intar en stor del av Filmstadens och Zaras webbplats, de hanterar bildstorleken ordentligt och det inte finns många punkter att förbättra. Å andra sidan förväntas JSPS förbättras genom att göra några bilder till en lämplig storlek. 
Jag tycker att Filmstaden och Zara är stora företag och att visa bilder för användarna är en viktig punkt för sidans syfte. Det verkar som om IT-teamet tar hänsyn till laddningstiden och bildstorleken eftersom det direkt påverkar försäljningen av deras produkter. 
I det avseendet är visning av bilder inte en prioriterad fråga för JSPS som inte är en privat organization. Därför de lägger inte tillräckligt med resurser på IT och det leder till serverproblem.

Om man bara tittar på laddningstiden är vinnaren Zara, men om man tittar på pageSpeed ​​​​Insights score tror jag att det är JSPS. Laddningstiden för JSPS är dock för lång för att överstiga 10s, så det är svårt att säga de är vinnare. Då är Zara kvar och det blir vinnaren enlight elimineringsmetod.

Angående en gräns för laddningstid känner jag att JSPS-sidan är långsam, och jag vill stänga webbläsaren på vägen. När jag mätte tajmingen när jag börjar känna frustrerande, det var 3 sekunder.Å andra sidan, när jag besöker Filmstaden eller Zara-sidan, glöm tanken om själva laddningstiden. Så mindre än 2 sekunder känner jag snabb.

Övrigt
-----------------------

<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->

Författare: Tomoko Svedlund Ishii