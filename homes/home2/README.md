# 家2（新居マンション）

内見〜入居準備の記録置き場。家1（[homes/home1](../home1/README.md)）と同じ形式で残して比較できるようにします。

- 内見日：2026-10-04（日）予定
- 公開repoには汎用テンプレートのみ。住所・物件名・部屋番号は記載不要です。

**公開前提の保存方針：** 以下の構成はprivate保存先で使う論理構成です。
写真・スキャン・実測値・間取りはこのGit checkout外のprivateフォルダに保存し、
公開テンプレートへ記入/commitしないでください。既存private repoまたはアクセス制限した
保存先へ第2コピーを作り、ファイルを開いて検証します。
`room-scan.glb`は過去の形式であり、今の端末/プランで取得できると断定しません。
GLTFの場合は全付属ファイルも保持。元captureと未編集写真を別途残します。

These paths describe a private data layout. Keep this public checkout's templates
blank; actual photos, scans, measurements and plans belong in private storage
outside the checkout. GLB availability must be tested; retain all GLTF sidecars
if GLTF is offered instead, alongside native captures and original photos.

## フォルダ構成

| 場所 | 入れるもの |
|---|---|
| `property.yaml` | 物件情報（賃料/価格、管理費、築年、方角、契約条件など） |
| `data/viewing-measurements.yaml` | 内見で測った寸法・設備位置（記入テンプレ） |
| `data/delivery-route.yaml` | 搬入経路の寸法（記入テンプレ） |
| `data/furniture-candidates.yaml` | 購入候補の家具（構造化データ） |
| `data/room-scan.glb` / GLTF一式 | private保存先のportable export（事前に取得可否を確認） |
| `furniture-candidates.md` | 家具候補の説明・確認ポイント |
| `analysis/` | スキャンから読み取った寸法（家1の `measurements.yaml` と同形式） |
| `outputs/` | 間取り図・レイアウト案 |
| `photos/` | private原写真＋対応台帳（例：`R01_W01_overview_P001.jpg`） |
| `assets/` | プレビュー画像など |

内見時の持ち物・撮影・計測リスト： [日本語](../../docs/viewing-checklist.ja.md) / [English](../../docs/viewing-checklist.md)。
