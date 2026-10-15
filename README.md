# Storechek Pilot downloads

Windows frontend test build for coworkers using an existing Storechek test database.

## Current test build: 0.2.0

- [Download the Windows installer](https://github.com/gyromind/Storechek-downloads/releases/download/v0.2.0-test/Storechek.Pilot_0.2.0_x64-setup.exe)
- [Download the setup guide](https://github.com/gyromind/Storechek-downloads/releases/download/v0.2.0-test/READ-ME-FIRST.txt)
- [Open the test release and release notes](https://github.com/gyromind/Storechek-downloads/releases/tag/v0.2.0-test)

No GitHub account is required to download these files.

**Editing is restricted to the designated development SQL test instance. Connections to coworkers' other servers remain read-only.** Setup does not migrate databases or grant permissions. Installing this version will not enable item editing on your server.

Before installing, configure and test your SQL Server DSN in **ODBC Data Sources (64-bit)**. The normal DSN name and required default database are **BackOfficeSQL**. This build uses Windows authentication and existing Storechek permissions.

The installer is unsigned. This pilot is for testing and does not replace Access. See the setup guide and release notes for requirements, validation, and limitations.

[Previous 0.1.1 test release](https://github.com/gyromind/Storechek-downloads/releases/tag/v0.1.1-test)

This repository contains only download information. Application source code is maintained separately and remains private.
