===================
pandoc-refheadstyle
===================

----------------------------------------------------
Sets a custom style for the reference section header
----------------------------------------------------

:Author: Odin Kroeger
:Date: April 22, 2018
:Version: 0.1.0
:Manual section: 1


SYNOPSIS
========

pandoc-refheadstyle [-h]


DESCRIPTION
===========

``pandoc-refheadstyle`` sets a custom style for the reference section header,
but only if the metadata field ``reference-section-title`` has been set to a
non-empty value.

By default, the reference section header will be assigned the custom style
'Bibliography Heading'. But you can change what style is assigned by setting
the metadata field ``reference-header-style`` to the name of a style of
your choice. If the style does not exist, it will be created.

``pandoc-refheadstyle`` considers any header the reference section header that
is a top-level header, close to the end of the document and has a header text
that is equal to the value of the metadata field ``reference-section-title``.


LICENSE
=======

Copyright 2018 Odin Kroeger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


FURTHER INFORMATION
===================

* <https://github.com/odkr/pandoc-refheadstyle>
* <https://pypi.org/project/pandoc-refheadstyle>


SEE ALSO
========

pandoc(1), pandoc-citeproc(1)
