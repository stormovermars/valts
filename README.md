# valts – Váltsunk hangnemet!

Plugin vitás szövegekhez: kommentekhez, válaszokhoz, cikkekhez, posztokhoz, levelekhez és beszédekhez. Tizenkét hangnem-elv alapján átnézi a szöveget, megjelöli, hol sérülnek az elvek, átfogalmazási javaslatot ad, és felismeri a gyakori manipulációs technikákat (elterelés, DARVO, vádözön, asztroturfing stb.). A saját szövegeink alapértelmezetten kerülik ezeket a technikákat. Szótérképet készít arról, melyik tábor milyen szót használ ugyanarra, és kérésre a szöveget „lefordítja” a másik tábor olvasójának, a tartalom változtatása nélkül. Az állításokat mindkét oldal forrásaival ellenőrzi, szótérképet készít, és kérésre átírja a másik tábor számára.

Parancs: `/valts` és utána a szöveg.

## Telepítés

**Claude Code** (marketplace):

```
/plugin marketplace add stormovermars/valts
/plugin install valts@valts
```

**Más eszközök:** a repó tartalmaz plugin-manifesteket Codex (`.codex-plugin/`) és Cursor (`.cursor-plugin/`) számára, valamint `AGENTS.md`-t azoknak az eszközöknek, amelyek azt olvassák. Add hozzá a repót az adott eszköz plugin-beállításaiban. Csak a fenti Claude Code lépéseket teszteltük.

**Kézzel:** másold a `skills/valts/SKILL.md` fájlt az eszköz skill-mappájába.

## Felépítés

- `skills/valts/SKILL.md` – a skill (elvek, menet, manipulációs technikák).
- `skills/valts/ledger.html` – állításnapló oldal (artifactként közzétéve; `db` capability kell).
- `AGENTS.md` – ugyanez az AGENTS.md-t olvasó eszközöknek. Tartsd szinkronban a SKILL.md-vel.
- `skills/valts/tests/` – regressziós esetek elvárt eredménnyel.
- `CHANGELOG.md` – változásnapló.
- `.claude-plugin/`, `.codex-plugin/`, `.cursor-plugin/` – plugin-manifestek.

## Megjegyzés

A skill a szöveg hangnemét és érvelését nézi, nem ítél emberek felett. A manipuláció-felismerés nem biztos: a skill jelzi a bizonytalanságot, a végső döntés a tiéd.
