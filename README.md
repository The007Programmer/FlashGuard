![FlashGuardLogo](docs/image.png)

![alt text](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#)
[![Read the Docs](https://img.shields.io/badge/Read%20the%20Docs-8CA1AF?logo=readthedocs&logoColor=fff)](#)
[![Debian](https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=fff)](#)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white)](#)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=fff)](#)


## What is it?
- A drive security tool for **Debian-based** systems. Verifies, logs, and tracks USB/Flash drive activity on device. This program utilizes `bash` scripts to log USB activity. This program is also an `apt` installable package for Debian based systems.

## TOC
> [Description](#what-is-it)<br>
> [Features](#features)<br>
> [Usage](#installation-and-usage)<br>
> [Credits](#credits)<br>
> [Understanding Commits](#commits-key)<br>

## Features
| Feature    | Implemented? |
| -------- | ------- |
|List all USB devices connected since startup|❌|
|Logging every USB device plugged in with timestamp, device name, etc...|❌|
|Interactive whitelist/blacklist management for individual USB devices|❌|
|Optional security backup feature with subcommands for size, trusted files, etc...|❌|
|Settings and config option|❌|

## Installation and Usage
- On Debian-based systems:
    - `sudo apt install flashguard`
- ### ^^^ This command will not work yet; APT package not built and published yet.
- For more best practices and usage info, refer to the documentation.

## Credits
- ChatGPT for brainstorming initial idea features and names.

## License
- 

### Commits Key
- SAFE: Stable and production-ready code; can be safely deployed.
- TEST: Code meant for testing or experimental changes; safe but does not affect the main program directly; stable for version control.
- UNST: Unstable commit with potential issues; not suitable for production, used for backup or testing phases.
- HTFX: Hotfix for critical issues.
- REFA: Refactor or restructure code for improved readability, maintainability, or efficiency, with no changes to core functionality.
- RESD: Revert previous changes due to instability or issues encountered during testing; restores the code to a prior stable state.
- BUGF: Bug fix or issue resolution, fixing known problems in the code without adding new functionality.
- DOCS: Documentation update, including comments, README files, or other forms of documentation to improve clarity and understanding.