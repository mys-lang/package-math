|buildstatus|_

Math
====

Basic math operations in the `Mys programming language`_.

Examples
========

.. code-block:: python

   from math import pi
   from math import e
   from math import sin
   from math import cos
   from math import is_nan
   from math import nan

   def main():
       print('pi =         ', pi)
       print('e =          ', e)
       print('sin(0) =     ', sin(0))
       print('cos(0) =     ', cos(0))
       print('is_nan(nan) =', is_nan(nan))

.. code-block:: text

   $ mys run
   pi =          3.14159
   e =           2.71828
   sin(0) =      0
   cos(0) =      1
   is_nan(nan) = True

.. |buildstatus| image:: https://travis-ci.com/eerimoq/mys-math.svg?branch=master
.. _buildstatus: https://travis-ci.com/eerimoq/mys-math

.. _Mys programming language: https://github.com/eerimoq/mys
