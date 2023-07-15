<h1 align="center">
  <br>
  <a href="https://github.com/ArmynC/ArminC-Windows-Debloat/archive/refs/heads/main.zip"><img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/arminc_windows_debloat.svg" alt="Windows Debloat"></a>
</h1>

<h4 align="center">A high-quality step-by-step guide for tech-savvy users.</h4>

<p align="center">
  <a href="#about">About</a> •
  <a href="#getting-windows">Get</a> •
  <a href="#installing-windows">Install</a> •
  <a href="#setting-windows">Set</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

 ## About

<table>
<tr>
<td>

**ArminC Windows Debloat** is an introduction to my method of  configuring the Windows operating system without all of the  **bloat** and **annoying features**  while keeping it  **stable** and **functional** in all scenario.

The chosen options should be up to everyone's preference and according to the computer's configuration.

</td>
</tr>
</table>

---

### Getting Windows

##### Download
First and foremost, you must obtain the **.iso** image file of Microsoft Windows. There are more variants to choose from:

<ul>
<li><b>Unofficial</b> pre-built images:</li>

<ol type="i">
<li><a href="https://forum.rg-adguard.net/forums/windows-11.76/">Assembly</a> based on original Windows Unified Update Platform, with <b>minimal modifications</b>, such as disabled system requirements check and account creation, integration of the most recent updates, SmartFix, Microsoft DaRT. (<b>Recommended</b>)</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/rg_adguard.png" width="30%" height="30%">
<br>
<sub>rg adguard assembly</sub>
</p>

<li><a href="https://www.teamos.xyz/forums/windows-11-x64.159/">Multiple customs build</a>, be it touched or untouched, including <b>modifications</b>, as disabled system requirements  check or even total reskin.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/teamos.png" width="30%" height="30%">
<br>
<sub>TeamOS builds</sub>
</p>

</ol>

<li><b>Official</b> images:</li>

<ol type="i">
<li><a href="https://github.com/pbatard/Fido">Fido PowerShell</a> download script with automated access to the official Microsoft Windows retail server. There are <b>no modifications</b> at all.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/fido.png" width="30%" height="30%">
<br>
<sub>Fido</sub>
</p>

<li><a href="https://www.microsoft.com/en-us/software-download/windows11">Official Windows Installation Media</a> tool for bootable USB or DVD.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/windows_installation_media.png" width="50%" height="50%">
<br>
<sub>Windows Installation Media tool</sub>
</p>

</ol>
</ul>

##### Create flash drive
If the **.iso** image file has been **completed**, now is the time to create a bootable flash drive. In order to do this, you'll need an utility. There are several ways:

<ol type="i">
<li><a href="https://www.ventoy.net/en/index.html">Ventoy</a> is an utility which creates a bootable usb, by <i>directly booting</i> the .iso file, without the need for the usb to be formatted.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/ventoy_bios.png" width="40%" height="40%">
<br>
<sub>Ventoy</sub>
</p>
    
<li><a href="https://rufus.ie/en/">Rufus</a> is an utility which creates a bootable usb, by <i>burning</i> the .iso file.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/rufus.png" width="40%" height="40%">
<br>
<sub>Rufus</sub>
</p>

Depending on the chosen settings, the application may ask if you want to **stop the Windows requirement checks**.

</ol>

### Installing Windows

Near the end of the installation, if you haven't downloaded a pre-built image with sequence skip, you will be asked about **privacy** preferences. Try to **disable/reject** them. Also, try to <b>avoid</b> connecting the device to Internet during the setup.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/privacy.png" width="50%" height="50%">
</p>

### Setting Windows

#### Prerequisites

If you are done with it, now you should prepare the operating system.

