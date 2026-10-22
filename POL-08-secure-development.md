# Secure Development Policy

**Owner:** Engineering Lead
**Review Date:** 22 April 2027
**Status:** Draft

## Purpose
Reduce security weaknesses in software and configuration.

## Scope
Code, scripts, APIs, dependencies and infrastructure configuration.

## Rules
1. Every production code change must receive review by another person before merge.
2. Secrets must not be hard-coded in source files.
3. Supported repositories must run dependency and secret scans.
4. Critical and High findings must be fixed or formally risk-accepted before release.
5. Production systems must not use default credentials.
6. Authorisation checks must be tested for endpoints handling sensitive data.
7. Emergency changes must receive retrospective review within two business days.

## Roles
Developers follow secure practices; reviewers inspect changes; Engineering owns remediation.

## Exceptions
Exceptions require risk documentation, approval and an expiry date.

## Review
Review every six months.
