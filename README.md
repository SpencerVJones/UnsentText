<div align="center">
  <h2 align="center">UnsentText</h2>
  <div align="left">
	

![Repo Views](https://visitor-badge.laobi.icu/badge?page_id=SpencerVJones/UnsentText)

</div>

  
<p align="center">
  A lightweight web app for writing “unsent” messages — thoughts you want to get out without actually sending.  
  Built with <strong>vanilla HTML, CSS, and JavaScript</strong>, bundled using <strong>npm + Webpack</strong> for a fast, deployable static site with <strong>PWA support</strong>.
  <br /><br />
  This project was inspired by 
  <a href="https://theunsentproject.com/" target="_blank" rel="noopener noreferrer">
    <strong>The Unsent Project</strong>
  </a>, 
  which explores emotional expression through anonymous, unsent messages.
  <br />
  <br />
  <a href="https://github.com/SpencerVJones/UnsentText/issues">Report Bug</a>
    ·
    <a href="https://github.com/SpencerVJones/UnsentText/issues">Request Feature</a>
  </p>
</div>


<!-- PROJECT SHIELDS -->
<div align="center">


![License](https://img.shields.io/github/license/SpencerVJones/UnsentText?style=for-the-badge)
![Contributors](https://img.shields.io/github/contributors/SpencerVJones/UnsentText?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/SpencerVJones/UnsentText?style=for-the-badge)
![Stargazers](https://img.shields.io/github/stars/SpencerVJones/UnsentText?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/SpencerVJones/UnsentText?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/SpencerVJones/UnsentText?style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/SpencerVJones/UnsentText?style=for-the-badge)

![Platform](https://img.shields.io/badge/Platform-Web-lightgrey.svg?style=for-the-badge&logo=google-chrome&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-2B3A42?style=for-the-badge&logo=webpack&logoColor=8DD6F9)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)


</div>



## 📑 Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Features](#features)
- [Demo](#demo)
- [Project Structure](#project-structure)
- [Testing](#testing)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [How to Run](#how-to-run)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
	- [Contributors](#contributors)
- [License](#license)
- [Contact](#contact)

## Overview
**UnsentText** is a simple web experience for writing messages you *don’t* plan to send.  
It’s intentionally minimal: write freely, keep things private, and (optionally) treat it like a personal draft/journal space.

This repository is structured as a **static site** bundled with **Webpack**, with a `dist/` output folder suitable for GitHub Pages-style deployment.  



## Technologies Used
- **JavaScript (ES6+)**
- **HTML5 / CSS3**
- **Webpack** (dev + prod configs)
- **PWA assets** (manifest + icons)

## Architecture
- **Static web app** with a Webpack build pipeline  
- **Source folders** for CSS/JS and a **compiled `dist/` output**  
- Separate webpack configs for **common**, **dev**, and **prod** builds

## Features
- ✍️ A clean interface for writing “unsent” messages
- ⚡ Webpack-bundled build for fast loading + easy deploy
- 📱 PWA-ready assets (manifest + icons) for installable feel
- 🧩 Simple structure (easy to extend with storage, tags, search, etc.)

## Demo
🔗 **Live Demo:** [https://spencervjones.github.io/UnsentText/](https://spencervjones.github.io/UnsentText/)

## Project Structure
```bash
UnsentText/
├── .github/workflows/           # CI / automation (GitHub Actions)
├── css/                         # Stylesheets
├── js/                          # JavaScript source
├── dist/                        # Production build output (static)
├── 404.html                     # SPA / Pages fallback
├── index.html                   # App entry
├── favicon.ico                  # Site icon
├── icon.png                     # PWA icon
├── icon.svg                     # Vector icon
├── robots.txt                   # SEO / crawling rules
├── site.webmanifest             # PWA manifest
├── package.json                 # Scripts + dependencies
├── package-lock.json            # Locked dependency tree
├── webpack.common.js            # Shared config
├── webpack.config.dev.js        # Dev config
├── webpack.config.prod.js       # Prod config
└── webpack.config.js            
```
## Testing
Coming Soon!


## Getting Started
### Prerequisites
-  **Node.js** (LTS recommended)
-   npm

### Installation
```bash
git clone https://github.com/SpencerVJones/UnsentText.git
cd UnsentText
npm install
```
 
### How to Run
```bash
npm run dev     # start development server
npm run build   # create production build in dist/
```

## Usage
-   Open the dev server URL (if running locally), or visit the deployed site above.
-   Write your message.
-   Extend the project by adding local persistence (`localStorage`), tags, export options, etc.
 
## Roadmap
 - [ ] Local persistence (`localStorage`) for drafts
 - [ ] Search + filtering
 - [ ] Tags / recipients / mood labels
 - [ ] Export drafts (TXT / JSON)
 - [ ] Optional passcode lock (client-side)
 - [ ] Better PWA offline support (service worker)
 - [ ]  Mobile-first polish & accessibility pass

See open issues for a full list of proposed features (and known issues).
 
 
## Contributing
Contributions are welcome! Feel free to submit issues or pull requests with bug fixes, improvements, or new features.
- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

### Contributors
<a href="https://github.com/SpencerVJones/UnsentText/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SpencerVJones/UnsentText"/>
</a>


## License
Distributed under the MIT License. See LICENSE for more information.



## Contact
Spencer Jones
📧 [SpencerVJones@outlook.com](mailto:SpencerVJones@outlook.com)  
🔗 [GitHub Profile](https://github.com/SpencerVJones)  
🔗 [Project Repository](https://github.com/SpencerVJones/UnsentText)
