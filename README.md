CSlossless_compression
======================

Lossless Compression algorithm for Comp490 Senior Design Cubesat project.

This is a modified version of V.Antonenko's lzw implementation that can be found at: https://code.google.com/p/clzw/. This version assumes that a file system is available. Instead of holding a large dictionary in RAM, this version of lzw stores the dictionary in a file.

### Note before using:
Make sure to remove the F_* and f_* types/functions. F_ and f_ are specific to the file system being used in this project.

This code is under the GPL v2 license. The license can be found under the LICENSE file in this repository.
