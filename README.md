# awesome-succint-data-structures
A curated awesome list of succint data structures, algorithms and articles for efficient computing with a smaller memory footprint 


## Bit maps and sets

- https://github.com/RoaringBitmap provides a compressed and fast way to store sets of integers.

## Compressed string Indexes

- FM-Index https://en.wikipedia.org/wiki/FM-index
  - Shellinford https://pypi.python.org/pypi/shellinford and https://code.google.com/archive/p/shellinford/ and https://bitbucket.org/oov/go-shellinford
  - Oktavia https://github.com/shibukawa/oktavia.py and https://github.com/shibukawa/oktavia

## Finite state machines, automata and transducers

- FSTs (note that while not strictly succint, transducers are densely compressed and are often used in the same context as succint data structures)
  - http://openfst.org/ Transducers C++ and Python
  - http://blog.burntsushi.net/transducers/ Index 1,600,000,000 Keys with Automata and Rust

## General purpose libraries

- SDSL C++ https://github.com/simongog/sdsl-lite : bitvectors, rank select, Wavelet Trees, suffix arrays, syffix tree
