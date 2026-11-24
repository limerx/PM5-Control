# Security policy

**English** | [Français](SECURITY.fr.md)

## Status and scope

PM5 Control is experimental. No supported production release or installation package is currently available. Use only with explicit authorization and respect organizational device-management policies. The project does not grant additional Android privileges.

## Reporting

For non-sensitive bugs, use the repository issue tracker. For vulnerabilities, request a private reporting channel from the maintainer without disclosing exploit details publicly. If GitHub private vulnerability reporting is enabled, prefer it.

Do not include real RFID identifiers, card contents, private dictionaries, credentials, device serial numbers or unredacted logs in reports.

## Review priorities

- Local HTTP, WebSocket and TCP isolation and access control.
- Safe process startup, disconnection and shutdown.
- Dependency and source provenance review.
- Sanitization of diagnostic logs and test fixtures.

Loopback binding is not, by itself, authentication or isolation from other local applications. A successful command or matching file hash alone does not establish complete physical readback.
