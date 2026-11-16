# Vocpuli Amazon Workbench Updates

Public release channel for verified updates to the Vocpuli Amazon Workbench.

## Scope

This repository may contain only:

- checksum-verified update packages;
- public release notes;
- an HTTPS update manifest containing version, download URL, SHA-256 and release date;
- non-sensitive installation documentation.

## Security rules

Never commit or upload:

- Amazon SP-API, Ads API or other access credentials;
- refresh tokens, client secrets, API keys or private certificates;
- seller, order, finance, inventory, advertising or customer data;
- local configuration files, logs, backups or reports;
- personal information.

Update clients must download packages over HTTPS and verify the published SHA-256 before installation. A failed verification must stop the upgrade and preserve the installed version.

## Status

Repository initialized. No production update package has been published yet.
