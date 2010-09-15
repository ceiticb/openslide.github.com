OpenSlide Java version 0.9.2, 2010-08-10
========================================
Version 0.9.2 of the Java bindings removes some experimental CMU-specific annotation support.

OpenSlide Java version 0.9.1, 2010-06-16
========================================
Version 0.9.1 of the Java bindings fixes a Windows build bug and removes checks for negative coordinates and zero dimensions.

OpenSlide version 3.2.2, 2010-06-16
===================================
Version 3.2.2 has been released, adding support for negative coordinates and zero-sized dimensions in openslide_read_region, fixing a Windows build bug with new NGR support, and adding untested BigTIFF support.

OpenSlide version 3.2.1, 2010-06-03
===================================
Version 3.2.1 has been released, fixing Windows crashes, quieting down the error logging, and fixing problems with libjpeg 7.

OpenSlide Java version 0.9.0, 2010-06-01
========================================
Version 0.9.0 of the Java bindings adds support for the error handling system, eliminates the swig dependency, and adds new methods for painting.

OpenSlide version 3.2.0, 2010-06-01
===================================
Version 3.2.0 has been released, adding experimental CMake support and fixes for building with MSVC, an error handling mechanism, initial Hamamatsu Nanozoomer VMU support, and the "openslide-write-png" tool.

OpenSlide version 3.1.1, 2010-04-27
===================================
Version 3.1.1 has been released, fixing some bugs reading invalid VMS files. VMS files with multiple layers (NoLayers > 1) are also supported now, but the additional layers are ignored.

OpenSlide version 3.1.0, 2010-04-01
===================================
Version 3.1.0 has been released, which fixes problems with some TIFF files and adds support for certain newer Aperio files (compression 33005).

OpenSlide version 3.0.3, 2010-03-01
===================================
Version 3.0.3 has been released, which fixes nasty artifacts in some MIRAX files seen at some zoom levels.

OpenSlide version 3.0.2, 2010-02-17
===================================
Version 3.0.2 has been released, which restores the ability to build with glib 2.12, at the expense of not having "quickhash-1" in that configuration.

OpenSlide version 3.0.1, 2010-02-04
===================================
Version 3.0.1 has been released, with a fix for drawing the edges of TIFF files.

OpenSlide Java version 0.8.0, 2010-01-28
========================================
Version 0.8.0 of the Java bindings changes the license to LGPLv2, fixes some bugs, adds a new selection type, and adds a call to paint a specific layer without scaling.

OpenSlide version 3.0.0, 2010-01-28
===================================
Version 3.0.0 has been released, with a license change to LGPLv2, introduction of "quickhash-1", MIRAX bug fixes, and documentation improvements.