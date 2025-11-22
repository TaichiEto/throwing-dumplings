# 🥟 餃子投げ検定試験 (Gyoza Throwing Master)

中華料理屋さんの店員に向かって餃子を投げつけ、その腕前を競うアクションゲームです。
制限時間内にハイスコアを目指し、「餃子神」の称号を手にしましょう！

## 🎮 プレイする (Play Demo)
以下のリンクからブラウザですぐに遊べます（PC / スマートフォン対応）。

**👉 [https://taichieto.github.io/throwing-dumplings/](https://taichieto.github.io/throwing-dumplings/)**

---

## 📋 ゲーム概要
主人公「餃子投男」を操作し、動き回る店員さんに餃子を提供する（投げつける）ゲームです。

- **制限時間**: 60秒
- **操作方法**:
    - 画面上の店員さんを **クリック / タップ** して発射！
- **検定システム**:
    - 命中数に応じてスコアが加算されます。
    - ゲーム終了時、スコアに応じて「5級」から「名人（5段以上）」までの段位が認定されます。
- **難易度**:
    - 時間が経つにつれて店員さんの動きが速くなり、人数も増えていきます。

## 🛠️ 技術スタック
このゲームは以下の技術のみで構成された **完全な静的サイト** です。

- HTML5 Canvas
- Vanilla JavaScript (フレームワークなし)
- Tailwind CSS (CDN読み込み)
- Google Fonts (Yuji Syuku)

## 🤝 貢献について (Contributing)
機能追加やバグ修正などのPull Request (PR) は大歓迎です！

### ⚠️ 制約事項 (Requirements)
PRを送る際は、以下の条件を必ず守ってください。

1.  **静的ページであること (Static Page Only)**
    - GitHub Pagesでホスティングするため、PHPやPython、Node.jsなどのサーバーサイド処理を含まないでください。
    - ビルド不要で、`index.html` を開くだけで動作する構成を維持してください。
2.  **1ファイル構成 (Single File preferred)**
    - 現状は管理を簡単にするため、HTML/CSS/JSを `index.html` 1つにまとめています（必須ではありませんが、シンプルな構成を推奨します）。

### 追加アイデアの例
- 新しい店員キャラクターやリアクションの追加
- 効果音 (SE) の実装
- コンボボーナス機能
- 難易度選択モード

## 📄 License
This project is open source.
