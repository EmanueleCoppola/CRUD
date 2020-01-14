<br>
<p align="center">
    <a href="https://backpackforlaravel.com" title="Backpack Logo"><img src="https://backpackforlaravel.com/uploads/github/logo.png" style="max-width: 600px"></a>
<p>

<p align="center">
    <a href="https://packagist.org/packages/backpack/crud" title="Latest Version on Packagist"><img src="https://img.shields.io/packagist/v/backpack/crud.svg?style=flat-square"></a>
    <a href="https://packagist.org/packages/backpack/crud" title="Total Downloads"><img src="https://img.shields.io/packagist/dt/backpack/crud.svg?style=flat-square"></a>
    <a href="https://scrutinizer-ci.com/g/laravel-backpack/crud" title="Quality Score"><img src="https://img.shields.io/scrutinizer/g/laravel-backpack/crud.svg?style=flat-square"></a>
    <a href="https://travis-ci.org/Laravel-Backpack/CRUD" title="Build Status"><img src="https://img.shields.io/travis/Laravel-Backpack/CRUD/master.svg?style=flat-square"></a>
    <a href="https://styleci.io/repos/53581270" title="Style CI"><img src="https://styleci.io/repos/53581270/shield"></a>
    <a href="https://scrutinizer-ci.com/g/laravel-backpack/crud/code-structure" title="Coverage Status"><img src="https://img.shields.io/scrutinizer/coverage/g/laravel-backpack/crud.svg?style=flat-square"></a>
    <a href="LICENSE.md" title="Software License"><img src="https://img.shields.io/badge/license-YuMMy-yellow.svg?style=flat-square"></a>
    <br><br>
    <a href="https://backpackforlaravel.com/">Website</a> | 
    <a href="https://backpackforlaravel.com/docs/">Documentation</a> | 
    <a href="https://stackoverflow.com/questions/tagged/backpack-for-laravel">Stack Overflow</a> | 
    <a href="https://backpackforlaravel.com/articles">Blog</a> | 
    <a href="https://backpackforlaravel.com/newsletter">Newsletter</a> | 
    <a href="https://backpackforlaravel.com/pricing">Pricing</a> |
    <a href="https://backpackforlaravel.com/need-freelancer-or-development-team">Hire Us</a>
</p>


<p align="center">
    <a href="https://backpackforlaravel.com/" title="Backpack Screenshots Spread"><img src="https://backpackforlaravel.com/uploads/github/Screenshots_Spread.png"></a>
</p>


Quickly build an admin interface for your Eloquent models. Then customize every little detail.

Features:
- 50+ field types
- 24+ column types
- 1-1, 1-n and n-n relationships
- Table view with search, pagination, click column to sort by it
- Reordering (nested sortable)
- Back-end validation using Requests
- Translatable models (multi-language)
- Easily extend fields/columns/filters/buttons (customising a field type or adding a new one is as easy as creating a new view with a particular name)
- Easily overwrite functionality (customising how the create/update/delete/reorder process works is as easy as creating a new function with the proper name in your EntityCrudController)

> ### Security updates and breaking changes
> If you're using Backpack in production, please **[subscribe to the Backpack Newsletter](http://backpackforlaravel.com/newsletter)** so you can find out about any security updates, breaking changes or major features. We rarely send emails (1-4 emails per year).


## Getting started

