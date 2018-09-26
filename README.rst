=====================================
EPQuery - EnergyPlus IDF editing tool
=====================================

Description
===========

EPQuery is a tool for exploring and editing large IDF files. The tool helps to automate tedious
tasks, like adding new schedules or external interface objects. EPQuery supplies basic methods
for querying the model, selecting different objects and perform basic editing, but the user
can pass custom functions to be used on the selected objects. 

The project is in the pre-release stage.

Installation
============

Option 1:
::

    pip install epquery

Option 2: clone this repository and install using pip:

::

    git clone https://github.com/sdu-cfei/epquery.git epquery
    cd epquery
    pip install . 

Option 3:

::

    python -m pip install https://github.com/sdu-cfei/epquery/archive/master.zip


Documentation
=============

The documentation is hosted on GitHub Pages:  `https://sdu-cfei.github.io/epquery <https://sdu-cfei.github.io/epquery>`_

License
=======

Copyright (c) 2017, University of Southern Denmark. All rights reserved.

This code is licensed under BSD 2-clause license. See
`LICENSE </LICENSE>`__ file in the project root for license terms.
