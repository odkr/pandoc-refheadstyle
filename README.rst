=======================
pandoc-reference-header
=======================

``pandoc-reference-header`` is a filter for `pandoc <http://pandoc.org/>`_
that changes the style of the reference section header, provided one was
inserted by ``pandoc-citeproc``. By default, it uses the style "Bibliography
Heading", but you can define a custome styleby setting the metadata field
``reference-header-style``.

See the `manual page <man/pandoc-reference-header.rst>`_ for more details.


Installing ``pandoc-reference-header``
======================================

You use ``pandoc-reference-header`` **at your own risk**. You have been warned.

You need `Python 2.7 <https://www.python.org/>`_ or newer and
`panflute <https://github.com/sergiocorreia/panflute>`_.

Simply run::

    pip install pandoc_reference_header

This will try to install ``pandoc-reference-header`` manual page, but this
will only work on a limited number of systems.

Alternatively, you can also download the source for the `current version
<https://codeload.github.com/odkr/pandoc-reference-header/tar.gz/v0.1.0>`_.

Simlpy run::

    curl https://codeload.github.com/odkr/pandoc-reference-header/tar.gz/v0.1.0 | tar -xz
    cd pandoc-reference-header-0.6.0
    python setup.py install


Documentation
=============

See the `manual page <man/pandoc-reference-header.rst>`_
and the source for details.


Contact
=======

If there's something wrong with ``pandoc-reference-header``, `open an issue
<https://github.com/odkr/pandoc-reference-header/issues>`_.


License
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


Further Information
===================

GitHub:
<https://github.com/odkr/pandoc-reference-header>

PyPI:
<https://pypi.org/project/pandoc-reference-header>