##### The browser
The first thing on the list, try to change the browser. **[Firefox](https://www.mozilla.org/en-US/firefox/new/ "Firefox")** is the most optimal variant, even for *extension capabilities*. About that, see my [uBlock Settings](https://github.com/ArmynC/ArminC-uBlock-Settings "uBlock Settings"). Some of the other good extensions are [Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/ "Bitwarden"), [Translate Web Pages](https://addons.mozilla.org/en-US/firefox/addon/traduzir-paginas-web/ "Translate Web Pages"), [Location Guard](https://addons.mozilla.org/en-US/firefox/addon/location-guard/ "Location Guard"), [FastForward](https://github.com/FastForwardTeam/FastForward "FastForward"). Some YouTube ones include [Return Youtube Dislikes](https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes/ "Return YouTube Dislikes"), [Thumbnail Rating Bar for YouTube](https://addons.mozilla.org/en-US/firefox/addon/youtube-thumbnail-rating-bar/ "Thumbnail Rating Bar for YouTube"), [YouTooltip](https://addons.mozilla.org/en-US/firefox/addon/youtooltip/ "YouTooltip"), [Watchmarker for Youtube](https://addons.mozilla.org/en-US/firefox/addon/watchmarker-for-youtube/ "Watchmarker for Youtube") ...

##### Other apps
Next thing, for all the other steps, you'll need a file archiver, [7-Zip](https://www.7-zip.org/ "7-Zip") is a good variant, it's even *open-source*.

For the peace of mind, it is a good habit to **install an antivirus**, depending on your Windows image, the default one, **Defender**, may be removed, disabled, or even working. For some, it is good enough, but I prefer to get [Kaspersky Security Cloud (Free)](https://www.kaspersky.com/free-antivirus "Kaspersky Security Cloud (Free)"), or even [BitDefender(Free)](https://www.bitdefender.com/solutions/free.html). Kaspersky has almost every protection module of its premium counterpart, and it is smart enough to **disable itself when resources are needed**, for example in gaming.


##### Updates
Now, **check all available updates and drivers**, install them, and restart the computer. **Make sure** there is **no** update remaining. It is **not advisable to disable** and avoid them.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/update_check.png" width="50%" height="50%">
</p>

Then, if desired, do the same for **Windows Store**, and only after that, **disable its auto updates**.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/store_no_updates.png" width="50%" height="50%">
</p>

##### Drivers
The main (e.g., graphical) drivers **shouldn't be installed through Windows Updates**, so it's recommended to reinstall them through official ways. To uninstall them, use [Display Driver Uninstaller](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html "Display Driver Uninstaller"), where you should **check all "remove"** specific options, and also very important, **check the Windows Update prevent download option**. Uninstall every component, restart, and find the latest official installers ([AMD](https://www.amd.com/en/support)/[NVIDIA](https://www.nvidia.com/download/index.aspx)/[INTEL](https://www.intel.com/content/www/us/en/download-center/home.html)).

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/ddu.png" width="50%" height="50%">
</p>

If your computer has an compatible NVIDIA GPU, you could try [NVCleanstall](https://www.techpowerup.com/download/techpowerup-nvcleanstall/) which is a tool for more **customizable capabilities**, **bloat-free** graphical drivers.

<ol type="i">
<li>Let it <b>auto-detect</b> the recommended drivers. You should double check.</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/nvcleanstall_auto_detect.png" width="40%" height="40%">
</p>
    
<li>Select the <b>Recommended</b> components if desired. It depdends on the type of computer and preferences. For laptops <b>Optimus</b> is somewhat required.</li>
    
<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/nvcleanstall_components.png" width="40%" height="40%">
</p>
    
<li>Then for the tweaks, set the <b>preferred</b> ones. You could <b>disable the telemetry</b>, <b>disable custom type of install</b> at all (make it faster), <b>clean the older driver traces</b> (not required if uninstalled trough DDU), <b>add support for custom/older hardware</b>, <b>enable DLSS version indicator</b>, <b>disable MPO</b> (which has to do with a technique that allows different user interface to be displayed on the screen at the same time and appear as if they are layered on top of each othe) - it is usable for stable windowed resolution apps and so on; it's useful but somewhat buggy in older versions, newer drivers should do it just fine. If something is wrong, e.g. there are crashes or slower experiences, this could be a reason, and if so, try to disable it. You can disable <b>Ansel</b> too, which is a in-game screenshot tool. 
    
There are also some <b>advanced settings</b> which could break or mess with the drivers and some of them even need repackage and a new signature (incompatible with some anti-cheats). It is able to <b>disable some in-driver telemetry</b>, <b>disable process containers</b> (see task manager), <b>disable the buggy audio timer</b> (not useful if there is no HD Audio component), <b>enable MSI</b> (it allows computer components, be it a GPU, to directly send interrupt messages to the CPU, bypassing the PIC which improves efficiency and reduces latency) - <i>older NVIDIA GPUs didn't have this feature enabled by default</i>. The newest models available probably have it enabled (manual check required). Also, it could <b>disable HDCP</b> (which is a digital copy protection module - some apps and streams will not allow their usage without this one), <b>enable custom patch for nvenc video encoding</b> (in day-to-day usage, the patch is beneficial for users who frequently work with video encoding tasks or streamers who need to encode multiple video streams at the same time).</li>

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/nvcleanstall_tweaks.png" width="40%" height="40%">
</p>

</ol>
    
Furthermore, for <b>AMD-enabled GPUs</b> there is no identical replacement. Their official installer has very few bloated components, making it unecesarry to unbloat it. But still, the closest available alternative in terms of operating mechanism would be [RadeonSoftwareSlimmer](https://github.com/GSDragoon/RadeonSoftwareSlimmer), which is pretty straight forward.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/radeon_software_slimmer.png" width="60%" height="60%">
</p>

##### Misc

In addition, don't forget to [activate](https://github.com/massgravel/Microsoft-Activation-Scripts "activate") Windows and <i>other</i> components.

#### Debloating

The default Taskbar, Start Menu, Context Menu, and File Explorer experiences are regrettable. [StartAllBack](https://www.startallback.com/ "StartAllBack") is **enhancing all elements** organically.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/startallback.png" width="50%" height="50%">
</p>

The first part of **debloating** is through [O&O Shutup](https://www.oo-software.com/en/shutup10 "O&O Shutup"). It can tweak most the usual settings. [Here is my exported configuration](https://github.com/ArmynC/ArminC-Windows-Debloat/blob/main/cfg/ooshutup10.cfg "Here is my exported configuration")... I've tried to combine the efficiency of use with stability. Disabling every feature can lead to compatibility errors. 

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/oo_shutup.png" width="50%" height="50%">
</p>

The second part is through [SohpiApp](https://github.com/Sophia-Community/SophiApp "SohpiApp"). It has some more in-depth settings. You can **disable some services** that are not needed and even **uninstall UWP apps**. Try to uninstall any app not needed (e.g., help, maps) but **avoid uninstalling the complex ones, linked to the operating system** such as Edge, Cortana or Xbox if not needed. These days, Windows is so interconnected that it will be difficult or almost impossible to use it in this way without any errors, at all.

<p align="center">
<img src="https://raw.githubusercontent.com/ArmynC/ArminC-Windows-Debloat/main/img/sophiapp.png" width="50%" height="50%">
</p>

#### Other apps

These apps are optional, or some of them may be included in the operating system.

##### Runtime
- [Microsoft Visual C++ Redistributable](https://github.com/abbodi1406/vcredist "Microsoft Visual C++ Redistributable")
- [Microsoft DirectX Legacy](https://www.microsoft.com/en-us/download/details.aspx?id=8109 "Microsoft DirectX Legacy") 
- [.NET Framework 3.5](https://www.microsoft.com/en-us/download/details.aspx?id=21 ".NET Framework 3.5")
- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48 ".NET Framework 4.8")
- [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0 ".NET 7.0")
- [Java](https://www.java.com/download/ie_manual.jsp "Java")

##### Tools
- [Revo Uninstaller](https://www.revouninstaller.com/ "Revo Uninstaller") or [BCUninstaller](https://github.com/Klocman/Bulk-Crap-Uninstaller "BCUninstaller")
- [IObit Unlocker](https://www.iobit.com/en/iobit-unlocker.php "IObit Unlocker")
- [qBittorent](https://www.qbittorrent.org/ "qBittorent")
- [WinCDEmu](https://wincdemu.sysprogs.org/ "WinCDEmu")
- [Parsec](https://parsec.app/ "Parsec")
- [WingetUI](https://github.com/martinet101/WingetUI "WingetUI")
- [Dimmer](https://www.nelsonpires.com/software/dimmer "Dimmer")

##### Media
- [Spotify-X](https://github.com/amd64fox/SpotX "Spotify-X")
- [Stremio](https://www.stremio.com/ "Stremio")
- [Bluetooth Audio Receiver](https://apps.microsoft.com/store/detail/bluetooth-audio-receiver/9N9WCLWDQS5J?hl=en-us&gl=us "Bluetooth Audio Receiver")

##### Development
- [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")
- [Visual Studio](https://visualstudio.microsoft.com/ "Visual Studio")
- [GitHub](https://desktop.github.com/ "GitHub")
- [Office](https://forums.mydigitallife.net/threads/office-r-tool-the-new-era.84450/ "Office")
- [Beyond Compare](https://www.scootersoftware.com/download.php "Beyond Compare")

##### Communication
- [Discord](https://discord.com/ "Discord")
- [Teams](https://www.microsoft.com/en-ww/microsoft-teams/download-app "Teams")

##### Games
- [Steam](https://store.steampowered.com/about/ "Steam")
- [Heroic Launcher](https://heroicgameslauncher.com/ "Heroic Launcher")

## Support

Reach out to me via the **[profile addresses](https://github.com/ArmynC)**.

## License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)