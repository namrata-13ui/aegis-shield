# Logging and Monitoring Policy

**Owner:** Security Operations
**Review Date:** 22 April 2027
**Status:** Draft

## Purpose
Provide evidence to detect and investigate security events.

## Scope
Authentication, sensitive-data access, administration and production systems.

## Rules
1. Systems must log successful and failed logins.
2. Privilege changes and security configuration changes must be logged.
3. Logs must include timestamps and relevant actor or system identifiers.
4. Logs must not contain passwords, MFA codes or private keys.
5. Access to logs must be restricted to authorised personnel.
6. Alerts for repeated failed logins must reach a named responder.
7. Alert delivery must be tested and recorded quarterly.

## Roles
System owners enable logs; Security monitors alerts; IT protects log storage.

## Exceptions
Exceptions require written approval and an expiry date.

## Review
Review every six months.
