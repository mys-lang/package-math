Math
====

Basic math operations in the `Mys programming language`_.

Examples
========

.. code-block:: python

   from math import PI
   from math import E
   from math import sin
   from math import cos
   from math import is_nan
   from math import NAN

   def main():
       print('pi =         ', PI)
       print('e =          ', E)
       print('sin(0) =     ', sin(0))
       print('cos(0) =     ', cos(0))
       print('is_nan(nan) =', is_nan(NAN))

.. code-block:: text

   $ mys run
   pi =          3.14159
   e =           2.71828
   sin(0) =      0
   cos(0) =      1
   is_nan(nan) = True

.. _Mys programming language: https://github.com/mys-lang/mys
