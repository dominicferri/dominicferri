<h1 align="center">Hi, I'm Dom</h1>

<p align="center">
  IT support and systems administration · Mac admin and security tools in Rust · Open to remote work (US)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dominic-f-/"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Remote%20(US)-open%20to%20work-2EA043?style=for-the-badge" alt="Open to remote work in the US">
</p>

## Projects

<a href="https://github.com/dominicferri/mactriage"><img src="https://raw.githubusercontent.com/dominicferri/mactriage/main/docs/images/banner.svg" alt="mactriage" width="100%"></a>

<p>
  <img src="https://img.shields.io/github/v/release/dominicferri/mactriage?style=flat-square&labelColor=000000&color=F4BD47" alt="Latest mactriage release">
  <img src="https://img.shields.io/github/last-commit/dominicferri/mactriage?style=flat-square&labelColor=000000&color=C00027" alt="Last mactriage commit">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/read--only-000000?style=flat-square" alt="Read-only">
</p>

A read-only command-line tool for Mac support work. It reads the crash reports, panic records, unified log and live state that macOS already keeps, then gives one list of problems sorted by severity, with a next step for each. It also builds a double-click MacSecurity.app that runs the security audit and writes an HTML report.

<a href="https://github.com/dominicferri/mactriage"><img src="https://raw.githubusercontent.com/dominicferri/mactriage/main/docs/images/report.png" width="720" alt="The mactriage HTML report for a demo Mac, with invented data"></a>

<a href="https://github.com/dominicferri/JamfSecurityAudit"><img src="https://raw.githubusercontent.com/dominicferri/JamfSecurityAudit/main/docs/images/banner.svg" alt="JamfSecurityAudit" width="100%"></a>

<p>
  <img src="https://img.shields.io/github/v/release/dominicferri/JamfSecurityAudit?style=flat-square&labelColor=000000&color=F4BD47" alt="Latest JamfSecurityAudit release">
  <img src="https://img.shields.io/github/last-commit/dominicferri/JamfSecurityAudit?style=flat-square&labelColor=000000&color=C00027" alt="Last JamfSecurityAudit commit">
  <img src="https://img.shields.io/badge/JavaScript%20for%20Automation-000000?style=flat-square&logo=apple&logoColor=white" alt="JavaScript for Automation">
  <img src="https://img.shields.io/badge/read--only-000000?style=flat-square" alt="Read-only">
</p>

Checks one Mac for 30 common security gaps in Jamf-managed Macs. It changes nothing and writes a private HTML report. The whole audit is a single JavaScript for Automation script, so it runs on stock macOS with no Python, Homebrew or Jamf credentials.

<a href="https://github.com/dominicferri/JamfSecurityAudit"><img src="https://raw.githubusercontent.com/dominicferri/JamfSecurityAudit/main/docs/images/report.png" width="720" alt="An example JamfSecurityAudit report for an invented demo Mac"></a>

<a href="https://github.com/dominicferri/office-license-removal"><img src="https://raw.githubusercontent.com/dominicferri/office-license-removal/main/docs/images/banner.svg" alt="Office License Removal" width="100%"></a>

<p>
  <img src="https://img.shields.io/github/v/release/dominicferri/office-license-removal?style=flat-square&labelColor=000000&color=F4BD47" alt="Latest office-license-removal release">
  <img src="https://img.shields.io/github/last-commit/dominicferri/office-license-removal?style=flat-square&labelColor=000000&color=C00027" alt="Last office-license-removal commit">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
</p>

A Rust replacement for the postinstall script in Microsoft's Office for Mac License Removal Tool 2.7. The original had two faults: the flight reset never ran, and the keychain deletes did not remove the user's sign-in items. This one fixes both, and it runs as a native app, as a terminal UI or from the command line.

<a href="https://github.com/dominicferri/office-license-removal"><img src="https://raw.githubusercontent.com/dominicferri/office-license-removal/main/docs/images/terminal-ui.png" width="720" alt="The Office License Removal terminal UI in lab mode after a remove"></a>

<a href="https://github.com/dominicferri/MacCleanUp"><img src="https://raw.githubusercontent.com/dominicferri/MacCleanUp/main/docs/images/banner.svg" alt="MacCleanUp" width="100%"></a>

<p>
  <img src="https://img.shields.io/github/v/release/dominicferri/MacCleanUp?style=flat-square&labelColor=000000&color=F4BD47" alt="Latest MacCleanUp release">
  <img src="https://img.shields.io/github/last-commit/dominicferri/MacCleanUp?style=flat-square&labelColor=000000&color=C00027" alt="Last MacCleanUp commit">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Trash%20only-000000?style=flat-square" alt="Moves items only to the Trash">
</p>

A native cleanup app for Macs with Apple silicon, written in Rust. It shows where the space on the startup disk goes. It finds caches, leftover installers, large old files and build folders, and moves only what you review to the Trash. It is one self-contained app, so it also runs straight from a disk image or a thumb drive.

<a href="https://github.com/dominicferri/MacCleanUp"><img src="https://raw.githubusercontent.com/dominicferri/MacCleanUp/main/docs/screenshots/storage.png" width="720" alt="The MacCleanUp Storage view: each part of the startup disk with its size"></a>

<a href="https://github.com/dominicferri/cups-web-interface"><img src="https://raw.githubusercontent.com/dominicferri/cups-web-interface/main/docs/images/banner.svg" alt="CUPS webui" width="100%"></a>

<p>
  <img src="https://img.shields.io/github/last-commit/dominicferri/cups-web-interface?style=flat-square&labelColor=000000&color=C00027" alt="Last cups-web-interface commit">
  <img src="https://img.shields.io/badge/Go-000000?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/local%20only-000000?style=flat-square" alt="Local only">
</p>

macOS 27 removed the CUPS web page at localhost:631, the place to manage printers and print queues in a browser. This is PaperCut's open-source replacement, packaged for the Mac. It adds a double-click installer, a server that runs only while the page is open, and a set of bug, security and speed fixes. It is an unofficial packaging, not published or supported by PaperCut.

<a href="https://github.com/dominicferri/cups-web-interface"><img src="https://raw.githubusercontent.com/dominicferri/cups-web-interface/main/docs/screenshot.png" width="720" alt="The CUPS webui dashboard in mock mode, with the printers and queues table"></a>

## What I work with

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=apple,windows,linux,rust,py,bash,powershell,swift,go,js,docker,postgres,nginx,cloudflare,git,github&perline=8" alt="Apple, Windows, Linux, Rust, Python, Bash, PowerShell, Swift, Go, JavaScript, Docker, PostgreSQL, nginx, Cloudflare, Git, GitHub"></a>
</p>

| Area | What I use |
|---|---|
| Endpoints | macOS and Windows 10/11, Jamf Pro, Microsoft 365, Google Workspace, Entra ID and Active Directory, Duo |
| Systems | Linux (Debian, Ubuntu, Fedora, Kali), Proxmox VE, Docker, WireGuard, Tailscale, nginx, PostgreSQL |
| Security and monitoring | Wazuh, Suricata, Zeek, Loki and Grafana, Zabbix |
| Languages | Rust, Python, Bash and zsh, PowerShell, Swift, Go |

## What I'm working on now

- Finishing two bachelor's degrees, Cybersecurity and Computer Science, in Dec 2026.
- Looking for a full-time remote role (US) in endpoint engineering, systems administration or security.

## Contact

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/dominic-f-/). If one of these tools saved you some time, or broke on your Mac, I would like to hear about it either way.
