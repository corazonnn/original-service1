# アプリ名
HALO(ハロ)
## 概要
- プログラミング初学者と対象とした日々の成果共有サービス。プログラミング学習を始めて55日目を迎える私自身がここまで来るのに一番苦労したことが今現在プログラミング学習している人はどんなアウトプットをしているのか、そもそも何を勉強しているのか、これらを聞くことのできる仲間の存在がいなかったことです。そのような経緯もあり「じゃあ、自分でプログラミング初学者向けのサービスを作ろう！」と思ったのがHALOを作ったきっかけです。このサービス公開以降はSNSを通じてプログラミング仲間を集め、朝活や日々のアウトプット報告を積極的に行って行きます。

## 機能一覧
|機能名|詳細
|-----|---|
|プロダクトのCRUD機能|プロダクトの新規作成、詳細、編集、削除ができます。|
|ユーザの新規登録/編集機能|ユーザーの新規登録、編集ができます。|
|プロダクトごとのコメント機能|多対多の関係。各プロダクトごとコメントができます。|
|画像ファイルのアップロード機能|アップロードした画像はユーザのアイコンとなります。アップロードする前はデフォルトが入っています。|
|ページネーション機能|kaminari|
|ログイン機能|session|
|いいね機能|多対多の関係。ユーザがプロダクトに対して「いいね」できます。|
|いいねのランキング表示機能|今まで登録されたプロダクトの中から言い値の多い５つを表示しています。|
|プロダクトの使用言語で検索機能|使用言語をしていることでその言語を用いたプロダクトのみ表示します。|
|チャット機能|朝活urlや日々の情報交換として使用します。|
|管理ユーザ登録機能|管理者として全ユーザーのプロダクトの監視が可能です。|
|管理ユーザログイン機能|管理者のみtrueとなるカラムを用意している。|
|レスポンシブ対応|HTML CSS Bootstrapを用いて実装しています。|
## 使用している技術一覧
|使用技術|詳細
|-----|---|
|開発言語|Ruby|
|サーバーサイドフレームワーク|Ruby on Rails|
|フロントエンド|HTML CSS Bootstrap|
|インフラ|Heroku|
|データベース・データストア|MySQL|
|画像ファイルアップロード|CarrieWave　Cloudinary|
|ログイン|session|
|単体テスト|RSpec|
|統合テスト|RSpec|

## これからやってみたいこと

- インフラにAWS
- 画像アップロードにS3



