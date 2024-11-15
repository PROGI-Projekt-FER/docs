# Programsko inženjerstvo - TicketSwapper

# Opis projekta
Ovaj projekt je reultat timskog rada u sklopu projeknog zadatka kolegija [Programsko inženjerstvo](https://www.fer.unizg.hr/predmet/proinz) na Fakultetu elektrotehnike i računarstva Sveučilišta u Zagrebu. 

Današnji korisnici često unaprijed kupuju ulaznice za razne događaje poput koncerata, kazališnih predstava, sportskih utakmica itd. No, kada ne mogu prisustvovati događaju zbog nepredviđenih okolnosti, često traže načine kako da prodaju ili zamijene svoje ulaznice, što može biti dosta stresno. Trenutačno rješenje navedenog problema su društvene mreže ili oglasne platforme. Takva rješenja često su neučinkovita, dugotrajna i nesigurna što može imati negativne posljedice za korisnika.

Cilj projekta „TicketSwapper“ je olakšati ovaj proces stvaranjem sigurne i učinkovite platforme za razmjenu i prodaju ulaznica. Naš sustav omogućiti će jednostavno pretraživanje i objavljivanje oglasa te povezivanje korisnika koji žele razmijeniti ulaznice jedan-na-jedan ili kroz lančanu razmjenu, ako je u pitanju više korisnika.

# Funkcijski zahtjevi

<h2> 2.2 Tablica funkcionalnih zahtjeva:

| ID zahtjeva | Opis | Prioritet | Izvor | Kriteriji prihvaćanja |
|----|----------|----------|----------|----------|
| F-001 | Sustav omogućuje prijavu korisniku s pomoću vjerodajnica vanjskih identiteta | Visok | Zahtjev dionika | Korisnik se može prijaviti koristeći vanjski identitet (Google OAuth). |
| F-002 | Sustav omogućuje korisnicima pregled dostupnih događaja i ulaznica prema kriterijima (datum, lokacija, vrsta) | Visok | Zahtjev dionika | Korisnik može filtrirati događaje prema navedenim kriterijima. |
| F-003 | Sustav omogućuje korisnicima kupovinu i prodaju ulaznica za specifične događaje. | Visok | Zahtjev dionika | Korisnik može kupiti ili prodati ulaznice za određeni događaj. |
| F-004 | Sustav omogućuje korisnicima slanje i primanje obavijesti vezanih uz status događaja (promjena datuma, slobodne ulaznice). | Srednji | Povratne informacije korisnika | Korisnik prima obavijesti o promjenama statusa događaja ili ulaznica. |
| F-005 | Sustav omogućuje razmjenu ulaznica među korisnicima. | Visok | Zahtjev dionika | Korisnik može ponuditi ili prihvatiti razmjenu ulaznica s drugim korisnicima. |
| F-006 | Sustav omogućuje korisnicima pregled njihovih prethodnih kupovina i razmjena ulaznica. | Visok | Zahtjev dionika | Korisnik može vidjeti povijest svojih transakcija u sustavu. |
| F-007 | Sustav omogućuje administratorima kontrolu nad sigurnosnim mjerama | Visok | Zahtjev dionika | Administrator može nadzirati oglase te uklanjati problematične oglase. |
| F-008 | Sustav omogućuje implementaciju vanjskih sustava za dohvaćanje željenih podataka  | Visok | Zahtjev dionika | Korisniku se isporučuju željeni podaci. |
| F-009 | Sustav omogućuje implementaciju baze podataka za pohranu podataka | Visok | Zahtjev dionika | Korisnikovi podaci pohranjuju se u bazu podataka. |


# Tehnologije

Frontend: React (JavaScript, HTML, CSS), Chakra UI

Backend: Spring

Baza podataka: PostgreSQL


# Članovi tima 
Pavle Ergović (voditelj), https://github.com/FERpavleerg</br>
Matko Papić, https://github.com/matko-papic-fer</br>
Roko Šabić, https://github.com/rs55056</br>
Fran Krušelj, https://github.com/kruseljfran</br>
Noa Deur, https://github.com/Noa-Deur</br>
Mia Periš, https://github.com/miap18</br>
Luka Stubičan, https://github.com/luka-stubican</br>

# Kontribucije
>Pravila ovise o organizaciji tima i su često izdvojena u CONTRIBUTING.md



# 📝 Kodeks ponašanja [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
Kao studenti sigurno ste upoznati s minimumom prihvatljivog ponašanja definiran u [KODEKS PONAŠANJA STUDENATA FAKULTETA ELEKTROTEHNIKE I RAČUNARSTVA SVEUČILIŠTA U ZAGREBU](https://www.fer.hr/_download/repository/Kodeks_ponasanja_studenata_FER-a_procisceni_tekst_2016%5B1%5D.pdf), te dodatnim naputcima za timski rad na predmetu [Programsko inženjerstvo](https://wwww.fer.hr).
Očekujemo da ćete poštovati [etički kodeks IEEE-a](https://www.ieee.org/about/corporate/governance/p7-8.html) koji ima važnu obrazovnu funkciju sa svrhom postavljanja najviših standarda integriteta, odgovornog ponašanja i etičkog ponašanja u profesionalnim aktivnosti. Time profesionalna zajednica programskih inženjera definira opća načela koja definiranju  moralni karakter, donošenje važnih poslovnih odluka i uspostavljanje jasnih moralnih očekivanja za sve pripadnike zajenice.

Kodeks ponašanja skup je provedivih pravila koja služe za jasnu komunikaciju očekivanja i zahtjeva za rad zajednice/tima. Njime se jasno definiraju obaveze, prava, neprihvatljiva ponašanja te  odgovarajuće posljedice (za razliku od etičkog kodeksa). U ovom repozitoriju dan je jedan od široko prihvačenih kodeks ponašanja za rad u zajednici otvorenog koda.
>### Poboljšajte funkcioniranje tima:
>* definirajte načina na koji će rad biti podijeljen među članovima grupe
>* dogovorite kako će grupa međusobno komunicirati.
>* ne gubite vrijeme na dogovore na koji će grupa rješavati sporove primjenite standarde!
>* implicitno podrazmijevamo da će svi članovi grupe slijediti kodeks ponašanja.
 
>###  Prijava problema
>Najgore što se može dogoditi je da netko šuti kad postoje problemi. Postoji nekoliko stvari koje možete učiniti kako biste najbolje riješili sukobe i probleme:
>* Obratite mi se izravno [e-pošta](mailto:vlado.sruk@fer.hr) i  učinit ćemo sve što je u našoj moći da u punom povjerenju saznamo koje korake trebamo poduzeti kako bismo riješili problem.
>* Razgovarajte s vašim asistentom jer ima najbolji uvid u dinamiku tima. Zajedno ćete saznati kako riješiti sukob i kako izbjeći daljnje utjecanje u vašem radu.
>* Ako se osjećate ugodno neposredno razgovarajte o problemu. Manje incidente trebalo bi rješavati izravno. Odvojite vrijeme i privatno razgovarajte s pogođenim članom tima te vjerujte u iskrenost.

# 📝 Licenca
Važeča (1)
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Ovaj repozitorij sadrži otvoreni obrazovni sadržaji (eng. Open Educational Resources)  i licenciran je prema pravilima Creative Commons licencije koja omogućava da preuzmete djelo, podijelite ga s drugima uz 
uvjet da navođenja autora, ne upotrebljavate ga u komercijalne svrhe te dijelite pod istim uvjetima [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License HR][cc-by-nc-sa].
>
> ### Napomena:
>
> Svi paketi distribuiraju se pod vlastitim licencama.
> Svi upotrijebleni materijali  (slike, modeli, animacije, ...) distribuiraju se pod vlastitim licencama.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: https://creativecommons.org/licenses/by-nc/4.0/deed.hr 
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

Orginal [![cc0-1.0][cc0-1.0-shield]][cc0-1.0]
>
>COPYING: All the content within this repository is dedicated to the public domain under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication.
>
[![CC0-1.0][cc0-1.0-image]][cc0-1.0]

[cc0-1.0]: https://creativecommons.org/licenses/by/1.0/deed.en
[cc0-1.0-image]: https://licensebuttons.net/l/by/1.0/88x31.png
[cc0-1.0-shield]: https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg

### Reference na licenciranje repozitorija
