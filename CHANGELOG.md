# Changelog

This changelog references the relevant changes (bug and security fixes) done to `jomweb/billplz`.

## 1.0.2

Released: 2017-10-08

### Added

* Add `Billplz\Client::check()` resource helper to make it easy to verify bank account via `$billplz->check()->bankAccount()`.

### Changes

* Improves readme/documentation.

## 1.0.1

Released: 2017-08-31

### Fixes

* `Billplz\Request::getApiEndpoint()` should properly handle `$path` when given an array.

## 1.0.0

Released: 2017-08-31

### New

* Initial stable release.

### Changes

* `Billplz\Three\Bill::create()` now support array for `$callbackUrl` parameter, when you can provide an associated array containing `callback_url` and `redirect_url`.
* Make `nesbot/carbon` dependency optional, simply use `new \DateTime()` if it is not presented.
