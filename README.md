# sing-box rulesets

For personal use, easy to update

## CDN URL

```sh
https://testingcf.jsdelivr.net/gh/ohotto/singbox_rulesets@main/<path>
#for example
https://testingcf.jsdelivr.net/gh/ohotto/singbox_rulesets@main/direct_address.json
```

## direct_address.json

Bypass websites with blocked foreign IPs but match proxy

- latexlive.com
- Steam download nodes (store goes through proxy normally)

## direct_process.json

Bypass processes that don't use a proxy (mainly for tun mode)

- WeChat
- qBittorrent

## bypass_hk.json

Services unavailable on Hong Kong nodes, it is recommended to add a outbound selector to select non-Hong Kong nodes.

- OpenAI
- Claude
- Gemini

