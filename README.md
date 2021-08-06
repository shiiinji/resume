# 職務経歴書

- 氏名: 寺本 真之（てらもと しんじ）

## 概要

- フロントエンド開発を主軸としたWebアプリケーションをしています。バックエンド開発はNode.jsを使ったREST API、GraphQLサーバーをFirebase、GCP上で運営しています
- モダンJavaScript・Reactの開発経験(実務)5年、TypeScriptの開発経験(実務)3年ほどあります。
- 自社開発、受託開発のどちらの経験もあり、どちらも新規開発から運用まで一気通貫して対応しています。自社サービスは最長8年(フルリプレースあり)、受託開発は最長5年の運用しております。
- インドのラボ型オフショア開発会社とシステム開発歴が8年あります。プロジェクトの工数管理、メンバーの進捗の管理やコードレビューをしています。


## 職歴概要

#### ハピログ株式会社: 2018年7月～現在
#### ピアズ・マネジメント株式会社: 2013年1月～2018年6月 (2012年8月よりインターン)

 - 事業の主体を事業会社に移行したことに伴う転籍であるため、仕事内容や開発体制等に実体に変更はありません

### 会社概要

 - 事業内容: 自社Webサービス、受託開発、コンサルティング、マーケティング支援
 - 従業員数: 3名 (エンジニア内1名: 本人)

### 開発体制

 - リードエンジニア: 1名(本人: 2016年〜現在)
 - プロジェクトマネージャー: 1名(本人: 2013年〜2015年)

#### インドのラボ型オフショア開発企業
   - マネージャー: 1名
   - エンジニア: 3名 (最大７名、最小1名)
   - 期間: 2013年1月～現在 

#### 役割分担

   - 基本的に全メンバーがフロントエンド、バックエンド共に担当しております。インフラ面に関しましてはセキュリティの関係上、私が全面的に担当しております。
   - 本人: 主に新規開発、アーキテクチャ設計、新技術の導入、コードレビュー、タスク管理を主に担当しております

### プロジェクト概要

###### *開発チーム規模は状況により柔軟に複数のプロジェクト間を行き来しているため目安になります。

#### 【受託開発】 プラスチック成形材料データベース (https://plabase.com)

- 概要



| 期間 | 内容 | 役割/開発チーム規模 |
| --- | --- | --- |
| 2015/10<br />〜<br />2015/12 | 2017/11 | jQueryを用いて検索ページのプロトタイプの作成。<br />プラスチックの物性構造化 | 1名 (本人) |
| 2016/4<br />〜<br />2016/11 |     |     |
|     |     |     |

- 使用技術
  - 使用言語: JavaScript(ES2015)、Node.js
  - フロントエンド: React-Router, Redux (Redux-Thunk)、Material-UI
  - バックエンド: Express, MongoDB
  - 開発環境：AWS(EC2, S3, CloudFront, Route53), Bitbucket

国内の主要な樹脂材料メーカーの製品をデータベース化しています。 （2785銘柄 2017年8月時点）. 物性値検索、メーカー横断の比較ができます。

## スキル

### 言語
  - JavaScript: 6年
  - TypeScript: 3年
    - JavaScriptよりTypeScriptを用いての開発を好みます。
    - 2018年以降の新規アプリケーションはフロントエンド・サーバーサイドともにTypeScriptを選択しています
  - Swift: 1年
  
### フレームワーク、ライブラリー
  - React: 5年
    - Next.js: 4年
      - Next.js 2.0の頃から利用を開始しました。動的なルーティングやApp Component(_document.js, _app.js)がまだない頃でしたが、webpackの負担軽減やSSRに魅力を感じ導入を決めました。
    - Redux
    - Recoil
    - GraphQL
      - Apollo Client
      - urql
        - GraphQLは型の自動生成でサーバーサイドとの通信が明示的になるために好みます。
        - GraphQLの導入前に一時的に一部のREST APIに対してSwaggerの試みましたが、TypeScriptとの導入前かつ実装済みのREST APIに対してSwaggerの記述になったので、負担の割にメリットを感じられなかったために導入を断念したことがあります。
    - Material UI
      - WebアプリケーションのデザインのUI/UXデザインは得意ではないため、基本的にMaterial UIをベースとしてWebアプリケーションのデザインをしてます。
    - Jest
    - React Testing Library
    - Cypress

