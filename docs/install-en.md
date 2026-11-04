# Install and connect a Windows folder

1. Download `LunaFolderConnector-0.8.2-win-x64.msi` from the [official download page](https://lunalab-ai.com/download/?lang=EN). Compare the release SHA256SUMS.txt with `Get-FileHash .\LunaFolderConnector-0.8.2-win-x64.msi -Algorithm SHA256`. Keep the versioned filename and installer for later maintenance.
2. Run the MSI. It installs for the current Windows user with a self-contained runtime. This is an unsigned preview; ask your administrator if Windows or school policy blocks it.
3. Open LUNA Folder Connector from Start. Under Account, sign in to LUNA and approve the matching browser account and confirmation code. No project selection is needed yet.
4. In My folders, add a folder using OneDrive detection or Browse. Choose a real folder synced by the official OneDrive client. No Entra registration or Microsoft secret is required.
5. Choose a project. Review subfolders, online-only downloads and the project audience before approving intake. Opening the app from a project can suggest a destination; this is never upload consent.
6. Review folder → grant → project and separate receipt, preservation and extraction counts. Add multiple folders and pause or unlink each. The same connections appear under grant/project external connections and My PC and sync management.

## Pause, deletion and updates

Install updates over the existing app as the same Windows user; do not uninstall first. Version 0.8.2 also supports reinstalling the same version. It keeps the already installed package source in a per-user cache so Windows can find it when a downloaded copy has another name. If installation fails, the error screen shows the automatically created MSI log location. Keep that log for support; do not change Windows security policy or remove your settings to repair an installation.

Allowing server intake preserves local global and folder pauses. Offline or signed-out PCs must reconnect. Unlinking stops future intake for that folder and preserves PC files, LUNA materials, versions, administrator copies and extracted information. Restoring retains IDs and keeps intake paused pending PC scope review.

Startup after Windows sign-in is optional in Settings. Closing the window leaves the tray app running; quit from the tray menu. Quit before running a new MSI. Existing settings, history and pause choices remain. Automatic update execution is disabled until publisher signing is provisioned.

Intake is one way: PC → LUNA. Local deletions do not delete LUNA materials. Optional AI summaries require administrator policy and existing AI allowances. Online-only downloads are off by default; network costs are separate. OneDrive cloud freshness is separate from server receipt.

[Full bilingual help and troubleshooting](https://lunalab-ai.com/workspace/help/folder-sync/). iOS is planned for future development.

## Lab Drive archive

Uses the administrator-configured nonpublic archive. Grant → project → connected folder contains current-material shortcuts, immutable original versions and version-specific JSON manifests. Intake, preservation and organization are separate. Code, array, data-table and model originals are stored without execution. The existing 100 MB/file, 1 GB/day and exclusions remain. Larger originals use resumable chunk uploads. Administrators review existing-file organization in the web folder detail; original Drive IDs and versions are retained. Connection and quota problems remain waiting or need attention. Optional AI summaries follow administrator policy and existing allowances.

## 0.7.0 sync and notices

File events complement inventory checks about every two minutes. Startup, detected changes and six-hour content verification catch edits under the same name. Encrypted scan pages and cursors resume large folders after restart or the next daily allowance. Encrypted transfer copies remain until Drive preservation is verified; a full cache waits. Absence requires two complete scans and a grace interval, preserving remote originals.

External connections separately show recent PC response, scanning and queued counts, Drive preservation, version and update status. A stale response does not prove the PC is off. Each release prepares a platform notice, private LUNA AI service message and email through verified university accounts. Older apps need an initial manual MSI installation. This unsigned preview cannot execute automatic installation. Later signed releases can use the automatic-install preference; failed installations are not repeatedly attempted.

Original filenames and human titles remain intact. Derived display titles are separate. Optional AI summaries follow the administrator policy, current source access and existing AI allowances, with evidence and coverage shown.


## 0.8.0 update button and 7-day grace period

Use the update button in the main window, Settings or tray. For unsigned previews, download from the official page and install over the existing app as the same Windows user. Do not uninstall first. Folders, connections, pending work and pauses remain. An activated minimum version restricts new uploads from unsupported apps after 7 days. Admitted transfers, existing materials, Drive preservation and status remain available. Check the per-PC deadline and supported-version response in platform update notices. Older apps require one initial manual install to gain the button. Do not bypass Windows or university security policies.

If an older preview reports error 2868, download 0.8.2 or later and quit the tray app before installing over it. This fixes setup message handling; another installation error may still need diagnosis. For a reproducible failure, keep a verbose log: `msiexec.exe /i "LunaFolderConnector-0.8.2-win-x64.msi" /L*V "%TEMP%\LunaFolderConnector-setup.log"`. Send support the error screenshot and relevant error lines privately; installation logs can include local paths. Do not uninstall, delete folder settings, disable Windows security, or force an administrator install.
