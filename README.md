# Proračun AB konstrukcija prema EC2 {#prora-un-ab-konstrukcija-prema-ec2}

Diplomski rad

Mentor: Student:

prof. dr Mato Uljarević Saša Tatar

Banja Luka, juni 2016.

UNIVERZITET U BANJOJ LUCI

ARHITEKTONSKO-GRAĐEVINSKO-GEODETSKI FAKULTET

GRAĐEVINSKI ODSJEK

University of Banja LukaFaculty of Architecture, Civil Engineering and GeodesyVojvode Stepe Stepanovića 77/378000 Banja LukaBosnia and Herzegovina[http://aggfbl.org/](http://aggfbl.org/)

Diploma thesis / Diplomski rad

**MATLAB reinforced concrete section design tool**

**Abstract**

In past, hand calculations were the only way to design reinforced concrete sections. With the rapid development of computers, engineers are now able to perform more complex calculations faster and with greater precision, achieving more economical solutions. The goal of this thesis was to create an easy to use reinforced concrete section design tool with GUI. The result is a MATLAB program called _ConcreteTool_ which can be used to design reinforced concrete beam sections (rectangular and T sections) subjected to bending, shear and torsion loads, according to Eurocode 2\. Numerical example results obtained by ConcreteTool are compared against another commercial software called BETONexpress by RUNET.

**Keywords:** Matlab, reinforced concrete, section design, Eurocode.

**MATLAB program za dimenzionisanje AB presjeka**

**Sažetak**

U relativno bliskoj prošlosti, dimenzionisanje AB presjeka se vršilo isključivo ručno. Naglim razvojem računara, inženjeri su sada u mogućnosti da rješavaju mnogo kompleksnije probleme mnogo brže, preciznije i ekonomičnije. Cilj ovog rada bio je izrada jednostavnog programa sa grafičkim interfejsom za dimenzionisanje AB presjeka prema Evrokodu 2\. Rezultat je MATLAB program pod nazivom _ConcreteTool,_ koji se može koristiti za dimenzionisanje AB grednih presjeka izloženih uticajima momenta savijanja, transverzalne sile i momenta torzije. Rezultat proračuna brojnog primjera upoređen je sa drugim komercijalnim programom pod nazivom BETONexpress (RUNET).

**Ključne riječi:** Matlab, armirani beton, dimenzionisanje presjeka, Evrokod.

Author: Saša TatarSupervisor: Prof. Dr. Mato Uljarević

Banja Luka, June 2016

![Creative Commons License](export/assets/creative_commons_license.png)This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

Predgovor

Ovaj diplomski rad je urađen u periodu od januara do juna 2016\. godine na Arhitektonsko-građevinsko-geodetskom fakultetu u Banjaluci, pod mentorstvom prof. dr Mate Uljarevića, kome se ovom prilikom zahvaljujem na pomoći i podršci.

Takođe želim da se zahvalim asistentima Radovanu Vukomanoviću i Draganu Zrniću na izuzetno korisnim diskusijama i savjetima.

Nadam se da će ovaj rad biti od koristi svakome ko želi da stekne dodatno znanje i dublje razumijevanje teorije proračuna AB presjeka prema Evrokodu, pogotovo imajući u vidu neažurnost odgovarajuće literature na našem jeziku. Posebno bih istakao dio rada koji objašnjava proračun transverzalne sile i momenta torzije prema modelu promjenljivog ugla pritisnutih dijagonala, s obzirom da nisam uspio pronaći ni jednu domaću knjigu ili publikaciju koja to adekvatno obrađuje.

S tim na umu, ovaj rad je objavljen pod _Creative Commons_ licencom koja omogućava njegovo slobodno dijeljenje, mijenjanje i korištenje u drugim radovima, čak i u komercijalne svrhe.

Na kraju, zahvaljujem se svojoj porodici na njihovoj bezrezervnoj podršci i strpljenju za vrijeme trajanja mog studija.

Saša TatarBanja Luka, juni 2016\. godine