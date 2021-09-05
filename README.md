# Overview

Package Repo for me

## Debian

### Buster

```bash
wget -qO - https://matt2005.github.io/packagerepo/PUBLIC.KEY | sudo apt-key add -
echo "deb http://matt2005.github.io/packagerepo/apt/debian buster main" > /etc/apt/sources.list.d/matt2005.list
```

### Bullseye

```bash
wget -qO - https://matt2005.github.io/packagerepo/PUBLIC.KEY | sudo apt-key add -
echo "deb http://matt2005.github.io/packagerepo/apt/debian bullseye main" > /etc/apt/sources.list.d/matt2005.list
```