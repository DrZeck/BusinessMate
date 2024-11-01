BusinessMate - Uputstvo za Korišćenje
BusinessMate je aplikacija za upravljanje poslovnim procesima, dizajnirana da pomogne u vođenju radnih naloga, upravljanju klijentima i uređajima, kao i generisanju mesečnih statistika. Aplikacija je jednostavna za korišćenje, a svi podaci se čuvaju lokalno koristeći SQLite bazu podataka.
Instalacija
1.	Preuzimanje i Instalacija: Aplikaciju preuzmite sa linka:
Korišćenje Aplikacije
1. Aktivacija Aplikacije
·	Prilikom prvog pokretanja, aplikacija će zahtevati unos licencnog ključa.
·	Unesite svoj ključ i kliknite na "Aktiviraj". Ako je ključ ispravan, aplikacija će se aktivirati.
2. Prijava i Registracija
·	Prijava: Unesite korisničko ime i lozinku da biste se prijavili. Ako je ovo prvi put da koristite aplikaciju, moraćete da registrujete administrativnog korisnika.
·	Registracija: Ako je administrativni korisnik već kreiran, možete dodati nove korisnike sa rolom "user".
3. Glavni Prozor
Glavni prozor aplikacije omogućava Vam da unosite i upravljate podacima o klijentima, uređajima i radnim nalozima.
Klijenti
·	Unesite podatke o klijentu, kao što su ime, prezime, telefon, PIB i email.
Uređaji
·	Izaberite tip uređaja i unesite brend, model i serijski broj uređaja.
Detalji Naloga
·	Unesite cene za delove i ukupnu cenu intervencije.
·	Unesite opis izvršenih intervencija na uređaju.
Status Naloga
·	“Otvoren” unos novog klijenta / uređaja u bazu podataka.
·	“Zatvoren” ažuriranje postojećeg naloga nakon izvršenih intervencija.
·	“Odložen” ažuriranje postojećeg naloga usled nabavke delova, čekanja delova itd...
·	Samo zatvoren i odložen status ažuriraju naloge u bazi; status “Otvoren” uvek pravi novi unos u bazi podataka, tako da prilikom odabira starih naloga iz baze možete uneti isti ili novi uređaj za postojećeg klijenta bez da ponovo upisujete podatke klijenta firme, itd. Potrebno je samo da, nakon učitavanja starog naloga iz baze, promenite status na “Otvoren”, izmenite potrebne podatke i ponovo sačuvate novi nalog.
4. Čuvanje, Ažuriranje i Brisanje Naloga
·	Kliknite na "Sačuvaj Nalog" da biste snimili podatke.
·	Da biste ažurirali postojeći nalog, selektujte ga iz tabele, napravite izmene i kliknite na "Sačuvaj Nalog".
·	Brisanje Naloga: Izaberite nalog i kliknite na "Obriši Nalog". *Dostupno samo administratoru. 
5. Štampanje i Pregled PDF-a
·	Kliknite na "Štampaj Nalog" da generišete PDF fajl radnog naloga.
·	PDF fajl se može pregledati i štampati korišćenjem ugrađenog PDF pregledača.
6. Statistika
·	Statistika: Grafički prikaz cele godine po mesecima. *Dostupno samo administratoru.
·	Godišnji prikaz u donjem levom uglu prozora samo numerički.
·	Odabir godine: Trenutna godina (default prikaz) sa opcijom za poslednjih 5 godina (padajući meni) u donjem desnom uglu prozora.
7. Podešavanja
·	IPS Podaci: Unesite podatke o firmi i broju računa. Ovi podaci će biti korišćeni za generisanje IPS QR koda. *Dostupno samo administratoru.
·	Otvaranje Template-a: Kliknite na "Otvori Template Nalog" da biste uredili Word template za radne naloge.
Automatska Prijava
Aplikacija podržava automatsku prijavu logovanog korisnika. Ovo podešavanje se može promeniti u meniju aplikacije.
Backup Baze
Podaci se čuvaju u business_mate.db bazi podataka koja se nalazi u:
C:\Users\VAŠ_KORISNIČKI_NALOG\Documents\BusinessMate\DB
Preporučuje se redovan backup baze kako biste izbegli gubitak podataka.
Tehnička Podrška
U slučaju problema sa aplikacijom, obratite se tehničkoj podršci ili pošaljite e-mail sa opisom greške.
Hvala što koristite BusinessMate!

