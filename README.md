# Shadowrocket-rule

Personal Shadowrocket rule configuration for public hosting and version tracking.

## Files

- `config/default.conf` - Shadowrocket configuration exported from the app. This repository intentionally hosts routing rules only and should not include proxy node credentials.

## Raw URL

Use this raw URL when importing or updating the configuration:

```text
https://raw.githubusercontent.com/Y88Y66/Shadowrocket-rule/main/config/default.conf
```

## Privacy checklist

Before committing future exports, verify that the file does not contain:

- proxy node URLs such as `ss://`, `ssr://`, `vmess://`, `vless://`, `trojan://`, `hysteria://`, or `tuic://`
- `[Proxy]`, `[Remote Proxy]`, `[Proxy Group]`, `[Subscription]`, or `[MITM]` sections with private credentials
- passwords, tokens, certificate passphrases, private domains, or subscription URLs
