<h1 align="center">Hi, I'm Dom</h1>

<p align="center">
  IT support and systems administration · Mac admin and security tools in Rust · Open to remote work (US)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dominic-f-/"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Remote%20(US)-open%20to%20work-2EA043?style=for-the-badge" alt="Open to remote work in the US">
</p>

## About me

I work in IT support and systems administration, and I build the tools I needed on the job and could not find. Since 2023 I have done Level 2 and 3 support across macOS and Windows, with Jamf, Microsoft 365, Google Workspace and Entra ID behind it. A lot of that work was the same check done by hand on one Mac after another, so I started writing tools that run the check and tell me what they found.

Most of what is public here is read-only on purpose. When someone hands me a Mac with a problem, I want to know what is wrong before I change anything, and I think a tool that reports "healthy" when it could not finish its checks is worse than no tool at all. That is why mactriage says its scan was incomplete instead of staying quiet about it.

I also help run a hands-on lab that is used to teach security. It is a five-node Proxmox cluster, and my part of it has been the Linux services, the WireGuard VPN, the backups and the monitoring with Wazuh, Zabbix and Loki.

Before IT, I spent ten years in Marine Corps aviation, flying, quality assurance and safety. That is where I learned to inspect the work and write it down so the next person can follow it, and I still work that way. I will earn two bachelor's degrees in Cybersecurity and Computer Science in Dec 2026.

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
