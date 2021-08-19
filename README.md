# 職務経歴書

- 氏名: 寺本 真之（てらもと しんじ） | 1988年12月27日

## 概要

- フロントエンド開発を主軸とてフロントエンドからサーバーサイドまで一気通貫したWebアプリケーション開発をしています。
- フロントエンドはモダンJavaScript・Reactの開発経験(実務)5年間、サーバサイドはNode.js/Express.js/mongoDBの開発経験(実務)3年間、Node.js/Firebaseの開発経験(実務)2年間、直近では3年間はフロントエンド・サーバーサイドをTypeScriptを使って開発しております。
- 自社開発、受託開発のどちらの経験もあり、どちらも仕様策定、新規開発から運用まで一気通貫して対応しています。自社サービスは最長8年(フルリプレース含み)、受託開発は最長5年の運用サービスがあります。
- チームメンバーは変則的になり、自社エンジニアは私しかおりませんが、インドのオフショア開発会社と契約して8年になり、私は最初の3年間はマネジメント中心、直近5年間はテックリードとして技術面で主導しております。
- 2013年からの3年間は初の自社サービスであるフォトブックサービスの立ち上げを担当、開発の業務部分としてはブリッジSEに近い立場でインドチームと共に開発を進めました。(AWS上でのインフラ整備やBitbucketによるバージョン管理の導入支援などは行いましたが、この期間のコーディングはインド側で行なっておりました。)

## 職歴概要

#### ハピログ株式会社: 2018年7月～現在
#### ピアズ・マネジメント株式会社: 2013年1月～2018年6月 (2012年8月よりインターン)

 - 事業の主体を事業会社に移行したことに伴う転籍であるため、仕事内容や開発体制等に実体に変更はありません。

## 会社概要

 - 事業内容: 自社Webサービス、受託開発、コンサルティング、マーケティング支援
 - 従業員数: 3名 (エンジニア内1名: 本人)

## 開発体制

 - リードエンジニア: 1名(本人: 2016年〜現在)
 - プロジェクトマネージャー: 1名(本人: 2013年〜2015年)

#### インドのラボ型オフショア開発企業
   - マネージャー: 1名
   - エンジニア: 3名 (最大７名、最小1名)
   - 期間: 2013年1月～現在 
     - 価値観や職業観の違いからマネジメントは大変な苦労がありました。様々な施策を経て、最終的にはタスクを細かく分割したり、レガシープロジェクトを最新のスタックに変更する部分を中心にアサインすることである一定の成果を安定的に出せるようになりました。

### 役割分担

   - 基本的に全メンバーがフロントエンド、バックエンド共に担当しております。インフラ面に関しましてはセキュリティの関係上、私が全面的に担当しております。
   - 本人: 主に新規開発、アーキテクチャ設計、新技術の導入、コードレビュー、タスク管理を主に担当しております

## 代表的なプロジェクト概要

###### *開発チーム規模は状況により柔軟に複数のプロジェクト間を行き来しているため目安になります。


### 【受託開発】 化学業界の総合メディアサイト (https://chematels.com)

#### 概要

AWSのEC2にnginx、node.jsを構築していた開発環境をフロントエンド面ではJamstack化、サーバーサイドをサーバーレス、フルマネージドを主軸とする構成にしました。主な変更理由は管理するプロジェクトの増加による煩雑化とコストダウン、Developer Experience向上を意図しました。

- 期間: 2019年12月〜現在


#### 主な取り組み

