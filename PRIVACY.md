# LocalKeyVault: privacy policy

Last updated: 12 October 2026

LocalKeyVault is a free application for Windows and Linux by Tomislav Savić. This policy covers every edition: the Microsoft Store edition, the installer, the portable edition and the Linux packages.

## In short

**LocalKeyVault does not collect, transmit, sell or share any data.** It has no account, no cloud service, no analytics or telemetry, no advertising and no update checks. The application contains no network code and never connects to the internet.

## What stays on your computer

Everything you put into LocalKeyVault stays on your own computer, under your control:

- **Your vault** (`vault.enc`): the credentials you add (names, values and their details), encrypted with AES-256-GCM, in the folder you choose.
- **The vault key, settings and local encrypted backups**: in `%LOCALAPPDATA%\LocalKeyVault` on Windows, protected by your Windows account, or in `~/.local/share/LocalKeyVault` on Linux, readable only by your user account.
- **Recovery files**: only where you save them, protected with a passphrase you choose.
- **Agent instructions**: only if you use the agent integration. A short text rule is then added to the instruction files of coding agents (Claude Code, Codex) on your computer, and you can remove it at any time.

The author of LocalKeyVault never receives any of this data and has no way to access it.

## Things you control

- **Syncing**: if you put your vault file in a folder synced by a cloud service (for example Google Drive, OneDrive or Dropbox), that service stores the **encrypted** file under its own privacy policy. LocalKeyVault itself does not talk to it.
- **Copying**: when you copy a secret, it goes to your system clipboard. LocalKeyVault marks it so that Windows clipboard history and cloud clipboard skip it, and clears it after the delay you choose if it is still there.
- **Your agents**: values you hand to a command with `localkey run` or `localkey get` go only to the program you start, which handles them under its own terms.

## Children

LocalKeyVault is a developer tool and is not directed at children.

## Changes and contact

Changes to this policy are published in this file, with the date at the top. Questions: open an issue at https://github.com/Maven303/LocalKeyVault-Releases/issues. Never include secrets, vault files, key files or recovery files.
