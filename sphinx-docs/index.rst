.. dt-foundation documentation master file, created by
   sphinx-quickstart on Wed Oct  2 22:10:36 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

dt-foundation documentation
===========================

**dt-foundation** is a set of common utilities leverage by dt_tools packages (dt-console, dt-net, dt-pinger,...).  

These can also be incorporated into your project to facilitate logging and os interaction.

Includes:

.. list-table::
   :widths: 20 80
   :header-rows: 1

   * - Module
     - Description
   * - :mod:`~dt_tools.logger.logging_helper`
     - Standardize logger (loguru) initialization and properties.
   * - :mod:`~dt_tools.misc.helpers`
     - String helpers and Object helpers (dict2object, object2dict).
   * - :mod:`~dt_tools.os.os_helper`
     - OS routines for identifying and working with Linux and Windows.
   * - :mod:`~dt_tools.os.os_project_helper`
     - Routines identifying project distribution and file versions.


.. toctree::
   :maxdepth: 5
   :caption: Contents:

   dt_tools
