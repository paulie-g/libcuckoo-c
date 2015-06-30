Attention
=========

Libcuckoo-c was abandoned by the original authors in favour of a c++ implementation and deleted the contents of the repo.
I'm assuming this was done so they wouldn't be bothered with questions or pull requests, so pleas keep that in mind.


libcuckoo
=========

High-performance Concurrent Cuckoo Hashing Library

This library provides a compact hash table that allows multiple
concurrent reader threads, while allowing one thread at a time
to make inserts or updates.  It is particularly useful for
applications with high read-to-write ratios that store small key/value
pairs in the hash table.

Authors: Bin Fan, David G. Andersen and Michael Kaminsky 

For details about this algorithm and citations, please refer to [our paper in NSDI 2013][1].

   [1]: http://www.cs.cmu.edu/~dga/papers/memc3-nsdi2013.pdf "MemC3: Compact and Concurrent Memcache with Dumber Caching and Smarter Hashing"

Building
--------

    $ autoreconf -fis
    $ ./configure
    $ make


Issue Report
------------
To let us know your questions or issues, we recommend you to use [issue report](https://github.com/efficient/libcuckoo/issues) on github.
You can also email us, however, at [libcuckoo-dev@googlegroups.com](mailto:libcuckoo-dev@googlegroups.com).
