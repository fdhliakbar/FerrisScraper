# FerrisScraper

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rust-lang/www.rust-lang.org/master/static/images/rust-social-wide-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rust-lang/www.rust-lang.org/master/static/images/rust-social-wide-light.svg">
    <img alt="The Rust Programming Language: A language empowering everyone to build reliable and efficient software"
         src="https://raw.githubusercontent.com/rust-lang/www.rust-lang.org/master/static/images/rust-social-wide-light.svg"
         width="50%">
  </picture>
</div>

FerrisScraper is a Rust-based web scraper that focuses on speed and efficiency. Built with an asynchronous runtime (`tokio`), HTTP client (`reqwest`), and HTML parser (`scraper`), FerrisScraper can be used to retrieve data from various websites and save it in JSON or CSV format.

## Why Rust?

- **Performance:** Fast and memory-efficient, suitable for critical services, embedded devices, and easily integrated with other languages.

- **Reliability:** Our rich type system and ownership model ensure memory and thread safety, reducing bugs at compile-time.

- **Productivity:** Comprehensive documentation, a compiler committed to providing great diagnostics, and advanced tooling including package manager and build tool `Cargo`, auto-formatter `rustfmt`, linter `Clippy` and editor support `rust-analyzer`.

---

## Features
- Asynchronous HTTP requests (using `tokio`)
- Simple HTML parsing (`scraper` crate)
- Output to JSON or CSV
- Command-line interface (CLI)
- Open contribution

---

## Installation

Clone repository:
```bash
git clone https://github.com/username/FerrisScraper.git
cd FerrisScraper
```

Build Project
```bash
cargo build --release
```
Run the Program
```bash
cargo run -- example -o data.json
```

Usage

Scrape 1 URL:
```
cargo run -- https://example.com -o result.json
```

Scrape multiple URLs:
```
cargo run -- https://example.com https://example.org -o result.csv
```

## Contribution

FerrisScraper is an open contribution project.
Please fork, create a new branch, and then submit a pull request.

```bash
git checkout -b feature-nama-fitur
git commit -m "Menambahkan fitur X"
git push origin feature-nama-fitur
```
