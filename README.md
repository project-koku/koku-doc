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
docker pull asciidoctor/docker-asciidoctor
```

Create an output directory.
```
mkdir -p output
```

Execute asciidoctor.
```
docker run -v ${PWD}:/documents/ --name asciidoc-to-html asciidoctor/docker-asciidoctor asciidoctor -D /documents/output **/*.adoc
```

View resulting HTML files in _output_ directory.


Contributing
=============
Thank you for your interest in contributing to this project!

Please see [CONTRIBUTING](./CONTRIBUTING.md) for more details.
