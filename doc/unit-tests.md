Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the bcashd tests manually, launch `src/test/test_bcash`.

To add more bcashd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the bcash-qt tests manually, launch `src/qt/test/test_bcash-qt`

To add more bcash-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
