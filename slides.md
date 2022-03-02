---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  Presentation slides for my profile.
  
  Learn more at [Sli.dev](https://sli.dev)
---

# My Profile

Presentation slides with slidev

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->


---

# 簡単な略歴

- 📝 **Name** - 石田　悠（いしだ　ゆう）
  - **Twitter** - <a href="https://twitter.com/ishiyu">@ishiyu</a>
  - **Github** - <a href="https://github.com/ishiyu">@ishiyu</a>
- 🤹 **学歴**
  - 2005 和歌山大学 システム工学部 卒業
    - 精密物質学科（有機化学専攻）
- 👨‍💼 **職歴**
  - 2005/4  株式会社ジェノア入社
  - 2011/10 ラクス株式会社入社
  - 2014/6  株式会社インゲージ入社

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>


---

# 職歴詳細

- 株式会社ジェノア
  - 派遣業務で eo 光（現・OPTAGE）の料金計算システムを開発・運用
  - Java 1.4系とC言語を触っていた
  - サービスの多さと２段階の従量課金の計算にめっちゃ苦労した
  - 東日本大震災とともに倒産した
- 株式会社ラクス
  - 和田さん、永田さんとともにアメリカ市場向けのSaaSサービスを構築
  - サービスのデザインもここでやりはじめた


---

# 職歴詳細

- 株式会社インゲージ（現在）
  - 和田さん、永田さんと3人で創業
  - ここから Ruby を触るように
  - Re:lation では以下を担当
    - Web API 設計
    - データベース設計
    - 画面デザイン
    - WebSocket (socket.io) サーバの構築・導入
    - RoR の実装
    - フロントエンドフレームワーク（angularjs, vuejs）の導入


---
layout: image-right
image: https://resources.jetbrains.com/storage/products/rubymine/img/meta/preview.png
---

# 現在の開発環境とか

## <a href="https://www.jetbrains.com/ja-jp/ruby/">RubyMine</a>
<br>
<br>

- すごく便利だけど VS Code が当たり前になっていて、ちょっと肩身が狭い
- そもそもキチンと比較してないので、どっちがどのように便利か把握できてない
  - 誰か勉強会開いてプリーズ（ひとまかせ）
- コードのフォントは <a href="https://fonts.google.com/specimen/Source+Code+Pro">Source Code Pro</a> がスキ
- 日本語フォントはブレブレ
  - 今は Hackgen だったり Source Code Han Jp だったり


---
layout: image-right-half
image: https://www.alfredapp.com/media/logo4.png
---

# 現在の開発環境とか

## <a href="https://www.alfredapp.com/">Alfred</a>
<br>
<br>

- spotlight + α みたいなツール
- amazon, google を直接検索できたりとかする
- caniuse も検索できたりする
- base64 encode/decode
- github も検索できるようにしてるけど使ってない
- ただ色々出来すぎて、セットアップは大変

---

# 現在の開発環境とか

## その他
- coteditor (テキストエディタ)
  - 何より軽い。便利
- figma (デザインツール)
  - デザインする上で必須になってきた
  - 共有する分には無料なのがありがたい (readonly)
- Homebrew
  - PC を新たにセットアップした際に、今更ながら便利さに感動
  - Brewfile で一発でインストールできて楽

---
layout: image-right
image: images/gcal.png
---

# 現在の開発環境とか (2022/3追記)

## その他
- chrome のショートカット作成
  - electron チックなアプリとして立ち上げれるようになる
  - ブラウザとは別に開くので alfred で一発で見れる
  - 石田は google calendar をこれで開いてる
  - ちなみに github は動きがおかしくなるので危ないです

---

# プライベート

## カレー
- 店に行くのも作るのも好きです 
- 作る場合はスパイスから作ってます。
- よく使うのはカルダモン、スターアニス、シナモン、クローブとか
## コーヒー
- 創業の始めの頃から、会社にミルを持ってきてます
- 浅煎り〜深煎りまで何でも好きです
- 最近、嫌気性発酵の豆が話題で飲んでみたいけど、ボツリヌス菌が怖くて飲めてない
  - 分かってないだけかもしれないけど

---

# 2021/4 追記

## DIY
- 最近引っ越した家の収納が少ないので自分で作ってます
  - 木やパイプのラック作ったり
  - カーテンレール取り付けたり
  - カーテンボックス作ったり
- 2022/3現在、ほとんどしなくなりました。。。

---
layout: image-right
image: https://booth.pximg.net/56590260-22c8-42eb-b945-c567e17785ca/i/1644450/98a08b66-a2de-4998-8570-329cb9161e12_base_resized.jpg
---

# 2022/3 追記

## 自作キーボード作りました
- caravelle-ble
- しっくり来る keymap を決めるのに半年ぐらいかかりました
- 最近は、もう一つ欲しいなと物欲センサーが鳴ってます

---
layout: image-right
image: ./images/baby-3months.JPG
---

# 2022/3 追記

- 2021/11 に女の子が生まれました
  - 現在、家の中では彼女中心に回ってます。。。

---

# slidev

ということで、今回は <a href="https://sli.dev/">slidev</a> をつかってみました。


---

# slidev 使ってみた感想

- よくある markdown でつくるスライド
- vue/vite base というのが珍しい気がする（vueファイルがそのまま作れる）
- セットアップは簡単
  - 今回の自己紹介の作成時間は全部で1時間ぐらい
- github にそのまま残せて便利
- まだ public beta だがソースは大きくないので全然読める・使える

---
