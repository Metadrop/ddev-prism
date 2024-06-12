[![tests](https://github.com/Metadrop/prism/actions/workflows/tests.yml/badge.svg)](https://github.com/Metadrop/prism/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

## Prism

Ddev addon based on docker image [Prism](https://github.com/stoplightio/prism)

## Configure addon

Use collection on Openapi format, example from (stoplightio/prism Examples)[https://github.com/stoplightio/prism/blob/master/examples]

Edit/add a .env file with the following variables:

Optional prism version, by default 4.10.5.
PRISM_VERSION=4.10.5
Prism collection Openai format, by default.
Prism collection folder.
PRISM_LOCAL_DIR=collections
PRISM_COLLECTION=example.yml

Furder info on [Prism](https://github.com/stoplightio/prism)
