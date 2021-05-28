General information
===================
@Sebastian

:Authors: `Sebastian D. Lumpp`_, `Michel Zadé`_, `Markus Doepfert`_
:Organization: `Chair of Energy Economy and Application Technology`_, Technical University of Munich
:Version: 1.0
:Date: 10.05.2021
:Copyright: The model code is licensed under the `GNU General Public License 3.0`_.
            This documentation is licensed under a `Creative Commons Attribution 4.0 International`_ license.

Features
--------
* list features of lemlab, which are also specified in the readme

Changes
-------
So far no new versions have been published.

Dependencies
------------
* `Python`_ version 3.8 or greater are supported
* `pyomo`_ for model equations and as the interface to optimisation solvers
  (CPLEX, GLPK, Gurobi, ...). Version 4 recommended, as version 3 support
  (a.k.a. as coopr.pyomo) will be dropped soon.
* Any solver supported by pyomo; suggestion: `gurobi`_ or `cplex`_


.. _Sebastian D. Lumpp: sebastian.lumpp@tum.de
.. _Michel Zadé: michel.zade@tum.de
.. _Markus Doepfert: markus.doepfert@tum.de
.. _Chair of Energy Economy and Application Technology: https://www.ei.tum.de/en/ewk/
.. _GNU General Public License 3.0: https://www.gnu.org/licenses/gpl-3.0
.. _Creative Commons Attribution 4.0 International: https://creativecommons.org/licenses/by/4.0/
.. _Python: https://www.python.org/
.. _pyomo: https://www.pyomo.org
.. _gurobi: https://www.gurobi.com/
.. _cplex: https://www.ibm.com/analytics/cplex-optimizer