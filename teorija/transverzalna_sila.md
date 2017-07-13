## Transverzalna sila {#transverzalna-sila}

### Model rešetke {#model-re-etke}

Ponašanje greda sa poprečnom armaturom pri graničnom stanju transverzalnih sila najbolje opisuje _model rešetke._ Ova analogija između nosača u stanju granične nosivosti i rešetke, koju su nezavisno uočili Ritter (1899.) i Mörsch (1902.), omogućava jednostavan model proračuna. Kao što je prikazano na slici 9.1a, u gredi sa kosim pukotinama formiraju se sile pritiska i zatezanja, i , u gornjoj i donjoj zoni, koje su ekvivalent gornjeg i donjeg pojasa u rešetci. Vertikalne uzengije djeluju kao zategnute vertikale, dok se dijelovi betona između paralelnih kosih pukotina ponašaju kao pritisnute dijagonale koje zaklapaju ugao sa podužnom osom nosača. Bitno je imati na umu da je u pitanju model rešetke čiji se kosi i vertikalni elementi višestruko presijecaju, tj. prepliću.

Uvodeći određena pojednostavljenja, uz zanemarivanje nosivosti betona na zatezanje i smicanje, ovaj višestruko statički neodređen sistem sila može se svesti na idealizovanu statički određenu rešetku prikazanu na slici 9.1b.

Slika 9.1 - Model rešetke

Dimenzionisanje presjeka prema transverzalnoj sili prema Evrokodu zasniva se na toj analogiji, s tim što se za razliku od klasične i poboljšane analogije koje se zasnivaju na pretpostavci da je , sada predviđa promjenljiv ugao koji omogućava tačniji proračun i ekonomičniji dizajn.

Idealizovani model rešetke se formira tako što se sva poprečna armatura koju siječe presjek A-A (paralelno pukotinama) zamjenjuje jednom vertikalom b-c, a sve pritisnute betonske dijagonale koje siječe vertikalni presjek B-B, mijenjaju se jednim dijagonalnim elementom e-f. Sila u ovom dijagonalnom elementu predstavlja rezultantu napona pritiska u pritisnutim betonskim dijagonalama koje siječe presjek B-B. Gornji pojas rešetke predstavlja silu pritiska u betonu, dok donji pojas silu zatezanja u glavnoj podužnoj armaturi. Svi pritisnuti elementi reštke su prikazani isprekidanim linijama, dok su zategnuti elementi prikazani punim linijama.

### Model promjenljivog ugla pritisnutih dijagonala {#model-promjenljivog-ugla-pritisnutih-dijagonala}

Model promjenljivog ugla pritisnugih dijagonala se zasniva na opsežnom testiranju ponašanja armirano-betonskih greda sa poprečnom armaturom pri djelovanju graničnih transverzalnih sila obavljenih na Univerzitetu Delft (Walraven, J.C. 1995-1999.). Na slici 9.2 opisan je princip promjene nagiba pritisnutih dijagonala u rebru sa porastom transverzalne sile u presjeku.

Slika 9.2 - Princip promjenljivog ugla _θ_ (Walraven, J.C. 1999\. Univerzitet Delft)

Na dijagramu (slika 9.2b) brojevima od 1-4 označene su faze kroz koje presjek prolazi:

1.  U prvoj fazi rebro prenosi poprečno opterećenje bez formiranja prslina, pravci glavnih napona pritiska su pod uglod od približno ,
2.  Sa pojavom prvih kosih prslina, smanjuje se i ugao pravca glavnih napona,
3.  U trećoj fazi dolazi do stabilizacije kosih prslina pri daljem porastu transverzalne sile, uz razvoj napona zatezanja u uzengijama u zoni elastičnosti,
4.  Kako smičuća sila dalje raste, uzengije dostižu granicu tečenja uz formiranje novih pukotina pod još nižim uglom , u nastojanju da se angažuje dodatni broj uzengija u kritičnom presjeku. Sa smanjenjem ugla pravca glavnih napona, raste napon pritiska u betonu, do konačnog pucanja rebra. Kada se iscrpi čvrstoća pritisnutih dijagonala, dolazi do smičućeg sloma grede.

Gornja i donja granica ugla propisane su nacionalnim aneksima, dok EC2 predlaže sledeće granice:

(9.1)

odnosno:

### Kapacitet pritisnutih betonskih dijagonala {#kapacitet-pritisnutih-betonskih-dijagonala}

