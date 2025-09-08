# PE Launcher

A (very early) Rust workspace for a fast Minecraft: Pocket Edition launcher. Currently just scaffold crates.

## Crates
- pe-launcher-frontend: Binary entrypoint (prints placeholder).
- pe-launcher-backend: Future core logic (downloading, launching, versions).
- pe-launcher-common: Shared types/utilities (planned).

## Quick Start
```
cargo build --workspace
cargo run -p pe-launcher-frontend
cargo test --workspace
```

## Roadmap (early thoughts)
- Version + asset manifest handling
- Install / cache management
- Launch process abstraction
- CLI subcommands (list, install, launch)
- Optional GUI later

## Contributing
PRs / issues welcome while architecture forms.

## License
MIT © Millesant
