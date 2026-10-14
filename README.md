<p align="center">
  <a href="https://www.valorant-spind.de/en/spindtune.html"><img src="media/banner-en.png" alt="SpindTune – free Windows tool to clean up, update and find every stutter" width="100%"></a>
</p>

<p align="center">
  🇬🇧 <b>English</b> · 🇩🇪 <a href="README.de.md">Deutsch</a>
</p>

<p align="center">
  <a href="https://www.valorant-spind.de/en/spindtune.html#download"><img src="https://img.shields.io/badge/Download-free-E8863C?style=for-the-badge&logo=windows&logoColor=white" alt="Download SpindTune for free"></a>
  <img src="https://img.shields.io/badge/version-3.5.0-1f2328?style=for-the-badge" alt="Version 3.5.0">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011%20(64--bit)-0078D4?style=for-the-badge" alt="Windows 10 and 11, 64-bit">
  <img src="https://img.shields.io/badge/languages-EN%20%7C%20DE-1f2328?style=for-the-badge" alt="English and German">
  <a href="https://discord.com/invite/rKqNGPE3hS"><img src="https://img.shields.io/badge/Discord-join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join the Discord"></a>
</p>

<p align="center">
  <b>No account</b> · <b>No ads</b> · <b>No subscription</b> · <b>No telemetry</b> · <b>Nothing happens without your click</b>
</p>

---

