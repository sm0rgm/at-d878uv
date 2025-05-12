
# Changelog

## 2025-05-12 (SM0RGM)

* Större uppdatering av kodpluggen som nu innehåller över 800 kanaler och zoner för SM, LA, OH, OZ, TK, JW, PA och DL (nordväst). I en sådan stor uppdatering kan det smyga sig in fel så felrapporter och förslag mottas tacksamt.
* En del repeaternamn har ändrats för att överensstämma med ortsnamnen i SK6BA:s repeaterkarta, t ex har repeatrar i Göteborg bytt namn till Guldheden och två av repeatrarna i Helsingborg heter numera Soderasen.
* P g a namnhamteringen mot SK6BA har repeatrar som kräver mellanslag i namnet istället ett understrykningstecken. T ex heter Upplands Väsby "Upplands\_Vasby".
* Kanaler i LA och OZ ligger i en enda zon vilket innebär att scanningslistorna innehåller för många kanaler. Hjälp med att dela in repeatrarna i dessa länder i zoner, t ex distriktsvis mottages tacksamt.
* Kanalnamnet har en eller flera bokstäver som suffix vilket anger vilken typ av funktioner som finns (om inget anges är repeatern antingen DMR via Brandmeister eller lokal FM-repeater utan reflektorkoppling):  
  L = Link (simplex)  
  A = AllstarLink  
  S = SVXlink  
  E = EchoLink  
  H = Hotspot (DMR)  
  F = FreeDMR / FinDMR  
  + = DMR+ / DMR Plus  
  I = IRLP / ircDDB  
  P = HAMphone

## 2025-05-04 (SM0RGM)

