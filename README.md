# Y-SysBooster

**A lightweight, open-source system optimization and diagnostics toolkit for Linux and Windows, built with Rust.**

Y-SysBooster aims to help users understand, maintain, and optimize their computers through a unified desktop application focused on performance, transparency, and safety.

Rather than applying aggressive or unnecessary tweaks, Y-SysBooster is designed to provide useful system insights and let users stay in control of every maintenance operation.

## ✨ Planned Features

- **System Monitoring** — Monitor CPU usage, memory consumption, disk space, and other available system metrics.
- **Process Manager** — Inspect running processes, identify resource-intensive applications, and let users close selected processes.
- **Storage Analyzer** — Discover large files and directories to understand disk space usage.
- **Safe Cleanup** — Review temporary files and potential cleanup candidates before confirming deletion.
- **Disk Health Diagnostics** — Read supported drive health information, including SMART data when available.
- **System Diagnostics** — Run basic checks and generate useful local diagnostic reports.
- **Cross-Platform Support** — Designed for Linux and Windows.
- **Privacy First** — Local system analysis without mandatory telemetry or automatic report uploads.

## 🛠️ Technology

- **Language:** Rust
- **Desktop UI:** egui / eframe
- **System Information:** sysinfo and platform-specific APIs where needed
- **Testing:** Cargo test
- **Code Quality:** Clippy and rustfmt
- **Build System:** Cargo

## 🔒 Safety Principles

Y-SysBooster is designed around user control and predictable behavior.

- No automatic deletion of personal files.
- No indiscriminate termination of background processes.
- No forced memory clearing marketed as a guaranteed performance improvement.
- No unnecessary administrator privileges for basic monitoring.
- Explicit confirmation before destructive operations.
- Clear reporting when hardware or operating system information is unavailable.

Performance recommendations should be based on actual measurements rather than misleading optimization claims.

## 🚧 Project Status

**Early Development — Pre-Release**

Y-SysBooster is currently in the planning and initial implementation stage. Features listed above describe the project roadmap and may not yet be implemented.

The initial development milestones are:

1. Establish the Rust project and cross-platform architecture.
2. Implement system monitoring and the desktop interface.
3. Add process inspection and safe process management.
4. Build storage analysis and user-controlled cleanup.
5. Introduce drive health diagnostics and system reports.
6. Test, package, and document releases for Linux and Windows.

The project will prioritize correctness, safety, and maintainability over unnecessary features.

## 💻 Building from Source

You will need a supported Rust toolchain and Cargo.

Once the initial Rust application and its dependencies have been implemented, the project will be built using:

```bash
cargo build --release
```

Run automated tests with:

```bash
cargo test
```

Check code quality with:

```bash
cargo clippy --all-targets --all-features -- -D warnings
```

Format the code with:

```bash
cargo fmt
```

Platform-specific development dependencies may be required depending on the desktop UI backend and target operating system.

## 🤝 Contributing

Contributions, bug reports, feature suggestions, and documentation improvements are welcome.

Please open an issue before starting major changes so that the proposed work can be discussed and coordinated.

All contributions should follow the project's safety, privacy, and cross-platform compatibility principles.

## 🗺️ Roadmap

- [ ] Rust project foundation
- [ ] Initial desktop interface
- [ ] CPU and memory monitoring
- [ ] Disk usage monitoring
- [ ] Linux and Windows compatibility testing
- [ ] Process manager
- [ ] Storage analyzer
- [ ] Safe cleanup
- [ ] Disk health diagnostics
- [ ] Release packaging and documentation

## 📜 License

The project is intended to be open source. The repository license will specify the permissions and conditions for using, modifying, and distributing the software.

## 🎯 Vision

Make computer maintenance more transparent, accessible, and reliable by giving users practical tools to understand their systems and make informed decisions.

**Y-SysBooster — Optimize. Diagnose. Take Control.**
