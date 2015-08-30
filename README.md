# serf-cpp
C++ implementation of serf client (http://www.serfdom.io)

This is a C++ library which can be used to interact with a Serf agent
using the msgpack RPC system it supports.

The Serf RPC interface is defined here:
https://www.serfdom.io/docs/agent/rpc.html.

For now the implementation is targeted toward C++03 and uses Boost for
portable thread support; future support for C++11 using std::thread is
possible.

# Status
Synchronous RPC methods supported: event, force-leave, join, members,
members-filtered, tags, leave

See TODO for major functionality remaining and some longer term plans.

# Dependencies

1. CMake used for building
2. Google Test (gtest) for unit tests
3. msgpack-c (https://github.com/msgpack/msgpack-c)
4. Boost

