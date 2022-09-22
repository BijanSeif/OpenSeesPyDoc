.. OpenSeesPy documentation master file, created by
   sphinx-quickstart on Tue Sep 26 12:56:27 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. include:: src/sub.txt

.. important::

   Version |opspy_version| is released!

   Python |python_version| is required for Windows.

   OpenSeesPy is on :doc:`src/pypi`.

   The latest version of this document can be found at
   `<https://openseespydoc.readthedocs.io/en/latest/>`_.

.. note::

   Questions including modeling issues and the use of OpenSeesPy,
   please post on `OpenSeesPy Forum <https://opensees.berkeley.edu/community/viewforum.php?f=12>`_.

   You are very welcome to contribute to OpenSeesPy with new command
   documents and examples
   by sending pull requests
   through `github pulls <https://github.com/zhuminjie/OpenSeesPyDoc/pulls>`_.

   For errors in this document, submit on 
   `github issues <https://github.com/zhuminjie/OpenSeesPyDoc/issues>`_.


========================
 The OpenSeesPy Library
========================
`OpenSeesPy`_ is a `Python 3`_ interpreter of `OpenSees`_.
A minimum script is shown below:

::

   # import OpenSeesPy
   import openseespy.opensees as ops

   # wipe model
   ops.wipe()

   # create model
   ops.model('basic', '-ndm', 2, '-ndf', 3)

   # print model
   ops.printModel()

============
 Developer
============

*Minjie Zhu*

| Research Associate 
| Civil and Construction Engineering
| Oregon State University

   
.. toctree::
   :maxdepth: 1
   :numbered:
   :caption: Contents
      
   src/installation
   src/compile
   src/changelog
   src/modelcmds
   src/analysiscmds
   src/outputcmds
   src/utilitycmds
   src/fsicmds
   src/senscmds
   src/reliabilitycmds
   src/parallelcmds
   src/preprocessing
   src/postprocessing
   src/examples


   

.. raw:: html

   <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=70&t=n&d=SKQBbxa32RopNU9415W5PDNgdO0XjXnxv2wJdeH0CHw'></script>
