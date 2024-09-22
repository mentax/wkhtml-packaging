# Binary (amd64) releases of wkhtmltopdf 0.12.6.1

The wkhtmltopdf project was archived at version 0.12.6.1, but I still use it
in my projects. This repo provides binary releases (both full .deb files
and just the wkhtmltopdf executable) through github actions for current (amd64)
versions of Debian and Ubuntu. This includes Ubuntu 24.04 (noble), which uses
g++ 13 by default and required some patching of the Qt configure script.

- Debian 12: bookworm
- Debian 11: bullseye
- Ubuntu 24.04: noble
- Ubuntu 22.04: jammy
- Ubuntu 20.04: focal

Warning: **Do not use wkhtmltopdf with any untrusted HTML**
