---
description: Welcome to the dogehouse documentation
---

# DogeHouse

![ Taking voice conversations to the moon &#x1F680;](https://raw.githubusercontent.com/benawad/dogehouse/staging/.redesign-assets/dogehouse_logo.svg)

                             [![discord - users online](https://img.shields.io/discord/810571477316403233?style=for-the-badge)](https://discord.gg/wCbKBZF9cV) [![dogehouse - users online](https://img.shields.io/endpoint?color=FD4D4D&style=for-the-badge&url=https%3A%2F%2Fapi.dogegarden.net%2Fv1%2Fshields)](https://dogehouse.tv)

###                              [Contribute](https://github.com/benawad/dogehouse/blob/staging/CONTRIBUTING.md) · [Community](https://discord.gg/82HzQCJCDg) · [Documentation](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/docs/README.MD)

## Structure

| Codebase | Description |
| :--- | :---: |
| [kousa](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/kousa/README.md) | Elixir API |
| [shawarma](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/shawarma/README.md) | Voice Server |
| [dinner](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/dinner/README.md) | Puppeteer shenanigans |
| [baklava](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/baklava/README.md) | Electron Wrapper |
| [pilaf](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/pilaf/README.md) | React Native App |
| [feta](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/feta/README.md) | Shared utils web/app |
| [kibbeh](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/kibbeh/README.md) | Next.js frontend |
| [kebab](https://github.com/FotieMConstant/dogehouse-docs/tree/61448218e2cf3967eb064bb8dcd372ec9da02f68/kebab/README.md) | API Client |

## Branches

* staging -&gt; pr this branch for everything
* prod -&gt; don't touch, this is what's running in prod

## Contributions

DogeHouse is open to contributions, but I recommend creating an issue or replying in a comment to let me know what you are working on first that way we don't overwrite each other.

Please read [CONTRIBUTING.md](https://github.com/benawad/dogehouse/blob/staging/CONTRIBUTING.md) for details on this project.

## DogeHouse Desktop

A desktop app built with [Electron](https://www.electronjs.org/) is available for Windows, Mac, and Linux.

There are different ways to get the Electron desktop app:

* Get the official builds from [here, in GitHub Releases](https://github.com/benawad/dogehouse/releases/latest)

  for any platform.

* Get it from AUR \(unofficial package\) for Arch/Manjaro or other Arch-based distro with

  `yay -S dogehouse`, using another AUR helper, or installing manually from the AUR.

* Get the desktop client for Debian-based distros \(including Ubuntu\)

  from the official APT repo with these simple steps:

  * Add the repo with `echo "deb http://ppa.dogehouse.tv/ ./" | sudo tee -a /etc/apt/sources.list > /dev/null`
  * Add Ben Awad's GPG key with `$(command -v curl>>/dev/null && echo "curl -o-" || echo "wget -q0-") http://ppa.dogehouse.tv/KEY.gpg | sudo apt-key add -`.
  * Finally, update your local repoistory list and install DogeHouse

    with `sudo apt update && sudo apt install dogehouse`.

* Get the snap for your systemd-powered Linux distro from either the

  [Snap Store](https://snapcraft.io/dogehouse) or in an terminal with

  `sudo snap install dogehouse`.

  * After installing the snap, you need to allow microphone access with

    `sudo snap connect dogehouse:audio-record` to be able to speak in rooms.

_**Notes:**_

* If a warning message pops up on Windows, go to 'more info' and select 'Run Anyway'
* Currently, the snap package's available channels are only `edge` as

  contributions for Baklava are merged almost on daily basis. Tested

  versions that are stable will be promoted into `stable` in the future.

## DogeReviewers

Contributors helping to review/merge pull requests:

* [@HarrisonMayotte](https://github.com/HarrisonMayotte)
* [@TheOtterlord](https://github.com/TheOtterlord)
* [@amitojsingh366](https://github.com/amitojsingh366)
* [@dk-raw](https://github.com/dk-raw)
* [@ermalsh](https://github.com/ermalsh)
* [@goldyydev](https://github.com/goldyydev)
* [@jamesql](https://github.com/jamesql)
* [@nadirabbas](https://github.com/nadirabbas)
* [@ofsho](https://github.com/ofsho)
* [@overlisted](https://github.com/overlisted)

## Code of Conduct

Please read [CODE\_OF\_CONDUCT.md](https://github.com/benawad/dogehouse/blob/staging/CODE_OF_CONDUCT.md) for details on our code of conduct.

## How to run locally

Check [here](https://github.com/benawad/dogehouse/blob/staging/CONTRIBUTING.md#quickstart-local-frontend-development) on how to run locally

## Why did you make this?

[https://www.youtube.com/watch?v=hy-EhJ\_tTQo](https://www.youtube.com/watch?v=hy-EhJ_tTQo)

## Attribution

For emojis, we use [Twemoji](https://twemoji.twitter.com/)

