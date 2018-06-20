## 概要
日本への脅威にフォーカスした脅威情報の配信サービスの提供を開始します。
弊社独自のマルウェア配信プラットフォーム観測と自動解析を用い、マルウェアの配信元を継続的に監視しており、1時間おきに日本国内からの到達可能性やドメイン・IP情報を更新し配信しております。
JSON形式でのご提供になりますが、既にご要望頂いているTAXII/STIX2.0対応についても順次進めて参ります。

## 試用期間について
現在は試験公開中であり、7/31までは無料でお使い頂けます。
通常、1ヶ月の試用期間を設けております。

# Active Defense Cyber Tactical Database API Specification and API clients
Swagger generated docs: [https://www.activedefense.co.jp/adctd-api-spec/][1]

# API Endpoints
- https://api.ctd.activedefense.co.jp/v1/malicious/uri

# API Call Sample
```
$ curl https://api.ctd.activedefense.co.jp/v1/malicious/uri?type=ek \                                 
  --header 'x-api-key:YOUR_ACCESS_KEY_FOR_ADCTD'
```
# Plan
## 二次配信不可ライセンス
- 費用：ご相談
- ご契約者様の組織内及びサービス・プロダクトでのご利用のみを許可

## 二次配信可能ライセンス
- 費用：ご相談
- 制限無し

# Trial
1ヶ月間、無料でお試し頂けます。APIキーを弊社から発行致します。
タイトルに"CTDテスト利用申込"、本文に下記の情報を沿えて、ctd-admin &#064; activedefense.co.jpお送りください。
- ご連絡先氏名
- ご連絡先メールアドレス
- ご所属
- ご希望ライセンス

# Contacts
Mail:
ctd-info &#064; activedefense.co.jp

Web: 
https://www.activedefense.co.jp/
#### Acknowledgements 
This is a swagger JSON built by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.

[1]: https://www.activedefense.co.jp/adctd-api-spec/
