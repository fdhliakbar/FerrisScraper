# FerrisScraper

FerrisScraper is a Rust-based web scraper that focuses on speed and efficiency.  
Built with an asynchronous runtime (`tokio`), HTTP client (`reqwest`), and HTML parser (`scraper`),  
FerrisScraper can be used to retrieve data from various websites and save it in JSON or CSV format.

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
