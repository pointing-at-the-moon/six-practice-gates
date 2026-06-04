# BOOK_BUILD_PLAN.md
## 六行門 Six Practice Gates — 成書階段計畫（book-phase plan of record）
### v0.1 · 2026-06-04 · 釋慧鏡（Shi Huijing）· Chat Opus 草擬

> 本檔為**成書階段**（paper-phase 封卷之後的 book-phase）之計畫總綱，與 `PROJECT_MASTER_PLAN.md`（架構總綱）、各 `{GATE}_PLAN.md`（卷之論文階段骨架）並列，專管「論文如何裝訂成書」。
> 架構、序列、心經對應、genre 分流等上位決定一律以 `PROJECT_MASTER_PLAN.md` 為準，本檔不重述、不改寫。
> 單一真實來源：**filesystem（各 gate README 之 sealed 狀態）為權威**，plan 之 snapshot 落後時以 disk 為準。

---

## 〇、本檔範圍

本檔只回答一個問題：**已封卷的論文，如何成書？**

它不決定論文寫什麼（那是 `{GATE}_PLAN.md`），不決定門的次第與心經對應（那是 `PROJECT_MASTER_PLAN.md §二/§四`）。它決定：裝訂法、降階法、卷層目錄結構、系列框架層、裝訂順序與閘門、Chat/Code 分工。

**前提事實（2026-06-04 · 以 disk / gate README 為準）**：念 NIAN 封卷 31/31；施 DĀNA 封卷 31/31；懺 KṢAMĀ 封卷 20/20；戒 SĪLA 封卷 30/30；定 SAMĀDHI 起草中（~28 ZH / 26 EN，未封）；願 PRAṆIDHĀNA Part I–IV（P01–P10）提前釋出，餘 gated on SAMĀDHI 封卷。**四卷可裝訂（NIAN/DĀNA/KṢAMĀ/SĪLA），二卷待封。**

---

## 一、兩種裝訂法（LOCKED · 八部曲 vs 六行門，刻意不同）

同一出版專案，**兩部語料用兩種裝訂律**。這不是不一致，是 genre 與 lifecycle 不同所要求的。

| | 八部曲 Octalogy（`dharma-research`）| 六行門 Six Gates（`six-practice-gates`，本 repo）|
|---|---|---|
| genre | 見 / 慧 · 學術論述（treatise stratum）| 行之研究 · practice-as-research |
| 狀態 | 已封、齊一、學術單元 | 逐卷封（四卷已封、二卷未封）|
| 裝訂法 | **平裝**：paper → chapter 一對一、一次過（91 → 91）| **兩層裝訂**：每卷 Part → chapter（兩級，Part 為承重之義理脊柱，非平鋪）|
| 卷與書 | 八系 = 八書部（series 即書部）| 每門一卷書（per-gate volume）|
| 語言 | ZH/EN 可並轡同書 | **ZH 與 EN 各為獨立成書**（兩本 standalone monograph，非雙語交陳）|
| 系列框架 | 不需 | **需**：系列框架層（總序 + 跨門橋樑）承載六門全對心經、懺＝空、願封筆之 meta-architecture |
| 裝訂時機 | 一次過（已封）| **逐卷於封卷時裝訂**（bound at volume-seal）|

**為什麼六行門不能照抄八部曲平裝**：八部曲無內部活層級、無後續起草擾動，平裝正確。六行門每卷有 Part 級義理脊柱（如 SĪLA Part VII 無相戒、DĀNA Part VIII 華嚴），平鋪成一串 chapter 會抹掉這條脊柱；且尚有未封之卷，照已封之法裝活卷，每落一篇就要重裝。

---

## 二、六行門裝訂規格（LOCKED）

1. **每門一卷書（per-gate volume）。** 六門 = 六卷（念/施/懺/戒/定/願）。
2. **兩級結構 Part → chapter。** 卷以 Part 分編，每篇論文降階為該 Part 之下的一章。Part 名即書中之編/部名，承重不可壓平。
3. **ZH 與 EN 各為獨立成書。** 兩本各自 standalone：中文卷面向無英文背景之全球華語讀者，英文卷面向西方學術讀者。**不交陳、不互為譯本**——二者是各自獨立的學術改寫（沿論文階段之雙軌律）。
4. **逐卷於封卷時裝訂。** 卷封即可裝；未封之卷不裝（防反覆重裝）。
5. **系列框架層在卷之上。** 六卷共處一層系列框架（§七）——此層承載「六門即一」之 grand arc。

---

