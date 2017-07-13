## Moment torzije {#moment-torzije}

Moment torzije izaziva napone smicanja usljed kojih se formiraju glavni naponi zatezanja u pravcu pod uglom od približno u odnosu na podužnu osu nosača. Nakon što naponi zatezanja prekorače čvrstoću betona na zatezanje, formiraju se dijagonalne pukotine koje se spiralno pružaju po dužini nosača, kao što je prikazano na slici 10.1\. Nakon nastanka dijagonalnih pukotina (naponsko stanje II), nosivost elementa je moguća samo uz pomoć poprečne i podužne armature.

Slika 10.1 - Djelovanje momenta torzije

Na osnovu eksperimentalnih istraživanja utvrđeno je da se najveći dio smičućih napona prenosi u relativno uskom pojasu po konturi presjeka, dok se uticaj središnjeg dijela betona na ukupnu torzionu nosivost može zanemariti, zbog čega se puni presjeci mogu posmatrati kao odgovarajući kutijasti presjeci. Na osnovu te činjenice i pretpostavke da beton nema nikakvu nosivost na zatezanje, značajno se pojednostavljuje proračun presjeka na moment torzije.

Na slici 10.2 prikazan je proizvoljan puni presjek koji se aproksimira sa ekvivalentnim kutijastim presjekom debljine .

Slika 10.2 - Ekvivalentni kutijasti presjek debljine

Usljed djelovanja momenta torzije , u konturnom pojasu presjeka javlja se konstantan _tok smicanja_ koji se prema klasičnoj teoriji elastičnosti definiše na sledeći način:

(10.1)

pri čemu je:

napon smicanja u -tom zidu,

efektivna debljina -te stranice, prema EC2 može se za sve stranice usvojiti jedinstveno , s tim da ta vrijednost ne smije biti manja od dvostruke udaljenosti od ivice presjeka do centra podužne armature, i veća od stvarne debljine zida u slučaju kutijastih presjeka,

ukupna površina presjeka, uključujući i šupljinu,

obim presjeka,

računski moment torzije,

površina ograničena centralnom linijom zidova, uključujući i šupljinu.

Smičuća sila u stranici , usljed djelovanja momenta torzije, data je izrazom:

(10.2)

pri čemu je odgovarajuća dužina centralne linije stranice , kao što je prikazano na slici 10.2.

### Model prostorne rešetke {#model-prostorne-re-etke}

Pod uticajem smičućih sila od momenta torzije između armature i betona javlja se efekat _prostorne rešetke_ (slika 10.3), pri čemu armatura vrši ulogu zategnutih elemenata rešetke, a beton pritisnutih dijagonala između uzengija. Slom elementa nastupa popuštanjem uzengija i pucanjem betona, čemu prethodi otvaranje spiralnih pukotina.

Slika 10.3 - Model prostorne rešetke

### Kapacitet pritisnutih betonskih dijagonala {#kapacitet-pritisnutih-betonskih-dijagonala}

Kao i u slučaju modela rešetke za proračun na uticaj transverzalne sile, pri dimenzionisanju presjeka na uticaj momenta torzije potrebno je provjeriti da li su prekoračeni dopušteni naponi pritiska u betonskim dijagonalama, što bi moglo prouzrokovati nenajavljeni slom po betonu.

Slika 10.4 - Sile koje djeluju u bočnom zidu kutijastog presjeka

Posmatrajući sliku 10.4, dobija se da je:

_Sila u pritisnutoj dijagonali_

_Površina dijagonale_

_Napon u dijagonali sila / površina_

Kao i u slučaju pritisnutih betonskih dijagonala usljed djelovanja transverzalnih sila, napon u pritisnutoj betonskoj dijagonali ne smije biti veći od računske čvrstoće betona na pritisak redukovane koeficijentima i (dio 9.3).

Uvrštavajući izraz 10.1 za tok smicanja u prethodno navedeni izraz za napon u dijagonali, iz prikazanog uslova može se izvesti formula za maskimalnu vrijednost momenta torzije koju presjek može da prenese:

Trigonometrijskom transformacijom gornji izraz može se napisati na sledeći način:

(10.3)

Kao i u slučaju proračuna za granično stanje transverzalnih sila, moguć je slobodan odabir vrijednosti ugla pri čemu je odabirom manje vrijednosti ugla moguće redukovati potrebnu količinu poprečne armature, što se kompenzuje nešto većom potrebnom količinom podužne armature.

### Proračun poprečne armature {#prora-un-popre-ne-armature}

Ukoliko se posmatra samo jedna stranica kutijastog presjeka, kao što je prikazano na slici 10.4, iz uslova ravnoteže vertikalnih sila, uz pretpostavku da uzengije dostižu granicu tečenja, dobija se:

