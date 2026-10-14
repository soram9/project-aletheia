# Security and Publication Boundaries

## Scope and status

This repository contains public project documentation. It does not provide a deployable product or supported software releases, and these documents do not establish that security controls have been implemented or audited.

Security measures described elsewhere in the documentation are goals or evaluation criteria unless supporting evidence explicitly establishes their implementation and validation.

## Material that must remain private

Do not publish:

- Credentials, access tokens, passwords, private keys, recovery codes, or secret-bearing configuration.
- Private engineering records, deployment configurations, or detailed infrastructure diagrams.
- Operational endpoints, private hostnames, network addresses, remote-access details, or access-control mappings.
- Personal knowledge-base contents, conversation exports, backups, or identifying information about other people.
- Logs, screenshots, attachments, or metadata that disclose any of the above.

Public examples should use synthetic data and clearly identified placeholders. A value should not be treated as safe merely because it looks harmless.

## Publication review

Before committing or attaching material:

1. Confirm that it belongs in the public repository and that sharing it is authorized.
2. Inspect the full content, including links, examples, embedded files, and metadata.
3. Remove private environment details rather than copying private records and relying only on automated redaction.
4. Check that implementation and security claims have supporting evidence.
5. Review the diff and affected links before publication.

Automated secret scanning, if available, can supplement this review. It does not replace it, and no scanning configuration is asserted here.

## Reporting a concern

Do not post credentials, personal data, private deployment information, or sensitive exploit details in public issues or pull requests.

A dedicated private reporting channel has not been established in this document. If the repository offers a private vulnerability-reporting option, use it for sensitive details. Otherwise, request a private reporting method through a public issue containing only a general, non-sensitive description. Wait for a private channel before sharing sensitive material.

No response-time commitment or security support guarantee is made.

## If sensitive material is published

For a future incident, revoke or rotate exposed credentials promptly, assess the scope of disclosure, and remove the material through an appropriate remediation process. Deleting a file from the current branch does not remove earlier commits or copies held by others.

Keep incident records private unless a sanitized public account has been explicitly approved.
