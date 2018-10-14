# 概要
AD-CTDは、株式会社アクティブディフェンス研究所が、インターネットから弊社独自の技術とOSSを組み合わせた観測システムにて、悪性広告、スパム、Exploit Kitを経路としたマルウェア感染に関する脅威情報を収集、提供するサービスです。弊社の研究調査から、いわゆるバラ撒き型においても、国や地域によって観測されるサイバー攻撃に偏りがあり、弊社では主に日本からの観測できるオープンな脅威についてフォーカスしています。AD-CTDでは、観測した情報を元に、他の公開情報及び攻撃手法の詳細化を図り、その付加情報を加えた上で配信しております。

# Active Defense Cyber Tactical Database API仕様及びJSONクライアント
ドキュメント: [https://www.activedefense.co.jp/adctd-api-spec/][1]

# APIエンドポイント
## v2(最新)
- https://api.ctd.activedefense.co.jp/v2/malicious/uri

## v1(deprecated)
- https://api.ctd.activedefense.co.jp/v1/malicious/uri

# API Callサンプル
```
$ curl https://api.ctd.activedefense.co.jp/v2/malicious/uri?type=ek \                                 
  --header 'x-api-key:YOUR_ACCESS_KEY_FOR_ADCTD'
```

# 費用
## 二次配信不可ライセンス（No redistribution License)
- 価格: 月額35万円（税抜）
- ご契約組織内及びご契約組織が利用するサービス・プロダクトでのご利用のみを許可

## 二次配信可能ライセンス（redistribution License）
- 費用：ご相談
- 制限無し

## コミュニティライセンス（Community License)
- 費用：なし
- 本サービスで利用しているOSSのコントリビュータは、本サービスを1年間単位で無償でご利用可能です。

# ご試用について
1ヶ月間、無料でお試し頂けます。APIキーを弊社から発行致します。
タイトルに"CTDテスト利用申込"、本文に下記の情報を沿えて、ctd-admin &#064; activedefense.co.jpにお送りください。
- ご連絡先氏名
- ご連絡先メールアドレス
- ご所属
- ご希望ライセンス
- ご利用目的

# 連絡先
Mail:
ctd-info &#064; activedefense.co.jp

# 利用しているOSS（特に脅威情報の解析について）
- EKTotal, StarC: @nao_sec (https://github.com/nao-sec)
- EKFiddle: @malwareinfosec (https://github.com/malwareinfosec/EKFiddle)
- [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.

# For overseas user and customer
## Overview
AD-CTD(Cyber Tactical Database) provides threat intelligence based on our systematic observation of the Internet by Active Defense Institute, Ltd.. Currently, our observation focus cyber threat in Japan.
Our observation system observe malvertising, malspam and Exploit Kits. Our API show observed threat as enriched indicator of compromise.
AD-CTD API provides as JSON format only.

# Active Defense Cyber Tactical Database API Specification and API clients
Swagger generated docs: [https://www.activedefense.co.jp/adctd-api-spec/][1]

# API Endpoints
- https://api.ctd.activedefense.co.jp/v2/malicious/uri

# API Call Sample
```
$ curl https://api.ctd.activedefense.co.jp/v2/malicious/uri?type=ek \                                 
  --header 'x-api-key:YOUR_ACCESS_KEY_FOR_ADCTD'
```
# Subscriptions
## No redistribution License
- Price: 3200 USD/Month
- This lisense allow to use our intelligence in your organization ONLY.

## Redistribution License
- Price: Contact us
- No limit for use and redistribution.

## Community License
- Price: Free
- Currently, contributor of EKTotal, EKFiddle and StarC can use this license.

# Trial
You can use this API for trial a month.
Please contact: ctd-admin &#064; activedefense.co.jp
- Name
- Email
- Organization
- License
- Reason for trial

# Contacts
Mail:
ctd-info &#064; activedefense.co.jp

Web: 
https://www.activedefense.co.jp/

### Acknowledgements
#### Thanks!
- EKTotal, StarC: @nao_sec (https://github.com/nao-sec)
- EKFiddle: @malwareinfosec (https://github.com/malwareinfosec/EKFiddle) 
- swagger JSON built by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.



[1]: https://www.activedefense.co.jp/adctd-api-spec/
