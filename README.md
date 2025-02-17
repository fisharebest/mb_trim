# `mb_trim`, `mb_ltrim`, and `mb_rtrim` polyfills

[![Latest Stable Version](http://poser.pugx.org/polyfills/mb-trim/v)](https://packagist.org/packages/polyfills/mb-trim) [![License](http://poser.pugx.org/polyfills/mb-trim/license)](https://packagist.org/packages/polyfills/mb-trim) [![PHP Version Require](http://poser.pugx.org/polyfills/mb-trim/require/php)](https://packagist.org/packages/polyfills/mb-trim)

Provides user-land PHP polyfills for the [`mb_trim`, `mb_ltrim`, and `mb_rtrim` functions added in PHP 8.4](https://php.watch/versions/8.4/mb_trim-mb_ltrim-mb_rtrim).

Requires PHP 8.0 or higher, with `mbstring` extension. The package is a no-op on PHP 8.4 and higher because these functions are natively implemented.

## Installation

```bash
composer require polyfills/mb-trim
```

## Usage

Simply use the `mb_trim`, `mb_ltrim`, and `mb_rtrim` functions as if they were declared already.

## Contributions

Contributions are welcome either as a GitHub issue or a PR to this repo.
