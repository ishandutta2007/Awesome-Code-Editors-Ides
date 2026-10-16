# Awesome-Code-Editors-Ides

## Top Code Editors & IDEs Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Extensible Editors, Language Server Protocol & AI-Native Development*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Code Editors & IDEs**. These tools enable developers to write, navigate, and debug code—from lightweight extensible editors that load in milliseconds to full-featured IDEs with deep language intelligence and integrated toolchains.



**Examples** include JetBrains IntelliJ IDEA, Visual Studio Code, Eclipse, NetBeans, Visual Studio, CLion, PyCharm, WebStorm, Sublime Text, and Xcode (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, extensible editors, and open IDE platforms—ideal for developers, platform teams, and organizations seeking transparent, vendor-independent development environments.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Integrated Development Environment (IDE) and code editor market is valued between $4B and $6B, expanding at a CAGR of ~10–14% fueled by AI developer tool adoption and cloud-based development environments. The sector is moderately fragmented across specialized language niches and open-source communities, but heavily concentrated at the top tier where tech giants (Microsoft and Apple) and category incumbents (JetBrains) capture the majority of global developer usage and enterprise market share.

## SaaS/Hosted Platforms

| Platform | Company / Valuation / Revenue | Starting Pricing | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple Xcode](https://developer.apple.com/xcode/)** | Apple Inc. (~$3.5T Market Cap / ~$390B Rev) | $99/year (Apple Developer Program to distribute on App Store) | Free forever (free download for macOS; limited to local device testing & simulator debugging without App Store distribution) | Apple's official IDE for macOS, iOS, iPadOS, watchOS, and visionOS development with SwiftUI live previews, Instruments profiling, and SDK simulator integration. |
| **[Microsoft Visual Studio](https://visualstudio.microsoft.com/)** | Microsoft (~$3.1T Market Cap / ~$245B Rev) | $45/user/month (Cloud subscription) or $499 (Perpetual license) | Free forever (Community edition: free for individuals, unlimited open-source contributors, and non-enterprise organizations with <250 PCs or <$1M annual revenue up to 5 users) | Microsoft's full-featured IDE for .NET, C++, C#, and Windows development with IntelliSense, remote debugging, profiling tools, and Azure DevOps integration. |
| **[JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/)** | JetBrains (Private; ~$700M+ Annual Rev) | $19.90/user/month or $199/year (Individual Ultimate); $71.90/user/month (Org) | 30-day free trial (fully functional Ultimate trial; free forever Community edition limited to standard Java/Kotlin/Groovy without enterprise frameworks, profilers, or database tooling) | Premier JVM IDE featuring deep code intelligence, automated refactoring, JVM profilers, HTTP client, and spring/enterprise framework support. |
| **[JetBrains PyCharm](https://www.jetbrains.com/pycharm/)** | JetBrains (Private; ~$700M+ Annual Rev) | $10.90/user/month or $109/year (Individual Professional); $27.90/user/month (Org) | 30-day free trial (fully functional Pro trial; free forever Community edition limited to pure Python development without web frameworks, remote interpreters, or SQL tooling) | Full-featured Python IDE supporting Django, Flask, FastAPI, remote Docker/SSH interpreters, and integrated Jupyter notebooks. |
| **[JetBrains WebStorm](https://www.jetbrains.com/webstorm/)** | JetBrains (Private; ~$700M+ Annual Rev) | $7.90/user/month or $69/year (Individual Commercial); $15.90/user/month (Org) | Free forever for non-commercial use (learning, open-source, hobby projects); 30-day fully functional free trial for commercial evaluation | Complete JavaScript and TypeScript IDE with built-in framework support (React, Vue, Angular, Node.js), integrated debugger, and test runners. |
| **[Sublime Text](https://www.sublimetext.com/)** | Sublime HQ (Private / Bootstrapped; ~2–10 employees) | $99 one-time purchase (includes 3 years of updates) | Indefinite free evaluation trial (fully functional without hard time expiry, but displays periodic purchase reminder prompts and restricts dev builds) | High-performance, lightweight code editor known for instantaneous startup, multi-cursor editing, command palette, and smooth custom UI rendering. |

## Open-Source GitHub Projects



- **[Visual Studio Code (Code - OSS)](https://github.com/microsoft/vscode)**  

  **Extensible lightweight code editor** (MIT for Code - OSS) . **The most widely adopted code editor**—**the upstream open-source project** that Microsoft builds VS Code from . **Features**: **IntelliSense**, **built-in Git**, **debugging**, **extension marketplace**, and **integrated terminal** . **Note**: The Microsoft-branded VS Code download includes **telemetry and proprietary license**—**Code - OSS is the pure open-source build** . **The reference implementation for extensible editors** .



- **[VSCodium](https://github.com/VSCodium/vscodium)**  

  **VS Code with the telemetry stripped out** (MIT) . **The most popular open-source VS Code distribution**—**strips telemetry, branding, and proprietary license from the VS Code repo** . **The user experience is almost identical**—editing is the same, but VSCodium trades Microsoft's marketplace for the **Open VSX marketplace** . **The downside**: Some extensions are Microsoft-exclusive (Pylance, Copilot, Remote SSH) and not available on Open VSX . **You can point VSCodium at the Microsoft marketplace, but it's a terms of service violation** . **Available as executable, Flatpak, APT, DNF, and more** . **The best choice for developers who want VS Code's experience without telemetry** .



- **[Eclipse IDE](https://github.com/eclipse-platform)**  

  **The original open-source IDE platform** (EPL-2.0) . **The most modular and extensible IDE**—**supports Java, C++, Python, PHP, and more through plugins** . Features **autocompletion**, **debugging**, **profiling**, and **customizable interface** . **The standard for enterprise Java development** for decades . **Still actively maintained** with regular releases .



- **[NetBeans](https://github.com/apache/netbeans)**  

  **Free and open-source IDE** (Apache-2.0) . **The most Java-focused open-source IDE**—**particularly powerful for Java development** while supporting PHP, C++, HTML5, and JavaScript . Features **autocompletion**, **debugging**, **profiling**, and **Maven/Gradle integration** . **The reference implementation for Java IDE functionality** .



- **[Eclipse Theia](https://github.com/eclipse-theia/theia)**  

  **Open-source cloud & desktop IDE** (EPL-2.0) . **The most modular open-source IDE platform**—**not a VS Code fork**, but shares components like the **Monaco editor** . **Built on TypeScript and Node.js** for cloud and desktop. **Features**: **Language Server Protocol (LSP)**, **Debug Adapter Protocol (DAP)**, **Open VSX extension registry (3,600+ extensions)**, **real-time collaboration**, **Theia AI framework** connecting to OpenAI, Anthropic, Google, Ollama, Hugging Face, or local models . **By default, no telemetry is collected** . **Used by Google Cloud Shell, Arduino IDE 2.x, and others** . **The best choice for building custom cloud IDEs** .



- **[Zed](https://github.com/zed-industries/zed)**  

  **High-performance code editor built for speed and AI** (GPL-3.0) . **91,000+ GitHub stars** . **The fastest code editor**—**built in Rust with GPU-accelerated rendering** . Features **AI-assisted coding**, **collaborative editing**, **multi-cursor editing**, and **native performance** . **The modern alternative to VS Code** for developers who prioritize speed . **The reference implementation for performance-first editors** .



- **[Void](https://github.com/voideditor/void)**  

  **Open-source alternative to Cursor** (Apache-2.0) . **The most popular open-source AI editor**—**fork of VS Code** designed to bring **inline edits, chat, and agent mode** without a subscription . **Connect to any AI model**—**Ollama or any OpenAI-compatible endpoint** . **Your code stays local**—no third-party services required . **Note**: Project hasn't been updated recently, but modern forks continue development . **The best choice for developers who want Cursor-like AI features without vendor lock-in** .



- **[CodeEdit](https://github.com/CodeEditApp/CodeEdit)**  

  **Free, open-source code editor for macOS** (MIT) . **The most macOS-native open-source editor**—**built in Swift** following Apple's design guidelines . Features **syntax highlighting**, **autocomplete**, **Git integration**, **built-in terminal**, **snippets**, **project search/replace**, and **extension support** . **Designed to complement Xcode** for projects outside the Apple ecosystem . **The best choice for macOS developers who want a native experience** .



- **[Lithe-IDEA](https://github.com/xxx/lithe-idea)**  

  **Lightweight Java IDE built from scratch** (open-source) . **The most interesting Java IDE project of 2026**—**built by a solo developer with SwiftUI + AppKit (macOS), React + Tauri 2 (Windows), and Rust for shared engine** . **The philosophy**: **"按需启动，用完即走"** (start on demand, leave when done)—**only opens the editor by default, starts LSP when you need code completion** . **Memory footprint: 300-400MB** vs. IntelliJ's 4-6GB . **Key features**: **double-Shift global search** (IDEA-compatible), **Spring Boot direct run/debug**, **Git Diff review for AI changes**, and **built-in database tools** . **The reference implementation for lightweight Java development** .



- **[Consulo](https://github.com/consulo/consulo)**  

  **Multi-language IDE** (Apache-2.0) . **The open-source fork of IntelliJ IDEA Community Edition**—started in 2013 with a **different goal**: **"create an open IDE where you don't need to select an IDE for different languages"** . **Each language is supported by a corresponding Consulo plugin** . **The most interesting IntelliJ-derived open-source project**—**attempts to be a universal IDE with a standard for language implementation** .



- **[Kate](https://github.com/KDE/kate)**  

  **Advanced text editor from KDE** (LGPL-2.0) . **The most feature-complete KDE-native editor**—**part of the KDE Project** with **integrated Konsole terminal**, **LSP support**, **project management**, and **plugin ecosystem** . **Fully open source**—**no proprietary components** . **Consumes about half the resources of VS Code** . **The best choice for KDE Plasma users** who want a cohesive desktop experience .



- **[GNOME Builder](https://github.com/GNOME/gnome-builder)**  

  **Tool to write and contribute to great GNOME-based applications** (GPL-3.0) . **The standard IDE for GNOME development**—**deep integration with GNOME stack**, **Flatpak support**, and **GNOME-native experience** .



### Additional Strong Open-Source Options



- **[Geany](https://github.com/geany/geany)** — Fast and lightweight IDE (GPL-2.0) . **The most lightweight full IDE**—supports many languages with minimal resource usage .

- **[Code::Blocks](https://github.com/obfuscated/codeblocks_sfmirror)** — Open-source, cross-platform IDE (GPL-3.0) . **The standard for C/C++ beginners**—lightweight and simple .

- **[Lite XL](https://github.com/lite-xl/lite-xl)** — Lightweight text editor written in Lua (MIT) . **The simplest extensible editor**—lua-based plugins, minimal footprint .

- **[Micro](https://github.com/zyedidia/micro)** — Modern and intuitive terminal-based text editor (MIT) . **The most intuitive terminal editor**—familiar keybindings, mouse support .

- **[Helix](https://github.com/helix-editor/helix)** — Post-modern modal text editor (MPL-2.0) . **The modern Vim alternative**—built-in LSP, tree-sitter, and multiple selections .

- **[Neovim](https://github.com/neovim/neovim)** — Vim-fork focused on extensibility and usability (Apache-2.0) . **The most extensible terminal editor**—Lua configuration, LSP support, and massive plugin ecosystem .

- **[NvChad](https://github.com/NvChad/NvChad)** — Neovim configuration framework (GPL-3.0) . **The most popular Neovim distribution**—IDE-like features out of the box .

- Community **n8n** workflows for editor configuration sync and development environment automation.



**Frameworks for building custom systems**: Combine **VSCodium** for telemetry-free VS Code experience with **Eclipse Theia** for custom cloud IDE building, **Zed** for performance-first editing, **CodeEdit** for macOS-native development, and **Void** for AI-assisted coding without vendor lock-in—creating a comprehensive open-source development environment stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Code editors and IDEs handling source code must follow security best practices, especially when connecting to AI services or remote development environments.

- **Open-source code editors are mature and production-ready.** VS Code (Code - OSS) is the most widely adopted editor . VSCodium provides telemetry-free VS Code . Zed (91K+ stars) offers GPU-accelerated performance . Theia enables custom cloud IDEs . **These are genuine alternatives to commercial platforms.**

- **The VS Code distinction matters: Code - OSS is open source, VS Code is proprietary.** The Microsoft-branded download includes **telemetry and a proprietary license**—**VSCodium strips these out** . **Extensions like Pylance, Copilot, and Remote SSH are Microsoft-exclusive and not available on Open VSX** . **Choose based on whether you need those extensions or want full open-source purity** .

- **IntelliJ IDEA's memory footprint is a real pain point.** Lithe-IDEA exists because **IntelliJ consumes 4-6GB for a Spring Boot project** while Lithe uses **300-400MB** . **The "lightweight IDE" category is emerging**—Zed, Lite XL, and Lithe all prioritize resource efficiency over feature completeness .

- **AI-native editors are the new category.** Void (open-source Cursor alternative), PearAI, and Theia AI all integrate AI assistants directly into the editor . **The choice is whether to use a commercial AI editor with vendor lock-in or an open-source alternative with local model support** .

- Self-hosted open-source solutions require proper configuration, plugin management, and ongoing maintenance. **Development environments are deeply personal**—invest time in your setup and it pays dividends for years.



---



**Made for developers, platform teams, and organizations building transparent development environment solutions.**  

Let's make Code Editors & IDEs more open, data-driven, and AI-native.
