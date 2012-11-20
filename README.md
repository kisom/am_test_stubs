# am_stub_tests
## automake CUnit test stubs

This project provides quick-start templates to add unit tests to your
C code using [CUnit](http://cunit.sourceforge.net/).

### What's provided

* `Makefile.am` has a few lines in it relevant to unit testing; they just
need to be integrated into the current build.
* `tests/Makefile.am` demonstrates a skeleton Makefile template for building
the tests.
* `tests/stub_test.c` is just a skeleton test; make sure to pass it
`-DTEST_SUITE="\"your_test_name\"" in the CFLAGS (see `tests/Makefile.am`).

### Using
0. Create the initial `tests` directory:
`cp -r /path/to/this/repo/tests /path/to/your/code`
0. Make sure the tests are called in your top level `Makefile.am`. Consult
the `./Makefile.am` provided here if you aren't sure what to add.

### License
`am_stub_tests` is provided under an
[ISC license](https://raw.github.com/kisom/am_test_stubs/master/LICENSE).

### Author
Kyle Isom (kyle `:at` tyrfingr `:dot:` is) put this together.
