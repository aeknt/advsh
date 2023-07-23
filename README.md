# ADVSH

## DESCRIPTION

Implement ADVanced(ish) functions in (preferably pure) sh

## FEATURES
- simple loops and ranges
- arrays
- ...more soon...

## HOWTO

Advsh functions are split into categories
- advsh -- common functions used by other advsh functions and currently also IFS niceties
- adv_loops -- loops and ranges
- adv_arrays -- basic arrays

The way you are supposed to use advsh is by copying the functions into your scripts, sourcing them isn't good idea as point of writing this in posix sh is the ultimate(?) portability. Also this way you can easily prevent breaking your scripts when i change something.

## EXAMPLES

See examples/
