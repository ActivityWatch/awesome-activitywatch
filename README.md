Awesome ActivityWatch :star2: :fire: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=====================

A collections of awesome links to resources relating to ActivityWatch, the free and open-source automated time-tracker.

**Please star :star: and share this repo! :loudspeaker:**

This list is just getting started. *Do you see anything missing? [Make a pull request!](https://github.com/ActivityWatch/awesome-activitywatch/edit/master/README.md) :pencil2:*

# Official links :link:

- [Website](https://activitywatch.net)
- [GitHub](https://github.com/ActivityWatch)
- [Forum](https://forum.activitywatch.net/)
- [Twitter](https://twitter.com/ActivityWatchIt)
- [Discord](https://discord.gg/vDskV9q)
- [LinkedIn](https://www.linkedin.com/company/activitywatch/)
- [r/ActivityWatch](https://www.reddit.com/r/ActivityWatch/) (mostly inactive), subreddit for ActivityWatch

# Applications

The main ActivityWatch application and alternative implementations:

- **ActivityWatch** ([releases](https://github.com/ActivityWatch/activitywatch/releases)) - The official distribution, includes:
  - aw-qt (tray application)
  - aw-server & aw-server-rust (storage and API)
  - aw-watcher-window (window tracking)
  - aw-watcher-afk (idle detection)
  - aw-watcher-input (keyboard/mouse usage)
  - aw-sync (data syncing)
  - aw-notify (notifications)
- [aw-tauri](https://github.com/ActivityWatch/aw-tauri) (WIP), experimental/alternative distribution of ActivityWatch using Tauri
- [Workflow](https://flathub.org/apps/com.gitlab.cunidev.Workflow), basic screentime application using GTK
- [Codewatch](https://github.com/jca41/codewatch), desktop client for ActivityWatch focused on software development and productivity.
- [yet-another-UI-for-AW](https://github.com/K-Kuyama/yet-another-UI-for-AW/), a native UI for ActivityWatch with Japanese localization ([announcement forum post](https://forum.activitywatch.net/t/another-gui-client-for-aw/2748))

# Documentation :books:

- [Official Documentation](https://docs.activitywatch.net)
- [Getting Started Guide](https://docs.activitywatch.net/en/latest/getting-started.html)
- [FAQ](https://docs.activitywatch.net/en/latest/faq.html)

# Server Implementations :computer:

ActivityWatch has a modular architecture that includes a server component for storing and analyzing the collected data.

- [aw-server](https://github.com/ActivityWatch/aw-server), an official server implementation written in Python
- [aw-server-rust](https://github.com/ActivityWatch/aw-server-rust), an official server implementation written in Rust for improved performance

# Client Libraries

The ActivityWatch ecosystem provides client libraries to help developers interact with the ActivityWatch server API and create custom watchers, integrations, extensions, or applications. Here are the official client libraries:

 - [aw-client](https://github.com/ActivityWatch/aw-client), a client library written in Python
 - [aw-client-js](https://github.com/ActivityWatch/aw-client-js), a client library written in JavaScript/TypeScript
 - [aw-client-rust](https://github.com/ActivityWatch/aw-server-rust/tree/master/aw-client-rust), a client library written in Rust

# Desktop Widgets :desktop_computer:

- [activitywatch-plasmoid](https://github.com/NicoWeio/activitywatch-plasmoid), a KDE Plasma widget for ActivityWatch
- [activitywatch-status-gnome-shell](https://extensions.gnome.org/extension/7774/activitywatch-status/), GNOME Shell extension that shows the total time spent today ([source](https://codeberg.org/cweiske/activitywatch-status-gnome-shell))

# Watchers :watch:

ActivityWatch comes with two watchers enabled by default:

- [aw-watcher-afk](https://github.com/ActivityWatch/aw-watcher-afk) - Watches for mouse & keyboard activity to detect if the user is active
- [aw-watcher-window](https://github.com/ActivityWatch/aw-watcher-window) - Watches the active window and its metadata

## Window Watchers :desktop_computer:

- [aw-watcher-window](https://github.com/ActivityWatch/aw-watcher-window) - The official window watcher for Windows, macOS, and Linux (X11)
- [aw-watcher-window-wayland](https://github.com/ActivityWatch/aw-watcher-window-wayland) - Window watcher for Wayland by @johan-bjareholt
- [awatcher](https://github.com/2e3s/awatcher) - A compiled watcher for X11 and Wayland by @2e3s
- [aw-watcher-enhanced](https://github.com/kepptic/aw-watcher-enhanced) - Enhanced window watcher with OCR screen capture, LLM-powered context extraction (via Ollama), smart idle detection, and remote desktop support by @kepptic

## Browser Watchers :globe_with_meridians:

- [aw-watcher-web](https://github.com/ActivityWatch/aw-watcher-web) - Official browser extension for Chrome, Edge, and Firefox

## Editor Watchers :pencil2:

- [aw-watcher-vim](https://github.com/ActivityWatch/aw-watcher-vim) - Vim extension by @johan-bjareholt and @ahnlabb
- [aw-watcher-vscode](https://github.com/ActivityWatch/aw-watcher-vscode) - Visual Studio Code extension by @Otto-AA
- [activity-watch-mode](https://github.com/pauldub/activity-watch-mode) - Emacs mode by @pauldub
- [aw-watcher-jetbrains](https://github.com/OlivierMary/aw-watcher-jetbrains) - For all JetBrains IDEs by @OlivierMary ([JetBrains Marketplace](https://plugins.jetbrains.com/plugin/11361-activity-watcher))
- [ActivityWatchVS](https://github.com/LaggAt/ActivityWatchVS) - Visual Studio extension by @LaggAt
- [aw-idea](https://github.com/pascalwhoop/aw-idea) - JetBrains IDE extension by @pascalwhoop (WIP)
- [aw-watcher-sublime](https://github.com/kostasdizas/aw-watcher-sublime) - Sublime Text 3 by @kostasdizas
- [aw-watcher-atom](https://github.com/NicoWeio/aw-watcher-atom) - Atom by @NicoWeio
- [AwWatcherNetBeans82](https://github.com/pytlus93/AwWatcherNetBeans82) - NetBeans 8.2 by @pytlus93
- [aw-watcher-obsidian](https://github.com/LordGrimmauld/aw-watcher-obsidian) - Obsidian.md extension by @LordGrimmauld

## Media Watchers :musical_note:

- [aw-watcher-spotify](https://github.com/ActivityWatch/aw-watcher-spotify) - Tracks currently playing Spotify tracks (Beta)
- [aw-watcher-chromecast](https://github.com/ActivityWatch/aw-watcher-chromecast) - For Chromecast devices (WIP)
- [aw-watcher-openvr](https://github.com/ActivityWatch/aw-watcher-openvr) - For VR applications (WIP)
- [aw-watcher-mpv-sender](https://github.com/RundownRhino/aw-watcher-mpv-sender) - Tracks currently playing mpv videos (WIP)
- [aw-watcher-media-player](https://github.com/2e3s/aw-watcher-media-player) - Tracks system-wide media playback
- [aw-watcher-lastfm](https://github.com/brayo-pip/aw-watcher-lastfm) - Tracks Last.fm scrobbles (supports most streaming services)

## Other Watchers :gear:

- [aw-watcher-input](https://github.com/ActivityWatch/aw-watcher-input) - Tracks keyboard/mouse usage statistics
- [aw-watcher-table](https://github.com/Alwinator/aw-watcher-table) - Monitors height-adjustable desk position by @Alwinator
- [aw-watcher-tmux](https://github.com/akohlbecker/aw-watcher-tmux) - Monitors tmux sessions by @akohlbecker
- [aw-watcher-ask](https://github.com/bcbernardo/aw-watcher-ask) - Periodically asks user questions (WIP)
- [aw-watcher-utilization](https://github.com/Alwinator/aw-watcher-utilization) - System resource monitoring by @Alwinator
- [aw-watcher-anki](https://github.com/abdnh/aw-watcher-anki) - Tracks Anki flashcard review time
- [aw-watcher-steam](https://github.com/Edwardsoen/aw-watcher-steam) - Tracks Steam gaming sessions
- [aw-watcher-toggl](https://github.com/RTnhN/aw-watcher-toggl) - Imports time entries from Toggl
- [aw-watcher-netstatus](https://github.com/sameersismail/aw-watcher-netstatus) - Network connectivity monitoring by @sameersismail
- [aw-watcher-buttons](https://github.com/RTnhN/aw-watcher-buttons) - Arduino-based hardware button tracking (WIP)

We also maintain a list of [watchers in the documentation](https://docs.activitywatch.net/en/latest/watchers.html).

Want to create your own watcher? Check out the [writing watchers guide](https://docs.activitywatch.net/en/latest/examples/writing-watchers.html) in the documentation.

Have you written a watcher? Submit a PR to have it included here!

# Sync

 - [aw-sync](https://github.com/ActivityWatch/aw-server-rust/tree/master/aw-sync), the official sync-with-folder/bring-your-own-sync solution for ActivityWatch
 - [aw-sync-suite](https://github.com/phrp720/aw-sync-suite), a centralized sync solution backed by Prometheus and visualized with Grafana, by @phrp720
 - [activitywatch-exporter](https://github.com/rare-magma/activitywatch-exporter), CLI tool that uploads the ActivityWatch data from the aw-server API to InfluxDB on a daily basis

# AI/LLM Integrations 🤖

- [activitywatch-mcp-server](https://github.com/8bitgentleman/activitywatch-mcp-server) - A Model Context Protocol (MCP) server that connects to ActivityWatch, allowing LLMs like Claude to interact with your time tracking data

# Videos :tv:

- [ActivityWatch - Application time tracking done well](https://www.youtube.com/watch?v=FIP3Qvja7RM) (2023-2-3)
- [ActivityWatch: Save Time With Helpful Telemetry](https://www.youtube.com/watch?v=ZmYNc-dXm2s) by @BrodieRobertson (2021-6-13)
- [ActivityWatch Development Visualization 2014-2020 (with Gource)](https://www.youtube.com/watch?v=zjIn43lZq3U) by @ErikBjare (2020-12-20)

# Custom dashboards :bar_chart:

- Metabase dashboard by @SqrtMinusTwo: https://twitter.com/ActivityWatchIt/status/1522126015082151936
- Grafana + PrometheusDB + InfluxDB dashboard by @KShivendu: https://twitter.com/KShivendu_/status/1697483679495557228

# Donations :moneybag:

Support the development of ActivityWatch by making a donation. Your contribution helps maintain and improve the software, ensuring its continued development.

- [GitHub Sponsors](https://github.com/sponsors/ActivityWatch), support the project through GitHub Sponsors
- [Open Collective](https://opencollective.com/activitywatch), donate and view transparent expenses and funding on Open Collective
- Support individual contributors
  - Erik Bjäreholt's [GitHub Sponsors](https://github.com/sponsors/ErikBjare) or [Patreon](https://www.patreon.com/activitywatch)
  - Johan Bjäreholt's [GitHub Sponsors](https://github.com/sponsors/johan-bjareholt)
- For more, see the [Donate page](https://activitywatch.net/donate/) on the website

Thank you for supporting ActivityWatch and helping it stay afloat financially as free and open-source software! :heart:

# Other links :link:

- [Awesome Quantified Self](https://github.com/woop/awesome-quantified-self), a list of awesome quantified self resources
- [Superuser Labs](https://superuserlabs.org/), company owned and run by founder Erik Bjäreholt for consulting and other ActivityWatch-related services (among other things).
  - [LinkedIn](https://www.linkedin.com/company/superuser-labs/)
  - [Twitter](https://twitter.com/SuperusrLabs)

