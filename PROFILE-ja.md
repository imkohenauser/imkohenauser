# 斉藤 廣兵

最終更新: 2026-07-12

### AI前提のフロントエンド開発と、デザインから実装までを担うデザインエンジニア

2003年からグラフィック、DTP、Flash、Web制作に携わり、現在はReact / Vue、Next.js / Astro、CMSを用いたフロントエンド開発。

Figmaデザインを既存コードベースやCMSへ組み込み、公開後も運用しやすいUIとして整えることが主な領域。近年は、Cursor、Codex、Claude Codeなどのコーディングエージェントを制作工程に取り入れ、実装指示、参照ファイル、変更範囲、確認工程、レビュー手順を整理する開発プロセスの改善も活動領域。


| Platform | URL                                                          |
| -------- | ------------------------------------------------------------ |
| GitHub   | [github.com/imkohenauser](https://github.com/imkohenauser)   |
| Medium   | [medium.com/@imkohenauser](https://medium.com/@imkohenauser) |
| Zenn     | [zenn.dev/imkohenauser](https://zenn.dev/imkohenauser)       |
| X        | [x.com/imkohenauser](https://x.com/imkohenauser)             |


### この先やりたいこと

フロントエンド開発をAI前提で再設計し、安全性と開発効率を両立できるプロセスづくり。

デザインシステムやFigmaデザインエージェントの活用、MCPやプラグインの開発、インハウスでのプロダクト開発、チーム内のAIアシスタント利用の改善と標準化への関与。

---

## フリーランス

### フロントエンドエンジニア / デザインエンジニア

**2024年3月〜現在**

Figmaデザインのクライアント引き継ぎまでを見据えた実装、WordPress / ACF、Headless CMS、LeadGrid CMSへの組み込み、セクション、コンポーネント、テンプレートの設計を担当。

GSAP、CSS Transitionを用いたアニメーション、レスポンシブ対応、アクセシビリティ対応、AIエージェント向け規約とレビュー工程のワークフロー整備にも対応。

大手音楽関連企業のコーポレートサイト、ゴルフブランドの日本語サイト、上場企業のコーポレートサイト刷新などの案件で、Figma、Cursor、Gitを利用した制作に関与。

#### 個人のプロダクト開発

LLM出力のステアリングのためのエージェントスキル、GitHub Actionsでの配布、Astro / Starlightによる日英ドキュメントサイトの構築など。Zenn、Mediumへ設計メモや実装ログも投稿。

### 大手食品メーカーサイト運用、改善

**2023年8月〜2024年2月**

大手食品メーカーの企業サイトおよび商品サイトで、レガシーサイトの改修、既存運用ルールに沿ったページ制作、更新、デザイン修正、バナー制作、レスポンシブ対応、表示確認を担当。

### 大規模Webサービス群のUI設計とフロントエンド開発

**2017年3月〜2023年7月**

東証プライム上場企業が展開する複数のWebサービスに、外部プロダクトパートナーとして6年以上継続して参画。

FigmaによるUI設計とコンポーネント管理、Tailwind CSS、Vue / Nuxt、React / Next.js環境へのUI組み込み、Storybookによるコンポーネント共有とデザインシステム運用を担当。

インハウスのエンジニア、デザイナーと連携し、既存コードベース、設計ルール、ブランド要件、リリースサイクルに沿った継続的なUI改善に関与。GitHubを用いたチーム開発とコードレビューにも対応。

---

## 制作会社

### Webデザイン、CMS構築

**2012年4月〜2017年3月**

企業、店舗、教育関連組織などのWebサイトで、デザイン、HTML、CSS、Sass、JavaScript実装、WordPress開発、小規模EC、要件整理、更新運用支援を担当。

### Web制作、印刷物制作

**2009年3月〜2012年4月**

Webサイトのデザイン、実装、WordPress、Concrete CMSによるCMS構築、ポータルサイトのUIデザイン、冊子、広報物などのDTP制作を担当。

### グラフィックデザイン、Web制作

**2006年4月〜2009年3月**

ロゴ、ブランドガイドライン、印刷物、Webサイト制作など、企業や店舗の立ち上げに伴う販促物全般を経験。Web制作部のマネージメントも担当。

---

## グラフィックデザイナー

### グラフィックデザイン、印刷物制作

**2003年4月〜2006年3月**

ロゴ、フライヤー、ポスター、CDジャケットなどのグラフィックデザインを制作。

---

## 主な執筆

- [Cursorでのクライアントワーク：Figma to Codeのハーネス整備](https://zenn.dev/imkohenauser/articles/cursor-agent-client-work)
- [Agent Skills配布用リポジトリの設計：CLI/ZIP配布とAstro公式サイト運用](https://zenn.dev/imkohenauser/articles/mtp-agent-skills-with-astro-starlight-docs)
- [AIの出力を調整するMapping the Promptの紹介とMTP SkillのZIP利用](https://zenn.dev/imkohenauser/articles/llm-output-tuning-mtp-and-skills-zip-guide)

---

## 個人のプロダクト開発

### MTP（Mapping the Prompt）

**2025年6月〜現在**

MTPは、生成AIの出力スタイルや応答傾向を、自然言語だけでなく、座標、強度、プリセットとして扱うための個人プロジェクト。

自然言語だけでは毎回長くなりやすい出力調整を、短い指定で再利用し、複数の応答傾向を比較できるようにすることが目的。

主な構成は次のとおりです。

- マッピングのためのフレームワーク設計
- エージェントスキルの開発
- CLI / ZIP形式での配布
- Astro / Starlightによる英日対応ドキュメントサイト
- GitHub Actionsによるサイトのデプロイ、リリース
- GitHub Releasesとrelease JSONによる配布管理
- Pythonによる入力コンパイラ、ファイル操作
- `llms.txt`、Raw Markdown、Copy Markdown導線
- 複数AIモデルを対象としたエージェントスキルの比較記録
- Zenn、Mediumにおける設計史、実装ログの公開

このプロジェクトでは、人間向けのドキュメントに加え、AIアシスタントが参照しやすい配信形式も整備。関連して、LaTeX、BibTeX、TikZを用いた論文形式の技術文書も作成。

関連リンク:

- 公式サイト: [mappingtheprompt.com](https://mappingtheprompt.com/)
- 公式サイト（日本語）: [mappingtheprompt.com/ja/](https://mappingtheprompt.com/ja/)
- GitHub: [github.com/imkohenauser/mtp](https://github.com/imkohenauser/mtp)

