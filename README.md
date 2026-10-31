# SigmaOS Diagnostics

This crate exports `DiagnosticsManager` and organizes source under a
`diagnostics` module, including crash and kernel-report modules. The repository
contains many versioned diagnostic modules; their presence does not establish
that a running kernel or host is being monitored. Check each data source and
collection path before relying on a diagnostic report.

## License

See [`LICENSE`](LICENSE) and [`Cargo.toml`](Cargo.toml).

