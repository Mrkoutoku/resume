# 業務経歴書

## 基本情報
|key|value|
|---|---|
|名前|小河 光徳|
|所在地|大阪府 大阪市|
|生年月日|1996年5月13日|
|Twitter|[@ktk0513](https://twitter.com/ktk0513)|
|保有資格| AWS Certified Cloud Practitioner　/AWS Certified Solutions Architect - Associate /AWS Certified Solutions Architect - Professional /AWS Certified Developer - Associate /AWS Certified Sysops Administrator - Associate|
|好きな事 / 興味のある事| 息子　/Architect /マルチクラウド　/データ基盤　/English　/バックエンド　/データ分析　/ワイン（お酒全般）|

# 自己紹介
- アーキテクチャ、クラウド技術全般、自動化による運用効率の改善、コスト削減、セキュリティ関連、が好きです。 
- これまでAWSインフラ基盤の設計、Terraform/TerragruntでのAWSインフラ基盤の構築、総合行政ネットワーク(LGWAN)に接続可能なAWSインフラ基盤構築の設計構築、AWSのシステム運用に携わってきました。 
- 新規開発フェーズ、改修フェーズ、保守運用フェーズの各フェーズ経験があります。
- リプレイスフェーズも是非経験したく資格勉強も兼ねてインプットはしましたが、機会がありませんでした。 
- 最近は子供と自転車の練習をすることが休日のタスクです。

# スキル
- 基本的に業務で関わった技術のみ記載しています。

### 言語
TypeScript 

### フレームワーク
serverless flamework (TS)
※ 社内の自己紹介サイトに展開する画像にサイズ制限があるので、画像がS3にアップロードされたことをトリガーに起動するlambdaを作成しました。 lambdaの内容は画像を圧縮するというだけの簡単な内容です。 誤解が生まれると思い記載しました。
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
- サーバーレスアーキテクチャの導入
- CIサービスの導入
- コンテナ化(Docker化)
- インフラのコード化
- オートスケールの設定
- デプロイの自動化
- 閉域網接続
- 自動化による運用効率の改善
- ログベースでの不具合調査
  

## シフトプラス株式会社での業務経歴
【プロジェクト概要】
- 取り込んだCSVからPDFを生成するサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）での利用に限らず、インターネットからの利用も可能にする設計/構築
- 定期的にCSVを取り込むAWS Batch　PDFを生成するためのAWS Batch起動上限100に設計

【発揮したバリュー】
Terragruntを使いこれまでよりも迅速に、運用しやすいインフラを構築。
【プロジェクト概要】
- 決裁を紙からWEBへ変更するためのWorkflowサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）での利用に限らず、インターネットからの利用も可能にする設計/構築

### AWSインフラ基盤のコスト削減　(2023年〜2024年)
【プロジェクト概要】
削減内容
- 各プロジェクトdev環境のNatGatewayをNatInstanceに変更
- Savings Plansの導入提案
- InterfaceEndpointの共通化
- コストの大きいデータベースは検討中

【発揮したバリュー】
各プロジェクトのランニングコストを削減し売り上げに貢献。

### AWSインフラ基盤の設計/構築　(2023年〜2024年)
【プロジェクト概要】
- 自治体向けAIサービスのAWSインフラ基盤の設計/構築
- 総合行政ネットワーク（LGWAN）からの閉域網接続可能なAWSインフラ基盤の設計/構築

【発揮したバリュー】
Terraformを使いインフラを構築し、運用しやすい環境を構築。

【発揮したバリュー】
Terragruntを使いこれまでよりも迅速に、運用しやすいインフラを構築。
【プロジェクト概要】
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

## 株式会社フィクラ通信技術研究所での業務経歴
### アカウント認証の設定変更　(2022年〜)
【プロジェクト概要】

- Windowsバージョンアップに伴いLinuxサーバのアカウント連携の仕組みを変更。
- Windowsバージョンアップで使用不能になる認証機能CAAC/LDAPの設定を削除し、新たにKerberos認証の設定を導入。

 ### データベースのインターコネクト設定変更(2022年〜)
【プロジェクト概要】

- データベースインターコネクトで設定されているvmnicの設定変更。
- 1本のアップリンクが設定されていたvmnicを2本に変更。

【発揮したバリュー】
単一障害点だった接続を冗長構成に変更。

 ### サービス終了作業(2022年〜)
【プロジェクト概要】

- サービス終了に伴う使用中のサーバの停止、設定変更作業。
- LDAPの設定変更、CAACの設定変更、NASの削除、Enterprise Cloud vLB/vFWの削除、ECのサーバ停止、LBの設定変更作業、設定変更による設計書の修正。

【発揮したバリュー】
ネットワーク機器以外も対応。

 ### Forti Managerの設計作業(2022年〜)
【プロジェクト概要】

- FortiGate一括管理するため導入。
【発揮したバリュー】
導入したFortiGateを運用効率を改善
 ### FortiGate Firewallの設計作業(2022年〜)
【プロジェクト概要】

- 既存のFirewall (Check Point) のサービス終了に伴い、新しいFirewall (FortiGate) への変更作業。

【発揮したバリュー】
新Firewallを導入し通信を制御。
 
  ### CISCO L2SWの構築(2022年〜)
【プロジェクト概要】

- Cisco L2スイッチを構築。

## 株式会社創生ハウジングでの業務経歴

### 不動産管理物件への申込対応 　(2021年〜2022年)
- 株式会社マストでの経験を活かし、柔軟な審査基準を導入

### 不動産賃貸営業　(2021年〜2022年)
- 株式会社マストでの経験を活かし、賃貸営業を行う

【発揮したバリュー兼感想】
未経験からエンジニアになるのが難しく、知り合いの会社で、営業、管理業務をしながら、一年間、短い期間ですが、業務を手伝いながらエンジニアの勉強をさせてくれた会社に本当に感謝。
ガッツリの営業職ではなく管理メインだったので休日も多く勉強する時間を確保できた。

## 株式会社マストでの業務経歴　(2021年〜2022年)
- 未経験で入社したが、上司にも恵まれ、やる気と根性で賃貸営業を行う

【発揮したバリュー】
コンスタントに売り上げ、会社の利益に貢献
月の平均売上およそ130万円
