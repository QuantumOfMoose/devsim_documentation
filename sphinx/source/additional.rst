.. include:: macros.txt

.. _ch__additional:

Additional Information
----------------------

.. _devsim__license:

DEVSIM License
~~~~~~~~~~~~~~


Individual files are covered by the license terms contained in the comments at the top of the file.  Contributions to this project are subject to the license terms of their authors.  In general, |devsim| is covered by the Apache License, Version 2.0 :cite:`apache2`.  Please see the ``NOTICE`` and ``LICENSE`` file for more information.


SYMDIFF
~~~~~~~

|symdiff| is available from |symdiffurl| under the terms of the Apache License, Version 2.0 :cite:`apache2`.


.. _thirdpartyavailability:

External Software Tools
~~~~~~~~~~~~~~~~~~~~~~~

.. _geniusAvailability:

Genius
^^^^^^

|genius| is available in commercial and open source versions from http://www.cogenda.com.

.. _gmshAvailability:

Gmsh
^^^^

|gmsh| :cite:`Gmsh:2009` is available from http://gmsh.info.

Paraview
^^^^^^^^

|paraview| is an open source visualization tool available at http://www.paraview.org.

..  Postmini
  ^^^^^^^^
  |postmini| is available from http://home.comcast.net/~john.faricelli/tcad.htm.

Tecplot
^^^^^^^

|tecplot| is a commercial visualization tool available from http://www.tecplot.com.

VisIt
^^^^^

|visit| is an open source visualization tool available from https://wci.llnl.gov/codes/visit/.


Library Availablilty
~~~~~~~~~~~~~~~~~~~~

The following tools are used to build |devsim|.

BLAS and LAPACK
^^^^^^^^^^^^^^^

These are the basic linear algebra routines used directly by |devsim| and by |superlu|. Reference versions are available from http://www.netlib.org.  There are optimized versions available from other vendors.

.. _additional__cgns:

CGNS
^^^^

|cgns| (CFD Generalized Notation System) is an open source library, which implements the storage format used to read |geniusds| meshes.  It is available from http://www.cgns.org.

.. _additional__python:

Python
^^^^^^

A |python|  distribution is required for using |devsim| and is distributed with many operating system.  Additional information is available at https://www.python.org.  It should be stressed that binary packages must be compatible with the |python| distribution used by |devsim|.

SQlite3
^^^^^^^

|sqlite| is an open source database engine used for the material database and is available from https://www.sqlite.org.

SuperLU
^^^^^^^

|superlu| :cite:`superlu99` is used within |devsim| and and is available from http://crd-legacy.lbl.gov/~xiaoye/SuperLU:

..

  Copyright (c) 2003, The Regents of the University of California, through
  Lawrence Berkeley National Laboratory (subject to receipt of any required
  approvals from U.S. Dept. of Energy)

  All rights reserved.

  Redistribution and use in source and binary forms, with or without modification,
  are permitted provided that the following conditions are met:

  (1) Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.
  (2) Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.
  (3) Neither the name of Lawrence Berkeley National Laboratory, U.S. Dept. of
  Energy nor the names of its contributors may be used to endorse or promote
  products derived from this software without specific prior written permission.

  THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
  IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
  IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
  PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR
  CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
  EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
  PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
  LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
  NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
  SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Tcl
^^^

|tcl| is the original parser for |devsim| and is superseded by |python|.  It is still used for some of the tests.  |tcl| is available from http://www.tcl.tk.

zlib
^^^^

|zlib| is an open source compression library available from https://zlib.net.

