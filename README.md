NOWSCI Anroid ROM
=================

Mostly stock AOSP ROM with slight alterations, mostly focused on privacy.

Downloading
-----------
To download a precompiled ROM, look in the folder for your device, and download the ZIP. Flash with your custom recovery (we recommend TWRP due to it's encryption support). Be sure to wipe caches.

Compiling yourself
------------------
Follow the [standard AOSP compilation process](http://source.android.com/source/building.html) but instead of running:

```
repo init
```

run:

```
repo init -u https://github.com/nowsci/platform_manifest -b L
```


