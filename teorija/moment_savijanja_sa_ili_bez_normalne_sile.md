## Moment savijanja sa ili bez normalne sile {#moment-savijanja-sa-ili-bez-normalne-sile}

U zavisnosti od graničnih uticaja koji u presjeku djeluju u kombinaciji sa momentom savijanja, razlikuju se dva osnovna slučaja:

1.  _čisto savijanje_ – javlja se kada je presjek izložen djelovanju momenta savijanja bez normalne sile.
2.  _složeno savijanje_ – javlja se kada se u presjeku, pored momenta savijanja , javlja i normalna sila .

Problem dimenzionisanja armirano-betonskog presjeka za poznate granične uticaje svodi se na dva slučaja:

1.  _vezano dimenzionisanje,_ koje podrazumijeva proračun potrebne površine pritisnute i zategnute armature u elementu poznatih dimenzija poprečnog presjeka,
2.  _slobodno dimenzionisanje,_ koje podrazumijeva proračun dimenzija betonskog poprečnog presjeka i potrebne površine armature.

U slučaju vezanog dimenzionisanja, razlikujemo dva tipa problema:

*   _jednostruko armiran presjek_, za koji se proračunava samo potrebna armatura u zategnutoj zoni, a zanemaruje se uticaj pritisnute montažne armature čija osnovna svrha je da poveže uzengije i poveća žilavost pritisnute zone betona.
*   _dvostruko armiran presjek,_ za koji se proračunava i armatura u pritisnutoj zoni presjeka.

U nastavku će biti objašnjen način iterativnog proračuna koji je pogodan za rad na računaru.

### Čisto savijanje {#isto-savijanje}

#### Vezano dimenzionisanje {#vezano-dimenzionisanje}

Jednostruko armirani presjek proizvoljnog oblika

S obzirom da su u slučaju vezanog dimenzionisanja unaprijed poznate dimenzije presjeka i računski moment savijanja , proračun se svodi na sledeće korake:

1.  Usvajaju se karakteristične čvrtoće betona i armature (, ) i odgovarajući parcijalni koeficijenti sigurnosti za materijale (, i ). U zavisnosti od usvojene klase betona, očitavaju se karakteristične vrijednosti dilatacija za beton ( i ) (prilog _A_) na osnovu kojih se definiše računski dijagram napon-dilatacija za beton u obliku parabole i prave.
2.  Pretpostavlja se položaj neutralne ose , na osnovu čega je određen dijagram dilatacija (slika 8.1b):

(8.1)

(8.2)

1.  Računa se rezultantna sila pritiska u betonu tako što se integrale naponi pritiska po pritisnutoj površini betona (slika 8.1a):

(8.3)

pri čemu je funkcija koja opisuje promjenu širine presjeka po visini (za pravougaone presjeke ), a zavisnost se dobija uvrštavanjem izraza 8.1 u izraz 5.1.

Tačka djelovanja sile može se odrediti preko sledećeg izraza:

(8.4)

Za proračun gore navedenih izraza najpogodnije je koristiti neku od numeričkih metoda.

1.  Uz pretpostavku da se težište zategnute armature nalazi na rastojanju od pritisnute ivice betona, dobija se da je krak unutrašnji sila (slika 8.1d):

(8.5)

na osnovu čega se može izračunati moment nosivosti presjeka:

(8.6)

Ukoliko je , usvaja se plići položaj neutralne ose, tj. umanjuje se , odnosno ukoliko je , se povećava. Za novu vrijednost ponavljaju se prethodna tri koraka, dok se ne dobije uz zadovoljavajuću preciznost.

1.  Na osnovu izraza 8.2 računaju se dilatacije () u armaturi. U zavisnosti od usvojenog računskog dijagrama za čelik, na osnovu izraza 5.2 odnosno 5.3 dobija se i napon (). Konačno, iz uslova ravnoteže normalnih sila:

(8.7)

potrebna količina armature dobija se preko izraza:

(8.8)

1.  Usvaja se raspored šipki i računa njihovo težište. U slučaju većeg odstupanja od pretpostavljene vrijednosti , postupak se ponavlja za novo .

Slika 8.1 - Jednostruko armirani T presjek sa vutama opterećen na savijanje

Da bi se obezbijedila dovoljna sposobnost rotacije presjeka (naročito kod statički neodređenih nosača) potrebno je ograničiti relativnu visinu pritisnute zone (). Ova granica zavisi od klase betona i od duktilnosti čelika. Prema EC2 date su granične vrijednosti relativne visine pritisnute zone iz kojih slijedi i odgovarajuća vrijednost momenta savijanja do koje se presjek može armirati jednostrukom armaturom.

