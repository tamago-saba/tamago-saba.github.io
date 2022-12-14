---
title: 鯖主が最近作ったプラグイン
---

最近私が個人的に手伝っている、とある建築サーバーにて建築したり観光したりしてたのですが、色々やっているうちに良さげなプラグインのアイデアをいくつも思いついてしまい、勢いで色々作ってみたところ、そこの鯖民にも好評だったので、自分のサーバーの人たち向けにも使い方的なものを書こうと思います。
<!--more-->
とりあえず単発サーバーに入れておこうと思います。

## MyLocation

サーバー内の好きな地点を登録し、インベントリ風の画面をタッチすることでいつでもその地点にテレポートできます。遠くに建築したり頻繫に移動したりするときに便利。

- `/ml` - 地点一覧を表示する
- `/ml add 名前` - 地点を追加する
- `/ml remove 番号` - 地点を削除する

![MyLocation](https://cdn.discordapp.com/attachments/1055400526105284688/1055400526302421002/image.png)

ソースコードは[こちら](https://github.com/tsuoihito/MyLocation)。

## WorldEditLook

ワールドエディットの範囲選択を、ブロックに触れずに視点の先のブロックに対して実行できるようになります。わざわざブロックのそばまで移動しなくていいので少し楽になるかも。

![WorldEditLook](https://cdn.discordapp.com/attachments/860512759313072159/1006940455646277693/WorldEditRemote.gif)

ソースコードは[こちら](https://github.com/tsuoihito/WorldEditLook)。

## TeleCraft

視点の先のブロックがマーキングされ、そこの座標がアクションバーに表示されます。自分が移動しなくても座標がわかるので、ブロック間の長さを測るときなどはかなり楽になります。一個上で紹介してるWorldEditLookと組み合わせると遠隔範囲指定がさらに強力に。OptiFineの拡大表示 (Cキー) との組み合わせもオススメです。

![TeleCraft](https://cdn.discordapp.com/attachments/1055400890091175967/1055400890552553502/image-1.png)

## CommandStick

自分の好きなコマンドを木の棒に割り当てて、その棒を振るだけでコマンドを実行できます。どんなコマンドでも割り当てられるので可能性は無限大。棒の名前を金床で自分のわかりやすいものに変えても大丈夫です。

- `/cstick コマンド 引数1 引数2 ...` - コマンドを割り当てた棒を入手

### 割り当てるコマンド例

- `/cstick summon chicken` - 振るたびにニワトリを召喚する棒。連打すれば連続召喚も簡単にできます。
- `/cstick /paste` - ワールドエディットの`//paste`コマンドを実行する棒。大量にペーストしたいときに便利。`//undo`の棒もオススメです。
- `/cstick gamemode creative` - クリエイティブになれる棒。コマンドを打つのが少し大変なスマホ版とかだとかなり楽になるかも。
- `/cstick ml` - 一番上で紹介したMyLocationの地点一覧を表示する棒。機能を呼び出してる感があってコマンド棒の可能性を感じます。

![CommandStick](https://cdn.discordapp.com/attachments/1056536233033084929/1056536233251176489/image.png)

ソースコードは[こちら](https://github.com/tsuoihito/CommandStick)。
