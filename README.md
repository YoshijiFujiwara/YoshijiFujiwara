# 業務経歴書

## 基本情報

| key    | value                              |
| ------ | ---------------------------------- |
| 名前   | 藤原吉司                           |
| 生息地 | 東京都 品川区                      |
| github | https://github.com/YoshijiFujiwara |

## 概要

生物系学部卒業 -> IT 系専門学校 -> Web エンジニア

## ポートフォリオ

### VR 文化祭 web アプリ(2020 ~ 2021 年)

【repository】https://github.com/YoshijiFujiwara/tulip-project
【YouTube】https://www.youtube.com/watch?v=g86MIp_KDuo
【詳細資料】https://docs.google.com/presentation/d/1p21GvZtLOdw6NG1Vtf9tjCB91JLErFQKyumCwg_4CVM/edit#slide=id.gb36322a21f_0_125
【使用技術】

-   フロント(文化祭主催側): Nuxt(TypeScript)
-   フロント（VR）: Aframe(Web で VR 表現が出来る)
-   バックエンド: Nest(TypeScript)
-   インフラ: k8s(Degital Ocean), docker-compose, GithubActions, 自動デプロイ
-   その他: スクラム(のような)開発。毎週の振り返り、KPT、タスク見積もり（プランニングポーカー）

【概要】
VR 空間で文化祭を開催できるアプリケーションを開発しました。VR 空間で、主催者と参加者が、オリジナルのアバターでコミュニケーションを取れます。音声通話にも対応しており、近くなれば、より大きな声で会話出来ます。

<img src="/images/tulip1.png" width="50%"/>
<img src="/images/tulip2.png" width="50%"/>

### 学習支援 Web アプリ(2020 年)

【repository】https://github.com/YoshijiFujiwara/himawari-project
【詳細資料】https://docs.google.com/presentation/d/1zWnowbMBMLSX05G95I5AbfSYCDozMrFKlVWgK3jLZxo/edit#slide=id.g8d2384fef3_8_7
【使用技術】

-   フロント: Vue(TypeScript)
-   バックエンド: Nest(TypeScript)
-   インフラ: k8s(Degital Ocean), skaffold, docker-compose, GithubActions, 自動デプロイ
-   その他: スクラム(のような)開発。毎週の振り返り、KPT、タスク見積もり（プランニングポーカー）

【概要】github リスペクトの学習支援アプリを開発しました。自分の学習記録をつけていくと、それに伴い、ひまわりが咲くようなデザインです。技術や、マネジメント面においても、10 人程度のメンバーが効率よく開発出来るように、自動デプロイやレビュー文化、インフラ整備、front と backend の言語統一などを行いました。

<img src="/images/himawari.png" width="50%"/>
<img src="/images/himawari_infra.png" width="50%"/>

### web デベロッパースキルツリー (2019 年)

【本番 URL】https://webdeveloper-skilltree.now.sh/
【repository】https://github.com/YoshijiFujiwara/web-developer-skill-calculator
【使用技術】Nuxt
【概要】２日で作成しました。ゲームによくあるスキルツリーを意識して作りました。上からポチポチしていくと、下のスキルが開放されます。背景のスタイルの変化などに、Vue のリアクティブな処理を活用しました。
<img src="/images/web_dev.png" width="50%"/>

### サボり共有アプリ (2019 年)

【google play store URL】https://play.google.com/store/apps/details?id=com.yoshijiFujiwara.saborie
【repository】https://github.com/YoshijiFujiwara/vue-native-saborie / https://github.com/YoshijiFujiwara/golang-saborie
【使用技術】**Vue Native** / Golang / Neo4j
【概要】サボりを共有するアプリを作りたいが、Vue で書きたい！。そんな願いを Vue Native が叶えてくれました。(React Native をうまいことラップして作ったそうです)
また、バックエンドの API は、Go でノンフレームワークで書いてみました。
データベースには、key/value 型の特徴と、RDS の特徴を持つ、グラフデータベースの一種である Neo4j を使いました。
<img src="/images/saborie.png" width="50%"/>

### slack のような SPA (2019 年)

【repository】https://github.com/YoshijiFujiwara/zlack-docker-2 など
【使用技術】Nuxt.js / LaravelAPI / JWT
【概要】初めての SPA 開発ということで、とっつきやすそうな、Nuxt での開発にチャレンジしました。
また、pusher などの websocket 技術も活用し、「〇〇さんがタイピング中。。」のような機能も作成しました
<img src="/images/zlack.png" width="50%"/>

### 幹事支援アプリのバックエンド (2019 年)

【repository】
backend: https://github.com/YoshijiFujiwara/hew-2-backend
front(Android): https://github.com/YoshijiFujiwara/hew-2-android-master
管理者画面(Nuxt): https://github.com/YoshijiFujiwara/hew-2-admin-panel
【使用技術】Laravel / Android / Nuxt / JWT
【概要】バックエンドと管理者画面を主に担当しました。
API の数が多いため、API 仕様書をきちんと定義し、Android 側の開発がスムーズに進むように意識しました
<img src="/images/laravel_api.png" width="50%"/>

また、管理者画面を高速で開発するために、Nuxt で開発しました。

## 主な業務経歴

### 従業員情報をサービス横断で使いやすくする開発(2021 年~)

【所属】freee 株式会社
【プロジェクト概要】freee 人事労務の従業員マスタを、freee 会計などの他サービスから利用しやすくするための機能開発
【担当業務】人事労務以外のサービスでは必要としない従業員情報を洗い出し（ex. 給与情報など) 、それらなしで、従業員作成やサービス間での連携が出来るようにしました。また、一括作成、一括更新機能を作り、ユーザーにとってより使いやすいものを目指しました。

-   React(JS, TypeScript) によるフロントエンドの実装
-   Rails によるバックエンドの実装

### freee プロジェクト管理リリース(2020 年~)

【所属】freee 株式会社 インターン
【プロジェクト概要】freee プロジェクト管理リリース、リリース後新機能追加
【担当業務】新サービスリリースにおいて、新機能のフロントエンド実装を主に担当しました。また、アクセシビリティを高めるための開発も行いました。

-   React(TypeScript) によるフロントエンド実装
-   LightHouse などを使った、アクセシビリティ向上

### エムスリー サマーインターン(2019 年)

【所属】エムスリー インターン
【プロジェクト概要】電子カルテ開発
【担当業務】Rails での新機能実装

### Voyage Group サマーインターン(2019 年)

【所属】Voyage Group インターン
【プロジェクト概要】React, Go の講義。後半は実践型チーム開発
【担当業務】ReactNative/Go を使った Native アプリを開発しました。バックエンドを担当しました。

### Fringe81 サマーインターン(2019 年)

【所属】Fringe81 インターン
【プロジェクト概要】React アプリケーションのリファクタリング
【担当業務】React のサンプルアプリケーションを、極限までコードにこだわってリファクタリングしました。

### Retty サマーインターン(2019 年)

【所属】Retty インターン
【プロジェクト概要】k8s 導入試験
【担当業務】Docker + AWS(Elastic Beanstalk) のアプリケーションを、k8s + GKE に移行するための調査を行いました

### マーケティングオートメーション開発の Laravel リファクタリング(~ 2019 年)

【所属】combz 株式会社 アルバイト
【プロジェクト概要】新規開発
【担当業務】Laravel API のリファクタリング

-   ORM を使用しやすいテーブル設計
-   RESTFul なルーティング設計
-   権限管理を Laravel 推奨のライブラリに変更
-   NoSQL 導入
