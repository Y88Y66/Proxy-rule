# Proxy-rule

Personal routing rules for proxy clients. This repository contains only public routing rules and configuration templates. Proxy nodes, subscription URLs, credentials, and certificates are intentionally excluded.

## Structure

- `shadowrocket/default.conf` - active Shadowrocket configuration.
- `v2ray/` - reserved for v2rayN and v2rayNG routing rules in their JSON format.
- `backups/` - dated snapshots before major changes.

## Active Shadowrocket URL

```text
https://raw.githubusercontent.com/Y88Y66/Proxy-rule/main/shadowrocket/default.conf
```

## Maintenance

1. Update the client-specific file in its own folder.
2. Create a dated snapshot in `backups/` before a substantial rewrite.
3. Never commit proxy nodes, subscription URLs, tokens, passwords, or certificates.
