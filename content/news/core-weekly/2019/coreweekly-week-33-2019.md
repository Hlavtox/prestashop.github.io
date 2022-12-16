---
layout: post
aliases: ["/news/coreweekly-week-33-2019"]
title:  "PrestaShop Core Weekly - Week 33 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-10-02 10:05:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 12th of August to Sunday 18th of August 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## A quick update about PrestaShop's GitHub issues and pull requests:

- [60 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-08-12..2019-08-18) have been created in the project repositories;
- [45 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-08-12..2019-08-18), including [2 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-08-12..2019-08-18) on the core;
- [30 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-08-12..2019-08-18) in the project repositories;
- [28 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-08-12..2019-08-18), including [13 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-08-12..2019-08-18).
        

## Code changes in the 'develop' branch

### Core

* [#15127](https://github.com/PrestaShop/PrestaShop/pull/15127): Remove Github checks for PHP 5.6, by [@eternoendless](https://github.com/eternoendless)

* [#15079](https://github.com/PrestaShop/PrestaShop/pull/15079): PhpDoc fix module::updatePosition() param type. Thank you [@zalexki](https://github.com/zalexki)

* [#15027](https://github.com/PrestaShop/PrestaShop/pull/15027): Typo fix in Employee processing. Thank you [@gavinkalika](https://github.com/gavinkalika)

* [#15076](https://github.com/PrestaShop/PrestaShop/pull/15076): Merge 1.7.6.x to develop, by [@matks](https://github.com/matks)

## Code changes in the '1.7.6.x' branch (for v1.7.6.1)

### Core

* [#15050](https://github.com/PrestaShop/PrestaShop/pull/15050): Update version to 1.7.6.1, by [@eternoendless](https://github.com/eternoendless)

### Back office

* [#15030](https://github.com/PrestaShop/PrestaShop/pull/15030): Get all categories in category tree form (not only enabled ones), by [@matthieu-rolland](https://github.com/matthieu-rolland)

* [#14966](https://github.com/PrestaShop/PrestaShop/pull/14966): Keep BO from using two different translators in parallel, by [@matthieu-rolland](https://github.com/matthieu-rolland)

### Front office

* [#15042](https://github.com/PrestaShop/PrestaShop/pull/15042): Only disable following steps in the checkout process when the current step has a continue button, by [@jolelievre](https://github.com/jolelievre)

## Code changes in modules, themes & tools

### PrestaShop Specifications

* [#41](https://github.com/PrestaShop/prestashop-specs/pull/41): Update specific price specs, by [@marionf](https://github.com/marionf)

* [#39](https://github.com/PrestaShop/prestashop-specs/pull/39): Add link to facetedsearch specs, by [@marionf](https://github.com/marionf)

* [#38](https://github.com/PrestaShop/prestashop-specs/pull/38): Create ps_facetedsearch.md, by [@marionf](https://github.com/marionf)

### Changes in developer documentation

* [#323](https://github.com/PrestaShop/docs/pull/323): Updated the article, misleading people to the wrong direction, by [@mickaelandrieu](https://github.com/mickaelandrieu)

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @marionf, @eternoendless, @zalexki, @matks, @mickaelandrieu, @jolelievre, @matthieu-rolland, @gavinkalika!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

