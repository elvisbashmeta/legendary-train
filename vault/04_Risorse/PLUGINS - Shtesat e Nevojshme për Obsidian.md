---
kodi: RES-PLG-01
titulli: "Plugins — Shtesat e Nevojshme për Obsidian"
tags: [obsidian, plugins, konfigurim, efikasitet]
statusi: "Referencë"
data_krijimit: 2026-11-02
---

# 🧩 PLUGINS — Shtesat që e kthejnë Vault-in në makinë studimi

> [!tip] Rregulli i artë
> Instalo VETËM këto 7 shtesa. Më pak është më shumë: çdo plugin shtesë të vjedh vëmendje. Hapi: **Settings → Community plugins → Turn off restricted mode → Browse** dhe keqyrto emrat më poshtë.

| # | Plugin | Pse (për studimin tënd) | Si ta përdorim në këtë vault | Konfigurim minimal |
|---|--------|--------------------------|-------------------------------|--------------------|
| 1 | **Spaced Repetition** | Automatizon përsëritjen intervale (D+1→3→7→14→30) brenda Obsidian | Lexon automatikisht [[FLAKCARDS - Banka Master e Flashcard-eve]] me formatin `Pyetje :: Përgjigge`; butonat `#flashcards/MPS` etj. ndajnë lëndët | Settings → global note `00_Dashboard/FLAKCARDS...`; formati "inline": `::` |
| 2 | **Dataview** | Kthen frontmatter-in (`statusi`, `kursi`, `kapitulli`) në lista e tabela dinamike | Dashboard shfaq automatikisht temën "Për t'u mësuar" vs "Të mësuar"; numëron flashcard-at e papërpunuara | Aktivizo "Inline queries" + "JavaScript queries" |
| 3 | **Templater** | Skelona të shpejta për shënime të reja pa ripunim | Shablonet në `_templates/` (Shënim Tema, Flashcard, Përmbledhje javore) | Folder templates → `_templates`; trigger: Ctrl/Cmd+N |
| 4 | **Excalidraw** | Harta konceptuale vizuale (memoria funksionon me imazhe) | Vizaton trekëndëshin koha–kosto–cilësi, ciklin e jetës, matricën Fuqi–Interes si në [[MATRIKE-KRYQEZORE - Lidhjet Ndër-lëndësive]] | Default; eksporto PNG në bashkëlidhje |
| 5 | **Calendar + Periodic Notes** | Rituali ditor/javoor sipas [[PLAN-JAVOR - Rituali i Studimit]] | Shënim ditor me 3 rreshta: çfarë studiova / çfarë rikujtova / çfarë s'(mbaj mend) | Javore: e hënë plan, e diel vet-vlerësim |
| 6 | **Auto Note Mover** (opsional) | Organizon automatikisht shënimet e reja në folderin e duhur | Sipas tag-ut `#mps`, `#abn`, `#aps`, `#ojf`, `#odss` | Vendos rregullat pas krijimit të skeloneve |
| 7 | **Omnisearch** (opsional) | Kërkim fuzzy edhe në tekste pa e pranishmë | Gjen terma të glosarit edhe me gabime shkrimi | Default |

## Verifikim pas instalimit (5 minuta)
- [ ] hap [[FLAKCARDS - Banka Master e Flashcard-eve]] → kliko "Start review" (Spaced Repetition)
- [ ] hap [[DASHBOARD - Qendra e Studimit]] → blloku Dataview duhet të tregojë listën e temave
- [ ] krijo një shënim nga `_templates/Tema e Re` → kontrollo që frontmatter copy vihet vetë
- [ ] te Calendar: shëno ditën e parë të rituales

## Kur të pyesni Qwen Coder
Nëse config-i nuk punon, kopjo mesazhin e gabimit dhe përdor prompt-in nga [[UDHEZUES-QWEN-CODER - Si ta Përdorim për Studim]] § Debug.
