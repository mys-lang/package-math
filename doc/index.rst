|discord|_
|test|_
|stars|_

About
=====

Basic math operations in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-math

Example
=======

.. code-block:: mys

   from math import PI
   from math import E
   from math import sin
   from math import cos
   from math import is_nan
   from math import sqrt

   def main():
       print("pi =         ", PI)
       print("e =          ", E)
       print("sin(0.0) =   ", sin(0.0))
       print("cos(0.0) =   ", cos(0.0))
       print("is_nan(0.0) =", is_nan(0.0))
       print("sqrt(4.0)   =", sqrt(4.0))

.. code-block:: myscon

   ❯ mys run
    ✔ Reading package configuration (0 seconds)
    ✔ Building (0.22 seconds)
   pi =          3.14159
   e =           2.71828
   sin(0.0) =    0
   cos(0.0) =    1
   is_nan(0.0) = False
   sqrt(4.0)   = 2

API
===

.. mysfile:: src/lib.mys

.. |discord| image:: https://img.shields.io/discord/777073391320170507?label=Discord&logo=discord&logoColor=white
.. _discord: https://discord.gg/GFDN7JvWKS

.. |test| image:: https://github.com/mys-lang/package-math/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-math/actions/workflows/pythonpackage.yml

.. |stars| image:: https://img.shields.io/github/stars/mys-lang/package-math?style=social
.. _stars: https://github.com/mys-lang/package-math

.. _Mys programming language: https://mys-lang.org
