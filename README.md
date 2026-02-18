# SACVPN Documentation

## Overview

The official documentation site for SACVPN, built with MkDocs and the Material theme. This static site provides comprehensive VPN setup guides, configuration references, and troubleshooting resources. The documentation is deployed automatically to GitHub Pages for public access.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Generator | MkDocs |
| Theme | Material for MkDocs |
| Hosting | GitHub Pages |
| Markup | Markdown |
| CI/CD | GitHub Actions |

## Features

- **VPN Documentation** -- Complete reference for SACVPN services, protocols, and configurations
- **Setup Guides** -- Step-by-step installation and configuration walkthroughs for all supported platforms
- **Troubleshooting** -- Common issues, error codes, and resolution steps organized for quick reference
- **Search** -- Built-in full-text search powered by MkDocs Material
- **Responsive Layout** -- Clean, mobile-friendly documentation browsing experience
- **Automatic Deployment** -- Push-to-deploy workflow via GitHub Pages integration

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/kstephens0331/sacvpn-docs.git
cd sacvpn-docs

# Install MkDocs and the Material theme
pip install mkdocs mkdocs-material

# Start the local development server
mkdocs serve
```

The documentation site runs on `http://localhost:8000` by default.

### Deploying to GitHub Pages

```bash
mkdocs gh-deploy
```

## Project Structure

```
sacvpn-docs/
├── docs/                    # Markdown documentation source
│   ├── index.md             # Home page
│   ├── setup/               # Setup & installation guides
│   ├── configuration/       # Configuration references
│   └── troubleshooting/     # Troubleshooting articles
├── overrides/               # Theme customizations
├── mkdocs.yml               # MkDocs configuration
├── requirements.txt         # Python dependencies
└── README.md
```

## License

MIT License. See [LICENSE](LICENSE) for details.

---

**Built by StephensCode LLC**