pri čemu je:

površina torzione poprečne armature na dužini stranice (obično je to površina jednog kraka uzengija ),

podužni razmak između uzengija, pa je broj uzengija koje siječe presjek pod uglom ,

smičuća sila koja djeluje u prikazanom zidu kutijastog presjeka.

Sređivanjem prethodnog izraza, dobija se izraz za potrebnu količinu uzengija da bi se obezbijedila nosivost presjeka za moment torzije :

(10.4)

Tako dobijena potrebna količina poprečne armature sabira se sa onom dobijenom proračunom na uticaje od poprečnih (transverzalnih) sila. S obzirom da je količina torzione poprečne armature u izrazu 10.4 dobijena za jednu stranicu presjeka, pri sabiranju je tu količinu potrebno pomnožiti sa 2, da bi se dobila količina torzione poprečne armature po _jediničnoj dužini_ grede, jer ukupnu količinu čine krakovi uzengija u dvije naspramne stranice presjeka. U skladu s tim, ukupna količina poprečne armature dobija se preko sledećeg izraza:

(10.5)

Pri sabiranju poprečne armature veće sječnosti () potrebno je obratiti pažnju da usvojeni razmak obezbjeđuje dovoljnu količinu torzione armature, imajući u vidu da u prenošenju torzionih uticaja efektivno učestvuju samo konturne uzengije koje se nalaze unutar zida ekvivalentnog kutijastog presjeka debljine (slika 10.5).

Slika 10.5 – Konturne i unutrašnje uzengije

Za razliku od uzengija koje se koriste za prenos transverzalne sile, torzione uzengije treba da budu zatvorene, pod uglom od 90⁰ u odnosu na osu nosača, ankerovane preklapanjem po jednoj (obično kraćoj) stranici ili kukama pod uglom od koje obuhvataju podužnu armaturu i koje su sa krajevima (dovoljne dužine) usidrene u središtu betonskog presjeka (slika 10.6), što je naročito bitno u seizmički aktivnim područijima.

Slika 10.6 - Pravilan i nepravilan način oblikovanja torzionih uzengija

Horizontalni razmak između uzengija u podužnom pravcu, pored uslova (9.10), ne smije biti veći od , odnosno od manje dimenzije poprečnog presjeka (obično je to širina rebra - ), odakle slijedi:

(10.6)

Istovremeno mora biti zadovoljen uslov za minimalnu količinu poprečne armature:

(10.7)

pri čemu je definisano izrazom 9.9.

### Proračun podužne armature {#prora-un-podu-ne-armature}

Imajući u vidu da predstavlja smičuću silu po jedinici dužine obima kutijastog presjeka, ukupna smičuća sila od toka smicanja se dobije kao proizvod i obima . Na slici 10.7 šematski su prikazani zidovi kutijastog presjeka sa slike 10.3 _razvijeni_ u ravan.

Slika 10.7 - Sile koje djeluju na prostornu rešetku

Ako se pretpostavi da se smičućoj sili suprotstavljaju sile u pritisnutim betonskim dijagonalama prostorne rešetke, iz uslova ravnoteže horizontalnih sila (slika 10.7b), može se dobiti dodatna zatežuća sila koju preuzima podužna torziona armatura:

Potrebna površina podužne armature za prenos momenta torzije , uz pretpostavku dostizanja računske granice tečenja dobija se iz sledećeg izraza:

(10.8)

Podužna torziona armatura se sastoji od najmanje po jedne šipke u svakom uglu presjeka, dok se ostatak raspoređuje ravnomjerno po konturi presjeka vodeći računa da **osni razmak između šipki nije veći od 350 mm**. Ugradnja dodatne podužne armature nije obavezna u pritisnutoj zoni presjeka, pod uslovom da je sila pritiska u betonu veća od sile zatezanja usljed djelovanja momenta torzije.

U zoni presjeka gdje se nalazi proračunska podužna armatura za prihvatanje momenta savijanja i poprečne sile, podužna armatura za prihvatanje momenta torzije se dodaje usvojenoj armaturi za prihvatanje tih uticaja. To se može postići usvajanjem šipki većeg prečnika ili ugrađivanjem dodatnih šipki. U slučaju kombinovanog uticaja momenta torzije i transverzalne sile, u praksi se najčešće ugrađuje dodatna podužna armatura za preuzimanje zatežuće sile od momenta torzije, dok se dodatna zatežuća sila od transverzalne sile pokriva prepuštanjem glavne podužne armature projektovane za prenos momenta savijanja, kao što je to opisano u dijelu 9.5, slika 9.4.

### Kombinovan uticaj torzije sa transverzalnom silom i momentom savijanja {#kombinovan-uticaj-torzije-sa-transverzalnom-silom-i-momentom-savijanja}

