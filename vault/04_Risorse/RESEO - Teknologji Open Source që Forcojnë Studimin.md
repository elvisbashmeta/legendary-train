---
kodi: RES-TEK-01
titulli: "Rezo — Teknologji open source që forcojnë studimin"
tags: [risorse, open-source, qwen, retrieval]
statusi: "Referencë"
data_krijimit: 2026-11-02
---

# 🛠️ RESEO — Teknologji me burim të hapur për vault-in tënd

Këto projekte janë **benefite konkrete** kur punon me **Qwen Coder**: e lejojnë atë të lexojë, kërkohë dhe gjenerojë materiale mbi të dhënat e tua lokale — pa i dërguar askund.

| Projekti | Çfarë bën | Si e përdorim këtu |
|---|---|---|
| **Open Deep Search** | Kërkim semantik lokal mbi dokumente | Qwen Coder mund të indexojë `/workspace/extracted/*.txt` (slides e MPS) dhe të gjejë fragmente për pyetje provimi |
| **Haystack** | Pipeline RAG (lexim → prerje → indeksim → gjenerim) | Automatizon nxjerrjen e përmbledhjeve nga .pptx/.docx të rinj që i vendos në dosje |
| **Weaviate** | Vektor-databazë me hyrde të filtrueshme | Indeks i flashcard-eve sipas `kursi`, `kapitulli`, `statusi` — rijekrim me filtra |
| **Obsidian API (core, closed por lokal)** | Skriptet Dataview/Templater | Të gjitha dashboard-et e këtij vault-i mbështeten peka |

## Udhëzim i shpejtë (opsional, pas provimit)
```bash
# Indeximi i teksteve të extraktuara për kërkim semantik lokal
pip install haystack-ai weaviate-client
python -m haystack.pipeline index /workspace/extracted --into vault-index
```
> [!warning] Prioriteti 0
> Asgjë nuk zëvendëson [[UDHEZUES - Metoda e Studimit me Rikujtim Aktiv]]. Këto mjete janë *lluks* — fitoren e sjell rikujtimi aktiv.

Lidhje: [[UDHEZUES-QWEN-CODER - Si ta Përdorim për Studim]] · [[00_Dashboard/DASHBOARD - Qendra e Studimit|DASHBOARD]]
