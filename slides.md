---
# You can also start simply with 'default'
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
fonts:
  sans: M PLUS 1
  serif: M PLUS 1
  mono: Shippori Mincho
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-left
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# 自己紹介資料

<Title />

---

# 目次

<Agenda />

---

# 自己紹介

<Intro />

---

# プログラミング経験

<Experience />

---

# Webアプリ作成

<WebAppIntro />

---

# Webアプリ作成 -落ちものゲーム

<WebAppTsubo />
<!-- 利用した技術、入れる余裕あったら入れたい -->

---

# Webアプリ作成 -日報作成アプリ

<WebAppDounatsu />
<!-- 利用した技術、入れる余裕あったら入れたい -->
---

# インターン

<Intern />

---

# キャリアビジョン

<Career />

---

<CareerDetail
  title="チームビルディング"
  detailTitle="チームメンバーのポテンシャルを引き出す人材になる"
  :details="[
    'コミュニケーションのバランサー',
    '過不足のない仕組み作り',
    '継続的な改善活動',
  ]"
/>
---

<CareerDetail
  title="技術力"
  detailTitle="技術力でチームを引っ張る"
  :details="[
    '最新技術のキャッチアップと広報',
    '技術の深い理解とニッチなユースケースへの対応',
  ]"
/>
---

<CareerDetail
  title="当事者意識"
  detailTitle="サービス全体に当事者意識を持つ"
  :details="[
    'ビジネス側も意識しながら働く',
    '利用しているOSSに当事者意識を持つ',
  ]"
/>
---

# これからやりたいこと

<FromNow />
