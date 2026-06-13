# プロフィール

最終更新: 2026-06-13

## 職種

**デザインエンジニア**  
UI / UXデザイン、Webデザイン、フロントエンド実装、CMS構築・運用支援  
実装コンテキスト設計、コーディングエージェントを活用した制作フロー整備

## 概要

斉藤廣兵（さいとうこうへい）は大阪を拠点に、2003年にグラフィックデザインから制作活動を始め、印刷物制作、Webデザイン、HTML / CSSコーディング、CMS構築、フロントエンドUI実装へと担当領域を広げてきました。現在は、UI / UX設計からCMS構築、フロントエンドUI実装、公開後の運用支援まで横断して対応しています。

特に、Figmaなどのデザインデータを、既存システムや運用フローに合わせてUIとして組み込む業務を得意としています。見た目の再現だけでなく、設計ルール、コードベース、更新フローを踏まえ、継続して扱える構造へ落とし込むことを重視しています。

近年は、コーディングエージェントを制作工程へ組み込み、実装指示や確認工程を整える開発フローも設計しています。

## 得意領域

* FigmaデザインをもとにしたCMS、SSG / SSR環境へのUI実装
* Webサイト、ランディングページ、WebサービスのUI設計と実装
* WordPress、Shopifyなど、更新運用を前提としたCMS構築
* 既存コードベース、既存コンポーネント、設計ルールに沿ったUI改修
* レスポンシブ対応、表示検証、公開後の運用を見据えた実装
* コーディングエージェントを利用した制作フロー設計
* 実装指示プロンプト、Rules、Agent Skills、ファイル構成によるハーネス・ガードレール整備
* UI仕様書、運用資料、技術ドキュメントの整理

## 技術スタック

### フロントエンド

* HTML / CSS / Sass
* JavaScript / TypeScript
* React / Next.js
* Vue.js / Nuxt.js
* Astro / Starlight
* Tailwind CSS
* Storybook
* Webpack / Vite

### CMS・EC

* WordPress / WooCommerce / WelCart
* Shopify

### UI実装・組み込み

* CMSテンプレート設計
* コンテンツ更新を前提としたフィールド設計
* SSG / SSR環境へのUI組み込み
* Ruby on Rails環境へのUI組み込み
* GitHub Primer、Material Designなどを利用したデザイン・実装
* 既存コードベース、デザインシステムへの適応

### デザイン

* Figma / Pencil / Paper
* Adobe Photoshop / Illustrator / InDesign

### 開発・運用

* GitHub / GitLab / Bitbucket
* Google Analytics / Google Search Console

### コーディングエージェント・生成AI

* Cursor
* Codex
* Claude Code

## 実務方針

デザインと実装を分離せず、要件整理、UI設計、CMS構築、フロントエンドUI実装、公開後の運用までを一つの流れとして捉えています。

実装前には、プロジェクトごとの設計ルール、コードベース、既存コンポーネント、命名規則、ディレクトリ構成、デザインシステムを確認します。そのうえで、既存環境との整合を保ちながら、更新・改修しやすい形に落とし込みます。

UI制御、モーダル、アニメーション、スクロール連動、レスポンシブ調整などは、必要な範囲を確認しながら実装・改修します。

複雑な業務ロジック、データベース設計、大規模なバックエンド開発を中心とする案件については、担当範囲を確認したうえで対応します。

## 業務スタンス・環境

* **リモートワークへの適応**  
  2017年より現在まで一貫して完全リモートワークの環境で活動しており、テキストやドキュメントをベースとした非同期コミュニケーション、自走的なタスク管理を得意としています。
* **開発環境・ツールの前提**  
  制作効率と品質の最大化、およびコーディングエージェントを用いた開発フローを前提としているため、実務ではCursorまたは同等のAI統合型IDEは必須と考えています。

## コーディングエージェント前提の実装コンテキスト設計

2025年末から、Cursor、Codex、Claude Codeなどのコーディングエージェントを制作工程へ導入しています。

主な対象は、デザインデータを既存コードベースやCMSテンプレートへ組み込むフロントエンド実装です。制作開始前に、参照ファイル、変更範囲、変更しない範囲、確認工程をタスク仕様として整理します。

生成されたコードをそのまま利用するのではなく、テンプレート構造、フィールド設計、命名規則、レスポンシブ仕様、公開後の更新方法に合わせて、本番環境で継続して扱える形へ調整しています。

また、エージェントが意図しない方向へ進まないよう、Rules、Commands、Workflows、Agent Skillsをハーネスやガードレールとして整備しています。

主に、次のような設計を行います。

