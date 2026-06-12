# 育毛LP（あるしあ鍼灸接骨院）

Canvaで作成したLP（https://alcia.my.canva.site/ikumou）をHTML化し、Microsoft Clarityで計測できるようにしたもの。

## 構成
- `index.html` — LP本体（画像12分割 + クリック領域オーバーレイ + Clarityタグ）
- `images/` — Canvaから書き出したLP画像（1280px幅、12分割）

## Canvaのデザインを更新したとき
1. Canvaで「薄毛用LP」(DAG0JrkAwxo) をJPG（幅1280px）で書き出す
2. 12分割して `images/` を差し替える（ボタン位置が変わった場合はオーバーレイ座標も修正）
3. git push すれば自動で反映される

※詳細はClaude Codeに「育毛LPを更新して」と頼めば再生成できます。
