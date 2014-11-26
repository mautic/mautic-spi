# [Mautic](https://www.mautic.org/) Single Page Installer

Mautic SPI is single PHP script, which can download latest Mautic ZIP package from [Mautic.org](https://www.mautic.org/) and unzip it to the same folder the script is. 

## Why to use Mautic SPI

Current unzipped Matuic core files has 73 MB and over 10 000 files. It can take few hours to upload so many files to your server via FTP (depends on your internet connection). Mautic SPI script communicates directly between servers. To download and unzip Mautic on your server with Mautic SPI takes just about few seconds.

## How to use it

1. Download this repo by clicking "Download ZIP" button on right bottom corner of [this](https://github.com/mautic/mautic-spi) page.
2. Unzip downloaded package somewhere on your computer.
3. Upload unzipped start.php (via FTP problably) to the folder on your server where you want Mautic to be installed.
4. Go to the URL where Mautic will run and add start.php behind the last slash. Example: `http://mautic.myweb.com/start.php`.

This installer is based on [Joomla SPI](https://github.com/dbhurley/joomla-spi) by David Hurley.
