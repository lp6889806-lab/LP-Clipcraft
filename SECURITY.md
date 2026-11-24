# Security policy

LP Clipcraft runs on your own computer. It does not upload your videos anywhere.

## Reporting a vulnerability

Please do not post exploit details in a public issue.

1. Open the repository's **Security** tab and choose **Report a vulnerability** (GitHub private advisory), or
2. If that is not available to you, open a public issue that only says "security report" (no details) and the maintainer will arrange a private channel.

You can expect a first reply within a few days. Fixes ship on the `main` branch; re-run `LP-Clipcraft-Setup.bat` (or `git pull`) to update.

## Supported version

Only the latest `main` is supported.

## What the app does and does not do

- The studio listens on `127.0.0.1` only, unless you start phone mode, which is protected by a 6-digit PIN.
- Optional diagnostics ("Report a problem") are shown to you first and only sent if you agree.
- Links, user names, e-mails and IP addresses are removed from diagnostics.
