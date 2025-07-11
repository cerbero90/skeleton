# :package_title

[![Author][ico-author]][link-author]
[![PHP Version][ico-php]][link-php]
[![Laravel Version][ico-laravel]][link-laravel]
[![Latest Version][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-actions]][link-actions]
[![Code Quality][ico-code-quality]][link-code-quality]
[![Coverage][ico-coverage]][link-coverage]
[![PHPStan Level][ico-phpstan]][link-phpstan]
[![Total Downloads][ico-downloads]][link-downloads]

:package_description


## 📦 Install

Via Composer:

``` bash
composer require cerbero/:package_name
```

## 🔮 Usage

1. Create a new package by [using this template](https://github.com/cerbero90/skeleton/generate)
1. Clone the newly created repository
1. Run `php prefill.php`
1. Review versions of PHP and Laravel to support in [composer.json](composer.json), [build.yml](.github/workflows/build.yml) and [README badges](README.md)
1. Push changes to master
1. Submit package to [Packagist](https://packagist.org/packages/submit)
1. Add repository to [Codacy](https://app.codacy.com/organizations/gh/cerbero90/repositories/add)
    - Generate [Repository API Token](https://app.codacy.com/gh/cerbero90/:package_name/settings/coverage)
    - Add `CODACY_REPO_TOKEN` to the [repository secrets](https://github.com/cerbero90/:package_name/settings/secrets/actions/new)
    - Find the [project ID in the badge URL](https://app.codacy.com/gh/cerbero90/:package_name/settings) and add it to the Codacy badges on this README
    - If needed, manually [ignore the files](https://app.codacy.com/gh/cerbero90/:package_name/settings/ignoredFiles) that should not be analyzed
1. Initialize GitFlow
1. Happy coding!

## 📆 Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## 🧪 Testing

``` bash
composer test
```

## 💞 Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## 🧯 Security

If you discover any security related issues, please email andrea.marco.sartori@gmail.com instead of using the issue tracker.

## 🏅 Credits

- [Andrea Marco Sartori][link-author]
- [All Contributors][link-contributors]

## ⚖️ License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-author]: https://img.shields.io/badge/author-cerbero90-blue?logo=x&style=for-the-badge&logoSize=auto
[ico-php]: https://img.shields.io/packagist/php-v/cerbero/:package_name?color=%23777BB4&logo=php&style=for-the-badge&logoSize=auto
[ico-laravel]: https://img.shields.io/static/v1?label=laravel&message=%E2%89%A55.5&color=ff2d20&logo=laravel&style=for-the-badge&logoSize=auto
[ico-version]: https://img.shields.io/packagist/v/cerbero/:package_name.svg?label=version&style=for-the-badge&logo=vitess&logoColor=fff&logoSize=auto
[ico-license]: https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge&logo=lerna&logoColor=fff&logoSize=auto
[ico-actions]: https://img.shields.io/github/actions/workflow/status/cerbero90/:package_name/build.yml?branch=master&style=for-the-badge&logo=github&logoSize=auto
[ico-code-quality]: https://img.shields.io/codacy/grade/xxxxx?style=for-the-badge&logo=codacy&logoSize=auto
[ico-coverage]: https://img.shields.io/codacy/coverage/xxxxx?style=for-the-badge&logo=codacy&logoSize=auto
[ico-phpstan]: https://img.shields.io/badge/phpstan-max-success?style=for-the-badge&logo=data:image/png;base64,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&logoSize=auto
[ico-downloads]: https://img.shields.io/packagist/dt/cerbero/:package_name.svg?style=for-the-badge&logo=packagist&logoSize=auto

[link-author]: https://x.com/cerbero90
[link-php]: https://www.php.net
[link-laravel]: https://laravel.com
[link-packagist]: https://packagist.org/packages/cerbero/:package_name
[link-actions]: https://github.com/cerbero90/:package_name/actions?query=workflow%3Abuild
[link-code-quality]: https://app.codacy.com/gh/cerbero90/:package_name/dashboard
[link-coverage]: https://app.codacy.com/gh/cerbero90/:package_name/dashboard
[link-downloads]: https://packagist.org/packages/cerbero/:package_name
[link-phpstan]: https://phpstan.org/
[link-contributors]: ../../contributors
