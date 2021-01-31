# serverless-python-template
serverless frameworkでpythonを使用する時のテンプレートです
 
# Requirement
* python（v3.8）
* serverless（v2.8.0）
 
# Installation
serverless frameworkのインストール 
```bash
npm install -g serverless
```

# Usage（環境別）

## 設定（serverless.yml）の確認
---
### 開発環境
    sls print --profile dev
### ステージング環境
    sls print --profile stg
### 本番環境
    sls print --profile prod

## デプロイ
---
### 開発環境
    sls deploy --profile dev
### ステージング環境
    sls deploy --profile stg
### 本番環境
    sls deploy --profile prod

## デプロイ済みサービスの削除
---
### 開発環境
    sls remove --profile dev
### ステージング環境
    sls remove --profile stg
### 本番環境
    sls remove --profile prod

# Author
eito.okuno
