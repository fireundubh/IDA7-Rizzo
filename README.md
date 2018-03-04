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

# Installation

Just copy `rizzo.py` into your IDA `plugins` directory.