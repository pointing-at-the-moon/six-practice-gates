# NIAN_FORMAT_AUDIT_2026Q2

**Date:** 2026-05-04
**Executor:** Code Sonnet 4.6 on commit `31b09cf`
**Last nian/papers commit:** `2026-05-03 23:38:22 -0700 nian: publish P31 — NIAN 31/31 sealed`
**Scope:** 62 files (31 en + 31 zh) under `nian/papers/part{1..8}_*/`
**Mode:** read-only audit (no edits, no commits)

> **Scope-check note:** `find nian/papers -name 'P*.md' | wc -l` yields 64 total, but 2 are rag-archive files
> (`part7_flower_ornament/rag/P26/v1_archive/P26.md` and `…P26_禮敬諸佛稱讚如來.md`). Excluding `/rag/` paths
> yields exactly 62 in-scope files. Audit proceeds on the 62 papers only.

---

## Section 1 — Manifest

| Paper | lang | part | section_style | abstract_style | has_author_block | has_zh_sub | sub_colon | references_heading | xref_loc | footer_form | FW_hits | trailing_orphan | yaml_series (truncated) | yaml_date | yaml_version |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| NIAN-P01 | en | 1 | arabic | bold_inline | False | False | absent | References | absent | A_short_en | 0 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P01 | zh | 1 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | absent | C_short_zh | 0 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P02 | en | 1 | arabic | bold_inline | False | False | absent | References | inside_references | B_short_bilingual | 20 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P02 | zh | 1 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | C_short_zh | 0 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P03 | en | 1 | arabic | bold_inline | False | False | absent | References | inside_references | A_short_en | 39 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P03 | zh | 1 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | C_short_zh | 0 | — | NIAN · Part I · Foundations (Pāli) | MISSING | None |
| NIAN-P04 | en | 1 | arabic | h2_heading | False | False | absent | References | inside_references | B_short_bilingual | 13 | — | MISSING | MISSING | None |
| NIAN-P04 | zh | 1 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | B_short_bilingual | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-15 | None |
| NIAN-P05 | en | 2 | roman | bold_inline | False | False | absent | Bibliography | inside_references | C_short_zh | 112 | — | NIAN · Part II · The Earliest Chinese Re | MISSING | None |
| NIAN-P05 | zh | 2 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | C_short_zh | 0 | — | NIAN · Part II · The Earliest Chinese Re | MISSING | None |
| NIAN-P06 | en | 3 | roman | h2_heading | False | False | absent | References | both | B_short_bilingual | 21 | — | MISSING | MISSING | None |
| NIAN-P06 | zh | 3 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | B_short_bilingual | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-16 | None |
| NIAN-P07 | en | 3 | roman | h2_heading | False | False | absent | References | both | B_short_bilingual | 16 | — | MISSING | MISSING | None |
| NIAN-P07 | zh | 3 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | B_short_bilingual | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-17 | None |
| NIAN-P08 | en | 3 | roman | h2_heading | False | False | absent | References | both | B_short_bilingual | 19 | — | MISSING | MISSING | None |
| NIAN-P08 | zh | 3 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | B_short_bilingual | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-17 | None |
| NIAN-P09 | en | 4 | roman | h2_heading | True | True | fullwidth | References | both | D_long_copyright | 12 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-17 | 1.0 |
| NIAN-P09 | zh | 4 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | D_long_copyright | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-17 | None |
| NIAN-P10 | en | 4 | roman | h2_heading | True | True | fullwidth | References | inside_references | other | 31 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-17 | 1.0 |
| NIAN-P10 | zh | 4 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-17 | None |
| NIAN-P11 | en | 4 | roman | h2_heading | True | True | fullwidth | References | inside_references | other | 13 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-17 | 1.0 |
| NIAN-P11 | zh | 4 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-17 | None |
| NIAN-P12 | en | 5 | roman | h2_heading | True | True | fullwidth | References | inside_references | other_italic | 11 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-18 | 1.0 |
| NIAN-P12 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-18 | None |
| NIAN-P13 | en | 5 | roman | h2_heading | True | True | fullwidth | References | inside_references | other_italic | 9 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-18 | 1.0 |
| NIAN-P13 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-18 | None |
| NIAN-P14 | en | 5 | roman | h2_heading | True | True | fullwidth | References | inside_references | other_italic | 4 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-18 | 1.0 |
| NIAN-P14 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-18 | None |
| NIAN-P15 | en | 5 | roman | h2_heading | True | True | fullwidth | Bibliography | inside_references | other_italic | 2 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-19 | 1.0 |
| NIAN-P15 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-19 | None |
| NIAN-P16 | en | 5 | roman | h2_heading | True | True | fullwidth | References | inside_references | other_italic | 17 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-20 | 1.0 |
| NIAN-P16 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-20 | None |
| NIAN-P17 | en | 5 | roman | h2_heading | True | True | fullwidth | Bibliography | inside_references | other_italic | 1 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-20 | 1.0 |
| NIAN-P17 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-20 | 1.0 |
| NIAN-P18 | en | 5 | roman | h2_heading | True | True | fullwidth | References | inside_references | other_italic | 33 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-20 | 1.0 |
| NIAN-P18 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | inside_references | other_italic | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-20 | 1.0 |
| NIAN-P19 | en | 5 | roman | h2_heading | True | True | fullwidth | References | both | other | 3 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-21 | 1.0 |
| NIAN-P19 | zh | 5 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | other | 0 | — | 四行門卷一《念——從阿含隨念到華嚴念佛》 | 2026-04-21 | 1.0 |
| NIAN-P20 | en | 6 | roman | h2_heading | True | True | fullwidth | References | inside_references | other | 86 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-21 | 1.0 |
| NIAN-P20 | zh | 6 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | other | 0 | — | 四行門卷一《念》—— 從早期佛教隨念到華嚴願景 | 2026-04-21 | 1.0 |
| NIAN-P21 | en | 6 | roman | h2_heading | True | True | fullwidth | References | inside_references | other | 146 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-23 | 1.0 |
| NIAN-P21 | zh | 6 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | other | 0 | — | 四行門卷一《念》—— 從早期佛教隨念到華嚴念佛 | 2026-04-23 | 1.0 |
| NIAN-P22 | en | 6 | roman | h2_heading | True | True | halfwidth | References | inside_references | other | 1 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-04-29 | 1.0 |
| NIAN-P22 | zh | 6 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | D_long_copyright | 0 | — | NIAN — Mindful of the Buddha | 2026-04 | 1.0 |
| NIAN-P23 | en | 6 | roman | h2_heading | True | True | fullwidth | References | absent | other | 0 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | 1.0 |
| NIAN-P23 | zh | 6 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | absent | D_long_copyright | 0 | — | NIAN — Mindful of the Buddha | 2026-05 | 1.0 |
| NIAN-P24 | en | 6 | roman | h2_heading | True | True | halfwidth | References | absent | other | 8 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | 1.0 |
| NIAN-P24 | zh | 6 | chinese_numeral | h2_heading | False | False | absent | (none) | absent | D_long_copyright | 0 | — | NIAN — Mindful of the Buddha | 2026-05 | 1.0 |
| NIAN-P25 | en | 7 | roman | h2_heading | True | True | halfwidth | References | absent | other | 0 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | 1.0 |
| NIAN-P25 | zh | 7 | chinese_numeral | h2_heading | False | False | absent | (none) | absent | D_long_copyright | 0 | — | 《念》Part VII《華嚴普賢之願》第一篇 | 2026-05-02 | None |
| NIAN-P26 | en | 7 | roman | h2_heading | True | True | fullwidth | References | absent | other | 2 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | None |
| NIAN-P26 | zh | 7 | chinese_numeral | h2_heading | False | False | absent | (none) | absent | D_long_copyright | 0 | — | 《念》Part VII《華嚴普賢之願》第二篇 | 2026-05-02 | None |
| NIAN-P27 | en | 7 | roman | h2_heading | True | True | fullwidth | References | absent | other | 2 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | None |
| NIAN-P27 | zh | 7 | chinese_numeral | h2_heading | False | False | absent | (none) | absent | D_long_copyright | 0 | — | NIAN | 2026-05-02 | None |
| NIAN-P28 | en | 7 | roman | h2_heading | True | True | fullwidth | References | absent | other | 2 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | None |
| NIAN-P28 | zh | 7 | chinese_numeral | h2_heading | False | False | absent | (none) | absent | D_long_copyright | 0 | — | NIAN | 2026-05-03 | None |
| NIAN-P29 | en | 7 | roman | h2_heading | True | True | fullwidth | Bibliography | absent | other | 9 | — | Four Practice Gates, Volume 1 — Mindful  | 2026-05 | None |
| NIAN-P29 | zh | 7 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | absent | D_long_copyright | 0 | — | NIAN | 2026-05-03 | None |
| NIAN-P30 | en | 8 | roman | h2_heading | True | False | absent | References | inside_references | D_long_copyright | 5 | 8.1 | NIAN | 2026-05 | 1.0 |
| NIAN-P30 | zh | 8 | chinese_numeral | h2_heading | False | False | absent | 參考文獻 | both | D_long_copyright | 0 | 8.1 | NIAN | 2026-05 | 1.0 |
| NIAN-P31 | en | 8 | roman | h2_heading | True | False | absent | (none) | absent | D_long_copyright | 3 | — | NIAN | 2026-05 | 1.0 |
| NIAN-P31 | zh | 8 | chinese_numeral | h2_heading | False | False | absent | (none) | separate_section | D_long_copyright | 0 | — | NIAN | 2026-05-03 | None |

