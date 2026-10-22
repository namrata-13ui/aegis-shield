# Backup and Recovery Policy

**Owner:** System Owner
**Review Date:** 22 April 2027
**Status:** Draft

## Purpose
Restore critical data and services after loss or disruption.

## Scope
Critical production data, configurations and systems.

## Rules
1. Each critical system must document its recovery time and recovery point objectives.
2. Critical data must be backed up at least daily unless an approved requirement says otherwise.
3. At least one backup copy must be protected from ordinary production-account modification.
4. Backup job success and failure must be recorded.
5. Backup failures must be reviewed within one business day.
6. Critical-system restores must be tested quarterly.
7. Restore-test results and corrective actions must be recorded.

## Roles
System owners define recovery needs; IT operates backups; Security reviews access.

## Exceptions
Exceptions require documented approval and an expiry date.

## Review
Review every six months.