Kod primjene teorije elastičnosti i gdje nije izvršena preraspodjela momenata savijanja:

(8.9)

Kod primjene teorije plastičnosti bez posebnog dokaza sposobnosti rotacije presjeka:

(8.10)

Iz tog razloga za početnu pretpostavku položaja neutralne ose u dugom koraku može se usvojiti , u zavisnosti od usvojene klase betona i primijenjene teorije.

Dvostruko armirani presjek proizvoljnog oblika

Kada su dimenzije poprečnog presjeka ograničene, a pri tom se ne može povećati kvalitet betona, može se javiti slučaj da jednostruko armiran presjek nije u stanju da primi granični moment savijanja uz zadovoljenje prethodno navedenih kriterijuma. Tada se rade dvostruko armirani presjeci, kod kojih se projektuje armatura u pritisnutoj zoni presjeka, slika 8.2\. U nastavku opisani postupak je primjenljiv na bilo koji oblik presjeka, ali je jednostavnosti radi na slici prikazan pravougaoni presjek.

Slika 8.2 - Dvostruko armiran presjek

Dodatna armatura u pritisnutoj zoni zahtijeva i dodatnu zategnutu armaturu , kako bi uslovi ravnoteže normalnih sila bili zadovoljeni.

Ako sa označimo graničnu vrijednost momenta savijanja koju može da prihvati jednostruko armiran presjek za najniži dopušteni položaj neutralne ose, tada je:

pri čemu se vrijednost dobije prateći korake definisane za proračun jednostruko armiranih presjeka kada se usvoji prema izrazu 8.9.

Razlika momenata se prihvata spregom unutrašnjih sila i , odnosno pritisnutom i dodatnom zategnutom armaturom. Na osnovu poznatih dilatacija i pretpostavljenih položaja težišta pritisnute i zategnute armature ( i ), prema izrazu 5.2, odnosno 5.3, u zavisnosti od usvojenog računskog dijagrama čelika, mogu se izračunati naponi u armaturi. Obično se usvaja .

Za poznate napone, potrebna površina pritisnute armature određuje se iz izraza:

(8.11)

Iz uslova ravnoteže unutrašnjih horizontalnih sila (), potrebna dodatna zategnuta armatura je:

Konačno, ukupna površina zategnute armature određuje se kao:

(8.12)

Iako to nije regulisano standardom, preporuka je da se količina pritisnute armature ograniči na do jednu trećinu zategnute armature (), što se može postići i ograničavanjem maksimalnog računskog momenta za dvostruko armirane presjeke na . Ukoliko taj uslov nije ispunjen, potrebno je usvojiti veći presjek.

#### Slobodno dimenzionisanje {#slobodno-dimenzionisanje}

Slobodno dimenzionisanje se obično svodi na određivanje potrebne visine presjeka , nakon što je prethodno pored karakteristika materijala usvojena i širina presjeka , ili u slučaju T presjeka, dimenzije flanše. Za uobičajene dimenzije greda, širina presjeka se bira u granicama od 25 do 50 cm, najčešće oko 30 cm. Izbor širine presjeka zavisi i od uslova pravilnog smještaja armature kao i od veličine transverzalnih sila.

Visina presjeka se može odrediti tako što se usvoje projektovane dilatacije zategnute armature () koje će osigurati najavljeni lom presjeka. Za dilatacije u zategnutoj armaturi između 7 i 10‰, dobijaju se i ekonomski i tehnički opravdane dimenzije presjeka i količine armature.

Iterativni postupak za proračun visine i potrebne količine armature odvija se slično kao kod jednostruko armiranih presjeka:

1.  Pretpostavi se početna visina pritisnute zone , npr. .
2.  Na osnovu izraza 8.3 i 8.4 izračuna se rezultantna sila pritiska u betonu () i njena tačka djelovanja ().
3.  Na osnovu sličnosti trouglova, određuje se statička visina presjeka na kojoj se javlja usvojena vrijednost dilatacija:

Ukupna visina presjeka procjenjuje se na osnovu pretpostavke da je .

1.  Za poznatu statičku visinu , prema izrazima 8.5 i 8.6računa se krak unutrašnjih sila i moment nosivosti presjeka .

