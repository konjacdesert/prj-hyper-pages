---
title: 仕様メモ
layout: default
permalink: /specs/
---

# {{ page.title }}

このページに乗っている情報は実際にゲームに実装されていない仮のものも含みます。

{% for pagespecs in site.specs %}
* [{{ pagespecs.title }}]({{ site.baseurl }}{{ pagespecs.url }})
{% endfor %}