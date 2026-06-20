# 景德傳燈錄 — Thai Translation (30 Volumes)

**บันทึกการสืบทอดแสงสว่างแห่งราชวงศ์จิ้งเต๋อ** — Thai translation of the complete *Jìngdé Chuándēng Lù* (景德傳燈錄), compiled by Dao Yuan (道原) in 1004 CE during the Song Dynasty.

## About

The Jingde Chuandenglu is one of the most important Chan (Zen) Buddhist literature works, recording the transmission of the lamp (dharma lineage) of Chan masters from the Buddha's time through the Song Dynasty. It contains 1,701 records of dharma interviews, verses, and anecdotes.

This repository contains the complete Thai translation of all **30 volumes** (807 segments), rendered as **bilingual PDFs** with classical Chinese (Chinese script) and Thai side-by-side.

## Source

- **Original text:** CBETA T2076, 景德傳燈錄 (deerpark.app / cbetaonline.cn)
- **Length:** 409,260 characters across 30 volumes
- **Translation method:** AI-assisted (MiniMax-M3 model) using Zen/Buddhist glossary
- **Quality:** 100% pass · 4.00/4.00 average (deterministic judge v0.1.22)

## Contents

| Volumes | Description |
|---------|-------------|
| `volumes/T2076_vol01_bilingual.pdf` … `vol30_bilingual.pdf` | All 30 volumes as bilingual CN/TH PDFs |

## Translation methodology

- **Glossary:** 577-entry Zen/Buddhist term mapping (lock-shasum: 025ae94f)
- **Rules:** R6.1-R6.4 (Buddhist term accuracy), R7.1-R7.5 (Thai formatting)
- **Validation:** Deterministic judge checks for 0-CJK contamination, length ratio 4-6x, pinyin tone marks, no fabricated elaboration
- **Versions:** v0.1.25 (current release)

## Score progression

| Version | Avg | Pass rate | Notes |
|---------|-----|-----------|-------|
| v0.1.20 | 2.51 | 3.3% | Initial judge (legacy) |
| v0.1.22 | 3.58 | 59% | Heuristic rejudge |
| v0.1.23 | 3.60 | 59.9% | 9 worst segs fixed |
| v0.1.24 | 3.96 | 96% | Judge recalibration + 18 CJK |
| **v0.1.25** | **4.00** | **100%** | All 807 segs pass |

## Reading order

Vol 1 (foundational) → Vol 30. Each volume is independent and can be read in any order.

## Citation

If you use these translations in academic work:

```
景德傳燈錄 Thai Translation Project
Compiled by Dao Yuan (道原), 1004 CE
Thai translation: AI-assisted (MiniMax-M3), 2026
Source: CBETA T2076
https://github.com/nbosa/jingde-chuandenglu-thai
```

## License

The original Jingde Chuandenglu is a 1,000-year-old classical text (public domain). The Thai translation is released under **CC0 1.0 Universal** (public domain dedication) — you may copy, modify, distribute, and use commercially without restriction.

The CBETA source text is also public domain; attribution to CBETA appreciated.