Ukoliko je , usvaja se plići položaj neutralne ose, tj. umanjuje se , odnosno ukoliko je , se povećava. Za novu vrijednost ponavljaju se prethodna dva koraka, dok se ne dobije uz zadovoljavajuću preciznost.

1.  U zavisnosti od usvojenog računskog dijagrama za čelik, na osnovu izraza 5.2, odnosno 5.3, dobija se i napon (). Konačno, iz uslova da je , potrebna količina armature se dobija preko izraza 8.8.

### Složeno savijanje {#slo-eno-savijanje}

U slučaju kada je presjek izložen djelovanju momenta savijanja u kombinaciji sa normalnom silom pritiska ili zatezanja (_složeno savijanje_), u zavisnosti od dijagrama dilatacija pri graničnom stanju loma, razlikuju se sledeći slučajevi:

*   područje velikog ekscentriciteta – kada se neutralna osa nalazi unutar poprečnog presjeka. Ovo stanje dilatacija se obično susreće kod greda (kada je dominantan uticaj od momenta savijanja) i kod ekscentrično opterećenih stubova (kada je dominantan uticaj od normalne sile).
*   područje malog ekscentriciteta – kada se neutralna osa nalazi na samoj ivici ili van presjeka, tj. čitav presjek je izložen jednoznačnim naponima pritiska ili zatezanja. Ovo stanje dilatacija je karakteristično za ekscentrično opterećene stubove ili zatege.

U okviru ovog rada biće prikazan način proračuna za gredne presjeke izložene normalnoj sili u području velikog ekscentriciteta, sa dominantnim uticajem od momenta savijanja.

Na slici 8.3 prikazan je opšti slučaj presjeka (sa pritisnutom armaturom) u kom djeluje moment savijanja i normalna sila . Presječne sile stoje u ravnoteži sa unutrašnjim silama (slika 8.3d).

Slika 8.3 - Proračunski model poprečnog presjeka napregnutog na složeno savijanje - veliki ekscentricitet

Iz uslova ravnoteže normalnih sila, dobije se:

Iz uslova da je suma svih momenata u odnosu na težište zategnute armature jednaka nuli, dobije se:

pri čemu je:

udaljenost težišta presjeka () od pritisnute ivice betona,

računski moment savijanja u odnosu na težište zategnute armature.

Dalji proračun se svodi na onaj definisan za čisto savijanje, pri čemu se umjesto vrijednosti uvrštava :

1.  Računa se granična vrijednost momenta savijanja koju može da primi jednostruko armirani presjek.
2.  Ukoliko je , vrši se proračun za jednostruko armiran presjek, odnosno, traži se položaj neutralne ose za koji je zadovoljena jednačina:

Potrebna površina armature se određuje iz izraza:

(8.13)

Prvi član na desnoj strani gornjeg izraza odgovara izrazu za potrebnu površinu armature presjeka opterećenog na čisto savijanje (izraz 8.8). Kako normalna sila unosi značajne napone pritiska u element opterećen na složeno savijanje, to se ukupna površina armature umanjuje za iznos .

Nakon usvajanja broja i prečnika šipki armature, te njihovog rasporeda po poprečnom presjeku, vrši se kontrola da li je . Ukoliko taj uslov nije zadovoljen, proračun se ponavlja za dobijenu vrijednost statičke visine .

1.  Ukoliko je , vrši se proračun za dvostruko armiran presjek, pri čemu je:

Ukupna količina zategnute armature se određuje iz izraza:

(8.14)

dok se potrebna površina pritisnute armature određuje iz izraza:

(8.15)

U slučaju kada je dominantan uticaj normalne sile, prethodno prikazanim proračunom se dobija mnogo veća površina pritisnute armature u odnosu na površinu zategnute armature, tj. dobije se da značajan dio sile pritiska nosi pritisnuta armatura, što nije realno. U takvim situacijama presjek je poželjno dimenzionisati kao stub, sa simetričnom raspodjelom pritisnute i zategnute armature.

Iako nije jasno definisana granica do koje se uticaj momenta savijanja može smatrati dominantnim, dobra je praksa pridržavati se prethodno date preporuke za odnos površina pritisnute i zategnute armature (). Primjera radi, u britanskoj literaturi definisana je granična vrijednost normalne sile do koje se pravougaoni presjeci u oblasti velikog ekscentriciteta mogu dimenzionisati na ovaj način, i to: (pri čemu je karakteristična čvrstoća betonske kocke na pritisak).