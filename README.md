# Projekta darbs

### Projekta ideja:

Es ziemas periodā regulāri nodarbojos ar ziemas aktīvo sportu ( braukšanu ar sniega dēli vai slēpošanu ) un vajadzīgo inventāru nomāju. Mana projekta ideja radās no vēlmes saprast cik viena mēneša laikā es samaksāju par nomātu inventāru, lai saprastu vai izdevīgāk to būtu iegādāties pašai. Kā arī, intereses pēc, saprast cik ilgu laiku konkrētā mēnesī es pavadu nodarbojoties ar šo sportu. 

### Programmas uzdevums:

Ziemas sporta veidu inventāra nomas uzņēmumam ir trīs faili. inventars.pdf ir skrejlapa, kura tiek izsūtīta klientiem un tajā atrodas informācija par nomas izcenojumu ( inventāra nosaukums, cena ). klienti.csv ir fails, kas satur informāciju par katru klientu ( unikālo kodu, vārdu un uzvārdu ). noma1.xlsx ir nomāšanas fails, kas satur informāciju par nomu vienā mēnesi ( unikālais kods, nomāšanas ilgums, iznomātais inventārs ).

#### Ievaddati:

Programmas sākumā jāievada patstāvīgā klienta vārds un uzvārds. 

Shakira Irwin, 
Aliza Rodgers, 
Pippa Lynn, 
Sadie Hoover, 
Brenda Sheppard, 
Melody Shaw, 
Cory Brewer, 
Donna Andrade, 
Kasey Terry, 
May Mack, 
Keisha Snow, 
Veronica Clarke, 
...

#### Izvaddati:

Programmai jāizvvada kopējā summa ko ievadītais klients ir samaksājis iznomājot inventāru ( piem. 60.10€ ) un laiku cik ilgi šomēness inventārs ir tikts nomāts uzskatāmā veidā ( 10:20:02 ).

#### Izpilde:

No inventars.pdf jāizgūst inventāra nosaukums un tā cena, ierakstot to masīvā. No klienti.csv jāizgūst klienta vārds un uzvārds, kā arī unikālais kods, ierakstot to masīvā. ( Unikālais kods izmantots klienta datu drošībai, failā noma1.xlsx ir izmantoti tieši šie unikālie kodi nevis klientu dati ). No noma1.xlsx ir jāizgūst unikālie kodi, nomas ilgums un inventārs arī ierakstot to masīvā.

Lietotājam jānodrošina vārda un uzvārda ievadīšana. Kad tas izdarīts, klienti.csv datu masīvā jaātrod šis vārds un uzvārds un jāiegūst attiecīgā cilvēka unikālais kods. Tālāk šis kods jasalīdzina ar noma1.xlsx datnu masīvu un jāatrod katra reize kad klients ir ko nomājis ( šīs reizes patstāvīgajiem klientiem atkārtojas ) un jāsaglabā katras nomas ilgums un kāds inventārs ir ticis nomāts. Tālāk no inventars.pdf datu masīva jāatrod šie nomātie inventāri un tā cena par 60 min. Uzņēmuma polise ir ka, ja konkrēts stundu skaits ir pārsniegts par minūtēm, tad tiek atsevišķi rēķināta cena 1 min ( maksa par 1 h/60 = maksa par 1 min). Jāaprēķina cik klients ir samaksājis par katru no inventāra nomāšanas reizēm un jāsaskaita kopā laiks, cik ilgi invnentārs ir nomāts. Laiks jāizvada uzskatāmā veidā.  

### Izmantotās Python bibliotēkas:

PyPDF2: Python bibliotēka, kas ļauj darboties ar PDF failiem. Šī bibliotēka piedāvā funkcijas, lai apvienotu, sadalītu un rediģētu PDF failus, kā arī izgūtu informāciju no PDF dokumentiem. Savā projektā es automātiski ieguvu tekstu no inventars.pdf faila programmēšanas veidā. 


