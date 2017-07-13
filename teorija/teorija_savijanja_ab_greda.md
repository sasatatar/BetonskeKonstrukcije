## Teorija savijanja AB greda {#teorija-savijanja-ab-greda}

### dijagram {#dijagram}

U bilo kom presjeku grede izložene savijanju, unutrašnji reaktivni moment savijanja mora da stoji u ravnoteži sa momentom savijanja koji djeluje u presjeku grede kao posljedica spoljašnjeg opterećenja. Unutrašnji reaktivni moment savijanja rezultat je djelovanja sprega unutrašnjih sila (sila pritiska u betonu) i (sila zatezanja u armaturi) koje djeluju na odstojanju (slika 9d).

Ponašanje armiranog betona pri savijanju je najpogodnije opisati pomoću odnosa _moment savijanja-zakrivljenost_ (u nastavku dijagram)za poprečni presjek grede izložen rastućem momentu savijanja. Zakrivljenost se definiše kao nagib dijagrama dilatacija po visini poprečnog presjeka grede u odnosu na vertikalu, odnosno:

(7.1)

gdje je:

maksimalna dilatacija u pritisnutoj ivici betona,

položaj neutralne ose u odnosu na pritisnutu ivicu.

Da bi se analitički konstruisao dijagram za bilo koji presjek, potrebno je usvojiti radne dijagrame koji dovoljno precizno opisuju odnos napona i dilatacija za beton i čelik. Za primjer u nastavku, korišteni su prethodno definisani radni dijagrami betona (slika 5.3) i čelika (slika 5.6). Osim toga, vrijede i sve ostale navedene pretpostavke prema teoriji graničnih stanja iz dijela 6.3.

Nakon definisanja osnovnih pojmova na dijagramu za tipičan poprečni presjek, biće razmatran niz različitih dijagrama moment-zakrivljenost da bi se ilustrovalo kako promjene pojedinih karakteristika poprečnog presjeka i čvrstoće materijala utiču na ponašanje presjeka pri savijanju.

Na slici 7.1 prikazan je jednostruko armirani pravougaoni poprečni presjek izložen djelovanju pozitivnog momenta savijanja. predstavlja ukupnu površinu armature u zategnutoj zoni, dok označava _statičku visinu presjeka_ – udaljenost od pritisnute ivice betona do težišta zategnute armature. Kompletan dijagram, kao što je prikazan na slici 7.2, može se generisati za ovaj presjek postepenim povećavanjem zakrivljenosti (nagiba dijagrama dilatacija) i korištenjem odgovarajućih dijagrama napon-dilatacija za beton i čelik za određivanje rezultujućih napona i unutrašnjih sila.

Slika 7.1 - Koraci pri analizi momenta i zakrivljenosti jednostruko armiranog poprečnog presjeka

Postupak konstrukcije dijagrama

Postupak određivanja specifične tačke na dijagramu prati proces predstavljen na slici 7.1 od b) do d) i može se opisati sledećim koracima:

1.  Usvoji se maksimalna dilatacija u pritisnutoj ivici betona, i pretpostavi položaj neutralne ose (za prvu iteraciju može se pretpostaviti: ). Za pretpostavljenu vrijednost definisan je dijagram dilatacija.
2.  Kada su poznate dilatacije po visini presjeka, mogu se odrediti dijagrami napona u betonu i armaturi na osnovu usvojenih radnih dijagrama betona i čelika.
3.  Integracijom dijagrama napona po odgovarajućim površinama poprečnog presjeka dobijaju se rezultantne unutrašnje sile u betonu () i armaturi () i tačke u kojima one djeluju.
4.  Provjerava se da li je za tako dobijene unutrašnje sile zadovoljen uslov ravnoteže da je suma svih horizontalnih sila koje djeluju u presjeku jednaka nuli:

(.2)

Ukoliko je , neutralna osa se pomjera nagore (smanjuje se pritisnuta zona betona), odnosno ukoliko je , neutralna osa se pomjera nadole (povećava se pritisnuta zona betona) i ponavljaju se koraci od 2 do 4.

