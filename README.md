# travis_gcc_cpp17_gprof

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17_gprof.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17_gprof)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17_gprof.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17_gprof)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: none
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Profiling: `gprof`
 * Source: one single file, `main.cpp`

More complex builds:
 * Add `qmake`: [travis_qmake_gcc_cpp17_gprof](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_gprof)

Less complex builds:
 * No `gprof`: [travis_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_gcc_cpp17)
 