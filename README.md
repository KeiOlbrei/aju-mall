# Minu ettevõtte aju

> Sinu aju on kaust tavalisi tekstifaile, mida su AI saab lugeda ja kirjutada. Ei rohkemat. Kogu maagia on selles, et see on ühes kohas ja alati kaasas.

See kaust on praegu peaaegu tühi. **Nii peabki olema** — see täitub siis, kui sa siin oma päris tööd teed.

---

## Alusta siit

1. **Ütle Claude'ile:** *„Loe mu aju läbi ja ütle, mis siin on ja mis on veel tühi."*
2. **Ava [`TEEMAD.md`](TEEMAD.md)** — üheksa teemat, mida su aju sinu kohta teada tahab. Alusta kahest esimesest.
3. **Ava [`KUIDAS-KASUTADA.md`](KUIDAS-KASUTADA.md)** — valmis laused, mida sa võid otse kopeerida. Sealhulgas see, mis paneb su aju sinult vastu küsima.

**Kaks harjumust, mis hoiavad kõik koos:**

> **Alusta pulliga. Lõpeta pushiga.**
> Kui aju avad: *„tõmba GitHubist viimased muudatused."*
> Kui lõpetad: *„salvesta kõik muudatused GitHubi."*

Claude ei salvesta ise. Ta teeb muudatused su arvutis ja jääb ootama. Kui sa ei ütle, siis GitHubis neid ei ole — ja veateadet sa ei näe.

---

## Mis kus on

**Kaks faili ütlevad, KUIDAS käituda:**

| Fail | Mis see on |
|---|---|
| [`AGENTS.md`](AGENTS.md) | **Juhend.** Kuidas minuga töötada. Iga AI loeb selle esimesena. |
| [`CLAUDE.md`](CLAUDE.md) | Viit `AGENTS.md`-le, Claude Code'i jaoks. |

**Kõik ülejäänu ütleb, MIS on tõsi.** Number sulgudes on teema number [`TEEMAD.md`](TEEMAD.md)-st:

| Fail | Mis sinna käib |
|---|---|
| `01-mina/kes-ma-olen.md` | Nimi, ettevõte, mida ma müün ühe lausega |
| `01-mina/stiil-ja-toon.md` | Kuidas ma kirjutan ja räägin **(1)** |
| `01-mina/tulevane-mina.md` | Kes ma olen, kui see kõik töötab **(9 — vabatahtlik)** |
| `02-pakkumine/ideaalklient.md` | Kellega ma tahan töötada ja kellega mitte **(2)** |
| `02-pakkumine/teenused.md` | Mida ma müün **(3)** |
| `02-pakkumine/hinnastamine.md` | Mis hinnaga **(3)** |
| `02-pakkumine/kliendi-tulemus.md` | Mis on kliendi jaoks pärast teisiti, ja mis seda tõestab **(6)** |
| `03-protsessid/kliendi-teekond.md` | Mis juhtub, kui klient ütleb jah **(4)** |
| `03-protsessid/mis-kordub.md` | Mis on iga kliendiga täpselt ühesugune **(4)** |
| `03-protsessid/pohjad.md` | Dokumendid, mida sa iga kord uuesti teed — leping, pakkumine, kokkuvõte **(4)** |
| `04-turundus/kanalid-ja-kitsaskoht.md` | Kust kliendid tulevad ja kus praegu kinni jääb **(7)** |
| `04-turundus/lood-ja-laused.md` | Laused ja lood, mis päriselt töötavad |
| `05-otsused/minu-numbrid.md` | Kus ma olen ja kuhu tahan **(5)** |
| `05-otsused/mis-on-proovitud.md` | Mis ei töötanud ja mille juurde ei ole vaja tagasi tulla **(8)** |
| `05-otsused/otsuste-logi.md` | Mis otsustati, millal, miks |

**Ja üks kaust, mis GitHubi ei lähe:**

| Kaust | Mis sinna käib |
|---|---|
| `toormaterjal/` | Toores materjal — ChatGPT eksport, häälmärkme transkript, ekraanipilt. **Jääb sinu arvutisse.** Vt [`toormaterjal/LOE-MIND.md`](toormaterjal/LOE-MIND.md). |

---

## Kolm sahtlit — kuhu mis läheb

| Kuhu | Mis | Kas läheb GitHubi |
|---|---|---|
| **Ajju** (`01-mina/`, `02-pakkumine/` …) | Destilleeritud teadmine — kes ma olen, mida ma müün, mu hääl, mu otsused | Jah |
| **`toormaterjal/`** | Lahtine toorik — eksport, transkript, ekraanipilt | **Ei.** Jääb ainult su arvutisse. |
| **Saladused** | Paroolid, API võtmed, ligipääsud | **Ei kunagi.** Ja mitte kunagi ka vestlusesse. |

**Destilleeri, ära kalla.** Aju ei ole prügikast. Toorest vestluslogi siia ei panda — pannakse see, mille AI sellest välja võttis.

---

## Kui su AI ei ole Claude

Su aju on tavalised tekstifailid, mis kuuluvad sulle. Nad töötavad iga AI-ga. Ütle uuele tööriistale: **„loe AGENTS.md"** — ja ta teab, kuidas siin käituda.

Mis töötab igal pool ja mis on ühe tööriista külge kinni, on kirjas failis [`kaasaskantavus.md`](kaasaskantavus.md).
