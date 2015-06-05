# C++ binding for proton.

This is a C++ binding for the proton API.

There are [examples](../../../examples/cpp/README.md) and the header files have
API documentation in doxygen format.

# TO DO

There are a number of things that remain to be done.

- Mapping of complex types.

- Finish blocking API & demos.
- API documentation, HTML docs on website.
- FIXME and TODO notes in code, esp. error handling, missing sender/receiver/connection methods.

- Valgrind for automated tests and demos.
- More automated tests and examples.

- Security: SASL/SSL support.
- Reconnection


# Nice to have

Subclasses of Encoder/Decoder that push to/pull from a std::ostream/istream as
values are inserted/extracted.

Better support for Decimal type.