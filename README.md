# Thesis, part 2

Continues the thesis "Understanding or Co-occurrence? Investigating Scene
Semantics and Reasoning in VLMs". Part 1 (`~/Desktop/Thesis`, GitHub
`gteodoro1/GistVsCoOccurrence`) built the co-occurrence lists and is closed.

## Input from part 1

`data/input/` holds a copy of part 1's final lists, taken unchanged from
`Thesis/data/results/` at commit `bdd3662` (full Qwen3 run of 2026-10-02, rules
version 4). `SHA256SUMS` lists their checksums.

| File | Content |
|---|---|
| `final.json` / `final.csv` | Up to 10 anchors for each of the 679 SUN2012 object types, all anchors |
| `final_no_background.json` / `.csv` | The same lists without 44 background types (sky, ground, walls...) |
| `vocab.txt` | The 679 object types |

Which of the two versions is used is still open. The field descriptions are in
part 1's README.
