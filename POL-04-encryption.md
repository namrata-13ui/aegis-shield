# Encryption Policy

**Owner:** Security Lead
**Review Date:** 22 April 2027
**Status:** Draft

## Purpose
Protect sensitive data in storage and transit.

## Scope
Confidential and Restricted data, backups and authentication secrets.

## Rules
1. Sensitive data sent over untrusted networks must use TLS 1.2 or later.
2. Confidential and Restricted data at rest must be encrypted using an approved method.
3. Encryption keys must be stored separately from the data they protect.
4. Keys and production secrets must not be committed to source control.
5. Access to keys must be limited to authorised roles.
6. System owners must document encryption settings and key ownership.
7. Encryption exceptions must be approved and given an expiry date.

## Roles
Security defines standards; system owners implement them; IT manages keys.

## Exceptions
Written approval and compensating controls are required.

## Review
Review every six months.
