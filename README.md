# Awesome KOReader [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A community-driven, curated list of awesome plugins, patches, tools, themes, sync servers, and resources for [KOReader](https://github.com/koreader/koreader) — the open-source document viewer for e-ink readers.

**KOReader** runs on Kindle, Kobo, PocketBook, reMarkable, Cervantes, and Android devices. It supports PDF, DjVu, EPUB, FB2, CBZ, and many more formats.

**Contributions are welcome!** Please read the [contributing guide](CONTRIBUTING.md) before submitting a pull request.

---

## Contents

- [Official Resources](#official-resources)
- [Plugin Management](#plugin-management)
- [AI & Assistants](#ai--assistants)
- [Book Discovery & Downloads](#book-discovery--downloads)
- [Sync & File Transfer](#sync--file-transfer)
- [Highlights & Annotations](#highlights--annotations)
- [Dictionary & Language Learning](#dictionary--language-learning)
- [RSS & Read-It-Later](#rss--read-it-later)
- [Reading Services Integration](#reading-services-integration)
- [Comics & Manga](#comics--manga)
- [UI & Customization](#ui--customization)
- [Reading Tracking & Goals](#reading-tracking--goals)
- [Utilities & Tools](#utilities--tools)
- [Games & Entertainment](#games--entertainment)
- [Device-Specific](#device-specific)
- [User Patches](#user-patches)
- [Self-Hosted Sync Servers](#self-hosted-sync-servers)
- [Desktop Companions & Tools](#desktop-companions--tools)
- [Calibre Integration](#calibre-integration)
- [Themes & Icons](#themes--icons)
- [Scripts & Automation](#scripts--automation)
- [Guides & Tutorials](#guides--tutorials)
- [Community](#community)

---

## Official Resources

- [koreader/koreader](https://github.com/koreader/koreader) - The main KOReader repository. Releases, issues, and source code.
- [koreader/contrib](https://github.com/koreader/contrib) - Official collection of non-official community plugins and scripts maintained under the KOReader org.
- [KOReader Wiki](https://github.com/koreader/koreader/wiki) - Official wiki with installation guides, user patches documentation, and device-specific notes.
- [KOReader Website](https://koreader.rocks) - Official website with download links and news.
- [KOReader User Patches Wiki](https://github.com/koreader/koreader/wiki/User-patches) - How to install and write your own user patches.
- [koreader/koreader-base](https://github.com/koreader/koreader-base) - Base framework providing the native/C layer.
- [koreader/crengine-ng](https://github.com/koreader/crengine-ng) - The CREngine document rendering engine used by KOReader.
- [koreader/android-luajit-launcher](https://github.com/koreader/android-luajit-launcher) - Android launcher for KOReader's LuaJIT-based runtime.
- [KoboUSBMS](https://github.com/koreader/KoboUSBMS) - Standalone mass storage mode for Kobo devices.
- [koreader/translations](https://github.com/koreader/koreader-translations) - Community-contributed translations for KOReader.

---

## Plugin Management

*Tools for discovering, installing, and managing plugins without leaving your device.*

- [appstore.koplugin](https://github.com/omer-faruq/appstore.koplugin) - In-device app store: browse, install, update, and remove community plugins and patches directly from within KOReader. Searches GitHub topics `koreader-plugin` and `koreader-user-patch`. ⭐ 136+

---

## AI & Assistants

*Large language model integrations for reading assistance, translation, and summarization.*

- [assistant.koplugin](https://github.com/omer-faruq/assistant.koplugin) - AI helper supporting Claude, GPT-4, Gemini, DeepSeek, Ollama, and more. Interact with AI while reading — translate, summarize, explain passages. ⭐ 442+
- [koassistant.koplugin](https://github.com/zeeyado/koassistant.koplugin) - Another powerful AI assistant plugin integrated into KOReader with configurable model support. ⭐ 59+

---

## Book Discovery & Downloads

*Search and download books directly to your device.*

- [zlibrary.koplugin](https://github.com/ZlibraryKO/zlibrary.koplugin) - Z-Library client for KOReader. Search and download books directly to your device. ⭐ 320+
- [zlibrary.koplugin (OctoNezd)](https://github.com/OctoNezd/zlibrary.koplugin) - Alternative Z-Library client implementation for KOReader. ⭐ 193+
- [zotero.koplugin](https://github.com/stelzch/zotero.koplugin) - Browse your Zotero collection on your e-reader and download papers and books. ⭐ 130+
- [legado.koplugin](https://github.com/pengcw/legado.koplugin) - Web fiction reading plugin with Legado library support — browse and read from web sources. ⭐ 166+
- [rakuyomi](https://github.com/hanatsumi/rakuyomi) - Manga reader plugin for KOReader with source/repository support. ⭐ 221+

---

## Sync & File Transfer

*Keep your books, progress, and settings in sync across devices.*

- [koreader-syncthing](https://github.com/jasonchoimtt/koreader-syncthing) - Syncthing integration plugin for KOReader — sync files wirelessly without a cloud.
- [localsend.koplugin](https://github.com/kaikozlov/localsend.koplugin) - Send and receive files wirelessly on your e-reader using LocalSend protocol (no internet required). ⭐ 104+
- [highlightsync.koplugin](https://github.com/gitalexcampos/highlightsync.koplugin) - Sync highlights, notes, and bookmarks across multiple devices using cloud storage (WebDAV, Dropbox, etc.). ⭐ 159+
- [AnnotationSync.koplugin](https://github.com/dani84bs/AnnotationSync.koplugin) - Keep annotations in sync between devices with cloud-based storage. ⭐ 69+

---

## Highlights & Annotations

*Export, manage, and share your reading highlights and notes.*

- [KoHighlights](https://github.com/noembryo/KoHighlights) - Desktop app for managing and exporting KOReader highlights and annotations.
- [KoInsight](https://github.com/GeorgeSG/KoInsight) - Web-based dashboard for reading stats that also handles highlights sync and can act as a sync server. ⭐ 452+
- [koreader-calibre-plugin](https://github.com/harmtemolder/koreader-calibre-plugin) - Sync KOReader sidecar metadata (progress, ratings, reviews, annotations) to Calibre.
- [koreader2obsidian](https://github.com/Tetrax-10/koreader-obsidian-sync) - Export KOReader highlights directly to Obsidian notes.

---

## Dictionary & Language Learning

*Integrate vocabulary tools and spaced repetition systems.*

- [anki.koplugin](https://github.com/Ajatt-Tools/anki.koplugin) - Generate Anki flashcards from words looked up in KOReader's built-in dictionary. Works with AnkiConnect. ⭐ 179+

---

## RSS & Read-It-Later

*Bring web articles and feeds to your e-reader.*

- [miniflux.koplugin](https://github.com/AlgusDark/miniflux.koplugin) - Access a Miniflux RSS instance and read feed entries offline. ⭐ 63+
- [readeck.koplugin](https://github.com/iceyear/readeck.koplugin) - KOReader plugin for Readeck read-it-later servers. ⭐ 63+
- [opds_plus.koplugin](https://github.com/greywolf1499/opds_plus.koplugin) - Enhanced OPDS catalog browser for KOReader with visual cover display. ⭐ 57+

---

## Reading Services Integration

*Connect KOReader to external reading tracking and book management services.*

- [hardcover.koplugin](https://github.com/zionso/hardcover.koplugin) - Sync reading progress and status to [Hardcover.app](https://hardcover.app).
- [wallabag.koplugin](https://github.com/koreader/koreader/tree/master/plugins/wallabag.koplugin) - Built-in Wallabag integration — fetch and read saved articles offline (ships with KOReader).
- [beeminder.koplugin](https://github.com/koreader/koreader/tree/master/plugins/beeminder.koplugin) - Built-in Beeminder integration for reading goal tracking (ships with KOReader).
- [kobo.koplugin](https://github.com/OGKevin/kobo.koplugin) - Enhances the Kobo reading experience with additional features and integrations. ⭐ 79+

---

## Comics & Manga

*Better comic, manga, and graphic novel reading experiences.*

- [rakuyomi](https://github.com/hanatsumi/rakuyomi) - Full-featured manga reader plugin with source support and chapter management. ⭐ 221+
- [comicreader.koplugin](https://github.com/KORComic/comicreader.koplugin) - Enhanced comic reading experience with dual-page support, metadata extraction, and navigation improvements. ⭐ 60+

---

## UI & Customization

*Redesign menus, customize the interface, and create a more personal reading environment.*

- [ProjectTitle](https://github.com/joshuacant/ProjectTitle) - Feature-rich homescreen/library UI plugin that transforms the Cover Browser into a beautiful, customizable interface. Supports user patches for endless personalization. ⭐ High
- [Koreader-Menu-customizer](https://github.com/JoeBumm/Koreader-Menu-customizer) - Hide menus and plugins to simplify the KOReader UI and focus on reading. ⭐ 70+
- [webbrowser.koplugin](https://github.com/omer-faruq/webbrowser.koplugin) - Text-based web browser plugin for KOReader — browse the web from your e-reader. ⭐ 58+

---

## Reading Tracking & Goals

*Track your reading habits, set goals, and review your statistics.*

- [KoInsight](https://github.com/GeorgeSG/KoInsight) - Web-based dashboard with charts and insights from your KOReader reading statistics. Self-hostable with Docker. ⭐ 452+
- [koreader-stats-exporter](https://github.com/bbb651/koreader-stats-exporter) - Export KOReader reading statistics to various formats for external analysis.

---

## Utilities & Tools

*Miscellaneous plugins that add useful functionality.*

- [webbrowser.koplugin](https://github.com/omer-faruq/webbrowser.koplugin) - Text-based web browser inside KOReader. ⭐ 58+
- [localsend.koplugin](https://github.com/kaikozlov/localsend.koplugin) - Wireless local file transfer. ⭐ 104+

---

## Games & Entertainment

*Because sometimes you just need a break.*

- [koreader/contrib: sudoku](https://github.com/koreader/contrib) - Sudoku game available in the official contrib collection.
- [koreader/contrib: crosswords](https://github.com/koreader/contrib) - Crossword puzzle game in the contrib collection.
- [koreader/contrib: word-search](https://github.com/koreader/contrib) - Word search puzzle in the contrib collection.

---

## Device-Specific

*Plugins and tools tailored to specific e-reader hardware.*

### Kobo

- [kobo.koplugin](https://github.com/OGKevin/kobo.koplugin) - Enhances Kobo-specific features within KOReader. ⭐ 79+
- [KoboUSBMS](https://github.com/koreader/KoboUSBMS) - Standalone USB Mass Storage mode toggle for Kobo devices.

### PocketBook

- [pocketbook-covers](https://github.com/koreader/contrib) - Cover sync and progress tracking patches for PocketBook devices (see contrib).

### Kindle

- [ProjectTitle](https://github.com/joshuacant/ProjectTitle) - Added Kindle support in v2025.04+.

### reMarkable

- [KOReader on reMarkable](https://github.com/koreader/koreader/wiki/Installation-on-Remarkable) - Installation guide and device-specific notes on the wiki.

---

## User Patches

*Lua patches placed in `koreader/patches/` that modify KOReader behavior without touching the source. File names must begin with a number (e.g., `2-my-patch.lua`).*

> **How to install:** Download `.lua` patch files and place them in your `koreader/patches/` folder. The leading number determines execution order.

### Patch Collections

- [SeriousHornet/KOReader.patches](https://github.com/SeriousHornet/KOReader.patches) - Visual overhaul suite: rounded covers, progress badges, custom widgets, status icons for Cover Browser and Project: Title.
- [sebdelsol/KOReader.patches](https://github.com/sebdelsol/KOReader.patches) - Well-tested collection that includes a self-updating patch mechanism. Requires KOReader v2025.04+.
- [joshuacant/KOReader.patches](https://github.com/joshuacant/KOReader.patches) - Assorted patches covering overlays, progress bars, font customization, and Project: Title enhancements.
- [loeffner/KOReader.patches](https://github.com/loeffner/KOReader.patches) - Patches for the default Cover Browser and Project: Title, including the Weather Lockscreen (now its own plugin).
- [jmanteau/KOReader.patches](https://github.com/jmanteau/KOReader.patches) - Consolidates 13+ community patches into 3 unified Lua scripts for Cover Browser mosaic view.
- [advokatb/KOReader-Patches](https://github.com/advokatb/KOReader-Patches) - Compatible with KOReader 2025.10 "Ghost" and Project: Title v3.5.
- [omer-faruq/koreader-user-patches](https://github.com/omer-faruq/koreader-user-patches) - Various user patches from the creator of appstore.koplugin.

### Official Example Patches

These are documented on the [User Patches Wiki](https://github.com/koreader/koreader/wiki/User-patches):

| Patch file | Description |
|---|---|
| `2-touchmenu-update-clock.lua` | Update clock and battery in the touch menu every minute |
| `2-dict-auto-copy-current-definition.lua` | Auto-copy/share dictionary definitions |

---

## Self-Hosted Sync Servers

*Run your own KOReader sync backend for progress synchronization and reading stats.*

- [koreader-sync-server](https://github.com/koreader/koreader-sync-server) - The official self-hostable sync server. Docker support included.
- [KoInsight](https://github.com/GeorgeSG/KoInsight) - Full-featured reading stats dashboard that also acts as a KOReader (kosync-compatible) sync server. Docker image available. ⭐ 452+
- [koreader-sync (b1n4ryj4n)](https://github.com/b1n4ryj4n/koreader-sync) - Simple sync server implementation with Docker support for arm and amd64.
- [kosync-dotnet](https://github.com/jberlyn/kosync-dotnet) - Self-hostable KOReader sync server written in .NET — extends official server functionality.
- [kosynco](https://github.com/koreader/koreader-sync-server) - Lightweight sync server variant (see community forks).
- [Calibre-Web](https://github.com/janeczku/calibre-web) - Popular Calibre web interface that includes a KOReader-compatible OPDS server and sync endpoint.

---

## Desktop Companions & Tools

*Applications that run on your PC/Mac to complement your KOReader experience.*

- [KoInsight](https://github.com/GeorgeSG/KoInsight) - Web dashboard for reading stats visualization, highlights management, and sync server. ⭐ 452+
- [KoHighlights](https://github.com/noembryo/KoHighlights) - Desktop GUI for browsing, filtering, and exporting highlights and notes from KOReader sidecar files.
- [koreader-calibre-plugin](https://github.com/harmtemolder/koreader-calibre-plugin) - Calibre plugin to sync reading progress, ratings, and annotations from KOReader `.sdr` metadata folders.

---

## Calibre Integration

*Use Calibre as your library management hub alongside KOReader.*

- [koreader-calibre-plugin](https://github.com/harmtemolder/koreader-calibre-plugin) - Syncs KOReader metadata (last read position, reading progress %, star rating, review, bookmarks) back into Calibre's database.
- [Calibre-Web](https://github.com/janeczku/calibre-web) - Self-hosted web UI for your Calibre library with OPDS server — browse and download books directly from KOReader.
- [Calibre OPDS](https://manual.calibre-ebook.com/server.html) - Calibre's built-in content server exposes an OPDS feed readable by KOReader.

---

## Themes & Icons

*Customize the visual appearance of KOReader.*

- [Project: Title themes](https://github.com/joshuacant/ProjectTitle) - Project: Title supports icon packs and theming through user patches.
- [readerbackdrop](https://www.readerbackdrop.com) - A collection of screensavers for KOReader devices.
- [SeriousHornet icon patches](https://github.com/SeriousHornet/KOReader.patches) - Custom status icons and rounded cover patches for a polished look.
- [WeatherLockscreen](https://github.com/loeffner/WeatherLockscreen) - Plugin that shows weather information on your device's sleep/lock screen.

---

## Scripts & Automation

*Shell scripts, Python utilities, and automation tools for KOReader workflows.*

- [koreader-calibre-plugin](https://github.com/harmtemolder/koreader-calibre-plugin) - Automates syncing of reading data from device to Calibre on connect.
- [sebdelsol/KOReader.patches: 2-update-patches.lua](https://github.com/sebdelsol/KOReader.patches) - A meta-patch that auto-updates other patches from GitHub — run patch updates from within KOReader.

---

## Guides & Tutorials

*Learn how to get the most out of KOReader, write plugins, and manage your e-reader.*

### Installation & Setup

- [Official Installation Guides](https://github.com/koreader/koreader/wiki) - Device-specific installation instructions for Kindle, Kobo, PocketBook, Android, reMarkable.
- [User Patches Documentation](https://github.com/koreader/koreader/wiki/User-patches) - How the patch system works, naming conventions, and execution order.
- [OPDS Setup Guide](https://github.com/koreader/koreader/wiki/OPDS-catalog) - Setting up OPDS catalog access from KOReader.

### Plugin & Patch Development

- [Plugin Development Wiki](https://github.com/koreader/koreader/wiki/Plugin-development-guide) - How to write your own KOReader plugin in Lua.
- [KOReader API Reference](https://koreader.rocks/doc/) - Internal Lua API documentation generated from source.
- [Project: Title Patch Guide](https://github.com/joshuacant/ProjectTitle) - How to create patches specifically for Project: Title.

### Guides by the Community

- [How to use User Patches](http://thedarnedestthing.com/koreader%20user%20patches) - Community blog post covering user patch basics and examples.
- [Export Highlights to Obsidian](https://github.com/koreader/koreader/wiki) - Workflow guides for exporting annotations to note-taking apps.
- [Self-hosting KOReader Sync](https://github.com/koreader/koreader-sync-server) - Set up your own sync server with Docker.

---

## Community

- [r/koreader](https://www.reddit.com/r/koreader/) - The KOReader subreddit — share tips, patches, and ask for help.
- [MobileRead Forums – KOReader](https://www.mobileread.com/forums/forumdisplay.php?f=276) - Long-running forum with deep historical knowledge of KOReader, patches, and device hacks.
- [GitHub Discussions](https://github.com/koreader/koreader/discussions) - Official GitHub discussions for feature requests, support, and community interaction.
- [KindleModShelf](https://kindlemodshelf.com) - Directory of Kindle-related tools and mods, including KOReader resources.
- [GitHub Topic: koreader-plugin](https://github.com/topics/koreader-plugin) - Browse all 100+ repositories tagged with `koreader-plugin` on GitHub.
- [GitHub Topic: koreader-user-patch](https://github.com/topics/koreader-user-patch) - Browse repositories tagged with `koreader-user-patch`.

---

## Contributing

Your contributions are what make this list awesome. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) guide for instructions on how to submit new entries, suggest new categories, or report outdated links.

If you know of a plugin, tool, patch, or resource that should be on this list — open a pull request!

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE) for details.
