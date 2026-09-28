# 家2（新居マンション）

内見〜入居準備の記録置き場。家1（[homes/home1](../home1/README.md)）と同じ形式で残して比較できるようにします。

- 内見日：2026-10-03 前後（今週末）
- 所在地・物件名・部屋番号：（記入）

## フォルダ構成

| 場所 | 入れるもの |
|---|---|
| `property.yaml` | 物件情報（賃料/価格、管理費、築年、方角、契約条件など） |
| `data/viewing-measurements.yaml` | 内見で測った寸法・設備位置（記入テンプレ） |
| `data/delivery-route.yaml` | 搬入経路の寸法（記入テンプレ） |
| `data/furniture-candidates.yaml` | 購入候補の家具（構造化データ） |
| `data/room-scan.glb` | 3Dスキャン（Polycamで書き出し） |
| `furniture-candidates.md` | 家具候補の説明・確認ポイント |
| `analysis/` | スキャンから読み取った寸法（家1の `measurements.yaml` と同形式） |
| `outputs/` | 間取り図・レイアウト案 |
| `photos/` | 内見で撮った写真（`<部屋名>_<内容>.jpg` 推奨） |
| `assets/` | プレビュー画像など |

内見時の持ち物・撮影・計測リストは [`docs/viewing-checklist.md`](../../docs/viewing-checklist.md)。
