# korean_trip

## サービス概要

旅行プランを自分でカスタマイズして旅のしおりを作成できたり、おすすめスポットや実際に行った場所を投稿共有し、韓国旅行をより楽しく充実できるようサポートするサービスです

##　想定されるユーザー層

韓国の食や美容、Kpopアイドル等に興味がある20代〜30代の韓国旅行が好きな女性

## サービスコンセプト
【Why You?】
私はよく韓国旅行に行くのですが、海外ということもあり言語の壁や、土地勘わからず不安なことが多いです。
そこで、みんなが行ったことのあるお店やスポットなどを共有し合うことで少しでも旅行への不安が和らぐのではないかと考えました。
また、時間がなく一日のプランをきちんと決めずに旅行に行った際、道順などわからないことを調べたり現地の人に尋ねたりする時間が多くなり、限られた旅行の時間をかなり無駄にしてしまいました。
そう行った問題を解決するために、旅行のしおりの機能を思いつきました。旅行のしおりを作ることで１日のプラン(場所や時間など)を把握することができ、慣れない海外でも時間を無駄にせずに安心して楽しむことができると思ったからです。

【差別化・売りのポイント】
現在よく使われてる韓国旅行で使えるアプリに韓国内の飲食店や人気のスポットを探せるアプリがありますが、韓国製のアプリなので日本語の表示が間違っていたりきちんと翻訳できていなかったりと使いずらさを感じたので、日本人が使った時にわかりやすいアプリを作りたいと思いこのアプリを考案しました。

## 実装を予定している機能
### MVP
* 会員登録
* ログイン
* 投稿一覧
* 投稿登録
* 投稿詳細
* 投稿編集
* 投稿ブックマーク機能
* タグ機能
* 旅のしおり作成機能

### その後の機能
* 旅のしおり作成機能
* おすすめのプランなどの記事一覧
* Google Maps Platformを使って現在位置取得機能

### 利用する具体的な技術と高度な機能
Rails7
Ruby3
Hotwire
postgresql or Mysql
JavaScript
Bootstrap or tailwindcss
heroku or http://Fly.io or render
Google Maps Geolocation API
Google Maps Geocording API