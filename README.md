[![Build Status](https://travis-ci.com/saeeddhqan/maryam.svg?branch=master)](https://travis-ci.com/saeeddhqan/maryam)
![Version 1.4.9](https://img.shields.io/badge/Version-1.4.9-green.svg)
![GPLv3 License](https://img.shields.io/badge/License-GPLv3-green.svg)
![Python 3.8.x](https://img.shields.io/badge/Python-3.8.x-green.svg)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/40d81c48b3444ee78ffc6c5c8639134c)](https://www.codacy.com/manual/saeeddhqan/Maryam?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=saeeddhqan/Maryam&amp;utm_campaign=Badge_Grade)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/4577/badge)](https://bestpractices.coreinfrastructure.org/projects/4577)

# OWASP Maryam

OWASP Maryam is a modular/optional open source framework based on OSINT and data gathering. Maryam is written in Python programming language and It’s designed
to provide a powerful environment to harvest data from open sources and search engines and collect data quickly and thoroughly. If you have skill in Metasploit or Recon-ng, you can easily use it without prerequisites and if not, please read the [Quick Guide](https://github.com/saeeddhqan/Maryam/wiki#quick-guide).
The interface of this project heavily inspired by [Recon-ng](https://github.com/lanmaster53/recon-ng).

# Install
For installing, there's no need for a lot of modules to install, It just needs a "requests"
library
### Supported OS
 - Linux
 - FreeBSD
 - OSX

### Prerequisites
 - Python 3.8.x or 3.9.x (NOT 3.7, ..)
 - requests module

```bash
git clone https://github.com/saeeddhqan/maryam.git
pip install -r requirements
cd maryam
python3 maryam -e help
```
[![asciicast](https://asciinema.org/a/382779.svg)](https://asciinema.org/a/382779?speed=2)

## News
**What is new?**

 - Fixed bing and google search
 - Deleted searchencrypt engine
 - Running modules with options(Without entering to program) 
 - Added youtube and quora search module
 - Added three new source rapiddns, certspotter and sublist3r for dns_search
 - Added dbrute, fbrute, tldbrute, entry_points and waf to footprint

## Contribution

Contributes are welcome! Here is a start guide: [Development Guide](https://github.com/saeeddhqan/maryam/wiki/Development-Guide)
You can add a new search engine to the util classes or use current search engines to write a new module.
The best help to write a new module is by checking the current modules.
 
## Roadmap

 - Write a complete metacrawler engine based on OSINT by using the current search engines
 - Add new sources for dns_search module
 - Compatible with Windows OS

## links
### [OWASP](https://owasp.org/www-project-maryam/)
### [Wiki](https://github.com/saeeddhqan/maryam/wiki)
### [Install](https://github.com/saeeddhqan/maryam/wiki#install)
### [Modules Guide](https://github.com/saeeddhqan/maryam/wiki/modules)
### [Development Guide](https://github.com/saeeddhqan/maryam/wiki/Development-Guide)

To report bugs, requests, or any other issues please [create an issue](https://github.com/saeeddhqan/maryam/issues).

