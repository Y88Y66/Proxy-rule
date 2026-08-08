# Proxy-rule

Personal Shadowrocket routing rules and configuration backups. This repository contains only public rules and configuration files. Proxy nodes, subscription URLs, credentials, and certificates are intentionally excluded.

## Structure

- `shadowrocket/default.conf` - active Shadowrocket configuration.
- `shadowrocket/backups/` - dated snapshots created before major changes.

## Active Configuration URL

```text
https://raw.githubusercontent.com/Y88Y66/Proxy-rule/main/shadowrocket/default.conf
```

## Maintenance

1. Update `shadowrocket/default.conf` for normal rule changes.
2. Before a substantial rewrite, copy the current file into `shadowrocket/backups/` with a dated filename.
3. Never commit proxy nodes, subscription URLs, tokens, passwords, or certificates.
