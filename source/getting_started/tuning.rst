Tuning your Software
====================

.. warning:: ARC-Docs is depricated and will no longer be updated. New version can be found at: :ref:`https://github.com/PSU-Research-Computing/psurc-docs.git`_


The optimal number of threads to use is entirely dependent on the program being run and may take a bit of trial and error. More threads does not usually result in faster runs and can actually be detrimental.

.. warning:: Please limit the number of threads to half of the currently available on the compute servers unless you have demonstrable evidence of increased performance with more threads.

Start small and increase the concurrency of your program.  Benchmarking will help you discover the optimal settings for your program.

.. warning:: More threads does NOT equal faster performance.  Play with the concurrency and thread settings and benchmark to find the sweet spot.
