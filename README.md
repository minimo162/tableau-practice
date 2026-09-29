# tableau-practice

Tableau の練習用リポジトリ。

## 手順書

**[Superstore で「売上分析ダッシュボード」を作る](https://minimo162.github.io/tableau-practice/)**（GitHub Pages）

実際の画面操作のスクリーンショット付き。月別売上推移＋予測 / サブカテゴリ別 売上と利益 / 都道府県別 利益マップ / 計算フィールド / ダッシュボード。ソースは [docs/index.html](docs/index.html)。

## 構成

- `docs/` — 手順書（HTML）とスクリーンショット（`docs/images/`）。GitHub Pages の公開元
- `workbooks/` — Tableau ワークブック（`.twb`）

## ワークブックを開くには

`workbooks/superstore-sales-dashboard.twb` は Tableau Desktop 付属のサンプルデータ「サンプル - スーパーストア」を使っています。データそのものはリポジトリに含めていません。

1. Tableau Desktop でワークブックを開く
2. 「参照ファイル…が見つかりませんでした。別のファイルと置換しますか？」と表示されたら「**はい**」を選ぶ
3. 「サンプル - スーパーストア.xlsx」を指定する（通常は `ドキュメント\マイ Tableau リポジトリ\データ ソース\<バージョン>\ja_JP-Japan\` にあります）

## メモ

- `.twbx` はバイナリのため差分が見にくい。バージョン管理したい場合は `.twb`（XML）で保存すると差分を追いやすい。
- `.twb` にはデータファイルの保存場所（パス）が入る。公開前に、パス中のユーザー名を `C:/Users/USERNAME/` に置換している（このリポジトリのワークブックも置換済み）。
