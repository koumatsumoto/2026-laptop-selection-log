# 比較メモ

## 比較のベース

現行マシンは `Surface Laptop 4` です。比較の基準として、まず以下を確定情報として残します。

- サイズ: `15インチ`
- CPU: `11th Gen Intel Core i7-1185G7`
- メモリ: `32GB`
- ディスプレイ: `2496 x 1664 / 150% 表示 / 実効 約 1664 x 1109`
- 重量: `1,542g`
- バッテリー基準: `軽い開発で 10 時間持てば十分`
- 不要要素: `タッチディスプレイ`

## 一次選定基準

### 必須条件

- `2026年発売予定モデル`
- `Panther Lake` 系 CPU
- `15インチ以上`
- `32GB以上`
- `512GB以上`
- `日本語キーボード配列`
- `タッチ非対応`
- `実効解像度が現行機より広い`

### 強く優先する条件

- `17インチ > 16インチ > 15インチ`
- `1.3kg台`
- `1,542g以下`
- Docker ビルド改善
- ストレージ体感改善
- 軽い開発で `10時間` 前後の実働

### 加点条件

- `64GB メモリ`
- `1TB SSD`
- SSD 拡張や換装のしやすさ

### 判定メモ

- `17インチ` で `1.55kg超` でも、他条件が強ければ許容する
- `国内正規販売で JIS 配列が選べないモデル` は除外する
- 解像度は物理値ではなく、`快適な表示倍率をかけた後の実効作業領域` で判断する

## 現在の整理

### 基準機

| 機種 | 画面サイズ | 重量 | CPU | メモリ | メモ |
| --- | --- | --- | --- | --- | --- |
| Surface Laptop 4 | 15 | 1,542g | Core i7-1185G7 | 32GB | 現在の比較基準。Docker ビルドとストレージ体感が弱い。 |

### 有力候補

| 機種 | 状態 | 理由 |
| --- | --- | --- |
| LG gram Pro 17 | 保留 | 17インチ最優先候補。ただし 2026 日本モデルの `Panther Lake / JIS / 非タッチ` 確認待ち。 |
| LG gram Pro 16 | 保留 | 軽さと画面サイズのバランス候補。ただし 2026 日本モデルの `Panther Lake / JIS / 非タッチ` 確認待ち。 |
| Acer Swift Edge 16 AI Intel | 調査継続 | Panther Lake 系、16インチ、超軽量。国内 SKU の `JIS / 32GB / 非タッチ` 確認待ち。 |

### 条件付き候補

| 機種 | 状態 | 主な理由 |
| --- | --- | --- |
| MSI Prestige 16 AI+ C3M | 条件付き候補 | Panther Lake 系、国内販売あり。約 `1.59kg` で重量条件だけ少し超える。 |
| Dell XPS 16 DA16260 | 条件付き候補 | Panther Lake 系、JIS / 非タッチ / 32GB / 1TB を確認しやすい。最小 `1.65kg` が重い。 |

### 保留または除外寄り

| 機種 | 状態 | 主な理由 |
| --- | --- | --- |
| ASUS Vivobook S16 S3607AA | 保留 | US 公式では条件が強いが、日本向け JIS SKU が未確認。 |
| Samsung Galaxy Book6 Pro 16 | 保留 | 国内 JIS 構成の確認が不足。 |
| Acer Swift 16 AI | 除外寄り | タッチ寄り構成が強く、非タッチ条件とぶつかる。 |
| Acer Swift Go 16 AI Intel | 除外 | Intel は Series 2 表記で、Panther Lake 必須条件から外れる。 |
| ROG Zephyrus G16 / MSI Stealth 系 | 除外寄り | dGPU 前提で重さ・価格・バッテリーの方向性がずれやすい。 |

## 次に確認すること

- `LG gram Pro 16 / 17` の 2026 日本モデルで `Panther Lake` と `JIS` が揃うか
- `Acer Swift Edge 16 AI Intel` の日本向け実売 SKU で `32GB` と `非タッチ` があるか
- `MSI Prestige 16 AI+ C3M` を重量超過込みで許容候補にするか
- `Dell XPS 16 DA16260` を重量超過込みで許容候補にするか

## 参考にした公式情報

- LG Japan press release, 2026-03-05  
  https://www.lg.com/jp/about-lg/press-and-media/20260305-lg-gram-pro-new-model/
- Acer Japan Swift Edge 14/16 AI Intel  
  https://www.acer.com/jp-ja/laptops/swift/swift-edge-14-16-ai-intel
- MSI Japan Prestige 16 AI+ C3M  
  https://jp.msi.com/Business-Productivity/Prestige-16-AI-Plus-C3MX
- MSI Japan launch news, 2026-03-05  
  https://jp.msi.com/news/detail/Prestige-16-AIplusC3MG-2601JP-148188
- Dell Japan XPS 16 DA16260  
  https://www.dell.com/ja-jp/shop/dell/xps-16-/spd/xps-da16260-laptop
- ASUS official tech specs, Vivobook S16 S3607AA  
  https://www.asus.com/us/laptops/for-home/vivobook/asus-vivobook-s16-s3607/techspec/
