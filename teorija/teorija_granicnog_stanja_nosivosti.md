## Teorija graničnog stanja nosivosti {#teorija-grani-nog-stanja-nosivosti}

### Uopšteno {#uop-teno}

Metoda graničnog stanja nosivosti razmatra stanje deformacija i naprezanja neposredno prije loma presjeka. Da bi se mogla odrediti nosivost prije loma, dobro je poznavati i ostala naponska stanja koja prethode onom graničnom.

Greda od armiranog betona opterećena koncentrisanom silom u sredini raspona ima različite stepene iskorištenosti u raznim presjecima zavisno o dijagramu momenata savijanja. Prateći od oslonca prema sredini raspona, vide se tri različita naponska stanja, poznata u armiranom betonu kao naponska stanja I, II i III (slika 6.1).

Slika 6.1 - Naponska stanja

Za naponsko stanje I naponi pritiska i zatezanja su mali, pa je opravdano pretpostaviti da za to naponsko stanje važi linearna raspodjela napona po visini presjeka (Navierova hipoteza). Kraj naponskog stanja I (Ia) signalizuje da je čvrstoća betona na zatezanje pred iscrpljenjem, pa raspodjela napona u zategnutoj zoni prati krivu liniju, dok je raspodjela napona u pritisnutoj zoni još uvijek linearna.

Naponsko stanje II karakteristično je po tome što u zategnutoj zoni nastaju pukotine pa se zategnuta zona betona može isključiti iz nosivosti, a raspodjela napona u pritisnutoj zoni već počinje da prati krivu liniju. Dimenzionisanje konstrukcije od armiranog betona prema teoriji dopuštenih napona bazira se na naponskom stanju II, s tim što se krivolinijska raspodjela napona u betonu aproksimira pravom.

Naponsko stanje III (stanje neposredno prije loma) karakteristično je po tome što raspodjela napona pritiska prati krivu liniju, dok se u zategnutoj zoni, kao i u naponskom stanju II, formiraju još veće pukotine koje dopiru do neutralne ose. Zona pritiska se smanjuje i neutralna osa se pomjera ka pritisnutoj ivici betona.

Očigledno je da se na osnovu napona određenih za naponsko stanje II ne može precizno, a ponekad ni približno odrediti sigurnost od loma.

Način loma armirano-betonskih elemenata zavisi od količine ugrađene armature, djelovanja presječnih sila i od mehaničkih karakteristika betona i armature.

### Osnovne postavke proračuna {#osnovne-postavke-prora-una}

Uslov nosivosti je zadovoljen ako je računska vrijednost presječne sile manja ili jednaka od računske nosivost presjeka :

(6.1)

Dimenzionisanje presjeka se sastoji u tome da se iz jednačine ravnoteže

(6.2)

odrede dimenzije presjeka i potrebna količina armature.

Računske vrijednosti presječnih sila, a prema tome i računske vrijednosti nosivosti mogu biti sve statičke veličine (normalna sila, tranverzalna sila, moment savijanja, moment torzije) izazvane vanjskim djelovanjem (koncentrisana sila, kontinuirano opterećenje, promjena temperature, skupljanje betona, pomjeranje oslonaca i dr.), odnosno one koje pružaju otpor vanjskom djelovanju.

Proračun računskih vrijednosti presječnih sila provodi se za računsko opterećenje ili za reprezentativno opterećenje (opterećenje u eksploataciji), s tim što se tada dobijene vrijednosti statičkih veličina množe koeficijentima sigurnosti.

Računske nosivosti presjeka (unutrašnje sile koje presjek može da primi) proračunavaju se u zavisnosti od presječne sile, dimenzija presjeka i kvaliteta materijala.

### Pretpostavke za proračun prema GSN {#pretpostavke-za-prora-un-prema-gsn}

Proračun presjeka prema graničnom stanju nosivosti zasniva se na sledećim pretpostavkama o ponašanju presjeka u graničnom stanju loma:

1.  raspodjela dilatacija po visini poprečnog presjeka je linearna, dakle važi Bernulijeva hipoteza o ravnim presjecima,
2.  potpuno se zanemaruje čvrstoća betona na zatezanje, cjelokupne napone zatezanja prima isključivo armatura,
3.  smatra se da u stanju loma nije narušena veza između betona i armature, dakle važi pretpostavka da je na kontaktu betona i armature ,
4.  veza između napona i dilatacija po visini pritisnute zone betona nije linearna i aproksimira se radnim dijagramom betona (RDB) u obliku parabole i prave, kojim se u proračunu opisuje ponašanje pritisnutog betona u stanju loma,
5.  računski dijagram veze napona i dilatacija u čeliku aproksimira se bilinearnim radnim dijagramom čelika (RDČ).

