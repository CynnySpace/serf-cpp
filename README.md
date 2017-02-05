[![Build Status](https://travis-ci.org/CJLove/serf-cpp.svg?branch=master)](https://travis-ci.org/CJLove/serf-cpp) 
[![Coverage Status](https://coveralls.io/repos/github/CJLove/serf-cpp/badge.svg?branch=master)](https://coveralls.io/github/CJLove/serf-cpp?branch=master)


# serf-cpp
C++ implementation of serf client (http://www.serfdom.io)

This is a C++ library which can be used to interact with a Serf agent
using the msgpack RPC system it supports.

The Serf RPC interface is defined here:
https://www.serfdom.io/docs/agent/rpc.html.

The 'cpp03' branch targets C++03 compilers and uses Boost for
portable thread support; the 'cpp11' branch targets modern compilers
suppporting C++11 without the Boost dependency.

# Status
See TODO for major functionality remaining and some longer term plans.
See Commands.txt for status of individual RPC commands

# Dependencies

1. CMake used for building
2. Google Test (gtest) for unit tests
3. msgpack-c (https://github.com/msgpack/msgpack-c)
4. Boost

