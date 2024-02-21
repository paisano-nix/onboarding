# Paisano Onboarding Script

## Usage

#### 1. Branded CLI (optional)

Re-expose a branded version of `paisano` CLI as `.#<your-name>`

#### 2. Install script

Create the following file within your repo:

```bash
#! /usr/bin/env bash

# optional, if you have a branded package
export OWNER=my-github-org
export REPO=my-repo
export PACKAGE=my-branded-cli

bash <(curl -L https://raw.githubusercontent.com/paisano-nix/Oonboarding/main/install)
```

#### 3. Readme Instructions

``````md
## Getting Set Up

```console
bash <(curl -L https://raw.githubusercontent.com/<myorg>/<myrepo>/<branch>/install.sh)
```

## Explore The Repo

```console
<mypackage>
```
``````

#### 4. Tips and Tricks

You can use GH Pages to host your scrit and prettify the instruction to:

```console
bash <(curl -L https://<myorg>.github.io/<myrepo>/install)

```
