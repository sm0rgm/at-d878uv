
# Changelog

## 2023-04-02 (SM0RGM)

* Samtliga A/D och D/A kanaler har fått som har CTCSS ENCODE har fått CTCSS DECODE, d v s tone squelch för att underlätta vid scanning.
* Repeatrar ansluta till svxlink märkta med "SVX"
* Ändrade, tillagda och borttagna kanaler per zon:
    * Simplex
        * +Hotspot ("HS") 434.475 MHz, CC1, TS2
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
        * Nykoping ny Nykoping 1
        * +Nykoping2 434.6375 DMR
        * Stigtomta bytt från FM till DMR
        * Sala nu Sala 1
        * +Sala 2 434.9375 DMR
        * +Uppsala 8 SVX 144.5750 FM
        * +Uppsala 9 SVX 433.4500 FM
        * +Flen 2 145.7625 FM
    * Marin-VHF
        * Innehåller nu samtliga marin-VHF-kanaler

* Receive Group Call; 240216 Swedenhubb ändrat till 240216 Sweden-hub

* TODO:
    * Scanlist SM0 mer max 50, dela upp i två?
    * Komplett kanaltabell för Marin-VHF
    * LA, OH, OZ är inte uppdaterade

## 2023-03-25 (SM0RGM)

* Ändrade APRS TOCALL till APAT81 enligt [issue 27 rapporterat av SM6VFJ](https://github.com/sm0rux/at-d878uv/issues/27) 


