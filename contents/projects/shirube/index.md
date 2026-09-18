---
app:
  name: しるべ
  description: 進振り要件を見ながら、必要な情報だけで履修を組める

  url: https://shirube.utcode.net/title
  platform: [web]
  domain: [tool] # バックエンドついたら app になる

date: 2026-09-18
kind: long-term
status: released
tags: [JavaScript]

thumbnail:
  src: ./thumbnail.png

favicon: ./favicon.png

social:
  github: https://github.com/ut-code/syllabus/
---

## 概要

時間割を作成することができ、自分の履修状況が前期課程修了要件・進学選択参加要件を満たしているかを確認できます。

## 特徴

- 自身の所属に基づき、必修科目が自動で登録
- 登録済みの講義が前期課程修了要件・進学選択参加要件を満たしているか判定
- 曜限や成績の評価方法など、様々なフィルターを用いた講義検索が可能
- 履修上の注意を記載したページがあり、時間割作成を補助します
- 時間割を見ながら講義を検索画面を開けるようにし、使いやすいアプリを目指しました

## Quick Start

1. [しるべのページ](https://shirube.utcode.net/title)にアクセス
2. 「はじめる」ボタンをクリック
3. 所属(学部・学年・クラス)を選択し、「次へ」をクリック
4. 必修科目の自動入力を確認し、「OK」をクリック

必修科目が登録された時間割の完成!
