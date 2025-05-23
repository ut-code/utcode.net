---
app:
  name: シ楽バス
  description: 前期課程に特化した時間割サービス
  url: https://syllabus.utcode.net/
  platform: [web]
  domain: [tool] # バックエンドついたら app になる

order: 3
date: 2023-10-02
kind: long-term
status: stable
tags: [JavaScript]

thumbnail:
  src: ./thumbnail.jpg

social:
  github: https://github.com/ut-code/syllabus-frontend
---

## 概要

シ楽バス(しらばす)では前期課程の講義情報への容易なアクセス、そして時間割の作成が可能です。
UTASより気軽に使用できます。

## 特徴

- 自身の所属に基づき、必須科目が自動で登録
- 登録された講義の合計単位の表示
- 曜限や成績の評価方法など、様々なフィルターを用いた講義検索が可能
- 履修上の注意を記載したページがあり、時間割作成を補助します
- 時間割の閲覧に特化したモードと編集に特化したモードを分離し、使いやすいアプリを目指しました

## Quick Start

1. [シ楽バスのページ](https://syllabus.utcode.net/)にアクセス
2. 「はじめる」ボタンをクリック
3. 所属を入力し、「OK」をクリック

必須科目が登録された時間割の完成!
