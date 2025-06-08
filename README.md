<!-- GitAds-Verify: MNWAWW434KY93EKQLA6WO5J5R7JVEEE6 -->
# AIO Installer

Welcome to the **AIO** setup script — a powerful, automated installation tool for essential development tools and environments on Ubuntu-based systems.

## Features

* Logging with timestamps
* System update and upgrade
* Installation of:

  * Curl
  * Node.js
  * Python 3.12 and virtual environment
  * Docker & Docker Compose
  * Git
  * Screen & Tmux
  * Go (Golang)
  * Rust (including RZup)
  * Additional utilities: `seq`, `jq`, `bc`, `htop`, `pv`

## Usage

```bash
wget https://github.com/Wimboro/AIO-script/raw/main/aio.sh -O aio.sh && chmod +x aio.sh && ./aio.sh
```

> **Note:** Root or sudo privileges are required to perform installations.

## Logging

All actions and outputs are logged to `script.log` in the same directory for future reference.

## Compatibility

* Ubuntu 20.04, 22.04 and other Debian-based distributions

## License

This project is open source under the MIT License. Feel free to fork, modify, and share!

---

**Crafted with 💻 by HIDDEN CYBER**
**Fork from rokipdj88/jamuvps**
