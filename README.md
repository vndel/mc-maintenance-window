# mc-maintenance-window

Change-management templates for planned Minecraft network maintenance. Coordinate ingress drain, persistence protection, rollback, validation, and player communication.

## Sequence
1. Announce the UTC window and affected services.
2. Confirm recent backups and restore-test evidence.
3. Drain proxy admission and allow sessions to exit gracefully.
4. Apply one bounded change at a time.
5. Validate login, permissions, economy, world save, and telemetry.
6. Reopen traffic gradually; roll back on failed checks.

A successful process start is not sufficient health validation. MIT licensed.