---

## Section 2 — D-1 Section-Style Classification

| Paper | EN style | ZH style | EN match ZH? | Notes |
|---|---|---|---|---|
| P01 | arabic | chinese_numeral | NO — by design | Arabic top-level (P01–P04 only) |
| P02 | arabic | chinese_numeral | NO — by design | Arabic top-level (P01–P04 only) |
| P03 | arabic | chinese_numeral | NO — by design | Arabic top-level (P01–P04 only) |
| P04 | arabic | chinese_numeral | NO — by design | Arabic top-level (P01–P04 only) |
| P05 | roman | chinese_numeral | NO — by design | Roman top-level |
| P06 | roman | chinese_numeral | NO — by design | Roman top-level |
| P07 | roman | chinese_numeral | NO — by design | Roman top-level |
| P08 | roman | chinese_numeral | NO — by design | Roman top-level |
| P09 | roman | chinese_numeral | NO — by design | Roman top-level |
| P10 | roman | chinese_numeral | NO — by design | Roman top-level |
| P11 | roman | chinese_numeral | NO — by design | Roman top-level |
| P12 | roman | chinese_numeral | NO — by design | Roman top-level |
| P13 | roman | chinese_numeral | NO — by design | Roman top-level |
| P14 | roman | chinese_numeral | NO — by design | Roman top-level |
| P15 | roman | chinese_numeral | NO — by design | Roman top-level |
| P16 | roman | chinese_numeral | NO — by design | Roman top-level |
| P17 | roman | chinese_numeral | NO — by design | Roman top-level |
| P18 | roman | chinese_numeral | NO — by design | Roman top-level |
| P19 | roman | chinese_numeral | NO — by design | Roman top-level |
| P20 | roman | chinese_numeral | NO — by design | Roman top-level |
| P21 | roman | chinese_numeral | NO — by design | Roman top-level |
| P22 | roman | chinese_numeral | NO — by design | Roman top-level |
| P23 | roman | chinese_numeral | NO — by design | Roman top-level |
| P24 | roman | chinese_numeral | NO — by design | Roman top-level |
| P25 | roman | chinese_numeral | NO — by design | Roman top-level |
| P26 | roman | chinese_numeral | NO — by design | Roman top-level |
| P27 | roman | chinese_numeral | NO — by design | Roman top-level |
| P28 | roman | chinese_numeral | NO — by design | Roman top-level |
| P29 | roman | chinese_numeral | NO — by design | Roman top-level |
| P30 | roman | chinese_numeral | NO — by design | Roman top-level |
| P31 | roman | chinese_numeral | NO — by design | Roman top-level |

**Summary:** 4 EN papers use Arabic top-level headings (P01–P04), 27 use Roman (P05–P31). ZH files uniformly use Chinese numeral headings (一、二、三…) — structurally equivalent to Roman in EN, but different notation system. Drift boundary: between P04 (Arabic, 2026-04-15) and P05 (Roman, 2026-04-15). No papers use alphabetic (A. B. C.) top-level headings anywhere in the corpus.

**Alphabetic-label scan:** `grep -r '^## [A-Z]\.' nian/papers/` — zero hits corpus-wide. Brief's suspicion confirmed negative.

---

## Section 3 — D-2 EN Drift (Full-Width Punctuation in EN Files)

> **Detection method:** grep `[（）「」『』，。、；：！？]` in EN files, excluding YAML front-matter, code blocks, and
> blockquotes where >30% surrounding chars are CJK. Lines where the ±20-char context has >50% CJK are suppressed.
> Remaining hits are EN-drift candidates.

