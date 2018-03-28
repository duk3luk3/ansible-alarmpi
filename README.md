# ansible-alarmpi

Raspberry Pi Archlinux-ARM Initial Setup

This repository contains a handful of ansible roles intended to provision a Raspberry Pi running Arch Linux ARM as a file hosting / backup node.

It runs the following tasks:

* Create a new user with sudo permissions and disable default alarm user
* Create an SSH Reverse Tunnel to a host in the outside world for remoting in
* Install and configure syncthing (ToDo)
