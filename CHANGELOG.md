# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2025-10-09

### Added

-   First stable version of the Razor templating engine.
-   Compatibility with the [`codemonster-ru/view`](https://github.com/codemonster-ru/view`) package.
-   Directive support:
-   `{{ $variable }}` — safe variable output.
-   `@if` / `@endif` — conditional blocks.
-   `@foreach` / `@endforeach` — loops.
-   `@include` — inserting other templates.
-   Caching of compiled templates.
-   PHPUnit tests.
-   Full README and documentation.
