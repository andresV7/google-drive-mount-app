# Privacy Policy

**App:** Google Drive mount via rclone (personal-use OAuth client)
**Owner:** Andres Villamizar (andresV7)
**Contact:** amvillamizar07@gmail.com

## Scope

This OAuth 2.0 client is a personal, non-distributed application. It is configured in [rclone](https://rclone.org/) to mount the account owner's **own** Google Drive on their **own** computer as a local filesystem.

## What data is accessed

- Files and folders in the owner's Google Drive, accessed only during mount and file operations performed by the owner (reading, writing, listing, syncing).
- OAuth tokens (access and refresh tokens) are stored **only** in the owner's local rclone configuration file (`~/.config/rclone/rclone.conf`) on their personal computer.

## What is NOT done

- No data is collected, stored, sold, or shared with any third party.
- No analytics, telemetry, or tracking of any kind.
- There is no backend server, database, or web interface. Everything runs locally on the owner's machine.

## Data retention

Google Drive content is not retained by this application beyond the local rclone VFS cache on the owner's device, which mirrors files the owner chooses to open. Deleting the local cache directory removes it.

## Revoking access

Access can be revoked at any time from the Google account security page (https://myaccount.google.com/permissions) by removing access for this application, or locally with `rclone config disconnect`.
