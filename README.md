Install
=======

1. Check out the repository with Git, or use the "Download Source" link on the
Github homepage.

2. Copy the files into `~/.vim/`.  You should end up with a structure like:

   * ~/.vim

     + compiler/

       * xmllint_sld.vim

     + xsd/

       * filter/

       * gml/

       * sld/

       * xlink/

Usage
=====

In vim, open an SLD file as normal.  Use `:compiler xmllint_sld` to activate
the compiler plugin, then `:make %` to get a validation report in vim's
compiler error list.

Further Reading
===============

* [Compiler Plugins](http://vimdoc.sourceforge.net/htmldoc/usr_41.html#41.13)

* [vim Quickfix Window](http://vimdoc.sourceforge.net/htmldoc/quickfix.html)
