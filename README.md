# 職務経歴書 2024.06.21

## 個人情報

| 項目  | 詳細                                 |
| :---: | :----------------------------------- |
| 氏名  | Genta Saito                          |
| 年齢  | 26 歳                                |
| 住所  | 神奈川県                             |
| Email | genta.otias@gmail.com                |
| 趣味  | 深夜ラジオ、料理、散歩, サイクリング |

## 使用したことのあるスキル

#### Language

Golang | Javascript | Typescript | PHP | Ruby | Python

#### Framework

Echo | Goa | Openapi | Gorm | Ruby on Rails | Django | Vue.js | React | Next.js

#### RDB/NoSQL

Mysql | DynamoDB | Spanner

#### Cloud

##### AWS

#####　GCP Firebase

#### SaaS | PaaS

Github | Github Actions | CircleCI | JIRA | Confluence | Snyk | Trivy | Slack | miro

#### Other

Terraform | Docker | Datadog | Elasticsearch | Kubernetes | Helm | Skaffold | Onelogin | Notion

## 職務経歴概要

#### 自社開発「FinTech SaaS【TypeScript | ts-rest | gRPC | Golang | GCP | Github Actions | Notion | ArgoCD 】(2024 年 4 月 〜 2024 年 6 月 )

【プロジェクト概要】

FinTech SaaSサーバサイド開発

【担当業務】

  - BFF開発
    - Express(TypeScript)でスキーマを実装
    - schema実装
    - BFF上から各マイクロサービスのgPRCサーバーへへの接続しクライアント側にRestAPIとしてレスポンスを返す
  - サーバーサイド開発
    - gPRC protoの実装
    - GolangでAPI実装
    - Spanner接続とクエリ実装
    - Spanner上でのER図自動生成導入
  - テストカバレッジ100%を達成
  - QAテストケースの作成と実施
  - Minispec作成

#### 自社開発「ニュースキュレーションアプリ」【TypeScript | Next.js | GraphQL | Golang | Terraform | AWS | Github Actions | Docker】(2023 年 7 月 〜 2024 年 3 月 )

【プロジェクト概要】

某大手キャリアのポータル兼ニュースキュレーションアプリの新管理画面開発

【担当業務】

- サーバーサイド開発

  - 技術選定
  - 運用チームから要望を聞き、機能に盛り込む
  - 管理画面の画面構成設計
  - ALB での Onelogin OIDC 認証の連携とユーザーごとの権限管理
  - Onelogin から JWT トークンを発行し、認証機能の実装
  - テーブル設計
  - GraphQL による API サーバーの構築
  - フロントエンドとの連携
  - 新管理画面のリリースに伴うサービスの構築
  - ポイント付与キャンペーンのための API/テーブル設計/プロモコード周りの構築
  - Terraform で必要なリソースの構築
  - Github Action での CI/CD パイプラインの構築

#### 自社開発「ニュースキュレーションアプリ」【Golang | Terraform | AWS | CircleCI | Github Actions | Docker | Datadog | Kubernetes】(2022 年 5 月 〜 2024 年 3 月 )

【プロジェクト概要】

某大手キャリアのポータル兼ニュースキュレーションアプリ開発

【担当業務】

- サーバーサイド開発

  - 新規施策のための API/テーブル設計
  - 他社サービス API との連携
  - リアルタイム更新のプロ野球スコアボードの実装
  - ポイント付与キャンペーンのための API/テーブル設計/プロモコード周りの構築

- インフラ
  - EKS バージョンアップグレード作業(1.21 → 1.22 / 1.22 → 1.23)
  - Helm Chart による EKS のパッケージ管理
  - Snyk からあがってくるセキュリティの指摘対応
  - Terraform による AWS の Iac 化
  - RDS ソフトウェアのアップデートのための深夜メンテ業務
  - CircleCI から　 Github Actions への CI/CD パイプラインの移行

#### 受託開発「自動車特化型フリマアプリ」【Next.js | Typescript | Golang | Firebase | Terraform | AWS | CircleCI | Docker】(2021 年 9 月〜 2022 年 5 月)

【プロジェクト概要】

中古車をスマホで個人間売買できるフリマアプリの開発

【担当業務】
言語選定からスケジュール管理などの上流工程から参加。
フロントエンドのロジックと管理者画面の構築やバックエンドの API サーバーの構築。
Terraform を用いた インフラのコード化。

- 言語選定。上記技術スタックの採用。環境構築
- システムフロー作成
- プロジェクトファイル構成検討
- Next.js(TypeScript) によるフロントエンド部分の実装
- Golang による REST JSON API サーバーの構築
- Golang JWT 発行と認証機能の実装
- Mysql のテーブル設計や構築。リレーションの構築
- Terraform でのインフラのコード化
- Firebase Authentication でユーザー２段階認証の追加
- CircleCI で CI/CD パイプラインの構築と本番環境とステージング環境のデプロイを構築

#### 自社開発「フリーランスコンサルタント向け案件紹介サイト」【Vue | Lavarel | AWS S3 | Docker】(2021 年 7 月〜 2021 年 9 月)

【プロジェクト概要】

フリーランスコンサルタント向け案件紹介サイトの開発

【担当業務】
本プロジェクトはサービス立ち上げから関わり、初期の要件定義から環境構築、実際のコーディング、テスト、デプロイに至るまで一通り担当した。

- 企画会議への参加
- 言語選定
- Docker Compose で環境構築
- Vue.js によるフロントエンド部分の実装
- Laravel Inertia による API サーバーの構築
- Mysql のテーブル設計や構築
- AWS S3 でファイル保存機能の実装
- IAM ユーザー作成とロールの選定
- デプロイ用 シェルスクリプトの作成
- サイト全体のリファクタリング

#### 自社開発「学生向け就活 SNS サイト」【React.js | Golang | Firebase | GCP | Docker | Github Actions】(2021 年 5 月〜 2022 年 5 月)

【プロジェクト概要】

学生向けのオファー型就活 SNS サイトの開発

【担当業務】
サービス全体の実装をするフルスタックエンジニアとして要件定義からテストまでの工程を担当した。
各領域で分業体制は取らず、一つの機能の要件定義からコーディング、テストまでを行なった。

- 新規機能追加などの企画会議への参加
- React.js によるフロントエンド部分の実装
- Firebase との連携
- Golang による REST JSON API サーバーの構築
- Mysql のテーブル設計や構築
- Firebase Authentication でユーザー２段階認証の追加
- Firebase Storage で画像や PDF ファイルの複数枚投稿を実装
- Firebase Function にメール送信機能を実装
- GCP デプロイ用 シェスクリプトの作成
- Github Actions で CI/CD パイプラインの構築と本番環境とステージング環境のデプロイを構築
- サイト全体のリファクタリング