| Paper | Hit count | First 3 examples (±20 char context) |
|---|---|---|
| P01 | 0 | — |
| P02 | **20** | `…ānaṃ buddho bhagavā*。本文主張：*Itipi so* 不是讚詩…` / `…buddho bhagavā*。本文主張：*Itipi so* 不是讚詩、不是敬稱…` / `…**關鍵詞：** itipi so、九德、十號、如來…` |
| P03 | **39** | `…巴利尼柯耶所載「六隨念」（*cha anussatiyo…` / `…巴利尼柯耶所載「六隨念」（*cha anussatiyo*）——…` / `…巴利尼柯耶所載「六隨念」（*cha anussatiyo*）——念…` |
| P04 | **13** | `…本篇精確界定近行定（*upacāra-samādhi*）與安…` / `…行定（*upacāra-samādhi*）與安止定（*appanā-samādhi…` / `…pacāra-samādhi*）與安止定（*appanā-samādhi*）兩詞之…` |
| P05 | **112** | `…Forty-Two Sections* （四十二章經， T0784), tradi…` / `…Two Sections* （四十二章經， T0784), traditional…` / `…to Kāśyapa Mātaṅga （迦葉摩騰） and Dharmaratn…` |
| P06 | **21** | `…面對性／認知親歷性）為結構骨架的現前三昧（*pratyutpanna-samādh…` / `…ratyutpanna-samādhi*）技術。本篇提出三重論證：其一，巴利（*P…` / `…yutpanna-samādhi*）技術。本篇提出三重論證：其一，巴利（*Pāli…` |
| P07 | **16** | `…續 P06 對《般舟三昧經》（T0418）見佛層的處理，追蹤佛國（*buddha-…` / `…《般舟三昧經》（T0418）見佛層的處理，追蹤佛國（*buddha-kṣetra*…` / `…經》（T0418）見佛層的處理，追蹤佛國（*buddha-kṣetra*）作為可往…` |
| P08 | **19** | `…P07 結尾提出的開放問題：*niàn*（念、憶念）如何讓位給 *chēng*（稱…` / `…7 結尾提出的開放問題：*niàn*（念、憶念）如何讓位給 *chēng*（稱、稱…` / `…尾提出的開放問題：*niàn*（念、憶念）如何讓位給 *chēng*（稱、稱名）？…` |
| P09 | **12** | `…**關鍵詞：** 四十八願、T0360《無量壽經》、…` / `…**關鍵詞：** 四十八願、T0360《無量壽經》、T0362 支謙…` / `…：** 四十八願、T0360《無量壽經》、T0362 支謙譯本、T0361 二十四…` |
| P10 | **31** | `…繼承自 T0643《佛說觀佛三昧海經》（佛陀跋陀羅譯，約 418–422 CE；…` / `…643《佛說觀佛三昧海經》（佛陀跋陀羅譯，約 418–422 CE；比 T0365…` / `…（佛陀跋陀羅譯，約 418–422 CE；比 T0365 早十至二十年），但線性十…` |
| P11 | **13** | `…yī-xīn bú-luàn* 執持名號、一日至七日、一心不亂) — is *no…` / `…bú-luàn* 執持名號、一日至七日、一心不亂) — is *not* a r…` / `…（T0366，鳩摩羅什 402 CE 譯）。主張三事：其一，T0366「執持名號、…` |
| P12 | **11** | `…ngniàn xiāngjì* 都攝六根、淨念相繼) is the dual-ax…` / `…yī-xīn bú-luàn* 執持名號、一心不亂) argued in P11…` / `…主張三事：其一，T0945 的「都攝六根、淨念相繼」是 P11 所論 T0366「…` |
| P13 | **9** | `…iān rén zé duō* 圓人唯一、偏人則多) qualitative ra…` / `…**關鍵詞：** 法華稱名、T0262《妙法蓮華經》…` / `…派念佛、T0262 與 T0366 並列。…` |
| P14 | **4** | `…fǎ bù suíshùn* 唯除頓覺人，并法不隨順). This self-li…` / `…xié fǎ zēngchì* 去佛漸遠、賢聖隱伏、邪法增熾)[^2] into…` / `…ǎ zēngchì* 去佛漸遠、賢聖隱伏、邪法增熾)[^2] into the v…` |
| P15 | **2** | `…-wú, lí yīn-guǒ* 離色心、離有無、離因果 — apart from…` / `…lí yīn-guǒ* 離色心、離有無、離因果 — apart from for…` |
| P16 | **17** | `…品〉為核心文本，結合 T0663 曇無讖、T0664 真諦合本、T0665 義淨三…` / `…ion 機制與 Augustine 告解、圓覺（P14）結三期、梵網（P15）見好…` / `…機制與 Augustine 告解、圓覺（P14）結三期、梵網（P15）見好相相區…` |
| P17 | **1** | `…ēi niànlǜ xīn* 樹木堅實心，非念慮心) locks the term…` |
| P18 | **33** | `…es." Original text: 「如來清淨藏，亦名無垢智，常住無終始，離四…` / `…淨藏，世間阿賴耶，如金與指環，展轉無差別。」A principal Chinese…` / `…藏，世間阿賴耶，如金與指環，展轉無差別。」A principal Chinese-…` |
| P19 | **3** | `…yī-zhí-xīn* 於一切處行住坐臥，常行一直心), "unmoving ri…` / `…n chéng jìngtǔ* 不動道場，真成淨土), self-power an…` / `…n chēng míngzì* 繫心一佛，專稱名字) to "at all pla…` |
| P20 | **86** | `…et the Chinese term 「他力」 predates Shinran…` / `…the Chinese term 「他力」 predates Shinran by…` / `…儜弱怯劣), and lists no 「他力」 vocabulary. Tanl…` |
| P21 | **146** | `…fourteen characters 「念佛即是念心，求心即是求佛」 — *re…` / `…n characters 「念佛即是念心，求心即是求佛」 — *recollect…` / `…cters 「念佛即是念心，求心即是求佛」 — *recollecting the…` |
| P22 | **1** | `…-niàn xiāng-jì* 都攝六根，淨念相繼) finds psycholo…` |
| P23 | 0 | — |
| P24 | **8** | `…hì wèi lǐ-chí* (憶念無間，是謂事持；體究無間，是謂理持). CBE…` / `…i lǐ-chí* (憶念無間，是謂事持；體究無間，是謂理持). CBETA *W…` / `…chí* (憶念無間，是謂事持；體究無間，是謂理持). CBETA *Wàn xù…` |
| P25 | 0 | — |
| P26 | **2** | `…tuìzuò yīmiàn* 稽首佛足，退坐一面). On a first re…` / `…ú zì pí láo yě* 不入斯觀，徒自疲勞也) — declares pl…` |
| P27 | **2** | `…> Shi Huijing （釋慧鏡）…` / `…> Shi Huijing （釋慧鏡）…` |
| P28 | **2** | `…> Shi Huijing （釋慧鏡）…` / `…> Shi Huijing （釋慧鏡）…` |
| P29 | **9** | `…great-wisdom"* (大悲下化、大智上求). Zongmi suppli…` / `…great-wisdom"* (大悲下化、大智上求) — formalises t…` / `…great-wisdom"* (大悲下化、大智上求) — encodes, in…` |
| P30 | **5** | `…十念、湛然無情有性、趙州狗子無、一念相應、AI 時代、Hershock、Schne…` / `…情有性、趙州狗子無、一念相應、AI 時代、Hershock、Schneider 二…` / `…、一念相應、AI 時代、Hershock、Schneider 二元、心理學化…` |
| P31 | **3** | `…ithout break*" (都攝六根，淨念相繼), the eight-cha…` / `…Part VIII Coda 之收束篇。承續 P30 之義理收束篇對 AI 時代…` / `…；NIAN 全卷封筆；四行門書系；釋慧鏡；2026-05…` |

**Summary:** 28 EN papers have full-width punctuation drift, 3 are clean. Total raw hits across 31 EN files: 640. Top 5 offenders: P21 (146), P05 (112), P20 (86), P03 (39), P18 (33).

> **Note on hit taxonomy:** Many hits in P02–P19 are inline transliterations surrounded by CJK context (`（念佛，niànfó*）`-style).
> In P20–P21 the bulk of hits are EN-prose quotes from Chinese sources using `「...」` — e.g., `「他力」 predates Shinran`.
> These two sub-types have different remediation paths and should be counted separately in the remediation brief.

**Clean papers (0 hits):** P23, P25 (2 papers)

**Clean paper list:** P01, P23, P25

---

## Section 4 — D-3 Footer Inventory

### 4.1 EN Footer Forms

