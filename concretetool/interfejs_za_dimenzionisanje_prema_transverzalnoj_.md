## Interfejs za dimenzionisanje prema transverzalnoj sili {#interfejs-za-dimenzionisanje-prema-transverzalnoj-sili}

Treći dio programa čini grafički interfejs za dimenzionisanje presjeka prema transverzalnoj sili. Za proračun za transverzalnu silu potrebno je pored čvrstoće na zatezanje i prečnika uzengija usvojiti njihovu sječnost i ugao Svi ostali parametri koji se koriste u proračunu ( koeficijenti sigurnosti, itd.) već su prethodno definisani u prvom dijelu programa. Na taj način se izbjegava dvostruki unos.

Korisnik sada može zadati vrijednost i kliknuti na dugme _Izračunaj s,_ kako bi program izračunao potreban razmak uzengija . Proračun se obavlja prema modelu opisanom u dijelu 9.

Kao rezultat proračuna program generiše dva dijagrama koji opisuju zavisnost smičuće nosivosti (lijevi dijagram) i dodatne sile zatezanja (desni dijagram) od količine poprečne armature , slika 13.1\. Pored toga, program tabelarno prikazuje rješenje proračuna, i to potrebni razmak između uzengija , , smičuću nosivost (koja odgovara zadanoj transverzalnoj sili ), dodatnu silu zatezanja i potrebnu dužinu prepuštanja armature . Dato rješenje predstavljeno je crvenim tačkama na dijagramima, dok horizontalna crvena linija predstavlja maskimalnu smičuću nosivost koju dati presjek može ostvariti. Za zadanu silu preko te vrijednosti, potrebno je usvojiti jači presjek.

Slika 13.1 - Grafički interfejs za dimenzionisanje prema transverzalnoj sili

U narednom koraku korisnik usvaja razmak između uzengija , dok klikom na dugme _Izračunaj Vrd_ program računa iste parametre, ovaj put za usvojenu količinu poprečne armature, i oni se prikazuju u drugom redu tabele, ispod potrebnih vrijednosti. Odgovarajuće tačke na dijagramima su označene zelenom bojom. Program takođe vrši provjeru da li je usvojeni razmak u skladu sa minimalnim i maksimalnim koje propisuje Evrokod.

Na ovaj način, korisnik dobija bolji pregled ostvarene rezerve smičuće nosivosti, u poređenju sa uobičajenim ručnim proračunom, gdje projektant pretpostavlja vrijednost ugla pa za nju računa potrebnu količinu armature i provjerava da li je tražena nosivost postignuta. S obzirom da program za usvojen razmak uzengija računa i vrijednost za koju se ostvaruje maksimalna smičuća nosivost presjeka, korisnik može jednostavno provjeriti tačnost proračuna.