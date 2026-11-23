# Windows AI application backups

Downloaded from official vendor sources and last checked November 23, 2026, for Windows x64. The desktop packages specify Windows 10 version 2004 (build 19041) or newer. Account sign-in and network access are still required to use the services. Installation may require Microsoft dependencies or Windows app installation permissions.

- `chatgpt-x64.msix`: ChatGPT desktop, including Codex, version 26.1117.4957.0. Source: https://persistent.oaistatic.com/codex-app-prod/ChatGPT-x64.msix
- `claude-desktop-x64.msix`: Claude desktop version 6.28899.6.0. Source: https://claude.ai/api/desktop/win32/x64/msix/latest/redirect
- `claude-code-2.1.330-x64.exe`: Claude Code command-line executable. Source: https://downloads.claude.ai/claude-code-releases/2.1.330/win32-x64/claude.exe. Its SHA-256 was checked against the included vendor manifest. Claude Code on Windows requires Git for Windows.
- `codex-package-x86_64-pc-windows-msvc.tar.gz`: Codex CLI 0.171.0 and its supporting files. Source: https://github.com/openai/codex/releases/tag/rust-v0.171.0. SHA-256 was checked against the official release. Extract the archive and run `bin\codex.exe` from PowerShell.

`SHA256SUMS.txt` records the hashes of all four downloaded files. Package versions and operating system compatibility were read from the packages or official metadata; they have not been tested on a Windows computer. MSIX packages may require additional dependencies and installation through PowerShell or Windows App Installer.

The four large files are stored using Git LFS. Download them from the repository or clone it with Git LFS installed. The release page does not contain the installers.
