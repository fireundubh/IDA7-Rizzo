IDA7-Rizzo
==========

Original plugin developed by devttys0, ported to IDA 7.0

# Features

Identifies and re-names functions between two or more IDBs based on:

* Formal signatures (i.e., exact function signatures)
* References to unique string
* References to unique constants
* Fuzzy signatures (i.e., similar function signatures)
* Call graphs (e.g., identification by association)

# Usage

To generate signatures for functions in your current IDB:

![Generating Rizzo signatures](../../images/rizzo_generate.png)

To apply generated signatures to your current IDB:

![Applying Rizzo signatures](../../images/rizzo_apply.png)

Some pre-generated signatures can be found in [the original repo](https://github.com/devttys0/ida/tree/master/plugins/rizzo).

# Installation

Just copy `rizzo.py` into your IDA `plugins` directory.