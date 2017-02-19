Boto Komandos:
=========

X - skaičius  
Priedai tarp ( ) yra nebūtini


Vadovas / Manager
-------

|Komanda | Argumentas |  Aprašymas |
|:------:|:---------:|:--------------------------------------:|
|!autoroulette | | Įjungia automatinę ruletę |
|!afklimit | X | Nustato maksimalų laiką, kurio metu vartotojas gali nebalsuoti už dainas |
|!botname | (vardas) | Pakeičia boto vardą |
|!bouncer+ | | Įjungia bouncer+ papildinį |
|!skippos | X | Nustato vietą waitlist`e į kurią bus perkelti žmonės panaudojus skippos arba lockskip komandas |
|!clearchat | | Išvalo chat`ą |
|!cycle | | Įjungia DJ ciklą |
|!cycletimer | X | Nustato ilgiausią DJ ciklo laiką, kai ciklo apsauga yra įjungta |
|!language | (kalba) | Nustato boto kalbą |
|!locktimer | X | Nustato ilgiasią laiko tarpą kurio metu waitlist`as gali būti užrakintas  |
|!maxlength | X | Nustato ilgiausią dainos trukmę |
|!logout | | Išregistruoja boto paleidėjo paskyrą |
|!refresh | | Boto perkrovimas |
|!usercmdcd | X | Nustato komandų panaudojimo intervalą pilkiems vartotojiems |
|!usercommands | | Įjungia vartotojų komandas |
|!voteskip | (X) | Jei argumentas nenurodytas, parodo dabartinį nustatymą, jei X įvestas, voteskip limitas yra atnaujinamas. |


Apsauginis / Bouncer
-------

|Komanda | Argumentas |  Aprašymas |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | Parodo kiek vartotojų rašė žinutes per pastarasiąs X minutes. Jei X nenurodytas, rodoma paskutinės valandos statistika |
|!add | @vartotojas | pridėti vartotoją į waitlistą |
|!afkremoval | | įjungti afk vartotojų patikrinimą |
|!afkreset | @vartotojas | Atstato vartotojo afk laiką |
|!afktime | @vartotojas | Parodo kiek laiko vartotojas nedalyvavo chate |
|!autoskip | | praskipina dainas po to, kai jos baigia groti (naudoti kai dainos pačios nepersijungia) |
|!autodisable | | Įjungti autodisable komandą, kuri išjungia botą po tam tikro laiko |
|!ban | @vartotojas | Užblokuoja vartotoją 1 dienai |
|!blacklist / !bl | sąrašo pavadinimas | Įtraukią dainą į draudžiamų dainų sąrašą |
|!commanddeletion | | Įjungia boto komandų trynimą |
|!blinfo | | Pateikia informaciją apie dainą |
|!cycleguard | | Įjungia ciklo apsaugą |
|!dclookup / !dc | (@vartotojas) | Parodo vartoto pozicija iki atsijungimo |
|!deletechat | @vartotojas | išvalo visas žinutes parašytas nurodyto vartotojo |
|!english | @vartotojas | Paprašo vartotojo kalbėti angliškai (prašoma ta kalba kurią vartotojas nusistatęs) |
|!eta | (@vartotojas) | Nurodo laiką iki grojimo |
|!filter | | Įjungią chato apsaugą |
|!forceskip | | Praleidžia dabartinę dainą |
|!historyskip | | Įjungia pasikartojančių dainų praleidimą |
|!jointime | @vartotojas | Parodo kiek laiko vartotojas praleido kambaryje neatsijungęs |
|!kick | (X) | Išmeta vartotoją iš kambario X minutėms, numatyta reikšmė yra 15 sekundžių (0.25 minutės) |
|!kill | | Išjungia botą |
|!lock | | užrakina waitlistą |
|!lockdown | | užrakina chatą, tik valdžia gali rašyti |
|!lockguard | | Įjungia lockguard |
|!lockskip | (priežastis) | Praleidžią dainą, užrakiną waitlistą ir grąžina vartotoją į tam tikrą poziciją (pozicija nustatoma su !skippos komanda) |
|!motd | (X)/(žinutė) | Jei argumentas nenurodytas, parodo dabartinę nustatytą žinute, kai X nurodytas, dienos žinutė yra rodoma kas X dainas, jei "žinutė" nurodyta, dienos žinutė pakeičiama |
|!move | @vartotojas (X) | perkelia vartotoją į nurodytą poziciją, nieko nenurodžius perkeliama į 1 vietą |
|!mute | @vartotojas/(X) | Uždraudžia rašyti vartotojui, X minutėms jei X nurodytas, kitu atveju neribotam laikui |
|!reload | | Perkrauna botą |
|!remove | @vartotojas | pašalina vartotoją iš waitlisto |
|!restricteta | | Įjungi eta komandos apribojimą: pilki vartotojai komandą gali vartoti kas valandą |
|~~!roulette~~ | | ~~paleidžia ruletę~~ |
|!sessionstats | | Parodo dabartinės sesijos būseną |
|!skip | (priežastis) | Praleidžia dainą bei parašo priežastį vartotojui |
|!songstats | | įjungia dainų statistiką |
|!status | | Parodo boto informacija bei keletą nustatymų |
|!timeguard | | Įjungia dainos trukmės limitą |
|!togglebl | | Įjungia draudžiamajį sąrašą |
|!togglemotd | | Įjungia dienos žinutę |
|!togglevoteskip | | Įjungia voteskip komandą, kuri skaičiuoja balsus reikalingus pakeisti dainai |
|!unban | @vartotojas | Atblokuja vartotoją |
|!unlock | | atrakina waitlistą |
|!unmute | @vartotojas/all | Leidžia vartotojui vėl rašyti |
|!voteratio | @vartotojas | Parodo vartotojo balsavimo už dainas statistiką |
|!welcome | | įjungia pasisveikinimo žinutę |
|!whois | @vartotojas | Parodo informaciją apie vartotoją |

Nuolatinis DJ / RDJ
-----------

|Komanda | Argumentas |  Aprašymas |
|:------:|:---------:|:--------------------------------------:|
|!link | | Nurodo dabartinės dainos nuorodą



Vartotojas / User
----

|Komanda | Argumentas |  Aprašymas |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (žinutė) | Paklausia boto klausimo į kurį atsakymas būtų taip arba ne, botas parenka atsitiktinį atsakymą |
|!autowoot | | Nurodo autowoot boto nuorodą |
|!ba | | Paaiškina kas tai yra Brand Ambassador |
|!commands | | Išmeta visų komandų linką |
|!cookie | (@vartotojas) | Duoda vartotojui sausainį |
|!dclookup / !dc | | Parodo vietą, kurioje buvote prieš atsijungdami |
|!emoji | | Nurodo emoji jaustukų adresą |
|!eta | | Nurodo po kiek laiko grosite savo pasirinktą dainą |
|!fb | | Nurodo kambario facebook adresą (jei nustatytas) |
|!gif | (kategorija) | Išmeta gif pagal nurodytą kategoriją, jeigu kategorija nenurodyta išrekama atsitiktinai |
|!help | | Nurodo vartotojų komandų sąrašą |
|!play | | Dalyvauti ruletės žaidime jei ji paleista |
|!leave | | Palikti ruletės žaidimą |
|!op | | Nurodo pasikartojančių dainų sąrašo adresą (jei nustatytas) |
|!ping | | Pong! |
|!purchase | | Nurodo plug taškų pirkimo adresą |
|!rules | | Nurodo kambario taisyklių adresą (jei nustatytas) |
|!theme | | Nurodo kambario dainų temą (jei nustatyta) |
|!website | | Nurodo kambario svetainės adresą (jei nustatytas |
|!youtube | | Nurodo kambario youtube kanalo adresą (jei nustatytas) |
