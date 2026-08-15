# SONEANDO

Live Cuban son and salsa in Tokyo — Roppongi and Hiroo, every month.
東京で本場のキューバ音楽を演奏しているバンドの告知サイト。

https://soneando.github.io/

## 日程の更新

`index.html` 末尾の `SHOWS` 配列に追記する。過去の日程は消してよい。
`price` は数値で必ず入れる（構造化データが参照するため）。

```js
{ date:"2026-09-23", open:"18:00", start:"19:15",
  venue:"All of Me Club", area:"六本木 / Roppongi",
  title:"Cuba Night with Soneando",
  charge:"¥4,000 ＋ 2オーダー", price:4000,
  sets:"19:15 / 20:30 / 21:45",
  map:"https://www.google.com/maps/search/?api=1&query=..." },
```
