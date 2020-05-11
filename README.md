# Ultra Recon

A tool for running all your recon tools in Docker without remembering Docker commands

[![Python 3.7](https://img.shields.io/badge/python-3.7-FADA5E.svg?logo=python)](https://www.python.org/) 
[![Docker](https://img.shields.io/badge/docker-required-0db7ed.svg?logo=docker)](https://www.docker.com/) [![PEP8](https://img.shields.io/badge/code%20style-pep8-red.svg)](https://www.python.org/dev/peps/pep-0008/) [![License](https://img.shields.io/badge/license-GPL3-lightgrey.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html) [![Twitter](https://img.shields.io/badge/twitter-sneakerhax-38A1F3?logo=twitter)](https://twitter.com/sneakerhax) [![Discord](https://img.shields.io/badge/discord-sneakerhax-7289DA?logo=discord)](https://discordapp.com/invite/wpxpYM3)

![alt text](.img/Ultra_Sun_Ultra_Moon_Ultra_Recon_Squad.png)

## Installation

Install Docker on your local system:
* <https://docs.docker.com/get-docker/>

Install Docker SDK for Python:

```pip install -r requirements.txt```

All keys should be added to config.conf

## Usage

```python3 ultra_recon -n <name_of_target> -t <target> -i <docker_image_name>```

## Current images

* Nmap
* PyDNSRecon (Requires Censys API ID + Secret)

## References

* <https://docker-py.readthedocs.io/en/stable/>
