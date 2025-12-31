# Goove

**Self-hosted vinyl collection management for music lovers**

Goove is an open-source application that helps you catalog, organize, and enjoy your vinyl record collection. Built for self-hosting on your homelab, it's designed to be lightweight, fast, and easy to deploy.

## Features

- 📀 Track your vinyl records with detailed metadata
- 🎨 Beautiful cover art display
- 🔍 Search and filter your collection
- 📊 Collection statistics and insights
- 🏷️ Discogs integration for automatic data lookup
- 🐳 Docker-ready for easy deployment
- 💾 SQLite-based for simple backups

## Quick Start

```bash
docker run -d \
  -p 8080:8080 \
  -v goove-data:/data \
  ghcr.io/gooveapp/goove:latest
```

Visit `http://localhost:8080` and start building your collection.

## Repositories

- **[goove](https://github.com/gooveapp/goove)** - Main application (Go + HTMX + Templ)

## Tech Stack

- **Backend:** Go
- **Frontend:** HTMX + Templ
- **Database:** SQLite
- **Deployment:** Docker

## Contributing

We welcome contributions! Whether it's bug reports, feature requests, or code contributions, check out our main repository to get started.

## License

MIT License - see individual repositories for details.

---

Built with ❤️ for vinyl collectors
