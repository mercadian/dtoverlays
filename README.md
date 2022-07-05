# dtoverlays
A collection of Device Tree overlays used by Mercadian devices.

## Building
This requires the `device-tree-compiler` package to run.

To build a file, simply run the `dtc` command with typical parameters.
For example:

```
cd proteus
dtc -O dtb -o sta-led-overlay.dtbo -@ sta-led-overlay.dts
```
