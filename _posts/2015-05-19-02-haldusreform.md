---
layout: post
title: "Haldusreformist"
author: "Oliver Aasmets, Sven Erik Ojavee"
---

Arutelu Eesti halduskorralduse mõistliku korraldamise üle on kestnud juba alates Eesti taasiseseisvumisest saati. Praegune Eesti suuresti valdadel põhinev haldusskeem kujunes välja 1930. aastatel ning hoolimata mõningatest nõukogudeaegsetest muudatustest, on süsteem üldiselt üsna sarnane esimese iseseisvusaja süsteemiga. Valdade arv oli üsna suur, sest suure maarahvastiku osakaalu tingimusis olid väiksed vallad halduse korraldamiseks sobivamad. Paraku on tänapäevaks maarahvastiku osatähtsus ning põllumajandusega seotud töökohtade arvud vähenenud oluliselt ning seega on tõusnud küsimus, kas oleks võimalik elu paremini korraldada teistsuguse omavalitsuste struktuuriga. Samuti peaks haldusreformi tulemusena olema teenused inimestele paremini kättesaadavad. Põhiline võimalus haldusreformi teostamiseks on kohalike omavalitsuste liitmine suuremateks, millel oleks suurem võimekus lahendada inimeste probleeme.
Siiani on Eestis olnud omavalitsuste liitumine või liitmine olnud vabatahtlik, mida on omakorda motiveeritud erinevate toetustega. Samas ei ole selline lähenemine toonud kaasa omavalitsuste arvu märgatavat vähenemist. Lätis teostati haldusreform aastal 2009 ning omavalitsuste arvu vähendati 520lt 119le, mis säästis märgatavalt vahendeid. Eestis on praegu 215 omavalitsust, paljud neist väga väiksed alla 1000 inimesega. Erinevate eelnevate analüüside tulemusena on välja käidud hinnang, mille kohaselt peaks kohalikus omavalitsuses elama vähemalt 5000 inimest [1](http://www.postimees.ee/2976843/uhes-eesti-omavalitsuses-peaks-elama-vahemalt-5000-inimest), ent välistatud pole ka sellest märksa suuremad numbrid. Sellise reformi tulemusena kujundataks ümber seega vähemalt 80% Eesti omavalitsuste toimimine. Et samm omabki tohutut potentsiaalset mõju Eesti elule, ongi oluline uurida, kas õigupoolest on tegemist tarviliku sammuga.
Käesolevas artiklis vaadeldakse peaasjalikult rahvaarvu ning erinevate sotsiaalsete, demograafiliste või majanduslike näitajate vahelisi seoseid. Haldusreformi teostamist loeme kindlasti motiveerituks, kui ilmneb, et suurem rahvaarv annab omavalitsusele olulisi majanduslikke või sotsiaalseid eeliseid.

###Elanike arv
Kõrvutades omavahel Eesti kaarte, milledele on märgitud omavalitsuste kaupa rahvaarv, on näha, et suurema rahvaarvuga on pigem Harjumaa omavalitsused, lisaks veel ka nn regionaalsed tõmbekeskused (nt Pärnu, Türi, Kuressaare).
![](/images/elanikearv.png)

Suuremad omavalitsused elanike arvu poolest:

![](/images/elanikudtb.png)


###Töötuse määr
Huvitaval kombel näitab sarnast klasterdumise tendentsi ka töötuse määr (töötuid tööealise elanikkonna kohta), kuid sel juhul on olukord vastupidine. Töötuse määr on selgelt suurem just Lõuna-Eestis ning pigem väiksem Põhja-Eestis mõningate eranditega Ida-Virumaal. Seega näib, et võib kehtida seos, mille kohaselt on töötuse määr väiksem piirkondades, kus on suurem rahvaarv, seega ka suurem suutlikkus panustada tööhõive kõrgemasse tasemesse.

![](/images/tootuid.png)

Lineaarsest mudelist, mis kasutab argumenttunnusena rahvaarvu ning funktsioontunnusena töötuse määra, selgub, et rahvaarv osutub (olulisuse nivool 0,05) töötuse määra kirjeldamisel ebaoluliseks. Sarnane tulemus joonistub välja ka graafikul (siin on tunnus rahvaarv logaritmitud). Punktiparv paikneb graafikul hajutatult ning pole võimalik väita nagu oleks seos tööpuuduse ja rahvaarvu vahel.

![](/images/tootutesc.png)

Suurema töötuse osakaaludega omavalitsused:

![](/images/tootudtb.png)


###Pensionäride osakaal
Uurime ka tööealiste ning pensionäride arvu suhet. Mida suurem on see suhe, seda edukam võib arvatavasti ka omavalitsus olla, sest maksumaksjaid on suurema suhte puhul rohkem võrreldes passiivsete saajatega. Eesti kaardi pealt joonistub jällegi välja asjaolu, et tööealiste arv suhtes pensionäride arvuga on suurem suuremate asulate ning tõmbekeskuste juures.
![](/images/penskareid.png)

Aladel, mis jäävad suurematest keskustest kaugemale, on ka selle suhte väärtus väiksem. Lineaarsest mudelist, mis kasutab argumenttunnusena rahvaarvu ning funktsioontunnusena eelkirjeldatud suhet, selgub, et rahvaarv osutub (olulisuse nivool 0,05) tööealiste ja pensionäride suhte kirjeldamisel ebaoluliseks. Samas, kui elanike arvu eelnevalt logaritmida, osutub, et tööealiste ja pensionäride arvu suhe sõltub logaritmitud elanike arvust. Mida suurem on rahvaarv, seda kõrgem on ka tööealiste ja pensionäride suhtarv.

![](/images/pensisc.png)

Omavalitsused, kus on pensionäri kohta enam tööealisi inimesi:

![](/images/penskarid1tb.png)


Omavalitsused, kus on pensionäri kohta vähem tööealisi inimesi:

![](/images/penskarid2tb.png)


###Tööliste palk
Vaatleme erinevate omavalitsuste keskmist palgataset. Niinimetatud sinikraede ehk oskustööliste keskmine palk valdade kaupa on küllaltki erinev ning on raske eristada kindlat mustrit. Et mitmed vallad on üsna väiksed, võib see tulemus olla suuresti mõjutatud ka näiteks mõne suurema ettevõtte poolt. Ka siin ei tule lineaarses mudelis argumenttunnusena kasutatav rahvaarv oluline sinikraede keskmise palga kirjeldamisel.
![](/images/sinikraed.png)

Kasutades lineaarse mudeli jaoks argumenttunnuse (rahvaarv) eelnevat logaritmimist, saame, et oskustöölise keskmine palk ei sõltu logaritmitud elanike arvust. 

![](/images/sinisc.png)

Omavalitsused, kus sinikraedele makstakse suurimat keskmist palka:

![](/images/sinikraedtb.png)


Osutus, et suurem osa sotsiaalmajanduslikest tunnustest, mida eelpool vaadeldi, ei ole statistiliselt oluliselt mõjutatud rahvaarvust. Vaid tööealiste ning pensionäride arvu suhe sõltus logaritmitud rahvaarvust. Selliseist tulemusist johtuvalt võiks väita, et haldusreformi tegemine ei ole õigustatud, sest statistilist tõestust ei leidnud tõik, nagu suurem omavalitsusüksuse rahvaarv aitaks hoida tööpuuduse taset madalamal või palgataset kõrgemal. Samas peab siiski möönma, et kaartidelt oli näha teatud sorti klasterdumist. Mõneti edukamad omavalitsused olid need, mis paiknesid lähedal tõmbekeskustele või olid ise need. Pigem kesiseid näitajaid andsid tõmbekeskustest kaugemal asuvad omavalitsused.

Kokkuvõttes võib märkida, et kuigi käesoleva analüüsi tulemusena ei suudetud tõestada palju olulisi seoseid rahvaarvu ja sotsiaalmajanduslike tunnuste vahel, on siiski võimalik, et haldusreformi tegemine on siiski vajalik.Erinevuste struktuurid võivad olla veelgi keerulisemad, mida lihtsalt käesolev analüüs ei suutnud välja tuua. Vihje sellele annavad eeltoodud kaardid, kuid täpsemad lahendused jäävad tulevaste uurimistööde kinnitada.