# hodea - Highly Optimized Deeply Embedded Auxiliaries

![logo](logo/hodea_logo.png)

---

## About HODEA

HODEA is the acronym for **H**ighly **O**ptimized **D**eeply
**E**mbedded **A**uxiliaries.
It the umbrella for source code libraries and template projects
for deeply embedded systems, and related tools supporting the engineering
process in this field of application.

## hodea-lib

This is a C++ source code library for deeply embedded, bare metal software.
It provides the infrastructure for software running on small 32 bit
microcontroller units (MCUs). It is compiled and linked together with the
application.

[Read more...](https://hodea.github.io/hodea-lib/)

## hodea-lib Wiki

The [Wiki](https://github.com/hodea/hodea-lib/wiki) provides some
information related to hodea-lib, in particular the development tools
used for the library.

## hodea-stm32f0-project-template

This project targets STM32F0 MCUs. It functions as template for own
projects based on hodea-lib. In addition it shows how to split the
firmware into bootloader and application.

[Read more...](https://hodea.github.io/hodea-stm32f0-project-template/)

## hodea-review-minder

The hodea-review-minder is a collection of python 3 scripts assisting code
reviews.

Issues found during a code review are directly written into the source
code as special C/C++ comment. The tool parses the source code, builds and
maintains a database file from the findings, and generates reports from it.

If an issue is solved it is marked as closed, or it is deleted from the
source code.

[Read more...](https://hodea.github.io/hodea-review-minder/)


## Source Code

The work is licensed under MIT. The source code is hosted on
on [github](https://github.com/hodea).
