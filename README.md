[![Build Status](https://travis-ci.org/project-koku/koku-doc.svg?branch=master)](https://travis-ci.org/project-koku/koku-doc)

# Koku-doc README

About
=====
Koku's goal is to provide an open source solution for cost management of cloud and hybrid cloud environments. This is offered via a web interface that exposes resource consumption and cost data in easily digestible and filterable views. The project also aims to provide insight into this data and ultimately provide suggested optimizations for reducing cost and eliminating unnecessary resource usage.

Getting Started
===============

Writing Documentation
---------------------
Add associated asciidoc files.

Building Documentation
----------------------

Download the asciidoctor container.
```
docker pull opennms/asciibinder
```

Execute asciibinder.
```
docker run --rm -v $(pwd):/docs opennms/asciibinder build
```

View resulting HTML files in `_preview/ascii_binder/latests` directory.


Contributing
=============
Thank you for your interest in contributing to this project!

Please see [CONTRIBUTING](./CONTRIBUTING.md) for more details.
