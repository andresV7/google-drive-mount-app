# google-drive-mount-app

Personal-use OAuth 2.0 client for [rclone](https://rclone.org/).

This repository serves as the **homepage** and **privacy policy** for a Google Cloud OAuth client used exclusively by the account owner to mount their own Google Drive as a local filesystem (rclone FUSE mount) on their personal Linux computer.

## What this app does

- Uses a private OAuth 2.0 client ID (Google Cloud, Desktop app type) with the Google Drive API scope `https://www.googleapis.com/auth/drive`.
- Authorizes **rclone** to read and write files between the owner's own Google Drive and their own local machine.
- It is **not** distributed to other users and has no backend, no web interface, and no analytics.

## Privacy policy

See [PRIVACY.md](PRIVACY.md).

## Owner

Andres Villamizar — https://github.com/andresV7
