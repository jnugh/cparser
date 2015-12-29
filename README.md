cparser - A C99 parser (with gnu extensions)
============================================

1. Introduction
---------------

cparser is a recursive descent C99 parser written in C99. It contains
preprocessor, lexer, parser, constructs an AST and does semantic analysis.  It
acts as a frontend to the libFirm intermediate representation, optimization and
code generation. It comes with typical compiler driver logic for parsing the
commandline to setup the environment and code generator and calling assemblers
and linkers. This allows it to be a drop-in replacement for gcc or clang in
many situations.

2. Building and Installation
----------------------------

Requirements:

* A C99 compiler (gcc and icc are known to work).
* libFirm-1.22

3. Further Information and Contact
----------------------------------

Official website: http://libfirm.org/

Contact E-Mail: firm@ipd.info.uni-karlsruhe.de

Mailing list: https://lists.sourceforge.net/lists/listinfo/libfirm-user

Bugtracker: http://pp.ipd.kit.edu/~firm/bugs

Internet relay chat: irc://chat.freenode.net/#firm