| # | 期間 | 内容 | 開発チーム | 
| --- | --- | --- | --- |
| 1 | 2019/12<br />〜<br />2020/1 | 開発基盤の技術検証を行い、フロントエンドはJamstackをベースにヘッドレスCMSのGraphCMSとBaaS(Cloud Firestore)をVercelにデプロイ、バックエンドはCloud Functions、アドミン系はCloud Runに構築、データ分析環境はFirebase Analytics、Firebase ExportsとFivetranの処理によりBigQueryに集める構成にスタックの導入することを決めました。データパイプライン等の導入は断念し、GraphCMS・AlgoliaのデータはFirebase FunctionsのpubsubでFirestoreにデータ追加した後、Firebase Exportsにより自動でBigQueryにデータエクスポートする構成にしました。 | 1名 (本人)
| 2 | 2019/2<br />〜<br />2020/6 | 時事通信社のRSS取得とGraphCMSのバックアップ部分を除く、大部分のフロントエンドとバックエンドの開発を担当しました。 | 2名 (本人含む)
| 3 | 2021/2<br />〜<br />現在 | 運営中・新規プロジェクトを横断してものづくり産業に関わる企業様が利用できるSaaSサービス開発中しております。*半育休中しながらの開発期間を含みます。 | 1名 (本人含む)
| |


- 使用技術
  - 使用言語: TypeScript、Node.js
  - フロントエンド: React, Next.js, GraphQL、Material-UI, Jest, Cypress
  - バックエンド: Cloud Firestore
  - 開発環境：GCP(Cloud Run, BigQuery, Cloud Functions), Github Actions,


### 【受託開発】 プラスチック成形材料データベース (https://plabase.com)

- 期間: 2015年10月〜

#### 概要

納品のない受託開発として構想段階から開発・運営まで一括で請負サービスをリリースさせる。複雑な成形材料の情報を電子化・データベース化する方法、Webサービスとしての機能を顧客と二人三脚で考え実現させる。その後も、2017年にサイトトラフィックの改善のNext.jsによるSSRへの移行、2018年に総合メディアサイト化、現在プラスチック成形材料データベース・総合メディアサイトして月間10万PVを達成し、プラスチック業界のマーケティングツールとしての地位を確立しました。


#### 主な取り組み

| # | 期間 | 内容 | 開発チーム | 
| --- | --- | --- | --- |
| 1 | 2015/10<br />〜<br />2015/11 | 成形材料に適した検索方法を考え、jQueryを用いて検索ページのプロトタイプの作成しました。 | 1名 (本人)
| 2 | 2015/12<br />〜<br />2016/3 | 自社・受託開発を含め諸事情により技術スタックの刷新を決め、新技術スタックの選定、シングルページアプリケーションによるフロントエンドとバックエンドの切り離し、JavaScriptを中心とするエコシステムの技術(JavaScript(ES2015)/Node.js/React/Redux/MongoDB)を中心とすることを決めました。 | 1名 (本人) |　
| 3 | 2016/4<br />〜<br />2016/11 | 新技術スタックの選定時に技術スタックの習熟をしていたため当初はメンバーの習熟支援を中心に行いました。メンバー間のJavaScriptのコードレベルの統一に苦労したため、基本的にAirbnb JavaScript Style Guideのgoodパターンに沿うように徹底しました。その他、フロントエンド・サーバーサイド面の開発を行いました | 4名 (本人含む)  | 
| 4 | 2016/4<br />〜<br />2016/11 | 新技術スタックの選定時に技術スタックの習熟をしていたため当初はメンバーの習熟支援を中心に行いました。メンバー間のJavaScriptのコードレベルの統一に苦労したため、基本的にAirbnb JavaScript Style Guideのgoodパターンに沿うように徹底しました。その他、フロントエンド・サーバーサイド面の開発を行いました | 4名 (本人含む)  | 
| 5 | 2017/6<br />〜<br />2017/9 | SEO強化に伴いシングルページアプリケーションからサーバーサイドレンダリングへの移行を実施しました。当初はwebpack-isomorphic-toolsはによる実装を試みましたが安定化に失敗、その後、Next.jsを導入してSSR化に成功しました。この時の経験から、ビルド環境はレールに乗るのが好ましいと考え、Next.jsをフロントエンドの開発の中心にすることにしました。 | 1名 (本人)
| 6 | 2017/10<br />〜<br />2018/2 | メディア化(ヘッドレスCMSとしてしてWordpressの導入・市況状況)の追加とモバイルWeb版(レスポンシブデザインではなく独立したモバイルWeb版)の導入をしました。私はモバイルWeb版を中心に開発をしました。 | 2名 (本人含む)
| |


