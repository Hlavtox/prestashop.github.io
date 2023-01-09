---
layout: post
aliases: ["/news/coreweekly-week-34-2019"]
title:  "PrestaShop Core Weekly - Week 34 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-10-02 10:10:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 19th of August to Sunday 25th of August 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## A quick update about PrestaShop's GitHub issues and pull requests:

- [75 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-08-19..2019-08-25) have been created in the project repositories;
- [78 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-08-19..2019-08-25), including [6 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-08-19..2019-08-25) on the core;
- [49 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-08-19..2019-08-25) in the project repositories;
- [57 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-08-19..2019-08-25), including [47 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-08-19..2019-08-25).


## Code changes in the 'develop' branch

### Core

* [#14951](https://github.com/PrestaShop/PrestaShop/pull/14951): Update PrestaShopCollection.php docs on getFirst method return type. Thank you [@zalexki](https://github.com/zalexki)

### Back office

* [#15005](https://github.com/PrestaShop/PrestaShop/pull/15005): Last visit date incorrect. Thank you [@cirykpopeye](https://github.com/cirykpopeye)

* [#14873](https://github.com/PrestaShop/PrestaShop/pull/14873): Remove AdminManufacturer controller again, by [@matks](https://github.com/matks)

* [#14869](https://github.com/PrestaShop/PrestaShop/pull/14869): Removes AdminPreferencesController again, by [@matks](https://github.com/matks)

### Front office

* [#15055](https://github.com/PrestaShop/PrestaShop/pull/15055): Fix duplicate class attribute in HTML element. Thank you [@asf-harlock](https://github.com/asf-harlock)

* [#14727](https://github.com/PrestaShop/PrestaShop/pull/14727): Fix compile id {render} override issue on theme. Thank you [@202-ecommerce](https://github.com/202-ecommerce)

* [#14539](https://github.com/PrestaShop/PrestaShop/pull/14539): Make email display dependant on configuration from ps_contactinfo module, by [@matthieu-rolland](https://github.com/matthieu-rolland)

### Installer

* [#15131](https://github.com/PrestaShop/PrestaShop/pull/15131): Fixed permanent redirection in installer, by [@mickaelandrieu](https://github.com/mickaelandrieu)

### Tests

* [#15206](https://github.com/PrestaShop/PrestaShop/pull/15206): Smoke tests - Fix the product selector in the FO. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)

* [#15163](https://github.com/PrestaShop/PrestaShop/pull/15163): Docker for test AutoUpgrade, by [@boubkerbribri](https://github.com/boubkerbribri)

* [#15161](https://github.com/PrestaShop/PrestaShop/pull/15161): Remove another faulty e2e test from Travis, by [@matks](https://github.com/matks)

* [#15156](https://github.com/PrestaShop/PrestaShop/pull/15156): Adding new Test UpgradeShop with puppeteer, by [@boubkerbribri](https://github.com/boubkerbribri)

* [#15155](https://github.com/PrestaShop/PrestaShop/pull/15155): Update expect usage in puppeteer tests, by [@boubkerbribri](https://github.com/boubkerbribri)

* [#15151](https://github.com/PrestaShop/PrestaShop/pull/15151): All BO classes should inherit from BObasePage, by [@boubkerbribri](https://github.com/boubkerbribri)

## Code changes in the '1.7.6.x' branch (for v1.7.6.1)

### Core

* [#15132](https://github.com/PrestaShop/PrestaShop/pull/15132): Fix abstract service declaration, by [@eternoendless](https://github.com/eternoendless)

### Back office

* [#15173](https://github.com/PrestaShop/PrestaShop/pull/15173): CLDR has access to all currencies regardless of the current shop, by [@jolelievre](https://github.com/jolelievre)

* [#15139](https://github.com/PrestaShop/PrestaShop/pull/15139): Make module and email translations work again when using a theme other than classic, by [@eternoendless](https://github.com/eternoendless)

## Code changes in modules, themes & tools

### PrestaShop Specifications

* [#68](https://github.com/PrestaShop/prestashop-specs/pull/68): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#67](https://github.com/PrestaShop/prestashop-specs/pull/67): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#66](https://github.com/PrestaShop/prestashop-specs/pull/66): Colinegin patch 7, by [@colinegin](https://github.com/colinegin)

* [#65](https://github.com/PrestaShop/prestashop-specs/pull/65): symfony migration, by [@colinegin](https://github.com/colinegin)

* [#64](https://github.com/PrestaShop/prestashop-specs/pull/64): Delete symfony-migration, by [@colinegin](https://github.com/colinegin)

* [#63](https://github.com/PrestaShop/prestashop-specs/pull/63): symfony-migration, by [@colinegin](https://github.com/colinegin)

* [#62](https://github.com/PrestaShop/prestashop-specs/pull/62): symfony-migration, by [@colinegin](https://github.com/colinegin)

* [#61](https://github.com/PrestaShop/prestashop-specs/pull/61): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#59](https://github.com/PrestaShop/prestashop-specs/pull/59): Create symfony-migration, by [@colinegin](https://github.com/colinegin)

* [#58](https://github.com/PrestaShop/prestashop-specs/pull/58): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#57](https://github.com/PrestaShop/prestashop-specs/pull/57): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#56](https://github.com/PrestaShop/prestashop-specs/pull/56): Update theme-logo.md, by [@colinegin](https://github.com/colinegin)

* [#55](https://github.com/PrestaShop/prestashop-specs/pull/55): Update README.md, by [@colinegin](https://github.com/colinegin)

* [#54](https://github.com/PrestaShop/prestashop-specs/pull/54): theme-logo, by [@colinegin](https://github.com/colinegin)

* [#53](https://github.com/PrestaShop/prestashop-specs/pull/53): Ecotax specs in product add/edit page, by [@marionf](https://github.com/marionf)

* [#52](https://github.com/PrestaShop/prestashop-specs/pull/52): Updates specs add / edit product, by [@marionf](https://github.com/marionf)

* [#51](https://github.com/PrestaShop/prestashop-specs/pull/51): Update specs for product SEO tab, by [@marionf](https://github.com/marionf)

* [#50](https://github.com/PrestaShop/prestashop-specs/pull/50): Specify errors message to add/edit product specs, by [@marionf](https://github.com/marionf)

* [#49](https://github.com/PrestaShop/prestashop-specs/pull/49): Update add/edit product specs links, by [@marionf](https://github.com/marionf)

* [#48](https://github.com/PrestaShop/prestashop-specs/pull/48): Add link to add/edit product specs, by [@marionf](https://github.com/marionf)

* [#47](https://github.com/PrestaShop/prestashop-specs/pull/47): Add options tab to add/edit product specs, by [@marionf](https://github.com/marionf)

* [#46](https://github.com/PrestaShop/prestashop-specs/pull/46): update faceted search specs, by [@marionf](https://github.com/marionf)

* [#45](https://github.com/PrestaShop/prestashop-specs/pull/45): update faceted search specs, by [@marionf](https://github.com/marionf)

* [#44](https://github.com/PrestaShop/prestashop-specs/pull/44): Update faceted seach specs, by [@marionf](https://github.com/marionf)

* [#43](https://github.com/PrestaShop/prestashop-specs/pull/43): Update faceted search specs, by [@marionf](https://github.com/marionf)

* [#42](https://github.com/PrestaShop/prestashop-specs/pull/42): Update specs of BO product page, by [@marionf](https://github.com/marionf)

* [#40](https://github.com/PrestaShop/prestashop-specs/pull/40): Rename Prestashop.md to README.md, by [@PierreRambaud](https://github.com/PierreRambaud)

### Changes in developer documentation

* [#327](https://github.com/PrestaShop/docs/pull/327): Fix typo for 'modules' in 1.7/themes/getting-started/theme-organization. Thank you [@hdasdoria](https://github.com/hdasdoria)

### Contact Informations module

* [#13](https://github.com/PrestaShop/ps_contactinfo/pull/13): Make email display in footer and contact us page configurable, by [@matthieu-rolland](https://github.com/matthieu-rolland)

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @colinegin, @marionf, @hdasdoria, @nesrineabdmouleh, @jolelievre, @boubkerbribri, @matks, @eternoendless, @mickaelandrieu, @PierreRambaud, @asf-harlock, @cirykpopeye, @zalexki, @202-ecommerce, @matthieu-rolland!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
