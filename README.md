# Azure Horizon Okinawa | 高級ホテル公式サイト（サンプルLP）

架空のラグジュアリーリゾートホテル「Azure Horizon Okinawa」のランディングページです。
ポートフォリオとして作成しました。

**[👉 デモサイトはこちら（実際の動作を確認できます）](https://okkunnkkk.github.io/azure-horizon-okinawa/)**
## 📌 コンセプト
**「静寂と碧（あお）の聖域」**
沖縄の隠れ家リゾートをテーマに、余白を活かした高級感のあるデザインと、波のようなゆったりとしたマイクロインタラクションを実装しました。

## ✨ こだわりのポイント（技術・デザイン）

### 1. ユーザー体験（UX）への配慮
- **インタラクション**: `Intersection Observer` APIを使用し、スクロールに合わせて要素がふわっと浮き上がる演出を実装。jQuery等のライブラリに頼らず、軽量なVanilla JSでパフォーマンスを最適化しています。
- **フォーム最適化**: スマートフォンでの入力負荷を下げるため、`<input type="email">` や `<input type="date">` 等の属性を適切に設定しています。
- **アクセシビリティ**: セマンティックなHTML構造（`<header>`, `<main>`, `<article>`等）を採用し、マシンリーダブルなコード記述を徹底しています。

### 2. デザイン実装
- **SVGロゴ**: 画像ファイルを使わず、SVGコードでロゴを描画。Retinaディスプレイ等の高解像度端末でも滲まず、鮮明に表示されます。
- **レスポンシブ対応**: CSS GridとFlexboxを組み合わせ、PC・タブレット・スマートフォンすべてのデバイスで崩れないレイアウトを構築しています。
- **世界観の統一**: Google Fonts（Shippori Mincho）を使用し、明朝体ベースの上品なタイポグラフィで統一しました。

## 🛠 使用技術
- **HTML5** (Semantic Markup)
- **CSS3** (CSS Variables, Flexbox, Grid, Animation)
- **JavaScript** (ES6+, Intersection Observer)
- **Single File Component** (配布・管理のしやすさを考慮し、今回は単一ファイルで構築)

## 📂 ファイル構成
```text
/
├── index.html   # HTML, CSS, JSを含むソースコード
└── README.md    # 本ファイル

⚠️ 注意事項
本サイトはポートフォリオ用の架空のサイトです。実在するホテルではありません。

予約フォームはデモ用のため、送信ボタンを押してもバックエンドへのデータ送信は行われません。

画像素材は Unsplash のフリー素材を使用しています。

© 2026 Syn Design
