<h1 align="center">
  Markdownlint
</h1>

<p align="center"><b>This is the snap for markdownlint</b>, <i>"A tool to check markdown files and flag style issues"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

[![Snap Status](https://build.snapcraft.io/badge/konrad11901/mdl-snap.svg)](https://build.snapcraft.io/user/konrad11901/mdl-snap)

> The original repository can be found [here](https://github.com/markdownlint/markdownlint/tree/v0.4.0).

## Install

    sudo snap install mdl

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->
## Usage

    cat file.md | mdl
    
## Known issues

* Trying to run `mdl <file>` will fail (permission error). Please use `cat <file> | mdl` instead. *This problem doesn't occur when the file is located in home directory or on removable media.*

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) 
are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml)
upstream so [Project] can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account.
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [ ] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [x] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link](https://forum.snapcraft.io/t/call-for-testing-markdownlint/3173)
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, transfer the snap name from you to snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

<!-- 
## The Snapcrafters

| [![Your Name](http://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/yourname/) |
| :---: |
| [Your Name](https://github.com/yourname/) |
--> 

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](http://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
