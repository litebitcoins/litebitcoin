Litebitcoin Core version *5.0.0.0* is now available from:



This is a majore version update what change algo from scrypt to neoscrypt.

latest block scrypt what can be mined is 68000 block , first neoscrypt block is 68001)

Please report bugs using the issue tracker at GitHub:

  <https://github.com/litebitcoins/litebitcoin/issues>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the 
installer (on Windows) or just copy over `/Applications/Litebitcoin-Qt` (on Mac)
or `litebitcoind`/`litebitcoin-qt` (on Linux).

The first time you run version 4.0.0.0 or higher, your chainstate database will
be converted to a new format, which will take anywhere from a few minutes to
half an hour, depending on the speed of your machine.

If you a pool after upgrade you need make setting to choise after 68000 block algo from scrypt to neoscrypt, ot change it manual when prefork block be mined.

Downgrading warning
-------------------

downgrad imposible from version 5.0.0.0 to 4.0.0.0.

Compatibility
==============

Litebitcoin Core is extensively tested on multiple operating systems using
the Linux kernel, macOS 10.8+, and Windows Vista and later. Windows XP is not supported.

Litebitcoin Core should also work on most other Unix-like systems but is not
frequently tested on them.