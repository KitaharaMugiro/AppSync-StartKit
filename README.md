# AppSync-StartKit
AppSyncでGraphQLを実装する際のスターターキットです。
実装例とデプロイまでをカバーしています。

# 使い方
npxが使用できる環境で、以下のコマンドを実行する。

```
npx degit https://github.com/KitaharaMugiro/AppSync-StartKit <Directory Name>
```

# 内容
- [x] スキーマ定義
- [x] VTLによるResolverの実装例 
- [x] Dynamoのリソース作成
- [x] CognitoによるAuthorization
- [x] ServerlessFrameworkでのデプロイ

# ワークフロー
1. 新しいデータソースが必要か検討
2. スキーマ情報を適宜追加または更新
3. マッピングリゾルバーを追加または更新

# デプロイ

```
sls deploy -v
```

# 参考
https://www.ragate.co.jp/blog/articles/4064

