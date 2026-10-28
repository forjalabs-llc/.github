# Security policy

## Repository privacy and access

Product source code and internal operations are private by default. Public content
is limited to deliberately approved company information, support/legal pages, and
general contribution standards. Publishing code requires an explicit owner decision.
Do not attach customer records, private builds, credentials, or internal logs to
public issues. CI and other integrations should receive only the repository access
and secrets they need. Two-factor authentication and independently stored recovery
material are required operational safeguards, not substitutes for access review.

## Reporting a vulnerability

Please use **Security → Report a vulnerability** in the affected repository to submit a private report.

Include the affected version or commit, reproduction steps, likely impact, and a minimal proof of concept. Remove tokens, personal data, and unrelated confidential material.

Do not publish an exploit or sensitive details in a public issue. If the private reporting button is unavailable, email support@forjalabs.dev with a short description and the affected project. Do not include credentials, financial records, health records, or unrelated confidential material in the initial message; arrange a suitable channel for sensitive evidence with the maintainer.

## Supported versions

Unless a project states otherwise, security fixes target its default branch. No support period or response-time guarantee is implied.

## Handling secrets

Revoke or rotate an exposed credential immediately. Deleting a file or commit does not invalidate a credential. Use repository / environment secrets or a dedicated secret manager and grant only the permissions needed.
