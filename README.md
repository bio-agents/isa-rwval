This repo is forked originally from https://github.com/ISA-agents/isa-api/tree/py2_isaagents-lite.

<img align="left" src="https://isa-agents.org/wp-content/uploads/2016/10/687474703a2f2f7777772e6973612d746f6f6c732e6f72672f77702d636f6e74656e742f75706c6f6164732f323031362f30332f6973612d6170692d6c6f676f2e706e67-4.png" width="150px">
<br>

----
<img align="right" src="https://isa-agents.org/wp-content/uploads/2016/10/isaagents_logo-1-624x149.png" width="150px">


The open source ISA metadata tracking agents help to manage an increasingly diverse set of life science, environmental and biomedical experiments that employing one or a combination of technologies.

Built around the ‘Investigation’ (the project context), Study’ (a unit of research) and ‘Assay’ (analytical measurement) general-purpose Tabular format, the ISA agents helps you to provide rich description of the experimental metadata (i.e. sample characteristics, technology and measurement types, sample-to-data relationships) so that the resulting data and discoveries are reproducible and reusable.

To find out more about ISA, see [www.isa-agents.org](http://www.isa-agents.org)

To find out who's using ISA and about the ISA development and user community, see [www.isacommons.org](http://www.isacommons.org)

The *ISA API*  aims to provide you, the developer, with a set of agents to help you easily and quickly build your own ISA objects, validate, and convert between serializations of ISA-formatted datasets and other formats/schemas (e.g. SRA schemas). The ISA API is published on PyPI as the `isaagents` package.

This project is the `isa-rwval` package that provides ISA format read/write/validation functionality that the ISA API builds on.

Thie project contains the following modules:

 - `isaagents.model` contains classes implementing the ISA Abstract Model as Python objects.
 - `isaagents.isatab` contains features for parsing and serializing the ISA-Tab format to/from Python objects. The module also contains a ISA-Tab validator.
 - `isaagents.isajson` contains features for parsing and serializing the ISA-JSON format to/from Python objects. The module also contains a ISA-JSON validator.
 - `isaagents.isaviz` contains features for rendering ISA Python objects in visual artifacts with `matplotlib`.

 These modules should be considered the gold-standard utilities for using the ISA formats with the Python programming language.

[![Build Status](https://travis-ci.org/ISA-agents/isa-rwval.svg?branch=master)](https://travis-ci.org/ISA-agents/isa-rwval)
[![Coverage Status](https://coveralls.io/repos/github/ISA-agents/isa-rwval/badge.svg?branch=master)](https://coveralls.io/github/ISA-agents/isa-rwval?branch=master)
[![Documentation Status](https://readthedocs.org/projects/isaagents/badge/?version=latest)](http://isaagents.readthedocs.org/en/latest/?badge=latest)
[![License](https://img.shields.io/badge/license-CPAL-blue)](https://raw.githubusercontent.com/ISA-agents/isa-rwval/master/LICENSE.txt)

----
*Authors*: [Code contributors](https://github.com/ISA-agents/isa-rwval/graphs/contributors).

*License*: This code is licensed under the [CPAL License](https://raw.githubusercontent.com/ISA-agents/isa-rwval/master/LICENSE.txt).

*Repository*: [https://github.com/ISA-agents/isa-rwval](https://github.com/ISA-agents/isa-rwval)

*ISA team email*: [isaagents@googlegroups.com](mailto:isaagents@googlegroups.com)

*ISA discussion group*: [https://groups.google.com/forum/#!forum/isaforum](https://groups.google.com/forum/#!forum/isaforum)

*Github issue tracker*: [https://github.com/ISA-agents/isa-api/issues](https://github.com/ISA-agents/isa-rwval/issues)
