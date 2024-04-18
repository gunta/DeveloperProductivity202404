---
theme: default
background: https://unsplash.com/photos/KE0nC8-58MQ/download?ixid=M3wxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNzEzMzY1OTIwfA&w=2400
title: 開発生産性を向上させた導入技術の紹介 @ 2024/4
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
author: Günther Brunner
download: true
twoslash: true
monaco: true
---


# 導入して開発生産性上がった技術を紹介

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Slidev <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: intro
---

# 自己紹介

<fluent-emoji-person-light /> Günther Brunner **（グンタ）**
<br>

<noto-calendar /> CyberAgent入社 **2012年**
<br>

<twemoji-flag-japan /> **東京**在住（現在）
<br>
<br>

<flat-color-icons-like /> <logos-openai-icon /> AI <majesticons-ux-circle-line /> UX <logos-figma /> Design <emojione-v1-lightning-mood /> Performance
<br>
<logos-spotify-icon /> Music <logos-netflix-icon /> Movies <noto-sushi /> Sushi <material-symbols-travel class="text-blue-400" /> Travel

<br>
<br>

<fa6-brands-square-x-twitter /> [@gunta85](https://twitter.com/gunta85)
<br>

<carbon-logo-github /> [@gunta](https://github.com/gunta)
<br>

<skill-icons-devto-light /> [dev.to/gunta](https://dev.to/gunta)
<br>

<simple-icons-zenn class="text-blue-400"/> [zenn.dev/gunta](https://zenn.dev/gunta)

---
layout: before-after
---

# 部署移動

::before::
- 🤖 `部署` **AI事業本部**（2年前から）
- 🔄 `事業` **AI Shift所属**（2023年7月から）
- 🎨 `職種` [**デザインエンジニア**](https://vercel.com/blog/design-engineering-at-vercel)

::after::
- 🏢 `新部署` 全社
  - **CTO統括室・Developer Productivity室**
  - 4/16付けで移動
- 🎯 `今期のミッション`
  - **🚀 生産性向上**
  - 🏃‍♂️ AI事業本部を中心に生産性を上げる

---
layout: quote
---

# 開発生産性を向上させた導入技術の紹介

## 2024/4

---
layout: iframe
url: https://ja.sli.dev/
---

---

# Slidevとは何ですか？

Slidevは**開発者向けのスライドメーカー・プレゼンター**で、以下の機能がある

- 📝 **テキストベース** 
  - Markdownでコンテンツに集中し、後でスタイルを整えられる
- 🧑‍💻 **開発者フレンドリー** 
  - コードハイライト、ライブコーディングと自動補完
- 🤹 **インタラクティブ** 
  - コンポーネントを埋め込んで表現ができる
- 🎥 **録画** 
  - 組み込みの録画とカメラビュー
- 📤 **ポータブル** 
  - PDF、PNG、またはGitHub PagesにSPAをエクスポート可能
- 🛠 **カスタマイサブル** 
  - ウェブページで可能なことは何でもできる


[Slidevについてもっと読む](https://ja.sli.dev/guide/why)

---

# ⭐️ Slidev

<StarHistory repo="slidevjs/slidev" />


---
transition: slide-up
level: 2
---

# AI Workerの紹介（4月）

<SlidevVideo autoplay controls width="70%" >
  <source src="/AIWorkerPortal.mp4" />
</SlidevVideo>

---

# AI Workerの利用言語

<logos-typescript-icon class="text-3xl "/> 
`Frontend` | `Backend` | `Scripts`


![Languages](/langs.png)

---
layout: before-after
---

# 🛠️ 開発環境 

::before::

- <logos-intellij-idea /> IntelliJ Idea
  - IDE完成度が高い
- <devicon-vscode /> VSCode
  - Extensionが充実

::after::



- <img alt="Cursor" src="https://cursor.sh/brand/icon.svg" width="28px" style="display: inline-block" /> [Cursor](https://cursor.sh/)
  - AI機能はGitHub Copilotを大幅に超えています
  - ユーザー体験が非常に優れています
  - OpenAIからの投資を受けて急速に成長中
  - VSCodeの全ての拡張機能と設定が利用可能
    - フォークであり、定期的に更新が行われる
  - $20/月のコストは使用開始20分で元が取れるほどの価値がある

---
layout: before-after
---

# ☑️ タスク管理

::before::

- <logos-jira /> JIRA
  - タスク管理に向いている
  - 使いたい人はいない
- <simple-icons-github /> GitHub Issues
  - 開くのだるい
  - 機能が貧弱

::after::

- <logos-linear-icon /> [Linear](https://linear.app/)
  - エンジニアが使いたくなる
  - UXが素晴らしい 
  - Notionよりもサクサク
  - サクサクすぎ（強調）
  - Local First Architectureの代表プロダクト

---
layout: before-after
---

# 🌐 ブラウザ

::before::

- <logos-chrome /> Chrome
- <logos-safari /> Safari

::after::

- <logos-arc /> Arc
  - <carbon-logo-github /> GitHubのプルリクをリアルタイムで表示される[Live Folders機能がリリースされた](https://zenn.dev/t_yng/articles/a6f6ff55bef1b4)

---
layout: before-after
---

# 📦 JS バンドラー

::before::

- <logos-webpack /> Webpack
  - 2014年に[日本語初の記事を書きました](https://ameblo.jp/ca-1pixel/entry-11884453208.html)

::after::

- <logos-vitejs /> [Vite](https://vitejs.dev/)
  - 一部Rust製
  - 開発時に速い

## 🔮 FUTURE
- <img src="https://www.farmfe.org/img/logo.png" alt="Farm" width="28px" style="display: inline-block;"/> [Farm](https://www.farmfe.org/)
  - Rust製
  - 100% Vite互換性
  - どんな時でも速い

---
layout: before-after
---

# 📦 CSS バンドラー

::before::

- <logos-esbuild /> ESBuild

::after::

- ⚡️ [Lightning CSS](https://lightningcss.dev/)
  - Transpilation
  - CSS Modules
  - Bundling
  - Minification 
  - Rust製、速い
  - Viteでも使える


---
layout: before-after
---

# <twemoji-flag-united-states /> 英語Linter

::before::

- 都度PR人間が修正
- 抜け漏れ発生

::after::

- <vscode-icons-file-type-cspell /> [CSpell](https://cspell.org/)
  - CI時
  - Lefthook時

---
layout: before-after
---

# ☁️ クラウド（最も大事）

::before::

- <logos-google-cloud /> GCP（40リージョン）
  - 🇯🇵 DC：東京、大阪
  - 🇨🇳 DC：無し
- <logos-aws /> AWS（33リージョン）
  - 🇯🇵 DC：東京、大阪
  - 🇨🇳 DC：無し
- <logos-microsoft-azure /> Azure（60リージョン）
  - 🇯🇵 DC：埼玉、大阪
  - 🇨🇳 DC：3つ

::after::

- <logos-cloudflare-icon /> Cloudflare（310リージョン）
  - 🇯🇵 DC: 4つ（東京、大阪、福岡、那覇）
  - 🇨🇳 DC: 37つ
  - 🇺🇸 DC: 53つ
  - 🚫 AWSの競合になり「Edge」もう呼ばない
  - 💸 コストメリットが顕著
  - ⚡️ デプロイ速度が速い（10倍〜）
  - 🆓 ストレージエグレス料金が不要
  - 🆓 I/O操作時の課金なし（LLM呼び出し等）
  - 🆓 Telemetryが無料
  - 🖥️ GPUとLLM推論
  - 😄 楽しい！（重要）

---
layout: before-after
---

# 🖥️ バックエンド言語

:: before ::

- <logos-go /> Golang

::after::

- <logos-typescript-icon /> TypeScript

---
layout: two-cols
---

<style>
.col-right {
border-left: 1px solid #ddd;
}
</style>

|  |  <br> 特徴 | <logos-typescript-icon />  | <logos-go /> |
|:---:|---|:---:|:---:|
| <flat-color-icons-parallel-tasks /> | 並行性と並列性 | ❌ | ✅ |
| <nonicons-type-16 class="text-blues-400" /> | ベーシックな型安全性 | ✅ | ✅ |
| <mdi-null class="text-yellow-400" /> | Null安全性 | ✅ | ❌ |
| <ooui-error class="text-red-400" /> | エラー安全性 | ❌ | ✅ |
| <ri-share-box-fill /> | 配布のしやすさ | ✅ | ✅ |
| <logos-microsoft-windows-icon /> | Windows対応 | ✅ | ✅ |
| <file-icons-terminal /> | スタンドアロンバイナリ | <logos-bun /> | ✅ |

::right::

|  |  <br> 特徴 | <logos-typescript-icon />   | <logos-go />  |
|:---:|---|:---:|:---:|
| <logos-arc  /> | ブラウザで実行 | ✅ | ❌ |
| <logos-cloudflare-workers-icon  /> | <span style="background-color:#FFFFE0"> **Edgeで実行** </span> | ✅ | ❌ |
| <logos-ios  /> | iOSで実行 | <logos-expo-icon /> | ❌ |
| <logos-android-icon  /> | Androidで実行 | <logos-expo-icon /> | ✅ |
| <ph-pipe-fill class="text-blue-400" /> | Pipes | ❌ | ❌ |
| <oui-token-enum class="text-yellow-400" /> | 代数的データ型 | ✅ | ❌ |
| <material-symbols-match-word-rounded class="text-red-400" /> | パターンマッチング | ❌ | ❌ |

---
layout: before-after
---

# <logos-typescript-icon /> TypeScriptランタイム

::before::

- <logos-nodejs-icon-alt /> Node

::after::

- <logos-bun /> [Bun](https://bun.sh/)
  - 実行時間が5倍速い
  - トランスパイル不要
  - CJSとESMがミックス可能

---
layout: before-after
---

# <logos-typescript-icon /> TypeScriptパッケージマネジャー

::before::

- <logos-npm /> npm
- <logos-pnpm /> pnpm

::after::

- <logos-bun /> [Bun](https://bun.sh/)
  - 10秒でインストール
  - npmより30倍速い

---
layout: before-after
---

# <logos-typescript-icon /> TypeScriptテストランナー

::before::

- <logos-vitest /> Vitest

::after::

- <logos-bun /> [Bun](https://bun.sh/)
  - 5倍速い

---
layout: before-after
---

# <heroicons-command-line-20-solid /> スクリプト

::before::

- <devicon-bash /> Bash
- <logos-google-icon /> Zx

::after::

- <logos-bun /> [Bun Shell](https://bun.sh/)
  - クロスプラットフォーム
  - ロジックが書きやすい
  - 若手も分かる
  - Full TS

```ts
import { $ } from "bun"

const output = await $`ls -l`.text()
console.log(output)
```

---
layout: before-after
---

# 🏗️ モノレポCI

::before::

- <logos-turborepo-icon /> Turborepo
- <simple-icons-moonrepo /> [moonbase](https://moonrepo.dev/moonbase)

::after::

- <logos-nx /> [Nx](https://nx.dev/)
  - 最も機能が充実している
  - 最もスケールする
  - 並行処理が得意
  - 速い

---
layout: before-after
---

# 🖥️ サーバーフレームワーク

::before:: 

- <devicon-express /> Express
- <logos-go /> Go

::after::

- <logos-hono /> [Hono](https://hono.dev/)
  - 軽量
  - 速い
  - シンプル
  - マルチランタイム（ロックインされない）
    - <logos-bun /> Bun
    - <logos-nodejs-icon /> Node.js
    - <logos-aws-lambda /> Lambda
    - <logos-vercel-icon /> Vercel
    - <logos-cloudflare-workers-icon /> Cloudflare Workers

---
layout: before-after
---

# 🗄️ データベースORM

::before:: 

- <logos-prisma /> Prisma

::after::

- <simple-icons-drizzle /> [Drizzle](https://orm.drizzle.team/)
  - 軽量、速い
  - SQLに近い
  - マイグレーションできる
  - マルチランタイム
    - <logos-bun /> Bun <logos-vercel-icon /> Vercel  <logos-cloudflare-workers-icon /> Cloudflare Workers <simple-icons-expo /> Expo <logos-arc /> Browser <logos-supabase-icon /> Supabase  <logos-electron /> Electron  <simple-icons-react /> React Native
  - マルチデータベース
    - <logos-postgresql /> PostgreSQL <logos-supabase-icon /> Supabase <logos-vercel-icon /> Vercel  <logos-sqlite /> SQLite <logos-mysql /> MySQL  <logos-xata-icon /> Xata  <simple-icons-turso /> Turso  <logos-neon-icon /> Neon
    
---
layout: before-after
---

# 🔍 Linter

::before::

- <logos-eslint/> Eslint

::after::

- <vscode-icons-file-type-biome /> [Biome](https://biomejs.dev/)
  - Rust製
  - ESLint等200以上のルール
  - 速い

---
layout: before-after
---

# 🎨 Formatter

::before::

- <logos-prettier /> Prettier
- <mdi-console /> dprint

::after::

- <vscode-icons-file-type-biome /> [Biome](https://biomejs.dev/)
  - Rust製
  - Prettierと97%互換性
  - 35倍速い

---
layout: before-after
---

# 🔐 認証基盤

::before:: 
- <logos-firebase /> Firebase Auth
- <logos-supabase-icon /> Supabase Auth
- <simple-icons-auth0 /> Auth0
- <simple-icons-okta /> Okta

::after::

- <simple-icons-clerk /> [Clerk](https://clerk.com/)
  - <twemoji-sparkles /> 最も優れたユーザーエクスペリエンス
  - <mdi-cash-multiple /> 合理的な価格設定
  - <mdi-speedometer /> 生産性向上
  - <mdi-react /> **React コンポーネント**を提供
  - <mdi-timer-sand /> リードタイムの短縮
  - <logos-stripe /> 今後、Stripeとの連携予定

<br> 

> UXよりも低コストが重要な場合
> - [Kinde](https://kinde.com/)
> - [Lucia](https://lucia-auth.com/)

---

# <bi-translate /> 自作したCLI自動LLM翻訳



<SlidevVideo autoplay controls width="70%" >
  <source src="/AutoCat1.mp4" />
</SlidevVideo>

---

# <logos-cloudflare-workers-icon /> Cloudflare Workers上で動作するLLM

<SlidevVideo autoplay controls width="60%" >
  <source src="/CFDemo.mov" />
</SlidevVideo>



---
layout: two-cols
---

# BEFORE
## LLMプロンプト錬金術
Hi


<!-- Copy-paste in your Readme.md file -->

<a href="https://next.ossinsight.io/widgets/official/analyze-repo-stars-history?repo_id=41986369" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/analyze-repo-stars-history/thumbnail.png?repo_id=41986369&image_size=auto&color_scheme=dark" width="721" height="auto">
    <img alt="Star History of pingcap/tidb" src="https://next.ossinsight.io/widgets/official/analyze-repo-stars-history/thumbnail.png?repo_id=41986369&image_size=auto&color_scheme=light" width="721" height="auto">
  </picture>
</a>

<!-- Made with [OSS Insight](https://ossinsight.io/) -->


::right::

# AFTER
## LLMプロンプトプログラミング
- DSPy
- merit
- merit
- merit

<img alt="Star History" src="https://api.star-history.com/svg?repos=stanfordnlp/dspy" width="100%">

---

# ⭐️ DSPy

<StarHistory repo="stanfordnlp/dspy" />



