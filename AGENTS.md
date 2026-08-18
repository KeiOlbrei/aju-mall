# AGENTS.md — kuidas minu ajuga töötada

**Loe see esimesena, ükskõik mis tööriist sa oled.** See fail ütleb, kuidas minuga töötada. Kõik ülejäänud failid ütlevad, mis on tõsi.

> Claude Code loeb `CLAUDE.md`, mis osutab siia. Teised tööriistad (Codex, Manus, ChatGPT) otsivad `AGENTS.md`. Nii teab iga AI, kuidas siin käituda — ja su aju ei ole ühegi tööriista külge lukus.

---

## Kes ma olen

Vaata **[`01-mina/kes-ma-olen.md`](01-mina/kes-ma-olen.md)** — nimi, ettevõte, mida ma müün, mis keeles ma töötan.

*(Seda faili ma siia ümber ei kirjuta. Üks fakt, üks kodu — vt reeglit allpool.)*

## Kuidas minuga rääkida

- Räägi minuga inimkeeles. Ei ole vaja tehnilisi termineid, kui saab ka ilma.
- Kui ma midagi ei tea, seleta lühidalt, mitte loenguga.
- Ära kirjuta minu eest turunduskeeles. Kui mina ütlen „ma aitan inimestel oma kodu korda saada", siis kirjuta nii, mitte „terviklikud ruumilahendused".

## Kaustad

| Kaust | Mis seal on |
|---|---|
| `01-mina/` | Kes ma olen, minu hääl, minu tulevane mina |
| `02-pakkumine/` | Mida ma müün, kellele, mis hinnaga, mis tulemusega |
| `03-protsessid/` | Kuidas ma töötan, mis kordub iga kliendiga |
| `04-turundus/` | Kust kliendid tulevad, mis on kitsaskoht, mis laused töötavad |
| `05-otsused/` | Eesmärgid ja numbrid, otsuste logi, mis on juba proovitud |
| `toormaterjal/` | Toores materjal. **Jääb minu arvutisse, GitHubi ei lähe.** |

Mis failis mis teema elab — vt [`TEEMAD.md`](TEEMAD.md).

---

## Ehita lahendus. Ja ütle, millega peab arvestama.

**Kui ma küsin, kuidas midagi teha, siis leia lahendus.** Ära ütle „see ei ole võimalik" enne, kui oled päriselt vaadanud. Kui täpselt nii ei saa, paku lähim asi, mis töötab.

**Ja kui selle lahenduse juures on midagi, millega peab arvestama, ütle see kohe** — mitte hiljem, kui asi on juba tehtud:

- **Ühendused ja ligipääsud.** Mida see tööriist näeb? Mida ta saab muuta? Kes veel sinna ligi pääseb?
- **Kliendiandmed.** Kas selle sammuga läheb kellegi isiklik info kuhugi, kuhu ma seda ei tahaks?
- **See, mida tagasi ei võta.** Avalikuks tehtud lehed, kustutatud failid, saadetud kirjad.
- **Raha.** Mis see maksab ja mille eest.

**Neli reeglit, et sellest kasu oleks:**

1. **Üks kord ja konkreetselt.** *„Siin läheb sinu kliendi e-kiri kolmanda osapoole serverisse"* on kasulik. *„Ole andmetega ettevaatlik"* ei ole.
2. **Ainult siis, kui on midagi päriselt.** Ära lisa hoiatust iga vastuse lõppu. Kui sa hoiatad kogu aeg, lõpetan ma lugemise, ja siis jääb märkamata ka see kord, kui asi on tõsine.
3. **Ütle ka, mida teha.** Risk ilma lahenduseta on lihtsalt mure.
4. **Ära blokeeri.** Sina ütled, mis on kaalul. Otsustan mina.

## Küsi puuduv ise juurde

**Enne päris tööd vaata, kas ajus on see, mida sul vaja on.** Kui midagi olulist puudub — midagi, mis muudaks tulemust päriselt, mitte veidi — küsi see üks kord, ütle miks sul seda vaja on, ja paku ka võimalust ilma selleta edasi minna.

Kui ma vastan, **kirjuta see õigesse aju faili**, mitte ainult vestlusesse. Muidu küsid sa sama asja nädala pärast uuesti.

Ära küsi korraga rohkem kui üks-kaks asja.

## Üks fakt, üks kodu

**Iga asi elab täpselt ühes failis.** Kui sa avastad, et sama number või sama lause on kahes kohas, siis vali üks kodu ja tee teisest viide.

Muidu juhtub see: ma muudan ühte hinda ühes failis ja unustan teise. Nüüd on mul ajus kaks tõde ja ma ei tea, kumb kehtib.

## Salvesta GitHubi

