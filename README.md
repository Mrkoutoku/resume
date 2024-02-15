# 業務経歴書

## 基本情報
|key|value|
|---|---|
|名前|小河 光徳|
|所在地|大阪府 大阪市|
|生年月日|1996年5月13日|
|Twitter|[@ktk0513](https://twitter.com/ktk0513)|
|保有資格| CLF SAA|
|興味のある事勉強したいこと| マルチクラウド データ基盤 英語 バックエンド データ分析  ワイン（お酒全般）|

# 概要
- クラウドアーキテクチャ設計、クラウドインフラ構築管理、基盤コード開発
- AWS全般、自動化による運用効率の改善、コスト削減、セキュリティ関連、が好きです。
- これまでAWSインフラ基盤の設計、Terraform/TerragruntでのAWSインフラ基盤の構築、総合行政ネットワーク（LGWAN）に接続可能なAWSインフラ基盤構築の設計構築、AWSのシステム運用に携わってきました。
- 新規開発フェーズ、改修フェーズ、保守運用フェーズの各フェーズ経験があります。


# スキル
- 基本的に実務で関わった技術のみ記載しています。

### 言語
TypeScript |

### フレームワーク
serverless flamework

### インフラ
AWS | Azure | オンプレ

AWS
VPC | S3 | API Gateway | Lambda | ELB | EC2 | ECS | Fargate | Route53 | IAM | RDS(MySQL|PostgreSQL) | Aurora | DynamoDB | ElastiCache(Redis) | SQS | SNS | SES |  CloudFormation | CloudWatch | EventBridge | AWS Batch | CloudTrail | AWS Config | GuardDuty | Security Hub | KMS | Parameter Store | AWS Organizations | AWS Control Tower | AWS SSO(Single Sign-On)

Azure
Endpoint | Cognitive Service | Text Analytics | Azure OpenAI Service | API Manager 

オンプレ
Cisco L3スイッチ | F5 LoadBalancer | FortiGate | FortiManager 
### SaaS
GitLab

### その他
Terraform | Terragrunt | GitlabCI | Linux | Apache | nginx | Docker | Notion | Backlog 

## バリューを発揮しやすい業務
- クラウドアーキテクチャ設計
- クラウドインフラ構築管理
- 基盤コード開発
- dev/stg/prod環境の切り分け
- サーバーレスアーキテクチャの導入
- メッセージングサービスの導入
- CIサービスの導入
- コンテナ化(Docker化)
- インフラのコード化
- オートスケールの設定
- デプロイの自動化
- 閉域網接続
- 自動化による運用効率の改善
- ログベースでの不具合調査
  

## 本業の業務経歴

### AWSインフラ基盤の設計/構築　(2023年〜2024年)
【プロジェクト概要1】
- 自治体向けAIサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- AWSからAzureへの閉域網接続

【発揮したバリュー】
Terraformを使いインフラを構築し、運用しやすい環境を構築。

【プロジェクト概要2】
- 取り込んだCSVからPDFを生成するサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）での利用に限らず、インターネットからの利用も可能にする設計/構築
- 定期的にCSVを取り込むAWS Batch　PDFを生成するためのAWS Batch起動上限100に設計

【発揮したバリュー】
Terragruntを使いこれまでよりも迅速に、運用しやすいインフラを構築。
【プロジェクト概要3】
- 決裁を紙からWEBへ変更するためのWorkflowサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）での利用に限らず、インターネットからの利用も可能にする設計/構築

【発揮したバリュー】
Terragruntを使いこれまでよりも迅速に、運用しやすいインフラを構築。
【プロジェクト概要4】
- 部署移動の多い自治体向けに適切な人材を配置提案する人材配置システムのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- 適切な人材配置ができるようテストするため、AWSインフラ基盤からセキュアに適性診断システムへ接続

【発揮したバリュー】
Terragruntを使いこれまでよりも迅速に、運用しやすいインフラを構築。

### 自動化による運用効率の改善　(2023年〜)
【プロジェクト概要】
GitlabCIで各プロジェクトのデプロイ方法を変更。

現状　
- Gitlabでレビュー後マージする。テスト完了後、S3にzipをアップロードしCodePipeline/CodeBuild/CodeDeployでAWS環境へデプロイ  

変更　
- Frontend | Backend
- Gitlabでレビュー後マージされるブランチごとに処理を追加。
- developブランチにマージされる。テストが完了する。2つの処理が問題なく実行されたことをトリガーに、S3に自動でアップロードし、STG環境へ自動でデプロイする。　　　
- masterブランチにマージされる。テストが完了する。2つの処理が問題なく実行されたことをトリガーに、S3に自動でアップロードし、PROD環境へ自動でデプロイする。
  
- Backend
- developブランチにマージされる。テストが完了する。2つの処理が問題なく実行され、S3に自動でアップロードしたことをトリガーに、STG環境のDBへワンクリックでマイグレーションする。　　　


【発揮したバリュー】
デプロイまでの作業を簡略化し各プロジェクトに貢献。

### AWSインフラ基盤のコスト削減　(2023年〜2024年)
【プロジェクト概要】
削減内容
- 各プロジェクトdev環境のNatGatewayをNatInstanceに変更
- 各プロジェクトで使用しているS3が全てスタンダードだったため見直し、一部をIntelligent - Tieringに変更
- InterfaceEndpointの共通化
- Compute optimizedを適用しインスタンスタイプの最適化

【発揮したバリュー】
各プロジェクトのランニングコストを削減し売り上げに貢献。

【感想（ここだけ）】
コスト最適化は設計構築より難しく感じたがアーキテクチャを考える作業と同等のおもしろさだった。
意味はないと思っていた資格の知識がここで活きた。
