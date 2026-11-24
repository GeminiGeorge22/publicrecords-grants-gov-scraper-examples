# Grants.gov Scraper — 使用例

募集中の米連邦助成金：機関、締切、対象資格、公式リンク。

このActorは**あなた自身の**Apifyアカウント（APIトークンまたはOAuth）で実行します。利用料はApifyの無料または有料プランであなたに課金されます。

## リンク
- [Apify Storeのページ](https://apify.com/publicrecords/grants-gov-scraper)
- [Apify MCPエンドポイント](https://mcp.apify.com?tools=publicrecords/grants-gov-scraper)
- [n8n / Make / Zapier / Pipedreamのレシピ](https://github.com/GeminiGeorge22/publicrecords-mcp/tree/main/templates)
- [公開スナップショット（Hugging Face）](https://huggingface.co/datasets/Publicrecords/us-open-federal-grants)

## 同期実行

`APIFY_TOKEN` に自分のApifyトークンを設定してください。リポジトリにコミットしないでください。

```bash
export APIFY_TOKEN=YOUR_TOKEN
python3 examples/python/run.py
# node examples/javascript/run.js
# bash examples/curl/run.sh
```

Python・JavaScript・curlの例は `examples/` にあります。作者: Public Records。ライセンス: MIT。このリポジトリにGitHub Actionsはありません。

READMEs: [English](README.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [Português](README.pt.md)
