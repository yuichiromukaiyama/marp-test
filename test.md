---
marp: true
theme: default
paginate: true
header: "Marpプレゼンテーション例"
footer: "Created by AI Assistant"
---

<!-- タイトルスライド -->
![bg left:40% 80%](https://marp.app/assets/marp.svg)

# **Marpプレゼンテーション例**

## 様々なパターンの紹介

---

<!-- 目次 -->
# 目次

1. 基本的な書式
2. 画像の使用
3. 背景画像
4. リストとテーブル
5. 数式
6. コードブロック
7. 自動スケーリング
8. テーマとスタイリング

---

<!-- 基本的な書式 -->
# 1. 基本的な書式

## 見出し

本文テキスト

*イタリック* と **太字**

[リンク](https://marp.app/)

> 引用文

---

<!-- 画像の使用 -->
# 2. 画像の使用

![width:300px](https://marp.app/assets/marp.svg)

![width:200px height:100px](https://marp.app/assets/marp.svg)

![w:100px h:100px](https://marp.app/assets/marp.svg)

---

<!-- 背景画像 -->
# 3. 背景画像

![bg](https://placehold.jp/500x500.png)

## 全面背景

---

![bg right:33%](https://placehold.jp/500x500.png)

# 背景画像（右寄せ）

- 左側にコンテンツ
- 右側に背景画像

---

<!-- リストとテーブル -->
# 4. リストとテーブル

- 箇条書き1
- 箇条書き2
  - ネストされた項目

1. 番号付きリスト1
2. 番号付きリスト2

| 列1 | 列2 | 列3 |
| --- | --- | --- |
| A   | B   | C   |
| D   | E   | F   |

---

<!-- 数式 -->
# 5. 数式

インライン数式: $E=mc^2$

ブロック数式:

$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

---

<!-- コードブロック -->
# 6. コードブロック

```python
def hello_world():
    print("Hello, Marp!")

hello_world()
```

---

<!-- 自動スケーリング -->
# 7. 自動スケーリング

<!-- 
  注: 一部のテーマでのみ動作します。
  長いコードブロックや数式が自動的に縮小されます。
-->

```python
def very_long_function_name_that_demonstrates_auto_scaling(param1, param2, param3, param4, param5):
    result = param1 + param2 + param3 + param4 + param5
    return result * 2
```

---

<!-- テーマとスタイリング -->
# 8. テーマとスタイリング

<style scoped>
h2 {
  color: #ff0000;
}
</style>

## この見出しは赤色です

通常の本文テキスト

---

<!-- フィット機能 -->
# <!--fit--> フィット機能のデモ

---

<!-- スピーカーノート -->
# スピーカーノート

このスライドにはノートがあります。

<!-- 
これはスピーカーノートです。
プレゼンテーションモードで表示されます。
-->

---

<!-- まとめ -->
# まとめ

- Marpは多様な機能を提供
- Markdownの簡潔さとプレゼンテーションの視覚的魅力を組み合わせる
- カスタマイズ性が高く、様々なニーズに対応可能

```

このプレゼンテーション例では、以下のMarpの主要機能を紹介しています：

1. 基本的なMarkdown書式
2. 画像の挿入と操作
3. 背景画像の使用
4. リストとテーブルの作成
5. 数式の表示
6. コードブロックの挿入
7. 自動スケーリング機能
8. テーマとカスタムCSSによるスタイリング
9. フィット機能によるテキストサイズの自動調整
10. スピーカーノートの追加

これらの例を参考に、Marpの機能を活用してプレゼンテーションを作成できます。必要に応じて、各スライドをカスタマイズしたり、内容を追加したりして、より充実したプレゼンテーションを作成してください。

Citations:
[1] https://gist.github.com/yhatt/a7d33a306a87ff634df7bb96aab058b5
[2] https://speakerdeck.com/yhatt/marp-basic-example
[3] https://qiita.com/tomoasleep/items/604107787d92dec4868e
[4] https://dev.to/andyhaskell/write-your-tech-talk-slides-rapidly-with-marp-2c7g
[5] https://qiita.com/e99h2121/items/79db6b7375ccbf3d3977
[6] https://zenn.dev/oyashiro846/articles/0deab8230432a5