### バックエンド
  - Node.js
    - Express.js
      - REST API
      - GraphQL
        - Apollo Server

### データベース
  - MongoDB
    - Mongoose
      - MongoDBへの直接アクセスはせずに、Mongooseのスキーマの型を通してのアクセスを徹底させることにより、NoSQLの柔軟性を得ながら、安全性を高めて利用しました。
  - Cloud Firestore
    - 2020年より、プロジェクト数の増加による負荷を低減させるために、可能な限りサーバーレスにして開発する方向に転換し、フロントエンドからのmBaaSとして採用を決めた。

- インフラ
 - GCP
   - Cloud Run
     - DockerをContainer Registryに登録、Cloud Buildによる継続的デプロイの設定は行えます
     - Serverless NEGとHTTPSロードバランサーをCloud Runと紐づけてIdentity-Aware Proxyを使ってのアクセス制御の経験はあります
   - BigQuery
     - WebサービスのFirebase Analytics、Firebase Extensions-Export Collections to BigQuery、Fivetranを用いてシンプルなデータ基盤の開発の経験はあります
   - Firebase
      - Cloud Firestore、Cloud Storageを使ってのサーバーレス開発の経験はあります
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

フロントエンドに関して当初は新技術を積極的に取り入れる方針にしてました。なぜなら、東京の先端企業に追随するため、新しい技術が取り入れなければならないと考えました。

例えば、2016年開始のプロジェクトのReactの状態管理のライブラリーの選定時は、当初はRefluxJSを採用を考えていた。コードベースの参考に使ったGithubのreact-musicがRefluxJSを採用していたことあり、Reduxより工数は多いが使いやすいと感じていたが、直前にReduxとRefluxJSのGithubのスター数が逆転しており、勢いと将来製からReduxを採用した。

比較的早期にNext.js 2.xやMaterial-UI 0.xを採用し苦しみがあったこと、ライブラリーを使うのは誰でもできるため最新のライブラリーを採用することは技術力高いことにはならないと気づきました。

その後は困っていることの解消やコードのシンプルさを向上できるなら選択することが多いです。

例えば、Redux Formを使っていましたが、レンダリングの遅さが気になり、Formikに移行した。その後、FormikはReact Hooksへの対応が遅く、React Hook Formが流行したが、すぐに乗り換えるほどではないと判断して、しばらく様子をみた。FormikがuseFormikとしてReact Hooksへの対応後は順次useFormikへの移行は行った。

インフラ面に関しては、当初は手がまわずにEC2に構築するシンプルな形にしていました。運用サービス数の増加に伴い、長期的な安定運用と管理コストを低減を面として考える方針にしました。。

具体的には、フロントエンドはVercel, サーバー環境はCloud Run, App EngineまたはCloud Functions、データベースをFirestore、CMS環境はWordpressからGraphCMS、データ基盤としてBigQueryの利用に伴い、以前の構成に比べて70%近くコストを下げ、尚且つ管理コストを下げることに成功しました。


**### 自己PR**

- やり切る力

  - 仕事がまだわからなくても、ビジネスを立ち上げ、規模としては小さいですが1千万弱のフォトブックを事業を立ち上げました。。

  - エンジニア一人でも、すべて新しいアーキテクチャを用いて受託開発を完遂した。そして、そのクライアントからの受注額が現職会社の最大売り上げを占めるまでに成長する礎を築きました。(開発他、プロダクトに関するコンサル、マーケティング支援を含めて)



### 今後の目標について
 
 #### 短期の目標: フロントエンドの専門性を高める
  - 少人数でプロジェクトの新規開発〜運営をする都合上、幅広く器用貧乏に技術を習得してきたため、今後は一つの分野の専門性を高めたいと思っております。
    - その中でフロントエンドを習得を望むのは現職の仕事を通して最もやり甲斐を感じたためです。

#### 中長期の目標:
  - 


#### 要望
- [条件](conditions.md)