* Uppdaterat filer för CPS version 3.07.
* APRS-frekvens nr 8 ändrad till 145.825 MHz för APRS via ISS. 
  Obs! För att sända APRS via ISS måste du ändra digipath till:
  ARISS,WIDE2-1
  Se denna [artikel av K7KEZ](https://k7kez.com/aprs-settings-for-the-iss-international-space-station/) om hur man kör APRS via ISS.

* Ändrade kanaler per zon:
    * Simplex
        * +APRS ISS 145.825 MHz FM

## 2025-04-28 (SM0RGM)

* Uppdaterad mot SK6BA/SSA repeaterdatabas 2025-04-28 01:28:11
* DigitalContacList.CSV tvättad från skandinaviska tecken
* Ändrade kanaler per zon:
    * JW
        * + Svalbard 145.6000 MHz FM
    * LA
        * Sandnessjoen ändrad till Sandnessjoen 1
        * + Sandnessjoen 2 145.7250 MHz FM
        * + Kristianstad 3 145.7500 MHz FM
        * + Haugesund 434.7500 MHz DMR
        * + Meloy LE 145.2875 MHz FM
        * Grimstad ändrad till Grimstad I
        * + Bodo I 145.7500 MHz FM
        * + Nesna LI 433.9500 MHz FM
        * + Rodoy LI 145.3125 MHz FM
        * Verdal ändrad till Verdal 1
        * + Verdal 2 L 145.4500 MHz FM
        * + Oppdal 145.7750 MHz FM
        * + Skotterud L 144.6625 MHz FM
        * + Hokasen 145.7125 MHz FM
        * + Alvdalen 2 145.6000 MHz FM
        * + Torseterkampen 434.7500 MHz FM
        * + Notodden 434.9250 MHz FM
        * + Ralingen 434.8250 MHz FM
        * Drammen ändrad till Drammen 1
        * + Drammen 2 145.7250 MHz FM
        * + Drammen 3 434.7250 MHz FM
        * Kongsberg ändrad till Kongsberg 1
        * + Kongsberg 2 145.7000 MHz FM
        * + Kongsberg 3 434.6250 MHz FM
        * Notodden ändrad till Notodden 1
        * + Notodden 2 L 144.6750 MHz FM
        * + Larvik L 144.6500 MHz FM
        * + Oslo E 434.9750 MHz FM
        * + Vangsasen 434.7000 MHz DMR / D-Star / C4FM
        * Hokasen ändrad till Hokasen 1
        * + Hokasen 2 434.6500 MHz FM / C4FM
        * + Hokasen 3 434.5625 MHz FM / C4FM
        * + Eidsvoll 434.8750 MHz FM / C4FM
        * Follo ändrad till Follo 1
        * + Follo 2 145.7875 MHz FM / C4FM
        * + Fredrikstad 145.6875 MHz FM / C4FM
        * Fredrikstad ändrad till Fredrikstad 1
        * + Fredrikstad 2 434.7000 MHz FM / C4FM
        * + Kongsvinger 3 145.6500 MHz FM
        * + Sunnhordland 145.6250 MHz FM
        * + Kirkenes 145.7500 MHz FM
        * + Kristianstad 4 145.6000 MHz FM / C4FM
        * Mo\_i\_Rana ändrad till Mo\_i\_Rana 1
        * + Mo\_i\_Rana 2 E 145.6750 MHz FM
        * + Vesteralen 145.6000 MHz FM / C4FM
        * Tromso ändrad till Tromso 1
        * + Tromso 2 434.7500 MHz FM
        * + S.\_Sunnmore E 145.7250 MHz FM
        * + Tromso 3 145.6250 MHz FM
        * + Mo\_i\_Rana 3 LI 145.3375 MHz FM
        * Mosjoen ändrad till Mosjoen 1
        * + Mosjoen 2 LI 145.2875 MHz FM
        * + Fosen 434.6250 MHz FM
        * + Fredrikstad 3 L 145.2500 MHz FM
        * + Arendal 145.7000 MHz FM
        * + Bjerkreim 145.7125 MHz FM
        * + Harpefoss 145.7250 MHz FM
        * + Moss E 145.6625 MHz FM
        * + Risor 145.7750 MHz FM
        * + Gardermoen 145.7375 MHz FM
        * Ralingen ändrad till Ralingen 1
        * + Ralingen 2 E 145.7625 MHz FM
        * Oslo E ändrad till Oslo 1 E
        * + Oslo 2 434.7750 MHz FM / C4FM
        * + Oslo 3 145.6000 MHz FM
        * Bergen ändrad till Bergen 1
        * + Bergen 2 E 145.7500 MHz FM
        * Stavanger ändrad till Stavanger 1
        * + Stavanger 2 145.7750 MHz FM
        * Egersund ändrad till Egersund 1
        * + Egersund 2 145.7250 MHz FM / C4FM
        * Haugesund ändrad till Haugesund 1
        * + Haugesund 2 434.6750 MHz FM
        * + Bergen 3 145.7750 MHz FM
        * + Follo 3 434.7500 MHz DMR / D-Star / C4FM
        * + Sandefjord 434.8000 MHz FM
        * + Tonsberg 434.9500 MHz FM
        * + Kvelde 434.6750 MHz FM
        * + Holmestrand 434.6500 MHz FM / DMR
        * Sandefjord ändrad till Sandefjord 1
        * + Sandefjord 2 145.7500 MHz FM
        * Skien ändrad till Skien 1
        * + Skien 2 145.6500 MHz FM
        * + Horten 145.6250 MHz FM
        * + Gaustatoppen 145.6125 MHz FM
        * + Skien 3 434.6125 MHz FM / C4FM
        * + Barum 434.9250 MHz FM / DMR
        * + Hovassfjell 145.6000 MHz FM
        * + Nesodden 145.6750 MHz FM
        * + Kragero 434.8500 MHz FM
        * + Eirefjell 145.7125 MHz FM
        * + Skien 4 434.5875 MHz FM
        * + Tromso 4 145.7500 MHz FM
        * + Tromso 5 434.7250 MHz FM
        * - Aalgaard 434.95000 MHz 
        * - Aamot 434.70000 MHz 
        * - Aasbygda 434.81250 MHz 
        * - Bardufoss 434.65000 MHz 
        * - Bergen 1 434.82500 MHz 
        * - Bronnoysund 434.97500 MHz 
        * - Egersund 1 145.58750 MHz 
        * - Fauske 434.95000 MHz 
        * - Geilo 434.65000 MHz 
        * - Harstad 434.80000 MHz 
        * - Haueheia 145.16250 MHz 
        * - Hurdal 434.87500 MHz 
        * - Hvittingen 434.65000 MHz 
        * - Kolsas 434.92500 MHz 
        * - Kongsvinger 2 434.71250 MHz 
        * - Moi 434.86250 MHz 
        * - Narvik 434.75000 MHz 
        * - Oppegaard 434.75000 MHz 
        * - Raufoss 434.97500 MHz 
        * - Roverkollen 434.88750 MHz 
        * - Sarpsborg 434.81250 MHz 
        * - Stavanger 1 434.97500 MHz 
        * - Stokke 434.55000 MHz 
        * - Tromso 1 434.80000 MHz 
        * - Verdal 1 434.60000 MHz 
    * OH
        * Helsinki ändrad till Helsinki 1
        * Lohja ändrad till Lohja 1
        * Lahti ändrad till Lahti 1
        * Mikkeli ändrad till Mikkeli 1
        * Kotka ändrad till Kotka 1
        * Jyvaskyla ändrad till Jyvaskyla 1
        * Jamsa Himos ändrad till Jamsa 1 Himos
        * Kokkola ändrad till Kokkola 1
        * Porvoo ändrad till Porvoo 1
        * Vantaa ändrad till Vantaa 1
        * Lappeenranta ändrad till Lappeenranta 1
        * Kouvola ändrad till Kouvola 1
        * Ylivieska ändrad till Ylivieska 1
        * Kuusamo ändrad till Kuusamo 1
        * Espoo ändrad till Espoo 1
        * Hameenlinna ändrad till Hameenlinna 1
        * Tervola ändrad till Tervola 1
        * Tampere 2 ändrad till Tampere 2 F
        * Tampere 3 ändrad till Tampere 3 F
    * OH0
        * + Dalkarby 145.6750 MHz FM
        * + Jomala 434.5500 MHz DMR
    * OH1
        * + Salo 145.7000 MHz FM
        * + Turku 145.7750 MHz FM
        * + Kiukainen 145.7250 MHz FM
        * + Kankaanpaa 145.6250 MHz FM
        * + Kaarina 145.6500 MHz FM
        * + Uusikaupunki 434.8250 MHz FM
        * + Rauma 434.6750 MHz FM
        * + Kokemaki 434.6500 MHz FM
        * + Jamijarvi 434.9750 MHz FM
        * Salo ändrad till Salo 1
        * + Salo 2 434.7000 MHz FM
        * + Parainen 434.8500 MHz FM
        * + Koski 434.9250 MHz FM
    * OH2
        * + Loviisa 145.6000 MHz FM
        * + Helsinki 2 145.7500 MHz FM
        * + Lohja 2 145.6000 MHz FM
        * + Porvoo 2 434.8750 MHz FM
        * Loviisa ändrad till Loviisa 1
        * + Loviisa 2 434.7000 MHz FM
        * + Artjarvi 434.7750 MHz FM
        * + Vantaa 2 434.9000 MHz FM
        * + Jarvenpaa 434.6500 MHz FM
        * + Lohja 3 434.7250 MHz FM
        * + Espoo 2 145.7875 MHz FM
        * + Espoo 3 145.6250 MHz FM / P25
        * + Espoo 4 434.8250 MHz FM / P25
    * OH3
        * + Lahti 2 145.7750 MHz FM
        * + Erkyla 145.7250 MHz FM
        * + Vesijako 434.8000 MHz FM
        * + Riihimaki 434.6750 MHz FM
        * + Hameenlinna 2 145.6750 MHz FM
        * + Hameenlinna 3 434.6250 MHz FM
        * + Forssa 145.6500 MHz FM
        * + Lahti 3 434.6000 MHz FM / C4FM
        * + Tampere 4 145.7500 MHz FM
        * + Tampere 5 434.8500 MHz FM
    * OH4
        * + Mikkeli 2 145.7500 MHz FM
        * + Pieksamaki 434.8000 MHz FM
        * Pieksamaki ändrad till Pieksamaki 1
        * + Pieksamaki 2 145.6750 MHz FM
        * + Savonlinna 145.6250 MHz FM
    * OH5
        * + Kotka 2 145.6500 MHz FM
        * + Kuusankoski 145.7000 MHz FM
        * + Lappeenranta 2 434.7750 MHz FM
        * + Kouvola 2 434.8500 MHz FM
        * + Hamina 434.9250 MHz FM
        * + Joutseno 145.7750 MHz FM
    * OH6
        * + Narpio 145.7000 MHz FM
        * + Jyvaskyla 2 145.7000 MHz FM
        * + Jakobstad E 145.6250 MHz FM
        * + Jamsa 2 145.6000 MHz FM
        * + Kokkola 2 145.7000 MHz FM
        * + Jamsankoski 434.7000 MHz FM
        * + Seinajoki 434.6750 MHz FM / C4FM / D-Star
        * + Jyvaskyla 3 434.6500 MHz FM
        * + Kauhajoki 434.8750 MHz FM
        * + Teuva 434.9250 MHz FM
        * + Vaasa 434.7500 MHz FM
        * Narpio ändrad till Narpio 1
        * + Narpio 2 434.8000 MHz FM
        * + Jyvaskyla 4 434.7250 MHz FM
        * + Kokkola 3 434.8000 MHz FM
        * + Kaustinen 434.9000 MHz FM
        * Jakobstad E ändrad till Jakobstad 1 E
        * + Jakobstad 2 434.7000 MHz FM
        * + Saarijarvi F 434.5125 MHz DMR
        * Vaasa ändrad till Vaasa 1
        * + Vaasa 2 145.7500 MHz FM
        * + Pihtipudas 145.7750 MHz FM
        * Seinajoki ändrad till Seinajoki 1
        * + Seinajoki 2 145.6750 MHz FM / C4FM
        * + Lapua 145.6500 MHz FM
    * OH7
        * + Nurmes 145.6750 MHz FM
        * + Joensuu 145.7500 MHz FM
        * + Iisalmi 145.6500 MHz FM
        * Joensuu ändrad till Joensuu 1
        * + Joensuu 2 434.6500 MHz FM
        * Iisalmi ändrad till Iisalmi 1
        * + Iisalmi 2 434.7500 MHz FM
        * + Kuopio 145.6000 MHz FM
        * + Joensuu 3 145.7250 MHz FM
    * OH8
        * + Oulu 3 145.7500 MHz FM
        * + Nivala 145.6000 MHz FM
        * + Kajaani 145.7000 MHz FM
        * Kajaani ändrad till Kajaani 1
        * + Kajaani 2 434.6750 MHz FM
        * + Oulu 4 434.7500 MHz FM
        * + Pattijoki 434.9250 MHz FM
        * + Ylivieska 2 434.6000 MHz FM
        * + Kuusamo 2 434.7250 MHz FM
        * + Oulu 5 434.9750 MHz FM
    * OH9
        * + Kemijarvi 145.6500 MHz FM
        * + Rovaniemi 145.7000 MHz FM
        * Rovaniemi ändrad till Rovaniemi 1
        * + Rovaniemi 2 434.7000 MHz FM
        * + Kolari 145.6000 MHz FM
        * + Tervola 2 145.7750 MHz FM
        * + Tornio 434.7750 MHz FM
        * + Yllastunturi 434.6500 MHz FM
    * OZ
        * + Roret 145.7000 MHz FM
        * + Maribo 434.8250 MHz FM
        * + Vejle 434.9250 MHz FM
        * + Ringsted 434.6250 MHz FM
        * + Roskilde 434.8750 MHz FM
        * Frederikshavn ändrad till Frederikshavn 1
        * + Frederikshavn 2 434.9750 MHz FM
        * + Gilleleje 434.8500 MHz DMR
        * + Knivsbjerg 434.7250 MHz FM
        * + Eskebjerg 434.8000 MHz FM
        * + Vejrhoj 145.6000 MHz FM
        * + Hjorring 145.6125 MHz FM
        * + Vongshoj 145.6125 MHz FM
        * Herning ändrad till Herning 1
        * + Herning 2 145.6250 MHz FM
        * Ringsted ändrad till Ringsted 1
        * + Ringsted 2 145.6250 MHz FM
        * + Them 145.6375 MHz FM
        * + Odense 145.6500 MHz FM
        * + Esbjerg 145.6500 MHz FM
        * + Ostermarie 145.6500 MHz FM
        * + Bandholm 145.6500 MHz FM
        * + Randers 145.7250 MHz FM
        * + Hanstholm 145.7375 MHz FM
        * + Nykobing LI 433.5000 MHz FM
        * + Svendborg 145.7500 MHz FM
        * + Skive 145.7500 MHz FM
        * + Helsingor 145.6125 MHz FM / C4FM
        * + Hundborg 145.7875 MHz FM
        * Knivsbjerg ändrad till Knivsbjerg 1
        * + Knivsbjerg 2 145.7250 MHz FM
        * + Saby 145.7750 MHz FM
        * + Vissenbjerg 145.7000 MHz FM
        * Svendborg ändrad till Svendborg 1
        * + Svendborg 2 E 434.8750 MHz FM
        * Yding ändrad till Yding 1
        * + Yding 2 434.7500 MHz FM
        * + Yding 3 145.6750 MHz FM
        * + Dutterhoj 434.9250 MHz FM
        * + Grenaa 145.6625 MHz FM
        * + Vejby 145.7250 MHz FM
        * + Hobro 434.7250 MHz FM
        * + Skjoldbjerg 145.7375 MHz FM
        * + Vestjylland 145.6000 MHz FM
        * Helsingor ändrad till Helsingor 1
        * + Helsingor 2 434.6375 MHz DMR
        * + Aalborg 145.6500 MHz FM
        * Aalborg ändrad till Aalborg 1
        * + Aalborg 2 434.9625 MHz FM
        * + Vodskov 434.6750 MHz DMR
        * + Fredrikstad 4 434.6250 MHz DMR
        * + Frederikshavn 3 434.8250 MHz FM
        * + Aalborg 3 + 434.6875 MHz DMR
        * + Ringsted 3 434.8625 MHz FM
        * + Soerup 145.6875 MHz FM
        * + Ydby 145.7000 MHz FM
        * + Torphoej 145.7750 MHz FM
        * + Fredericia 145.7875 MHz FM
        * + Yding 4 434.5125 MHz DMR / D-Star
        * Esbjerg ändrad till Esbjerg 1
        * + Esbjerg 2 434.9625 MHz FM
        * + Fredrikstad 5 434.7125 MHz DMR
        * - Frederikshavn 1 434.71250 MHz 
        * - Herning 1 434.71250 MHz 
        * - Hillerod 434.68750 MHz 
        * - Naestved 434.60000 MHz 
        * - Skjern 434.77500 MHz 
        * - Yding 1 434.67500 MHz 
    * SM0
        * Sandhamn ändrad till Sandhamn L
        * Kopparmora ändrad till Kopparmora L
        * Taby 2 ändrad till Taby 2 I
        * Stockholm City ändrad till Stockholm
        * Tyreso ändrad till Tyreso +
        * + Kista 7 S 145.7875 MHz FM
        * + Hagsatra L 434.4250 MHz FM
        * + Haninge 5 434.5625 MHz DMR
        * Ingaro 2 S ändrad till Ingaro 2 E
        * Vastberga 1 ändrad till Vastberga 1 S
        * + Vallentuna 4 434.7000 MHz FM
        * - Brandbergen 434.56250 MHz 
        * - Ingaro 1 145.22500 MHz 
        * - Nynashamn 5 145.73750 MHz 
        * - Stockholm Norr S 145.78750 MHz 
        * - Tullinge 145.66250 MHz 
        * - Taby 1 434.70000 MHz 
    * SM2
        * Vannas 2 S ändrad till Vannas 2 SE
        * + Kalix-Vattentorn 434.7250 MHz FM / DMR
        * Kiruna 4 S ändrad till Kiruna 4 LS
        * - Kristineberg 145.67500 MHz 
    * SM3
        * Sundsvall 1 S ändrad till Sundsvall 1 SE
        * Ostersund 4 ändrad till Ostersund 4 E
        * Forsa 2 ändrad till Forsa 2 S
        * Krokom ändrad till Krokom L
        * + Forsa 4 145.6000 MHz FM
        * Osterfarnebo S ändrad till Osterfarnebo 1 S
        * + Osterfarnebo 2 S 434.8500 MHz FM
        * - Forsa 1 145.61250 MHz 
        * - Svedja S 145.60000 MHz 
        * - Areskutan 145.72500 MHz 
        * - Osterfarnebo 1 S 434.65000 MHz 
    * SM4
        * Filipstad 1 ändrad till Filipstad 1 L
        * Nyhammar ändrad till Nyhammar L
        * Grangesberg ändrad till Grangesberg L
        * Torsby 1 ändrad till Torsby 1 L
        * Orsa 1 ändrad till Orsa 1 E
        * Alvdalen S ändrad till Alvdalen 1 S
        * + Eksharad HI 433.2000 MHz DMR
        * Sunne 2 ändrad till Sunne 2 HI
        * Hagfors 2 ändrad till Hagfors 2 E
        * Leksand 2 ändrad till Leksand 2 I
        * Falun 1 S ändrad till Falun 1 SE
        * Malung ändrad till Malung H
        * Alvdalen 1 S ändrad till Alvdalen 1 LS
        * Nybble S ändrad till Nybble LS
        * Lindesberg 2 S ändrad till Lindesberg 2 LS
        * Orsa 3 S ändrad till Orsa 3 LS
        * + Karlstad S 145.5750 MHz FM
        * - Vansbro 2 434.65000 MHz 
    * SM5
        * Sala 1 ändrad till Sala 1 E
        * Uppsala 3 ändrad till Uppsala 3 H
        * Eskilstuna 2 S ändrad till Eskilstuna 2 SE
        * Atvidaberg S ändrad till Atvidaberg SE
        * Norrkoping 1 S ändrad till Norrkoping 1 LSE
        * + Finspang 3 434.7000 MHz DMR
        * Stigtomta ändrad till Stigtomta LF
        * Uppsala 8 S ändrad till Uppsala 8 LS
        * Uppsala 9 S ändrad till Uppsala 9 LS
        * - Eskilstuna 1 145.58750 MHz 
        * - Finspang 2 434.81250 MHz 
        * - Nykoping 1 145.47500 MHz 
    * SM6
        * + Guldheden 434.9750 MHz FM
        * Guldheden ändrad till Guldheden 1
        * + Guldheden 2 LE 144.5750 MHz FM
        * + Guldheden 3 434.7875 MHz DMR
        * + Guldheden 4 S 434.6500 MHz FM
        * + Guldheden 5 S 145.6500 MHz FM
        * + Guldheden 6 LE 144.6750 MHz FM
        * + Guldheden 7 434.6000 MHz FM / C4FM
        * + Orby 2 LA 434.2250 MHz FM
        * + Vargarda 434.8500 MHz FM
    * SM6 Gbg
        * Floda 1 ändrad till Floda 1 LI
        * Molndal 1 ändrad till Molndal 1 EI
        * Molndal 2 ändrad till Molndal 2 EI
        * Kortedala 1 ändrad till Kortedala 1 LE
        * Langedrag ändrad till Langedrag LE
        * Hono 1 ändrad till Hono 1 LE
        * Molnlycke ändrad till Molnlycke LE
        * Kungsbacka 1 ändrad till Kungsbacka 1 LE
        * - Goteborg 1 144.57500 MHz 
        * - Goteborg 2 144.67500 MHz 
        * - Goteborg 3 S 145.65000 MHz 
        * - Goteborg 4 S 434.65000 MHz 
        * - Goteborg 5 434.67500 MHz 
        * - Goteborg 6 434.78750 MHz 
        * - Goteborg 7 434.97500 MHz 
        * - Lunden 145.78750 MHz 
        * - Ytterby S 145.78750 MHz 
    * SM6 Ovriga
        * Mariestad ändrad till Mariestad E
        * Boras 4 S ändrad till Boras 4
        * Skarsjon ändrad till Skarsjon LE
        * Boras 1 ändrad till Boras 1 LE
        * Halmstad 1 ändrad till Halmstad 1 S
        * Skene 1 ändrad till Skene 1 EI
        * Skene 3 ändrad till Skene 3 EI
        * Skene 2 ändrad till Skene 2 HI
        * Stenungsund 2 S ändrad till Stenungsund 2 SE
        * Myggenas ändrad till Myggenas LE
        * Hjo S ändrad till Hjo LS
        * Orby S ändrad till Orby LSE
        * Orby LSE ändrad till Orby 1 LSE
        * - Falkenberg S 145.62500 MHz 
        * - Hajom S 145.40000 MHz 
        * - Istorp S 145.28750 MHz 
        * - Stenungsund 3 S 434.56250 MHz 
    * SM7
        * + Soderasen S 145.6500 MHz FM
        * + Olofstrom 2 I 434.7125 MHz DMR / D-Star
        * + Bredaryd 145.6875 MHz FM
        * Soderasen S ändrad till Soderasen 1 S
        * + Soderasen 2 434.6500 MHz FM / DMR
        * + Hillerstorp 434.6000 MHz FM
        * + Karlshamn 434.9250 MHz FM
        * + Farjestaden LSE 145.2375 MHz FM
        * + Borgholm 3 LS 145.3125 MHz FM
        * + Jonkoping 4 S 145.7000 MHz FM
        * + Sodra\_Vi 2 LAE 433.5000 MHz FM
        * + Hallandsas 2 S 434.6625 MHz FM
        * + Lonsboda 2 434.9500 MHz DMR / D-Star
    * SM7 Ovriga
        * Borgholm 1 S ändrad till Borgholm 1 SE
        * Morbylanga S ändrad till Morbylanga SE
        * Boda S ändrad till Boda SE
        * Olofstrom ändrad till Olofstrom 1
        * Olofstrom 1 ändrad till Olofstrom 1 E
        * Ljungby S ändrad till Ljungby SE
        * Vaxjo 1 S ändrad till Vaxjo 1 SE
        * Algutsrum 3 S ändrad till Algutsrum 3 SE
        * Solvesborg ändrad till Solvesborg L
        * Algutsrum 1 S ändrad till Algutsrum 1 SE
        * Algutsrum 2 ändrad till Algutsrum 2 I
        * Ekenassjon 1 ändrad till Ekenassjon 1 H
        * Linderod ändrad till Linderod I
        * Moheda S ändrad till Moheda SE
        * Borgholm 2 S ändrad till Borgholm 2 SE
        * Sodra\_Vi ändrad till Sodra\_Vi 1
        * - Aneby 1 145.77500 MHz 
        * - Aneby 2 434.72500 MHz 
        * - Aneby 3 434.92500 MHz 
        * - Linneryd S 145.40000 MHz 
        * - Svangsta 434.92500 MHz 
        * - Varnamo 2 434.60000 MHz 
    * SM7 Skane
        * Gladsax 1 ändrad till Gladsax 1 I
        * Hallandsas ändrad till Hallandsas S
        * Everod S ändrad till Everod LS
        * Malmo 1 ändrad till Malmo 1 I
        * Hallandsas S ändrad till Hallandsas 1 S
        * Lonsboda ändrad till Lonsboda 1
        * - Blentarp 1 145.67500 MHz 
        * - Eslov 1 434.70000 MHz 
        * - Helsingborg 1 S 145.65000 MHz 
        * - Helsingborg 3 434.65000 MHz 
        * - Hassleholm 145.76250 MHz 
        * - Lonsboda 1 434.90000 MHz 
    * TF
        * + Bruaras 145.7500 MHz FM
        * + Reykjavik 145.6000 MHz FM
        * Reykjavik ändrad till Reykjavik 1
        * + Reykjavik 2 145.6500 MHz FM
        * + Akureyri 145.6250 MHz FM
        * + Burfell 145.7000 MHz FM
  
codeplugadmin 1.0 (2025-04-28)

## 2025-03-22 (SM0RGM)

* Bytt namn på några repeatrar i OZ, LA och OH som har dubbelnamn för anpassning till namnstandard.

## 2025-03-09 (SM0RGM)

SM0RUX/Pontus är silent key. Tänk gärna på Cancerfonden tel. 010-199 10 10

## 2025-03-05 (SM0RGM)

* DigitalContactList uppdaterad och tvättad avseende internationella tecken (bl a åäö)

## 2025-02-01 (SM0RGM)

* RDT-filen uppdaterad för CPS och fw version 3.06.
* Digital Contact list uppdaterad. Denna innehåller DMR-id för Norden. Vill du ha ett annat urval behöver du själv generera en CSV-fil hos radioid.net.

## 2024-12-31 (SM0RGM)

* RDT-filen uppdaterad för CPS och fw version 3.05. Obs! I RDT-filen är det ytterligare ett ställe (Master Id) där du måste lägga in ditt DMR-ID, callsign och namn innan du skjuter i filen i din radio.

## 2024-10-04 (SM0RGM)

* RDT-filen uppdaterad för CPS version 3.04
* Ändrade kanaler per zon:
    * SM0
        * +Haninge 4 434.6375 MHz SK0NN-2

## 2024-04-29 (SM0RGM)

* Blentarp 1 ändrat scanlist till SM7 Skane
* 145.500 MHz tillagd i scanlistorna för SM0-SM7

## 2024-04-15 (SM0RGM)

* PMR1-16 och SRBR1-8 ändrade från Analog till A+D tx A för att kunna ta emot DMR.
* Ny Zone och ScanList "Diverse" för olika kanaler man vill lägga till som egna scankanaler. Egna kanaler läggs lämpligen från kanal 3900 och uppåt så blir det lätt att kopiera över dem när man uppdaterar till ny kodplug.
* RoamingChannel Aneby 3 bytt namn till Aneby 3/Sjobo och Sjobo borttagen (samma frekvens och CC)

## 2024-04-14 (SM0RGM)

* Roaming Channel Stockholm City borttagen ur Roaming Zone SM0 då repeatern saknar anslutning till Brandmeister. Om detta ändras är jag tacksam om sysop/admins för SK0RYG meddelar det så lägger jag in den igen.

## 2024-04-13 (SM0RGM)

* Kanallistorna omnumrerade för att underlätta bl a för synsvaga. Första siffran i kanalnumrets hundrasiffra motsvarar nu distriktssiffran:
    * 001-099: SM0
    * 100-199: SM1
    * 200-299: SM2
    * 300-399: SM3
    * 400-499: SM4
    * 500-599: SM5
    * 600-699: SM6
    * 700-799: SM7
    * 800-899: Norden d v s LA, OH, OZ mm
    * 900-919: Simplex
    * 921-936: PMR kanal 1-16
    * 940: 156.000 MHz
    * 941-948: SRBR kanal 1-8
    * 951-1019: LPD kanal 1-69
    * 1021-1027: Jakt kanal 1-7
    * 1101-1199: Marin VHF kanal 1-88, F1, F2, F3, L1, L2

## 2024-04-06 (SM0RGM)

* Brottby 2 434.800 FM 77 Hz subton

## 2024-04-05 (SM0RGM)

* Roamingchannel Bruzaholm -> Bzhlm/Hbg 2 samt Helsingborg 2 borttagen då dessa har samma frekvens och CC vilket innebär att roaming endast visar första träff (Bruzaholm).
* Roamingchannel Jonkoping 3 -> Jkp 3/O-ljunga då de har samma frekvens och CC samt Orkelljunga borttagen

## 2024-03-31 (SM0RGM)

* Ändrade kanaler per zon:
    * Marin VHF
        * +Marin-VHF 75 156.775 MHz
        * +Marin-VHF 76 156.825 MHz
 * Kanalnummer ändrade:
    * PMR-SRBR-LPD startar nu på kanal nr 501
    * Jakt startar nu på kanal 601
    * Marin-VHF startar nu på kanal 701, andra och tredjesiffran i kanalnumret motsvarar den marina kanalplanens kanalnummer. T ex VHF kanal 16 ligger på kanalplats 716.
    
## 2024-03-26 (SM0RGM)

* Optional settings -> Ranging interval(s) ändrat från 5s till 60s

## 2024-03-24 (SM0RGM)

* N0CALL.rdt nu sparad för MODE 0003 Amateur EU

## 2024-03-23 (SM0RGM)

* NOCALL.rdt fixad med avseende på roamingbug.
* Ändrade kanaler per zon:
    * SM0
        * -Hagsatra
        * Farsta namnbytt till Hogdalen och sorterad rätt i listan

## 2024-03-19 (SM0RGM)

* N0CALL.rdt komplett kodplugg för CPS/FW 3.03.

## 20214-02-24 (SM0RGM)

* Ändrade kanaler per zon:
    * PMR-SRBR
        * +156.000 MHz FM

## 2024-02-17 (SM0RGM)

* Ändrade kanaler per zon:
    * Simplex
        * +APRS 1 144.800 MHz FM
        * +APRS 2 432.500 MHz FM
        * +APRS US 144.390 MHz FM
        * +145.450 MHz FM
    * SM0
        * Ingaro 1 CTCSS decode off
        * +Sandhamn 434.375 
        * Kista 3 nu SVX
        * Stockolm 2 nu SVX
        * Stockholm Norr nu SVX
        * Sodertalje 4 434.6870 -> 434.8750
        * -Skarpnack 145.700
        * -Kista 434.6625
        * -Galo 434.6875
        * -Haninge 4 434.5375
    * SM2
        * Vannas 2 nu SVX
        * Storuman 2 nu SVX
        * Skelleftea 2 nu D+A
        * -Lycksele 1 QRT
        * -Lycksele 2 QRT
        * -Nordmailing QRT
    * SM3
        * +Areskutan 145.725
        * -Soderhamn 1 145.575
        * -Soderhamn 3 434.525
        * -Vemdalen 145.625 QRT
        * Ostersund 2 nu SVX
    * SM4
        * Orsa 2 nu SVX 
        * Alvdalen S 145.250 -> 434.500
        * +Orsa 3 S 145.275
        * +Smedjebacken 434.6375
        * -Hagfors 1 145.225
        * -Leksand 1 145.5875 DMR
    * SM5
        * Kisa nu CTCSS 82.5 Hz
        * Eskilstuna 3 nu SVX
        * Uppsala 1 nu SVX -DMR
        * Eskilstuna 2 nu SVX
        * Atvidaberg nu SVX
        * Norrkoping 1 nu SVX
        * +Norrkoping 5 434.6625 FM
        * Flen 2 145.7625 +CTCSS 103.5
        * -Sala 2 434.9375 QRT
        * -Uppsala 7 434.7500 QRT
        * -Vasteras 2 434.7000 QRT
    * SM6 Gbg
        * +Molndal 1 145.700 FM
        * +Molndal 2 434.700 FM
    * SM6 Ovriga
        * Skovde 1 145.6875 FM korrigerat felaktig tx frekvens
        * Uddevsalla 1 S nu 145.7375 DMR FM
        * +Orby S 145.2375 MHz FM SVX
        * +Karlsborg 145.7625 FM
        * +Dingle 434.8875 DMR
    * SM7 Ovriga
        * Varnamo 1 CTCSS decode off
        * -Morrum 434.825 FM QRT
        * -Farjestaden S 145.2375 FM QRT
        * Ljungby S +SVX +CTCSS 94.8 Hz
        * Hoor -CTCSS 79.7 Hz
        * +Moheda S 145.6375 MHz SVX
        * +Malmo 1 434.6125 MHz DMR
        * Malmo -> Malmo 2 434.7750 MHz DMR
        * Borgholm S -> Borgholm 1 S 145.6625 MHz FM
        * +Borgholm 2 S 434.7750 MHz FM SVX
        * -Spjutsbygd 2 434.8750 MHz FM
* APRS-frekvens 1-4 144.800 MHz och 5-8 432.500 MHz
        
## 2023-08-21 (SM0RGM)

* Ändrade kanaler per zon:
    * SM0
        * Kista 1 -> Farsta 145.575 DMR

## 2023-06-24 (SM0RGM)

* Lagt till APRS UHF-frekvens (432.500 MHz), ändrat Transmit Delay till 600 ms och Prewave Time till 200 ms, ändrat manuell APRS TX till 60s, auto APRS TX 180s, samt 15s visning av mottagen APRS. APRS TX skall vara FM narrow (12 kHz) enligt IARU region 1 bandplan: https://www.iaru-r1.org/wp-content/uploads/2020/12/VHF-Bandplan.pdf

## 2023-06-16 (SM0RGM)

* Ändrat APRS SSID till -7 som skall användas för handapparater
* Lagt in 144.800 MHz på alla 8 frekvensalternativ för APRS för att förhindra att man sänder utanför amatörradiobanden av misstag
* Analog APRS, ändrat Transmit delay och Prewave time till 600 ms. Annars fungerar inte analog APRS, källa: https://www.reddit.com/r/AnyTone/comments/han0y5/aprs\_problems\_the\_solution\_anytone\_atd878uv/

## 2023-04-10 (SM0RGM)

* Lagt till TG 98 Radio Test för att kunna ställa mic gain. Kontrollera nivån genom att samtidigt lyssna och se VU-mätaren på TG 98 via https://hose.brandmeister.network.

## 2023-04-09 (SM0RGM)

* Talgrupp 240721 rättat TG nummer och bytt benämning till SK7RFL

## 2023-04-08 (SM0RGM)

* Ändrat HS DMR default TG till Regional SM0
* Lagt till importlista för Anytone AT-D868

## 2023-04-07 (SM0RGM)

* Ingen scanlista var förvald för PMR-SRBR, fixat.
* LPD-kanaler tillagda i PMR-SRBR och zonen namnändrad till PMR-SRBR-LPD. Ingen scanlista är gjord för LPD eftersom de inte får plats i en lista.
* Ändrat squelch type till CTCSS/DCS på alla kanaler som har subton

## 2023-04-06 (SM0RGM)

* Samtliga Analoga, A/D- och D/A-kanaler som har CTCSS ENCODE har fått CTCSS DECODE, d v s tone squelch för att underlätta vid scanning.
* Repeatrar ansluta till svxlink märkta med "S" i kanalnamnet
* Ändrade, tillagda och borttagna kanaler per zon:
    * Simplex
        * +HS DMR 434.475 MHz, CC1, TS2 (avsedd för hotspot)
    * SM0
        * -Botkyrka 1 DMR
        * +Stockholm 1 FM
        * -Varmdo borttagen ur roaming zone då den saknar anslutning till BM
        * +Haninge 4 434.5375 FM
        * +Skarpnäck 145.7000 FM
        * Sigtuna bytt subton till 123.0 Hz
        * +Nynäshamn 5 145.7375 FM
        * +Nynäshamn 6 434.9125 FM
        * Vallentuna bytt till Vallentuna 1
        * +Vallentuna 2 434.5500 DMR
        * +Sodertalje 4 434.6375 DMR
        * -Sandhamn 434.3750 FM
        * -Stockholm 3 433.4000 DMR
        * -Sodertalje 1 145.7000 FM
        * -Toro 145.7375 FM
    * SM2
        * +Storuman 1 145.7250 FM
        * -Jorn 145.7500 FM
        * +Storuman 2 434.7500 FM
        * Skelleftea bytt till Skelleftea 1
        * +Skelleftea 2 145.5875 FM
        * +Skelleftea 3 SVX 434.6750 FM
        * +Kiruna 4 SVX 434.4000 FM
        * +Burtrask SVX 434.9500 FM
    * SM3
        * Gavle 1 bytt från 434.7375 till 434.7000 DMR
        * -Bollnas 3 434.5500 DMR 
        * -Bollnas 1 145.5875 DMR
        * -Sundsvall 2 434.5375 DMR
        * Solleftea bytt till Solleftea 1
        * +Solleftea 2 434.9250 FM
        * +Svedja SVX 145.6000 FM (SK3RQE)
        * Osterfarnebo 145.5500 FM bytt till Osterfarnebo SVX 434.6500 FM
        * -Sandviken 2 434.7000 FM
    * SM4
        * Mora 3 434.8500 -> 434.7000 FM
        * Vansbro 1 + 2 lagt till 85.4 Hz subton
        * Karlskoga 2 434.850 -> 434.8000 FM/DMR
        * Falun 2 rättad fr 145.6250 till 434.6250 DMR
        * Malung 434.8500 -> 144.8375 DMR
        * +Salen SVX 145.6000 FM
        * +Alvdalen SVX 145.2500 FM
        * Lindesberg bytt till Lindesberg 1
        * +Lindesberg 2 SVX 145.3000 FM
        * -Filipstad 2 145.7000 FM
        * -Kopparberg 2 434.6375 DMR
        * -Kristinehamn 434.9250 FM
        * -Mora 1 145.7000 FM
        * -Mora 2 434.6750 FM
    * SM5
        * +Motala 145.7375 FM
        * Norrköping 3 434.6000 FM lagt till subton 82.5 Hz SVX
        * Västerås 1 nu SVX
        * Linköping 3 nu SVX
        * Linköping 1 lagt subton 82.5 Hz
        * Flen 2 nu Flen 3 SVX
        * Finspang nu Finspang 1
        * +Finspang 2 434.8125 DMR
        * Nykoping nu Nykoping 1
        * +Nykoping 2 434.6375 DMR
        * Stigtomta bytt från FM till DMR
        * Sala nu Sala 1
        * +Sala 2 434.9375 DMR
        * +Uppsala 8 SVX 144.5750 FM
        * +Uppsala 9 SVX 433.4500 FM
        * +Flen 2 145.7625 FM
    * SM6
        * Boras 4 nu SVX
        * -Molndal 1 145.7000 FM
        * -Molndal 2 434.7000 FM
        * Alingsas 4 nu SVX
        * Bengsfors 1 korrigerad till Bengtsfors 1
        * Bengsfors 2 korrigerad till Bengtsfors 2 samt subton korrigerad till 114.8 Hz
        * Bokenas nu SVX
        * Lysekil nu SVX
        * Tanumshede nu SVX
        * Falkenberg nu SVX
        * Stenungsund 2 nu SVX
        * Goteborg 4 nu SVX
        * Goteborg 3 nu SVX
        * Kungshamn nu SVX
        * Hono 2 145.7500 FM nu Ockero 1 SVX 145.7500 FM
        * Hono 3 434.8500 DMR nu Ockero 2 434.8500 DMR
        * +Stenungsund 3 SVX 434.5625 FM/DMR
        * Ytterby nu SVX och subton 218.1 Hz samt bytt från DMR till FM
        * Uddevalla nu SVX
        * Skara 434.9875 FM/DMR bytt till Skara 3
        * +Skara 1 145.7250 FM
        * Trollhattan 2 bytt till Trollhattan 3 434.8750 FM/DMR
        * +Trollhattan 2 434.7250 FM
        * +Skara 2 434.5625 FM
        * +Torup SVX 434.8875 FM
        * +Hjo SVX 145.2375 FM
        * +Hajom SVX 145.4000 FM
        * +Istorp SVX 145.2875 FM
        * Uddevalla 1 145.6375 FM/DMR bytt till Uddevalla 1 SVX 145.7375 FM/DMR
        * -Lidkoping 145.3000 FM
        * -Aleklatten 144.6125 FM
        * -Alingsas 1 144.6125 FM
        * -Falkoping 145.7250 FM
        * -Landvetter 144.5625 FM
        * -Sloinge 145.7375 FM/DMR
        * -Stenungsund 1 145.6875 FM
        * -Torestorp 144.6625 FM
        * -Vastra Frolunda 144.5375 FM
        * -Orby 434.2250 FM
    * SM7
        * +Sjobo 434.9250 DMR
        * Eslov 1 434.7500 FM bytt till Eslov 1 434.7000 FM
        * Helsingborg 1 nu SVX
        * Borgholm nu SVX och subton 79.7 Hz
        * Morbylanga nu SVX och subton 79.7 Hz
        * Boda nu SVX och subton 79.7 Hz
        * Gladsax bytt till Gladsax 2
        * +Gladsax 1 145.5750 DMR
        * Kristianstad 1 nu SVX
        * Blentarp bytt till Blentarp 2
        * +Blentarp 1 145.6750 FM
        * Olofstrom korrigerad från 440.0000 till 145.7000 FM
        * -Gnosjo 145.6875 FM
        * Vaxjo 1 nu SVX
        * Huskvarna nu med subton 156.7 Hz
        * Algutsrum 3 nu SVX
        * Aneby 1 nu med subton 156.7 Hz
        * Vastervik 1 nu med subton 77.0 Hz
        * +Savsjo 434.5250 DMR
        * Sodra Vi 434.6625 bytt från FM till DMR
        * Algutsrum 1 nu SVX
        * Ekenassjon bytt till Ekenassjon 1
        * +Ekenassjon 2 145.7125 FM/DMR
        * Emmaboda bytt till Emmaboda 1
        * +Emmaboda 2 434.7875 DMR
        * Spjutsbygd 1 nu SVX
        * +Linneryd SVX 145.4000 FM
        * +Linderod 145.5875 DMR
        * +Everod SVX 145.2375 FM
        * +Farjestaden SVX 145.2375 FM
        * -Jonkoping 1 145.4000 FM
    * Marin-VHF
        * Innehåller nu samtliga marin-VHF-kanaler
    * OZ
        * Hilolerod (typo) korrigerad till Hillerod
    * Jakt
        * Skapat kanaler, zon och scanlista för Jakt-01 till Jakt-07

* Talgrupper; 240216 Swedenhubb ändrat till 240216 Sweden-hub

* TODO:
    * LA, OH, OZ är inte uppdaterade
    * Skall benämningarna i framtiden ha förkortningar, t ex R = Repeater, L = simplexlänk, S = svxlinknod, E = echolinknod? Kom med synpunkter!

## 2023-03-25 (SM0RGM)

* Ändrade APRS TOCALL till APAT81 enligt [issue 27 rapporterat av SM6VFJ](https://github.com/sm0rux/at-d878uv/issues/27) 


