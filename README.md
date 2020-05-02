# WiFi-Sploit - Exploitation Framework for Embedded Devices

[![Python 3.6](https://img.shields.io/badge/Python-3.6-yellow.svg)](http://www.python.org/download/)

The WiFi-Sploit Framework is an open-source exploitation framework dedicated to embedded devices.

[![asciicast](https://asciinema.org/a/180370.png)](https://asciinema.org/a/180370)

It consists of various modules that aids penetration testing operations:

* exploits - modules that take advantage of identified vulnerabilities
* creds - modules designed to test credentials against network services
* scanners - modules that check if a target is vulnerable to any exploit
* payloads - modules that are responsible for generating payloads for various architectures and injection points
* generic - modules that perform generic attacks 

# Installation

## Requirements

Required:
* future
* requests
* paramiko
* pysnmp
* pycrypto

Optional:
* bluepy - bluetooth low energy 

## Installation on Kali Linux

```
apt-get install python3-pip
git clone https://www.github.com/abhi007aryan/WiFi-Sploit
cd WiFi-Sploit
python3 -m pip install -r requirements.txt
python3 rsf.py
```

Bluetooth Low Energy support:
```
apt-get install libglib2.0-dev
python3 -m pip install bluepy
python3 rsf.py
```

## Installation on Ubuntu 18.04 & 17.10

```
sudo add-apt-repository universe
sudo apt-get install git python3-pip
git clone https://www.github.com/abhi007aryan/WiFi-Sploit
cd WiFi-Sploit
python3 -m pip install setuptools
python3 -m pip install -r requirements.txt
python3 rsf.py
```
# License

The WiFi-Sploit Framework is under a BSD license.
Please see [LICENSE](LICENSE) for more details.

# Acknowledgments
* [riposte](https://github.com/threat9/RouterSploit)
