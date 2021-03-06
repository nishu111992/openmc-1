.. _notes_0.4.0:

==============================
Release Notes for OpenMC 0.4.0
==============================

-------------------
System Requirements
-------------------

There are no special requirements for running the OpenMC code. As of this
release, OpenMC has been tested on a variety of Linux distributions as well as
Mac OS X. However, it has not been tested yet on any releases of Microsoft
Windows. Memory requirements will vary depending on the size of the problem at
hand (mostly on the number of nuclides in the problem).

------------
New Features
------------

- The probability table method for treatment of energy self-shielding in the
  unresolved resonance range has been implemented and is now turned on by
  default.
- Calculation of Shannon entropy for assessing convergence of the fission source
  distribution.
- Ability to compile with the PGI Fortran compiler.
- Ability to run on IBM BlueGene/P machines.
- Completely rewrote how nested universes are handled. Geometry is now much more
  robust.

---------
Bug Fixes
---------

- Many geometry errors have been fixed. The Monte Carlo performance benchmark
  can now be successfully run in OpenMC.
