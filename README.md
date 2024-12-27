
### タブ補完を有効化する
```bash
$ terraform -install-autocomplete
```
### 既存のインフラリソースをTerraformリソースに紐づけ
```bash
$ terraform import
```
### Terraformモジュールのテストを実行
```bash
$ terraform test
```
### リモートの状態に合うようにステートファイルをアップデート
```bash
$ terraform refresh
```
### パスワードなどoutputされた値を確認できる
```bash
$ terraform output
```
### リソース間の依存関係を可視化（graphvizをinstallすると画像に変換できる）
```bash
$ terraform graph
```
- terraform init
- terraform plan
- terraform apply
- terraform destroy
- データソースを使ってAWSなどの既存リソースを参照できる(サブネットIDを調節指定でも可だが)
