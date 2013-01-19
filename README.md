# emacs-doxygen

This package provides basic support for adding
[Doxygen](http://www.doxygen.org/) comments to C++ code. I wrote this over a
decade ago while working at [Basis Technology](http://www.basistech.com/) and
they have graciously given their permission to release it under an open source
license.

At the time it was written `doxygen.el` was the only Emacs package to help
with Doxygen, but over the years a couple of others have come into existance,
including [epydoc-el](http://code.google.com/p/epydoc-el) (which is based on
this!) and [Doxymacs](http://doxymacs.sourceforge.net).

There is a chance I'll extended this further, but for now it scratches the
itch I have (the code works fine in Emacs 24) so who knows?

## Installation

Put

    (require 'doxygen)
    
in your `~/.emacs` or `~/.emacs.d/init.el`. 

## License

Copyright (c) 2000-2001 Basis Technology, Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