Iz uslova ravnoteže vertikalnih sila za dio grede desno od presjeka B-B (slika 9.1b), dobija se da je vertikalna komponenta sile u pritisnutoj dijagonali jednaka sili , odnosno:

Maksimalna vrijednost smičuće sile , koju neki presjek može da prenese, ograničava se kako ne bi došlo do prekoračenja dopuštenih napona pritiska u betonskim dijagonalama, što bi izazvalo krt lom po betonu. Stoga je tranverzalna sila ograničena maskimalnom dopuštenom silom u pritisnutoj betonskoj dijagonali , tj. njenom vertikalnom komponentom :

Prema slici 9.1b, efektivna površina betona koji vrši ulogu pritisnute dijagonale je . Vrijednost je širina rebra u slučaju T presjeka. Ako se širina rebra mijenja po visini presjeka, uzima se najmanja vrijednost između između gornjeg i donjeg pojasa idealizovane rešetke, slika 9.3.

Slika 9.3 - Minimalna širina rebra

Maksimalna sila u pritisnutoj dijagonali jednaka je proizvodu njene efektivne površine i redukovane čvrstoće betona na pritisak.

Prema EC2, je koeficijent redukcije čvrstoće betona na pritisak usljed prisustva pukotina od smicanja koji se definiše nacionalnim aneksima, pri čemu se za njegov proračun predlaže sledeći izraz:

za u .

Ubacivanjem izraza za u jednačinu za , dobija se:

Transformacijom trigonometrijskih izraza dobija se:

Ukoliko je greda izložena sili prednaprezanja, njen uticaj na normalne napone u pritisnutom pojasu uzima se u obzir preko koeficijenta , pa se konačno dobija:

(9.2)

Koeficijenti takođe se definiše nacionalnim aneksima, pri čemu EC2 predlaže sledeće vrijednosti:

kada element nije prednapregnut,

za ,

za , i

za .

srednja vrijednost napona pritiska u betonu, od proračunske aksijalne sile. Dobija se kao srednja vrijednost napona pritiska u betonskom bruto presjeku, uzimajući u obzir i armaturu. Vrijednost treba računati na rastojanju ne manjem od od ivice oslonca.

Na sličan način, u slučaju kada uzengije stoje pod uglom u odnosu na podužnu osu nosača, razmatra se presjek paralelan njima, te se iz uslova ravnoteže vertikalnih sila dobija sledeći opšti izraz za kapacitet pritisnute dijagonale:

(9.3)

Kada se u gornji izraz uvrsti ugao , dobije se izraz 9.2 izveden za vertikalne uzengije. Ukoliko se kombinuju vertikalne uzengije sa povijenim podužnim šipkama, usvaja se .

### Proračun poprečne armature {#prora-un-popre-ne-armature}

Iz uslova ravnoteže za vertikalne sile za dio grede lijevo od presjeka A-A (slika 9.1b) koji je paralelan kosim pukotinama, dobija se da kompletnu silu nose uzengije koje siječe presjek A-A. Njihov broj se dobije kada se horizontalni raspon presjeka A-A () podijeli sa horizontalnim razmakom između uzengija pa se uz uslov da uzengije pri djelovanju sile dostižu granicu tečenja, dobija njihov kapacitet za prenošenje transverzalne sile:

(9.4)

Izjednačavanjem sa dobija se izraz za potrebnu količinu armature po _jediničnoj dužini_ grede:

(9.5)

pri čemu je:

površina armature za smicanje na dužini elementa (površina poprečnog presjeka uzengije × sječnost uzengija ),

računska čvrstoća uzengija.

U slučaju kada se poprečna armatura postavlja pod uglom , izraz za glasi:

(9.6)

Izraz za potrebnu količinu armature biće:

(9.7)

Prema EC2 potrebno je obezbijediti minimalnu količinu poprečne armature koja je definisana u nacionalnim aneksima, i treba da bude usaglašena sa važećim pravilnicima za seizmičke uticaje ukoliko se objekat izvodi na trusnom području. Prema Evrokodu treba da je:

(9.8)

pri čemu je:

površina armature za smicanje na dužini elementa ,

horizontalno rastojanje poprečne armature, mjereno u podužnom pravcu,

širina rebra elementa,

ugao između poprečne armature i podužne ose elementa,

minimalni koeficijent poprečne armature čija vrijednost se definiše u nacionalnim aneksima, dok Evrokod preporučuje sledeći izraz:

(9.9)

