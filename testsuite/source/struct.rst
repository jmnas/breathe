
doxygenstruct Directive Example
===============================

Working Example
---------------

This should work::

   .. doxygenstruct:: CoordStruct
      :project: restypedef

It produces this output:

.. doxygenstruct:: CoordStruct
   :project: restypedef

Failing Example
---------------

This intentionally fails::

   .. doxygenstruct:: made_up_struct
      :project: restypedef

It produces the following warning message:

.. doxygenstruct:: made_up_struct
   :project: restypedef
