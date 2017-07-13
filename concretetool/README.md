# ConcreteTool {#concretetool}

Program za dimenzionisanje pravougaonih i T armirano-betonskih presjeka prema Evrokodu rađen je u MATLAB-u R2014b. Program je napravljen sa pratećim grafičkim interfejsom, što omogućava njegovo jednostavnije i fleksibilnije korištenje. Korisnik je u mogućnosti da mijenja pojedinačne parametre presjeka (dimenzije, klasu betonu, čvrstoću armature, i sl...) i da istovremeno vidi efekat koji određena promjena ima na nosivost presjeka, što omogućava lakše pronalaženje optimalnog rješenja. Pored toga, izgled poprečnog presjeka kao i prečnici usvojene podužne armature se prikazuju u stvarnoj razmjeri. Sve to doprinosi sticanju boljeg „osjećaja“ projektanta za odnose dimenzija unutar presjeka i samo projektovanje presjeka za uticaje momenta savijanja sa normalnom silom i momenta torzije sa transverzalnom silom.

Program se sastoji od preko 3500 linija koda ispisanog u više datoteka koje je potrebno držati u jednom folderu, a pokreće se kucanjem komande _ConcreteTool_ u Matlabu.

Algoritam programa je rađen na principima objektno-orijentisanog programiranja i sastoji se od tri glavne klase:

1.  CrossSection – glavna klasa koja objedinjuje sve parametre koji definišu presjek (dimenzije, klasa betona, vrsta armature, zaštitni sloj...) i funkcije za njegovo modelovanje (generisanje izgleda presjeka sa pratećim dijagramima, proračun potrebne količine armature, dodavanje armature, proračun momenta nosivosti , itd...),
2.  Rebar – klasa koja predstavlja šipku armature,
3.  VTModeler – klasa koja objedinjuje sve parametre potrebne za dimenzionisanje presjeka prema momentu torzije i transverzalnoj sili, te funkcije koje vrše proračun i generišu prateći dijagram.

Grafički interfejs programa je podijeljen u četiri glavne cjeline, pri čemu svaka cjelina predstavlja jedan jezičak, tj. _tab_:

1.  Presjek – za definisanje presjeka,
2.  Moment savijanja – za proračun potrebne količine armature i nosivosti na savijanje ,
3.  Transverzalna sila – za proračun potrebne poprečne i dodatne podužne armature i nosivosti na smicanje ,
4.  Moment torzije – za proračun potrebne poprečne i podužne armature za kombinovani uticaj momenta torzije i transverzalne sile .

Dodatni dio programa čini poseban prozor sa grafičkim interfejsom za jednostavno dodavanje šipki podužne armature po zonama poprečnog presjeka.

U nastavku će svaki dio biti detaljnije opisan.