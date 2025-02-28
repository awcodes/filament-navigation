# Changelog

All notable changes to `filament-navigation` will be documented in this file.

## v0.2.0 - 2022-04-21

## What's Changed

- fix: use longText instead of json column for MySQL 5.7 by @ryangjchandler in https://github.com/ryangjchandler/filament-navigation/pull/4
- Fixes item input styling for dark mode. by @awcodes in https://github.com/ryangjchandler/filament-navigation/pull/2

## Upgrade

When upgrading to this version, please run the following commands:

```sh
composer update
php artisan view:clear
php artisan vendor:publish --tag="filament-navigation-assets"
php artisan migrate

```
## New Contributors

- @ryangjchandler made their first contribution in https://github.com/ryangjchandler/filament-navigation/pull/4
- @awcodes made their first contribution in https://github.com/ryangjchandler/filament-navigation/pull/2

**Full Changelog**: https://github.com/ryangjchandler/filament-navigation/compare/v0.1.0...v0.2.0

## v0.1.0 - 2022-04-19

**Full Changelog**: https://github.com/ryangjchandler/filament-navigation/commits/v0.1.0

## 1.0.0 - 202X-XX-XX

- initial release