| Paper | footer_form | verbatim (truncated to 90 chars) |
|---|---|---|
| P01 | A_short_en | `*NIAN-P01 · Shi Huijing · 2026-04-14*` |
| P02 | B_short_bilingual | `*NIAN-P02 · 釋慧鏡 (Shi Huijing) · 2026-04-14*` |
| P03 | A_short_en | `*NIAN-P03 · Shi Huijing · 2026-04-15*` |
| P04 | B_short_bilingual | `*NIAN-P04 · 釋慧鏡 (Shi Huijing) · 2026-04-15*` |
| P05 | C_short_zh | `*NIAN-P05 · 釋慧鏡 · 2026-04-15*` |
| P06 | B_short_bilingual | `*NIAN-P06 · 釋慧鏡 (Shi Huijing) · 2026-04-16*` |
| P07 | B_short_bilingual | `*NIAN-P07 · 釋慧鏡 (Shi Huijing) · 2026-04-17*` |
| P08 | B_short_bilingual | `*NIAN-P08 · 釋慧鏡 (Shi Huijing) · 2026-04-17*` |
| P09 | D_long_copyright | `*GitHub: https://github.com/pointing-at-the-moon/four-practice-gates*` |
| P10 | other | `**GitHub:** github.com/pointing-at-the-moon/four-practice-gates` |
| P11 | other | `**Repo:** github.com/pointing-at-the-moon/four-practice-gates` |
| P12 | other_italic | `*Source: T0945 verified against CBETA Chinese Electronic Tripiṭaka 2024*` |
| P13 | other_italic | `*CBETA verification: all T-number citations are entity-verified against the CBETA Electron` |
| P14 | other_italic | `*CBETA verification: all T-number and X-number citations are entity-verified against the C` |
| P15 | other_italic | `*CBETA verification: all T-number and X-number citations are entity-verified against the C` |
| P16 | other_italic | `*CBETA verification: All T-number and X-number citations are verified against the CBETA El` |
| P17 | other_italic | `*CBETA collation: all T-number / X-number citations verified against the CBETA Electronic ` |
| P18 | other_italic | `*CBETA verification: all T-number citations have been verified against the CBETA Electroni` |
| P19 | other | `GitHub: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P20 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P21 | other | `Book series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P22 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P23 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P24 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P25 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P26 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P27 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P28 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P29 | other | `Series GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P30 | D_long_copyright | `*This paper is the Part VIII Coda opener of *Mindful of the Buddha*, Volume One of *The Fo` |
| P31 | D_long_copyright | `*This paper is the Part VIII Coda closer of *Mindful of the Buddha*, Volume One of *The Fo` |

### 4.2 ZH Footer Forms

| Paper | footer_form | verbatim (truncated to 90 chars) |
|---|---|---|
| P01 | C_short_zh | `*NIAN-P01 · 釋慧鏡 · 2026-04-14*` |
| P02 | C_short_zh | `*NIAN-P02 · 釋慧鏡 · 2026-04-14*` |
| P03 | C_short_zh | `*NIAN-P03 · 釋慧鏡 · 2026-04-15*` |
| P04 | B_short_bilingual | `*NIAN-P04 · 釋慧鏡 (Shi Huijing) · 2026-04-15*` |
| P05 | C_short_zh | `*NIAN-P05 · 釋慧鏡 · 2026-04-15*` |
| P06 | B_short_bilingual | `*NIAN-P06 · 釋慧鏡 (Shi Huijing) · 2026-04-16*` |
| P07 | B_short_bilingual | `*NIAN-P07 · 釋慧鏡 (Shi Huijing) · 2026-04-17*` |
| P08 | B_short_bilingual | `*NIAN-P08 · 釋慧鏡 (Shi Huijing) · 2026-04-17*` |
| P09 | D_long_copyright | `*GitHub: https://github.com/pointing-at-the-moon/four-practice-gates*` |
| P10 | other | `**Repo:** github.com/pointing-at-the-moon/four-practice-gates` |
| P11 | other | `**Repo:** github.com/pointing-at-the-moon/four-practice-gates` |
| P12 | other_italic | `*CBETA 校對：所有 T-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證*` |
| P13 | other_italic | `*CBETA 校對：所有 T-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證*` |
| P14 | other_italic | `*CBETA 校對：所有 T-number／X-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證*` |
| P15 | other_italic | `*CBETA 校對：所有 T-number／X-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證。T1484 引文據卷下原典；T1501 引文據玄奘譯《菩薩戒` |
| P16 | other_italic | `*CBETA 校對：所有 T-number／X-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證。T0663／T0664／T0665 三譯引文據 CBETA ` |
| P17 | other_italic | `*CBETA 校對：所有 T-number／X-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證。T0670／T0671／T0672 三譯引文據 CBETA ` |
| P18 | other_italic | `*CBETA 校對：所有 T-number 引文均據 CBETA 電子佛典集成 2024 版實體驗證。T0681／T0682 雙譯本引文據《大正藏》冊 16；§2.2 [^7] [` |
| P19 | other | `GitHub: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P20 | other | `本書系 GitHub repository：https://github.com/pointing-at-the-moon/four-practice-gates` |
| P21 | other | `本書系 GitHub repository: https://github.com/pointing-at-the-moon/four-practice-gates` |
| P22 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P23 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P24 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P25 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P26 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P27 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P28 | D_long_copyright | `*GitHub: github.com/pointing-at-the-moon/four-practice-gates*` |
| P29 | D_long_copyright | `*CC BY-NC-SA 4.0 · CBETA 大正藏／卍續藏電子版校對 · github.com/pointing-at-the-moon/four-practice-gate` |
| P30 | D_long_copyright | `*本論為《四行門》第一卷《念》之 Part VIII Coda opener。© 釋慧鏡 2026 · CC BY-NC-SA 4.0 · 本論引用之大正藏資料皆據 CBETA 電` |
| P31 | D_long_copyright | `*CC BY-NC-SA 4.0 · CBETA 大正藏／卍續藏電子版校對 · github.com/pointing-at-the-moon/four-practice-gate` |

### 4.3 Trailing Orphan Tokens and Special Lines

| Paper | lang | token | Description |
|---|---|---|---|
| P30 | en | `8.1` | **Bare section-number orphan** after footer `---` block |
| P30 | zh | `8.1` | **Bare section-number orphan** after footer `---` block |
| P31 | en | `§ 8.2 — NIAN Part VIII Coda Closer · NIAN 31/31 ✅ …` | **Pre-footer coda-marker block** between two `---` separators; is a body element, not a footer line. Chat Opus ruling needed. |

