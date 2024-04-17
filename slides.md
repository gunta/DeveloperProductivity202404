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
layout: two-cols-header
---

# 開発環境

::left::

#  BEFORE

- IntelliJ Idea
  - IDE完成度高い
- VSCode
  - Extensionが充実

::right::

# AFTER

- Cursor
  - AI機能はGitHub Copilotを大幅に超えてる
  - UXは素晴らしい
  - 勢いはある（OpenAIが投資）
  - VSCodeのExtensionと設定が全部使える
    - Forkではあるが、頻繁に更新される
  - 20$/月の価値は20分でペイするのを体感


---
layout: two-cols
---

# タスク管理 BEFORE

- JIRA
  - タスク管理に向いてる
  - 使いたい人はいない
- GitHub Issues
  - 開くのだるい
  - 機能貧弱

::right::

# AFTER

- Linear
  - エンジニアが使いたくなる
  - UXが素晴らしい 
  - Notionよりもサクサク
  - サクサクすぎ（強調）
  - Local First Architectureの代表プロダクト

---
layout: two-cols
---

# ブラウザ BEFORE

- Chrome
- Safari

::right::

# AFTER

- Arc
  - GitHubのPull Requestをリアルタイムで表示される機能がリリース

---
layout: two-cols
---

# バンドラーBEFORE

- Webpack

::right::

# AFTER

- Vite
- 今後はFarm

---
layout: two-cols
---

# 英語修正 BEFORE

- PR都度修正

::right::

# AFTER

- CSpellを導入
  - CI
  - Lefthook

---
layout: two-cols
---

# クラウド BEFORE

- AWS（33リージョン）
- GCP（40リージョン）
- Azure（60リージョン）

::right::

# AFTER

- Cloudflare（310リージョン）
  - Edgeではない、AWSの競合になった
  - コストメリットがデカすぎる
  - デプロイが早すぎる
  - エグレスがかからない
  - I/O時は課金されない
  - Telemetryは無料
  - 日本にDCが4個
  - 中国にDCが37個
  - アメリカにDCが3個
  - GPU Inference
  - 楽しい！（大事）

---
layout: two-cols
---

# バックエンド言語 BEFORE

- Golang

::right::

# AFTER

- TypeScript

---
layout: two-cols
---

# TSランタイムBEFORE

- Npm
- Pnpm

::right::

# AFTER

- Bun
- 10秒でインストール

---
layout: two-cols
---

# CI BEFORE

- GitHub Actions
- Turborepo

::right::

# AFTER

- GitHub Actions
- Nx

---
layout: two-cols
---

# スクリプトBEFORE

- Bash
- Zx

::right::

# AFTER

- Bun Shell

---
layout: two-cols
---

# サーバーBEFORE

- Express
- Go

::right::

# AFTER

- Hono

---
layout: two-cols
---

# ORM BEFORE

- Prisma

::right::

# AFTER

- Drizzle

---
layout: two-cols
---

# Linter BEFORE

- Eslint

::right::

# AFTER

- Biome
  - 早い

---
layout: two-cols
---

# Auth BEFORE

- Firebase
- Auth0

::right::

# AFTER

- Clerk
  - UXが良い
  - 料金はボッタクリではない
  - 生産性が上がる
  - React Componentが全部用意されている

-

---

# CLIでLLM翻訳

<SlidevVideo v-click autoplay controls width="70%" >
  <source src="/AutoCat1.mp4" />
</SlidevVideo>

---

# CloudflareでLLM

<SlidevVideo v-click autoplay controls width="70%" >
  <source src="/CFDemo.mov" />
</SlidevVideo>

---

# Test 

<div class="p-3">
  Text
</div>

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row1Col1 | Row1Col2 | Row1Col3 |
| Row2Col1 | Row2Col2 | Row2Col3 |
| Row3Col1 | Row3Col2 | Row3Col3 |

```ts {monaco-diff}
console.log('Original text')
~~~
console.log('Modified text')
```


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

<!-- <logos-bun class="text-4xl" /> -->

<StarHistory repo="stanfordnlp/dspy" />


---
layout: before-after
---

# 比較

::before::
- Hers

```ts
fafaf
```

::after::

- Chau
- Bye

---

