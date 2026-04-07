# OSINT Resource Center

A curated, single-file intelligence hub for open-source analysts. Discover tools, frameworks, and data sources across every domain of OSINT collection — all in one searchable, filterable interface.

Vibe coded with [Claude](https://claude.ai).

---

## Overview

The OSINT Resource Center is a self-contained HTML page that organizes hundreds of open-source intelligence tools into a clean, dark-themed reference interface. It requires no backend, no dependencies, and no build process — just open the file in a browser.

---

## Features

- **Live search** across all tool names, descriptions, and tags with a one-click clear button
- **Category filters** to narrow results by domain (People Search, Domain & IP, Social Media, Geospatial, Images & Video, Email & Username, Threat Intel, Dark Web, Breaches & Leaks, Corporate, Frameworks, Documents)
- **Access filters** to filter by pricing tier — Free, Freemium, or Paid
- **Quick Access toolbar** for the most commonly used analyst tools
- **Last updated banner** displayed at the top of the page
- **Live stats** showing total resources, free tools, and filtered result counts
- No external dependencies, no tracking, no accounts required

---

## Categories

| Category | Description |
|---|---|
| People Search | Identity lookup, public records, court records, voter data |
| Domain & IP | WHOIS, DNS, certificate transparency, IP geolocation, network recon |
| Social Media | Platform search, social graph analysis, archiving, monitoring |
| Geospatial | Satellite imagery, street-level imagery, sun/shadow analysis, vessel and flight tracking |
| Images & Video | Reverse image search, EXIF metadata, deepfake detection, image forensics |
| Email & Username | Email lookup, username enumeration, breach checking, account discovery |
| Threat Intelligence | Malware analysis, IOC lookup, threat feeds, sandboxing |
| Dark Web | Onion search, paste monitoring, leak indexing |
| Breaches & Leaks | Credential exposure, data breach search, leak databases |
| Corporate | Company registration, financial filings, corporate graph |
| Frameworks | OSINT automation frameworks, recon tooling |
| Documents | FOIA portals, document repositories, public filing search |

---

## Usage

1. Clone or download the repository
2. Open `index.html` in any modern browser
3. No installation, server, or internet connection required to use the interface (individual tools will open in new tabs)

```bash
git clone https://github.com/yourusername/osint-resource-center.git
cd osint-resource-center
open index.html
```

---

## Structure

```
osint-resource-center/
├── index.html        # The entire application — HTML, CSS, and JS in one file
└── README.md
```

All styles and JavaScript are embedded directly in `index.html`. There are no external stylesheets, frameworks, or scripts loaded at runtime.

---

## Contributing

To suggest a new tool or report a broken link, open an issue with:

- The tool name and URL
- The category it belongs in
- Whether it is free, freemium, or paid

---

## Disclaimer

This resource center is intended for lawful open-source research and investigative purposes only. The inclusion of a tool does not constitute an endorsement. Users are responsible for ensuring their use of any listed tool complies with applicable laws, terms of service, and ethical guidelines.

---

## License

MIT
