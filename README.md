<<<<<<< master
# Introduction

 

![ Taking voice conversations to the moon&#x1F680;](https://raw.githubusercontent.com/benawad/dogehouse/staging/.redesign-assets/dogehouse_logo.svg)

                           [![discord - users online](https://camo.githubusercontent.com/e6d2ca88c3d8ea88fdd7c6c581077903866f6cb8bc77de8027b89d74377a51c4/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f3831303537313437373331363430333233333f7374796c653d666f722d7468652d6261646765)](https://discord.gg/wCbKBZF9cV) [![dogehouse - users online](https://camo.githubusercontent.com/f711749b0b5736ecceb9dab129c12aea74321a268bfd721232a6cc8752385e6b/68747470733a2f2f696d672e736869656c64732e696f2f656e64706f696e743f636f6c6f723d464434443444267374796c653d666f722d7468652d62616467652675726c3d68747470732533412532462532466170692e646f676567617264656e2e6e65742532467631253246736869656c6473)](https://dogehouse.tv/)

###                          [Contribute](https://github.com/benawad/dogehouse/blob/staging/CONTRIBUTING.md) · [Community](https://discord.gg/82HzQCJCDg) · [Documentation](https://github.com/benawad/dogehouse/blob/staging/docs/README.MD)

## Structure

| Codebase | Description |
| :--- | :--- |
| [kousa](https://github.com/benawad/dogehouse/blob/staging/kousa) | Elixir API |
| [shawarma](https://github.com/benawad/dogehouse/blob/staging/shawarma) | Voice Server |
| [dinner](https://github.com/benawad/dogehouse/blob/staging/dinner) | Puppeteer shenanigans |
| [baklava](https://github.com/benawad/dogehouse/blob/staging/baklava) | Electron Wrapper |
| [pilaf](https://github.com/benawad/dogehouse/blob/staging/pilaf) | React Native App |
| [feta](https://github.com/benawad/dogehouse/blob/staging/feta) | Shared utils web/app |
| [kibbeh](https://github.com/benawad/dogehouse/blob/staging/kibbeh) | Next.js frontend |
| [kebab](https://github.com/benawad/dogehouse/blob/staging/kebab) | API Client |

## Branches

* staging -&gt; pr this branch for everything
* prod -&gt; don't touch, this is what's running in prod

## Contributions

DogeHouse is open to contributions, but I recommend creating an issue or replying in a comment to let me know what you are working on first that way we don't overwrite each other.

Please read [CONTRIBUTING.md](https://github.com/benawad/dogehouse/blob/staging/CONTRIBUTING.md) for details on this project.

## DogeHouse Desktop

A desktop app built with [Electron](https://www.electronjs.org/) is available for Windows, Mac, and Linux.

There are different ways to get the Electron desktop app:

* Get the official builds from [here, in GitHub Releases](https://github.com/benawad/dogehouse/releases/latest) for any platform.
* Get it from AUR \(unofficial package\) for Arch/Manjaro or other Arch-based distro with `yay -S dogehouse`, using another AUR helper, or installing manually from the AUR.
* Get the desktop client for Debian-based distros \(including Ubuntu\) from the official APT repo with these simple steps:
  * Add the repo with `echo "deb http://ppa.dogehouse.tv/ ./" | sudo tee -a /etc/apt/sources.list > /dev/null`
  * Add Ben Awad's GPG key with `$(command -v curl>>/dev/null && echo "curl -o-" || echo "wget -q0-") http://ppa.dogehouse.tv/KEY.gpg | sudo apt-key add -`.
  * Finally, update your local repoistory list and install DogeHouse with `sudo apt update && sudo apt install dogehouse`.
* Get the snap for your systemd-powered Linux distro from either the [Snap Store](https://snapcraft.io/dogehouse) or in an terminal with `sudo snap install dogehouse`.
  * After installing the snap, you need to allow microphone access with `sudo snap connect dogehouse:audio-record` to be able to speak in rooms.

_**Notes:**_

* If a warning message pops up on Windows, go to 'more info' and select 'Run Anyway'
* Currently, the snap package's available channels are only `edge` as contributions for Baklava are merged almost on daily basis. Tested versions that are stable will be promoted into `stable` in the future.

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
=======
# dogehouse-docs

Repository for the dogehouse doc 🚀
>>>>>>> main

