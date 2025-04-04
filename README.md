# test-boatrace-infra
boatraceインフラ

## setup
```
bash -eu setup_base.sh {環境識別子}
bash -eu deploy.sh {環境識別子}
```
注: 環境識別子は、envsディレクトリ内のファイル名称に対応

## delete
マネジメントコンソールからCloudFormationページを開き、作成したスタックを手動で削除する。

## デプロイ後
スキーマ、ロール、ユーザ、テーブル作成、リンクサーバ設定を行う。
