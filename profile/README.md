# Nautilus by Verne Software

**Sign-in and users for European SaaS teams.**

[![Website](https://img.shields.io/badge/Website-vernesoft.com-blue?style=flat-square)](https://vernesoft.com)
[![Docs](https://img.shields.io/badge/Docs-docs.vernesoft.com-blue?style=flat-square)](https://docs.vernesoft.com)

Nautilus gives your product registration and login, two-factor sign-in, your users'
organizations and roles, an audit log, and automatic deletion of inactive accounts on
the retention period you set for the GDPR. Webhooks, scheduled jobs and Telegram
sign-in are part of the same product, in one plan priced by monthly active users:
Free up to 1,000, Pro €99, Advanced €199.

## What it is built on

- **Sign-in and users** runs on [Ory Kratos](https://github.com/ory/kratos), unmodified.
- **Webhooks** run on [Svix](https://github.com/svix/svix-webhooks), the open-source server.
- **Scheduled jobs** run on our own scheduler, written in Rust.
- Our own layer around them (the gateway, the dashboard, organizations and roles,
  automatic deletion, the audit log) is Rust and Nuxt.

Servers are in France, at OVHcloud, with daily encrypted backups kept in a separate
data centre. Verne Software is registered in Serbia. You can have your users exported
with their password hashes on request.

## SDKs

| Language | Repository | Package |
|:-|:-|:-|
| Node.js | [vrn-sdk-node](https://github.com/Verne-Software/vrn-sdk-node) | `@verne-software/sdk` on npm |
| PHP | [vrn-sdk-php](https://github.com/Verne-Software/vrn-sdk-php) | `vernesoft/sdk` on Packagist |
| Python | [vrn-sdk-python](https://github.com/Verne-Software/vrn-sdk-python) | `vernesoft` on PyPI |
| Rust | [nautilus-rs](https://github.com/Verne-Software/nautilus-rs) | `nautilus-rs` on crates.io |

## Who answers

Verne Software is [Max Zhuk](https://in.zhukmax.com/). Questions go to
[support@vernesoft.com](mailto:support@vernesoft.com).

---

[Create a free account](https://app.vernesoft.com/registration) · [Plans](https://vernesoft.com/pricing) · [Docs](https://docs.vernesoft.com)
