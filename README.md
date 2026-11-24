**READMEs:** [English](README.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Português](README.pt.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md) · [한국어](README.ko.md)

# Grants.gov Scraper — examples

Open US federal grants: agency, deadline, eligibility and source link.

The Actor runs on **your** Apify account (API token or OAuth). Usage is billed to you on Apify's free or paid tier.

## Links
- [Apify Store page](https://apify.com/publicrecords/grants-gov-scraper)
- [Apify MCP endpoint](https://mcp.apify.com?tools=publicrecords/grants-gov-scraper)
- [n8n / Make / Zapier / Pipedream recipes](https://github.com/GeminiGeorge22/publicrecords-mcp/tree/main/templates)
- [Public snapshot dataset (Hugging Face)](https://huggingface.co/datasets/Publicrecords/us-open-federal-grants)

## Run a sync job

Set `APIFY_TOKEN` to your own Apify token. Do not commit it.

```bash
export APIFY_TOKEN=YOUR_TOKEN
python3 examples/python/run.py
# node examples/javascript/run.js
# bash examples/curl/run.sh
```

Examples in Python, JavaScript and curl are in `examples/`. Author: Public Records. License: MIT. No GitHub Actions in this repository.

