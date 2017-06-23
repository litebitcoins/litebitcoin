# LBTC
================================
What is LiteBitcoin?
================================

LiteBitcoin / LBTC :- 
Bitcoin reborn as LiteBitcoin, it is an experimental new digital currency that enables instant payments to anyone, anywhere in the world. 
LiteBitcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network.
LiteBitcoin is also the name of the open source software which enables the use of this currency.


LiteBitcoin integration/staging tree
================================

http://www.lbtc.info

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 LiteBitcoin Developers

What is LiteBitcoin?
----------------

LiteBitcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 
----------------

LiteBitcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the LiteBitcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/litebitcoin-project/litebitcoin/tags) are created
regularly to indicate new official, stable release versions of LiteBitcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./litebitcoin-qt_test


LiteBitcoin specifications:
----------------
Scrypt-algo - "Proof of Work" crypto currency.

Algorithms: SCRYPT

Abbreviation: LBTC

Address letter: 2

Total coin supply: 1 Billion LiteBitcoins

Block Reward: 500 LBTC

Block Time: 5 minutes

P2P Port: 19037

RPC Port: 19038