**SpindTune** is a free Windows tool by [Valorant-Spind](https://www.valorant-spind.de) to **clean up, update and check your PC** – with a clear focus on gaming. It removes junk files without touching the registry, keeps apps, Windows and drivers up to date, finds hidden slowdowns with the **Gaming Check**, shows you exactly why your game stutters with the **Lag Hunter** and tests TPM 2.0, Secure Boot and everything else Riot Vanguard needs with the **Valorant Check**.

Every action is shown before it happens. You decide – SpindTune only does what you click.

<p align="center">
  <img src="media/tour-en.gif" alt="Animated tour through SpindTune 3.5.0: Home, Updates, Clean Up, Gaming Check, Lag Hunter, Valorant Check, Hardware and Gaming Mode" width="900">
  <br><sub>Real screenshots of SpindTune 3.5.0 on Windows 11 (October 12, 2026). Personal details are pixelated.</sub>
</p>

## Contents

- [Why SpindTune](#why-spindtune)
- [Simple mode](#simple-mode-four-cards-one-score)
- [New in 3.5.0: Lag Hunter](#new-in-350-the-lag-hunter)
- [All features](#all-features)
- [Valorant Check](#valorant-check-tpm-20-secure-boot--vanguard)
- [Share cards](#share-cards)
- [Safety rules](#what-spindtune-never-does)
- [Privacy](#privacy)
- [Download & install](#download--install)
- [Version history](#version-history)
- [FAQ](#faq)

## Why SpindTune

| | |
|---|---|
| 🔒 **Your data stays yours** | No sign-up, no telemetry, no background service, no startup entry. Close the window and SpindTune is off. |
| 👆 **Only on your click** | Nothing is checked, updated or deleted until you start it and confirm. Every row tells you *why*. |
| 🧹 **No registry cleaning** | The risky "registry cleaner" is left out on purpose – Microsoft doesn't support registry cleaners either. |
| ♻️ **Reversible where possible** | Restore point before drivers and cleanup, duplicates and clips only go to the Recycle Bin, startup entries are backed up. |
| 🎮 **Built for gamers** | Gaming Check with a 0–100 score, Lag Hunter with frame-time analysis, Valorant Check for Vanguard, Hz Check and more. |
| 💸 **Free. For real.** | No Pro version, no subscription, no in-app purchases, no ads. |

## Simple mode: four cards, one score

Every launch starts in **Simple mode**. Four big cards answer the questions almost every gamer has – and the PC health score (0–100) in the top right shows where you stand.

<p align="center"><img src="media/en/simple-mode.webp" alt="SpindTune Simple mode with PC health 99/100 and the four cards: Keep PC up to date, Free up space, Game faster, My PC" width="900"></p>

| Card | What it does |
|---|---|
| **Keep PC up to date** | Apps, Windows, antivirus and Office – with a list you see and confirm first. |
| **Free up space** | Junk files, old update files, caches and the Recycle Bin. No registry, nothing risky. |
| **Game faster** | Wrong refresh rate, old drivers, shaky Wi-Fi, too many startup apps, temperature. |
| **My PC** | All parts at a glance, an estimated setup tier and your Hardware Card to share. |

Want every detail? Switch to **Pro mode** – a sidebar with **16 pages in six groups**.

## New in 3.5.0: the Lag Hunter

**Why does your game stutter?** Hit *Start recording*, play as usual – after the match the report is ready:

- average FPS, **1 % and 0.1 % lows**
- every stutter with its **time and likely cause**
- whether the **graphics card, processor or an FPS cap** was holding you back
- which programs were running during the stutters
- a **timeline with ping** (router and internet) and a plan with concrete steps

Frame times come from **Intel PresentMon 2.6.0** (MIT license). It ships with SpindTune, its Intel signature is verified before every start, and it **only reads Windows events – nothing is injected into the game**. Menus and loading screens are filtered out automatically.

<table>
  <tr>
    <td width="50%"><img src="media/en/lag-hunter-report-1.webp" alt="Lag Hunter report: 3 stutters, average 358 FPS, 1% lows 208, processor was the limit"></td>
    <td width="50%"><img src="media/en/lag-hunter-report-2.webp" alt="Lag Hunter timeline with stutters as red bars and ping below"></td>
  </tr>
  <tr>
    <td><sub><b>The result:</b> a real Valorant match (3:44 min, 80,271 frames) – 3 stutters, avg 358 FPS, 1 % lows 208.</sub></td>
    <td><sub><b>Timeline:</b> every stutter as a red bar with timestamp and cause, ping below.</sub></td>
  </tr>
  <tr>
    <td><img src="media/en/lag-hunter-report-3.webp" alt="Lag Hunter frame-time distribution and ping to router and internet"></td>
    <td><img src="media/en/lag-hunter-report-4.webp" alt="Lag Hunter comparison of recent matches and data sources"></td>
  </tr>
  <tr>
    <td><sub><b>Smoothness:</b> how evenly frames arrived, plus ping to router and internet.</sub></td>
    <td><sub><b>History & sources:</b> recent matches compared. No value? SpindTune says "not measurable" instead of guessing.</sub></td>
  </tr>
</table>

**Also new in 3.5.0:** GPU temperature and load for NVIDIA, AMD and Intel straight from Windows, CPU temperature via the free tool HWiNFO (on request), a politer Gaming Mode using the Windows Restart Manager, a stricter cleanup block list, ⓘ explanations on every page and a rewritten safety window.

## All features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 Home</h3>
      <img src="media/en/home.webp" alt="SpindTune Home page with six tiles after Check everything">
      <p><b>Check everything</b> in about 2–4 minutes – updates, gaming readiness, junk files and startup apps – without changing anything.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔄 Updates</h3>
      <img src="media/en/updates.webp" alt="SpindTune Updates page">
      <p>Apps via <b>winget</b>, <b>Windows Update</b>, Defender, Store, Office, WSL, launchers and <b>graphics drivers directly from NVIDIA or AMD</b>. Drivers only with a restore point.</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🧹 Clean Up</h3>
      <img src="media/en/clean-up.webp" alt="SpindTune Clean Up analysis with sizes, file counts and reasons">
      <p>Analyze first, delete later. Temp files, old update downloads, caches, crash dumps. Uses the <a href="https://github.com/MoscaDotTo/Winapp2">Winapp2</a> database (4,068+ apps) – <b>file rules only, registry rules are always skipped</b>.</p>
    </td>
    <td valign="top">
      <h3>🎮 Gaming Check</h3>
      <img src="media/en/gaming-check.webp" alt="SpindTune Gaming Check with score 99">
      <p>Twelve areas in about 30 seconds: monitor Hz, RAM dual channel and XMP/EXPO, PCIe and Resizable BAR, driver age, Windows settings, ping & Wi-Fi, SSD health. Score from ROOKIE (D) to LEGEND (S+).</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>⚡ Gaming Mode</h3>
      <img src="media/en/gaming-mode.webp" alt="SpindTune Gaming Mode listing background programs">
      <p>Close chat apps, launchers, updaters and cloud sync before you play – you pick with checkboxes, <b>Restore</b> starts everything again. Games, anti-cheat, drivers and Windows are never touched.</p>
    </td>
    <td valign="top">
      <h3>🖥️ Hardware & Card</h3>
      <img src="media/en/hardware.webp" alt="SpindTune Hardware page with CPU, motherboard, RAM, GPU, drives and drivers">
      <p>CPU, motherboard with BIOS date, RAM per slot, GPUs, drives with firmware and all key drivers with their age – each with a link to the manufacturer.</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>📺 Hz Check</h3>
      <img src="media/en/hz-check.webp" alt="SpindTune Hz Check showing 144 Hz over DisplayPort">
      <p>Is your monitor really running at 144, 165 or 240 Hz? Shows what's set, what's possible and whether the cable or port holds you back.</p>
    </td>
    <td valign="top">
      <h3>📶 Connection Check</h3>
      <img src="media/en/connection-check.webp" alt="SpindTune Connection Check with ping to router and internet">
      <p>20 seconds of ping, measured separately for your home network and the internet – so you know whether Wi-Fi or your provider causes the lag.</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>💾 Storage Analysis & Duplicates</h3>
      <img src="media/en/storage-analysis.webp" alt="SpindTune Storage Analysis with folder sizes">
      <p>See which folders eat your drive (display only). Duplicate Files finds identical files by checksum, always keeps one per group and only moves the rest to the Recycle Bin.</p>
    </td>
    <td valign="top">
      <h3>🚀 Startup Apps & Uninstall</h3>
      <img src="media/en/startup-apps.webp" alt="SpindTune Startup Apps manager">
      <p>Enable and disable startup entries like Task Manager does, with a backup before deleting. Uninstall always uses each program's official uninstaller.</p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🎬 Clips</h3>
      <img src="media/en/clips.webp" alt="SpindTune Clips finder for game recordings">
      <p>Finds recordings from Medal, NVIDIA, Xbox Game Bar, OBS, AMD, Steam & co. on your drives – only what you tick goes to the Recycle Bin.</p>
    </td>
    <td valign="top">
      <h3>⏱️ Playtime</h3>
      <img src="media/en/playtime.webp" alt="SpindTune Playtime statistics">
      <p>Optional and local: playtime per day, when you usually play and your recent sessions – only if you switch it on and SpindTune is open.</p>
    </td>
  </tr>
</table>

## Valorant Check: TPM 2.0, Secure Boot & Vanguard

On Windows 11, Valorant only starts with **TPM 2.0** and **UEFI Secure Boot**. If something is missing, Vanguard shows errors like **VAN 9001** or **VAN 9003**. The Valorant Check tests everything Vanguard needs in 10–30 seconds – **read only, nothing is changed**:

- Windows version, UEFI/legacy, partition style (GPT/MBR), Secure Boot incl. keys and the 2023 certificate
- TPM version and status – Intel PTT, AMD fTPM, Microsoft Pluton or a discrete chip
- Control Flow Guard, test mode, VT-x/AMD-V, VBS, memory integrity (HVCI), Kernel DMA Protection (IOMMU)
- Vanguard services `vgc` and `vgk`, plus a lookup for **27 VAN error codes**

Instructions match your hardware, with concrete BIOS paths for ASUS, MSI, Gigabyte and ASRock and typical paths for Dell, HP, Lenovo and Acer. If BitLocker is on, SpindTune warns you to back up your recovery key first.

<table>
  <tr>
    <td width="50%"><img src="media/en/valorant-check-tpm.webp" alt="SpindTune Valorant Check with TPM details"></td>
    <td width="50%"><img src="media/en/valorant-check-howto.webp" alt="SpindTune Valorant Check how-to with the BIOS path for an MSI board"></td>
  </tr>
</table>

Full guide without the tool: [Valorant: enable Secure Boot & TPM 2.0](https://www.valorant-spind.de/en/valorant-secure-boot-tpm.html) · [VAN error codes](https://www.valorant-spind.de/en/valorant-van-fehlercodes.html)

## Share cards

Save your **Gaming Check**, **Hardware Card** and **Speed Test** as JPG or PNG (up to 2,160 × 2,700 px) – ready for Discord, Reddit or Instagram. Serial numbers, user name, IP and MAC addresses never end up on a card.

<p align="center"><img src="media/en/share-cards.webp" alt="Three SpindTune share cards: Gaming Check, Hardware Card and Speed Test" width="900"></p>

## What SpindTune never does

SpindTune shows its rules after every install and every new version – you confirm them with two checkboxes.

<table>
  <tr>
    <td width="55%" valign="top">

**How each action is safeguarded**

- **Drivers:** restore point required, only from approved manufacturer sites, signature verified
- **Clean Up:** restore point on by default, file list beforehand
- **Duplicate files & clips:** only to the Recycle Bin
- **Startup apps:** backup before deleting, restore with one click
- **Never two actions at once** – a global lock prevents conflicts

**Never**

- nothing automatic, nothing in the background
- no registry cleaning
- no BIOS, UEFI or SSD firmware updates, no Python updates
- no deleting restore points, no DISM cleanup

</td>
    <td width="45%" valign="top"><img src="media/en/safety-notice.webp" alt="SpindTune safety notice that must be confirmed with two checkboxes"></td>
  </tr>
</table>

Honest about limits: app updates and uninstalls use the official publisher routes and don't create their own restore point; cleaned files and an emptied Recycle Bin are gone for good. If you don't understand an item, just leave it out – the reason is in every row.

## Privacy

SpindTune contains **no telemetry** and sends **no data about you** to us. It only goes online when you start a feature that needs it – for example updates via Microsoft (winget, Windows Update), drivers straight from NVIDIA or AMD, game requirements from the Steam store, the Cloudflare speed test, the Lag Hunter ping (router and `1.1.1.1`) or the cleanup database update from GitHub. Settings stay local in `%LOCALAPPDATA%\SpindTune`.

Full details: [Privacy policy, section "SpindTune"](https://www.valorant-spind.de/en/datenschutz.html#spindtune)

## Download & install

<p align="center">
  <a href="https://www.valorant-spind.de/en/spindtune.html#download"><img src="https://img.shields.io/badge/⬇%20Download%20SpindTune%203.5.0-free%20·%2018.0%20MB-E8863C?style=for-the-badge" alt="Download SpindTune 3.5.0 for free"></a>
</p>

| | |
|---|---|
| **Version** | 3.5.0 (October 12, 2026) |
| **System** | Windows 10 & 11, 64-bit |
| **Size** | 18.0 MB (`SpindTune-Setup.exe`, setup wizard) |
| **Languages** | English & German – chosen in setup, switchable in the app |
| **Rights** | Administrator (needed for updates, drivers, restore points and system folders) |
| **Price** | Free – no subscription, no account |
| **SHA-256** | `e7c0ad024744cd04add7338be70810e24c33fe09e0cfb5bebec2580fedc8392a` |

1. **Download** `SpindTune-Setup.exe` from the [official page](https://www.valorant-spind.de/en/spindtune.html#download) – only download SpindTune from valorant-spind.de.
2. **Verify** (optional) in PowerShell: `Get-FileHash .\SpindTune-Setup.exe`
3. **Install** – the file is not digitally signed yet, so SmartScreen may show "Unknown publisher" → *More info* → *Run anyway*.
4. **Read the safety notes**, tick both boxes, and start in Simple mode.

**VirusTotal:** as of October 13, 2026, 68 of 71 engines report no detection ([report](https://www.virustotal.com/gui/file/e7c0ad024744cd04add7338be70810e24c33fe09e0cfb5bebec2580fedc8392a)). Trellix and Skyhigh ("Artemis", a cloud reputation rating) and Deep Instinct (AI rating) flag it – we consider these false positives, as reputation- and AI-based detections more often flag new, unsigned installers that are still rarely downloaded.

**Uninstall:** Settings → Apps → Installed apps → SpindTune → Uninstall.

## Version history

| Version | Date | Highlights |
|---|---|---|
| **3.5.0** | Oct 12, 2026 | **Lag Hunter** (frame times via Intel PresentMon, 1 %/0.1 % lows, stutter causes, ping timeline), GPU temperature for all vendors, CPU temperature via HWiNFO, politer Gaming Mode, stricter cleanup, ⓘ explanations, new safety window |
| **3.4.0** | Oct 11, 2026 | **Gaming Mode**, **Hz Check**, **Connection Check**, **Clips**, **Playtime** |
| **3.3.0** | Oct 8, 2026 | Setup in English & German, the app starts in the setup language |
| **3.2.0** | Oct 7, 2026 | First public release |

## FAQ

<details>
<summary><b>Is SpindTune really free?</b></summary>

Yes. No subscription, no Pro version, no in-app purchases and no ads. It's a private project by Valorant-Spind.
</details>

<details>
<summary><b>Is the source code on GitHub?</b></summary>

No. SpindTune is free to use, but closed source. This repository is the project's showcase – screenshots, features, version history and links. Downloads are only offered on [valorant-spind.de](https://www.valorant-spind.de/en/spindtune.html#download).
</details>

<details>
<summary><b>Does SpindTune clean the registry?</b></summary>

No, on purpose. SpindTune also skips the registry rules of the Winapp2 database. Only the startup manager changes startup entries – like Task Manager does – and only when you click.
</details>

<details>
<summary><b>Does it fix VAN 9001 / VAN 9003 automatically?</b></summary>

No. The Valorant Check only reads and shows what's missing, with step-by-step instructions for your motherboard. You flip the BIOS switches yourself. If you want, SpindTune restarts your PC straight into the BIOS after a safety prompt.
</details>

<details>
<summary><b>Does the Lag Hunter touch the game or anti-cheat?</b></summary>

No. Frame times come from Intel PresentMon, which only reads Windows events – nothing is injected into the game. The load per program comes from the Windows process list without opening any programs.
</details>

<details>
<summary><b>Why does Windows SmartScreen warn me?</b></summary>

SpindTune is not digitally signed yet, so SmartScreen often reports new, unsigned programs as "Unknown publisher". Only download it from valorant-spind.de and compare the SHA-256 checksum if you like.
</details>

More questions: [SpindTune FAQ](https://www.valorant-spind.de/en/spindtune.html#faq) · help and bug reports in the **SPIND-TUNE** channels on [Discord](https://discord.com/invite/rKqNGPE3hS)

## More from Valorant-Spind

- 🗄️ [**Valorant-Spind app**](https://github.com/Valorant-Spind/Valorant-Spind) – how much is your Valorant locker worth? Locker value, coach, 2D match replay – free for Windows.
- 🌐 [**valorant-spind.de**](https://www.valorant-spind.de/en/) – 40+ free Valorant tools: [crosshair generator](https://www.valorant-spind.de/en/valorant-crosshair-generator.html), [sensitivity converter](https://www.valorant-spind.de/en/valorant-sensitivity-converter.html), [system requirements](https://www.valorant-spind.de/en/valorant-systemanforderungen.html), [tech fix](https://www.valorant-spind.de/en/valorant-technik-fix.html) and more.
- 💬 [**Discord**](https://discord.com/invite/rKqNGPE3hS) – SpindTune changelog, help and community.

---

<p align="center">
  <img src="media/icon.webp" alt="SpindTune icon" width="64"><br>
  <sub>SpindTune is an independent project by <a href="https://www.valorant-spind.de">Valorant-Spind</a> and not an official product of Riot Games, Microsoft, NVIDIA, AMD or Intel. VALORANT is a trademark of Riot Games, Inc.<br>
  Cleanup database: <a href="https://github.com/MoscaDotTo/Winapp2">Winapp2</a> (CC BY-SA 4.0) · Frame-time measurement: Intel PresentMon 2.6.0 (MIT license)<br>
  Use at your own responsibility – <a href="https://www.valorant-spind.de/en/impressum.html">disclaimer & terms of use</a> · <a href="https://www.valorant-spind.de/en/datenschutz.html#spindtune">privacy</a></sub>
</p>
