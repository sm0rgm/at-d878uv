
# Changelog

## 2023-04-07 (SM0RGM)

* Ingen scanlista var förvald för PMR-SRBR, fixat.
* LPD-kanaler tillagda i PMR-SRBR och zonen namnändrad till PMR-SRBR-LPD. Ingen scanlista är gjord för LPD eftersom de inte får plats i en lista.
* Ändrat squelch type till CTCSS/DCS på alla kanler som har subton

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