- 使用技術
  - 使用言語: JavaScript(ES2015)、Node.js
  - フロントエンド: React, React-Router → Next.js, Redux (Redux-Thunk)、Material-UI, Jest
  - バックエンド: Express, MongoDB, Redis
  - 開発環境：AWS(EC2, S3, CloudFront, Route53), Bitbucket


### 【自社開発】 ご当地アイドル公式iOSアプリ (https://applion.jp/iphone/app/1001901462/)

- 期間: 2015年2月〜2016年5月

#### 概要

2014年から学習中だったSwift・iOS学習を自社ビジネスに繋げたいと考え、当時地下アイドルブームだった市場情勢を活用し、アプリ × 地下アイドルのビジネス化を企画しました。まず、身近な富山県のご当地アイドルの公式アプリ化を目標とすることにし、ご当地アイドルのプロデューサにイベント後に突撃営業をして、公式アプリの権利を獲得しました。

| # | 期間 | 内容 | 開発チーム |
| --- | --- | --- | --- |
| 1 | 2015/2<br />〜<br />2015/6 | ゲームパートのドット絵とロゴのデザインを除いて、アプリ開発、リリース作業等のすべての開発面を担当しました。Swift/iOSの学習は主にraywenderlich.comから得ました。 | 1名 (本人)
| |

- 使用技術
  - 使用言語: Swift



## スキル

### 言語
  - JavaScript: 6年
    - JavaScriptは基本的にES2015以降の言語仕様ベースにしております。
  - TypeScript: 3年
    - 現在はフロントエンドとバックエンド(Node.js)共にTypeScriptをベースに開発をしております。
    - 2018年以降の新規アプリケーションはフロントエンド・サーバーサイドともにTypeScriptを選択しています
  - Swift: 1年
    - Swift 1.0がリリースされた2014年からアプリを2015年にiOSアプリを一本リリースするまで利用しておりました。リリース以後はJavsScriptをベースとしたWebアプリケーション開発の学習に主軸を移行しました。
  
