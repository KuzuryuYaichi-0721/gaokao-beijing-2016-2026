# Beijing Gaokao Questions 2016–2026

This repository contains **2,602 Beijing Gaokao / mock questions** from the
purchased Beijing paper compilation used by GaokaoCoach.

```text
questions.json   2,602 questions
manifest.json    counts + SHA-256
RIGHTS.md        rights-holder assertion
DATA_LICENSE.md  CC BY 4.0 for this compilation
MARKERS.md       underline/dot/wave markup
```

## Scope

- Beijing only
- Years 2016–2026
- 高考/一模/二模
- Tags: year, region, district, exam_type, exam_kind, mock_level, mock_no

## Quality

- 1,614 questions from the 2016–2020 purchased export
- 988 questions from the 2021–2026 OCR batch
- OCR rows are C-confidence and may contain recognition errors
- Some answers are empty because no reliable answer page was available; empty
  does not mean the answer is intentionally omitted

## Markers

Original paper formatting that plain text cannot show is encoded as:

```text
【画线】…【/画线】
【波浪线】…【/波浪线】
【加点】…【/加点】
```

If a mark could not be located in the text layer, `mark_note` records
`见原卷` instead of guessing.

## Excluded

This repository excludes:

- GAOKAO-Bench / GAOKAO-Bench-Updates
- Xiaohongshu items
- synthetic demo questions
- personal progress, PDFs, images, audio

## Rights

See `RIGHTS.md` and `DATA_LICENSE.md`. The repository owner asserts that the
underlying Beijing compilation was purchased with permission to redistribute
these question texts. If you are a rights holder and object, open an issue and
the disputed material will be removed.
