# Terraform Lambda Hello World

## プロジェクト概要
シンプルなHello Worldの Lambda 関数をTerraformでデプロイするサンプルプロジェクト。


## セットアップ

### 1. 環境設定
- Terraformをインストール
- AWS CLIを設定

### 2. AWS IAM許可ポリシー
- IAMFullAccess
- AWSLambda_FullAccess
- AmazonAPIGatewayAdministrator

### 3. デプロイ

```bash
zip lambda.zip index.js &&  terraform apply -auto-approve
```

### 4. クリーンアップ
```bash
terraform destroy -auto-approve
```
