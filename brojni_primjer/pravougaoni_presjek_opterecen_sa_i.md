## Pravougaoni presjek opterećen sa i {#pravougaoni-presjek-optere-en-sa-i}

Pravougaoni presjek dimenzija izložen je djelovanju momenta savijanja , transverzalne sile , i momenta torzije . Za klasu betona i karakterističnu čvrstoća armature potrebno je izračunati neophodnu količinu podužne i poprečne armature.

Uzeti da je ; zaštitni sloj betona , i da se koriste uzengije

U tabeli su prikazani uporedni rezultati proračuna programa ConcreteTool i BETONexpress:

Tabela 15.1 – Uporedni rezultati proračuna programa ConcreteTool i BETONexpress

| **Oznaka** | **Mjerna jedinica** | **Potrebno** | **Usvojeno** |
| --- | --- | --- | --- |
|  |  | **ConcreteTool** | **BETONexpress** | **ConcreteTool** | **BETONexpress** |
|  |  | 20,03 | 20,11 | 19,64 | 19,64 |
|  |  | 0,82 | 0,98 | 3,08 | 3,08 |
|  |  | 320 | 320 | 325,51 | 324,52 |
|  | - | 1,81 | 1,19 | 1,43 | 1,19 |
|  |  | 461.75 | 71,35 | 511,50 | 511,50 |
|  |  | 59.77 | 534,85 | 66,21 | 66,21 |
|  | - | 1,00 | 0,85 | 0,90 | 0,85 |
|  |  | 11,8 | 15,7 | 14,9 | 16,10 |
|  |  | 9,11 | 6,48 | 7,22 | 9,68 |

U nastavku će biti izvršena provjera rezultata ručnim proračunom.

### Provjera nosivosti za moment savijanja {#provjera-nosivosti-za-moment-savijanja}

Na slici 15.1 označene su veličine koje se koriste u proračunu.

Slika 15.1 – Presjek b/h = 300/500 mm

Uz pretpostavku da su i pritisnuta i zategnuta armatura ušle u fazu tečenja, dobija se:

Za , koristeći formulu za blok dijagram () dobija se:

Položaj sile pritiska u betonu:

Položaj rezultantnih sila i:

Provjera dilatacija u pritisnutoj armaturi:

Maksimalni reaktivni moment savijanja:

Oba programa pokazuju dobro poklapanje sa ručno dobijenom vrijednošću nosivosti na savijanje za prethodno usvojenu armaturu. Mala odstupanja u potrebnim količinama pristisnute i zategnute armature posljedica su različitih početnih pretpostavki statičke visine .

### Provjera nosivosti za transverzalnu silu i moment torzije {#provjera-nosivosti-za-transverzalnu-silu-i-moment-torzije}

Uočljiva je razlika dva programa u pristupu proračunu potrebne poprečne i podužne armature za kombinovan uticaj transverzalne sile i momenta torzije .

BETONexpress usvaja fiksnu vrijednost ugla kosih prslina, , i za njega vrši kontrolu nosivosti i proračun poprečne i podužne armature, što za posljedicu ponekad ima i znatno veće količine poprečne armature od stvarno potrebnih.

S druge strane, ConcreteTool vrši proračun kritične vrijednosti ugla za koju će vrijednost interakcione funkcije biti jednaka jedinici, na osnovu čega se dobija i minimalna potrebna količina poprečne armature. Usvajanjem veće količine poprečne armature od minimalno potrebne, raste i vrijednost ugla pri kojoj dolazi do istovremenog iscrpljenja nosivosti uzengija i pritisnutih betonskih dijagonala, na osnovu čega program vrši novi proračun potrebne količine podužne armature , čime se dobija ekonomičnije rješenje. Pored toga, korisnik ima i bolji uvid u ostvarenu rezervu tj. nivo iskorištenosti maksimalne moguće nosivosti presjeka.

S obzirom da ConcreteTool ulazi u proračun sa nižom vrijednošću ugla , dovoljno je samo za nju izvršiti ručnu provjeru nosivosti presjeka.

Na slici 15.2 su označene pojedine veličine koje se koriste u proračunu.

Slika 15.2 – Ekvivalentni tankozidni presjek

Za zadani presjek i dobija se:

Iz ovoga slijedi da će za sve niže vrijednosti interakciona funkcija biti manja od 1\. Preostaje još da se provjere količine armature koje se dobiju za i :

Dobijene vrijednosti se u potpunosti poklapaju sa onima prikazanim u tabeli 15.1.

U poređenju sa potrebnom količinom poprečne armature dobijene u BETONexpress-u, ostvarena je ušteda od preko 14%.

Iako BETONexpress pravilno računa pojedinačno potrebne količine poprečne armature za transverzalnu silu i moment torzije, program pravi grešku pri sabiranju te dvije vrijednosti:

Naime, program sabira ove vrijednosti bez prethodnog množenja torzione armature sa 2, kao što je objašnjeno u dijelu 10.3, zbog čega se dobija nešto manja ukupna količina poprečne armature () od stvarno potrebne za taj ugao (). U konkretnom slučaju, s obzirom da je presjek projektovan sa značajnom rezervom zbog pretpostavke velikog ugla usvojena armatura je zadovoljavajuća, ali u situacijama kada je iskorištenost presjeka veća, može se desiti da tako dobijena količina armature ne bude dovoljna za prenos projektovanih uticaja, što predstavlja opasan propust.

Pored toga, BETONexpress ne raspoređuje dodatnu podužnu armaturu po zonama, nego za dobijenu količinu automatski usvaja potreban broj šipki po konturi presjeka, što, zbog zaokruživanja, za posljedicu ima mnogo veću usvojenu količinu od stvarno potrebne podužne armature.

Nakon sabiranja podužne armature po zonama, dobijene su sledeće potrebne količine armature:

*   zona zatezanja:
*   zona pritiska:
*   konturna zona:

Na osnovu toga, u programu ConcreteTool usvojen je raspored šipki kao na slici 15.3.

Slika 15.3 - Usvojena armatura