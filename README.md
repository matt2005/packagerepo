# Overview

Package Repo for me

## Debian

### Buster

```bash
wget -qO - https://matt2005.github.io/packagerepo/PUBLIC.KEY | sudo apt-key add -
cat >/etc/apt/sources.list.d/matt2005.list <<EOCAT
deb http://matt2005.github.io/packagerepo/debian buster main
EOCAT
```

### Bullseye

```bash
wget -qO - https://matt2005.github.io/packagerepo/PUBLIC.KEY | sudo apt-key add -
cat >/etc/apt/sources.list.d/matt2005.list <<EOCAT
deb http://matt2005.github.io/packagerepo/debian bullseye main
EOCAT
```