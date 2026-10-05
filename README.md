# 二代目ととのえ親方 — 配布用

Chrome 拡張機能「二代目ととのえ親方」（裁判所 mints に Mac から出すファイル名の濁点・半濁点を、送る前にととのえる）を
Google 管理コンソールから自動配布するための、**crx と update.xml を置くだけ**のリポジトリ。

ソースは `takeuchi-ace/mints-apl`（private）。更新手順はそちらの `README.md`「版を上げる・配る」を参照。ここを直接編集しない。

| | |
|---|---|
| 拡張ID | `lfpfppkcjdioedchpoealihdcgglkghj` |
| 管理コンソールに登録するURL | `https://raw.githubusercontent.com/takeuchi-ace/mints-nfcfix-hosting/main/update.xml` |

`update.xml` の `version` と `mints-nfcfix.crx` 内の manifest の `version` は必ず一致させる。
ずれていると更新が降りない（`tools/pack_crx.sh` が両方を一度に作る）。

**このリポジトリへの push が、そのまま全社への配信になる。**

事務所内で作った非公式の補助ツール。裁判所が配っているものではない。
