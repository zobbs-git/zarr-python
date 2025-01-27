.. zarr documentation main file, created by
   sphinx-quickstart on Mon May  2 21:40:09 2016.

Zarr
====

Zarr is a format for the storage of chunked, compressed, N-dimensional arrays.
These documents describe the Zarr format and its Python implementation.

Highlights
----------

* Create N-dimensional arrays with any NumPy dtype.
* Chunk arrays along any dimension.
* Compress and/or filter chunks using any NumCodecs_ codec.
* Store arrays in memory, on disk, inside a Zip file, on S3, ...
* Read an array concurrently from multiple threads or processes.
* Write to an array concurrently from multiple threads or processes.
* Organize arrays into hierarchies via groups.

Status
------

Zarr is still a young project. Feedback and bug reports are very welcome, please get in touch via
the `GitHub issue tracker <https://github.com/zarr-developers/zarr-python/issues>`_. See
:doc:`contributing` for further information about contributing to Zarr.

Contents
--------

.. toctree::
    :maxdepth: 2

    installation
    tutorial
    api
    spec
    release
    contributing

Projects using Zarr
-------------------

If you are using Zarr, we would `love to hear about it
<https://github.com/zarr-developers/zarr-python/issues/228>`_.

Acknowledgments
---------------

The following people have contributed to the development of Zarr by contributing code,
documentation, code reviews, comments and/or ideas:

* :user:`Francesc Alted <FrancescAlted>`
* :user:`Martin Durant <martindurant>`
* :user:`Stephan Hoyer <shoyer>`
* :user:`John Kirkham <jakirkham>`
* :user:`Alistair Miles <alimanfoo>`
* :user:`Mamy Ratsimbazafy <mratsim>`
* :user:`Matthew Rocklin <mrocklin>`
* :user:`Vincent Schut <vincentschut>`
* :user:`Anthony Scopatz <scopatz>`
* :user:`Prakhar Goel <newt0311>`

Zarr is inspired by `HDF5 <https://www.hdfgroup.org/HDF5/>`_, `h5py
<https://www.h5py.org/>`_ and `bcolz <https://bcolz.readthedocs.io/>`_.

Development of Zarr is supported by the
`MRC Centre for Genomics and Global Health <https://www.cggh.org>`_.

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _NumCodecs: https://numcodecs.readthedocs.io/
