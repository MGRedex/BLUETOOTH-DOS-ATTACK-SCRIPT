# Bluetooth DOS-Attack Script

![Python Version](https://img.shields.io/pypi/pyversions/Django.svg)

Script for conducting DOS-attacks on Bluetooth devices for pentest purposes.

## Disclaimer

This project was created for educational purposes and personal use only.

**DISCLAIMER:** This software is provided "as is" without any warranty. Usage is at your own risk. The developers assume no liability for any misuse or damage caused by this program.

## Installation

```shell
$ sudo apt update
$ sudo apt install python3
$ sudo git clone https://github.com/jieggiI/BLUETOOTH-DOS-ATTACK-SCRIPT.git
$ cd BLUETOOTH-DOS-ATTACK-SCRIPT/
$ python3 Bluetooth-DOS-Attack.py
```

## Note

This script is designed to work only on Linux systems.You must have "l2ping" and "hcitool" utilities on your Linux machine (they are installed by default on Kali Linux).

## Tested on

Kali Linux as attacker, and Xiaomi Portable Bluetooth Speaker as target, 

Raspberry Pi W Zero as attacker, and Redmi Buds Lite as target

## Manual

Target ID or MAC: ID or MAC address displayed after scanning.

Package Size: Size of the packages to be sent to the target (600 is optimal).

Threads Count: Number of threads that simultaneously send packages to the target. Optimal value can be found in the provided table.

## What Happens to the Target Device

While I can't speak for all devices, the device I tested typically just turned off.
