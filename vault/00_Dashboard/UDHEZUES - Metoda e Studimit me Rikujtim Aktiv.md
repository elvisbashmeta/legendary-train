---
kodi: METH-01
titulli: "Udhëzues — Metoda e Studimit me Rikujtim Aktiv"
tags: [metode-studimi, retrieval-practice, spaced-repetition, obsidian]
data_krijimit: 2026-11-02
---

# 🧠 UDHEZUES — Si të studiohesh me këtë vault (metoda më efikase)

> [!abstract] Parimi themeltar
> **Memorizimi i qëndrueshëm nuk vjen nga sa herë e lexon, por nga sa herë e rikujton.** Rikujtimi aktiv (*retrieval practice*) + përsëritja me intervale (*spaced repetition*) janë dy metodat me evidencën shkencore më të fortë (Roediger & Karpicke; Dunlosky et al., 2013). Ky vault është ndërtuar posaçërisht për to.

## 🔄 Cikli 5-hapat (për çdo temë, ~60–90 min)

| Hapi | Veprimi | Koha |
|---|---|---|
| 1. **Parashiko** | Para leximit: shkruaj nga kujtesa ç'din & ç'pyet i pret temës | 5 min |
| 2. **Lexo për kuptim** | Lexo duke ndjekur logjikën koncept → proces → rezultat; nënvizo MOS lista, POR arsyet | 20–30 min |
| 3. **Mbyll & rikujto** | Mbyll tekstin. Përgjigju pyetjeve `> [!question]-` dhe kartelave pa parë përgjigjen | 15 min |
| 4. **Kontrollo & korrigjo** | Hap përgjigjet. Shëno gabimet. Rishkruaj të saktën me fjalët tua | 10 min |
| 5. **Planifiko përsëritjen** | Interval: Dita 1 → 3 → 7 → 14 → 30 ([[SPACED-REPETITION - Kalendari i Përsëritjes]]) | 5 min |

## 🛠️ Si funksionojnë mjetet në Obsidian

### Callout-et e palosshme (rikujtim aktiv)
```markdown
> [!question]- Pyetja?
> Përgjigja e fshehur poshtë — hap vetëm pasi të provosh!
```
Shënimi `-` në fund (`[!question]-`) e bën kutinë **të palosur si default**. Nëse një temë s'ka callout-e, krijo ti vetë: çdo nëntitull → ktheje në pyetje.

### Flashcards për plugin-in Spaced Repetition
```markdown
Çfarë është {{dekomodifikimi::flashcard}}? :: shkallën e pavarësisë nga tregu për standard jetese
```
Ose stil classic `Pyetje :: Përgjigje`. Banka master: [[FLAKCARDS - Banka Master e Flashcard-eve]].

### Dataview (për progres automatik)
Kodet `statusi: "Për t'u mësuar"` / `"E mësuar"` te temat lexohen nga skripta në [[04_Risorse/PLUGINS - Shtesat e Nevojshme për Obsidian|Plugins]] dhe mbledhin statistikat te Dashboard.

## 🎯 Teknika shtesë sipas llojit të materialit

| Materiali | Teknika |
|---|---|
| Përkufizime & terma | Flashcards + GLOSAR |
| Tipologji (p.sh. 3 botët e mirëqenies) | **Matrica krahasuese** — vizatoje nga kujtesa, pastaj krahaso |
| Procese/cikle (cikli i projektit) | **Draw.io/Excalidraw** — riprodho diagramin mermaid memorisht |
| Ligje & rregulla (Fondi Social 90/60/30%) | Kartela + shembull numerik i vet |
| Teori të gjata (Esping-Andersen) | **Feynman Technique**: shpjegoje me gjuhë të thjeshtë sikur flet me nxënës |
| Para provimit | **Interleaving**: përzier pyetje nga 3–4 tema, jo blloqe monoton |

## ⚠️ Gabimet e zakonshme (dushmanët e memorizimit)

1. **Rileximi pasiv** — ndihet produktiv, por efekti ≈ 0. Zëvendëso me rikujtim.
2. **The illusion of competence** — "e njoh kur e shoh" ≠ "mund ta sjell nga kujtesa". Vet-testo.
3. **Overlearning pa pushim** — blloqet ≤50 min + break 10 min (Pomodoro); gjumi konsolidon!
4. **Mesimi pa lidhje** — konceptet e izoluara harrohen; përdor [[MATRIKE-KRYQEZORE - Lidhjet Ndër-lëndësive]].

## 📅 Rituali ditor (minimumi që mos e prish zinxhirin)

- [ ] 15 min flashcards (Spaced Repetition -> due cards)
- [ ] 1 temë e re ose e përsëritur me ciklin 5-hapat
- [ ] 3 rreshta reflektim: Ç'mësova? Ç'shkaka? Ç'riprovohet nesër?

Lidhu me: [[PLAN-JAVOR - Rituali i Studimit]] · [[UDHEZUES-QWEN-CODER - Si ta Përdorim për Studim|Udhëzuesi Qwen Coder]]
