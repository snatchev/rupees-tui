Rupees Project
===

Desired Usage
---
b/
User can SSH into their "instance" (firecracker-vm) that will have up-to-date ledger files for all of their accounts

User can add / remove / reconcile accounts via tui built with https://github.com/charmbracelet/wish


Dev Notes
---

How to setup the env

install ledger (with python3 support):
```
sudo add-apt-repository ppa:mbudde/ledger
sudo apt-get update
sudo apt-get install ledger ledger-autosync
```
