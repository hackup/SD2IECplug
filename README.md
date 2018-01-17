SD2IEC Pluggable
================

* KiCAD project files for my take on an [SD2IEC](http://www.pitsch.de/stuff/mmc2iec/) compatible board.
* The schematics are heavily based on the [design by Shadowolf](https://www.forum64.de/index.php?thread/21242-sd2iec-hardware-1-0/).
* The [BOM export](SD2IECplug-BOM.csv) is included in the repository. If you don't intend to use the TAPuino functionality (and there isn't any firmware support for this yet) you can omit R16-R21 and the optocoupler U3. Also, the board can be power either through the USB or the tape port connector so you don't necessarily need to fit both.
* There should probably more documentation here, but while it is still missing you may find some additional information in [this blog post](https://www.hackup.net/2017/12/sd2iec-revisited/).
