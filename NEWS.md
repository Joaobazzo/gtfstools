# gtfstools dev

## New features

- `filter_route_id()`, `filter_route_type()`

## Bug fixes

- The `get_trip_speed()` and `set_trip_speed()` examples, tests and vignette bits now only run if `{lwgeom}` is installed. `{lwgeom}` is an `{sf}` "soft" dependency required by these functions, and is listed in `Suggests`. However, package checks would fail not so gracefully if it wasn't installed, which is now fixed.

## Notes

- Some utility functions previously provided by [`{gtfs2gps}`](https://github.com/ipeaGIT/gtfs2gps) will now be exported by `{gtfstools}`. Huge thanks to the whole `{gtfs2gps}` crew!

# gtfstools 0.1.0

- Initial CRAN release.
