## Changelog

## 0.19 (2014-01-14)

* Ord instance for Integer
* Export base versions of Maybe, Ordering, and Either instead of redefining when compiling with GHC. This helps when writing libraries targeting both Fay and GHC
* `Prelude`: Add `void`, `>=>` and `<=<`, `unless`, `forM`, `mapM`
* Add `Debug.Trace` module exporting `trace` and `traceShow`

Minor:
* Upper bound to the latest major Fay version

## 0.18.0.0 (2013-09-24)

* Fixed implementation of `>>` and `>>=` (this bug didn't affect normal usage)
* Add `fail`
* Generalize type signatures for `fromIntegral` and `fromInteger`


## 0.17.0.0 (2013-08-27)

* The type signature of `FFI.ffi` has been generalized to `IsString s => s -> a` to support `RebindableSyntax`.
* Prelude now exports `ifThenElse` as a default for `RebindableSyntax`


## 0.16.0.0 (2013-08-05)

* Added more Ratio functions and move them all into Data.Ratio
