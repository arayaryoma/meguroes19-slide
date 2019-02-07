## Temporal について

@arayaryoma

2019-02-07 #meguroes

---

### 自己紹介

![](assets/profile-image.png) <!-- .element height="200px"-->

- <i class="fas fa-user"></i> あらや/Ryoma Abe
- <i class="fas fa-building"></i> 合同会社ヘマタイト/フリーランス
- <i class="fab fa-twitter"></i> [@arayaryoma](https://twitter.com/arayaryoma)
- <i class="fas fa-laptop"></i> JavaScript/TypeScript/Go/Kotlin 好き
- <i class="fab fa-js-square"></i> Angular/React/ReactNative/Next.js

---

### Temporal とは

- ECMAScript に出されている proposal の 1 つ(Stage2)
- 一言でいうと`Date`よりも日付・時間を扱いやすくするためのもの
- Microsoft の方 3 名・Bloomberg の方 1 名が Champion

---

### なぜ Temporal なのか

## JavaScript の Date object が扱いづらい

#### Date の問題点

- Date object がタイムゾーンをサポートしていない
- parser が貧弱かつ無効な date format 等について標準化されていない
- mutable である
- Date の計算が扱いづらい
- グレゴリオ暦以外のカレンダーがサポートされていない

<p style="font-size: 0.5em">[https://maggiepint.com/2017/04/09/fixing-javascript-date-getting-started/](https://maggiepint.com/2017/04/09/fixing-javascript-date-getting-started/)より</p>
