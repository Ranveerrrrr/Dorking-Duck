# Dorking Duck 🚦‏

![Google Dorks](https://img.shields.io/badge/Google-Dorking-blue)
![Security](https://img.shields.io/badge/Security-Research-red)
![Bug Bounty](https://img.shields.io/badge/Bug-Bounty-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)


Dorking Duck is a fast, browser-based Google Dorks generator designed for web security research, bug bounty reconnaissance, and OSINT work.
It helps you generate powerful Google search queries (dorks) using curated patterns to find exposed files, misconfigurations, and interesting attack surfaces.

Live Site: https://dorking-duck.web.app/

---


Features
---
- 150+ pre-built Google dorks
- Domain-specific dorking (ex: site:target.com)
- Wildcard dorking for large recon
- Supports directories, admin panels, APIs, and cloud exposures
- Lightweight and fast (no backend)
- Runs completely in the browser
- Easy to copy and export dorks

---

Who This Tool Is For
---
Dorking Duck is built for:
- Bug Bounty Hunters
- Penetration Testers
- Web Security Researchers
- OSINT Practitioners
- Students Learning Web Hacking
- Red Team Reconnaissance Workflows

If you do recon before exploitation, this tool is meant for you.

---


Where Dorking Duck Can Be Used
---
Dorking Duck can be used in multiple scenarios, such as:

- Finding open directories and file listings
- Discovering exposed .env, .log, and backup files
- Identifying publicly accessible API endpoints
- Searching for admin and login panels
- Finding cloud misconfigurations (AWS, GCP, Azure)
- Early reconnaissance during bug bounty programs

---

Examples Google Dorks
---
site:target.com intitle:"index of"
site:target.com filetype:env
site:target.com inurl:admin
site:target.com AWS_ACCESS_KEY_ID
site:target.com filetype:log password

---

Installation
---
1. Clone the repository:
git clone https://github.com/Ranveerrrrr/Dorking-Duck.git

2. Open index.html in your browser.

3. Start generating dorks.

Or use the live version directly:
https://dorking-duck.web.app

---


Project Structure
---
Dorking-Duck
- index.html
- README.md
- LICENSE

---

LIcense
---
This project is licensed under the MIT License. You are free to use, modify, and distribute it.

---

Disclaimer
---
This tool is intended for educational and authorized security testing only. Do not use it against targets you do not have explicit permission to test.

---

Made by Ranveerrrr
