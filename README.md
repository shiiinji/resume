# 職務経歴書

- 寺本 真之（てらもと しんじ）

## 概要

- フロントエンド開発を主軸としたWebアプリケーションをしています。バックエンド開発はNode.jsを使ったREST API、GraphQLサーバーをFirebase、GCP上で運営しています
- モダンJavaScript・Reactの開発経験(実務)5年、TypeScriptの開発経験(実務)3年ほどあります。
- 自社開発、受託開発のどちらの経験もあり、どちらも新規開発から運用まで一気通貫して対応しています。自社サービスは最長8年(フルリプレースあり)、受託開発は最長5年の運用しております。
- インドのラボ型オフショア開発会社とシステム開発歴が8年あります。プロジェクトの工数管理、メンバーの進捗の管理やコードレビューをしています。


## 職歴概要

### ピアズ・マネジメント株式会社: 2013年1月～2018年6月 (2012年8月よりインターン)
### ハピログ株式会社: 2018年7月～現在
 - 事業の主体を事業会社に移行したことに伴う転籍であるため、仕事内容や開発体制等に実体に変更はありません

### 会社概要

 - 事業内容: 自社Webサービス、受託開発、コンサルティング、マーケティング支援
 - 従業員数: 3名 (エンジニア内1名: 本人)


### 開発体制

 - リードエンジニア・プロジェクトマネージャー: 1名(本人)

#### インドのラボ型オフショア開発企業
   - マネージャー: 1名
   - エンジニア: 3名 (最大７名、最小1名)
   - 期間: 2013年1月～現在 

#### 役割分担

   - 本人: 主に新規開発のフロントエンド、バックエンド、インフラと運営・保守のプロジェクトマネジメントを担当
   - インド: 主に運営・保守のフロントエンド、バックエンドを担当

### プロジェクト概要



 

## スキル

### 技術選定の指針
- 原体験で、2012年に"RailsによるアジャイルWebアプリケーション開発"の本で勉強したときに写経でカートシステムが完成したが、Railsコマンドを幾つかためしたら、動かなくなった。Ruby on Railsの強い力を感じた一方、当時の私には身に余る力であると感じ、チームにベテランメンバーがいなければ危ないと思いました。
- また一方、2013年からの自社サービスはPHP/CodeIgniterで開発された。CodeIgniterは自由度の高いフレームワークであるため、自制が効かなければ、コードが負の遺産となりやすいと感じました。自社サービスはメンテナンスが厳しくなり、2018年にフルリプレースをしております。
- そのような経験から、SimpleとEasyならば、多少非効率でも主にSimpleを選択しました。その一方、やり方は統一して行うことにしました。
  - 新しい技術を導入するときはまず私が一つのプロジェクトまたは幾つかの機能に適用し、それに沿って他の部分のリファクタリングをインド側に依頼する形にしておりました。

### 言語
  - JavaScript: 6年
  - TypeScript: 3年
    - JavaScriptよりTypeScriptを用いての開発を好みます。
    - 2018年以降の新規アプリケーションはフロントエンド・サーバーサイドともにTypeScriptを選択しています
  - Swift: 1年
  - Rust: 今年より勉強を開始しているが実務レベルには達していないです。
    - 興味がある部分は、今後フロントエンドにどの程度影響を与えるのか、低レベル部分への実装です。
  
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
      - WebアプリケーションのデザインのUI/UXデザインは得意ではないため、基本的にMaterial UIをベースとして開発してます。
    - Jest
    - React Testing Library
    - Cypress

### バックエンド
  - Node.js
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
   
- その他
  - 英語
    - インドのラボ型オフショア開発会社とを9年間のチームを構築しています。
    - 英語は文字によるコミュニケーションをしています。オフショア開発で必要とされている英語の読み書きはある程度できます。英語の会話と聞き取りはできません。

### 技術のキャッチアップ方法
  - 社内にエンジニアがいない環境かつ地方都市在住のため、まとまった情報は書籍、先端企業の考え方を知る方法として企業ブログやTechイベントの動画、最新情報はTwitterで収集することが多かったです。
    - iOSのアプリ作成時はraywenderlich.comの本とチュートリアルを主に参考にしました。。
    - 2015年からのES2015のキャッチアップはSecrets of the JavaScript Ninja, Second Editionを写経を繰り返して身につけました。
  - ソースコードのクオリティの担保としてはオープンソースとして公開されている企業コードを参考にすることが多かったです。
    - F8 App 2016 (F8のイベントのReact Nativeアプリ)
    - mtc2018-app (mtc2018-webのイベントのReact/Apollo Client/Next.js)

#### 要望
- [条件](conditions.md)



