### オープンソースへの貢献

マージされたプルリクエスト

- **[aws/aws-cdk-cli](https://github.com/aws/aws-cdk-cli)**：[fix(cli): cdk migrate --from-scan fails when stdout is not a terminal](https://github.com/aws/aws-cdk-cli/pull/2146)<br>
  出力先が端末でないとき（CI、パイプ、ファイルへのリダイレクト）に`cdk migrate --from-scan`が異常終了していた不具合を修正。
- **[pulumi/pulumi](https://github.com/pulumi/pulumi)**：[Fix silent `up --plan` failure for whole-resource stack outputs](https://github.com/pulumi/pulumi/pull/25629)<br>
  スタック出力にリソースをそのまま渡すと、`pulumi up --plan`がエラーを表示しないまま失敗していた不具合を修正（Node.js SDKとエンジン）。
- **[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)**：[fix(deploy): brace shell vars before full-width punctuation for bash 3.2](https://github.com/TencentCloud/TencentDB-Agent-Memory/pull/1613)<br>
  macOS標準のbash 3.2では`$VAR`の直後の全角記号が変数名の一部と解釈され、デプロイスクリプトが止まっていた問題を修正（5ファイル13か所）。
- **[labring/FastGPT](https://github.com/labring/FastGPT)**：[fix(deploy): define vector network in v4.14 compose template](https://github.com/labring/FastGPT/pull/7914)<br>
  v4.14とMilvusを選んだワンクリックインストールで、生成されるdocker-compose.ymlが未定義のネットワークを参照し、起動できなかった問題を修正。
- **[srbhr/Resume-Matcher](https://github.com/srbhr/Resume-Matcher)**：[docs: add Windows 11 setup instructions](https://github.com/srbhr/Resume-Matcher/pull/1021)<br>
  Windows 11（PowerShell）向けのセットアップ手順を追加。