## 三、呈現原則：因陀羅網 / 一總九別（從 S8-P11 繼承）

「如何呈現六扇各自可獨立修習、卻又是一的門？」此問題**已由作者在八部曲 S8-P11（華嚴十玄門 × 普賢十大願王）解決**，六行門直接繼承其解。

- **錯誤圖象（多元論）**：六門各自通向同一個無我——把門當作六條會合於一點的路。
- **正確圖象（華嚴）**：**一法（無我 / 般若 / 法界）即其六門**，且**每一門已含其餘五門**。如 S8-P11：禮敬諸佛不是「通向」其餘九願，而是「含攝」其餘九願；同時具足相應門為總，而每一別門亦各具十門。
- **正圖 = 因陀羅網**：每一門是反映其餘一切門的一顆寶珠。入懺，則念施戒定願已在其中。此即「何以任一門皆能通向無我」——不因一門是一條足夠的偏路，而因**它就是整張網從一個結點看出去的全貌**。

**對成書之後果**：你不是呈現六扇門。你呈現的是**一法、六遍、遍遍俱足**。系列框架層（§七）與各卷導論（§六）都要說這件事，而非把六卷當六個獨立主題並列。

---

## 四、降階法 paper → chapter（demotion）

成書不是重寫論文 prose。降階＝把已封之論文編進書的章位，**信任已完成的思想**。

**降階要做的**：
- 移除各篇之 YAML frontmatter、單篇 abstract / 關鍵詞、單篇 footer（CC/CBETA/GitHub 三行）——這些是 paper-unit 元件，書層另設。
- 章次重編（卷內連續編號），保留 Part 歸屬。
- 腳註、參考文獻、經論索引（T-number index）、名相對照 glossary **彙整至書末 back-matter**（不再逐篇各帶一份）。
- 補**連續性橋樑**：論文是離散節點，書是連續路徑；Part 與 Part 之間、章與章之間補敘事連接（此為 Chat 之設計工作，見 §九）。
- 各 Part 加**部前導言**（Part introduction）：說明該 Part 在全卷論證中的位置。
- 全卷加**導論**＝grand arc（見 §六）。

**降階不做的**：不重寫論文核心論證、不新增新義理（新義理走新論文）、不改動關鍵框架。

**反律藏防火牆等義理鎖一律隨章遷入，不因成書而鬆動。**

---

## 五、context-bounded 成書法（spine method · 解決「上下文有限」之核心）

> 問題：一卷 31 篇（× 雙語 = 62 檔），Chat 無法將全部原文讀進上下文做結構判斷。
> 解：**不讀原文做書級判斷——讀 spine。**

每篇論文已帶可機械萃取之結構層：YAML（paper_id / part / part_number / volume / series）+ 壓縮 abstract + ≥10 關鍵詞 + 腳註/T-number apparatus（皆由 `scripts/paper_audit.py` 既有產出）。

- **Code Opus** 萃取全卷每篇之 `YAML + abstract + 關鍵詞 + T-index + cross-refs` → 成單檔 `{GATE}_BOOK_SPINE.md`（純萃取，不再生，**零 CJK drift 風險**）。spine 每列＝paper_id · Part · ZH/EN 章題 · abstract · 關鍵詞 · 引用 T-numbers · cross-refs。
- **Chat Opus** 只讀此 spine + 既有 Part 級框架。spine 可入上下文；Chat 據此做書級判斷：章序、部前導言、章間橋樑、跨篇論證去重、前後 matter 規劃、grand arc 撰寫。

**關鍵 reframe**：書的承重工作是**接縫（連續性 + 框架 + apparatus）**，不是 chapter bodies。接縫小、可整體握於上下文；bodies 大、但不重判。故上下文有限非阻礙。

---

## 六、卷層目錄結構（per-gate book layout · NIAN 為樣板）

每門 `{gate}/book/` 之下：

```
{gate}/book/
├── README.md                 # 本卷成書狀態 + 裝訂律摘要 + 指向 /BOOK_BUILD_PLAN.md
├── {GATE}_BOOK_SPINE.md      # Code 萃取之 spine（§五）——book-build 第一步產出
├── zh/                       # 中文卷（standalone monograph）
│   ├── 00_導論_grand-arc.md  # 全卷導論 = grand arc（框架全論證、點名各 Part）
│   ├── front-matter/         # 書名頁、版權頁、目次（build 時生）
│   ├── parts/                # part1..partN/ 各 Part 之 chapter 家（降階後落位）
│   └── back-matter/          # 名相對照 · 經論索引(T-index) · 參考文獻 · 跨門橋樑指引
└── en/                       # English volume（standalone monograph · 鏡像 zh/）
    ├── 00_introduction_grand-arc.md
    ├── front-matter/
    ├── parts/
    └── back-matter/
```

