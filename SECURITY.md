**English** | [Русский](SECURITY.ru.md)

# Security policy

## Reporting a vulnerability

Please report a vulnerability **privately**, in one of two ways:

- GitHub: **Security → Report a vulnerability** in the affected repository (a private advisory only the maintainer sees);
- email: **support@vazie.app**, with "Security" in the subject.

**Do not open a public issue, discussion or pull request for a security problem**, and do not publish details before
a fix is released.

Never include real credentials: a password database, a key file, a `vless://` link or a subscription link. Describe
the problem with made-up data (`example.com`, documentation addresses such as `192.0.2.1`) instead.

What helps:

- the app version and the operating system version;
- what an attacker can do, and what they need first (physical access, another app on the device, a network position);
- steps to reproduce, or a proof of concept that touches no real account or server.

## What happens next

- An acknowledgement within 7 days.
- An assessment and, for a confirmed issue, a plan for the fix.
- The fix in a release, and credit in its notes unless you prefer to stay anonymous.

There is no bug bounty.

## Scope

Every repository in this organization is in scope. Each project documents its own threat model in its `docs`
folder, and known platform limitations are listed there rather than treated as vulnerabilities.
