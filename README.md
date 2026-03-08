# 2026-laptop-selection-log

2026年4月に購入予定の新規開発用ラップトップを選定するための比較・評価・検討記録です。

単なるスペック比較ではなく、`開発用途での快適さ` と `持ち運びやすさ` の両立を重視して記録します。

## このリポジトリで扱うこと

- 候補機種ごとのスペックと実用面を一貫した観点で比較する
- 候補ごとのメリット・懸念点を簡潔に残す
- 最終的な選定理由を後から追える状態にする

## 背景

現在のメイン端末は `Surface Laptop 4` です。主な不満は以下です。

- 端末がやや重い
- 画面がやや小さい
- Docker が遅い
- Flutter ビルドが遅い

次の開発用ラップトップの購入時期は `2026年4月` を想定しています。

## 現在の最有力候補

- `LG gram Pro 17`
- `LG gram Pro 16`
- 比較対象には他社の16〜17インチ帯や上位 `Panther Lake` 搭載機も含める

## 主な用途

- WSL を用いた Web 開発
- TypeScript / Next.js を中心とした開発
- Docker ベースの開発環境
- Flutter によるネイティブアプリ開発
- VS Code とブラウザを中心とした日常作業

## ファイル構成

```text
.
├── README.md
├── comparison.md
├── current-machine.md
└── candidates/
    ├── README.md
    ├── lg-gram-pro-16.md
    └── lg-gram-pro-17.md
```

## ファイルの役割

- `comparison.md`: 比較観点、比較表、記録方針、更新ルール
- `current-machine.md`: 現行機の詳細と比較のベース情報
- `candidates/`: 候補機種ごとの詳細メモ
