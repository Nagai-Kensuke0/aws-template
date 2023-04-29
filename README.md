# aws-template

## リポジトリの説明

- AWS に色々な構成でインフラ構築を試したいという為のリポジトリです
- 構築した内容を Cloud Formation のテンプレートにしてこのリポジトリにアップロードします
- 各構成は、AWS SAA の学習をする中で問題集などで出てきた内容を参考としています
- ただ構築するだけでなく、その構成の利点などを検証してまとめをアップロードしたいと思っています  
  ex）【Auto Scaling の場合】意図的に負荷をかけてスケーリングすることを確認する

## デプロイコマンド

- autoscaling-template.yaml  
  $ aws cloudformation create-stack --stack-name my-autoscaling-stack --template-body file://autoscaling-template.yaml
