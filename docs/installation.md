---
sidebar_label: 'Giture Installation'
---
# Installation / Upgrade

## Docker

[Docker](https://github.com/gerardnico/giture/pkgs/container/giture)

```bash
docker run \
  --rm \
  ghcr.io/gerardnico/giture:latest \
  git-log --help
```

## HomeBrew

Mac / Linux / Windows WSL with HomeBrew

* Installation
```bash
brew install gerardnico/tap/giture
```

* Upgrade
```bash
brew update
brew upgrade giture
```
