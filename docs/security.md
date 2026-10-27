# Security and Publication Policy

This repository is intentionally **documentation-only**.

## Do not publish

- Production source code, executables, installation packages, or private dependencies.
- Secrets, credentials, API keys, tokens, private keys, or environment files.
- Customer names, personal data, orders, invoices, fiscal documents, or database exports.
- Internal IP addresses, hostnames, endpoint URLs, network diagrams, or authentication details.
- Raw logs, crash dumps, or screenshots containing private information.

## Before adding screenshots

1. Use test data and nonproduction environments.
2. Remove account identifiers, customer data, network details, and system notifications.
3. Review the entire frame, including window titles, taskbars, and browser tabs.
4. Obtain permission for any third-party trademarks or confidential UI.
5. Review the final exported image separately before committing.

## Before every public commit

Review `git diff --cached`, verify only approved documentation/assets are staged, and scan for accidental sensitive strings. A clean working tree is not a security audit.

## Ownership

Valorium commercial software remains proprietary. This showcase does not distribute or license its implementation.
