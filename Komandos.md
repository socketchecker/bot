Boto Komandos:
=========

X - skaičius  
Priedai tarp ( ) yra nebūtini


Manager
-------

|Komanda | Argumentas |  Aprašmas |
|:------:|:---------:|:--------------------------------------:|
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


Bouncer
-------

|Komanda | Argumentas |  Aprašmas |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | Parodo kiek vartotojų rašė žinutes per pastarasiąs X minutes. Jei X nenurodytas, rodoma paskutinės valandos statistika |
|!afkreset | @vartotojas | Atstato vartotojo afk laiką |
|!afktime | @vartotojas | Parodo kiek laiko vartotojas nedalyvavo chat`e |
|!autodisable | | Įjungti autodisable komandą, kuri išjungia botą po tam tikro laiko |
|!ban | @vartotojas | Užblokuoja vartotoją 1 dienai |
|!blacklist / !bl | sąrašo pavadinimas | Įtraukią dainą į draudžiamų dainų sąrašą |
|!commanddeletion | | Įjungia boto komandų trynimą |
|!blinfo | | Pateikia informaciją apie dainą |
|!cycleguard | | Įjungia ciklo apsaugą |
|!dclookup / !dc | (@vartotojas) | Parodo vartoto pozicija iki atsijungimo |
|!english | @vartotojas | Paprašo vartotojo kalbėti angliškai (prašoma ta kalba kurią vartotojas nusistatęs) |
|!eta | (@vartotojas) | Nurodo laiką iki grojimo |
|!filter | | Įjungią chat`o apsaugą |
|!forceskip | | Praleidžia dabartinę dainą |
|!historyskip | | Įjungia pasikartojančių dainų praleidimą |
|!jointime | @user | Parodo kiek laiko vartotojas praleido kambaryje neatsijungęs |
|!kick | (X) | išmeta vartotoją iš kambario X minutėms, numatyta reikšmė yra 15 sekundžių (0.25 minutės) |
|!kill | | Išjungia botą |
|!lockguard | | Įjungia lockguard |
|!lockskip | (priežastis) | praleidžią dainą, užrakiną waitlist`ą ir grąžina vartotoją į tam tikrą poziciją (pozicija nustatoma su !skippos komanda) |
|!motd | (X)/(žinutė) | jei argumentas nenurodytas, parodo dabartinę nustatytą žinute, kai X nurodytas, dienos žinutė yra rodoma kas X dainas, jei "žinutė" nurodyta, dienos žinutė pakeičiama |
|!mute | @vartotojas/(X) | Uždraudžia rašyti vartotojui, X minutėms jei X nurodytas, kitu atveju neribotam laikui |
|!reload | | Perkrauna botą |
|!restricteta | | Įjungi eta komandos apribojimą: pilki vartotojai komandą gali vartoti kas valandą |
|!sessionstats | | Parodo dabartinės sesijos būseną |
|!skip | (priežastis) | Praleidžia dainą bei parašo priežastį vartotojui |
|!status | | Parodo boto informacija bei keletą nustatymų |
|!timeguard | | Įjungia dainos trukmės limitą |
|!togglebl | | Įjungia draudžiamajį sąrašą |
|!togglemotd | | Įjungia dienos žinutę |
|!togglevoteskip | | Įjungia voteskip komandą, kuri skaičiuoja balsus reikalingus pakeisti dainai |
|!unban | @vartotojas | Atblokuja vartotoją |
|!unmute | @vartotojas/all | Leidžia vartotojui vėl rašyti |
|!voteratio | @vartotojas | Parodo vartotojo balsavimo už dainas statistiką |
|!whois | @vartotojas | Parodo informaciją apie vartotoją |

Nuolatinis DJ
-----------

|Komanda | Argumentas |  Aprašmas |
|:------:|:---------:|:--------------------------------------:|
|!link | | Nurodo dabartinės dainos nuorodą



Vartotojas
----

|Komanda | Argumentas |  Aprašmas |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (žinutė) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | gives a link to the commands |
|!cookie | (@vartotojas) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!fb | | links to the room's Facebook page (if set in the settings) |
|!ghostbuster | @user | checks if user is ghosting |
|!gif | (žinutė) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | links to an image to help get people started on plug |
|!play | | join the roulette if it's up |
|!leave | | leave the roulette if you joined |
|!link | | when the user is the DJ, give a link to the current song |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!purchase | | Nurodo plug taškų pirkimo adresą |
|!rules | | Nurodo kambario taisyklių adresą (jei nustatytas) |
|!theme | | Nurodo kambario dainų temą (jei nustatyta) |
|!thor | | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. |
|!website | | Nurodo kambario svetainės adresą (jei nustatytas |
|!youtube | | Nurodo kambario youtube kanalo adresą (jei nustatytas) |
