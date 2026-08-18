# Kuidas oma aju kasutada

Valmis laused. Kopeeri, kleebi, muuda oma sõnadega ümber. Sa ei pea neid pähe õppima — see fail on selleks, et sa ei peaks.

---

## Iga kord, kui alustad ja lõpetad

> **Alusta pulliga. Lõpeta pushiga.**

**Alguses:**
> *Tõmba GitHubist viimased muudatused.*

**Lõpus:**
> *Salvesta kõik muudatused GitHubi.*

**Kui sa ei ole kindel, kas kõik on salvestatud:**
> *Kas mul on salvestamata muudatusi?*

Või ava github.com ja vaata: kas viimane muudatus on tänane?

---

## Kui alustad uues vestlusaknas

Iga vestlus algab külmalt. Claude ei mäleta eelmist korda — konteksti kannab repo, mitte vestlus. Nii et kirjuta talle nagu uuele töötajale:

> *Loe mu aju läbi. Täna teeme [see, mida sa teed]. Kogu vajalik info on repos olemas.*

Ära kirjuta „nagu eelmine kord rääkisime" — seda korda tema jaoks ei olnud.

---

## Esimene lause, kui aju on veel tühi

> *Loe mu aju läbi ja ütle, mis siin on ja mis on veel tühi.*

---

## Aju seemendamine

Enne faili või kausta näitamist küsi kaks eri küsimust: **kas see tohib minna GitHubi ajalukku?** ja **kas AI-pakkuja tohib selle sisu töödelda?** Lokaalne kaust ja `.gitignore` lahendavad ainult esimese. Kui AI ei tohi materjali töödelda, ära seda siia lisa ega ava; anonümiseeri esmalt offline.

Kaks liigutust, ja enamik inimesi vajab mõlemat.

### 1. Näita, mis sul juba on

**Kui su materjal on juba mingis kaustas** — näita talle seda kausta. Ära kopeeri midagi.

> *Loe kõik failid kaustast `Dokumendid/Minu firma` ja destilleeri need mu ajju.*

**Näita kindlat kausta, mitte kogu arvutit.** Osuta `Dokumendid/Minu firma` peale, mitte `Dokumendid` peale — muidu loeb ta ka su maksuasjad läbi.

**Kui midagi on lahtiselt ja AI tohib seda töödelda** — ChatGPT eksport, häälmärkme transkript, ekraanipilt — pane see kausta `toormaterjal/` ja ütle:

> *Loe `toormaterjal/` läbi ja destilleeri see mu ajju. Toorikut ennast ajju ei kopeeri.*

> Sinna võib panna PDF-i, pildi, Wordi faili või ekraanipildi **ainult siis, kui AI-pakkuja tohib selle sisu töödelda.** §.gitignore§ tähendab, et GitHub ei salvesta faili; see ei tähenda, et Claude seda lugedes ei töötle.

### 2. Lase tal endalt küsida

See on see pool, mida kuskil kirjas ei ole — su hääl, miks sa mõnest kliendist ära ütled, mida sa kunagi ei teeks.

> *Sa oled lugenud, mis mul olemas on. Nüüd küsi minult see, mis puudu on — üks-kaks küsimust korraga, ja kirjuta mu vastused õigesse faili. Vaata `TEEMAD.md`, kust alustada.*

**Järjekord loeb: kõigepealt materjal, kasvõi natuke, siis alles intervjuu.** Claude, kes on su kodulehe läbi lugenud, küsib *„su kodulehel on kolm paketti, aga arvetel ainult üks — kumb on praegu tõsi?"*. Külm Claude küsib *„kirjelda oma äri"*. Sama tööriist, täiesti erinev küsimus.

---

## Aju + töökaust — sa ei pea kõike ajju kolima

Su arvutis on kaustu, mis ei ole ja ei peagi olema osa ajust — arved, CRM, kliendikaustad, pildid. **Sa ei koli neid ajju. Kui AI tohib nende sisu töödelda, ühendad vajaliku kausta või faili vestluses aju kõrvale ainult selle töö ajaks.** Ühendamine ei saada faili GitHubi, kuid AI-pakkuja töötleb faili, mida ta loeb.

Ühes vestluses saab korraga ühendatud olla mitu kausta: vali aju, ja lisa `+` alt juurde see kaust, millega sa töötad.

> *Ühenda mu aju ja kaust `Arved`. Tee uus arve — üldised reeglid võta ajust; kliendi andmed, numbrid ja vorm võta sellest töökaustast. Salvesta mustand samasse töökausta, mitte ajju.*

> *Ühenda mu aju ja mu CRM-i kaust. Lisa sinna eilne uus klient — kes ta on ja mida ta tahab, vaata ajust.*

Mis siin toimub:

- **Aju annab konteksti** — kes on klient, mis on su hinnad, kuidas sa asju sõnastad.
- **Kaust on töölaud** — sealt tulevad näidised, sinna läheb tulemus.
- **Kaust ei muutu aju osaks.** Midagi ei kopeerita ja midagi ei sünkita GitHubi.

Ajju läheb ainult see, mida sa ütled, et sinna läheks:

> *Neid arveid ajju ei pane. Pane ajju ainult see, et selle kliendi hind tõuseb 1. septembrist.*

**Sellepärast sa ei kaota midagi sellega, et kliendi andmed ajus ei ela.** Nad on su arvutis või Drive'is, ühe klõpsu kaugusel, ja aju teab neist täpselt nii palju, kui sina tahad.

> **Lokaalne kaust on ainult desktopis.** Brauseri Claude su arvutisse ei näe. iCloudi või Dropboxi sünkitud kaust on Claude'i jaoks samuti tavaline lokaalne kaust — desktop näeb, brauser ei näe. Kui sul on vaja sama kaust ka brauseris kätte saada, hoia seda Google Drive'is ja ühenda konnektoriga.

---

## Aju küsib vastu

**See on nädala 1 kõige tähtsam lause.** Kasuta seda siis, kui ajus on juba midagi sees.

> *Loe kogu mu aju läbi ja ole minuga aus.*
>
> *1. Mis siin on omavahel vastuolus — kus ma ütlen üht ja teen teist?*
> *2. Mis on puudu — mida peaks iga AI minu ärist teadma, aga siit ei leia?*
> *3. Millele ma pole ilmselt mõelnud?*
> *4. Mis on kolm asja, mis praegu kõige rohkem mu kasvu takistavad?*
> *5. Mis on see üks töö, mille sa minu asemel esimesena ära teeksid?*

> **See töötab siis väga hästi, kui su aju juba tunneb sind ja sinu ettevõtet.** Kui vastus tuleb lahja, ei ole see märk sellest, et asi ei tööta — see on märk, et aju on veel näljane. Sööda teda edasi ja küsi nädala pärast uuesti.

---

## Päevane rütm

**Hommikul esimese asjana:**
> *Tõmba GitHubist viimased muudatused. Täna teen [...]. Mis sa arvad, mis on täna kõige tähtsam?*

**Päeva lõpus:**
> *Viska päev ajju: [mis juhtus, mis otsustati, mis on järgmine]. Kirjuta see õigesse faili ja salvesta GitHubi.*

---

## Kui midagi läks hästi

> *Lisa see mu tõendite nimekirja failis `01-mina/tulevane-mina.md`.*

---

## Ära usalda pimesi

Kui su AI midagi soovitab või küsib ja sa ei saa aru, miks:

> *Seleta mulle, miks see oluline on.*

AI võimendab tarkust ja ka rumalust. Otsustaja oled sina.
