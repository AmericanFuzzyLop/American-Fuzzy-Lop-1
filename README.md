# American-Fuzzy-Lop-1
A number of iBoot modules have fuzzing interfaces. This document describes
how to fuzz those modules, and how to set up a new module for fuzzing.

There are a number of open and closed-source fuzzers available, but by far
the best is AFL (american fuzzy lop): <http://lcamtuf.coredump.cx/afl/>.
The rest of this document is geared towards fuzzing with AFL, but the
interface is fairly generic.
