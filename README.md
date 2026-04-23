# embi-kas

This repository provides `kas` configuration files to build Embi OS Yocto images based on Boot2Qt.

---

## Prerequisites

### System packages (Ubuntu/Debian example)

```bash
sudo apt update
sudo apt install -y \
    git wget diffstat unzip texinfo gcc build-essential chrpath socat \
    cpio pipx python3 python3-pip python3-pexpect xz-utils debianutils \
    iputils-ping python3-git python3-jinja2 libsdl1.2-dev \
    xterm
pipx install kas --system-site-packages
```

## Quick start

Clone this repository:

```bash
git clone git@github.com:Embi-OS/embi-kas.git

kas build embi-kas/latest.yml
```

For more information about Embi OS, see https://github.com/Embi-OS
