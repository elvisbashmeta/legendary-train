---
kodi: BAZ-01
titulli: "Arkitektura e vault-it — si punon sistemi"
tags: [arkitekturë, strukture, referencë]
statusi: "Referencë"
data_krijimit: 2026-11-02
---

# 🏗️ SISTEMI — Arkitektura e Vault-it

```
vault/
├── .obsidian/          → konfigurimi (hapja e parë: "Open folder as vault")
├── 00_Dashboard/       → QENDRA: DASHBOARD + 5 MOC + metodologjia + kalendari + bankat
├── 01_Kurse/           → LËNDA (5 dosje): tema nga 01..n + banka pyetjesh + folio slides
│   ├── Menaxhimi i Projekteve Sociale/      (17 tema + 2 folio + udhëzues praktik)
│   ├── Analiza krahasuese e politikave sociale/ (12 tema + udhëzues krahasimi)
│   ├── Administrimi i Burimeve Njerezore/   (12 tema)
│   ├── Organizimi dhe Drejtimi i Sherbimeve Sociale/ (12 tema)
│   └── Organizata jofitimprurese.../        (12 module kurs-i)
├── 02_Baza_e_Ndertese/ → ky dokument + burimet bazë të lëndës
├── 03_Praktika/        → rastet reale (Fondi Social, Bashkia Patos, Aneksi C)
├── 04_Risorse/         → PLUGINS · RESEO · UDHEZUES-QWEN-CODER
└── _templates/         → shablonet Templater (Tema e Re, Flashcard, Përmbledhje Javore)
```

## Konventat që e mbajnë sistemin të gjallë
- **Frontmatter** (`statusi`, `kursi`, `kapitulli`) → ushqen Dataview. Ndrysho `statusi: "Për t'u mësuar"` → `"Të mësuar"` pasi kalon vet-testin me ≥80%.
- **Wiki-links me kllapa katrore** → çdo temë lidhet me MOC-në dhe me fqinjët (⬅️ ➡️). Lidhjet e kuqe = skedar që mund ta krijoni (p.sh. leksionet që mungojnë).
- **Flashcards `Pyetje :: Përgjigje`** → format universal; nëse s'keni plugin, mbulo pjesën pas `::`.
- **Emërtimi**: `Tema NN - Titull.md`; pa karaktere të ndaluara (`/ \ : * ? " < > |`).

## Rendi i përdorimit (rrjedha e vetme e saktë)
1. [[DASHBOARD - Qendra e Studimit|Hap DASHBOARD]] → 2. zgjidh MOC-në e lëndës → 3. [[UDHEZUES - Metoda e Studimit me Rikujtim Aktiv|lexo metodën 1 herë]] → 4. studio temën sipas [[SPACED-REPETITION - Kalendari i Përsëritjes|kalendari]] → 5. testohu me [[FLAKCARDS - Banka Master e Flashcard-eve|bankën master]] → 6. për rastet reale shko te [[03_Praktika/RASTI - Fondi Social 2024 dhe Bashkia Patos|Rasti: Fondi Social/Patos]].
