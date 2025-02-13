libwdi: A Windows Driver Installation library for USB devices
=============================================================

[![Build status](https://img.shields.io/github/actions/workflow/status/pbatard/libwdi/vs2022.yml?style=flat-square&label=VS2022)](https://github.com/pbatard/libwdi/actions/workflows/vs2022.yml)
[![Build status](https://img.shields.io/github/actions/workflow/status/pbatard/libwdi/mingw.yml?style=flat-square&label=MinGW)](https://github.com/pbatard/libwdi/actions/workflows/mingw.yml)
[![Coverity Scan Build Status](https://img.shields.io/coverity/scan/2174.svg?style=flat-square&label=Coverity)](https://scan.coverity.com/projects/pbatard-libwdi)
[![Github stats](https://img.shields.io/github/downloads/pbatard/libwdi/total.svg?style=flat-square&label=Downloads)](https://github.com/pbatard/libwdi/releases)
[![Licence](https://img.shields.io/badge/license-LGPLv3-blue.svg?style=flat-square&label=License)](https://www.gnu.org/licenses/lgpl-3.0.en.html)

Main features
-------------

* Automated inf creation, using reported USB device name
* Automated catalog file creation and signing, using autogenerated certificate
* Automated driver files extraction, for both 32 and 64 bit platforms
* Automated driver installation, including UAC elevation where necessary
* Single library embedding all the required files
* Supports Windows platform from Windows 7 to Windows 11

Additional features
-------------------

* Embedding of WinUSB, libusb0.sys or libusbK.sys, USB Serial (CDC) or your own 
  USB drivers (eg. WHQL)
* Full locale support with UTF-8 API strings and UTF-16 autogenerated inf files
* Resolution of USB Vendor IDs, based on the data maintained by Stephen J. Gowdy 
  at http://www.linux-usb.org/usb.ids
* Fully Open Source (LGPL v3), with multiple sample applications
* Supports MinGW32, MinGW-w64, Visual Studio, WDK

Installation and Compilation
----------------------------

See: https://github.com/pbatard/libwdi/wiki/Install

API usage
---------

See: https://github.com/pbatard/libwdi/wiki/Usage

FAQ
---

See: https://github.com/pbatard/libwdi/wiki/FAQ
