# Vaja11-LCD2x16-STM32F0

ODGOVORI NA VPRAŠANJA

2.b) Za RS in E priključka na LCD zaslonu izberite in aktivirajte ustrezna pina ___PB11___ in ___PB12___ kot GPIO_Output
(SAMO pini PB11, PB12, PB13, PA11, PC7 in PC6 so 5V tolerant). Pine tudi ustrezno preimenujte v RS in E 
(desni klik na pin in izberite Enter User Labe…l). Tudi za priključke D4 do D7 na LCD zaslonu aktivirajte 4
ustrezne pine _PB13__, __PC6_, _PC7__ in _PC8__ kot GPIO_Output. 

2.e) V Clock Configuration spremenite frekvenco na vrednost, da bo polovica najvišje možne: Nova frekvenca 
bo ___84___ MHz. 

2.f) V zavihku Pinout & Configuration pod rubriku System Core kliknite gumb GPIO. Kakšna je nastavljena 
hitrost podatkov na vodilih (max. output speed) ? __LOW___

3.h) Kakšne so min ter max vrednosti za x in y za vaš LCD zaslon? 
--> 0-16 za x
--> 0-2 za y

3.h) Kaj počne funkcija itoa?
--> Spremeni int v string

3.h) Zakaj jo moramo uporabiti?
--> Z TM_HD44780_PUT sprejme string in ga zato moramo spremeniti v številke.

3.h) Kaj pomeni tretji argument v tej funkciji?
--> Z zadnjo vrednostjo spremnimo število v heksadecimalno, desetiško, oktodecimalno, binarno.

KOMENTAR NA DELOVANJE --> Kodo nama ni uspelo zapisati do konca, zmanjkalo nama je časa. 
Ni nama uspelo premikati besed na LCD-ju. 

![Video]()
![Slika mikroprocesorja]()
![Slika LCD]()
![Slika vezave]()
