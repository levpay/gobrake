Gobrake Changelog
=================

### master

### [v4.1.2][v4.1.2] (July 20, 2020)

* Deprecated the `KeysBlacklist` option in favor of `KeysBlocklist`
  ([#141](https://github.com/airbrake/gobrake/pull/141))

### [v4.1.1][v4.1.1] (May 8, 2020)

* Bumped go-tdigest dependency to v3.1.0
  ([#138](https://github.com/airbrake/gobrake/pull/138))
* Bumped pkg/errors dependency to v0.9.1
  ([#138](https://github.com/airbrake/gobrake/pull/138))

### [v4.1.0][v4.1.0] (May 6, 2020)

* README was rewritten from scratch, added new information and examples
  ([#130](https://github.com/airbrake/gobrake/pull/130))
* Changed license from BSD to MIT
  ([#129](https://github.com/airbrake/gobrake/pull/129))
* Added `DisableCodeHunks` option
  ([#122](https://github.com/airbrake/gobrake/pull/122))
* Added support for go1.13 and go1.14 (started testing against them)
  ([#135](https://github.com/airbrake/gobrake/pull/135),
  [#125](https://github.com/airbrake/gobrake/pull/125))
* Improved error handling when the Airbrake API returns HTTP 400
  ([#128](https://github.com/airbrake/gobrake/pull/128))
* Started logging configuration errors
  ([#133](https://github.com/airbrake/gobrake/pull/133))

[v4.1.0]: https://github.com/airbrake/gobrake/releases/tag/v4.1.0
[v4.1.1]: https://github.com/airbrake/gobrake/releases/tag/v4.1.1
[v4.1.2]: https://github.com/airbrake/gobrake/releases/tag/v4.1.2
