# ショッピングカートの詩

## 考えていること

まず考えていることを言葉にします。

* ショッピングカートは道具だ。ショッピングカートを見るために訪問する人はいない。また、初めてショッピングカートを見るという人も少ない。ショッピングカートに求められているものは、ショッピングカートと聞いて想像するものだ。ショッピングカートのデザインに求められていることとは、ボタンが押せそうに見えることや、テキストフォームが文字を入力できそうに見えることだ。
* ショッピングカートはすべてのショップで利用できるものだから、年齢・性別・デバイスの操作に慣れているかどうかを絞ることができない。また、あらゆるジャンルの商品の購入に利用される可能性がある。
* iOS や Android のデザインルールが陰影の少ない平面的なデザインの UI を採用している以上、ブラウザの UI も OS のデザインに準じるので、ブラウザの内容であるショッピングカートの UI も OS やブラウザの世界観を継承するべきだ。しかし、ウェブページは OS を問わずに表示できるものだから、iOS や Android の UI をコピーしてしまうと、コピーした OS 以外のデバイスから見たときに違和感が生まれてしまう。
* ショッピングカートは今後も継続的に改善されるし機能が追加されることがわかっているから、ショッピングカートをデザインをする人もひとりではなく複数の人が関わることが考えられる。厳密なルールを守らないと成立しないものではなく、柔軟に変更に耐えうるものであるべきだし、予想できるような要素はあらかじめ用意されているべきだ。
* 買い物をすることは、楽しいことだ。買い物をすることは、作業ではないはずだ。実店舗で買い物をするときのことを思い出してみると、家を出る、電車に乗る、お店に入る、商品を手に取る、買ったあとどういうふうに使うか考える、ちょっと悩んで店を出てまた戻ってきたりして、レジに持っていく、店員さんにお金を渡して、袋にいれてもらって、電車で帰って、家で箱をあける。ショッピングカートが提供するのはそのレジの部分だけだけど、インターネットで買い物をすることだって、同じように体験であるべきだ。

## 整理する

わたしたちが作りたいショッピングカートってどういうもの？

* できるだけ普通のもの。普通とは、見たことがあるもの。誰もが使ったことがあるもの。
* 押せるものが押せそうに見えるもの。書けるものが書けそうに見えるもの。
  * それは見た目だけではなく、触れたときリアクションがあることや、触れそうなところへ促してくれることによっても補えるのかもしれない。
* 特定のイメージが生まれないもの。商品のイメージと相反しないもの。ショップのページから遷移して違和感がないもの。
* OS が採用している世界観とつながるもの。特定の OS の世界観に依存しないもの。
* 開発した人以外が手を加えても壊れないもの。開発してない人が手を加えやすいもの。
  * 例えば、将来追加されてもおかしくない要素は、いま使わなくても用意しておいてもいいのかもしれない。
* 入力する作業が、作業を超えて体験になるもの。

## 具体的に

そんなショッピングカートを作るには、どうすればいいんだろう？

* 普通のものとは何か？
  * 他社のショッピングカートを調べて比べたうえで、共通するものを探してみよう。
* 押せるものが押せそうに見えるものとは何か？
  * どの程度の陰影があれば押せそうだと思えるのか比べてみよう。
  * どんなリアクションがあれば押せそうだと思えるのか考えてみよう。
* 特定のイメージが生まれないものとは何か？
  * あらゆるショップで違和感のない配色を考えてみよう。
  * カスタマイズするとしたら何をカスタマイズさせるか考えてみよう。
* OS が採用している世界観とつながるものとは何か？
  * OS が公表しているデザインルールを調べてみよう。
  * OS が公表しているデザインルールを比べたうえで、共通するものを探してみよう。
* 開発した人以外が手を加えても壊れないものとは何か？
* 体験とは何か？

## 例えば

* 押せるものには影がついている。書けるものはくぼんでいる。
* 影はささやかで、広がらずにシャープだ。
* グラデーションがなく、要素の境界がはっきりしている。
* アイコンが OS が提供しているものと同じ形をしている。
* ショップページにあるものがショッピングカートにもある。
  * ショップのロゴとか、背景色とか。
* 楽しさを演出する工夫がある。
  * 数字が飛び跳ねたりするアニメーションがある。

----

この詩は、第4回ペパボテックカンファレンスで発表した「ウェブサービスを開発するために詩を書いた話」の資料です。

http://eventdots.jp/event/573086

## Usage

* チームみんなで読む
* 迷ったときに方向性を確認する

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
