# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|田中 穏識 (Yasunori Tanaka))|
|GitHub|[yanak](https://github.com/yanak)
|Blog|[CODING ECHO](https://blog.codingecho.com)|
|Twitter|[@yanak174](https://twitter.com/yanak174)|
|Qiita|[ytanaka](http://qiita.com/ytanaka)|
|Speakerdeck|[yanak](https://speakerdeck.com/yanak)|

## スキル

### 言語

#### プログラミング言語

#### 自然言語

|言語|備考|
|---|---|
|日本語|ネイティブ|
|英語|技術的な文章を8割程度読める程度。日常会話で簡単な意思疎通ができる。|

|言語|備考|
|---|---|
|Go|6ヶ月の経験|
|C#|6ヶ月の経験。Unityで使用|
|JavaScript|1.5年の経験。ES2015|
|Scala|1.5年の経験。Play frameworkでWeb APIが作れる|
|PHP|3年の経験|

### フレームワーク

#### Play framework (Scala)
- [ゲームプラットフォーム](https://games.yahoo.co.jp/gameplayer/about)の開発者向けゲーム管理Webアプリケーション

#### Reactjs, Redux
- [ゲームプラットフォーム](https://games.yahoo.co.jp/gameplayer/about)の開発者向けゲーム管理Webアプリケーション

#### Zend framework ベースのカスタマイズフレームワーク
- [フィーチャーフォンゲーム](http://jp.apps.gree.net/ja/23)

### その他

#### Docker
- [ゲームプラットフォーム](https://games.yahoo.co.jp/gameplayer/about)の開発者向けWebアプリケーションの開発環境から本番環境まで
- CIのテスト環境構築

#### Jenkins
- CI、CD

#### Keras
- カスタマーサポートの自動応答のためのテキスト分類

## 強み
- 周りを巻き込んで技術力を向上させること
- 業務改善や品質向上に取り組む意識を持つこと

## 興味があること(今後やりたいこと)
- 機械学習を使用した開発効率改善やビジネスへの適用

## 職務経歴

### 2013/04 - : 株式会社enish

職務: エンジニア

#### フィーチャーフォン向けゲームの運用開発: 2013/04 - 2014/10

アプリケーションエンジニアとしてゲームのフロントエンドとバックエンドの運用開発を経験しました。開発言語はPHPです。データストアはMySQL、memcachedを使用しました。ソースコード管理はSubversion、 Githubを使用してきました。

##### 担当業務

- フロントエンドの開発
- バックエンドのビジネスロジックの開発
- カスタマーサポート(不具合調査)

#### 社内MBaaS (Mobile Backend as a Service)の運用開発: 2014/11 - 2015/06

APIの設計開発を経験しました。開発言語はPHPです。使用したフレームワークはZend frameworkベースのカスタマイズされたものです。データストアはMySQL、memcachedです。開発環境はGithubです。テストがシナリオテストしかなくメンテナンスされていない状態だったため、DockerとPHPUnit、Jenkinsを使ってCI環境を作り直しました。PHPUnitのテストビジネスロジックや、DBの値、キャッシュの値をテストできるようになったため品質向上に繋がりました。

##### 担当業務

- API設計開発
- カスタマーサポート(不具合調査)
- CI環境改善

#### 社内MBaaS向けの管理Webアプリケーションの開発運用: 2015/07 - 2016/11

フロントエンドからバックエンドまでの設計開発を経験しました。開発言語はScala、JavaScriptです。使用したフレームワークはPlay Framework, Reactjsです。データストアはMySQL、memcachedです。開発環境はGithubです。ScalaやReactjsは初めての技術だったため、これらの技術を使ったWebアプリケーション開発のプロセスを学ぶことができました。また、JavaScript周辺の技術は変化が大きく多くのライブラリを使用したりライブラリに手を入れてしまうと、ライブラリの変更への対応でコストが増加してしまうことを理解しました。

##### 担当業務

- フロントエンド設計開発
- Web API設計開発
- CI環境の構築

#### チャットシステムの開発とMBaaSへのAPI追加: 2015/09 - 2016/03

[スマートフォンゲーム](http://12odins.com)向けに[Photon chat](https://www.photonengine.com/ja/chat)を使用したチャットシステムを構築するためのAPIを社内MBaaSに追加しました。また、Photonの死活監視用にReactjsとC#でWebアプリケーションを作成しました。使用した技術はC#, JavaScriptです。フレームワークはASP.NET、Reactjsです。インフラはAWS ELBとEC2です。

##### 担当業務

- APIの設計開発
- チャットシステムの設計開発
- 負荷テスト

#### ゲームプラットフォーム向けの管理Webアプリケーションの開発: 2016/12 - 2017/08

[ゲームプラットフォーム](https://games.yahoo.co.jp/gameplayer/about)の開発者向けゲーム管理Webアプリケーションを開発しました。Webアプリケーションのフロントエンドからバックエンドまでの設計開発と、CI、CD環境の構築、ログのモニタリングまで、サービスとして提供するまで全てを担当しました。使用した言語は、Scala、JavaScriptです。フレームワークはPlay framework、Reactjs、Reduxです。そのほかに使用した技術はDocker、fluentd、kibana(elasticsearch)です。

これまでの経験から、運用が長期化するとインフラ周りや使用するライブラリのバージョンが開発や本番環境で揃わなくなることがありました。そのため、このプロジェクトではDockerを使用してインフラや実行環境をコードで管理できるようにしました。

デプロイも今まで人の手で行われることが多く、オペレーションミスが発生する可能性があるため、JenkinsとDocker Swarmを使用して、デプロイを自動化しました。構成図のリンクを貼る。

- フロントエンド・バックエンド設計開発
- サービスアーキテクチャ設計
- インフラ設計
- テスト・リリース・運用

#### スマートフォンアプリの開発: 2017/09 - 2018/01

スマートフォンアプリケーションの開発としてサーバーサイドのWeb APIの開発とクライアントサイドとのつなぎこみ(Unity)と、iOSのIn-App Purchaseの実装とUnityとのつなぎこみを担当しました。使用した言語はC#、Go、Objective-Cです。使用したフレームワークはUnityです。全て初めて使用した技術であったため、Unityを使用したスマートフォンアプリケーションの一連の開発プロセスを身につけました。

##### 担当業務

- クライアントサイド(Unity)の開発
- Web APIの設計開発
- In-App Purchaseの実装

#### スマートフォンアプリの運用開発: 2018/02 -

サーバーサイドエンジニアとして[スマートフォンアプリ](https://keyakise.jp)のビジネスロジックの開発を担当しています。使用している言語はGoです。CIのテスト環境が構築されていないので、DockerとJenkins、EC2でテスト環境を構築しています。また、チームのサーバー品質向上のための取り組みを考案中です。

##### 担当業務

- サーバーサイド開発
- カスタマーサポート(不具合調査)

#### 業務外 Deep Learning 社内勉強会: 2017/02 -

Deep Learningの手法を理解するために勉強会を立ち上げました。

ゲームの開発プロセスの中で自動化できそうな部分が手動で設計されていたり、カスタマーサポートのプロセスに非効率な部分があると感じていたため、自動化のためにMachine Learningの手法を検討しました。いくつかプロトタイプ([1](https://blog.codingecho.com/2018/01/01/gan-ios-app/), [2](https://blog.codingecho.com/2018/03/25/lstmを使ってテキストの他クラス分類をする/))を作成して社内に向けて説明することで、Machine Learningを使った自動化の有用性を社内に示すことができました。その結果として、Machine Learningを使ったカスタマーサポートの自動返答の設計開発を担当させてもらえることになりました。

## 登壇歴

|Date|Event|Slide|
|---|---|---|
|2018/03/31|有志勉強会第4回目|[再帰型ニューラルネットを用いたCSの返答自動化の検討](https://speakerdeck.com/yanak/zai-gui-xing-niyurarunetutowoyong-itacsfalsefan-da-zi-dong-hua-falsejian-tao)|
|2017/12/17|有志勉強会第2回目|[CoreMLを使って手書き文字を出力するAppを作る](https://speakerdeck.com/yanak/coremlwoshi-tuteshou-shu-kiwen-zi-wochu-li-suruappwozuo-ru)|
|2017/11/12|有志勉強会1回目|[みんなが使えるGANを作る](https://speakerdeck.com/yanak/minnagashi-eruganwozuo-ru)
