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