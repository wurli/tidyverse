## R CMD check results

0 errors | 0 warnings | 1 notes

> checking package dependencies ... NOTE
  Imports includes 29 non-default packages.
  Importing from so many packages makes the package vulnerable to any of
  them becoming unavailable.  Move as many as possible to Suggests and
  use conditionally.

This is a false positive - the majority of packages are maintained by me or my team, so there's little risk of them becoming unavailable.

## revdepcheck results

We checked 218 reverse dependencies, comparing R CMD check results across CRAN and dev versions of this package.

 * We saw 0 new problems
 * We failed to check 2 packages

Issues with CRAN packages are summarised below.

### Failed to check

* loon.shiny (NA)
* loon.tourr (NA)
