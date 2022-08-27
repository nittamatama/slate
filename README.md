# slate

## 開発の動機
- なぜ必要なのか
  - slackの無料版の閲覧期間指定が設けられてしまったことにより、slackをノート・メモアプリとしての使い方ができなくなってしまったため
  - 「ノートアプリとしてslackを使用する」ということの便利さを感じていたため
- なぜそれが良いのか
  - 各ノートやメモの分野をチャンネルごとに分けることができる
  - スレッド形式のため、似たような内容をスレッド内にも小分類できる
  - マークダウンやコードスニペットが使用できる
  - すぐに立ち上げてメモすること（メッセージを送る感覚）ができる
  - 検索が直感的にすぐにできる
    - チャンネル単位で検索ができる
- どのような問題を解決できるのか
  - slackの有料プランを使用しなくてもよくなる
  - 既に存在するslackのデータを同じ形式のまま移行することができる
- どのような場面で役に立つのか
  - 業務中にメモやノートを取るとき
  - 会議中など、ある程度スピード感をもってノートをとりたいとき
  - 複数人で雑な共有ノートを持ちたいとき
- どのような人たちにとってメリットがあるのか
  - 今までslackをメモやノート機能として使用してきた人
  - 気軽にメモをとりたい人
  - でも共有もしたい人
- 今までのものと比べた違いの良さは何か
  - コードスニペットに色を付けられる
  - slackよりも少しだけ一般的なノートの機能に寄せる（タグとか）

## ターゲットの明確化

| ターゲット | 求められるもの                     | 備考 |
| ---------- | ---------------------------------- | ---- |
| ノート     | メモが投稿された状態を保持する     |      |
|            | メモが検索できる                   |      |
|            | 誰のメモか判別できる               |      |
|            | メモを投稿できる                   |      |
|            | ノートにスレッドを出せる |      |
| ユーザー   | ノートを投稿できる                 |      |
|            | 自分のノートを閲覧できる           |      |
|            | 許可した別ユーザーも閲覧できる     |      |
|            | 投稿したメモを削除できる           |      |
| チャンネル | ノートをメッセージごとに分類できる |      |
|            | チャンネルごとに検索ができる       |      |

## 機能の洗い出し
- ノート投稿機能
- ノート編集機能
- ノート削除機能
- ノート検索機能
- スレッド機能
- ユーザー登録機能
- 相互メッセージ投稿機能
- 投稿権限付与機能
- チャンネル分類機能
