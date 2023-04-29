Droidian for Samsung A5 2017
============================

Droidian is a GNU/Linux distribution based on top of Mobian, a Debian-based distribution for mobile devices. The goal of Droidian is to be able to run Mobian on Android phones.


# Recovery-flashable zipfile: installation instructions

## Installation

### First

Download Droidian Image [here](https://github.com/Exynos7880-Linux/droidian-images-samsung-a5y17lte/releases/)

From recovery open adb sideload mode (under advanced on TWRP) and run following commands on your computer replacing `YYYYMMDD` with the date of the Image:

* `adb sideload droidian-UNOFFICIAL-phosh-phone-samsung_a5y17lte-api29-arm64-nightly_YYYYMMDD.zip`

### Second

Download the adaptation bundle: [adaptation-droidian-a5y17lte.zip](https://github.com/Exynos7880-Linux/adaptation-samsung-a5y17lte/releases/download/adaptation/adaptation-droidian-a5y17lte.zip)

* `adb sideload adaptation-droidian-a5y17lte.zip`

Note that you have to restart the sideload mode by tapping back and starting sideload again before every `adb sideload command`.

## Finalizing installation

Now, you have to reboot the device. It should boot to phosh (a graphical user interface used by Droidian) after rebooting once more automatically. When the device has booted, you can unlock the device with the default passcode `1234`.

