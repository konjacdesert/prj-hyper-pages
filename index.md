---
layout: home
permalink: /
---

# 殴りロボ2(仮)資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。
巨大人型メカに乗って敵機をしばきましょう！

## このサイトの説明
ここは開発用の資料が置かれています。
ゲームに関する情報は大体ここにあるはずです。

## 最終更新
{{ site.time }}

## 管理者
蒟蒻砂漠([Twitter](https://x.com/konjacdesert))

## アクセス
* ~~[リリース版]()~~
    * 普通に遊ぶならこちら
* ~~[トライアル版]()~~
    * 試験的な機能を試すならこちら

## 遊び方
{% for pagehowto in site.howto %}
* [{{ pagehowto.title }}]({{ site.baseurl }}{{ pagehowto.url }})
{% endfor %}

## お知らせ
{% for pagenotices in site.categories.notices %}
* [{{ pagenotices.title }}]({{ site.baseurl }}{{ pagenotices.url }})
{% endfor %}

## アップデート
{% for pageupdate in site.categories.updates %}
* [{{ pageupdate.title }}]({{ site.baseurl }}{{ pageupdate.url }})
{% endfor %}

## TIPS
{% for pagetips in site.tips %}
* [{{ pagetips.title }}]({{ site.baseurl }}{{ pagetips.url }})
{% endfor %}

***

[.](./_pages/specs.md)