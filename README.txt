Web Sajt TireShop&Servis Čačak namenjen je prodaji auto guma i pružanju usluga auto servisa i vulkanizerska radnja. Sajt omogućava korisnicima da pregledaju ponudu guma po dimenziji, proizvođaču i sezoni za koju je guma namenjena, kao i da dobiju informacije o dostupnim servisnim uslugama.
Takodje cilj sajta je da omogući zakazivanje termina za mali servis, veliki servis, servis kočionog sistema i vulkanizerske usluge kao i pregled korpe odnosno proizvoda za koje se kupac odlučio.

Kako sajt funkcioniše:
Korisnik ima više načina da izabere gume koje su mu potrebne.
Na početnoj stranici odmah mu se pojavljuje deo za pretragu guma gde moze izabrati širinu, visinu, prečnik i sezonu za koju je sama guma namenjena.
Drugi način je da klikom na stranicu gume može izabrati gume sam skrolovanjem stranice ili sa desne strane uraditi filtraciju sa gore pomenutim filterima.
Nakon što korisnik izabere odgovarajuće gume one se prikazuju u korpi i nakon klika na korpu korisnik potvrđuje kupovinu ili može da nastavi sa dodavanjem guma i kasnije završi kupovinu.
Završetak kupovine se realizuje na način tako što korisnik unese potrebne informaciju u formu za unos kao što su ime i prezime, adresa za dostavu i broj telefona.

Takođe na sajtu je moguće zakazati servisne usluge na stranici servis gde se pojavljuje padajući meni i korisnik bira servis.
Nakon odabira servisa korisnik popunjava formu i bira datum servisa.

Tehnologije korišćene u izdradi sajta:
***Tehnologije su i dalje podlozne promenama, na kraju projekta bice update README.md fajla i spisak svih korišćenih tehnologija***

Potrebni alati i opis za pokretanje sajta:
Od alata instaliranih na računar potrebni su python i flask, python se instalira sa zvaničnog sajta python.org dok se flask instalira unutar terminala projekta otvorenog u VScode sa komandom pip install flask (ili ako ne radi onda python -m pip install flask).
Nakon instaliranja pokreće se fajl server.py komandom u terminalu: python server.py
U zavisnosti od instalirane verzije pythona probati neki od sledećih komandi:
python3 server.py
py server.py

Povezivanje SQL baze podataka:
Kod baze se nalazi u fajlu prodavnica_guma.sql i ona je povezana sa projektom preko mysql connectora u pythonu.
Korisnik pokreće i unosi bazu sledećim koracima:
U programu XAMPP pokrene se Apache server i MySQL, zatim se pristupi phpmyadmin-u tako što se u browseru kuca localhost i izabere se kartica phpmyadmin ili se u XAMPP-u klikne na button admin pored MySQL.
Kreira se baza i zatim se importuje fajl prodavnica_guma.sql u tu bazu.