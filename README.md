# Min kodplugg till Anytone AT-D878UV

## Copyright

© 2019-2023 by SM0RUX Pontus Falk

Filerna är tillgängliga under [GPLv3](https://github.com/sm0rux/at-d878uv/blob/master/LICENSE).

## Uppdatering av SM0RGM 

På grund av att Pontus SM0RUX av personliga skäl inte har möjlighet att uppdatera kodpluggen så har han och jag kommit överens om att jag övertar och uppdaterar kodpluggen. Kodpluggen är och förblir därmed "SM0RUX kodplugg" men underhållen av mig. Jag har skapat en fork av kodpluggarna och publicerat under mitt eget Github-konto och ändrat kontaktytorna i dessa filer, så kommentarer, ändringar och liknande lägger du som en issue på min Github eller kontaktar mig.

Även om man försöker vara minutiöst noggrann så kan det smyga sig in fel. Kodpluggen innehåller i denna version 538 kanaler. Så hittar du något fel eller har andra synpunkter, lägga gärna en issue eller skicka ett mail. 

Nacka mars 2023
SM0RGM Stefan Helander

## Syfte

Det här är min kodplugg till min Anytone AT-D878UV. Jag använder CPS version 1.27 och firmware 1.27. Huvudsyftet med publiceringen av filerna här på GitHub är att förenkla för mig själv när det gäller uppdateringar. Jag har inget emot att dela med mig av filerna så att andra kan nyttja dem under förutsättning att de som återanvänder mina filer följer licensvillkoren i [GPLv3](https://github.com/sm0rux/at-d878uv/blob/master/LICENSE).

Om du vill bidra med något så är du naturligtvis välkommen att göra så antingen genom att skapa en Pull Request (kräver en del kunskap om hur GitHub funkar) eller genom att skapa ett [issue](https://github.com/sm0rgm/at-d878uv/issues).

## Vad ingår i filerna?

Alla repeatrar i Sverige som kan köra DMR eller FM är inkluderade (källa: [sk6ba.se](https://sk6ba.se/repeater/karta/)). Även repeatrar som kör exempelvis C4FM och FM finns med. Repeatrarna är indelade distriksvis. Tyvärr finns det så många repeatrar i sjätte distriktet att alla inte får plats i scanning-listan.

DMR-repeatrarna är också indelade i roaming-zoner för att få roamingen att funka på ett smidigt sätt.

## Boot logo

Bland filerna i kodpluggen finner du filen SSA.jpg. Det är SSAs logotype som kan användas som startbild. Gör så här:

* I CPS, gå till Tool -> Boot image (när radion är ansluten till datorn)
* Klicka på Open Image och välj filen SSA.jpg
* Logon ska ny synas i bildfönstret, annars är något fel
* Klicka på Write
* Gå till Optional Setting -> Power on -> Power-on interface -> Custom picture
* Spara ändringarna till radion

## Vad du måste göra!

### Vilka filer ska du hämta?

Jag rekommenderar att du hämtar filerna som jag har packat ihop i en [release](https://github.com/sm0rgm/at-d878uv/releases) istället för att hämta mina arbetsfiler!

### När filerna är hämtade... 

Om du vill använda mina filer så behöver du i princip bara ändra DMR-ID i RadioIDList.CSV och APRS-inställningarna i APRS.CSV - sedan är det bara att tuta och köra.

Förmodligen vill du ändra på fler saker, men det överlåter jag till dig att fixa med själv.

### Uppdatera befintlig kodplugg

Om du bara vill uppdatera din radio med kanaler, scanlistor, roaming och zoner men låta resterande inställning vara som de är kan du, istället för att importera hela N0CALL.LST välja att enbart importera filerna för Channel, ScanList, RoamingChannels, RoamingZone och Zone. (SM0RGM)

73's de SM0RUX Pontus

2020-11-01