* 実装指示プロンプトのタスク仕様化
* Figma MCPを用いたデザインデータ参照と実装支援
* Rules、Commands、Workflows、Agent Skillsによるハーネス・ガードレール設計
* 必要な情報を段階的に渡すProgressive Disclosure
* エージェントによる実装と、人間による確認工程の分離
* 既存コードベースへの影響範囲の確認
* 技術ドキュメント、運用資料の整理

関連する記事:

* [Cursor でのクライアントワーク：Figma to Code のハーネス整備](https://zenn.dev/imkohenauser/articles/cursor-agent-client-work) / 2026-06-06

## 個人プロジェクト

### MTP（Mapping the Prompt）

生成AI（大規模言語モデル）の出力スタイルや応答傾向を、自然言語だけでなく、座標、強度、プリセットとして扱うためのインターフェースを設計・開発しています。自然言語だけでは毎回長くなりやすい出力調整を、短い指定で再利用し、複数の応答傾向を比較できるようにすることを目的としています。

![MTPのキービジュアル。左のパネルにはOpen-StillやPower-VoidなどのSide A / Side Bのノードスライダーが示され、Powerは70に設定されています。右のパネルにはA-Sと1-19のラベルが付いた19x19のcolumn:rowカラーグリッドが示されています。](https://raw.githubusercontent.com/imkohenauser/mtp/main/public/ogp%402x.png)

主な構成は次のとおりです。

* Agent Skills（エージェントスキル）
* Pythonによる入力コンパイラ
* CLI / ZIP形式での配布
* Astro / Starlightによる公式ドキュメント
* GitHub Actionsによるデプロイ・リリース
* 複数AIモデルを対象とした比較記録
* Zenn、Mediumにおける設計史、実装ログの公開

関連リンク:

* 公式サイト（日本語）: [mappingtheprompt.com/ja/](https://mappingtheprompt.com/ja/)
* GitHub: [github.com/imkohenauser/mtp](https://github.com/imkohenauser/mtp)

関連する記事:

* 【開発運用向け】[Agent Skills配布用リポジトリの設計：CLI/ZIP配布とAstroの公式サイト運用](https://zenn.dev/imkohenauser/articles/mtp-agent-skills-with-astro-starlight-docs) / 2026-05-16
* 【利用者向け】[AIの出力を調整する「Mapping the Prompt」の紹介と、ZIP追加したMTP SkillをClaude iOSアプリで使う](https://zenn.dev/imkohenauser/articles/llm-output-tuning-mtp-and-skills-zip-guide) / 2026-05-25

---

## 職務経歴

### 2024/03〜現在

| 項目 | 内容 |
|------|------|
| 職種 | Web制作受託・フロントエンド実装支援 |
| 役割 | UI / UXデザイン、Webデザイン、フロントエンド実装、制作ディレクション |
| 体制 | 個人または小規模チーム |
| 主な環境 | Figma、WordPress、Shopify、HTML、CSS、Tailwind CSS、JavaScript、TypeScript、React、Next.js、GitHub、Cursor、Codex、Claude Code |
| 概要 | Web制作の受託業務として、デザイン、コーディング、CMS構築、既存サイト改修、運用支援を担当しています。 |
| 主な業務 | Webサイト、ランディングページのデザイン、実装<br>FigmaデザインのCMS、SSG / SSR環境への組み込み<br>WordPressテーマの調整、テンプレート改修<br>Shopifyを用いたサイト構築<br>React / Next.js環境でのUIコンポーネント実装<br>Tailwind CSSを用いたUI実装<br>レスポンシブ対応、表示検証、運用資料作成<br>コーディングエージェントを用いた実装工程の効率化 |

### 2023/08〜2024/02

| 項目 | 内容 |
|------|------|
| 職種 | 大手食品メーカーの企業サイト・商品サイト運用 |
| 役割 | Webデザイナー、コーダー |
| 主な環境 | Adobe Photoshop、Adobe Illustrator、HTML、CSS、jQuery |
| 概要 | 大手食品メーカーの企業サイトおよび商品サイトにおいて、既存運用ルールに沿ったページ制作、更新、デザイン修正を担当しました。 |
| 主な業務 | デザインデータをもとにしたHTML / CSS / jQuery実装<br>既存静的ページの更新、テンプレート改修<br>商品・キャンペーン関連ページのデザイン修正、バナー制作<br>レスポンシブ対応、表示確認 |

### 2017/03〜2023/07

| 項目 | 内容 |
|------|------|
| 職種 | 大規模Webサービス群のUI設計・フロントエンド実装 |
| 役割 | UI / UXデザイン、フロントエンド実装 |
| 主な環境 | Figma、Tailwind CSS、Vue.js、Nuxt.js、React、Next.js、Storybook、Webpack、GitHub |
| 概要 | 東証プライム上場企業が展開する、数百万ユーザー規模のマルチブランドWebサービス群に、外部プロダクトパートナーとして6年以上継続して参画しました。複数サービスにまたがるUI設計、コンポーネント実装、デザインシステム運用を担当し、各サービスの個別要件とグループ全体のデザイン共通化の両立に取り組みました。 |
| 主な業務 | FigmaによるUI設計、コンポーネント管理<br>Tailwind CSSを用いたUI実装<br>Vue.js / Nuxt.js、React / Next.js環境への組み込み<br>Storybookを用いたコンポーネント共有、デザインシステム運用<br>インハウスのエンジニア・デザイナーとの連携<br>既存コードベース、設計ルール、ブランド要件に沿ったUI改修<br>GitHubを用いたチーム開発、コードレビュー対応 |
| 実績・貢献 | 複数サービスが並行稼働する環境下で、既存コードベースへの適応、UIの一貫性保持、リリースサイクルに沿った継続的な改善に貢献しました。 |

### 2012/04〜2017/03

| 項目 | 内容 |
|------|------|
| 職種 | 制作会社におけるWebデザイン・CMS構築 |
| 役割 | Webデザイナー、コーダー |
| 主な環境 | Adobe Photoshop、Adobe Illustrator、WordPress、HTML、CSS、Sass、JavaScript、jQuery、PHP |
| 概要 | 企業、店舗、教育関連組織などのWebサイト制作を担当しました。デザイン、コーディング、CMS構築、運用支援まで一貫して対応しました。 |
| 主な業務 | Webデザイン<br>HTML / CSS / Sass / jQueryによる実装<br>WordPressテーマ・プラグイン開発<br>小規模ECサイト構築<br>BEM / FLOCSSを用いたCSS設計<br>要件整理、更新運用支援 |

### 2009/03〜2012/04

| 項目 | 内容 |
|------|------|
| 職種 | 制作会社におけるWeb制作・印刷物制作 |
| 役割 | Webデザイナー、コーダー |
| 主な環境 | Adobe Photoshop、Adobe Illustrator、Adobe InDesign、WordPress、Concrete CMS、HTML、CSS、JavaScript、PHP |
| 概要 | Webサイト制作、CMS構築、運用支援、印刷物制作を担当しました。 |
| 主な業務 | Webサイトのデザイン、実装、運用<br>WordPress、Concrete CMSを用いたCMS構築<br>ポータルサイトのUIデザイン<br>冊子、広報物などのDTP制作 |

### 2006/04〜2009/03

| 項目 | 内容 |
|------|------|
| 職種 | 制作会社におけるグラフィックデザイン・Web制作 |
| 役割 | グラフィックデザイナー、Webデザイナー、コーダー |
| 主な環境 | Adobe Photoshop、Adobe Illustrator、HTML、CSS、JavaScript、PHP |
| 概要 | 企業や店舗の立ち上げに伴うブランディング、印刷物制作、Webサイト構築を担当しました。Web制作部門の進行管理や制作指導も経験しました。 |
| 主な業務 | ロゴ、ブランドガイドライン、印刷物の制作<br>HTML / CSS / JavaScriptによるWebサイト構築<br>Web制作の進行管理<br>制作メンバーへの指導 |
| 実績・貢献 | 特にロゴ制作を多く担当し、1案件につき3案を提案する形式で進行しました。黄金比を用いた企業や団体等のロゴを、ブランドカラー・デザインシートと共に年間30件以上を納品しました。 |

### 2003〜2006/03

| 項目 | 内容 |
|------|------|
| 職種 | グラフィックデザインの個人制作 |
| 役割 | グラフィックデザイナー |
| 主な環境 | Adobe Illustrator、Adobe Photoshop |
| 概要 | イベント告知を中心に、フライヤー、ポスター、ロゴなどのグラフィックデザインを制作しました。 |

---

## 関連リンク

| Platform      | URL                                                          |
|---------------|--------------------------------------------------------------|
| GitHub        | [github.com/imkohenauser](https://github.com/imkohenauser)   |
| Medium        | [medium.com/@imkohenauser](https://medium.com/@imkohenauser) |
| Zenn          | [zenn.dev/imkohenauser](https://zenn.dev/imkohenauser)       |
| X             | [x.com/imkohenauser](https://x.com/imkohenauser)             |
