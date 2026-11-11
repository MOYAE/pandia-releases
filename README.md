# Pandia downloads

Pandia, by Moyae, is the small program that runs on one computer at a clinic. It connects the clinic's instruments,
such as the Haag-Streit Elara 900 slit lamp, to Jupiter, where the practice reviews exams and joins remote sessions.

This repository only holds the release files. Pandia's source code is private.

## Download the newest version

| Computer | File |
|---|---|
| Windows 10 or 11 | [Install-Pandia.cmd](https://github.com/MOYAE/pandia-releases/releases/download/dev-latest/Install-Pandia.cmd), [install.ps1](https://github.com/MOYAE/pandia-releases/releases/download/dev-latest/install.ps1) and [pandia-windows-x64.tar.gz](https://github.com/MOYAE/pandia-releases/releases/download/dev-latest/pandia-windows-x64.tar.gz) |
| Mac (Apple silicon) | Ask Moyae for the installer package (not built automatically yet) |
| Linux (x64) | [pandia-linux-x64.tar.gz](https://github.com/MOYAE/pandia-releases/releases/download/dev-latest/pandia-linux-x64.tar.gz) |

These links always give the newest development build, which works with Jupiter's test environment. Every version
is listed under [Releases](https://github.com/MOYAE/pandia-releases/releases), with install steps on each one.

## Install on Windows

1. Put the three Windows files in one folder.
2. Double-click `Install-Pandia.cmd` and allow administrator rights.
3. Choose "Enter enrollment code..." from the Pandia icon next to the clock and paste the code from Jupiter.

Pandia is not code-signed yet, so Windows may say the publisher is unknown. Choose "More info", then "Run anyway".

The Linux build has no installer yet; ask Moyae if you need it.

## Open source

Pandia includes open source programs, used unmodified. Their notices and license texts, with links to their source
code, are in the `licenses` folder of every release.
