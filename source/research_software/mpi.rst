*************
MPI and MPICH
*************

.. warning:: ARC-Docs is depricated and will no longer be updated. New version can be found at: :ref:`https://github.com/PSU-Research-Computing/psurc-docs.git`_


System MPI
==========

Message passing has been installed on the research system, but has to be enabled using the module system.   Here are examples on how to do that if you need those::

  module load openmpi-x86_64
  module load mpich2-x86_64

These commands can be added to your ``.bashrc`` if you need them routinely or dynamically loaded from shell scripts that launch your MPI jobs.  You may be interested in running this on the :ref:`clusters`.

