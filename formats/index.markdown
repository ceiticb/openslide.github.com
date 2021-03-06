---
layout: default
title: Virtual slide formats understood by OpenSlide
---

{% include links.markdown %}

OpenSlide's support for these formats is not endorsed by their respective
vendors and may be incomplete.  Problems should be reported to the OpenSlide
[mailing list][users-subscribe] or [issue tracker][c-issues].


Aperio
------

Single-file pyramidal tiled TIFF, with non-standard metadata and compression.

File extensions
:`.svs`, `.tif`

OpenSlide vendor backend
:`aperio`

OpenSlide ops backend
:`tiff`

More info
:[Aperio format][format-aperio]


Hamamatsu
---------

Multi-file JPEG/NGR with proprietary metadata and index file formats.

File extensions
:`.vms`, `.vmu`

OpenSlide vendor backend
:`hamamatsu`

OpenSlide ops backend
:`jpeg` for `.vms`, `ngr` for `.vmu`

More info
:[Hamamatsu format][format-hamamatsu]


Leica
-----

Single-file pyramidal tiled BigTIFF with non-standard metadata.

File extensions
:`.scn`

OpenSlide vendor backend
:`leica`

OpenSlide ops backend
:`tiff`

More info
:[Leica format][format-leica]


MIRAX
-----

Multi-file JPEG with very complicated proprietary metadata and indexes.

File extensions
:`.mrxs`

OpenSlide vendor backend
:`mirax`

OpenSlide ops backend
:`jpeg`

More info
:[MIRAX format][format-mirax]


Trestle
-------
Single-file pyramidal tiled TIFF, with non-standard metadata and
overlaps. Additional files can contain more metadata and detailed
overlap info.

File extensions
:`.tif`

OpenSlide vendor backend
:`trestle`

OpenSlide ops backend
:`tiff`

More info
:[Trestle format][format-trestle]


Generic tiled TIFF
------------------

Single-file pyramidal tiled TIFF.

File extensions
:`.tif`

OpenSlide vendor backend
:`generic-tiff`

OpenSlide ops backend
:`tiff`

More info
:[Generic tiled TIFF format][format-generic-tiff]