Moment torzije vrlo rijetko djeluje kao jedino opterećenje u elementu, a najčešće je prisutan u kombinaciji sa transverzalnom silom i momentom savijanja. Usljed kombinovanog djelovanja momenta torzije i transverzalne sile, smičući naponi u jednom dijelu presjeka se superponiraju, dok se u drugom suprotstavljaju (poništavaju) – slika 10.8\.

Slika 10.8 - Superponiranje napona smicanja od momenta torzije i transverzalne sile

Prema Evrokodu, kao što je već prikazano, podužna i poprečna armatura se računa za svaki uticaj posebno, pa se njihove površine sabiraju. Stoga je bitno osigurati da ne dođe do prekoračenja nosivosti pritisnutih betonskih dijagonala.

Na slici 10.9 prikazan je tipičan interakcioni dijagram za moment torzije i transverzalnu silu, na osnovu kog se vidi da je nosivost presjeka pri kombinovanom djelovanju umanjena u odnosu na pojedinačne vrijednosti.

Slika 10.9 - Interakcioni dijagram za moment torzije i transverzalnu silu

S obzirom da mehanizam interakcije još uvijek nije definitivno utvrđen, Evrokod propisuje pojednostavljen, konzervativniji, izraz za kontrolu nosivosti za slučaj istovremenog djelovanja momenta torzije i poprečne sile:

(10.9)

pri čemu su i maksimalne nosivosti presjeka na moment torzije i poprečnu silu s obzirom na nosivost pritisnute betonske dijagonale, definisane pod (9.2) i (10.3).

### Maksimalan kapacitet presjeka na kombinovani uticaj i {#maksimalan-kapacitet-presjeka-na-kombinovani-uticaj-i}

Uvrštavanjem izraza 10.3 za i 9.2 za u izraz 10.9, i sređivanjem izraza dobija se kvadratna jednačina u funkciji od iz koje se može odrediti granična vrijednost za koju će zbir interakcione funkcije (10.9) biti jednak jedinici:

Uvođenjem smjene dobija se pregledniji oblik kvadratne jednačine:

Tražena vrijednost odgovara prvom rješenju gore navedene kvadratne jednačine:

(10.10)

Za tako dobijenu vrijednost , uvrštavanjem izraza 9.5 i 10.4 za potrebne količine armature za transverzalnu silu i moment torzije u izraz 10.5 može se izračunati ukupna potrebna količina armature:

(10.11)

Upotrebom izraza 10.9 i 10.11 za vrijednosti u rasponu od dobija se funkcionalna zavisnost između interakcione funkcije i ukupne količine poprečne armature. Na slici 10.10 prikazan je primjer dijagrama te funkcije.

Slika 10.10 - Zavisnost vrijednosti interakcione funkcije od količine poprečne armature

Dijagram daje vizuelnu predstavu nivoa iskorištenosti kapaciteta presjeka za kombinovani uticaj i , u zavisnosti od ugrađene količine poprečne armature. Tački B na dijagramu odgovara ugao za koji će se dobiti minimalna potrebna količina poprečne armature pri kojoj će vrijednost interakcione funkcije biti jednaka jedinici, odnosno stanju maksimalne iskorištenosti napona u pritisnutim betonskim dijagonalama. Za veće vrijednosti ugla (manje vrijednosti ) dobijaju se veće količine poprečne armature (izraz 10.11) kao i veće nosivosti i (izrazi 10.3 i 9.2), zbog čega dobijamo vrijednosti interakcione funkcije manje od jedan. Tačka C predstavlja ujedno i maksimalnu dozvoljenu količinu poprečne armature koja se dobije za , odnosno , a kojoj odgovaraju i najveće vrijednosti i . U slučaju kada je presjek nedovoljno jak, kompletan dijagram nalaziće se iznad iscrtkane linije koja označava vrijednost interkacione funkcije jednake jedinici.

Na slici 10.11 prikazani su dijagrami interakcije koji odgovaraju različitim vrijednostima (tačke A, B i C sa slike 10.10). Kao što se vidi sa slike, najveća nosivost presjeka se dobija za (dijagram interakcije C), dok najmanja nosivost odgovara vrijednosti (dijagram interakcije A). Tačka sa koordinatama leži na dijagramu interakcije B, kom odgovara za koji je vrijednost interakcione funkcije jednaka jedinici.

Slika 10.11 – Dijagrami interakcije

Kao i u slučaju dimenzionisanja prema transverzalnoj sili, projektovanjem sloma pri nižoj vrijednosti ugla postiže se ušteda u potrebnoj količini poprečne armature, ali se to odražava na povećanu vrijednost dodatne sile zatezanja, od momenta torzije i od transverzalne sile, što kao posljedicu povlači veću količinu podužne armature.