# Square signup and login implementation for socialite - https://github.com/laravel/socialite

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

## Install

Via Composer

``` bash
$ composer require arsumcom/socialite-square-up
```

## Configuration

After installing the SocialiteStripe library, register the `ArsumCom\SocialiteStripe\SocialiteSquareUpServiceProvider` in your `config/app.php` configuration file:

```php
'providers' => [
    // Other service providers...

    ArsumCom\SocialiteStripe\SocialiteSquareUpServiceProvider::class,
],
```

You will also need to add credentials for the OAuth services your application utilizes. These credentials should be placed in your `config/services.php` configuration file, and should use the key `squareup`. For example:
```php
'squareup' => [
    'client_id' => env('SQUAREUP_CLIENT_ID', 'your-squareup-app-id'),
    'client_secret' => env('SQUAREUP_CLIENT_SECRET', 'your-squareup-app-secret'),
    'redirect' => env('SQUAREUP_REDIRECT', 'http://your-callback-url'),
],
```
## Basic Usage

https://github.com/laravel/socialite#basic-usage

## Security

If you discover any security related issues, please email max.fetisov@arsum.com instead of using the issue tracker.

## Credits

- [Max Fetisov][link-author]
- [Arsum][http://arsum.com]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/arsumcom/socialite-square-up.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/arsumcom/socialite-square-up/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/arsumcom/socialite-square-up.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/arsumcom/socialite-square-up.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/arsumcom/socialite-square-up.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/arsumcom/socialite-square-up
[link-travis]: https://travis-ci.org/arsumcom/socialite-square-up
[link-scrutinizer]: https://scrutinizer-ci.com/g/arsumcom/socialite-square-up/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/arsumcom/socialite-square-up
[link-downloads]: https://packagist.org/packages/arsumcom/socialite-square-up
[link-author]: https://github.com/kovalski
