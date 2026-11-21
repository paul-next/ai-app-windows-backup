# Windows AI app backups

These are backups for **64-bit Windows**. The desktop apps require Windows 10 version 2004 (build 19041) or newer. These copies were saved on November 20, 2026; they do not update automatically.

| What you want | File | Version | Download size |
| --- | --- | --- | --- |
| **Claude desktop app** — the graphical app, including access to Claude Code | [Claude desktop installer](claude-desktop-x64.msix) | 6.28899.2.0 | 298 MiB |
| **Claude Code CLI** — Claude Code for the command line | [Claude Code executable](claude-code-2.1.330-x64.exe) | 2.1.330 | 370 MiB |
| **ChatGPT desktop app** — the graphical app, including Codex | [ChatGPT desktop installer](chatgpt-x64.msix) | 26.1117.4957.0 | 760 MiB |
| **Codex CLI** — Codex for the command line | [Codex CLI package](codex-package-x86_64-pc-windows-msvc.tar.gz) | 0.171.0 | 206 MiB |

Click a link, then click **Download raw file** on the GitHub file page. The desktop files are MSIX installers; open the downloaded file to begin installation. The Claude Code CLI is an executable and needs [Git for Windows](https://git-scm.com/downloads/win). For the Codex CLI, extract the `.tar.gz` archive and run `bin\codex.exe` from PowerShell, keeping the extracted supporting files together.

The files are stored with Git LFS. Signing in and an internet connection are needed to use these services. Installation may require Windows dependencies or permissions; these packages have not been tested on Windows here.

For source links and verification details, see [backup information](BACKUP-INFO.md). [SHA256SUMS.txt](SHA256SUMS.txt) contains checksums; [claude-code-manifest.json](claude-code-manifest.json) is the vendor's checksum manifest for Claude Code.