Osim minimalne količine armature, EC2 ograničava horizontalne razmake između uzengija u podužnom i poprečnom pravcu.

U podužnom pravcu:

(9.10)

U poprečnom pravcu:

(9.11)

U slučaju povijenih šipki, maksimalan razmak u podužnom pravcu definisan je izrazom:

(9.12)

Ukoliko se kombinuju uzengije sa povijenim podužnim šipkama, EC2 propisuje da najmanje potrebne poprečne armature čine uzengije. Podužne šipke se povijaju isključivo pod uglom od , dok se za uzengije ugao može birati u rasponu od do .

U ovom dijelu namjerno je zanemarena Evrokodm definisana nosivost na smicanje elemenata bez poprečne armature (), s obzirom da je u pitanju komplikovan empirijski izraz za čija vrijednost ne utiče na rezultat proračuna prema prethodno izloženom postupku. Može se zaključiti da je Evrokod zadržao pojam nosivosti betona na smicanje () kao indikator kada nije potrebno ulaziti u proračun prema modelu promjenljivog ugla pritisnutih dijagonala, s obzirom da je svakako potrebno ispuniti prethodno definisane uslove za minimalnu količinu i međusobne razmake poprečne armature i u slučaju kada je .

### Dodatna podužna armatura {#dodatna-podu-na-armatura}

Kada se koristi analogija sa rešetkom, potrebno je uzeti u obzir dodatnu silu zatezanja koju izaziva transverzalna sila Ova podužna sila zatezanja prouzrokovana je horizontalnom komponentom sile u pritisnutoj betonskoj dijagonali idealizovane rešetke, koja iznosi:

Na osnovu razlike sila dobijenih iz modela rešetke (stanje II, sa pukotinama) za zategnuti pojas i sile zatezanja koju nosi armatura za homogeni presjek (stanje I), dobija se da polovinu ove sile nosi zategnuta podužna armatura, odnosno:

(9.13)

U slučaju kada se poprečna armatura postavlja pod uglom , izraz za glasi:

(9.14)

Da bi se primila dodatna sila zatezanja, potrebno je obezbijediti dodatnu armaturu u zategnutoj zoni, pored one proračunate za moment savijanja. U praksi, to se obično postiže dodatnim razvlačenjem dijagrama momenata za vrijednost , što će za posljedicu imati dodatno prepuštanje zategnute armature, kao što je prikazano na slici 9.4.

Izraz za dužinu prepuštanja u opštem slučaju glasi:

(9.15)

Slika 9.4 – Prepuštanje zategnute armature za prihvat dodatne sile zatezanja

### Maksimalan kapacitet presjeka na smicanje {#maksimalan-kapacitet-presjeka-na-smicanje}

Iz jednačine 9.4 odnosno 9.6 može se zaključiti da se za manje vrijednosti ugla (veće ) dobija veća smičuća nosivost presjeka za istu količinu poprečne armature. S druge strane, smičuća nosivost s obzirom na kapacitet pritisnute dijagonale se smanjuje za vrijednosti manje od . Iz toga slijedi da se maksimalan kapacitet na smicanje za određenu količinu poprečne armature dobija za vrijednost ugla za koju je smičući kapacitet uzengija jednak smičućem kapacitetu pritisnute dijagonale:

To dalje implicira da se iz izraza za može odrediti minimalna vrijednost ugla , iz uslova da je:

Transformacijom izraza dobija se osnovni oblik kvadratne jednačine u funkciji od :

Uvođenjem smjene dobija se pregledniji oblik kvadratne jednačine:

Tražena vrijednost odgovara prvom rješenju gore navedene kvadratne jednačine:

Za tako dobijen ugao može se preko izraza 9.5 odnosno 9.7 jednoznačno odrediti minimalna količina poprečne armature () potrebna za prenos smičuće sile .

Na slici 9.5 je prikazan tipičan dijagram koji opisuje funkciju smičuće nosivosti presjeka u zavisnosti od količine poprečne armature, uzimajući u obzir prethodno navedena ograničenja za vrijednost ugla (9.1).

Slika 9.5 - Smičuća nosivost presjeka u zavisnosti od količine poprečne armature

Prema modelu promjenljivog ugla pritisnutih dijagonala, projektovanjem smičućeg sloma pri nižoj vrijednosti ugla postiže se ušteda u potrebnoj količini poprečne armature, ali se to odražava na povećanu vrijednost dodatne sile zatezanja , što za posljedicu ima veće dužine prepuštanja glavne zategnute armature.