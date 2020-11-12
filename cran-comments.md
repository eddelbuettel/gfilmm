## Release summary

* I have fixed the issue spotted by the CRAN check on Solaris. It was due to 
the C++ `pow` function which doesn't accept integer arguments.

* This is a major release, with bugs fixed, new features, and updated vignette.

* On r-hub, the compilation fails on Fedora, which uses the `clang` compiler. 
But the version of `clang` used on CRAN is more recent, so I hope the 
compilation will work.

## Test environments

* ubuntu 18.04, R 3.6.3
* win-builder (devel & release)
* r-hub

## R CMD check results

OK