## About Scout Extended

Scout Extended was created by, and is maintained by [Algolia](https://github.com/algolia), and extends [Laravel Scout](https://github.com/laravel/scout)'s Algolia driver adding **Algolia-specific features**.

## Installation

This package is **still in development**. It's not ready for use.

> **Requires:**
- **[PHP 7.1.3+](https://php.net/releases/)**
- **[Laravel 5.6+](https://github.com/laravel/laravel)**

You may use [Composer](https://getcomposer.org) to install Scout Extended into your Laravel project:
```bash
composer require algolia/scout-extended
```

## Features

- [x] For [Laravel Scout](https://github.com/laravel/scout)
- [x] Based on [Algolia's PHP Client v2](https://github.com/algolia/algoliasearch-client-php/tree/2.0) ([47e84e3](https://github.com/nunomaduro/scout/commit/47e84e3c62121a588930b7e04901f7e6a378abb2))
- [x] Contains **macros** from [github.com/algolia/laravel-scout-algolia-macros](https://github.com/algolia/laravel-scout-algolia-macros)
- [x] **Facade** to provide a "static" interface to access clients and analytics
- [x] Replace `scout:flush` command : Clear the index of the the given model
- [x] Replace `scout:import` command : Import the records of the given model
- [x] Adds `scout:reimport` command : Reimport the records of the given model using a temporary indices
- [x] Adds `scout:status` command : Gives information about the remote status
- [x] Adds `scout:optimize` command : Optimize the search experience based on information from the model class
- [x] Adds `scout:sync` command : Backups & Synchronize the given model settings
- [x] Adds `scout:aggregator` command : Create a new aggregator class
- [x] Aggregators - **Multiple models on the same index**
- [x] Ability to use **display features** (**Searchable attributes**, **Query Language**, **Custom Ranking**, etc) of using a configuration file
- [x] Automatic way of leverage **Distinct**
- [x] Update **UserAgent**
- [x] Adds `@scout` blade directive
- [ ] Manager - **Multiple client connections** per project
- [ ] **Extends Driver's Query Builder** adding more methods: whereIn, whereNotIn, whereNot, whereBetween, and others cases to be studied
- [ ] Support to **multiple language indexes**
- [ ] Ability to use **synonyms features** of using a configuration file
- [ ] Ability to use **Rules features**

## License

Scout Extended is an open-sourced software licensed under the [MIT license](LICENSE.md).
