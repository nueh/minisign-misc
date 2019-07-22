![MSmisc-platform-macos](https://img.shields.io/badge/platform-macOS-lightgrey.svg)
![MSmisc-code-shell](https://img.shields.io/badge/code-shell-yellow.svg)
[![MSmisc-depend-minsign](https://img.shields.io/badge/dependency-minisign%200.7-green.svg)](https://github.com/jedisct1/minisign)
[![MSmisc-license](http://img.shields.io/badge/license-MIT+-blue.svg)](https://github.com/JayBrown/minisign-misc/blob/master/license.md)

# Minisign Miscellanea <img src="https://github.com/JayBrown/minisign-misc/blob/master/img/jb-img.png" height="20px"/>
**macOS workflows and shell scripts to verify and sign files with minisign**

![ms-verify-screengrab](https://github.com/JayBrown/minisign-misc/blob/master/img/minisign-verify-grab.png)

## Prerequisites
Install using [Homebrew](http://brew.sh) with `brew install minisign` (or with a similar manager)

* [minisign](https://github.com/jedisct1/minisign)

Because Minisign Miscellanea use the macOS Notification Center, the minimum Mac OS requirement is **OS X 10.8 (Mountain Lion)**.

## Installation & Usage
* [Download the latest DMG](https://github.com/JayBrown/minisign-misc/releases) and open

### Workflows
* Double-click on the workflow files to install
* If you encounter problems, open them with Automator and save/install from there
* Standard Finder integration in the Services menu

### Shell scripts [optional]
* Move the scripts to `/usr/local/bin`
* In your shell enter `chmod +x /usr/local/bin/minisign-verify.sh` and `chmod +x /usr/local/bin/minisign-sign.sh`
* Run the scripts with `minisign-verify.sh /path/to/your/file` and `minisign-sign.sh /path/to/your/file`

Only necessary if for some reason you want to run this from the shell or another shell script.

## General Notes
* My own minisign public key for releases on Github will be created in `${HOME}/Documents/minisign`

## Screengrabs
### Signing
![ms-sign-screengrab](https://github.com/JayBrown/minisign-misc/blob/master/img/minisign-sign-grab.png)

![ms-signresults-screengrab](https://github.com/JayBrown/minisign-misc/blob/master/img/minisign-signingresults-grab.png)

### Verifying
![ms-verify-screengrab](https://github.com/JayBrown/minisign-misc/blob/master/img/minisign-verify-grab.png)

![ms-verifyresults-screengrab](https://github.com/JayBrown/minisign-misc/blob/master/img/minisign-verifyingresults-grab.png)
