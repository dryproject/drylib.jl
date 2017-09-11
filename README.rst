****************
DRYlib for Julia
****************

.. image:: https://img.shields.io/badge/license-Public%20Domain-blue.svg
   :alt: Project license
   :target: https://unlicense.org/

.. image:: https://img.shields.io/travis/dryproject/drylib.jl/master.svg
   :alt: Travis CI build status
   :target: https://travis-ci.org/dryproject/drylib.jl

|

http://drylib.org

Prerequisites
=============

* `Julia <https://en.wikipedia.org/wiki/Julia_(programming_language)>`__
  0.6+

Features
========

Caveats
=======

Installation
============

::

   julia> Pkg.clone("https://github.com/dryproject/DRYlib.jl.git")

Usage
=====

::

   julia> using DRYlib
   julia> const DRY = DRYlib

Reference
=========

``core``
--------

=============== ================================================================
DRY Symbol      Julia Symbol
=============== ================================================================
``bool``        ``DRY.Bool`` (type alias for ``Core.Bool``)
``char``        ``DRY.Char`` (type alias for ``Core.Char``)
``complex``     ``DRY.Complex`` (type alias for ``Base.Complex{Base.MPFR.BigFloat}``)
``float``       ``DRY.Float`` (type alias for ``Core.Float64``)
``float32``     ``DRY.Float32`` (type alias for ``Core.Float32``)
``float64``     ``DRY.Float64`` (type alias for ``Core.Float64``)
``int``         ``DRY.Int`` (type alias for ``Core.Int64`` or ``Int32``)
``int8``        ``DRY.Int8`` (type alias for ``Core.Int8``)
``int16``       ``DRY.Int16`` (type alias for ``Core.Int16``)
``int32``       ``DRY.Int32`` (type alias for ``Core.Int32``)
``int64``       ``DRY.Int64`` (type alias for ``Core.Int64``)
``int128``      ``DRY.Int128`` (type alias for ``Core.Int128``)
``integer``     ``DRY.Integer`` (type alias for ``Base.GMP.BigInt``)
``natural``     ``DRY.Natural`` (type alias for ``DRY.Integer``)
``rational``    ``DRY.Rational`` (type alias for ``Base.Rational{Base.GMP.BigInt}``)
``real``        ``DRY.Real`` (type alias for ``Base.MPFR.BigFloat``)
``word``        ``DRY.Word`` (type alias for ``Core.UInt64`` or ``UInt32``)
``word8``       ``DRY.Word8`` (type alias for ``Core.UInt8``)
``word16``      ``DRY.Word16`` (type alias for ``Core.UInt16``)
``word32``      ``DRY.Word32`` (type alias for ``Core.UInt32``)
``word64``      ``DRY.Word64`` (type alias for ``Core.UInt64``)
=============== ================================================================
