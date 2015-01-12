=====================================================
NetCDF Climate and Forecast (CF) Metadata Conventions
=====================================================

Version 1.7.1 DRAFT , 20 November, 2013
---------------------------------------

### Original authors

  - Brian Eaton, NCAR
  - Jonathan Gregory, Hadley Centre, UK Met Office
  - Bob Drach, PCMDI, LLNL
  - Karl Taylor, PCMDI, LLNL
  - Steve Hankin, PMEL, NOAA

### Additional authors:
  - John Caron, UCAR
  - Rich Signell, USGS
  - Phil Bentley, Hadley Centre, UK Met Office
  - Greg Rappa, MIT
  - Heinke Höck, DKRZ
  - Alison Pamment, BADC
  - Martin Juckes, BADC
  - Andrew Walsh, METOC

Many others have contributed to the development of CF through their
participation in discussions about proposed changes.

Abstract
--------

This document describes the CF conventions for climate and forecast
metadata designed to promote the processing and sharing of files
created with the netCDF [netCDF](#netCDF) Application Programmer Interface [NetCDF].
The conventions define metadata that provide a definitive description
of what the data in each variable represents, and of the spatial and
temporal properties of the data. This enables users of data from
different sources to decide which quantities are comparable, and
facilitates building applications with powerful extraction,
regridding, and display capabilities.

Link to [Appendix C](appendix-c.md),
and [an anchor](appendix-c.md#table-c1-standard-name-modifiers).

The CF conventions generalize and extend the COARDS conventions [
COARDS ]. The extensions include metadata that provides a precise
definition of each variable via specification of a standard name,
describes the vertical locations corresponding to dimensionless
vertical coordinate values, and provides the spatial coordinates of
non-rectilinear gridded data. Since climate and forecast data are
often not simply representative of points in space/time, other
extensions provide for the description of coordinate intervals,
multidimensional cells and climatological time coordinates, and
indicate how a data value is representative of an interval or cell.
This standard also relaxes the COARDS constraints on dimension order
and specifies methods for reducing the size of datasets.


**Table of Contents**

.. toctree::
   :maxdepth: 2

   pr01

.. toctree::
   :maxdepth: 2
   :numbered:

   ch01
   ch02

.. toctree::

   appendix-g
   bibliography

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

<a name="netCDF"></a> This is a footnote.
[NetCDF]: http://www.unidata.ucar.edu/netcdf/index.html "UNIDATA Program Center of the University Corporation for Atmospheric Research."
