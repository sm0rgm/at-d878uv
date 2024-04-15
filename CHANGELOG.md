
# Changelog

## 2024-04-15 (SM0RGM)

* PMR1-16 och SRBR1-8 ändrade från Analog till A+D tx A för att kunna ta emot DMR.
* Ny Zone och ScanList "Diverse" för olika kanaler man vill lägga till som egna scankanaler. Egna kanaler läggs lämpligen från kanal 3900 och uppåt så blir det lätt att kopiera över dem när man uppdaterar till ny kodplug.

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
* Analog APRS, ändrat Transmit delay och Prewave time till 600 ms. Annars fungerar inte analog APRS, källa: https://www.reddit.com/r/AnyTone/comments/han0y5/aprs_problems_the_solution_anytone_atd878uv/

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


