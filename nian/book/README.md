# 念 NIAN — Book Phase（成書階段）

> **狀態：** 論文階段封卷 31/31（8 Parts，2026-05-03）｜成書階段 = **骨架已立，未降階**（scaffolding only，2026-06-04）
> **裝訂律：** 見 repo root `/BOOK_BUILD_PLAN.md`（六行門兩層裝訂：Part → chapter；ZH/EN 各為獨立成書；逐卷於封卷時裝訂）。
> **試裝卷：** NIAN 為六行門成書法之試裝卷（最成熟、最書形）。

## 卷形（NIAN book-shape · Hybrid C）

卷-landing 導論（grand arc）＋ Part 分組目次 ＋ 篇即章 detail。導論框架 31 篇之單一論證弧、點名 8 Parts，使 P31 全卷回顧得以收束其弧。

## 8 Parts → chapters（章＝該 Part 內之論文，spine 萃取後定章序/章題）

| Part | 名 | 論文 |
|------|----|------|
| 一 | 巴利根基 Foundations (Pāli) | P01–P04 |
| 二 | 最早期漢譯 Earliest Chinese | P05 |
| 三 | 初期大乘 Early Mahāyāna | P06–P08 |
| 四 | 淨土三經 Three Pure Land Sūtras | P09–P11 |
| 五 | 大乘大經 Great Mahāyāna | P12–P19 |
| 六 | 兩條流 Two Streams（淨土／禪／天台橋樑）| P20–P24 |
| 七 | 華嚴 Flower Ornament（普賢十大願）| P25–P29 |
| 八 | 尾聲 Coda | P30–P31 |

## 目錄結構

```
nian/book/
├── README.md                 # 本檔
├── NIAN_BOOK_SPINE.md        # Code 萃取之 spine（下一步產出 · 現為佔位）
├── zh/  { 00_導論_grand-arc.md · front-matter/ · parts/ · back-matter/ }
└── en/  { 00_introduction_grand-arc.md · front-matter/ · parts/ · back-matter/ }
```

## 下一步（非本輪）

1. **Code**：萃取 `NIAN_BOOK_SPINE.md`（每篇 YAML + abstract + 關鍵詞 + T-index + cross-refs）。
2. **Chat**：讀 spine（不讀 raw bodies）→ 起草 zh/en grand-arc 導論 + 8 部前導言 + 章間橋樑。
3. **Code**：降階機械落位（移單篇 YAML/abstract/footer、腳註與參考與經論索引與名相對照彙整至 back-matter、章次重編）。
