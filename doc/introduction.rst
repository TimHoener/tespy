.. _tespy_label:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
TESPy -  Thermal Engineering Systems in Python
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

TESPy stands for "Thermal Engineering Systems in Python" and provides a powerful simulation toolkit for thermal engineering plants such as power plants, district heating systems or heat pumps.
It is an external extension module within the `Open Energy Modeling Framework <https://oemof.org/>`_ and can be used as a standalone package.

With the TESPy package you are able to calculate stationary operation in order to design the process of your plant.
From that point it is possible to calculate the offdesign behaviour of your plant using underlying characteristics for each of the plants components.
For now, the package inlcudes basic components, such as turbines, pumps, compressors, heat exchangers, pipes, mixers and splitters as well as some advanced components (derivatives of heat exchangers, drum).

Everybody is welcome to use and/or develop TESPy. Contribution is already possible on a low level by simply fixing typos in TESPy's documentation or rephrasing sections which are unclear.
If you want to support us that way please fork the TESPy repository to your own github account and make changes as described in the github guidelines: https://guides.github.com/activities/hello-world/

.. contents::
    :depth: 1
    :local:
    :backlinks: top


Documentation
=============

You can find the full documentation at `readthedocs <http://tespy.readthedocs.org>`_. Use the `project site <http://readthedocs.org/projects/tespy>`_ of readthedocs to choose the version of the documentation.
Go to the `download page <http://readthedocs.org/projects/tespy/downloads/>`_ to download different versions and formats (pdf, html, epub) of the documentation. Currently, only the dev branch is available.

To get the latest news visit and follow our `website <https://www.oemof.org>`_.

Installing TESPy
================

If you have a working Python3 environment, use pypi to install the latest tespy version: Clone the github repository and then run:

.. code:: bash

    pip install tespy

We provide :ref:`more detailed installation instructions <installation_and_setup_label>`, too.

If you want to use the latest features, you might want to install the **developer version**. See section :ref:`Developing TESPy <developing_tespy_label>` for more information. The developer version is not recommended for productive use.

Examples
========

For a short introduction on how TESPy works and how you can use it, we provide some examples at the :ref:`examples section <tespy_examples_label>`.
On top of that, there is a :ref:`step-by-step tutorial <heat_pump_tutorial_label>` on how to model a heat pump in TESPy.

The :ref:`using TESPy section <using_tespy_introduction_label>` provides you with information on the basics (TESPy network, components, connections) and
more advanced subjects (TESPy's solver, design/offdesign calculation, custom components and subsystems, network export and import).

License
=======

Copyright (C) 2018 oemof developing group

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.