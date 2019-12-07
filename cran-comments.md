Update to solve the `class(x) == "y"` issue. 

# Changelog

## Major change
 * Added a `ti_scorpius()` wrapper to SCORPIUS.
   
## Minor change
 * Use `RANN::nn2()` instead of own nearest neighbour functions. 
 
 * Remove deprecated functions.
 
 * Use `lmds` instead of `dyndimred`.

# Checks
## Test environments
* local Fedora 30 install, R 3.6.0
* OS X (on travis-ci), R 3.6.0
* ubuntu 16.04 (on travis-ci), R 3.6.0
* win-builder: release and devel

## R CMD check results

0 errors | 0 warnings | 0 notes

## Reverse dependencies

There are no reverse dependencies.
