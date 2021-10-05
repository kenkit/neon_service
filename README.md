# neon_service
Neon Service binary

[![GitHub Releases (by Release)](https://img.shields.io/github/downloads/kenkit/neon_service/latest/total)](https://github.com/kenkit/neon_installer/releases/latest)

[![GitHub issues by-label](https://img.shields.io/github/issues-raw/kenkit/neon_service/qt_app_crash)](https://github.com/kenkit/neon_service/issues?q=is%3Aissue+is%3Aopen+label%3Aqt_app_crash)
[![GitHub issues by-label](https://img.shields.io/github/issues-raw/kenkit/neon_service/neon_service_crash)](https://github.com/kenkit/neon_service/issues?q=is%3Aissue+is%3Aopen+label%3Aneon_service_crash)
[![GitHub issues by-label](https://img.shields.io/github/issues-raw/kenkit/neon_service/Investigating)](https://github.com/kenkit/neon_service/issues?q=is%3Aissue+is%3Aopen+label%3AInvestigating)
[![CMake](https://github.com/kenkit/neon_service/actions/workflows/cmake.yml/badge.svg)](https://github.com/kenkit/neon_service/actions/workflows/cmake.yml)

Neon Service was designed by DeadDevice Technologies and requires the installation of Neon.

## Features

-   Runs as a background service.
-   File download manager.
-   SUpports sharing credits.
-    ~~Search engine for files that can only be download/decrypted with neon (file names are mangled to avoid prying) ~~
-   Remote download manager.
-   ~~Google chrome plugin to grab new download links like idm.~~
-   Google drive plugin
-   Google drive upload encrypted files
-   Gadget recovery options for mobile devices supports(MTK) Work in progress(QLCM,SPD) .
-   Firmware Download|Upload-(Encryption|Decryption) from server
-   Supports automatic decompression of supported firmware files
-   Upload system shares your files to our global search engine
-   Working on SLA Bypass

## Installation

Install neon updater to get everything.

You might need visual studio redistributable 2015 for the installer will fix in next release of the installer

We are working on an automated updater

## Plugins

This project uses a number of plugins

-   Most of the features require installation of Neon to be able to access them
-   More work upcoming

## Development
Project is not opensource but things may change in the future.

Want to work with us ? Get in touch with me and we will see what we can do.

Project can only be built automatically by cl servers, source is not available

## Building for source

Check Developement

## Developers

[![KENKIT](https://www.codewars.com/users/kenkit/badges/large)](https://www.codewars.com/users/kenkit)


## Todos

-   Make the installer download plugins seperately

## License
```
/* Copyright (C) Neon Systems, Inc - All Rights Reserved
 * Unauthorized copying of this file, via any medium is strictly prohibited
 * Proprietary and Should only be installed using Neon
 * Written by Ken <webmaster@deaddevice.com>, May 2019
 */
```

## Software used in this project

   [CURL]()

   [ARIA2]()

   [CRYPTOPP]()

   [7zip-cpp]()

   [JSON]()

   [GOOGLETEST]()

   [FLATBUFFERS]()

   [YOUTUBEDL]()

   [CFSCRAPE]()

   [SIMPLEWEBSOCKETS]()

   [SPFLASHTOOL]()


