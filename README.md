# ProcessKit — documentation site

Source for the **[ProcessKit documentation site](https://zelanton.github.io/ProcessKit/)** — an umbrella guide for the ProcessKit family of async child-process management libraries.

Currently covering:

- **Rust** — [processkit](https://crates.io/crates/processkit) ([source](https://github.com/ZelAnton/ProcessKit-rs))

Future sections will cover Go, F#, Kotlin, and a Python wrapper as those implementations are built.

## Build locally

```sh
cargo install mdbook          # once
mdbook serve                  # live-reload at http://localhost:3000
```

## Contributing

Edit the Markdown sources under `docs/` and open a pull request. The site is rebuilt and deployed automatically on every push to `main` via GitHub Actions.