中英**各自一棵樹**，呼應「ZH/EN 各為獨立成書」。本輪只立骨架（dir + .gitkeep + README + spine 佔位），實 content 於 build 階段逐 Part 生成。

---

## 七、系列框架層（series framing layer · the grand arc, scaled up）

六卷之上需一層共享框架，承載「六門即一」之 meta-architecture（六門全對心經 · 懺＝空 · 願封筆）。其成份：

- **六行門總序**（series preface）：一法六遍之開示；六門全對心經之招牌論證（五動＋一空）；願為封筆之說明。
- **跨門橋樑**（cross-gate bridges）：因陀羅網式互攝索引——入一門見其餘五門之指引。

**位置（結構決定 · 待 Max 定）**：建議於 repo root 立 `book/`（或 `series-book/`）為系列書層之家，與各 `{gate}/book/` 並列、在其上。⚠ 此為結構性決定，本輪**不創建**，列為待決項；各卷導論（§六，卷級）與系列總序（系列級）分屬兩層，不可混。

---

## 八、裝訂順序與閘門

- **可裝訂 now**：念 NIAN · 施 DĀNA · 懺 KṢAMĀ · 戒 SĪLA（四卷皆已封）。
- **待封**：定 SAMĀDHI（起草中）· 願 PRAṆIDHĀNA（Part I–IV 提前釋出，餘 gated on SAMĀDHI 封卷）。
- **裝訂 = 兩階段**（per `{GATE}_PLAN.md` 既定）：(1) spine 萃取 →（2) 降階落位 + 接縫撰寫。系列框架層俟多卷成書後再立（願封筆時 grand reveal 完整）。
- **試裝卷 = NIAN**（§十）：以最成熟、最書形（一論證、一作者、循序可讀）之卷驗整套法，再推及他卷。

---

## 九、分工（沿 PROJECT 雙-Claude 律）

| 工作 | 執行端 |
|------|--------|
| spine 萃取（YAML+abstract+關鍵詞+T-index+cross-refs → `{GATE}_BOOK_SPINE.md`）| **Code Opus**（機械、deterministic）|
| 讀 spine、定章序、撰 grand arc / 部前導言 / 章間橋樑、跨篇去重、前後 matter 規劃 | **Chat Opus**（設計，讀 spine 不讀 raw bodies）|
| 降階機械落位（移 YAML/abstract/footer、彙整腳註/參考/索引/glossary 至 back-matter、章次重編）| **Code Opus** |
| 目錄 scaffold、.gitkeep、git commit/push、staged-set 驗證 | **Code Opus** |
| 最終編輯、結構、義理裁決 | **Max** |

紀律沿用：單篇 CJK 一律 single-shot `create_file`（不對中文 iterative str_replace）；無 `git add -A`，push 前驗 staged set；commit 不附 `Co-Authored-By`；CJK ghost-UTF 顯示 bug 以 Code hexdump 為 ground truth，Chat 不據顯示重生罕用字。

---

## 十、NIAN 試裝（本輪：scaffolding only）

念 NIAN 已封 31/31、8 Parts，為試裝卷。本輪只在 `nian/book/` 立骨架（見隨附 `nian/book/README.md` + 空樹），**不做降階、不生 chapter content**。

NIAN 書形（my rec · Hybrid C 之書面對應）：卷-landing 導論（grand arc，框架 31 篇之一論證、點名 8 Parts）+ Part 分組之目次 + 篇即章之 detail。讓 P31《念佛的內部步驟 / What You Just Walked Through》真正擔起其「全卷回顧」之職——讀者落於卷導論即見 P31 所收束之論證弧。

**下一步（非本輪）**：Code 萃取 `nian/book/NIAN_BOOK_SPINE.md` → Chat 讀 spine 起草 grand arc 導論 + 8 部前導言。

---

## 版本紀錄

- **v0.1 (2026-06-04)** — Chat Opus 初版。封存裝訂二律（八部曲平裝 vs 六行門兩層）、ZH/EN 各為獨立成書、因陀羅網呈現原則（繼承 S8-P11）、降階法、spine context-bounded 成書法、卷層目錄結構、系列框架層（位置待 Max 定）、裝訂順序與閘門、雙-Claude 分工、NIAN 試裝。源於 2026-05-04「NIAN 呈現」與 2026-06-03「fact-check」二次對話之結論。
