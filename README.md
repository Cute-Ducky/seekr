<p align="center">
  <a href="https://github.com/seekr-osint/seekr" target="blank"><img src="./web/images/seekr-transparent.png" width="250" alt="Seekr Logo" /></a>
 </p>

 <p align="center">
 A multi-purpose toolkit for gathering and managing OSINT-Data with a neat web-interface.
</p>
<p align="center">
<img alt="GitHub" src="https://img.shields.io/github/license/seekr-osint/seekr">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/seekr-osint/seekr/go.yml">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/seekr-osint/seekr">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/seekr-osint/seekr">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/seekr-osint/seekr">
</p>

## Table of Contents
- [What is seekr?](#what-is-seekr)
- [Why use seekr over my current tool?](#why-use-seekr-over-my-current-tool)
- [Key features](#key-features)
- [Inatallation](#installation)
- [Usage](#usage)
- [Feedback](#feedback)
- [Contact us](#contact-us)
- [Legal Disclaimer](#legal-disclaimer)

## What is seekr?
Seekr is a multi-purpose toolkit for gathering and managing OSINT-data with a sleek web interface. Our desktop view enables you to have all of your favourite OSINT tools integrated in one. The backend is written in Go with BadgerDB as database and it offers a wide range of features for data collection, organization and analysis. Whether you're a researcher, investigator or just someone looking to gather information, seekr makes it easy to find and manage the data you need. Give it a try and see how it can streamline your OSINT workflow!

Check the wiki for setup guide, etc.

<img width="800" src="https://github.com/Cute-Ducky/seekr/blob/main/images/seekr.gif">
<img src="https://github.com/Cute-Ducky/seekr/blob/main/images/seekr-short.gif">

## Why use seekr over my current tool?
Seekr combines note taking and OSINT in one application. Seekr can be used alongside your current tools.
Seekr is desingned with OSINT in mind and optimized for real world usecases.
## Key features
- **NO** api keys required for **all** features
- Desktop interface
- Database for OSINT targets
- Integration / adaptation of many popular OSINT-tools (e.g. phoneinfoga)
- GitHub to email
- Guide (Enter information you have and get web-tools recommended to help you)
- Account cards for each person in the database
- Account discovery intigrating with the account cards
- Pre defined commonly used fields in the database
- Themes & Plugins
## Installation
### Windows
Download and run the latest exe from the [latest release](https://github.com/seekr-osint/seekr/releases/latest).

Now open [the web interface](http://localhost:8569/web/) in your browser of choice.
### Docker
Run the following commands in your terminal:
```sh
docker pull ghcr.io/seekr-osint/seekr:latest
docker run -p 8569:8569 ghcr.io/seekr-osint/seekr:latest
```
### Linux
#### Stable
Download the latest stable binary from the [latest release](https://github.com/seekr-osint/seekr/releases/latest).
#### Unstable
To install seekr (unstable) on linux simply run:
```sh
git clone https://github.com/seekr-osint/seekr
cd seekr
go run main.go
```
Now open [the web interface](http://localhost:8569/web/) in your browser of choice.
### Run on NixOS
Seekr is build with NixOS in mind and therefore supports nix flakes.
To run seekr on NixOS run these commands:
```sh
nix shell github:seekr-osint/seekr
seekr
```
## Usage
Just open [the web interface](http://localhost:8569/web/) in your browser of choice.
Open the menu by pressing the button in the bottom left corner.
Start any of the tools you want and rearrange them however you like!
## Feedback
We would love to hear from you. Tell us about your opinions on seekr. Where do we need to improve?...
You can do this by just opening up an issue or maybe even telling others in your blog or somewhere else about your experience.
## Contact us
You can contact us at **[seekr-osint@proton.me](mailto:seekr-osint@proton.me)**!
## Legal Disclaimer
This tool is intended for legitimate and lawful use only. It is provided for educational and research purposes, and should not be used for any illegal or malicious activities, including doxxing. Doxxing is the practice of researching and broadcasting private or identifying information about an individual, without their consent and can be illegal. The creators and contributors of this tool will not be held responsible for any misuse or damage caused by this tool. By using this tool, you agree to use it only for lawful purposes and to comply with all applicable laws and regulations. It is the responsibility of the user to ensure compliance with all relevant laws and regulations in the jurisdiction in which they operate. Misuse of this tool may result in criminal and/or civil prosecution.
For legal questions contact us at **[seekr-osint@proton.me](mailto:seekr-osint@proton.me)**!
## Thanks to
[![Stargazers repo roster for @seekr-osint/seekr](https://reporoster.com/stars/seekr-osint/seekr)](https://github.com/seekr-osint/seekr/stargazers)

- [WinBox.js](https://github.com/nextapps-de/winbox)
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/)
- [WAU/discord.go](https://github.com/alpkeskin/wau/blob/main/cmd/apps/discord.go)
