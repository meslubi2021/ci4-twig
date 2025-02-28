# Codeigniter 4 with Template Engine

[![GitHub Release](https://img.shields.io/github/v/release/ManuelGil/ci4-twig)](https://github.com/ManuelGil/ci4-twig/releases/tag/v1.10.0)
[![GitHub Release Date](https://img.shields.io/github/release-date/ManuelGil/ci4-twig)](https://github.com/ManuelGil/ci4-twig/releases/tag/v1.10.0)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/ci4-twig)](./LICENSE)

Boilerplate with CodeIgniter 4 and Twig Template Engine.

## Requirements

- [PHP 8.1](https://www.php.net/releases/8_1_0.php) or later
  - [intl](http://php.net/manual/en/intl.requirements.php)
  - [libcurl](http://php.net/manual/en/curl.requirements.php) if you plan to use the HTTP\CURLRequest library
  - json (enabled by default - don't turn it off)
  - [mbstring](http://php.net/manual/en/mbstring.installation.php)
  - [mysqlnd](http://php.net/manual/en/mysqlnd.install.php) if you plan to use MySQL
  - xml (enabled by default - don't turn it off)

## Installation

### Copy this project

1. Clone or Download this repository
2. Unzip the archive if needed
3. Rename the folder if needed
4. Start a Text Editor (VSCode, Sublime, PHPStorm, etc)
5. Add the project folder to the editor

### Install the project

You can install this project via composer with the following commands:

#### _Development_

- Required a composer installation.

```bash
composer install
```

- Downloading [composer.phar](https://getcomposer.org/download/).

```bash
sudo php composer.phar install
```

#### _Production_

- Required a composer installation.

```bash
composer install --no-dev --optimize-autoloader
```

- Downloading [composer.phar](https://getcomposer.org/download/).

```bash
sudo php composer.phar install --no-dev --optimize-autoloader
```

## Configure the project

- Copy the [`env`](./env) file and call it `.env`.

```bash
cp env .env
```

- Edit the environment variables in the .env file as you need.

- Make www-data the owner to `writable` folder.

```bash
sudo chown -R www-data: writable/
```

- Start project

```bash
php spark serve
```

## Built With

- CodeIgniter 4.4.3 ([CodeIgniter](https://www.codeigniter.com/download))

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Contributing

Thank you for considering contributing to alternative admin. The contribution guide can be found in the [CONTRIBUTING.md](./.github/CONTRIBUTING.md).

## Code of Conduct

In order to ensure that the alternate admin community is welcoming to all, please review and abide by the [CODE_OF_CONDUCT](./.github/CODE_OF_CONDUCT.md).

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/ci4-twig/contributors)
who participated in this project.

## License

This project is licensed under the MIT License - see the [MIT](https://opensource.org/licenses/MIT) for details.
