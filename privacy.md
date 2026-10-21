---
title: Privacy Policy
permalink: /privacy/
---

# Privacy policy — SQL DB Data Transfers

**Last updated:** 21 October 2026

SQL DB Data Transfers ("the app") is a macOS tool for copying tables between SQL
databases. The app runs on your Mac and connects directly to databases you choose.
This policy explains what the app does and does not do with your data.

## What we collect

**Nothing.** The developer does not collect, receive, store, or transmit any data
about you or your use of the app. The app has no analytics, no telemetry, no
crash reports, no accounts, and no sign-in. The app does not phone home.

## What the app stores on your Mac

- **Connection details** (database name, host, port, user, SSL preference, schema,
  and the display name you chose) are saved in a JSON file inside the app's
  sandbox container, at:
  `~/Library/Containers/com.bshreeves.sqldbdatatransfers/Data/Library/Application Support/SQLDBDataTransfers/connections.json`
- **Passwords and tokens** for your database connections are stored in the macOS
  Keychain, keyed by a per-connection identifier. The Keychain is managed by
  macOS, protected by your login password, and never leaves your Mac.
- **UI preferences** (pane sizes, the last-used ratios) are stored in standard
  macOS `UserDefaults`.

## Where your data goes

- **Between your Mac and your databases, directly.** The app opens TLS
  connections (or non-TLS when you turn SSL off) from your Mac to the database
  hosts you specify. No third-party service sits between them.
- **Nowhere else.** The app does not send anything to the developer, to Apple
  beyond what the operating system itself handles, or to any other party.

## Database contents

- **Databases you connect to.** The app reads from the source database you pick
  and writes to the target database you pick. Everything stays between your Mac
  and those databases. The developer has no access to the data.

## Children

The app is not directed at children. It is a developer utility rated 4+ because
it contains no objectionable content.

## Changes to this policy

If this policy changes, the new version will replace this document in a future
app release and the "Last updated" date above will change.

## Contact

Questions about this policy or the app:  
Brian Shreeves — brian.shreeves@gmail.com
