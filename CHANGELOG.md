# Változásnapló

A GitHub-repó egyetlen összevont commitot tartalmaz; a változások története itt van.

## 1.4.0 – 2026-10-18 – audit javítások

- Státuszok: egy lista mindenhol (igaz / részben igaz / hamis / ellenőrizetlen / vélemény / jóslat); a „még nem találtam” ideiglenes köztes állapot, a „jóváhagyatlan” az egész naplót jelöli; a „nyitott” nem státusz; „nem ellenőrzött” → „ellenőrizetlen”.
- 4.1: az 1.3 kérdései a naplóval együtt, aztán megállás és várakozás a szerzőre; ha nem elérhető vagy mindent egyszerre kér, folytatás „jóváhagyatlan” naplóval. A 4.1 a szótérképet is mutatja.
- Szótár kötelező, ha kifejezéseket cseréltünk.
- Kimeneti formátum: rögzített sorrend (egy kódblokk: szöveg, szótár, Források; utána a másik oldal listája, nyitott pontok, rövidebb változat felajánlása). A rögzített feliratok (Források, A szövegedhez:, a szótár címe) a szerző nyelvén szerepelnek.
- 11./12. elv: a HU megkapta az EN kitételeit (szalmabáb és kiragadott adat nélkül; töltött szavak kerülése).
- Ellenőrzés: a 4. pont kettévált (4: mindkét oldal sajtója; 5: források oldala, szűretlen keresés, ellenőrizetlen csak ezután); a további pontok eggyel följebb (összesen 12).
- Átírás: 5.3 hamis állítás a pontos tény váltja fel (hivatkozással) vagy kimarad, véleményként nem marad; 5.2 jelölője „szerintem…”; 5.4 a megfigyelés a szerző beszámolója marad.
- Menete: új szöveg írásakor a 2–3. lépés a saját állításokra, 1.3 és 4.1 kimarad. 7.1 csak mutató az elvek utáni bekezdésre.
- Szótérkép és Állításnapló egységes felvezetés; kettős üres sor javítva.
- Manipuláció: új „Általánosítás” (21 → 22); bevezető: másik fél szövegében „védekezzünk”, a sajátunkban átírás; a védekezés „Ha a szerző a célpont:” alatt; a sugalmazó kérdés példája semleges.
- Leírások (SKILL.md, manifestek, README): mindkét oldal forrásai, szótérkép, átírás a másik tábornak; a „Magyarul.” helyett „Magyar nyelvű skill.”.
- Tesztek: a skill címkéi; eset-01 #15 (történelmi analógia); eset-02 #5b, #5c, Folytatás szakasz, #10 szótár kötelező.
- Idézőjelek: a nyitó „ után záró ” (nem ASCII ").
- Verzió: 1.4.0 minden manifestben.

## 1.3.0 – 2026-10-18 – késő este: videó és elérhetetlen szöveg terepen tesztelve

- Videó: a cím és leírás a csatorna keretezése, nem bizonyíték; az automatikus felirat gépi szöveg, csak ellenőrzés után idézhető; jegyezni kell, teljes felvétel-e vagy részlet, melyik oldal csatornája, és egyezik-e a dátum az eseménnyel.
- Elérhetetlen elsődleges szöveg: a védelmet nem kerüljük meg; a letöltött tartalmat ellenőrizni kell (a CAPTCHA-oldal is jöhet sikeres válaszként); tartaléksorrend: jogszabálytár/közlöny, kihirdetés előtt a többi hivatalos dokumentum, végül szó szerint idéző cikk; parafrázis nem helyettesíti a szöveget.
- Minimális mélység: elérhetetlen elsődleges oldal nem számít keresésnek.
- Nem tesztelt még: fizetőfalas cikk.

## 1.2.0 – 2026-10-18 – este: szótérkép, közérthető szavak, fordítás a másik tábornak

Egy éles, érzelmes politikai szöveg átnézése és négy cikk teszte (mindkét tábor sajtójából) alapján.

Előkészítés
- Ha a szerző nem elérhető (megjelent cikk átnézése), a kérdések a nyitott pontok közé kerülnek, a napló „jóváhagyatlan”.

Szótérkép és állításnapló
- Új szótérkép: minden vitatott dologhoz melyik tábor milyen szót használ, és mi az konkrétan, mindkét fél által elfogadható leírásban.
- Új állapot: „jóslat”.

Ellenőrzés
- Kiegyensúlyozott források már az első körben, mindkét tábor saját szavaival keresve. A táborokat a vita határozza meg, nem az, ki van kormányon.
- A naplóban minden forrás mellett a tábora, vagy „vegyes/hivatalos”. A szűrt keresések után egy szűretlen is.
- Ha a vita nem két politikai oldal között zajlik: a felek saját csatornái és egy független forrás.
- Videó: először átirat; ha nincs, a videó a szerző megfigyeléseként szerepel, időbélyeget kérünk.
- Elérhetetlen elsődleges szöveg (CAPTCHA, fizetőfal): hivatalos jogtár, közlöny vagy szó szerint idéző cikk, megnevezve.
- Tilalmak pontosan: mit, hol, mióta, és mit nem.
- Büntetőügyek: gyanú, őrizet, letartóztatás, vádemelés és ítélet külön; ártatlanság vélelme.
- Sok állításnál előbb azok, amelyeken a következtetés áll.

Átírás
- Jóslat a szerző jóslata marad.
- Számozott hivatkozások a szövegben, a végén „Források:” lista (lap, dátum, URL).
- Történelmi párhuzam: konkrét hasonlóság vagy a szerző véleménye.
- Szándék helyett hatás, csoportokra is.
- Közérthető szavak az egész szövegben; a szakszavak és szépítő kifejezések konkrét leírásra cserélve, a törvény szövege idézőjelben marad. Kötelező szószedet a források előtt, a szótérképből, a másik tábor szavával együtt. Saját fordítást jelölni kell.

Kimeneti formátum (új szakasz)
- Napló és sértések rövid listában vagy táblázatban; az átírás egyszerű szövegként, egyetlen kódblokkban.

Lezárás
- Mellékkérdésre rövid, kiegyensúlyozott válasz, a végén „A szövegedhez:” és egy kész, a naplóval egyező mondat.
- Ha a felhasználó a modellnek esik: egyszer, nyugodtan, a tényleges álláspontok, majd vissza a feladathoz.

8. Külön művelet: fordítás a másik tábornak (új)
- Kérésre ugyanaz a tartalom a másik tábor olvasójának szavaival; állítások, források, következtetés változatlan; a cserék listája a végén.

Manipulációs technikák
- 18 → 21: hamis analógia, sugalmazó kérdés, szándéktulajdonítás.
- A szabályok példái általánosak; konkrét esetek csak a tesztekben.

Tesztek
- eset-01: +13–14 (forrás tábora, kódblokk-kimenet).
- Új eset-02 (gyermekvédelmi törvénymódosítás, 15 elvárás).
- Terepen még nem kipróbált: videó átirat nélkül, elérhetetlen elsődleges szöveg.

## 1.1.0 – 2026-10-18 – délután: általánosítás bármely véleményre

- Cél: a vita minősége, nem a szerző álláspontjának megváltoztatása; mindkét oldalra érvényes.
- Hét lépéses menet: előkészítés, állításnapló, ellenőrzés, visszajelzés két lépésben, átírás, felkészülés a másik oldalra, lezárás.
- Minimális keresési mélység: két keresés, legalább egy elsődleges forrásra; „nem találtam” ≠ „hamis”.
- Átírás: a szerző hangja marad, nem adunk szavakat a szájába, javítunk és nem törlünk, az ellenőrizetlen vélemény jelölve marad.
- Első regressziós eset: eset-01 (építőipari kizárás).

## 1.0.0 – 2026-10-18 – délelőtt: első kiadás

- Tizenkét hangnem-elv és a manipulációs technikák listája (elterelés, DARVO, vádözön, asztroturfing stb.).
- A 11. és 12. elv a saját szövegeinkre is alapértelmezett.
- Ellenőrző lépések: nevek külön keresése, legalább két keresés, „nem találtam” ≠ „hamis”.
- Plugin-elrendezés Claude Code, Codex és Cursor számára, AGENTS.md.
- Angol testvér-skill: switch.
