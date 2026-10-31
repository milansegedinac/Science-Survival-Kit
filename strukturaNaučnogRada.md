# 1 Struktura naučnog rada
Pored toga što naučni rad reflektuje smisleno i značajno naučno istraživanje, tekst **mora** da zadovolji kriterijume strukture da bi se smatrao naučnim radom. Pravi naučni rad ima sledeće sekcije.

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Related Work](#related-work)
- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
- [Results](#results)
- [Discussion](#discussion)
- [Conclusion](#conclusion)

Važno je da napomenem da velik broj radova, čak možda i većina, objavljenih u visokokotiranim časopisima ne zadovoljava u potpunosti ovu strukturu. Struktura koju prikazujem u ovom tekstu je idealizovana. Odstupanja od te strukture ne znače nužno da rad neće biti objavljen, kao što ni poštovanje ove strukture nije garant da će rad biti prihvaćen. Ali svako odstupanje od strukture naučnog rada otvara prostor recenzentima za kritiku tehničkih aspekata rada, a time smanjuje verovatnoću objavljivanja rada i produžava proces korekcija. 

Napominjem još i da je tekst nastao kao uputstvo za pripremu rada iz računarskih nauka za časopis [_Computers in Industry_](https://www.sciencedirect.com/journal/computers-in-industry), ali se lako može primeniti na bilo koje srodno istraživanje.

## Abstract
Svaki časopis ima svoje propozicije pisanja sažetka u kome navodi koliko reči treba da bude i koju strukturu treba da prati. Tako, na primer, Computers in Industry navodi svoje propozicije u [uputstvu za autore](https://www.sciencedirect.com/journal/computers-in-industry/publish/guide-for-authors#writing-and-formatting-abstract).

Kada čitalac inicijalno pregleda radove, vrlo često će imati pristup samo naslovu i apstraktu. Čitav rad će možda morati i da plati. Zato apstrakt treba da bude tako napisan da privuče pažnju potencijalnog čitaoca. Apstrakt se piše kada je rad već potpuno gotov.

Sažetak treba da bude samostalan, odnosno da iz njega čitalac može saznati osnovne nalaze rada čak i ako neće čitati sam rad. Mora biti navedena svrha rada, odnosno motivacija za istraživanje. Pored toga, treba da ugrubo opiše metodologiju koja je korišćena i da uključi glavne nalaze rada (koja istraživačka pitanja su potvrđena, a koja pobijena i da li je potvrđena hipoteza). Apstrakt takođe treba da prikaže i šta je u radu _novo_ i _originalno_.

U sažetku se, tipično, ne navodi literatura. Ukoliko mora da se navede, to treba da budu reference koje će se kasnije pojavljivati i u radu. Takođe, apstrakt ne treba da uvodi nove i neuobičajene skraćenice.

## Introduction
U ovoj sekciji čitalac treba da se uvede u temu. Iako se _Uvod_ čita prvi i to je čitaočev prvi kontakt sa samim radom (mimo pregleda apstrakta), autor ovu sekciju piše na kraju pisanja rada, kada je već napisao zaključak. Sekcija treba da pokrije:

- Širi kontekst istraživanja: industrijski kontekst ako je rad iz industrije. Obrazovni ako je iz obrazovanja. Zašto je oblast u kojoj se pravi istraživanje važna? (1 paragraf)
- Konkretan problem: šta je tačno problem koji se rešava? Zašto je potrebno da se taj problem rešava? (1 paragraf)
- Postojeći pristupi i njihova ograničenja: šta postoji, zašto to ne valja? (1 do 2 paragrafa)
- „Vaše rešenje“: šta ste Vi napravili da biste adresirali ograničenja trenutnog pristupa? (1 paragraf)
- Doprinos: nekoliko stavki (3-4) koje jasno naglašavaju šta je konkretan doprinos istraživanja izloženog u radu. To mogu biti:
    - konceptualni: razvijena je teorija.
    - metodološki: unapređena je metoda, razvijen novi algoritam.
    - tehnička novina: napravljen novi model, definisan novi protokol.
    - artefakt: napravljen je skup podataka, razvijen program.
    - validacija: pokazano je da neki postojeći pristup (ne) radi
 
**Napomena: paragraf o doprinosima istraživanja je najvažniji deo kako uvoda, tako i čitavog rada. Ukoliko doprinos nije jasan iz uvoda, recenzent neće dalje čitati rad i odmah će ga odbiti.**

Naučni rad ima **jedan glavni doprinos**. Ukoliko se ispostavi da rad ima više različitih doprinosa (razvijeno je više različitih teorija, razvijeno više različitih softverskih rešenja) najverovatnije je u pitanju ili više različitih radova ili nijedan rad vredan publikovanja. **Beznačajnost doprinosa ne može se prevazići gomilanjem beznačajnih doprinosa**. Ukoliko je doprinos beznačajan, na primer, ukoliko je teorija koja se predlaže u radu marginalna i neinovativna, rad neće biti bolji ako se doda još jedna marginalna teorija. Samo će biti još gori.

- Pregled strukture rada: koja poglavlja će biti u radu? Mapa puta za čitaoca. (1 paragraf)

## Related Work
Preduslov za naučno istraživanje je da je istraživač upoznat sa oblašću kojom se bavi. Nepoznavanje literature u oblasti prvi je znak neozbiljnosti istraživača, bez obzira na to da li je u pitanju rad koji piše, izlaganje na konferenciji ili diskusija sa kolegama.
 
Upoznatost sa oblašću podrazumeva čitanje stotina, čak i hiljada naučnih radova. Takođe, istraživač mora tokom čitave karijere da ostane u oblasti, tako što stalno prati i čita radove koji se tiču njegovog istraživanja. Ranije je to bilo kroz kupovinu publikacija, pa su ustanove bile pretplaćene na časopise, danas je to kroz digitalne repozitorijume poput [arXiv](https://arxiv.org). Pregled novih publikacija treba da postane deo dnevne rutine istraživača.
 
Pregled literature je prvi korak istraživanja i prethodi identifikovanju problema. Idealno bi bilo da se za pregled literature koristi **systematic literature review** (_SLR_). Postoje jasne i striktne metodološke smernice kako se sprovodi _SLR_, poput [PRISMA metodologije](https://www.prisma-statement.org/). _SLR_ je istraživanje za sebe i radovi koji imaju **samo** dobar i sistematičan pregled literature, pregledni radovi, mogu da se objave i u najboljim časopisima. Preporuka je da _SLR_ bude sastavni deo doktorske teze.

Ukoliko se ne radi o preglednom radu, nego je u pitanju istraživački rad, ne mora se raditi _SLR_.

Preporuka je da se pregled literature organizuje **po temama**, a ne hronološki, ili, još gore, prostim nabrajanjem radova. Ove teme su, tipično:
- Domen primene: ukoliko je rad iz primene računara u industriji, šta se radi u konkretnoj industrijskoj oblasti? Ukoliko je iz obrazovanja, šta se radi u konkretnom domenu obrazovnih istraživanja? Kada se pravi pregled radova iz domena primene, prednost se daje varijansi, a ne količini radova. Bolje je imati manje radova koji tvrde različite stvari, nego puno radova koji samo potvrđuju jedni druge.
- Metodološka oblast: tehnike na kojima se rad zasniva. Osnovne tehnike, poput računanja standardne devijacije, nije potrebno navoditi.
- Jaz u oblasti: nedostatak radova koji se bave istraživanjem predloženim u Vašem radu. **Ukoliko postoje istraživanja koja se bave problemom koji ste rešavali i znate za njih, obavezno morate da ih navedete!** Ne smeju se prikrivati srodna istraživanja, čak i kada to znači da je Vaše istraživanje devalviralo. Izostanak srodnih istraživanja u boljem slučaju se tumači kao neozbiljnost istraživača. U gorem slučaju se tumači kao namerno, maliciozno prikrivanje. Zato je neophodno uraditi pregled literature pre nego što se sprovede istraživanje. Pravljenje pregleda literature nakon što je istraživanje sprovedeno može se protumačiti kao retrofiting istraživanja.

Pregled literature za istraživački rad treba da pokrije između 20 i 100 naučnih radova i treba da ima između 2 i 6 strana.

## Problem Statement

_Problem Statement_ je, tipično, ili zasebna sekcija ili podsekcija odeljka _Methodology_. Ova sekcija treba jasno da odgovori na pitanje _šta_ se u istraživanju radi. To je druga po važnosti sekcija u radu, od nje je važniji samo paragraf o doprinosu u uvodu i zato joj se mora posvetiti posebna pažnja. Sekcija mora da bude jasna i metodološki čista.

Ova sekcija sadrži:
- Narativni opis sistema: u grubim crtama opisati sistem, bez prikaza slučaja i primera upotrebe sistema. Ko su akteri, šta se posmatra, šta se meri, šta se kontroliše? (1-2 paragrafa)
- Formalni, matematički model problema (ako postoji).
- Pretpostavke: šta se uzima u obzir, šta se zanemaruje? (1-2 paragrafa)
- Hipoteza: __najvažnije!__ šta Vaš rad tačno proverava? Šta tačno tvrdite? Hipoteza mora da bude u takvom obliku da se __može pobiti__, odnosno da je apsolutno jasno koji rezultati bi doveli do toga da se hipoteza odbaci. __Naučni rad ima jednu hipotezu.__ Ukoliko rad ima više hipoteza, najverovatnije se radi o više radova.
- Istraživačka pitanja: __važno!__ Proizilaze iz hipoteze. Rad ima nekoliko istraživačkih pitanja, tipično 2 do 4. Za svako istraživačko pitanje je jasno kako se može pobiti. Dobro je da ostvarenost istraživačkih pitanja može da se izmeri i kvantifikuje, pa da se kaže da je ostvareno u izvesnoj meri. Ostvarenost istraživačkih pitanja direktno rezultuje potvrđivanjem ili pobijanjem hipoteze.
- Veza sa metodologijom: metodologija u radu služi da potvrdi ili pobije istraživačka pitanja i time, posredno, potvrdi ili pobije hipotezu. Metodologiji se posvećuje posebna sekcija, ali dobro je da _Problem Statement_ ima vezu ka toj, narednoj sekciji.

## Methodology

Dok _Problem Statement_ daje odgovor na pitanje _šta_ se ispituje, ova sekcija daje odgovor na pitanje _kako_ se sprovodi istraživanje. Kako je ova sekcija vrlo egzaktna, recenzentima je najlakše da je kritikuju i da na njoj „obore“ rad bez puno upuštanja. Tipične primedbe koje recenzenti daju za ovu sekciju tiču se veličine i reprezentativnosti uzorka u slučaju statističke analize ili potrebe za kvantitativnom potvrdom rezultata u slučaju da se koristi kvalitativna metodologija. 

Postoji velik broj potencijalnih metodoloških pristupa naučnom istraživanju i u ovom tekstu će inicijalno biti pokrivena samo dva:
- kvalitativna metoda studije slučaja
- kvantitativna metoda statističke analize

__Napomena__: u slučaju radova u kojima je razvijeno softversko rešenje, sekcija _Methodology_ treba da sadrži podsekciju u kojoj je to rešenje opisano. To bi bila podsekcija _System Architecture_ ili bi se zvala po softverskom paketu koji je razvijen (_PROcurement MultI agent System (PROMIS)_). U njoj se opisuju arhitektura, algoritmi, agenti, protokoli, poslovni procesi, sve ono što pripada samom softveru koji je razvijen. Ta sekcija prikazuje UML dijagrame i navodi slučajeve korišćenja. Pa ipak, ne treba je pisati kao tehničku dokumentaciju, ili, još gore, korisničku dokumentaciju. Umesto toga, treba se fokusirati na one aspekte softvera koji su relevantni za istraživanje. Ova sekcija je najobimnija i u inženjerskim radovima tipično ima 3-5 strana. Pravi, praktičan doprinos inženjerskog naučnog rada nalazi se baš u toj sekciji. Ali, da bi rad imao naučnu vrednost i da ne bi bio prezentacija tehničkog rešenja ili opis patenta, potrebno je i potvrditi da razvijeni softver odgovara na istraživačka pitanja. Zato nakon ove podsekcije sledi podsekcija koja opisuje bilo kvantitativnu, bilo kvalitativnu metodu na kojoj je samo istraživanje sprovedeno.

### Kvalitativne metode: studija slučaja

Studija, odnosno prikaz slučaja, _case study_ je __empirijsko__ istraživanje fenomena u njegovom realnom okruženju. Koristi se kada granice između fenomena i okruženja nisu jasne i kada istraživač nema kontrolu nad događajima koji ispituje. To je čest slučaj u razvoju softvera. Takvo je, na primer, industrijsko okruženje u koje se uvodi multiagentski sistem: sam sistem koji se uvodi organski pripada okruženju i transformiše ga.

Studija slučaja je _kvalitativna metoda_. To znači da je opravdan izbor kada istraživačka pitanja počinju sa _kako_ i _zašto_, a ne sa _koliko_. Ukoliko se na istraživačko pitanje može odgovoriti merenjem i poređenjem, odnosno ukoliko se može kvantifikovati, treba koristiti kvantitativne metode.

**Studija slučaja nije demonstracija.** Najčešća greška u korišćenju studije slučaja je da se slučaj koristi da ilustruje upotrebljivost nekog rešenja. Tada se razvijeni sistem prosto primeni na jedan primer i to se nazove studijom slučaja. Ovakav pristup nije naučno istraživanje. Studija slučaja ne samo da __prikazuje__ slučaj, ona ga i __proučava__ i __analizira__. Dok ilustracija pokazuje da nešto radi, studija slučaja proverava da li hipoteza važi. Zato je važno da iz studije slučaja __direktno proizilaze zaključci vezani za istraživačka pitanja i da ih jasno potvrđuju ili pobijaju__.

Studija slučaja je __egzaktna__ naučna metoda. Česta zabluda je da se studiji slučaja i drugim kvalitativnim metodama pristupa olako i da se tretiraju kao _građani drugog reda_ naučne metodologije. To je nedopustivo.

Sekcija treba da pokrije:

- Izbor slučaja i obrazloženje: zašto baš taj slučaj? Slučaj se bira namerno, a ne zato što je bio dostupan. Slučaj može biti tipičan (predstavlja uobičajenu situaciju), kritičan (ukoliko hipoteza ne važi ovde, ne važi nigde drugo), ekstreman ili jedinstven. Ukoliko se koristi više slučajeva, objasniti zašto ti slučajevi i kako se međusobno razlikuju, a šta ih povezuje. U slučaju uvođenja multiagentskog sistema neophodno je slučaj (procurement) pozicionirati prema ovim pitanjima. (1-2 paragrafa)
- Jedinica analize: šta se tačno analizira? Organizacija, tim, proces, softverski sistem, projekat? Nejasna jedinica analize najčešće znači da istraživačka pitanja nisu jasno i dobro definisana. (1 paragraf)
- Protokol: plan prikupljanja i analize podataka **mora** biti napravljen pre nego što se uđe u slučaj. Protokol definiše koje podatke prikupljamo, od koga i kako ih analiziramo. Protokol napravljen nakon prikupljanja podataka je retrofiting istraživanja. Retrofiting istraživanja se jasno uočava u radu i tumači kao maliciozno narušavanje akademske etike.
- Izvori podataka: intervjui, dokumentacija, arhivski zapisi, posmatranje, artefakti. **Jedan izvor podataka nije dovoljan.** Zaključci moraju biti potvrđeni iz više nezavisnih izvora.
- Analiza podataka: kako se od sirovih podataka stiže do zaključka? Kodiranje, tematska analiza, poređenje obrazaca, izgradnja objašnjenja. Postupak mora biti opisan tako da drugi istraživač može da ga ponovi i da dođe do istog zaključka. U slučaju uvođenja multiagentskog sistema, to znači da se mora jasno objasniti kako su identifikovani benefiti i nedostaci pristupa koji se koristi.
- Veza sa hipotezom: **najvažnije!** I studija slučaja mora da bude falsifikabilan. Pre analize treba jasno navesti kakav nalaz bi pobio hipotezu. Takođe, moraju se razmotriti i eksplicitno odbaciti _alternativna objašnjenja_. Ukoliko se nalaz može objasniti na neki drugi način, a to drugo objašnjenje nije odbačeno, hipoteza nije potvrđena i istraživanje ne stoji.
- Validnost: kako znate da su zaključci ispravni? Validnost konstrukata (merimo ono što tvrdimo da merimo), unutrašnja validnost (uzročna veza nije prividna), spoljašnja validnost (na šta se zaključci mogu uopštiti) i pouzdanost (ponovljivost). (1-2 paragrafa)

Kvantitativno istraživanje koje koristi statističke metode dozvoljava nam da napravimo generalizaciju na _populaciju_. Statistika upravo to i radi: daje nam alat da, na osnovu izmerenih vrednosti pojava iz populacije, zaključimo karakteristike same populacije. Studija slučaja ne dozvoljava takvo uopštavanje, ne omogućuje nam da generalizujemo zaključke na populaciju. Ali to ne znači da studija slučaja ne rezultuje generalizacijom. Umesto generalizacije na populaciju, studija slučaja daje generalizaciju na _teoriju_. Zato tvrdnje u radu moraju biti skromne i precizne: _u ovom slučaju, pod ovim uslovima, hipoteza je potvrđena_. Tvrdnja da rezultati važe za čitavu industriju, u svakoj situaciji u kojoj se radi bilo kakav _procurement_, na osnovu studije jednog slučaja nabavki, može da diskvalifikuje rad zbog neopravdane generalizacije. Tako bi na primer bilo:
- __Neopravdano tvrditi__: „Predloženi pristup unapređuje procurement.“
- __Opravdano tvrditi__: „U procurement procesima sa ponovljenim nabavkama standardizovanih artikala i više konkurentnih dobavljača, automatska evaluacija ponuda skraćuje ciklus nabavke, zato što uklanja ručno poređenje ponuda kao usko grlo. Mehanizam ne deluje kada su artikli nestandardni, jer tada evaluacija zahteva ekspertsku procenu.“

### Kvantitativne metode
TODO

## Results

Ova sekcija odgovara na pitanje _šta je dobijeno_. Rezultati se prikazuju, ali se njihove implikacije ne tumače u ovoj sekciji. Tumačenju rezultata, poređenju sa literaturom i implikacijama posvećuje se posebna sekcija, _Discussion_. Mešanje ove dve sekcije je česta greška: čitalac više ne može da razlikuje šta je izmereno ili uočeno, a šta autor misli o tome.

Rezultati se organizuju **po istraživačkim pitanjima**, a ne hronološki, niti, još gore, redosledom kojim su podaci prikupljeni. Svako istraživačko pitanje dobija svoju podsekciju. Ukoliko neki rezultat ne odgovara ni na jedno istraživačko pitanje, on ne pripada radu. Isto tako, ukoliko nekom istraživačkom pitanju ne odgovara nijedan rezultat, to istraživačko pitanje nije deo rada.

Sekcija treba da pokrije:

- Odgovor na svako istraživačko pitanje: za svako pitanje prikazati rezultate i na kraju podsekcije jasno navesti da li je kriterijum za pobijanje, kako je definisan u metodologiji, ispunjen ili ne.
- Negativne rezultate: rezultati koji ne idu u prilog hipotezi **moraju** biti prikazani. Prikazivanje samo povoljnih rezultata (_cherry-picking_) je ozbiljna povreda naučne etike. Negativan rezultat koji je pošteno prikazan je validan naučni nalaz, a nikako nije _greška_.
- Odgovor na hipotezu (__najvažnije!__): na kraju sekcije, u jednom paragrafu, navesti da li je hipoteza potvrđena ili pobijena, i na osnovu kojih rezultata.

S obzirom na to da se kvalitativne i kvantitativne metode značajno razlikuju, i rezultati se u njima drugačije prikazuju.

### Studija slučaja

- Nalazi: rezultati se prikazuju kao nalazi, organizovani po istraživačkim pitanjima. Svaki nalaz **mora** biti povezan sa podacima referencom na konkretan izvor (I3, D2, zapis iz sistema).

  _Primer: „Referenti su predloge sistema prihvatali bez izmena u 71 % slučajeva (zapisi MAS-a, n = 1.420). Izmene su se uglavnom odnosile na rok isporuke kod novih dobavljača (I2, I5, I7), za koje sistem nije imao istoriju pouzdanosti.“_

- Citati: citati učesnika nisu ukras ili ilustracija, nego služe kao dokaz ispunjenosti ili pobijanja istraživačkog pitanja. Citat se navodi samo kada potkrepljuje nalaz (bilo pozitivan, bilo negativan), uz oznaku izvora. Nalaz se ne može zasnivati samo na citatu jednog učesnika.
- Povezanost nalaza: za svaki nalaz treba pokazati da je potvrđen iz više izvora. Ukoliko se izvori ne slažu, to se navodi kao rezultat, a ne skriva se.

  _Primer: „Prema intervjuima, ciklus nabavke se značajno skratio (I1, I3, I4). Zapisi iz ERP sistema potvrđuju skraćenje medijane ciklusa sa 6,5 na 3 radna dana za redovne nabavke, ali ne pokazuju promenu kod nabavki od novih dobavljača.“_

- Kontradiktorni dokazi: podaci koji ne idu u prilog nalazu **moraju** biti prikazani.
- Alternativna objašnjenja: za svako alternativno objašnjenje navedeno u metodologiji prikazati podatke koji ga potvrđuju ili odbacuju.

  _Primer: „U posmatranom periodu nije bilo promene dobavljača niti smanjenja obima nabavke (D3, zapisi ERP sistema), pa se skraćenje ciklusa ne može pripisati tim faktorima.“_

### Kvantitativna analiza
TODO

## Discussion

Nakon sekcije sa rezultatima, u kojima je prikazano _šta je u radu dobijeno_, sledi sekcija u kojoj se diskutuje _šta to znači_. Ovo je sekcija u kojoj autor tumači rezultate i objašnjava _šta je dobio_, _zašto je to dobio_ i _koja su ograničenja_.

U ovoj sekciji se **ne uvode novi rezultati**. Svaka tvrdnja u diskusiji mora se oslanjati na rezultate koji su već prikazani u sekciji _Results_. Takođe, diskusija nije ponavljanje rezultata drugim rečima. Ukoliko se paragraf diskusije može izbaciti, a da čitalac ne izgubi ništa što već nije znao iz rezultata, taj paragraf ne treba da postoji.

Sekcija sadrži:

- Tumačenje rezultata: zašto su rezultati takvi kakvi jesu? Kakav mehanizam ih objašnjava? Posebnu pažnju posvetiti neočekivanim i negativnim rezultatima. Oni često govore više od očekivanih. (2-3 paragrafa)

  _Primer: „Skraćenje ciklusa nabavke izostalo je kod novih dobavljača. To je posledica dizajna sistema: agent za evaluaciju rangira ponude i po istoriji pouzdanosti, a za nove dobavljače te istorije nema. Referenti su zato predloge ručno proveravali, pa ručno poređenje ponuda kod njih nije uklonjeno.“_

- Značenje odluke o hipotezi: odluka o tome da li je hipoteza potvrđena ili pobijena donosi se u sekciji _Results_, na osnovu kriterijuma definisanog u metodologiji. U diskusiji se ta odluka **ne preispituje**, nego tumači: ukoliko je hipoteza potvrđena, pod kojim uslovima važi i koliko daleko seže? Ukoliko je pobijena, šta se iz toga može naučiti? __Hipoteza se ne sme naknadno menjati da bi se uklopila u rezultate.__ (1 paragraf)

- Poređenje sa literaturom: da li su rezultati u skladu sa radovima iz sekcije _Related Work_ ili su u suprotnosti sa njima? Ukoliko su u suprotnosti, objasniti zašto. Radovi sa kojima se rezultati porede **moraju** biti navedeni u _Related Work_. Uvođenje novih radova u diskusiji je znak da pregled literature nije bio potpun. (1-2 paragrafa)

- Implikacije: šta rezultati znače za teoriju, a šta za praksu? Teorijske implikacije pokazuju kako rad menja razumevanje oblasti. Praktične implikacije pokazuju šta praktičar treba da uradi drugačije. Implikacije moraju direktno proizlaziti iz rezultata. (1-2 paragrafa)

  _Primer praktične implikacije: „Pre uvođenja multiagentskog sistema u nabavku, preduzeće treba da obezbedi istoriju isporuka za dobavljače koji se uključuju u sistem. U suprotnom, sistem kod tih dobavljača ne smanjuje manuelni rad.“_

- Ograničenja: šta rezultati **ne** pokazuju? Ograničenja se navode iskreno i konkretno, uz objašnjenje kako svako ograničenje utiče na zaključke i šta je urađeno da se njegov uticaj smanji. Uopštena ograničenja, poput „uzorak je mali“ ili „potrebno je još istraživanja“, ne govore ništa. (1-2 paragrafa)

  _Primer: „Istraživanje je sprovedeno u jednom preduzeću, pri čemu su nabavke uglavnom bile ponovljene i za standardizovan materijal. Zaključci zato ne važe za nabavke kapitalne opreme, gde je svaka nabavka jedinstvena i zahteva ekspertsku procenu.“_

### Studija slučaja

U studiji slučaja diskusija je mesto gde se vrši generalizacija na teoriju. Na osnovu rezultata se konačno formuliše teorijska propozicija: mehanizam, uslovi i ishod. Uslovi propozicije moraju biti izvedeni iz rezultata, a ne pretpostavljeni.

_Primer: „U procesima nabavke sa ponovljenim nabavkama standardizovanog materijala i dobavljačima za koje postoji istorija isporuka, multiagentski sistem skraćuje ciklus nabavke, zato što uklanja ručno poređenje ponuda kao usko grlo. Kada istorija isporuka ne postoji, mehanizam ne deluje, jer referent ponovo preuzima poređenje.“_

Ovako formulisana propozicija je preciznija od polazne hipoteze, jer je slučaj otkrio dodatni uslov: postojanje istorije isporuka. To je legitiman rezultat studije slučaja. Ali polazna hipoteza se ne briše niti prepravlja: u radu se jasno navodi šta je bila hipoteza, šta je slučaj pokazao i kako je propozicija precizirana. Precizirana propozicija nije potvrđena ovim slučajem, nego je predlog za proveru u narednim slučajevima.

## Conclusion

Zaključak je poslednje što čitalac pročita i, uz apstrakt i uvod, često jedino što pročita. Zato zaključak **mora** da bude samostalan: čitalac koji pročita samo zaključak treba da zna šta je bio problem, šta je urađeno, šta je dobijeno i šta to znači.

U zaključku se ne uvode novi rezultati, nova tumačenja niti nova literatura. Sve što je u zaključku već je rečeno u radu. Zaključak to sažima, ali ga ne ponavlja doslovno. Iako su često vrlo slični, zaključak ne sme da bude prosto kopija apstrakta.

Sekcija treba da pokrije:

- Problem i pristup: šta je bio problem i kako mu se pristupilo. (1 paragraf, 2-3 rečenice)
- Odgovori na istraživačka pitanja i odluka o hipotezi: kratak, direktan odgovor na svako istraživačko pitanje, uz ključne brojeve ili nalaze, i jasnu konstataciju da li je hipoteza potvrđena ili pobijena. Zaključak ne sadrži opširna objašnjenja, ona se navode u diskusiji. (1 paragraf)
- Doprinos: šta rad donosi oblasti. Doprinos u zaključku **mora** biti isti kao doprinos najavljen u uvodu. Ukoliko se razlikuju, ili uvod obećava više nego što je urađeno, ili je rad tokom pisanja promenio smer, uvod mora da se prepravi i prilagodi zaključku. (1 paragraf)
- Budući rad (_future work_): konkretni pravci istraživanja koji proističu iz ograničenja i nalaza ovog rada. Svaki pravac mora biti vezan za konkretno ograničenje ili nalaz. Uopšteni pravci, poput „primena u drugim oblastima“ ili „dalje unapređenje sistema“, ne govore ništa i ne treba ih navoditi. (1 paragraf)

Zaključak ima između pola strane i jedne strane.

U studiji slučaja, budući rad se prirodno nastavlja na teorijsku propoziciju iz diskusije. Propozicija precizirana na jednom slučaju nije potvrđena tim slučajem, nego je predlog za proveru. Zato je osnovni pravac budućeg rada replikacija: provera propozicije u slučajevima koji dele iste uslove (doslovna replikacija) i u slučajevima koji ih namerno ne dele, gde se očekuje drugačiji ishod (teorijska replikacija).

_Primer: „Studija slučaja je pokazala da multiagentski sistem skraćuje ciklus nabavke standardizovanog materijala, ali samo kod dobavljača za koje postoji istorija isporuka. Naredno istraživanje treba da proveri ovu propoziciju u preduzeću sa većim udelom novih dobavljača, gde bi, prema propoziciji, efekat trebalo da izostane. Ukoliko efekat ipak nastupi, uslov o istoriji isporuka nije neophodan i propoziciju treba odbaciti.“_

Uvod se piše poslednji, nakon zaključka. Kada je zaključak napisan, uvod i zaključak treba pročitati jedan za drugim: problem, rešenje i doprinos moraju se poklapati. Uvod najavljuje ono što zaključak potvrđuje.

# 2 korišćenje AI
Izdavači imaju svoje politike koje određuju korišćenje AI. Na primer, Elsevier ima [politiku korišćenja generativne AI u časopisima](https://www.elsevier.com/about/policies-and-standards/generative-ai-policies-for-journals)

AI se može slobodno koristiti za:
- ispravljanje slovnih grešaka
- **manje** gramatičke korekcije, koje ne menjaju strukturu rečenice i ne uvode nove termine

Neki izdavači dozvoljavaju da se AI koristi za druge aktivnosti u okviru pisanja naučnog rada. To su, tipično:
- pregled literature
- ideacija
- organizacija sadržaja

Ukoliko se AI koristi za ove aktivnosti, izdavači zahtevaju da se korišćenje AI **mora** jasno naglasiti navođenjem deklaracije o korišćenju AI (_AI declaration statement_). Danas se korišćenje AI ne može sakriti zbog tehnika poput _watermarkinga_. Nepoštovanje ovog zahteva izdavača i prikrivanje korišćenja AI povlači sa sobom ozbiljnu akademsku odgovornost.

Kriterijumi korišćenja AI u ovom momentu nisu definisani na nivou obrazovnih institucija u Srbiji. Deklaracija o korišćenju AI ostaje u radu i nakon publikacije i može da da predstavlja nepremostiv problem prilikom prijave i odbrane doktorata. **Zato se AI u pisanju rada sme koristiti isključivo za ispravljanje slovnih grešaka i manje gramatičke korekcije koje ne menjaju strukturu rečenice, i ni za šta drugo!**

Radove napisane pomoću AI alata mentor ne uzima u razmatranje i preporuka je da, ukoliko prepozna neprimereno korišćenje AI alata, prekine dalju saradnju sa kandidatom.

# 3 Jezik naučnog rada
Kao i svaka druga pisana forma, i naučni rad ima jezik koji ga karakteriše. S obzirom na to da se naučni radovi pišu na engleskom jeziku, koji je većini istraživača drugi jezik, treba koristiti:
- kratke i jasne rečenice
- pojednostavljen vokabular, bez egzotičnih termina
- terminologiju karakterističnu za oblast istraživanja

Termine koji se uvode obavezno treba objasniti prvi put kada se koriste. Ukoliko se uvode akronimi, prvi put kada se akronim koristi treba objasniti šta znači. Ne treba objašnjavati značenje termina koji se standardno koriste u oblasti, kao što je, na primer, varijansa ili standardna devijacija. Imajte na umu da je osoba koja čita Vaš rad upućena u oblast istraživanja baš kao i Vi.