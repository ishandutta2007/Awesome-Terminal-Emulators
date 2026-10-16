# Awesome-Terminal-Emulators

# Awesome-Terminal-Emulators

# Top Terminal Emulators Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on GPU-Accelerated Rendering, Cross-Platform Workflows & Modern Terminal Features*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Terminal Emulators**. These tools provide the command-line environment where developers, sysadmins, and power users spend their day — rendering text, handling input, and supporting modern features like GPU acceleration, ligatures, images, and multiplexing without external tools.

**Examples** include ConEmu, Cmder, Windows Terminal, Alacritty, Kitty, iTerm2, Warp, WezTerm, Hyper, and Terminus (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, cross-platform consistency, and transparent development — ideal for developers prioritizing performance, customization, and freedom from vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Warp](https://www.warp.dev/)**  
  AI-native terminal and agentic development environment with cloud agents, codebase indexing, and MCP client support. **Free tier** includes core terminal features plus bring-your-own AI inference. **Build plan at $18/month** (annual) and **Max at $180/month**. **Business tier at $45/user/month** adds team collaboration and Zero Data Retention by default. 64,800+ GitHub stars after open-sourcing in 2025. macOS-first; Windows lags on stability and feature parity.

- **[iTerm2](https://iterm2.com/)**  
  macOS-only terminal emulator with native split panes, search, autocomplete, and extensive customization. Free and open-source (GPL). The default choice for Mac power users.

- **[SecureCRT](https://www.vandyke.com/)**  
  Commercial terminal emulator for Windows, macOS, and Linux with SSH, Telnet, serial, and rlogin protocols. Advanced session management, scripting, and secure file transfer.

- **[Termius](https://termius.com/)**  
  Cross-platform SSH client with sync across devices, SFTP, port forwarding, and team collaboration features. Free tier available; paid plans for advanced features.

## Open-Source GitHub Projects

- **[WezTerm](https://github.com/wez/wezterm)**  
  **The most feature-complete modern terminal emulator** — GPU-accelerated, cross-platform, written in Rust. Runs on **Linux, macOS, Windows 10+, FreeBSD, and NetBSD**. **Built-in multiplexer** means you don't need tmux for tabs, panes, or workspaces. **Lua-based configuration** with hot reloading, so changes apply immediately without restart. Supports **ligatures, color emoji, font fallback, true color (24-bit)**, and multiple graphics protocols including **iTerm2 images, Kitty graphics, and Sixel**. MIT licensed.

- **[Kitty](https://github.com/kovidgoyal/kitty)**  
  **Cross-platform, fast, feature-full, GPU-based terminal emulator** — offloads rendering to the GPU for lower system load and buttery smooth scrolling. **Supports tiling multiple terminal windows side by side** in different layouts without needing tmux. **Framework for "Kittens"** — small terminal programs that extend functionality (Unicode input, Hints, side-by-side diff). **Startup sessions** let you specify window/tab layout, working directories, and programs to run on startup. Works on Linux and macOS; only OpenGL for rendering, making it portable to other Unix-like platforms. GPL licensed.

- **[Hyper](https://github.com/vercel/hyper)**  
  **Modern terminal built on web technologies** — HTML, CSS, and JavaScript on top of Electron. **Plugin ecosystem based on Node.js packages** that can extend practically every part of the interface and behavior. **Fast split-pane workflows** with configurable hotkeys. **Fully tweakable front end and back end** — anyone comfortable with web technologies can create or modify plugins. Best for developers who enjoy web technologies and want a terminal they can shape to their workflow. **Default feature set is intentionally minimal** — power comes from extensibility.

- **[Tabby](https://github.com/Eugeny/tabby)**  
  **"A terminal for a more modern age"** — the most feature-rich cross-platform terminal with integrated SSH and serial clients. **Integrated SSH client with connection manager**, SFTP and Zmodem file transfers, X11 and port forwarding, jump hosts, and agent forwarding. **Integrated serial terminal** with multiple connection profiles, hexdump output, and automatic reconnection. **Remembers open tabs and split panes** where you left off. **Full Unicode support** including double-width characters. **Themes customizable with CSS**, plugin system in JavaScript, and **portable mode** on Windows. 69,000+ GitHub stars. Best for sysadmins and developers who want one tool for local shells, remote servers, and serial connections.

- **[Extraterm](https://github.com/sedwards2009/extraterm)**  
  **"The swiss army chainsaw of terminal emulators"** — open source terminal with modern workflow features beyond a glorified teletype. **Shell integration** can isolate and "frame" command output (bash, zsh, fish supported), making previous command output usable as input for new commands. **Built-in SSH client, images in terminal, mini-map, command palette, output colorizing, and multiple windows/tiling**. Supports **iTerm2 themes**, color emoji, font ligatures, and Unicode. **MIT licensed**. Modern Qt-based version (0.60.0+) available alongside classic Electron version.

- **[Windows Terminal](https://github.com/microsoft/terminal)**  
  **Microsoft's modern terminal for Windows** — the default replacement for the legacy console host. GPU-accelerated rendering, tabs, panes, and full Unicode/emoji support. **Highly customizable** with JSON configuration, color schemes, and profiles for PowerShell, WSL, CMD, and Git Bash. **Open-source under MIT license**. Actively developed by Microsoft.

### Additional Strong Open-Source Options

- **Alacritty** — GPU-accelerated terminal emulator focused on simplicity and performance. No tabs or splits by design — designed to integrate with tmux. Rust-based, Apache 2.0 licensed.
- **Cmder** — Portable console emulator for Windows built on ConEmu. Bundles Git for Windows, Clink, and a custom prompt. **ConEmu** is the underlying engine with tabs, splits, and extensive customization.
- **Terminus** — Cross-platform terminal with tabs, splits, themes, and plugin support. Electron-based.
- **GNOME Terminal** — Default terminal for GNOME desktop with tabs, profiles, and transparency. VTE-based.
- **Konsole** — KDE's terminal emulator with tabs, splits, bookmarks, and SSH management.
- **Rio** — Rust-based GPU-accelerated terminal focused on speed and simplicity.

**Frameworks for building custom systems**: Combine **WezTerm** for full-featured cross-platform with built-in multiplexing and Lua config, **Kitty** for GPU rendering with Kittens extensibility, **Tabby** for integrated SSH/serial with session persistence, **Hyper** for web-technology extensibility, and **Windows Terminal** for native Windows integration — to build a complete terminal environment tailored to your workflow.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Terminal emulators differ significantly in rendering approach (GPU vs CPU), platform support, and feature scope. **Electron-based terminals like Hyper and Tabby consume significantly more resources than native alternatives** like Alacritty or Kitty. **Warp's AI features and cloud agents require account sign-in** and Business tier pricing scales steeply for teams. GPU acceleration requires compatible drivers and may not work in all environments.
- Self-hosted open-source solutions require proper configuration backup strategies and understanding of shell integration where applicable.

---

**Made for developers, system administrators, and anyone who works in the terminal.**  
Let's make terminal emulation more open, performant, and modern.
