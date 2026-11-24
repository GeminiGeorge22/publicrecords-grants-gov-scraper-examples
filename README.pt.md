# Grants.gov Scraper — exemplos

Subsídios federais abertos dos EUA: agência, prazo, elegibilidade e ligação à fonte.

O Actor corre na **sua** conta Apify (token de API ou OAuth). O uso é cobrado a si, no plano gratuito ou pago da Apify.

## Ligações
- [Página no Apify Store](https://apify.com/publicrecords/grants-gov-scraper)
- [Endpoint MCP da Apify](https://mcp.apify.com?tools=publicrecords/grants-gov-scraper)
- [Receitas n8n / Make / Zapier / Pipedream](https://github.com/GeminiGeorge22/publicrecords-mcp/tree/main/templates)
- [Conjunto de dados público (Hugging Face)](https://huggingface.co/datasets/Publicrecords/us-open-federal-grants)

## Executar uma chamada síncrona

Defina `APIFY_TOKEN` com o seu próprio token da Apify. Não o envie no repositório.

```bash
export APIFY_TOKEN=YOUR_TOKEN
python3 examples/python/run.py
# node examples/javascript/run.js
# bash examples/curl/run.sh
```

Há exemplos em Python, JavaScript e curl em `examples/`. Autor: Public Records. Licença: MIT. Este repositório não usa GitHub Actions.

READMEs: [English](README.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [Português](README.pt.md)
