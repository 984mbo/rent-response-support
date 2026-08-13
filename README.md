# RENT RESPONSE サポート窓口

このリポジトリは、[RENT RESPONSE](https://rent-response-pages.pages.dev/) の公開問い合わせ・障害案内窓口です。サービス運営主体は **RENT RESPONSEプロジェクト（984mbo）** です。

## 問い合わせ方法

- 操作方法、不具合、表示・データ出典に関する問い合わせは、[公開Issueを作成](https://github.com/984mbo/rent-response-support/issues/new/choose)してください。
- 脆弱性、個人情報の意図しない露出、第三者が案件へアクセスできる可能性などは、公開Issueへ書かず、[非公開で脆弱性を報告](https://github.com/984mbo/rent-response-support/security/advisories/new)してください。
- 賃貸借契約や家賃値上げに関する個別相談は、本窓口では回答できません。[東京都の家賃値上げ相談案内](https://www.shouhiseikatu.metro.tokyo.lg.jp/sodan/kinkyu/20260303.html)または消費者ホットライン `188` を利用してください。

公開Issue・非公開報告のどちらもGitHubアカウントが必要で、報告内容はGitHub上に保存され、リポジトリ管理者が確認します。GitHubの利用には[GitHub Privacy Statement](https://docs.github.com/ja/site-policy/privacy-policies/github-general-privacy-statement)が適用されます。

## 報告へ記載してはいけない情報

公開Issueだけでなく非公開報告にも、通知画像・PDF、氏名、住所、家賃、契約情報、Cookie・token、案件ID、ダウンロードしたPDF・ZIP、秘密値、画面全体のスクリーンショットを添付しないでください。発生日時、利用したページURL、個人情報を除いた操作手順、画面のエラーコード、表示されていればCF-Rayだけを記載してください。追加情報が必要な場合は、運営側から安全な受け渡し方法を案内します。

## 対応目標

- 重大なセキュリティ・プライバシー報告：受領から24時間以内に一次確認
- サービス停止・OCR利用不能：2営業日以内に一次回答
- 一般的な不具合・データ出典・操作案内：5営業日以内に一次回答

これは目標時間であり、解決時間を保証するものではありません。稼働状況と既知障害は[障害・メンテナンスIssue](https://github.com/984mbo/rent-response-support/issues?q=is%3Aissue+label%3Aincident)で案内します。

## インシデント対応

検知、受付、封じ込め、影響確認、復旧、利用者通知、再発防止の手順は [INCIDENT_RESPONSE.md](INCIDENT_RESPONSE.md) に公開しています。実在の個人情報、攻撃手順、秘密値、未修正の脆弱性は公開Issueへ掲載しません。