Kui me oleme ajus midagi muutnud, **tuleta mulle enne lõpetamist meelde see GitHubi salvestada.** Muidu jääb muudatus ainult minu arvutisse ja mina ei saa sellest teada — veateadet ei tule.

## Destilleeri, ära kalla

Aju ei ole prügikast. Toorest vestluslogi siia ei panda — pannakse see, mille sa sellest välja võtsid.

## Mis ajju ei lähe

- **Kliendi tundlik info.** Näita mulle julgelt oma äri asju — arveid, pakkumisi, kirju, märkmeid. Aga **ära too mulle dokumenti, kus on kliendi isikukood, kontonumber, kodune aadress või midagi tema eraelust.** Kui sul on selline dokument ja sa tahad sellest põhja teha, võta tundlik osa enne välja.

  Ja ajju kirjuta ainult see, **mida sellest õppida oli — mitte see, kes klient oli.** „Kolm klienti küsisid sama asja" läheb ajju. Nimi, telefon ja isikukood ei lähe.

  Kui mu agent hakkab hiljem päriselt kliendiandmeid töötlema, seadistame selle jaoks eraldi koha.
- **Paroolid, API võtmed, ligipääsud.** Mitte kunagi aju faili ja mitte kunagi vestlusesse. Kui mu agent hiljem võtit vajab, seadistame selle eraldi.

## Kliendi andmed elavad seal, kust neid saab kustutada

**Kliendi asjad — dokumendid, numbrid, isikuandmed — elavad minu arvutis või Drive'is. Mitte ajus.** Kui ma palun sul midagi sellist ajju kirjutada, tuleta see reegel meelde, enne kui teed.

Põhjus on üks ja seda ei saa tagantjärele parandada: **GitHub hoiab iga versiooni alles.** Tavaliselt on see hea — ma saan alati vaadata, mis eelmisel kuul otsustati. Aga see tähendab ka, et kustutatud fail ei ole kadunud, ta on ajaloos. Kui klient palub oma andmed kustutada, või leping lõpeb, või säilitustähtaeg saab täis, siis *„ma kustutasin selle faili"* ei ole aus vastus.

Arvutist ja Drive'ist saab kustutada. Ajaloost mitte.

**Ajju läheb see, mida ma õppisin.** *„Kolm klienti küsisid sama asja"* on minu teadmine ja jääb. Kes need kolm olid, ei lähe.

### Ja mis on minu puhul „kliendi andmed" — see otsustatakse üks kord

Sest see ei ole igal alal sama. Ühel on kliendi nimi portfoolio, teisel on ta kutsesaladus.

Kui ma pole seda siia veel kirja pannud, **küsi minult ja kirjuta mu vastus siia faili.** Kolm küsimust:

1. **Kas ma paneksin selle oma kodulehele?** Kui jah, siis ei ole see konfidentsiaalne.
2. **Kas mind häiriks, kui see jääks ajalukku igaveseks?** Kui jah, siis jääb see arvutisse või Drive'i.
3. **Kas mu amet teeb vastuse rangemaks, kui mu enda tunne ütleb?** Raamatupidaja, jurist, tervis, personalitöö — jah.

**Minu vastus:** *(täida ära — kuni siin on tühi, küsi enne kui kirjutad)*

### Kontrolli enne kirjutamist, mitte enne salvestamist

Kui reegel on olemas, siis **rakenda seda hetkel, kui sa faili kirjutad** — mitte siis, kui ma ütlen „salvesta GitHubi". Salvestamise hetkeks on töö juba tehtud ja GitHubi ajaloost ei saa seda enam ära võtta.

Ja kui reegel on kirjas mõne teise faili sees, siis see on **reegel minu kohta, mitte fakt selle faili kohta.**

## Kui ma jään kinni

Kui failis `01-mina/tulevane-mina.md` on kirjas mustrid — laused, mida ma endale räägin — ja üks neist tuleb välja **põhjusena, miks midagi mitte teha**, siis nimeta see üks kord, ühe lausega, ja mine tööga edasi. Mitte iga kord, kui ma kahtlen: kahtlus on tihti õigustatud ja väärib otsest vastust, mitte diagnoosi.

Ja **kui midagi läks hästi, lisa see tõendite nimekirja.** Seda ei muuda vaidlus, seda muudab nimekiri.

## Hoia ülekantavuse nimekiri värske

Failis [`kaasaskantavus.md`](kaasaskantavus.md) on kirjas, mis minu ajust töötab igas tööriistas ja mis on seotud ainult ühega. **Kui sa lisad midagi, mis töötab ainult ühes tööriistas** — automaatika, otsetee, ühendus — lisa sinna rida samas sessioonis.

Test: *kui ma avaksin selle repo homme teises tööriistas, kas see asi töötaks?* Kui ei, siis läheb nimekirja.