Start with the ["Getting Started" series](https://backpackforlaravel.com/docs/4.0/introduction) in our docs. We try to nudge you towards creating a Backpack acccount, but you don't _need_ one, if you're just trying it out.

Alternatively, if you don't have 20 minutes right now, subscribe to our [drip email tutorial](https://backpackforlaravel.com/getting-started-emails). You'll receive one email per day, for 5 days, 5 minutes each. By the end, you'll be familiar with how Backpack works, and be able to create admin panels for your Laravel apps.

## Install

Installation guides:
- [Install Backpack 4.0 on Laravel 6](https://backpackforlaravel.com/docs/4.0/installation) - recommended
- [Install Backpack 3.6 on Laravel 5.8 or 6.x](https://backpackforlaravel.com/docs/3.6/installation) - last feature update was 17th Sep 2019;
- [Install Backpack 3.5 on Laravel 5.5, 5.6, 5.7](https://backpackforlaravel.com/docs/3.5/installation) - last feature update was 27th Feb 2019;
- [Install Backpack 3.x on Laravel 5.4](https://laravel-backpack.readme.io/docs/install-on-laravel-54) - last feature update was 27 Sep 2017;
- [Install Backpack 3.x on Laravel 5.3](https://laravel-backpack.readme.io/docs/installation-on-laravel-53) - last feature update was 02 Feb 2017;
- [Install Backpack 3.x on Laravel 5.2](https://laravel-backpack.readme.io/docs/installation) - deprecated, lacks a lot of features;

## Features

Check out [the about page in the documentation](https://backpackforlaravel.com/docs/4.0/getting-started-crud-operations) to get familiar with most Backpack features.


## Usage

If you've already checked out the features link above, take a look at how you can create a CRUD for a model in [this example](https://backpackforlaravel.com/docs/4.0/getting-started-crud-operations). At the end of the page you'll also find a way you can do everything in 1-2 minutes, using the command line and [backpack/generators](https://github.com/laravel-backpack/generators).

In short:

1. Make your model use the CrudTrait.

2. Create a controller that extends CrudController, route and menu item.

3. **(optional)** Define your validation rules in a Request files.


## Screenshots

- List operation:

![List / table view for Backpack/CRUD](https://backpackforlaravel.com/uploads/docs-4-0/general/4.png)

- Create/Update operations:

![Create or update view for Backpack/CRUD](https://backpackforlaravel.com/uploads/docs-4-0/general/16.png)

- Custom menu & sidebar colors:

![Custom sidebar and menu colours](https://backpackforlaravel.com/uploads/docs-4-0/ui/examples/blue.png)

More screenshots available at [backpackforlaravel.com](https://backpackforlaravel.com).

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email hello@tabacitu.ro instead of using the issue tracker.

Please **[subscribe to the Backpack Newsletter](http://backpackforlaravel.com/newsletter)** so you can find out about any security updates, breaking changes or major features. We send an email every 1-2 months.

## Credits

- [Cristian Tabacitu](http://tabacitu.ro) - creator & lead maintainer;
- [Pedro Martins](https://github.com/pxpm) - maintainer;
- [All Contributors][link-contributors]

Special thanks go to:
- [Owen Melbourne](https://github.com/OwenMelbz) - new features, bug fixing and support;
- [Oliver Ziegler](https://github.com/OliverZiegler) - new features, bug fixing and support;
- [Thomas Swonke](https://github.com/tswonke) - new features, bug fixing and support;
- [Catalin Tudorache](https://github.com/tumf87) - new features, bug fixing and support;
- [John Skoumbourdis](http://www.grocerycrud.com/) - Grocery CRUD for CodeIgniter was a big inspiration for this package;
- [Łukasz Holeczek](https://coreui.io/) - creator of CoreUI (used in Backpack v4);
- [Abdullah Almsaeed](https://adminlte.io/) - creator of AdminLTE (used in Backpack v3);


## License

Backpack is dual-license: 
- free for non-commercial use
- 69 EUR/project for commercial use

Please see the [License File](LICENSE.md) and [backpackforlaravel.com](https://backpackforlaravel.com/#pricing) for more information.

<a name="versioning"></a>
# Versioning

When installing Backpack, require its minor version (currently ```4.0.*```). For us, this is what ```major.minor.patch``` means:

- ```major``` - **PAID upgrade; MAJOR breaking changes;** historically every 2-3 years; upgrading may take even 2-3 hours; includes major new features, major changes in how the whole system works, and complete rewrites; it allows us to _considerably_ improve the product, and add features that were previously impossible;
- ```minor``` - **FREE upgrade; MINOR breaking changes**; historically every 6-12 months; upgrading takes less than 30 minutes; it allows us to add big new features, for free;
- ```patch``` - **FREE upgrade; NO breaking changes**; historically every week; upgrading can be done automatically with composer; includes bug fixes and non-breaking new features;

## Hire us

We've spend more than 10.000 hours creating, polishing and maintaining administration panels on Laravel. We've developed e-Commerce, e-Learning, ERPs, social networks, payment gateways and much more. We've worked on admin panels _so much_, that we've created one of the most popular packages for Laravel - just from making public what was repetitive in our projects.

If you are looking for a developer/team to help you build an admin panel on Laravel, look no further. You'll have a difficult time finding someone with more experience & enthusiasm for admin panels. This is _what we do_. [Contact us](https://backpackforlaravel.com/need-freelancer-or-development-team).


[ico-version]: https://img.shields.io/packagist/v/dick/crud.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/tabacitu/crud.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/backpack/crud
[link-downloads]: https://packagist.org/packages/backpack/crud
[link-author]: https://tabacitu.ro
[link-contributors]: ../../contributors
