---
layout: default
title: ホーム
image:
  path: /assets/img/tamago-saba.png
  height: 720
  width: 1280
  alt: たまご鯖
---

![image](https://cdn.discordapp.com/attachments/962216466076291092/1010557165787943023/2022-08-18_12.27.41.png)

<p style="text-align: center;">
2種類のサバイバルサーバーでプレーしたり、運営主催のイベントに参加したり
</p>

## Address

- サーバーアドレス : `play.tamago-saba.com`
- ポート番号（統合版のみ） : `19132`

## Information

- [ルール](docs/rules.md)
- [サーバーの紹介](docs/servers.md)
- [プラグインの使い方](https://sites.google.com/view/tamago-saba/plugin-usage){:target="_blank"}
- [本サイトの更新履歴](https://github.com/tamago-saba/tamago-saba.github.io/commits/main){:target="_blank"}

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

- [Discord](https://discord.gg/eVGqDxrsmv){:target="_blank"}
- [Dynmap](https://map.tamago-saba.com){:target="_blank"}
- [Wiki](https://wiki.tamago-saba.com){:target="_blank"}
- [Japan Minecraft Servers](https://minecraft.jp/servers/play.tamago-saba.com){:target="_blank"}
- [GitHub](https://github.com/tamago-saba){:target="_blank"}
- [YouTube](https://www.youtube.com/channel/UCLyRcPT4LbzW6bTJ3bw2yjQ){:target="_blank"}
