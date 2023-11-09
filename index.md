---
layout: default
title: ホーム
image:
  path: /assets/img/tamago-saba.png
  height: 720
  width: 1280
  alt: たまご鯖
---

![top](/assets/img/top.png)

<p style="text-align: center;">
2種類のサバイバルサーバーでプレーしたり、運営主催のイベントに参加したり
</p>

## Address

- サーバーアドレス : `play.tamago-saba.com`
- ポート番号（統合版のみ） : `19132`

## Information

- [ルール](docs/rules.md)
- [サーバーの紹介](docs/servers.md)
- [プラグインの使い方](https://sites.google.com/view/tamago-saba/plugin-usage)
- [本サイトの更新履歴](https://github.com/tamago-saba/tamago-saba.github.io/commits/main)

## Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y/%m/%d" }}
    </li>
  {% endfor %}
</ul>

- [記事一覧](docs/posts.md)

## Links

- [Discord](https://discord.gg/eVGqDxrsmv)
- [Dynmap](https://map.tamago-saba.com)
- [Wiki](https://wiki.tamago-saba.com)
- [Japan Minecraft Servers](https://minecraft.jp/servers/play.tamago-saba.com)
- [GitHub](https://github.com/tamago-saba)
- [YouTube](https://www.youtube.com/channel/UCLyRcPT4LbzW6bTJ3bw2yjQ)
