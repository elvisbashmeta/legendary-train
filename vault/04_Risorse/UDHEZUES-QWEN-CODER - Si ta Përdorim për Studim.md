---
kodi: RES-QC-01
titulli: "Udhëzues Qwen Coder — si ta përdorim me këtë vault me cilësi maksimale"
tags: [qwen-coder, prompt-engineering, studim, automatizim]
statusi: "Referencë"
data_krijimit: 2026-11-02
---

# 🤖 UDHEZUES QWEN CODER — Motori i këtij sistemi

Qwen Coder lexon dhe shkruan brenda repo-s (`/workspace`). Sa më i qartë konteksti, aq më e mirë dalja. Rregullat dhe prompt-et gati-përdorim:

## Parimet (vlen për çdo sesion)
1. **Një detyrë, një prompt** — mos blendo "përmiro flashcard-at DHE krijo plan". 
2. **Jep referencën e dosjes** — emrat e skedarëve janë unikë; përmend shtegun (`vault/01_Kurse/Menaxhimi i Projekteve Sociale/Tema 05...md`).
3. **Kërko formatin** — "tablele markdown me kolonat X|Y", "rreshta `Pyetje :: Përgjigje` pa numra".
4. **Verifiko pas gjenerimit** — kontrolloni përmbajtjen kundrejt burimit (`extracted/*.txt`) para se ta pranoni si të saktë.
5. **Shqip i saktë** — nëse shfaqet term i huaj, kërko: "rimërkato termin me ekuivalentin zyrtar shqip + kllapë termin origjinal".

## Prompt-e gati (kopjo–ngjit)
### A. Gjenerim flashcards nga një temë
```
Lexo vault/01_Kurse/<LENDA>/<TEMA>.md dhe prodho 15 flashcards në formatin
"Pyetje :: Përgjigje" (një rresht për kartë, pa numra, pa bold).
Rregulla: pyetjet të kenë një fjalë kyçe në fillim; përgjigjet ≤25 fjalë;
përfshi 3 pyetje krahasuese ("Dallimi mes X dhe Y?") dhe 2 aplikative (rast konkret).
Mos kopjo fraze nga dokumenti — rikthe konceptin me gjuhën tënde.
```
### B. Simulim provimi (retrieval practice)
```
Si profesor i FSHS, zbulo 10 pyetje të hapura mbi `[[Tema ... (emri i temës)] |Tema e zgjedhur]]` me barazh 40%
mësim bazik / 40% analizë / 20% rast. Mbylli në fund me "Udhëzues pikësh"
sipas modelit 10/20/70 (shih MOC - Menaxhimi i Projekteve Sociale).
```
### C. Përmbledhje e dokumenteve Office të rinj
```
Nxirr tekstin nga dosje/<file>.pptx dhe krijo përmbledhje strukturore në
vault/01_Kurse/<LENDA>/ me frontmatter (kursi, kapitulli, statusi: "Për t'u mësuar"),
seksione me titujt e folias, dhe 8 flashcards në fund të skedarit.
```
### D. Debug i plugin-eve Obsidian
```
Dataview/Spaced Repetition nuk punon: <kopjo mesazhin e gabimit>.
Shiko konfigurimin në vault/.obsidian/community-plugins.json dhe .obsidian/data.json
dhe korrigjo vetëm atë që duhet; shpjego ndryshimin.
```
### E. Interleaving (ndërlidhje lëndësh)
```
Merr rastin e Bashkia Patos nga MATRIKE-KRYQEZORE dhe krijo 5 pyetje që
detyronin të përgjigjen duke kombinuar MPS Tema 04 (stakeholder) + ABN Tema 04
(rekrutimi) + ODSS Tema 06 (menaxhimi i rastit).
```

## Kufizimet e dijetshme
- Nuk e zëvendëson leximin e burimeve primare (lekserat e ligjëratës për kap. 10, 12–13, 15–17 që s'kanë slides).
- Gjenerimi i mediokër ndalohet vetëm me **verifikim kundrejt `/workspace/extracted`** — gjithmonë kërko "cila folia e burimit e mbështet këtë pohim?".

Lidhje: [[PLUGINS - Shtesat e Nevojshme për Obsidian]] · [[RESEO - Teknologji Open Source që Forcojnë Studimin]] · [[DASHBOARD - Qendra e Studimit]]