### フレームワーク、ライブラリー
  - React: 5年
    - ReactはプレーンなJavaScriptで書くことができ、タグの中にフレームワーク特有のシグナルで条件分岐や繰り返しがないところに当初は魅力を感じ使いはじめました。その後は豊富なエコシステムやReact hooksのシンプルなAPIに魅力感じております。
    - サスペンスを使ったデータ取得と取得中のスケルトン表示はエンドユーザーへの高いユーザーエクスぺリンスの提供に好ましいと考え積極的に利用しております。
  - Next.js: 4年
    - Next.js 2.0の頃から利用を開始しました。動的なルーティングやApp Component(_document.js, _app.js)がまだない頃でしたが、webpackの負担軽減やSSRに魅力を感じ導入を決めました。
    - 直近では、Next.js 9.4のIncremental Static Regenerationが魅力的な機能と思っております。特にメディアサイトをJamstack
  - Redux
    - ReduxはStoreでデータを一元管理でき、またRedux DevToolsで時系列でデータ更新が追えて、尚且つデータ状態がビジュアルイメージとしてもみれることに魅力を感じました。そのため、バックエンドのDBのように考え、フロントデータは基本的にすべてStoreに入れて情報を出し入れして使う設計にしていました。バックエンドをmongoDB、､データはREST APIでフロントエンドにデータを返していたので、データ構造がフロントエンドとバックエンドでほとんど同じで、データの流れを把握し易かったことも関係があったと思います。
    - しかし、すべてのデータをReduxに入れていたため、複数のディレクトリーに分かれているactions/constants/reducersを大量に書いており、Redux疲れを発生させてしまいました。2018年頃からページを跨ぐ状態管理を必要としないデータはReact hooks、REST APIの呼び出しは、通常のFetchやGraphQLなどで置き換えを開始しました。
  - Recoil
    - 今のところ小規模にしか使用経験がありませんが、React hooksに近しいAPI設計を魅力に感じ、今後積極的に利用したい技術です。
    - OSSは凄いエンジニアが行うものであると躊躇しており、例えプロジェクトで必要な変更が発生したときはFormして一部変更して本体が修正されるまでそっちを使うことが多かったです。しかし、今回の転職活動で視野が少し広がり、RecoilにPull Requestを投げ、マージされました。変更内容は一行のみの大した内容ではありませんが、今回の件で心理的な障壁が下がったので、今後積極的にOSS活動ができればとおもっております。
  - GraphQL
    - Apollo Client
    - urql
      - GraphQLは型の自動生成でサーバーサイドとの通信が明示的になるために好みます。
      - GraphQLの導入前に一時的に一部のREST APIに対してSwaggerの試みましたが、TypeScriptとの導入前かつ実装済みのREST APIに対してSwaggerの記述になったので、負担の割にメリットを感じられなかったために導入を断念したことがあります。
    - TypeScriptの自動生成は当初、Apollo codegenを利用しておりましたが、GraphQL Code GeneratorでuseQueryをラッパーしたコードを自動生成をすることを知り、useQueryにTypesを付与していた時よりもスッキリ書くことができるため移行をしました。
  - Material UI
    - UIコンポーネントフレームワークを使ってのWebアプリケーション開発を好みます。UIコンポーネントにより素早く、コードの読みやすさ、長期的な保守運営するのは必須であると考えています。
    - その中で、Material UIを選択した理由は2016年当時では最も安定したUIコンポーネントフレームワークだったからです。
  - Jest
  - React Testing Library
  - Cypress
    - 仕様があまり固まった状態ではなくプロトタイプを作成、フィードバックを繰り返して開発していたこともあり、テストファーストの実施はしておりませんでした。ある程度、プロダクトが固まったら段階的にテストコードを追加していました。
    - テストはE2Eを中心に薄くしか実施できていません。E2EはBDDベース、画面遷移やボタンアクションのテストを中心にテストしております。

### バックエンド
  - Node.js
    - Express.js
      - バックエンドは薄めのフレームワークであるExpress.jsでREST API開発をしておりました。高トラフィックの経験はほとんどないため、基本的に受けた処理に従って、データベースにRead/WriteしてJsonを返す、blockingが発生する処理はchild processに逃す程度の利用をしておりました。
      - REST API
      - GraphQL
        - Apollo Server

### データベース
  - MongoDB
    - Mongoose
      - MongoDBへの直接アクセスはせずに、Mongooseのスキーマの型を通してのアクセスを徹底させることにより、NoSQLの柔軟性を得ながら、安全性を高めて利用しました。
  - Cloud Firestore
    - 2020年より、プロジェクト数の増加による負荷を低減させるために、可能な限りインフラ部分はフルマネージド環境で開発する方向に転換しました。
    - MongoDB Atlasも検討しましたが、BaaS環境の弱さと
    フロントエンドからのmBaaSとして採用を決めました

- インフラ
  - GCP
    - Cloud Run
      - DockerをContainer Registryに登録、Cloud Buildによる継続的デプロイの設定は行えます
      - Serverless NEGとHTTPSロードバランサーをCloud Runと紐づけてIdentity-Aware Proxyを使ってのアクセス制御の経験はあります
    - BigQuery
     - WebサービスのFirebase Analytics、Firebase Extensions-Export Collections to BigQuery、Fivetranを用いてシンプルなデータ基盤の開発の経験はあります
    - Firebase
      - Cloud Firestore、Cloud Storageを使ってのサーバーレス開発の経験はあります
    - 2019年まではAWSでシンプルなEC2, S3, CloudFrontを使っていましたが、運用プロジェクトの増加により煩雑になったため、2020年よりフルマネージド型に強みがあるGCPを中心に利用を開始しました。また、Cloud Storage for FirebaseとBigQueryの自動同期（Firebase Extensions）の存在もGCP以降への強いきっかけとなりました。
  - Github Actions
  - Docker
   
   

