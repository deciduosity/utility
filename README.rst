============================================
``utility`` -- Common Golang Utility Library
============================================

Overview
--------

This package contains a collection of common utility functions collected and
isolated from projects ``util`` (or "misc") packages.

Key Features
------------

- HTTP Client pooling.

- Reading and writing structured data to a file.

- Convince functions for rounding time values to predictable intervals.

- Slice manipulation and introspection functions for inspecting common string
  types.

Use and Development
-------------------

The utility package is available under the terms of the Apache License (v2).

All dependencies are managed by go module. The main dependencies are grip,
for logging and `rehttp <https://github.com/PuerkitoBio/rehttp>`_ which
provides automatic retry logic for HTTP requests, though the rehttp dependency
is isolated from callers.

All documentation is available on the `godoc
<https://godoc.org/github.com/deciduosity/utility>`_.

Feel free to open issues or submit pull requests!
