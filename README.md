# **the wisard-overlay**
This overlay contains ebuilds that I personally maintain or copied from other overlays with minor changes.

![Gentoo](https://img.shields.io/badge/Gentoo-54487A?style=for-the-badge&logo=gentoo&logoColor=white)
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

## current packages

| name | version | description | license |
----------- | ----------- | ----------- | ----------- |
| **bolt-launcher** | 0.14.0 / 0.15.0 | "An alternative launcher for your favourite MMO" | AGPL-3.0
| **r2modman-bin** | 3.1.57 | "R2ModMan is a simple and easy to use mod manager" | MIT |

##### credits
> [solarbaron-overlay](https://github.com/solarbaron/solarbaron-overlay/tree/main)

## how to use this overlay?
Since I don't have the overlay listed under the [gentoo overlays](https://repos.gentoo.org/), you can run the following commands:

>emerge --ask app-eselect/eselect-repository\
>eselect repository add wisard git https://git.wisard.me/wisard/wisard-overlay.git

manually adding it (/etc/portage/repos.conf/eselect-repo.conf):

> [wisard]\
> location = /var/db/repos/wisard\
> sync-type = git\
> sync-uri = https://git.wisard.me/wisard/wisard-overlay.git
