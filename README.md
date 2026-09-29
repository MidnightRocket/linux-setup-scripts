# linux-update-scripts
Scripts for simplifing and automating updates and installation of software.

# Installation of `COMPONENTS`
```sh
curl -fsSL "https://github.com/MidnightRocket/linux-setup-scripts/raw/refs/heads/main/download" | COMPONENTS="autoupdate/debian,healthping/debian" sh
```

# Specify custom `BRANCH` and `DOMAIN`
It is possible to specify alternative hosting provider, such as [Codeberg](https://codeberg.org/MidnightRocket/linux-setup-scripts) and alternative branch.
```sh
curl -fsSL "https://codeberg.org/MidnightRocket/linux-setup-scripts/raw/branch/main/download" | DOMAIN=codeberg.org BRANCH=some-branch COMPONENTS="autoupdate/debian,healthping/debian" sh
```