### 技術のキャッチアップ方法
  - 社内にエンジニアがいない環境かつ地方都市在住のため、まとまった情報は書籍、先端企業の考え方を知る方法として企業ブログやTechイベントの動画、最新情報はTwitterで収集することが多かったです。
    - iOSのアプリ作成時はraywenderlich.comの本とチュートリアルを主に参考にしました。。
    - 2015年からのES2015のキャッチアップはSecrets of the JavaScript Ninja, Second Editionを写経を繰り返して身につけました。
  - ソースコードのクオリティの担保としてはオープンソースとして公開されている企業コードを参考にすることが多かったです。
    - F8 App 2016 (F8のイベントのReact Nativeアプリ)
    - mtc2018-app (mtc2018-webのイベントのReact/Apollo Client/Next.js)

### 技術選定の指針

- 開発していて楽しい長期的な運用に耐えれる
- 長期的な運用に耐えれる
- イージーよりシンプル

原体験として、2012年に"RailsによるアジャイルWebアプリケーション開発"の本で勉強したときに写経でカートシステムが完成したが、Railsコマンドを幾つかためしたら、動かなくなった。Ruby on Railsの強い力を感じた一方、当時の私には身に余る力であると感じ、チームにベテランメンバーがいなければ危ないと思いました。

一方、2013年からの自社サービスはPHP/CodeIgniterで開発しました。(当時の私はこの技術選択やコードにはほとんど関与せず、インド側で決めました。)。CodeIgniterは自由度の高いフレームワークであるため、やり方を決めなかれば自制が効かなく、コードが破綻状態になりやすいと思いました。自社サービスはメンテナンスが厳しくなり、2018年にフルリプレースをしております。

そのような経験から、SimpleとEasyならば、多少非効率でも主にSimpleを選択するが、その一方ある程度統制して行うことにしました。

そのような理由から、2016年開始のプロジェクトのアーキテクチャはMEANスタック (MongoDB, Express.js, React, Node.js. *AはAngularJSではなくReact)を選定しました。その結果、フロントからバックエンド・データベースまでとてもシンプルで一貫して開発できる体制を整えられ、すべての技術スタックを一新してのプロジェクトでしたが、細かい苦労は多かったですが、無事にプロジェクトを成功させ、その後のプロジェクトの基盤となる技術体制を確立できました。

その他にも、2016年開始のプロジェクトのReactの状態管理のライブラリーの選定時は、当初はRefluxJSを採用を考えていた。コードベースの参考に使ったGithubのreact-musicがRefluxJSを採用していたことあり、Reduxより工数は多いが使いやすいと感じていたが、直前にReduxとRefluxJSのGithubのスター数が逆転しており、勢いと将来製からReduxを採用しました。

比較的早期にNext.js 2.xやMaterial-UI 0.xを採用し苦しみがあったこと、ライブラリーを使うのは誰でもできるため最新のライブラリーを採用することは技術力高いことにはならないと気づきました。

その後は困っていることの解消やコードのシンプルさを向上できるなら選択することが多いです。

例えば、Redux Formを使っていましたが、レンダリングの遅さが気になり、Formikに移行した。その後、FormikはReact Hooksへの対応が遅く、React Hook Formが流行したが、すぐに乗り換えるほどではないと判断して、しばらく様子をみた。FormikがuseFormikとしてReact Hooksへの対応後は順次useFormikへの移行は行った。

インフラ面に関しては、当初は手がまわずにEC2に構築するシンプルな形にしていました。運用サービス数の増加に伴い、長期的な安定運用と管理コストを低減を面として考える方針にしました。。

具体的には、フロントエンドはVercel, サーバー環境はCloud Run, App EngineまたはCloud Functions、データベースをFirestore、CMS環境はWordpressからGraphCMS、データ基盤としてBigQueryの利用に伴い、以前の構成に比べて70%近くコストを下げ、尚且つ管理コストを下げることに成功しました。



#### 要望
- [条件](conditions.md)



