This is a patch for the valgrind errors present in last submission. Since I 
cannot reproduce them on any of the systems available to me it is a bit in the
blind, but fingers crossed.

This release mainly adds new features to allow access to the internal cache of
freetype objects from other packages as well as attaching OpenType features to 
fonts for use during shaping by graphic devices.

## Test environments
* local R installation, R 4.0.1
* ubuntu 16.04 (on travis-ci), R 4.0.1
* win-builder (devel)

## R CMD check results

0 errors | 0 warnings | 0 note

## revdepcheck results

We checked 3 reverse dependencies, comparing R CMD check results across CRAN and dev versions of this package.

 * We saw 0 new problems
 * We failed to check 0 packages
 
