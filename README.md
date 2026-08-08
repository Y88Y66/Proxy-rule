# Proxy-rule

Personal routing rules for proxy clients. This repository contains only public routing rules and configuration templates. Proxy nodes, subscription URLs, credentials, and certificates are intentionally excluded.

## Structure

- `shadowrocket/default.conf` - active Shadowrocket configuration.
- `shadowrocket/backups/` - dated Shadowrocket snapshots before major changes.
- `v2ray/` - v2rayN and v2rayNG routing rules. Its future active rule file and snapshots are maintained inside this folder.

## Active Shadowrocket URL

```text
https://raw.githubusercontent.com/Y88Y66/Proxy-rule/main/shadowrocket/default.conf
```

## Maintenance

1. Update each client only inside its own folder.
2. Before a substantial rewrite, create a dated snapshot in that client's `backups/` folder.
3. Never commit proxy nodes, subscription URLs, tokens, passwords, or certificates.
