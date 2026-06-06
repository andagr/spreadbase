# Spreadbase

## Prerequisites
Before running the application, ensure your system has the following core tools installed:

1. **Rust & Cargo**: https://rustup.rs/
2. **pnpm**: https://pnpm.io/installation
3. **Tauri prerequisites**: https://tauri.app/start/prerequisites/
## Development
Follow these steps to install dependencies and start the desktop development environment:
```bash
# 1. Install frontend packages via pnpm
pnpm install

# 2. Start the desktop development window
pnpm tauri dev
```

## Build & Publish
To compile the application into an installation package for your current operating system:

```bash
pnpm tauri build
```