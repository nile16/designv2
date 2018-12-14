Utvärdering av webbplatsers laddningstid
========================================

Denna uppgiften går ut på att analysera hastigheten på Sveriges tre mest
traffikerade webbsidor.

Urval
-----------------------

Enligt Alexa.com är Sveriges tre mest traffikerade webbsidor:

* [Youtube.com](https://youtube.com)
* [Google.se](https://google.se)
* [Facebook.com](https://facebook.com)

Metod
-----------------------

För att få ett betyg på webbplatsernas hastighet användes Google Pagespeed.
Firefox konsol användes för att mäta laddningstid och antal resurser.

Resultat
-----------------------

|               | Youtube  | Google   | Facebook |
|---------------|----------|----------| ---------|
| Score desktop | 78       | 100      | 99       |
| Score mobile  | 47       | 90       | 73       |
| Laddningstid  | 3560 ms  | 780 ms   | 1893 ms  |
| Resurser      | 60       | 4        | 10       |
| Storlek       | 381 kb   | 69 kb    | 59 kb    |
| Hastighet     | 107 kb/s | 88 kb/s  | 31 kb/s  |


Analys
-----------------------

Googles sida är överlägset snabbast och vinner men också den sida med minst
innehåll.

Youtube är långsammast men också den sida med mest bilder och storlek.
Youtubes ganska höga hastighet gör att jag placerar den som tvåa.

Facebook är långsam trots sin ringa storlek och får därför jumboplatsen.

Jag vet inte hur dessa jättar kan förbättra sina sidor, det är över huvudet på
mig. Möjligtvis kunde Facebook kanske göra något åt sin hastighet.

Själv tycker jag att 2 sekunder är en övre gräns för laddningtid om en sida
ska uppfattas som snabb. Mindre än en sekund om den ska kännas som "realtid".


Referenser
-----------------------

[Google pagespeed](https://developers.google.com/speed/pagespeed/insights/)

[Youtube Skärmdump](img/report/youtube.jpg)

[Facebook Skärmdump](img/report/facebook.png)

[Google Skärmdump](img/report/google.png)

[Rådata](data/speed.ods)

Övrigt
-----------------------

Denna rapport är skriven av Nils Leandersson.
