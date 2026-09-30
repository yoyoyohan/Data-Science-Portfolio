# Yohan Deshpande — selected work

Short version of six repositories, written so a LinkedIn visit has somewhere to land.

**Live page:** https://yoyoyohan.github.io/Data-Science-Portfolio/

## Results up front

| Result | Where |
| --- | --- |
| **1st**, research paper · **14th** overall of 110+ teams | [LLM calibration audit](https://github.com/yoyoyohan/llm-calibration-audit) · NSRI Summer Research Hackathon 2026, with Akul Bajpai (The Mentalists) |
| **30th** of 199+ · score **0.83157** | [Handwritten to Data](https://github.com/yoyoyohan/handwritten-to-data) |
| **Live site** | [NJ high school ratings](https://sportsbusinessrankings.onrender.com) · [repo](https://github.com/yoyoyohan/sportsbusinessrankings) |

## The projects

### LLM calibration audit

Do verbally stated confidences get worse as questions get harder? 540 MMLU items, three difficulty tiers fixed before scoring, five trials, three API models, 8,100 parsed answers. Claude Haiku was nearly calibrated (accuracy 0.895, ECE 0.033). GPT-4o-mini and Gemini Flash-Lite were overconfident, and the gap widened from easy to hard.

### Handwritten to Data

Ukrainian mixed-document recognition. YOLOv8x finds the regions; TrOCR, Tesseract, pix2tex, and a table model transcribe them. Page character error is half the competition score. Finished 30th of 199+ at 0.83157.

### NJ high school ratings

Rankings, results, and rating history served from the spreadsheets coaches already maintain. The Drive folder is read-only. About 600,000 games land in Postgres, refreshed four times a day. [Open the site](https://sportsbusinessrankings.onrender.com).

### Ranking Studio

The graphics desk for those rankings. Paste a table, match New Jersey high school names to a crest library, adjust the poster through design tokens, export a PNG. [Repository](https://github.com/yoyoyohan/designtool).

### Football clip stats

YOLOv8 and ByteTrack, jersey colors, and a pitch homography turn a short broadcast clip into possession, passes, shots, shots on target, and goals. Built for 10–30 second clips. [Repository](https://github.com/yoyoyohan/football-clip-stats).

### Is it alpha or just exposure?

CAPM, Fama–French, and Carhart on daily excess returns, with Newey–West standard errors. Apple’s leftover is about 10.5% a year and is not distinguishable from zero. SPY’s alpha sits on zero with an R² of 0.99. [Repository](https://github.com/yoyoyohan/alpha-or-exposure).
