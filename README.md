<!-- Start -->
<div align=center>

<img src="photon-logo.png"></img>

# Photon

Minecraft optimization framework prioritizing performance, simplicity, and compatibility. 1.7.10-1.21.5 across Fabric, Forge, NeoForge, and Quilt!

[![PhotonMC](github-link.svg)](https://github.com/PhotonMC)
[![Read the Wiki](wiki-link.svg)](https://github.com/PhotonMC/home/wiki)

[![Mod Request](modrequest-link.svg)](https://github.com/PhotonMC/home/issues/new?template=mod-request.yml)
[![Bug Report](bugreport-link.svg)](https://github.com/PhotonMC/home/issues/new?template=bug-report.yml)

[![Modlist](modlist-link.svg)](https://github.com/PhotonMC/home/blob/main/MODLIST.md)

</div>

Photon is a client-side modpack that dramatically improves performance on Minecraft 1.7.10-1.21.5 across Fabric, Forge, NeoForge, and Quilt. Photon is deliberately built with simplicity and compatibility in mind. As a result, Photon can be used as a framework for building larger, content-focused modpacks.

<!--Download-->
## Download

[![Modrinth](modrinth-link.svg)](https://modrinth.com/modpack/phtn)

<!--Installation-->
## Installation and Setup

**It is assumed that you have already installed and setup the Modrinth app or another modded launcher that supports Modrinth packs. This installation guide will be for the Modrinth app, although other launchers should be a similar process. If you would like to download the Modrinth app, you can do so here: https://modrinth.com/app.**

<details>
    <summary><h3>Standalone</h3></summary>
    Installation guide for using Photon standalone without any additional mods or configuration.
    <h4>Downloading</h4>
    <ol>
        <li>Launch the Modrinth app</li>
        <li>Click the <code><img src="discover-content.png" style="vertical-align:middle; display:inline"> Discover content</code> icon on the left sidebar</li>
        <li>Search for <code>Photon</code> under <code>Modpacks</code></li>
        <li>Click on the <code><img src="photon-icon.png" style="vertical-align:middle; display:inline"> Photon Icon</code></li>
        <li>Navigate to <code>Versions</code></li>
        <li>Filter to your desired Modloader and Minecraft Version by using the <code>Platform</code> and <code>Game versions</code> dropdown menus</li>
        <li>Select the newest Photon release (First option)</li>
        <li>Click <code>Install</code></li>
    </ol>
    <h4>Updating</h4>
    <ol>
        <li>Select your Photon instance (<b>Don't click <code>Play</code></b>)</li>
        <li>Click the green <code>Update pack</code> option next to <code>Refresh</code></li>
        <li>Scroll until you find the newest release of Photon for <b>your desired modloader and Minecraft version</b> (If the newest choice for your modloader and MC version has a gray check next to it, you are up to date)</li>
        <li>Click the green, antiparallel <code>arrows icon</code> next to your chosen Photon release</li>
    </ol>
</details>

<details>
    <summary><h3>Modpack Base</h3></summary>
    Installation guide for using Photon as a base for your modpack (<b>not a guide on how to properly create a modpack</b>).
    <h4>Downloading</h4>
    <ol>
        <li>Launch the Modrinth app</li>
        <li>Click the <code><img src="discover-content.png" style="vertical-align:middle; display:inline"> Discover content</code> icon on the left sidebar</li>
        <li>Search for <code>Photon</code> under <code>Modpacks</code></li>
        <li>Click on the <code><img src="photon-icon.png" style="vertical-align:middle; display:inline"> Photon Icon</code></li>
        <li>Navigate to <code>Versions</code></li>
        <li>Filter to your desired Modloader and Minecraft Version by using the <code>Platform</code> and <code>Game versions</code> dropdown menus</li>
        <li>Select the newest Photon release (First option)</li>
        <li>Click <code>Install</code></li>
    </ol>
    <h4>Setup</h4>
    <ol>
        <li>Select your Photon instance (<b>Don't click <code>Play</code></b>)</li>
        <li>Click the <code><img src="instance-settings.png" style="vertical-align:middle; display:inline"> Instance settings</code> icon</li>
        <li>Select <code>Installation</code></li>
        <li>Click <code>Unlink instance</code></li>
        <li>Confirm to <code>Unlink instance</code></li>
        <li>You may use this instance as your own custom modpack</li>
    </ol>
    <h4>Updating</h4>
    <b>*Backup your modpack before updating Photon!*</b>
    <ol>
        <li>Perform the <code><b>Downloading</b></code> steps listed above for a new, temporary Photon instance</li>
        <li>Select the temporary Photon instance (<b>Don't click <code>Play</code></b>)</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Copy the <code>config</code> and <code>mods</code> folders (highlight both by holding <code>Ctrl</code> and selecting each, and copy to clipboard by pressing <code>Ctrl + C</code>)</li>
        <li>Close the File Explorer window and navigate back to the Modrinth app</li>
        <li>Navigate to the modpack you are updating</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Without selecting any of the subfolders/files, press <code>Ctrl + V</code> to merge to the <code>mods</code> and <code>config</code> folders (Select <code>Replace the files in the destination</code> to confirm the merging)</li>
        <li>You may delete the temporary Photon instance (located in <code><img src="instance-settings.png" style="vertical-align:middle; display:inline"> Instance settings</code>)</li>
    </ol>
</details>

<details>
    <summary><h3>Preexisting Modpack</h3></summary>
    Installation guide for using Photon in a preexisting modpack. <b>*Backup your modpack before incorporating Photon into it!*</b>
    <h4>Downloading</h4>
    <ol>
        <li>Launch the Modrinth app</li>
        <li>Click the <code><img src="discover-content.png" style="vertical-align:middle; display:inline"> Discover content</code> icon on the left sidebar</li>
        <li>Search for <code>Photon</code> under <code>Modpacks</code></li>
        <li>Click on the <code><img src="photon-icon.png" style="vertical-align:middle; display:inline"> Photon Icon</code></li>
        <li>Navigate to <code>Versions</code></li>
        <li>Filter to your desired Modloader and Minecraft Version by using the <code>Platform</code> and <code>Game versions</code> dropdown menus</li>
        <li>Select the newest Photon release (First option)</li>
        <li>Click <code>Install</code></li>
    </ol>
    <h4>Setup</h4>
    <ol>
        <li>Select the Photon instance (<b>Don't click <code>Play</code></b>)</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Copy the <code>config</code> and <code>mods</code> folders (highlight both by holding <code>Ctrl</code> and selecting each, and copy to clipboard by pressing <code>Ctrl + C</code>)</li>
        <li>Close the File Explorer window and navigate back to the Modrinth app</li>
        <li>Navigate to the modpack you are incorporating Photon into</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Without selecting any of the subfolders/files, press <code>Ctrl + V</code> to merge to the <code>mods</code> and <code>config</code> folders (Select <code>Replace the files in the destination</code> to confirm the merging)</li>
        <li>You may delete the Photon instance (located in <code><img src="instance-settings.png" style="vertical-align:middle; display:inline"> Instance settings</code>)</li>
    </ol>
    <h4>Updating</h4>
    <ol>
        <li>Perform the <code><b>Downloading</b></code> steps listed above for a new, temporary Photon instance</li>
        <li>Select the temporary Photon instance (<b>Don't click <code>Play</code></b>)</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Copy the <code>config</code> and <code>mods</code> folders (highlight both by holding <code>Ctrl</code> and selecting each, and copy to clipboard by pressing <code>Ctrl + C</code>)</li>
        <li>Close the File Explorer window and navigate back to the Modrinth app</li>
        <li>Navigate to the modpack you are updating</li>
        <li>Click the <code>ellipsis (three dots) menu</code> located next to the green <code>Play button</code></li>
        <li>Select <code>Open folder</code> and navigate to the new File Explorer window</li>
        <li>Without selecting any of the subfolders/files, press <code>Ctrl + V</code> to merge to the <code>mods</code> and <code>config</code> folders (Select <code>Replace the files in the destination</code> to confirm the merging)</li>
        <li>You may delete the temporary Photon instance (located in <code><img src="instance-settings.png" style="vertical-align:middle; display:inline"> Instance settings</code>)</li>
    </ol>
</details>

<!--Repo List-->
## Repositories

<!--Photon Fabric links-->
<details>
    <summary>Photon <img src="fabric-logo.png" style="vertical-align:middle; display:inline">Fabric Repositories</summary>
    <ul>
        <li><a href="https://github.com/PhotonMC/fabric-1.21.5">Photon Fabric 1.21.5</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.21.4">Photon Fabric 1.21.4</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.21.1">Photon Fabric 1.21.1</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.20.6">Photon Fabric 1.20.6</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.20.4">Photon Fabric 1.20.4</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.20.1">Photon Fabric 1.20.1</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.19.4">Photon Fabric 1.19.4</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.18.2">Photon Fabric 1.18.2</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.17.1">Photon Fabric 1.17.1</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.16.5">Photon Fabric 1.16.5</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.15.2">Photon Fabric 1.15.2</a></li>
        <li><a href="https://github.com/PhotonMC/fabric-1.14.4">Photon Fabric 1.14.4</a></li>
    </ul> 
</details>

<!--Photon Forge links-->
<br/>
<details>
    <summary>Photon <img src="forge-logo.png" style="vertical-align:middle; display:inline">Forge Repositories</summary>
    <ul>
        <li><a href="https://github.com/PhotonMC/forge-1.20.1">Photon Forge 1.20.1</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.19.4">Photon Forge 1.19.4</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.18.2">Photon Forge 1.18.2</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.17.1">Photon Forge 1.17.1</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.16.5">Photon Forge 1.16.5</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.12.2">Photon Forge 1.12.2</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.11.2">Photon Forge 1.11.2</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.10.2">Photon Forge 1.10.2</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.9.4">Photon Forge 1.9.4</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.8.9">Photon Forge 1.8.9</a></li>
        <li><a href="https://github.com/PhotonMC/forge-1.8.9">Photon Forge 1.7.10</a></li>
    </ul>
</details>

<!--Photon NeoForge links-->
<br/>
<details>
    <summary>Photon <img src="neoforge-logo.png" style="vertical-align:middle; display:inline">NeoForge Repositories</summary>
    <ul>
        <li><a href="https://github.com/PhotonMC/neoforge-1.21.5">Photon NeoForge 1.21.5</a></li>
        <li><a href="https://github.com/PhotonMC/neoforge-1.21.4">Photon NeoForge 1.21.4</a></li>
        <li><a href="https://github.com/PhotonMC/neoforge-1.21.1">Photon NeoForge 1.21.1</a></li>
        <li><a href="https://github.com/PhotonMC/neoforge-1.20.6">Photon NeoForge 1.20.6</a></li>
        <li><a href="https://github.com/PhotonMC/neoforge-1.20.4">Photon NeoForge 1.20.4</a></li>
        <li><a href="https://github.com/PhotonMC/neoforge-1.20.1">Photon NeoForge 1.20.1</a></li>
    </ul>
</details>

<!--Photon Quilt links-->
<br/>
<details>
    <summary>Photon <img src="quilt-logo.png" style="vertical-align: middle; display:inline">Quilt Repositories</summary>
    <ul>
        <li><a href="https://github.com/PhotonMC/quilt-1.21.5">Photon Quilt 1.21.5</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.21.1">Photon Quilt 1.21.1</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.20.6">Photon Quilt 1.20.6</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.20.4">Photon Quilt 1.20.4</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.20.1">Photon Quilt 1.20.1</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.19.4">Photon Quilt 1.19.4</a></li>
        <li><a href="https://github.com/PhotonMC/quilt-1.18.2">Photon Quilt 1.18.2</a></li>
    </ul>
</details>

<!--Credits -->
## Credits

<ul>
    <li>PhotonMC logo: <a href="https://game-icons.net">game-icons.net</a> (by <a href="https://lorcblog.blogspot.com/">Lorc</a> under <a href="https://creativecommons.org/licenses/by/3.0/">CC BY 3.0</a>)</li>
    <li>Read the Wiki icon: <a href="https://www.iconfinder.com/icons/8664950/book_education_icon">iconfinder.com</a> (under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>)</li>
    <li>Bug Report icon: <a href="https://www.iconfinder.com/icons/9104219/warning_danger_attention_caution_alert_icon">iconfinder.com</a> (under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>)</li>
    <li>Mod List icon: <a href="https://www.iconfinder.com/icons/9040475/list_ul_icon">iconfinder.com</a> (under <a href="https://opensource.org/license/MIT">The MIT License</a>)</li>
    <li>Discover content icon: <a href="https://www.iconfinder.com/icons/8666705/compass_icon">iconfinder.com</a> (under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>)</li>
    <li>Instance settings icon: <a href="https://www.iconfinder.com/icons/2849830/multimedia_options_setting_settings_gear_icon">iconfinder.com</a> (under <a href="https://creativecommons.org/licenses/by/3.0/">CC BY 3.0</a>)</li>
    <li>Badges: <a href="https://shields.io/">shields.io</a> (under <a href="https://creativecommons.org/publicdomain/zero/1.0/deed">CC0 1.0</a>)</li>
</ul>