**Summary:** 6 distinct footer forms observed corpus-wide. Form `B_short_bilingual` (*NIAN-P## · 釋慧鏡 (Shi Huijing) · date*) appears in EN P02, P04, P06, P07, P08 and ZH P04, P06, P07, P08 — 8 total uses. A large cluster of EN P09–P29 uses `other` (bare GitHub URL or bold `**Repo:**`/`**GitHub:**` lines, not wrapped in `*…*`). A cluster of ZH P09–P29 uses `other_italic` (CBETA collation notice without NIAN-P## identifier). Forms A, C, D, E also present.

**Two structural families not in the original brief taxonomy:**
- `other_italic` (EN P12–P18): CBETA verification notice — italic, but no NIAN-P## identifier and no date. Example: `*CBETA verification: all T-number citations have been verified…*`
- `other` (EN P09–P29 mostly): bare GitHub URL or bold `**Repo:**` block — not italic at all.

---

## Section 5 — D-4 References-Section Inventory

### 5.1 EN References Section

| Paper | top heading | sub-headings (verbatim) | xref-index location |
|---|---|---|---|
| P01 | References | — | absent |
| P02 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | inside_references |
| P03 | References | `I. Primary Buddhist Sources 佛教原典`; `II. Modern Scholarship 現代學術著作`; `III. Sūtra & Śāstra Index 經論索引` | inside_references |
| P04 | References | `Primary Sources (Sūtra and Vinaya)`; `Commentaries & Śāstras`; `Secondary Literature`; `Cross-Reference Index` | inside_references |
| P05 | Bibliography | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Index of Sūtras and Śāstras` | inside_references |
| P06 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | both |
| P07 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | both |
| P08 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | both |
| P09 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | both |
| P10 | References | `I. Primary Buddhist Sources`; `II. Cross-Reference Index`; `III. Sūtra & Śāstra Index` | inside_references |
| P11 | References | `I. Primary Buddhist Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-Reference to Series Papers`; `V. Sūtra & Śāstra Index` | inside_references |
| P12 | References | `I. Primary Buddhist Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-Reference to Series Papers`; `V. Sūtra & Śāstra Index` | inside_references |
| P13 | References | `I. Canonical Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-References Within the Series`; `V. Canonical Index` | inside_references |
| P14 | References | `I. Canonical Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-References Within the Series`; `V. Canonical Index` | inside_references |
| P15 | Bibliography | `I. Buddhist Canonical Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-References Within the Series`; `V. Canonical Index` | inside_references |
| P16 | References | `I. Buddhist Canonical Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-References Within the Series`; `V. Canonical Index` | inside_references |
| P17 | Bibliography | `I. Buddhist Primary Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Cross-Series Internal References`; `V. Index of Sūtras and Treatises` | inside_references |
| P18 | References | `I. Buddhist Canonical Sources`; `II. Patriarchal Commentaries`; `III. Modern Scholarship`; `IV. Series-Internal Cross-References`; `V. Sūtra-Śāstra Index` | inside_references |
| P19 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | both |
| P20 | References | `I. Primary Buddhist Sources (Taishō Tripiṭaka)`; `II. Ancient Chinese Commentaries`; `III. Modern Scholarship`; `IV. Sūtra and Śāstra Index` | inside_references |
| P21 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | inside_references |
| P22 | References | `I. Primary Buddhist Sources (Taishō Tripiṭaka)`; `II. Ancient Chinese Commentaries`; `III. Modern Scholarship`; `IV. Sūtra and Śāstra Index` | inside_references |
| P23 | References | `Primary sources`; `Secondary sources` | absent |
| P24 | References | `Primary Sources (CBETA Taishō and *Wàn xùzàng*)`; `Secondary Scholarship` | absent |
| P25 | References | `Primary Sources`; `Secondary Scholarship` | absent |
| P26 | References | `Primary Sources`; `Secondary Scholarship` | absent |
| P27 | References | `Primary Canonical Texts`; `Secondary Scholarship` | absent |
| P28 | References | `Primary Canonical Texts`; `Secondary Scholarship` | absent |
| P29 | Bibliography | `Primary Sources`; `Secondary Scholarship` | absent |
| P30 | References | `I. Primary Buddhist Sources`; `II. Modern Scholarship`; `III. Sūtra & Śāstra Index` | inside_references |
| P31 | (none) | — | absent |

### 5.2 ZH References Section

| Paper | top heading | sub-headings (verbatim) | xref-index location |
|---|---|---|---|
| P01 | 參考文獻 | — | absent |
| P02 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | inside_references |
| P03 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | inside_references |
| P04 | 參考文獻 | `原典｜Primary Sources（經與律）`; `論疏｜Commentaries & Śāstras`; `次要文獻｜Secondary Literature`; `索引表｜Cross-Reference Index` | inside_references |
| P05 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | inside_references |
| P06 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P07 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P08 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P09 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P10 | 參考文獻 | `一、佛教原典`; `二、系列論文交叉引用`; `三、經論索引` | inside_references |
| P11 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P12 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P13 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P14 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P15 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P16 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P17 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P18 | 參考文獻 | `一、佛教原典`; `二、祖師註疏`; `三、現代學術`; `四、系列論文交叉引用`; `五、經論索引` | inside_references |
| P19 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P20 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P21 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P22 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P23 | 參考文獻 | `一手文獻`; `二手文獻` | absent |
| P24 | (none) | — | absent |
| P25 | (none) | — | absent |
| P26 | (none) | — | absent |
| P27 | (none) | — | absent |
| P28 | (none) | — | absent |
| P29 | 參考文獻 | `經典原典（大正藏／卍續藏）`; `現代學術文獻（英文學界）` | absent |
| P30 | 參考文獻 | `一、佛教原典 Primary Buddhist Sources`; `二、現代學術著作 Modern Scholarship`; `三、經論索引 Sūtra & Śāstra Index` | both |
| P31 | (none) | — | separate_section |

**Summary (EN):** `References` used 26×; `Bibliography` used 4× (P05, P15, P17, P29); `(none)` 1× (P31, coda paper). Sub-heading structure evolves in three phases:
- **P01:** no sub-headings
- **P02–P09:** 3-part Roman (`### I. Primary Buddhist Sources`, `### II. Modern Scholarship`, `### III. Sūtra & Śāstra Index`) — most consistent block
- **P04:** outlier — no Roman numerals in sub-headings (`### Primary Sources (Sūtra and Vinaya)`, etc.)
- **P10–P14:** 5-part Roman (adds `### II. Patriarchal Commentaries`, `### IV. Cross-Reference to Series Papers`)
- **P23–P29:** 2-part flat (`### Primary sources`, `### Secondary sources` — no Roman numerals, abbreviated)

Cross-reference index location also drifts: `inside_references` (P02–P22), `separate_section` (P06–P09, P19–P22 — appears as both), `absent` (P23–P29, P31).

**ZH missing ref heading:** P24, P25, P26, P27, P28 have no `## 參考文獻` heading. P31 also missing.

---

## Section 6 — Optional Diagnostics

### O-1 YAML Field Consistency

#### O-1a: `paper_id` field

| Issue | Papers |
|---|---|
| `paper_id: MISSING` (field absent from YAML, or parse failed) | P04 en, P06 en, P07 en, P08 en — **see Anomaly #9: YAML parse failure** due to bare `*` in `series:` field; actual paper_id is present and correct |
| Underscore separator `NIAN_P##` (should be `NIAN-P##`) | P25 zh, P26 en/zh, P27 en/zh, P28 en/zh, P29 en/zh, P31 zh |
| `paper_id` present and correct (`NIAN-P##`) | all others |

#### O-1b: `date` field

| Issue | Papers |
|---|---|
| `date` field genuinely absent from YAML | P01 en/zh, P02 en/zh, P03 en/zh, P05 en/zh (no date field in YAML at all) |
| `date` field present but unparseable | P04 en, P06 en, P07 en, P08 en — YAML parse failure (Anomaly #9); actual date values: 2026-04-15, 2026-04-16, 2026-04-17, 2026-04-17 |
| Month-only format `YYYY-MM` (too lossy per brief) | P22 zh, P23 en/zh, P24 en/zh, P25 en, P26 en, P27 en, P28 en, P29 en, P30 en/zh, P31 en |
| Full ISO date `YYYY-MM-DD` | P04 zh, P06 zh, P07 zh, P08 zh, P09–P22 en (most), P25 zh, P26 zh, P27 zh, P28 zh, P29 zh, P31 zh |

#### O-1c: `version` field

| Issue | Papers |
|---|---|
| `version: null` (field absent) | P01–P08 en/zh (except P09 en, P17 zh, P18 zh) |
| `version: 1.0` present | P09 en, P10–P22 en, P17–P22 zh |
| Later papers (P23–P31): mixed | P23–P29 en has it; P25–P29 zh and P30–P31 zh absent |

#### O-1d: `series` field variants

| Variant | Papers |
|---|---|
| `NIAN · Part I · Foundations (Pāli)` | P01–P03 en/zh |
| `NIAN · Part II · The Earliest Chinese Reception` | P05 en/zh |
| `四行門卷一《念——從阿含隨念到華嚴念佛》` | P04 zh, P06–P19 zh |
| `MISSING` (field absent) | P04 en, P06–P08 en |
| `Four Practice Gates, Volume 1 — Mindful of the Buddha: From…` (full English) | P09–P29 en |
| `四行門卷一《念》—— 從早期佛教隨念到華嚴願景` | P20 zh |
| `四行門卷一《念》—— 從早期佛教隨念到華嚴念佛` | P21 zh |
| `NIAN — Mindful of the Buddha` | P22–P24 zh |
| `《念》Part VII《華嚴普賢之願》第一篇` | P25 zh |
| `《念》Part VII《華嚴普賢之願》第二篇` | P26 zh |
| `NIAN` | P27–P31 en/zh (various) |

**Total distinct `series:` variants: at least 11.** EN and ZH files for the same paper frequently disagree.

### O-2 Author-Metadata Block and Chinese-Subtitle-Line Presence

| Paper | EN has author block | EN has `*中文主題：*` | subtitle colon style |
|---|---|---|---|
| P01 | False | False | absent |
| P02 | False | False | absent |
| P03 | False | False | absent |
| P04 | False | False | absent |
| P05 | False | False | absent |
| P06 | False | False | absent |
| P07 | False | False | absent |
| P08 | False | False | absent |
| P09 | True | True | fullwidth |
| P10 | True | True | fullwidth |
| P11 | True | True | fullwidth |
| P12 | True | True | fullwidth |
| P13 | True | True | fullwidth |
| P14 | True | True | fullwidth |
| P15 | True | True | fullwidth |
| P16 | True | True | fullwidth |
| P17 | True | True | fullwidth |
| P18 | True | True | fullwidth |
| P19 | True | True | fullwidth |
| P20 | True | True | fullwidth |
| P21 | True | True | fullwidth |
| P22 | True | True | halfwidth |
| P23 | True | True | fullwidth |
| P24 | True | True | halfwidth |
| P25 | True | True | halfwidth |
| P26 | True | True | fullwidth |
| P27 | True | True | fullwidth |
| P28 | True | True | fullwidth |
| P29 | True | True | fullwidth |
| P30 | True | False | absent |
| P31 | True | False | absent |

**Summary:** EN P01–P08 have no `**Author:** … **Date:** …` block. EN P09–P31 all have it (23/31 EN). ZH files were not checked for author block as it appears to be EN-specific. All 23 EN papers with author block also have `*中文主題：…*` line, except P30 and P31.

**Subtitle colon style (EN files with `*中文主題*` line):** fullwidth `：` — 18 papers; halfwidth `:` — 3 papers (P22, P24, P25).

#### O-2b: Abstract Style

| Paper | EN abstract style | ZH abstract style | EN has `## 摘要`? |
|---|---|---|---|
| P01 | bold_inline | h2_heading | False |
| P02 | bold_inline | h2_heading | False |
| P03 | bold_inline | h2_heading | False |
| P04 | h2_heading | h2_heading | True |
| P05 | bold_inline | h2_heading | False |
| P06 | h2_heading | h2_heading | True |
| P07 | h2_heading | h2_heading | True |
| P08 | h2_heading | h2_heading | True |
| P09 | h2_heading | h2_heading | True |
| P10 | h2_heading | h2_heading | True |
| P11 | h2_heading | h2_heading | True |
| P12 | h2_heading | h2_heading | True |
| P13 | h2_heading | h2_heading | True |
| P14 | h2_heading | h2_heading | True |
| P15 | h2_heading | h2_heading | False |
| P16 | h2_heading | h2_heading | True |
| P17 | h2_heading | h2_heading | False |
| P18 | h2_heading | h2_heading | False |
| P19 | h2_heading | h2_heading | False |
| P20 | h2_heading | h2_heading | False |
| P21 | h2_heading | h2_heading | False |
| P22 | h2_heading | h2_heading | False |
| P23 | h2_heading | h2_heading | False |
| P24 | h2_heading | h2_heading | False |
| P25 | h2_heading | h2_heading | False |
| P26 | h2_heading | h2_heading | False |
| P27 | h2_heading | h2_heading | False |
| P28 | h2_heading | h2_heading | False |
| P29 | h2_heading | h2_heading | False |
| P30 | h2_heading | h2_heading | True |
| P31 | h2_heading | h2_heading | True |

**Summary:** ZH files uniformly use `## 摘要` (h2_heading, 31/31). EN files: `bold_inline` (**Abstract**) in P01–P03, P05; `h2_heading` (`## Abstract`) in P04, P06–P31. 13 EN files also have `## 摘要` as a bilingual second heading.

### O-3 Body-Text Section Reference Style

| Paper | EN body_ref_style | EN roman_refs | EN arabic_refs | ZH body_ref_style | ZH roman_refs | ZH arabic_refs | Mismatch? |
|---|---|---|---|---|---|---|---|
| P01 | arabic | 0 | 2 | arabic | 0 | 1 | — |
| P02 | arabic | 0 | 9 | arabic | 0 | 9 | — |
| P03 | arabic | 0 | 40 | arabic | 0 | 35 | — |
| P04 | arabic | 0 | 30 | arabic | 0 | 29 | — |
| P05 | arabic | 0 | 29 | arabic | 0 | 26 | EN: roman headings, arabic body refs |
| P06 | mixed | 26 | 10 | arabic | 0 | 26 | EN: roman headings, mixed body refs |
| P07 | mixed | 14 | 15 | arabic | 0 | 15 | EN: roman headings, mixed body refs |
| P08 | mixed | 20 | 40 | arabic | 0 | 33 | EN: roman headings, mixed body refs |
| P09 | mixed | 29 | 60 | arabic | 0 | 60 | EN: roman headings, mixed body refs |
| P10 | mixed | 30 | 15 | mixed | 2 | 9 | EN: roman headings, mixed body refs |
| P11 | mixed | 9 | 34 | arabic | 0 | 34 | EN: roman headings, mixed body refs |
| P12 | mixed | 13 | 28 | mixed | 1 | 25 | EN: roman headings, mixed body refs |
| P13 | mixed | 17 | 48 | mixed | 1 | 27 | EN: roman headings, mixed body refs |
| P14 | mixed | 18 | 4 | arabic | 0 | 4 | EN: roman headings, mixed body refs |
| P15 | mixed | 18 | 18 | mixed | 1 | 11 | EN: roman headings, mixed body refs |
| P16 | mixed | 18 | 16 | mixed | 2 | 17 | EN: roman headings, mixed body refs |
| P17 | mixed | 38 | 48 | mixed | 13 | 47 | EN: roman headings, mixed body refs |
| P18 | mixed | 39 | 69 | arabic | 0 | 77 | EN: roman headings, mixed body refs |
| P19 | mixed | 11 | 29 | arabic | 0 | 35 | EN: roman headings, mixed body refs |
| P20 | mixed | 11 | 21 | mixed | 1 | 28 | EN: roman headings, mixed body refs |
| P21 | mixed | 26 | 49 | arabic | 0 | 53 | EN: roman headings, mixed body refs |
| P22 | mixed | 13 | 13 | arabic | 0 | 11 | EN: roman headings, mixed body refs |
| P23 | mixed | 46 | 2 | mixed | 4 | 2 | EN: roman headings, mixed body refs |
| P24 | mixed | 40 | 3 | arabic | 0 | 1 | EN: roman headings, mixed body refs |
| P25 | roman | 3 | 0 | none | 0 | 0 | — |
| P26 | roman | 17 | 0 | none | 0 | 0 | — |
| P27 | mixed | 34 | 3 | arabic | 0 | 3 | EN: roman headings, mixed body refs |
| P28 | roman | 37 | 0 | arabic | 0 | 19 | — |
| P29 | roman | 27 | 0 | arabic | 0 | 17 | — |
| P30 | mixed | 4 | 15 | arabic | 0 | 15 | EN: roman headings, mixed body refs |
| P31 | mixed | 41 | 13 | arabic | 0 | 13 | EN: roman headings, mixed body refs |

**Summary:** P01–P05 EN have all-Arabic body refs (`§1`, `§3.4`) consistent with Arabic headings. P06–P31 EN show extensive mixing: roman refs (`§I`, `§II`) coexist with arabic refs (`§3.1`, `§4.2`). This is the dominant pattern — 22 EN papers have `mixed` body refs. ZH files consistently show arabic body refs (`§一` not used; ZH refs use `§3.4` style), even when the ZH headings are `一、二、三…`.

**Notable pure-roman body-ref papers (EN):** P25, P26, P28, P29 — consistent with Roman heading style.

### O-4 EN ↔ ZH Heading Parity (H2 and H3 counts)

| Paper | EN H2 count | ZH H2 count | H2 match? | EN H3 count | ZH H3 count | H3 match? |
|---|---|---|---|---|---|---|
| P01 | 9 | 11 | **NO** | 13 | 13 | yes |
| P02 | 9 | 11 | **NO** | 10 | 10 | yes |
| P03 | 9 | 11 | **NO** | 17 | 17 | yes |
| P04 | 12 | 12 | yes | 12 | 12 | yes |
| P05 | 9 | 11 | **NO** | 11 | 11 | yes |
| P06 | 12 | 12 | yes | 12 | 10 | **NO** |
| P07 | 12 | 12 | yes | 14 | 14 | yes |
| P08 | 12 | 12 | yes | 19 | 19 | yes |
| P09 | 11 | 12 | **NO** | 18 | 18 | yes |
| P10 | 10 | 11 | **NO** | 17 | 17 | yes |
| P11 | 10 | 11 | **NO** | 23 | 23 | yes |
| P12 | 10 | 11 | **NO** | 21 | 21 | yes |
| P13 | 10 | 11 | **NO** | 23 | 23 | yes |
| P14 | 10 | 11 | **NO** | 21 | 21 | yes |
| P15 | 9 | 11 | **NO** | 18 | 18 | yes |
| P16 | 10 | 10 | yes | 20 | 20 | yes |
| P17 | 9 | 11 | **NO** | 23 | 23 | yes |
| P18 | 9 | 10 | **NO** | 24 | 24 | yes |
| P19 | 10 | 12 | **NO** | 26 | 26 | yes |
| P20 | 10 | 10 | yes | 14 | 16 | **NO** |
| P21 | 10 | 10 | yes | 21 | 21 | yes |
| P22 | 10 | 11 | **NO** | 11 | 10 | **NO** |
| P23 | 10 | 11 | **NO** | 13 | 13 | yes |
| P24 | 10 | 9 | **NO** | 14 | 4 | **NO** |
| P25 | 9 | 10 | **NO** | 15 | 12 | **NO** |
| P26 | 9 | 10 | **NO** | 10 | 7 | **NO** |
| P27 | 9 | 9 | yes | 11 | 11 | yes |
| P28 | 9 | 9 | yes | 15 | 9 | **NO** |
| P29 | 10 | 11 | **NO** | 16 | 12 | **NO** |
| P30 | 12 | 11 | **NO** | 9 | 9 | yes |
| P31 | 12 | 11 | **NO** | 0 | 0 | yes |

**Summary:** H2 count differs in 22 papers: P01, P02, P03, P05, P09, P10, P11, P12, P13, P14, P15, P17, P18, P19, P22, P23, P24, P25, P26, P29, P30, P31. H3 count differs in 8 papers: P06, P20, P22, P24, P25, P26, P28, P29. The H2 differences are structural (ZH includes `Abstract` and bilingual `Keywords` headings that EN sometimes omits, or vice versa), not content divergence. H3 mismatches in P24, P25, P26, P28, P29 are more significant — warrant Chat Opus review.

---

## Section 7 — Action-Items Worksheet

> **Protocol:** Candidate canonical conventions listed with occurrence counts only.
> The 'what to change to' decision is reserved for Chat Opus + Max. No edits proposed here.

### D-1 Section Style

| Candidate | Count (EN papers) | Notes |
|---|---|---|
| Roman top-level (`## I.`, `## II.`, …) | 27/31 | Dominant pattern; P05–P31 |
| Arabic top-level (`## 1.`, `## 2.`, …) | 4/31 | P01–P04 only |
| ZH Chinese-numeral top-level (`## 一、`) | 31/31 | Consistent across all ZH; not a candidate for change — language-appropriate |

**Remediation scope if Roman chosen as canonical:** 4 EN papers (P01–P04) + 4 ZH papers (P04 uses bilingual headings which may warrant review).

### D-2 Full-Width Punctuation in EN Files

| Sub-type | Estimated papers affected | Notes |
|---|---|---|
| Full-width parens around transliterations: `（迦葉摩騰）` | ~20 papers | Convert to half-width `(…)` |
| Full-width CJK quotes in EN prose: `「他力」` | ~5 papers (P20, P21 dominant) | Decision needed: keep as Chinese citations, or convert to English quotes |
| Mixed-paren: `（…)` opening full-width, `)` closing half-width | Confirmed P05, possibly others | Convert both to half-width |
| Full-width comma `，` inside EN sentence | Confirmed P05 | Convert to `,` |
| Full-width period `。` at end of EN sentence | Rare | Convert to `.` |

**28/31 EN papers contain at least one FW-punct hit. P23 and P25 are the only completely clean EN papers.**

### D-3 Footer

| Candidate footer form | EN count | ZH count | Notes |
|---|---|---|---|
| `B_short_bilingual`: `*NIAN-P## · 釋慧鏡 (Shi Huijing) · YYYY-MM-DD*` | 5 EN | 4 ZH | Brief-identified canonical candidate |
| `C_short_zh`: `*NIAN-P## · 釋慧鏡 · YYYY-MM-DD*` | 1 EN | 4 ZH | ZH-files alternative |
| `A_short_en`: `*NIAN-P## · Shi Huijing · YYYY-MM-DD*` | 2 EN | 0 ZH | No Chinese name |
| `D_long_copyright` | 3 EN | 11 ZH | P09, P30, P31 EN; P09, P22–P31 ZH |
| `other_italic` (CBETA notice) | 7 EN | 7 ZH | P12–P18; no NIAN-P## identifier |
| `other` (bare GitHub URL / bold Repo block) | 13 EN | 5 ZH | P10–P11, P19–P29 EN |

**If a unified canonical form is adopted:** 20 EN papers and 23 ZH papers currently do not match the `B_short_bilingual` pattern.

**P30 and P31 orphan/pre-footer tokens:** The `D_long_copyright` footer for P30/P31 (Coda papers) may be intentional as series-closer markers. Chat Opus ruling needed on whether these retain special treatment.

### D-4 References Section

| Dimension | Candidate canonical | Count matching | Papers diverging |
|---|---|---|---|
| Top heading (EN) | `## References` | 26/31 | P05, P15, P17, P29 (`Bibliography`); P31 (`none`) |
| Top heading (ZH) | `## 參考文獻` | 25/31 | P24–P28 `(none)`; P31 `(none)` |
| Sub-headings (EN, 3-part Roman) | `### I. Primary Buddhist Sources` / `### II. Modern Scholarship` / `### III. Sūtra & Śāstra Index` | ~9 papers (P02–P03, P05–P09, P19–P22, P30) | ~21 papers use 5-part, 2-part, or no-numeral variants |
| Sub-headings (EN, 5-part Roman) | Adds `### II. Patriarchal Commentaries` and `### IV. Cross-Reference` | ~8 papers (P10–P18) | — |
| Sub-headings (EN, 2-part flat) | `### Primary Sources` / `### Secondary Scholarship` | 7 papers (P23–P29) | — |
| Cross-reference index location | Inside References (as `### IV` sub-heading) | ~14 papers | `separate_section` (P06–P09, P19–P22 — appear in both locations) |
| Index sub-heading name | `Sūtra & Śāstra Index` | ~9 papers | `Index of Sūtras and Śāstras` (P05, P17), `Canonical Index` (P13–P14) |

---

## Section 8 — Files-of-Concern Quick List

> Papers exhibiting 4 or more distinct drift categories (D-1 through D-4 + O-1 scope).

| Paper | Drift category count | Drift categories |
|---|---|---|
| P03 | **4** | D1_arabic_section_style; D2_fw_hits(39); D3_en_footer_non_B(A_short_en); O1_yaml_date_issue |
| P04 | **4** | D1_arabic_section_style; D2_fw_hits(13); O1_yaml_paper_id; O1_yaml_date_issue |
| P05 | **4** | D2_fw_major(>50 hits); D3_en_footer_non_B(C_short_zh); D4_en_bibliography; O1_yaml_date_issue |
| P24 | **4** | D2_fw_hits(8); D3_en_footer_non_B(other); D4_zh_no_ref_heading; O1_yaml_date_issue |
| P26 | **5** | D2_fw_hits(2); D3_en_footer_non_B(other); D4_zh_no_ref_heading; O1_yaml_paper_id; O1_yaml_date_issue |
| P27 | **5** | D2_fw_hits(2); D3_en_footer_non_B(other); D4_zh_no_ref_heading; O1_yaml_paper_id; O1_yaml_date_issue |
| P28 | **5** | D2_fw_hits(2); D3_en_footer_non_B(other); D4_zh_no_ref_heading; O1_yaml_paper_id; O1_yaml_date_issue |
| P29 | **5** | D2_fw_hits(9); D3_en_footer_non_B(other); D4_en_bibliography; O1_yaml_paper_id; O1_yaml_date_issue |
| P31 | **4** | D2_fw_hits(3); D3_en_footer_non_B(D_long_copyright); D4_zh_no_ref_heading; O1_yaml_date_issue |

---

## Section 9 — Unanticipated Anomalies

> Items not covered by the brief's 4 main concerns, noted for Chat Opus ruling.

1. **`paper_id` separator inconsistency:** P25–P29 and P31 ZH use `NIAN_P##` (underscore) instead of `NIAN-P##` (hyphen). Affects 10 files.

2. **EN YAML parse failure in P04, P06, P07, P08 (superseded by Anomaly #9):** Initial analysis suggested these files had missing YAML; post-verification shows the YAML is present but uses `series: *Mindful of the Buddha*…` with bare asterisks, causing pyyaml's alias resolver to raise `ComposerError`. All four files have well-formed `paper_id:` and `date:` values that are not accessible without a lenient parser. See Anomaly #9 for full details.

3. **P31 pre-footer coda-marker block:** `§ 8.2 — NIAN Part VIII Coda Closer · NIAN 31/31 ✅ …` sits between two `---` horizontal-rule separators, above the actual `*This paper is…*` copyright footer. This pattern is absent from all other papers. Brief classified it as `E_coda_marker` variant — needs Chat Opus ruling on whether it's a body element or footer variant.

4. **P30 orphan `8.1` token:** The bare token `8.1` appears as the very last line of P30 EN and ZH files (after the footer). Identical to what the brief predicted. Likely a build artifact — the paper is part §8.1 of the coda structure.

5. **Two `other_italic` footer sub-types in P12–P18:** EN files use CBETA verification notices, ZH files use CBETA 校對 notices — both italic, but neither contains the NIAN-P## identifier or date that would anchor them as proper attribution footers. These are functionally CBETA collation disclosures, not publication attribution lines.

6. **ZH files P24–P28 missing `## 參考文獻` heading entirely.** These papers (Part VII, P25–P29) appear to have folded references into the body or omitted them. P31 EN also has no `## References` section (coda paper).

7. **ZH `series:` field has at least 11 distinct variants** — far more than the 4 the brief anticipated. EN `series:` is more consistent (mainly the full English title for P09–P29) but still drifts at both ends (P01–P03 and P30–P31).

8. **`version:` field absent from all P01–P08 en/zh.** The field appears beginning P09 EN; ZH files lag further — P17–P18 zh are the earliest ZH with it.

9. **P04 EN / P06–P08 EN: YAML parse failure (bare-asterisk YAML alias).** These four EN files have `series: *Mindful of the Buddha*…` in their YAML front-matter. The bare asterisk `*` triggers `pyyaml`'s alias resolver, causing a `ComposerError: found undefined alias 'Mindful'`. The audit's `except: return {}` fallback silently returned empty dict, causing `paper_id`, `date`, and `series` to appear as MISSING in the manifest. **Actual field values (extracted via raw text):** `paper_id: NIAN-P04/P06/P07/P08`, `date: 2026-04-15/16/17/17`, `series: *Mindful of the Buddha*, Volume I of *The Four Practice Gates*`. The YAML `series:` value with unquoted asterisks is invalid YAML and will break any standard YAML parser — this is a genuine YAML format defect requiring remediation (wrap value in quotes). The manifest table rows for P04–P08 EN should be read with this caveat: their `yaml_*` columns show MISSING due to parse failure, not absent fields.

10. **O-3 body-ref style mismatch pattern:** 22/31 EN papers use `mixed` body refs (both `§I` and `§3.4` in same paper). This is the majority pattern, not an outlier. The `mixed` condition arises because: (a) Roman section refs (`§I`, `§II`) coexist with Arabic sub-section refs (`§3.1`, `§3.4`). If sub-section refs are excluded from the Roman/Arabic classification, the body-ref style would be `roman` for all P05+ papers. This nuance should be weighed before treating `mixed` as a defect.

---

*NIAN Format Audit 2026Q2 · Read-only · 62 files (31 en + 31 zh) · git commit `31b09cf` · Code Sonnet 4.6 · 2026-05-04*