# Načrt za spletno stran pivnice in picerije Kozel

## 1. Načrtovanje in zasnova spletišča

### Namen spletišča:
- **Namen**: Povedati zgodbo o pivnici in piceriji Kozel, predstaviti meni, dogodke, informacije o lokaciji, zgodovini in storitvah.
- **Ciljna skupina**: Ljubitelji piva, ljubitelji pice, družine, prijatelji, poslovni obiskovalci, turisti in lokalni obiskovalci, ki iščejo prijetno okolje za obrok, pijačo in sprostitev.

### Zemljevid spletišča (Sitemap):
- **index.html** (domača stran)
- **o-nas.html** – zgodovina pivnice in picerije Kozel, vizija, poslanstvo.
- **meni.html** – podroben meni za pivo, pice, jedi, pijače.
- **galerija.html** – slike pivnice, picerije, hrane, pijače, dogodkov.
- **dogodki.html** – koledar prihajajočih dogodkov, koncertov, specialitet.
- **kontakt.html** – kontaktni obrazec, naslov, telefonska številka, e-pošta, Google Maps API za lokacijo.
- **novice.html** – najnovejši dogodki, akcije, popusti, novice.
- **pogoji.html** – pogoji uporabe spletne strani, pravice obiskovalcev, odgovornost.
- **politika-zasebnosti.html** – varstvo osebnih podatkov, piškotki.
- **faq.html** – pogosto zastavljena vprašanja (npr. o odpiralnih časih, rezervacijah, posebnih potrebščinah v meniju).
- **rezervacija.html** – obrazec za rezervacijo miz in naročanje hrane.

---

## 2. Struktura in postavitev spletnih strani (11 strani)

### index.html (domača stran):
- **Vsebina**: 
  - Zgornji del strani (header) z logotipom **Kozel** in navigacijskim menijem (linki do vseh glavnih strani).
  - Kratek uvod v pivnico in picerijo, pozdravni tekst: "Dobrodošli v pivnici in piceriji Kozel!"
  - Povezava do glavnega menija in galerije.
  - Slika ali video predstavitev (npr. prostor pivnice, pice na mizi, pivo).
  - Prikazovanje aktualnih dogodkov (vključno z datumom in uro).
  
### o-nas.html:
- **Vsebina**:
  - Zgodovina pivnice in picerije Kozel (kako je nastalo, kdo so lastniki, kaj ponujajo).
  - Misija in vizija podjetja.
  - Prizadevanja za kakovostno hrano in pijačo ter prijetno okolje.
  - Povezave na ključne dejavnosti (dogodki, posebne ponudbe).
  - Fotografije prostora, ekipe, notranjosti.

### meni.html:
- **Vsebina**:
  - Podroben meni z kategorijami:
    - **Piva**: Seznam vrst piva, vključno z informacijami o vrsti (lager, ale, stout…), ceni.
    - **Pice**: Seznam pic (klasične, vegetarijanske, specialitete), sestavine, cena.
    - **Jedilnik**: Predjedi, glavne jedi, priloge, sladice.
    - **Pijače**: Različne vrste pijač (brezalkoholne, koktejli).
    - **Posebna ponudba**: Sezonske ponudbe, akcije, dnevni meniji.
  - Slike jedi in pijač.
  - Povezava za hitro naročanje ali rezervacijo (če je mogoče).

### galerija.html:
- **Vsebina**:
  - Galerija slik pivnice in picerije Kozel, s slikami:
    - Notranjosti prostora.
    - Pice, piva, jedi.
    - Dogodki (koncerti, zabave, posebni večeri).
  - Oblikovanje galerije s CSS za prikazovanje slik v mreži, kjer se slike lahko povečajo ob kliku (lahko vključite **lightbox**).
  
### dogodki.html:
- **Vsebina**:
  - Koledar prihajajočih dogodkov (koncerti, posebni večeri, degustacije piva, tematske zabave).
  - Kratke informacije o vsakem dogodku (datum, ura, cena vstopnine).
  - Povezave do prijav za dogodke ali dodatnih informacij.
  
### kontakt.html:
- **Vsebina**:
  - Kontaktni obrazec (ime, e-pošta, sporočilo).
  - Naslov pivnice, telefonska številka, e-poštni naslov.
  - **Google Maps API** za prikaz lokacije pivnice.
  - Delovni čas pivnice.
  
### novice.html:
- **Vsebina**:
  - Najnovejši dogodki in akcije v pivnici Kozel.
  - Obvestila o posebnih ponudbah, popustih, novih vrstah piva.
  - Pretekli dogodki s fotografijami in povzetki.
  
### pogoji.html:
- **Vsebina**:
  - Splošni pogoji uporabe spletne strani.
  - Pravice uporabnikov (npr. varstvo podatkov, pravice do vsebin).
  - Odgovornost gostov in podjetja pri obisku.
  
### politika-zasebnosti.html:
- **Vsebina**:
  - Politika varovanja osebnih podatkov (kako zbiramo podatke o uporabnikih, piškotki).
  - Kakšne podatke zbiramo (npr. kontaktne informacije, podatki za rezervacijo).
  
### faq.html:
- **Vsebina**:
  - Odgovori na pogosto zastavljena vprašanja:
    - Ali je potrebno rezervirati mizo vnaprej?
    - Kako naročiti posebno pico ali pivo?
    - Kaj narediti, če sem izgubil svojo kartico z darilnimi boni?
    - Kateri so vaši dnevi specialitet?

### rezervacija.html:
- **Vsebina**:
  - Obrazec za rezervacijo miz (ime, datum, čas, število oseb, posebne zahteve).
  - Povezava do telefonske številke za rezervacijo in dostopnost prek e-pošte.
  
---

## 3. Oblikovanje in pozicioniranje (CSS)

### Uporaba CSS za oblikovanje:
- **Pisava**: Uporaba pisav, kot sta **"Roboto"** za besedilo in **"Merriweather"** za naslove (iz **Google Fonts**).
- **Barve**: Temne barve za ozadje, kontrastne za besedilo (npr. temno rjava ozadje, bele in svetle barve za besedilo).
- **Oblikovanje menija**: Uporaba **CSS psevdorazredov** za aktivne in obarvane povezave.
- **Povezave**: Uporaba barvnih prehodov in animacij pri premiku miške.
- **Responsive Design**: Uporaba **media queries** za prilagoditev strani na mobilne naprave.

---

## 4. Testiranje in optimizacija

- Preveriti, ali so vse povezave pravilne, slike optimizirane, in ali so strani prilagojene za mobilne naprave.
- **SEO optimizacija**: Uporaba ustreznih **meta oznak**, **alt besedila za slike**, in **ključe besede** za boljšo vidnost v iskalnikih.
  
---

## 5. Objavljanje spletišča

- Objavite spletno stran na strežniku (uporabite lahko **GitHub Pages**, **Netlify**, **Vercel**).
- Preverite, da delujejo vsi obrazci in da so vse strani dostopne.
