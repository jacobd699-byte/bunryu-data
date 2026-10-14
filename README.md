# Bunryu Data

This repository stores example-files and import-ready CSV files for [Bunryu](https://bunryu.netlify.app), a Japanese learning app that turns selected vocabulary into stories for reading and listening practice.

## CSV Format

Use UTF-8 CSV with these columns:

| Column | Description |
| --- | --- |
| `expression` | Japanese word or phrase |
| `reading` | Reading in kana |
| `meaning` | Translation or explanation |

```csv
expression,reading,meaning
猫,ねこ,cat
犬,いぬ,dog
```

[`testvocab.csv`](./testvocab.csv) is a small format example, not a complete vocabulary list.

## References

- [Open Anki JLPT Decks](https://github.com/jamsinclair/open-anki-jlpt-decks) — vocabulary lists for N1–N5.
- [Kaishi 1.5k](https://github.com/donkuri/kaishi) — a beginner-oriented Japanese Anki deck.

These are external resources; their data is not included here. Check their reuse terms before copying or redistributing data.