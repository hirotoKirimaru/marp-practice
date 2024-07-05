---
layout: intro
background: https://sli.dev/demo-cover.png
---

# TDD とは

## KAKEAI テックディスカッション

### 2024/07/10 水上 皓登

<!--
ああああああ
-->

---
layout: cover
background: https://sli.dev/demo-cover.png
---

# 水上が社会人として働いてわかった

# うまく働くコツ

---
layout: cover
background: https://sli.dev/demo-cover.png
---

# いかに早く理解するか
# いかに深く理解するか

<!-- ああ -->


---
layout: cover
---
# 理解度と時系列

---
---

# 理解度と時系列

![](/graph.png)


---
---
# 理解度と時系列

![](/graph2.png)

---
layout: cover
---

# 早く理解する方法はいろいろある


---
layout: cover
---

# 分かりやすく効果が出やすい

# TDD を紹介します

---
layout: cover
---

# TDD

Test Driven Development
テスト駆動開発 と呼ばれる手法

---
layout: cover
---

# 忘れてください

---
layout: cover
---

# TDD

Todo Driven Development
Todo 駆動開発

---

BabyStep
カイジの鉄骨渡りのような進み方。

汚くてもいい
目的のテストが実行できていれば、最初から機能を担保しきれていなくてもいい










1 サイクル 30 秒

Red
Green
Refactor
Report

TopDown/ BottomUp
どこから担保するか

TopDown はテストしづらい、その代わりに安定する
BottomUp はテストしやすい、その代わりに不安定。リファクタリングで別の場所に移動することがあるから。

TDD はどこから？
理想はテストコードから。
Java ならテストコードを生やすことも可能。

フラクタル構造をもつ

テストはデザイン
---

# TDDの基本サイクル
- Red: 失敗するテストを書く
- Green: テストが通る最小限の実装をする
- Refactor: リファクタリングを行う



---

# 正しいものを正しくつくる

---
# TDDブートキャンプ
## FizzBuss
## 暦で1か月


TDDとは
Test Driven Development (テスト駆動開発)
プログラムの実装前にテストコードを書く開発手法
短いサイクルを繰り返して開発を進める
「動作する綺麗なコード」を目指す
TDDの基本サイクル
Red: 失敗するテストを書く
Green: テストが通る最小限の実装をする
Refactor: リファクタリングを行う
このサイクルを繰り返す
TDDのメリット
仕様への理解が深まる
早期にバグを発見できる
必要な機能を無駄なく開発できる
リファクタリングが容易になる
テストによる安心感
TDDの実践例: FizzBuzz
1〜100の数字を入力とする
3の倍数なら「Fizz」
5の倍数なら「Buzz」
3と5の両方の倍数なら「FizzBuzz」
それ以外は数字をそのまま返す
TDDの実践ポイント
Baby Step: 小さな一歩ずつ進める
30秒サイクル: 短いサイクルを意識する
Top-down / Bottom-up: アプローチを選択する
テストはデザイン: テストを通して設計を考える
まとめ
TDDは「正しいものを正しくつくる」ための手法
テスト→実装→リファクタリングのサイクルを繰り返す
小さな一歩を積み重ねて開発を進める
テストを通して設計や仕様への理解を深められる
TDDを実践して、堅牢なソフトウェア開発を目指しましょう！