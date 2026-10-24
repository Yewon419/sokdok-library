# sokdok-library

Texts served to the 누빠읽 reading app (GitHub Pages).

- `library/index.json`: catalog. Every entry lists its `source` and `license`.
- `library/<id>.json`: one text, split into reading chunks.
- `search/`: sharded full-text index (format: `meta.json` + `<n>.bin`).

Only public-domain texts (author died before 1962 in Korea and expired in the US),
CC BY / BY-SA texts, KOGL type 1 texts, and statutes are included. CC BY-SA texts
remain under CC BY-SA; see each entry's `source` for attribution.
