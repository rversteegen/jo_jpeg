# A jo_jpeg fork
A public domain, single file, extremely small (314 LoC excluding comments/space) JPEG encoder.
This is a fork of the original jo_jpeg 1.60 by Jon Olick (http://www.jonolick.com/code.html)

Changes from original jo_jpeg:
* Optional file output via callback function

Features:
* Supports 1, 3 or 4 component input (luminance, RGB or RGBX)
* No memory allocation
* MT safe
* Output baseline JPEG
* U,V subsampling at quality <= 90
* Fixed luminance, chrominance and Huffman tables for simplicity (and slightly worse compression)