### Moguća stanja deformacija presjeka {#mogu-a-stanja-deformacija-presjeka}

Iz svega naprijed navedenog može se zaključiti da u proračunu prema graničnom stanju nosivosti kriterijumi loma nisu vrijednosti dostignutih napona, već vrijednosti dostignutih, konvencionalno usvojenih, _graničnih dilatacija._

U zavisnosti od materijala u kome su te granične dilatacije dostignute, razlikujemo tri vrste loma presjeka izloženog uticajima savijanja sa ili bez normalne sile:

1.  lom po armaturi
2.  lom po betonu
3.  simultani lom

_Lom po armaturi_ nastaje iz jednog od razloga:

*   količina armature nije dovoljna da preuzme napone zatezanja pri pojavi prvih pukotina na prelazu iz naponskog stanja Ia u naponsko stanje II. Lom nastaje trenutno uslijed krtog pucanja betona u zategnutoj zoni presjeka. Odmah potom otkazuje i armatura. Da bi se takav lom spriječio, standardi propisuju minimalne količine armature kojima je potrebno armirati presjek.
*   dolazi do popuštanja (tečenja) armature u zategnutoj zoni presjeka prije nego što se iscrpi čvrstoća betona u pritisnutoj zoni. S obzirom na duktilnost čelika, lom ne nastupa odmah, nego mu prethode sve veće pukotine i naglašene deformacije armature u zoni zatezanja. Takav lom je _najavljen_ ili _duktilan lom._

_Lom po betonu_ (nenajavljen lom) nastaje iscrpljivanjem čvrstoće betona u pritisnutoj zoni presjeka pri čemu napon u zategnutoj armaturi nije dostigao granicu tečenja i do njega dolazi ukoliko je presjek prearmiran. Takav lom može biti iznenadan, bez naglašenih pukotina i većih deformacija, posebno ako se koriste betoni visoke čvrstoće, te ga treba izbjegavati.

_Simultani lom_ nastaje pri istovremenom iscrpljenju čelika i betona (balansirani lom). I ovoj vrsti loma prethode naglašene deformacije i pukotine.

Za proračun nosivosti, EC2 definiše moguća stanja deformacija poprečnog presjeka, pri čemu u trenutku graničnog stanja loma, dijagram dilatacija prolazi kroz jednu od tri tačke: A, B i C (slika 6.2).

Slika 6.2 – Moguća stanja deformacije presjeka

U zavisnosti od deformacija betona i čelika, razlikuje se pet osnovnih mogućnosti naprezanja:

1.  Područje 1 opisuje ekscentrično zatezanje s malim ekscentricitetom. Kompletan presjek izložen je naponima zatezanja (neutralna osa se nalazi na ivici ili van presjeka). Čelik je pri tome u potpunosti iskorišten.
2.  Područje 2 opisuje savijanje sa ili bez normalne sile zatezanja. Čelik je potpuno iskorišten, a beton dostiže granične vrijednosti dilatacija (). Ukoliko se koristi bilinearni RDČ sa horizontalnim gornjim krakom, prema EC2 dilatacije u čeliku nisu ograničene, dok se za gornji krak pod nagibom propisuje gornja granica (preporučena vrijednost je ).
3.  Područje 3 opisuje savijanje sa ili bez normalne sile pritiska ili zatezanja. Beton i čelik su pri tome potpuno iskorišteni (; ).
4.  Područje 4 opisuje djelovanje ekscentrične sile pritiska. Beton je potpuno iskorišten (), dok naponi u čeliku dostižu granicu tečenja.
5.  Područje 5 opisuje djelovanje ekscentrične sile pritiska sa malim ekscentricitetom. Cijeli presjek je pri tome izložen naponima pritiska (neutralna osa se nalazi na ivici ili van presjeka). Ukoliko se neutralna osa nalazi na ivici presjeka, dilatacije u najopterećenijoj ivici betona se ograničavaju na vrijednost Kako se smanjuje ekscentricitet, ograničavaju se dilatacije u opterećenijoj ivici uslovom da dijagram dilatacija pri graničnom stanju loma mora prolaziti kroz tačku C koja je definisana vertikalnom linijom koja označava vrijednost i linijom iz tačke B ka suprotnoj ivici presjeka. Shodno tome, pri centričnom pritisku, dilatacije u betonu se ograničavaju na vrijednost (vrijednosti u zagradama su za klase betona ).

U nastavku će biti prikazan postupak proračuna presjeka armirano-betonskih greda prema EC2, na uticaje momenta savijanja sa normalnom silom, momenta torzije i transverzalne sile.