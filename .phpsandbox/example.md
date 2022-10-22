# Carbon

[![Latest Stable Version](https://img.shields.io/packagist/v/nesbot/carbon.svg?style=flat-square)](https://packagist.org/packages/nesbot/carbon)
[![Total Downloads](https://img.shields.io/packagist/dt/nesbot/carbon.svg?style=flat-square)](https://packagist.org/packages/nesbot/carbon)
[![GitHub Actions](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fbriannesbitt%2FCarbon%2Fbadge&style=flat-square&label=Build&logo=none)](https://actions-badge.atrox.dev/briannesbitt/Carbon/goto)
[![codecov.io](https://img.shields.io/codecov/c/github/briannesbitt/Carbon.svg?style=flat-square)](https://codecov.io/github/briannesbitt/Carbon?branch=master)
[![Tidelift](https://tidelift.com/badges/github/briannesbitt/Carbon)](https://tidelift.com/subscription/pkg/packagist-nesbot-carbon?utm_source=packagist-nesbot-carbon&utm_medium=referral&utm_campaign=readme)

An international PHP extension for DateTime. [https://carbon.nesbot.com](https://carbon.nesbot.com)


[Get supported nesbot/carbon with the Tidelift Subscription](https://tidelift.com/subscription/pkg/packagist-nesbot-carbon?utm_source=packagist-nesbot-carbon&utm_medium=referral&utm_campaign=readme)

## Installation

### With Composer

```
$ composer require nesbot/carbon
```

```json
{
    "require": {
        "nesbot/carbon": "^2.16"
    }
}
```

```php
<?php
require 'vendor/autoload.php';

use Carbon\Carbon;

printf("Now: %s", Carbon::now());
```

### Without Composer

Why are you not using [composer](https://getcomposer.org/)? Download the Carbon [latest release](https://github.com/briannesbitt/Carbon/releases) and put the contents of the ZIP archive into a directory in your project. Then require the file `autoload.php` to get all classes and dependencies loaded on need.

```php
<?php
require 'path-to-Carbon-directory/autoload.php';

use Carbon\Carbon;

printf("Now: %s", Carbon::now());
```

## Docs

[https://carbon.nesbot.com/docs](https://carbon.nesbot.com/docs)

## Security contact information

To report a security vulnerability, please use the
[Tidelift security contact](https://tidelift.com/security).
Tidelift will coordinate the fix and disclosure.

## Credits

### Contributors

This project exists thanks to all the people who contribute. 

<a href="https://github.com/briannesbitt/Carbon/graphs/contributors" target="_blank"><img src="https://opencollective.com/Carbon/contributors.svg?width=890&button=false" /></a>

### Translators

[Thanks to people helping us to translate Carbon in so many languages](https://carbon.nesbot.com/contribute/translators/)

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website.

<a href="https://tidelift.com/subscription/pkg/packagist-nesbot-carbon?utm_source=packagist-nesbot-carbon&utm_medium=referral&utm_campaign=readme" target="_blank"><img src="https://carbon.nesbot.com/tidelift-brand.png" width="256" height="64"></a>
<a href="https://casinohex.org/canada/?utm_source=opencollective&amp;utm_medium=github&amp;utm_campaign=Carbon" target="_blank"><img src="https://images.opencollective.com/hexcasinoca/2da3af2/logo/256.png" width="85" height="64"></a>

<a href="https://github.com/taylorotwell" target="_blank"><img src="https://avatars.githubusercontent.com/u/463230?s=128&v=4" width="64" height="64"></a>
<a href="https://github.com/usefathom" target="_blank"><img src="https://avatars.githubusercontent.com/u/38684088?s=128&v=4" width="64" height="64"></a>
<a href="https://github.com/tobischulz" target="_blank"><img src="https://avatars.githubusercontent.com/u/576014?s=128&v=4" width="64" height="64"></a>

<a href="https://opencollective.com/Carbon/sponsor/0/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/1/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/2/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/3/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/4/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/5/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/6/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/7/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/Carbon/sponsor/8/website" target="_blank"><img src="https://opencollective.com/Carbon/sponsor/8/avatar.svg"></a>

[[Become a sponsor](https://opencollective.com/Carbon#sponsor)]

### Backers

Thank you to all our backers! 🙏

<a href="https://opencollective.com/Carbon#backers" target="_blank"><img src="https://opencollective.com/Carbon/backers.svg?width=890"></a>

[[Become a backer](https://opencollective.com/Carbon#backer)]

## Carbon for enterprise

Available as part of the Tidelift Subscription.

The maintainers of ``Carbon`` and thousands of other packages are working with Tidelift to deliver commercial support and maintenance for the open source dependencies you use to build your applications. Save time, reduce risk, and improve code health, while paying the maintainers of the exact dependencies you use. [Learn more.](https://tidelift.com/subscription/pkg/packagist-nesbot-carbon?utm_source=packagist-nesbot-carbon&utm_medium=referral&utm_campaign=enterprise&utm_term=repo)
