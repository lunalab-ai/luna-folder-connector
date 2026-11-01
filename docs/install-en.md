# Install and connect a Windows folder

1. Download the MSI from the [official download page](https://lunalab-ai.com/download/). Compare the release SHA256SUMS.txt with `Get-FileHash .\LunaFolderConnector-Setup-x64.msi -Algorithm SHA256`.
2. Run the MSI. It installs for the current Windows user with a self-contained runtime. This is an unsigned preview; ask your administrator if Windows or school policy blocks it.
3. Open LUNA Folder Connector from Start. Under Account, sign in to LUNA and approve the matching browser account and confirmation code. No project selection is needed yet.
4. In My folders, add a folder using OneDrive detection or Browse. Choose a real folder synced by the official OneDrive client. No Entra registration or Microsoft secret is required.
5. Choose a project. Review subfolders, online-only downloads and the project audience before approving intake. Opening the app from a project can suggest a destination; this is never upload consent.
6. Review folder → grant → project and separate receipt, preservation and extraction counts. Add multiple folders and pause or unlink each. The same connections appear under grant/project external connections and My PC and sync management.

## Pause, deletion and updates

Allowing server intake preserves local global and folder pauses. Offline or signed-out PCs must reconnect. Unlinking stops future intake for that folder and preserves PC files, LUNA materials, versions, administrator copies and extracted information. Restoring retains IDs and keeps intake paused pending PC scope review.

Startup after Windows sign-in is optional in Settings. Closing the window leaves the tray app running; quit from the tray menu. Quit before running a new MSI. Existing settings, history and pause choices remain. Automatic update execution is disabled until publisher signing is provisioned.

Intake is one way: PC → LUNA. Local deletions do not delete LUNA materials. Paid AI does not run automatically. Online-only downloads are off by default; network costs are separate. OneDrive cloud freshness is separate from server receipt.

[Full bilingual help and troubleshooting](https://lunalab-ai.com/workspace/help/folder-sync/). iOS is planned for future development.
