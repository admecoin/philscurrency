Philscurrency Core
===============================


https://www.philscurrency.org

Copyright (c) 2009-2015 Bitcoin Core Developers

Copyright (c) 2011-2015 Litecoin Core Developers

Copyright (c) 2014-2016 Dash Core Developers

Copyright (c) 2015-2017 Philscurrency Developers


What is Philscurrency?
----------------

Philscurrency is an experimental new digital currency that enables anonymous, instant
payments to anyone, anywhere in the world. Philscurrency uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network. Philscurrency Core is the name of open
source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Philscurrency Core software, see https://www.philscurrency.org


License
-------

Philscurrency Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Philscurrency
development team members simply pulls it.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see [doc/coding.md](doc/coding.md)) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/philscurrency/philscurrency/tags) are created
regularly to indicate new official, stable release versions of Philscurrency.


**compiling for debugging**

Run configure with the --enable-debug option, then make. Or run configure with
CXXFLAGS="-g -ggdb -O0" or whatever debug flags you need.

**debug.log**

If the code is behaving strangely, take a look in the debug.log file in the data directory;
error and debugging messages are written there.

The -debug=... command-line option controls debugging; running with just -debug will turn
on all categories (and give you a very large debug.log file).

The Qt code routes qDebug() output to debug.log under category "qt": run with -debug=qt
to see it.
#### Bitcoin donations welcome: 3BJbCUdJ8mhZn9B2Ncz1JBBEbe1R8816AW
#### Litcoin donations welcome: MQRLB7gYHBAZuY8erwbMTguG24CBAwgwo4
#### Dash coin donations welcome: XsXNddLuVLc1b1Q2DDqniSvwYbpq7F2BLe