1.  Nakon što je zadovoljen uslov ravnoteže (7.2, zakrivljenost se dobija prema izrazu 7.1 a odgovarajući moment savijanja sumiranjem momenata unutrašnjih sila oko pogodne tačke na presjeku – obično je to težište zategnute armature:

(7.3)

gdje je unutrašnji krak sila.

Ovaj postupak se može ponoviti za više vrijednosti . Kako budemo uvećavali maksimalnu dilataciju u betonu , dobijaćemo sve veću zakrivljenost presjeka . Na slici 7.2 označene su tačke sa karakterističnim dilatacijama u pritisnutoj ivici betona.

Slika 7.2 - Dijagram moment savijanja - zakrivljenost za presjek na slici 9

### Granica razvlačenja {#granica-razvla-enja}

Tačka Y na dijagramu predstavlja granicu elastičnosti datog presjeka. Naime, kako raste moment savijanja u presjeku, tako se povećavaju naponi zatezanja u armaturi i naponi pritiska u pritisnutoj zoni betona. Vremenom, jedan od ova dva materijala će dostići svoju graničnu čvrstoću. Shodno tome, doći će ili do razvlačenja čelika, ili do pucanja betona. S obzirom da se za presjek u primjeru pretpostavlja da nije prearmiran, napon u čeliku će dostići granicu tečenja prije nego što dilatacije u betonu dostignu kritičnu vrijednost. Nakon toga, presjek prestaje da se ponaša elastično, i počinje izraženo razvlačenje armature.

Zakrivljenost pri kojoj se dostiže granica razvlačenja, može se izračunati tako što se usvoji da je dilatacija u nivou armature jednaka , pa se dalje na isti način, kao što je prethodno opisano, odredi položaj neutralne ose za koji je ispunjen uslov ravnoteže horizontalnih sila ((7.2). Sa daljim povećanjem zakrivljenosti preko vrijednosti nema značajnijeg priraštaja reaktivnog momenta savijanja presjeka, ili drugim riječima, za male priraštaje momenta savijanja, značajno se povećava zakrivljenost presjeka, odnosno drastično rastu dilatacije u betonu i armaturi. Za usvojeni model proračuna, preostalo povećanje vrijednosti momenta savijanja na dijagramu, nakon što armatura uđe u fazu tečenja, posljedica je blagog povećanja kraka sila , jer se sa porastom zakrivljenosti i neutralna osa pomjera nagore, a sa njom i tačka djelovanja rezultantne sile u betonu.

Tačnost modela

Ako bi se koristio realniji radni dijagram prilagođen klasi betona (sa opadajućim naponom za vrijednosti dilatacija preko ), imali bismo beznačajnu razliku u graničnoj nosivosti presjeka na savijanje, dok bi dimenzionisanje bilo mnogo komplikovanije jer bi se za različite klase betona razlikovali njihovi radni dijagrami.

Ako se koristi bilinearni radni dijagram čelika sa gornjim krakom pod nagibom, moment savijanje nastaviće da raste i nakon dostizanja granice tečenja u armaturi, što bi rezultovalo neznatno većom nosivošću, ali isto tako i dosta komplikovanijim proračunom.

Većina standarda ograničavaju dilatacije u betonu na predefinisanu vrijednost. Prema Evrokodu i BAB-u 87, to je 3,5‰. Američki standard ACI koristi granicu od 3‰. Sa dijagrama je jasno da su razlike u nosivosti presjeka beznačajne, bez obzira na granicu koja se koristi.

### Duktilnost presjeka {#duktilnost-presjeka}

Duktilnost je izuzetno bitna osobina presjeka koja se može definisati kao njegova sposobnost da se deformiše i preko granice razvlačenja, bez značajnog gubitka nosivosti. Mjera duktilnosti može se izraziti preko odnosa ugiba, rotacija ili zakrivljenosti presjeka. Za navedeni primjer kao mjera duktilnosti može se usvojiti odnos njegove zakrivljenosti u stanju loma i na granici razvlačenja: . Što je taj odnos veći, presjek je duktilniji, što se na dijagramu manifestuje izraženijim gornjim krakom, nakon granice tečenja. Na osnovu prethodne definicije, navedeni primjer opisuje presjek dobre duktilnosti.

### Uticaj pojedinih parametara na nosivost i duktilnost presjeka {#uticaj-pojedinih-parametara-na-nosivost-i-duktilnost-presjeka}

U nastavku će biti prikazana analiza kako promjena pojedinog parametra utiče na nosivost i duktilnost presjeka. U tabeli 7.1 dato je šest varijacija parametara koji definišu karakteristike presjeka i materijala, pri čemu je za svaku varijaciju mijenjan samo po jedan parametar (podebljana vrijednost), u odnosu na osnovni presjek (prva kolona) koji je preuzet iz prethodnog primjera.

Tabela 7.1 - Varijacije karakteristika presjeka i materijala

| **Glavni parametri** | **Osnovni presjek** | **Umjereno _A<sub>s1</sub>_** | **Veliko _A<sub>s1</sub>_** | **Visoko _f<sub>yk</sub>_** | **Veliko _d_** | **Uvećano _f<sub>ck</sub>_** | **Veliko _b_** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| _A<sub>s1</sub>_ (cm<sup>2</sup>) | 19,6 | **29,4** | **49,1** | 19,6 | 19,6 | 19,6 | 19,6 |
| _f<sub>yk</sub>_(MPa) | 400 | 400 | 400 | **600** | 400 | 400 | 400 |
| _d_ (cm) | 60 | 60 | 60 | 60 | **90** | 60 | 60 |
| _f<sub>ck</sub>_ (MPa) | 30 | 30 | 30 | 30 | 30 | **35** | 30 |
| _b_ (cm) | 30 | 30 | 30 | 30 | 30 | 30 | **40** |

dijagrami koji predstavljaju osnovni presjek i prve dvije varijacije iz tabele predstavljeni su na slici 7.3\. Jedina izmjena koja je napravljena u obe varijacije jeste povećana količina zategnute armature - . Sa dijagrama se vidi da se srazmjerno povećanju količine zategnute armature povećava i nosivost presjeka. S druge strane, povećanjem zategnute armature smanjuje se duktilnost presjeka, tj. lom presjeka se dešava pri manjoj zakrivljenosti presjeka i nižem položaju neutralne ose. Da bi se osigurao duktilan rad presjeka, Evrokod uvodi ograničenja u pogledu najnižeg dopuštenog položaja neutralne ose u trenutku loma, definisanog odnosom , o čemu će biti riječi kasnije.

Slika 7.3 - Efekat povećanja količine zategnute armature

Na slici 7.4 prikazani su dijagrami za osnovni presjek i preostale četiri varijacije iz tabele 7.1\. Interesantno je razmotriti kako promjena pojedinih parametara utiče na nosivost na savijanje, krutost i duktilnost presjeka. Povećanje karakteristične čvrstoće čelika u suštini ima isti efekat kao povećanje površine zategnute armature – nosivost presjeka raste, dok se duktilnost smanjuje. Ni povećanje čvrstoće čelika, kao ni povećanje povrišine zategnute armature, nemaju značajan efekat na povećanje krutosti presjeka u području elastičnosti, što se bolje vidi na slici 7.4 gdje se nagib elastičnog dijela dijagrama osnovnog presjeka praktično poklapa sa nagibom dijagrama koji predstavlja presjek sa povećanom čvrstoćom čelika.

S druge strane, povećavanjem statičke visine presjeka , povećava se nosivost presjeka bez smanjenja njegove duktilnosti. Pored toga, porast statičke visine značajno povećava i elastičnu krutost presjeka, jer moment inercije presjeka uveliko zavisi od njegove visine. Ovakvi rezultati jasno upućuju na bitnost statičke visine presjeka, zbog čega je izuzetno važno obratiti pažnju na položaj šipki armature prilikom njihove ugradnje na gradilištu.

Promjene čvrstoće betona i širine presjeka imaju mnogo skromniji uticaj na nosivost presjeka nego što bi se to prvobitno očekivalo. Ova dva parametra imaju doduše vrlo mali efekat na krak sila prikazan na slici 9d, ali ne utiču na povećanje sile zatezanja u čeliku, što znači da i rezultantna sila pritiska u betonu ostaje ista. Shodno tome, ovi parametri imaju mnogo manji uticaj na nosivost presjeka nego količina zategnute armature, čvrstoća čelika i statička visina presjeka. S obzirom da lom ovih presjeka nastupa dostizanjem granične dilatacije u pritisnutoj ivici betona, povećanje čvrstoće betona ili širine presjeka povećava kapacitet sile pritiska koju beton može da podnese, što za posljedicu izaziva povećanje zakrivljenosti presjeka u trenutku loma, tako što se smanjuje dubina neutralne ose potrebna da se ostvari ravnoteža sa silom zatezanja u armaturi.

Posljednji parametar koji će se razmatrati je dodatak armature u pritisnutu zonu betona površine . Ova varijacija presjeka nije navedena u tebeli 7.1 iz praktičnih razloga, jer su svi ostali parametri ostali nepromijenjeni u odnosu na osnovni presjek.

Slika 7.4 - Efekat povećanja f<sub>yk</sub>, d, f<sub>ck</sub>, b i A<sub>s2</sub>

Kao što se vidi na slici 7.4, dodatak pritisnute armature ima vrlo mali efekat na povećanje nosivosti presjeka. S druge strane, preuzimanjem dijela sile pritiska sa betona, smanjuje se potrebna dubina neutralne ose i presjek dostiže mnogo veću zakrivljenost (veća duktilnost) prije nego što dilatacije u betonu dostignu graničnu vrijednost. Stoga se može reći da je primarna funkcija pritisnute armature da poveća duktilnost zadanog presjeka, uz pretpostavku da je obezbijeđena i neophodna poprečna (obavijajuća) armatura koja će spriječiti bočno izvijanje pritisnutih šipki.

### Minimalna i maksimalna količina armature {#minimalna-i-maksimalna-koli-ina-armature}

Da bi se spriječio krt lom usljed iscrpljenja čvrstoće betona na zatezanje sa prelaza iz naponskog stanja I u naponsko stanje II, količina armature mora biti tolika da primi silu zatezanja koju prije pucanja prenosi zategnuta zona betona.

EC2 propisuje _minimalnu količinu zategnute armature_ u iznosu:

(7.4)

pri čemu je

srednja čvrstoća betona na zatezanje (vrijednosti su date u prilogu _A_),

srednja širina zategnute zone presjeka. Za T presjeke gdje je flanša izložena pritisku (pozitivan moment savijanja), usvaja se da je jednako širini rebra ().

Da bi se obezbijedila dobra ugradnja betona i minimalna duktilnost presjeka, EC2 propisuje _maksimalnu količinu pritisnute ili zategnute armature_:

(7.5)

gdje je površina betonskog presjeka. Izuzetak ovom pravilu mogu biti zone nastavljanja armature.