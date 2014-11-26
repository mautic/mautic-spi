# [Mautic](https://www.mautic.org/) Single Page Installer

## What it does

Mautic SPI is single PHP file, which can download latest Mautic ZIP package from [Mautic.org](https://www.mautic.org/) and unzip it on the server. Current unzipped Matuic files has 73 MB and over 10 000 files. It can take few hours to upload to your server via FTP (depends on your internet connection). Mautic SPI script communicates directly between servers. To download and unzip Mautic on your server takes few seconds.

## How to use it

1. Download files of this repo by clicking "Download ZIP" button on right bottom corner of this ([GitHub](https://github.com/mautic/mautic-spi)) page.
2. Unzip downloaded package somewhere on your computer.
3. Upload start.php (via FTP problably) to the folder on your server wher you want Mautic to be installed.
4. Go to the URL where Mautic will be and add start.php behind the last slash. Example: http://mautic.myweb.com/start.php

This installer is based on [Joomla SPI](https://github.com/dbhurley/joomla-spi) by David Hurley.
