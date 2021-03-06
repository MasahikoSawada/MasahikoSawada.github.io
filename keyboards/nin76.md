---
layout: post
title: 自作キーボード Nin76
permalink: /keyboards/nin76.html
---

~~試作機を[BOOTH](https://masahi-shop.booth.pm/items/1370844)にて頒布中です。~~ 現在売り切れ中です(2019/05/30)。

<div align="center">
<img src="/images/nin76/top.jpg">
</div>

自作キーボード「Nin76」の紹介です。

# コンセプト

左右分割キーボードに気軽に挑戦できるように設計したキーボードです。

最近様々な自作キーボードが開発されていて、僕も使いたいと思ったのですが以下のような悩みがありました。

* **自作キーボードはUS配列のものが多い**
  * 普段JIS配列を使っていてそこからの移行コストが高い（頭が切り換えられない＋サーバルームでの作業等、普段と異る環境でタイピングすることがある）
* **60%キーボード、40%キーボードはキーが少なく、現在使っているキーボードからの変更が大きい**
  * やはり頭の切り替えができない
* **教科書通りの綺麗なタイピングをしていない**
  * 例えば「T」は右手でタイプする時があるので、左右分離にするとやりづらい
  * タイピング癖の矯正には良いかもしれないけど

そして、JIS配列を使っている人でもできるだけ移行コストが低い左右分離キーボードが欲しくなり作りました。

# 特徴

* **Row Staggered**
  * 通常のキーボードと同じように使える
* **日本語（JIS）配列**
  * 日本語配列ユーザにも優しい
* **中央に重複キーあり**
  * 分割していないキーボードと同じようにタイピングできます
* **左右分割**
  * 肩凝り予防！
* **側面につけるパーツがある**
  * ホコリが入りにくいです
* **配列は自由にカスタマイズできる**
  * qmk_firmwareを使っていて、自由にカスタマイズが可能です
* フルキーボード（108キー）のキーキャップがそのまま使用可能（Cherry MXのスイッチのみ対応）

# キーレイアウト

両手の中央部分に余分なキー（黄色のキー）があるので、それを使ってキーボードの中央付近のキー（「T」、「Y」、「G」など）を重複させても良いですし、別のキーを割り当てる事も可能です。

<div align="center">
<img src="/images/nin76/layout_jis.png">
</div>

これは自分で使っている配列です。

<div align="center">
<img src="/images/nin76/layout_own.png">
</div>

# 側面のパーツ

Nin76にはキーボード側面を覆うパーツが付いていて、キーボード内部へのゴミ、ほこりの侵入を防ぎます。

<div align="center">
<img src="/images/nin76/hight.jpg">
</div>

側面のパーツは少し内側にあるため、キーボードが掴みやすくなっています。

<div align="center">
<img src="/images/nin76/hekomi.jpg">
</div>

# 組み立て方法

<div align="center">
<iframe src="//slides.com/masahikosawada/nin76/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

# 組み立てに必要なもの

|パーツ名|個数|同梱|備考|
|--------|----|----|----|
|PCB基板（右手用）|1枚|○||
|PCB基板（左手用）|1枚|○||
|ケース（右手用）|1個|○|全部で7個（上下＋側面5個)のパーツからできています|
|ケース（左手用）|1個|○|全部で7個（上下＋側面5個)のパーツからできています|
|ダイオード|76個+予備|○||
|ネジ||○||
|スペーサ||○||
|TRRSジャック|2個|○||
|スタビライザー|4個|○|
|ProMicro|2個|○|希望があれば開封し、ファームウェア書き込み済みの状態でお渡しします|
|タクトスイッチ|1個|○|リセットスイッチ用です|
|ゴム足(大)|4個|○|滑り止め、高さ調整用です|
|ゴム足(小)|4個|○|滑り止め、高さ調整用です|
|キースイッチ(Cherry MX)|76個|×||
|キーキャップ|76個|×||
|TRRSケーブル|1個|×|遊舎工房さんにも[売ってます](https://yushakobo.jp/shop/trrs_cable/)|
|USB Micro B|1個|×|データ転送に対応しているもの|

上記の他、パーツの取り付け等に半田ごてが、ケースの組み立てにドライバーが必要になります。

## キースイッチ

Cherry MXのキーが76個必要です。キースイッチは、[遊舎工房](https://yushakobo.jp/product-category/switches/)さんが色々な種類のキースイッチを販売しています。

## キーキャップ

Nin76に必要なキーキャップです。

|サイズ|個数|
|------|----|
|1 x 1|65個|
|1.25 x 1|5個|
|1.5 x 1|1個|
|1.75 x 1|1個|
|2 x 1|2個|
|2.25 x 1|1個|
|エンターキー用(L字のやつ)|1個|

[Majestouch 日本語108キーの交換用キーキャップセット](https://www.diatec.co.jp/shop/det.php?prod_c=3716)に入っているキーも使えます。

<div align="center">
<img src="/images/nin76/black.jpg">
</div>

# ギャラリー

<div align="center">
<img src="/images/nin76/leftside.png">
</div>

<div align="center">
<img src="/images/nin76/incline.png">
</div>

<div align="center">
<img src="/images/nin76/right_hand_close.jpg">
</div>

<div align="center">
<img src="/images/nin76/left_hand_close.jpg">
</div>
