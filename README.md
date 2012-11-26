EMake
=====

Makefile generator for Erlang OTP projects, inspired by CMake and rebar.

This program will solve:
1. Long compilation times (compilation must be very fast, even with long
   dependency chains)
2. Custom commands should be straightforward and transparent, Makefile style.

It will be as much as possible compatible with rebar configuration-wise. For
non-fancy projects with a few dependencies you should just be able to replace
rebar with EMake.

Project roadmap
===============

1. Cowboy (very simple project, almost works with current EMake)
2. Erlualib (project with no dependencies and a linked-in library)
3. Moon (project with a few dependencies and a NIF)
4. Riak (very large project, but nothing really fancy)
5. Piqi-rpc (as fancy as you can get in a real-world project)
