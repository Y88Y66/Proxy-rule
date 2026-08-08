# Shadowrocket-rule

Personal Shadowrocket rule configuration for public hosting and version tracking.

## Structure

- `config/default.conf` - active Shadowrocket configuration. Use this file for future changes and daily import/update.
- `backups/default-2026-08-08.conf` - initial exported snapshot. Keep this as a rollback reference and do not edit it unless intentionally replacing the backup.

## Raw URL

Use this raw URL when importing or updating the active configuration:

```text
https://raw.githubusercontent.com/Y88Y66/Shadowrocket-rule/main/config/default.conf
```

## Maintenance workflow

1. Edit `config/default.conf` for normal rule changes.
2. Before major rewrites, copy the current active file into `backups/` with a date-based filename such as `default-YYYY-MM-DD.conf`.
3. Do not put proxy nodes or subscriptions in this public repository.

## Privacy checklist

Before committing future exports, verify that the file does not contain:

- proxy node URLs such as `ss://`, `ssr://`, `vmess://`, `vless://`, `trojan://`, `hysteria://`, or `tuic://`
- `[Proxy]`, `[Remote Proxy]`, `[Proxy Group]`, `[Subscription]`, or `[MITM]` sections with private credentials
- passwords, tokens, certificate passphrases, private domains, or subscription URLs
