# DiscordChatExporter

[![Status](https://img.shields.io/badge/status-maintenance-ffd700.svg)](https://github.com/Tyrrrz/.github/blob/prime/docs/project-status.md)
[![Made in Ukraine](https://img.shields.io/badge/made_in-ukraine-ffd700.svg?labelColor=0057b7)](https://tyrrrz.me/ukraine)
[![Build](https://img.shields.io/github/actions/workflow/status/Tyrrrz/DiscordChatExporter/main.yml?branch=prime)](https://github.com/Tyrrrz/DiscordChatExporter/actions)
[![Coverage](https://img.shields.io/codecov/c/github/Tyrrrz/DiscordChatExporter/prime)](https://codecov.io/gh/Tyrrrz/DiscordChatExporter)
[![Release](https://img.shields.io/github/release/Tyrrrz/DiscordChatExporter.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Downloads](https://img.shields.io/github/downloads/Tyrrrz/DiscordChatExporter/total.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Pulls](https://img.shields.io/docker/pulls/tyrrrz/discordchatexporter)](https://hub.docker.com/r/tyrrrz/discordchatexporter)
[![Discord](https://img.shields.io/discord/869237470565392384?label=discord)](https://discord.gg/2SUWKFnHSm)

<table>
    <tr>
        <td width="99999" align="center">Development of this project is entirely funded by the community. <b><a href="https://tyrrrz.me/donate">Consider donating to support!</a></b></td>
    </tr>
</table>

<p align="center">
    <img src="favicon.png" alt="Icon" />
</p>

**DiscordChatExporter** is an application that can be used to export message history from any [Discord](https://discord.com) channel to a file.
It works with direct messages, group messages, and server channels, and supports Discord's dialect of markdown as well as most other rich media features.

> [!WARNING]
> While **DiscordChatExporter** allows it, automating user accounts is against Discord TOS and may result in you getting banned.
> If possible, use a bot to export chat logs from accessible channels.

## ToS by politic-coder been here, but i remove it :(

- Its too bad that this product is restricted for people from some countries just because their monarchs do very bad things. **What is our fault? We dont support they but we cant do anythink with it. And we dont select where born. Stop internet war, bro....** 


## Download

- **Graphical user interface** (desktop app):
  - 🟢 **[Stable release](https://github.com/Tyrrrz/DiscordChatExporter/releases/latest)**: look for `DiscordChatExporter.*.zip`
  - 🟠 [CI build](https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml): look for `DiscordChatExporter.*.zip`
  - 📦 [Scoop](https://scoop.sh/#/apps?q=DiscordChatExporter&p=1&id=c71b7367623c560a2dc746b9739b9568b79b59ae): `scoop install extras/discordchatexporter` (community-maintained)
  - 📦 [WinGet](https://winstall.app/apps/Tyrrrz.DiscordChatExporter.GUI): `winget install Tyrrrz.DiscordChatExporter.GUI` (community-maintained)
  - 📦 [AUR](https://aur.archlinux.org/packages/discord-chat-exporter-gui): `yay -S discord-chat-exporter-gui` (community-maintained)
  - 📦 [Nix](https://search.nixos.org/packages?show=discordchatexporter-desktop): `nix-shell -p discordchatexporter-desktop` (community-maintained)
- **Command-line interface** (terminal app):
  - 🟢 **[Stable release](https://github.com/Tyrrrz/DiscordChatExporter/releases/latest)**: look for `DiscordChatExporter.Cli.*.zip`
  - 🟠 [CI build](https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml): look for `DiscordChatExporter.Cli.*.zip`
  - 🐋 [Docker](https://hub.docker.com/r/tyrrrz/discordchatexporter): `docker pull tyrrrz/discordchatexporter`
  - 📦 [WinGet](https://winstall.app/apps/Tyrrrz.DiscordChatExporter.CLI): `winget install Tyrrrz.DiscordChatExporter.CLI` (community-maintained)
  - 📦 [AUR](https://aur.archlinux.org/packages/discord-chat-exporter-cli): `yay -S discord-chat-exporter-cli` (community-maintained)
  - 📦 [Nix](https://search.nixos.org/packages?show=discordchatexporter-cli): `nix-shell -p discordchatexporter-cli` (community-maintained)

> [!IMPORTANT]
> To launch the GUI version of the app on MacOS, you may need to first remove the downloaded file from quarantine.
> You can do that by running the following command in the terminal: `xattr -rd com.apple.quarantine DiscordChatExporter.app`.

> [!NOTE]
> Community-maintained packages are published independently from this repository and may not always be up to date with the latest release.

> [!NOTE]
> If you're unsure which build is right for your system, consult with [this page](https://useragent.cc) to determine your OS and CPU architecture.

## Features

- Cross-platform graphical and command-line interfaces
- Authentication via either a user or a bot token
- Multiple output formats: HTML (dark/light), TXT, CSV, JSON
- Support for markdown, attachments, embeds, emoji, and other rich media features
- File partitioning, date ranges, message filtering, and other export options
- Self-contained exports that can be viewed offline

## Screenshots

![channel list](.assets/list.png)
![rendered output](.assets/output.png)

## See also

- [**Chat Analytics**](https://github.com/mlomb/chat-analytics) — solution for analyzing chat patterns of Discord users, using exports produced by **DiscordChatExporter**.
- [**DiscordChatExporter-frontend**](https://github.com/slatinsky/DiscordChatExporter-frontend) — convenient viewer for exports produced by **DiscordChatExporter**.
