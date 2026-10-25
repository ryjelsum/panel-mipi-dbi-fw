# panel-mipi-dbi

Tool to make firmware files for the Linux SPI display driver [panel-mipi-dbi](https://github.com/torvalds/linux/blob/master/drivers/gpu/drm/tiny/panel-mipi-dbi.c).

This repository also contains firmware files for selected displays, as well as their source files with informative comments, if possible. 

The generator can convert back and forth between the input and output formats, so it is not essential to provide both, but more information is preferred, such as the source for the initialization sequence (stock DTS, etc). 

See wiki for more information: https://github.com/notro/panel-mipi-dbi/wiki
