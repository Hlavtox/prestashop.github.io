---
layout: post
aliases: ["/news/coreweekly-week-06-2019"]
title:  "PrestaShop Core Weekly - Week 06 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-02-11 14:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 04th to Sunday 10th of February 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Last week, Pablo Borowicz, PrestaShop's lead developer, started [a series on the blog about the architecture of the PrestaShop open source project](http://build.prestashop.com/news/prestashop-in-2019-and-beyond-introduction/). The next chapter is currently under review and should be published this week.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [81 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-02-04..2019-02-10) have been created in the project repositories
- [76 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-02-04..2019-02-10), including including [13 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-02-04..2019-02-10) on the core.
- [163 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-02-04..2019-02-10) in the project repositories
- [51 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-02-04..2019-02-10)), including [41 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-02-04..2019-02-10)

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#12263](https://github.com/PrestaShop/PrestaShop/pull/12263): Migrate Add/Edit actions for webservice keys. Thank you [@sarjon](https://github.com/sarjon)
* [#12284](https://github.com/PrestaShop/PrestaShop/pull/12284): Include script handler to manage installation of modules, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#12293](https://github.com/PrestaShop/PrestaShop/pull/12293): Migrate actions of Languages list. Thank you [@sarjon](https://github.com/sarjon)
* [#12397](https://github.com/PrestaShop/PrestaShop/pull/12397): Fix use of array_merge in HookFinder->addExpectedInstanceClasses. Thank you [@TysonAndre](https://github.com/TysonAndre)
* [#12398](https://github.com/PrestaShop/PrestaShop/pull/12398): Fix unused variables where straightforward to do so. Thank you [@TysonAndre](https://github.com/TysonAndre)
* [#12399](https://github.com/PrestaShop/PrestaShop/pull/12399): Actually use arguments passed to CountryDataProvider->getCountries(). Thank you [@TysonAndre](https://github.com/TysonAndre)
* [#12400](https://github.com/PrestaShop/PrestaShop/pull/12400): Remove a harmless duplicate array entry in PositionsController. Thank you [@TysonAndre](https://github.com/TysonAndre)
* [#12444](https://github.com/PrestaShop/PrestaShop/pull/12444): Merge back branch 1.7.5.x (changes for 1.7.5.1), by [@jolelievre](https://github.com/jolelievre)
* [#12446](https://github.com/PrestaShop/PrestaShop/pull/12446): Enable new Languages page. Thank you [@sarjon](https://github.com/sarjon)
* [#12447](https://github.com/PrestaShop/PrestaShop/pull/12447): Remove legacy Webservice controller. Thank you [@sarjon](https://github.com/sarjon)


### Back office

* [#11470](https://github.com/PrestaShop/PrestaShop/pull/11470): Improve birthdate validation. Thank you [@zessx](https://github.com/zessx)
* [#11894](https://github.com/PrestaShop/PrestaShop/pull/11894): Migration of international/localization/currencies page form and some exchange rate actions. Thank you [@tomas862](https://github.com/tomas862)
* [#12128](https://github.com/PrestaShop/PrestaShop/pull/12128): Add migrated customers page helper card, by [@matks](https://github.com/matks)
* [#12479](https://github.com/PrestaShop/PrestaShop/pull/12479): Avoid module sorting function warnings when module data is invalid, by [@matks](https://github.com/matks)


### Front office

* [#12406](https://github.com/PrestaShop/PrestaShop/pull/12406): Revert "Fix translation on account creation email error", by [@marionf](https://github.com/marionf)


### Tests

* [#12021](https://github.com/PrestaShop/PrestaShop/pull/12021): Add unit tests for CommandBus, DocumentationLinkProvider and UrlFileChecker, by [@matks](https://github.com/matks)
* [#12431](https://github.com/PrestaShop/PrestaShop/pull/12431): TE: update product quantity test. Thank you [@YosraAk](https://github.com/YosraAk)
* [#12480](https://github.com/PrestaShop/PrestaShop/pull/12480): Add a descriptif comment for the broken test "shopping_carts_view". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12481](https://github.com/PrestaShop/PrestaShop/pull/12481): Add a descriptif comment for the broken test "create_product_with_combination". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12482](https://github.com/PrestaShop/PrestaShop/pull/12482): Add a descriptif comment for the broken test "Delete category". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12485](https://github.com/PrestaShop/PrestaShop/pull/12485): Add a descriptif comment for the broken test "create_feature". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12486](https://github.com/PrestaShop/PrestaShop/pull/12486): Add a descriptif comment for the broken test "read_more_module". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12487](https://github.com/PrestaShop/PrestaShop/pull/12487): Add a descriptif comment for the broken test "configuration". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12491](https://github.com/PrestaShop/PrestaShop/pull/12491): TE: add a descriptif comment for the broken test "category". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12492](https://github.com/PrestaShop/PrestaShop/pull/12492): Add a descriptif comment for the broken test "page". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12493](https://github.com/PrestaShop/PrestaShop/pull/12493): Add a descriptif comment for the broken test "linkWidget". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12494](https://github.com/PrestaShop/PrestaShop/pull/12494): Add a descriptif comment for the broken test "sort filter file". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12496](https://github.com/PrestaShop/PrestaShop/pull/12496): Add a descriptif comment for the broken test "autoupgrade". Thank you [@YosraAk](https://github.com/YosraAk)


## Code changes in the '1.7.5.x' branch (for v1.7.5.1)

### Core

* [#12367](https://github.com/PrestaShop/PrestaShop/pull/12367): Move PositionColumn in its original folder, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#12389](https://github.com/PrestaShop/PrestaShop/pull/12389): Fixed grid hook calls, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Back Office


* [#12234](https://github.com/PrestaShop/PrestaShop/pull/12234): Force refresh of tinymce editors in product page step 1, by [@jolelievre](https://github.com/jolelievre)
* [#12370](https://github.com/PrestaShop/PrestaShop/pull/12370): RTL fixes: profile, select and notification dropdown, popover tooltips, stock quantity arrows, by [@jolelievre](https://github.com/jolelievre)
* [#12372](https://github.com/PrestaShop/PrestaShop/pull/12372): Fix provider warehouse routes, by [@jolelievre](https://github.com/jolelievre)
* [#12402](https://github.com/PrestaShop/PrestaShop/pull/12402): Fix first attribute generation when not choosing first attribute, by [@jolelievre](https://github.com/jolelievre)


### Front office

* [#12337](https://github.com/PrestaShop/PrestaShop/pull/12337): Slow combination update due to delay before request, by [@jolelievre](https://github.com/jolelievre)


## Code changes in modules, themes & tools


###  Auto-upgrade

* [#278](https://github.com/PrestaShop/autoupgrade/pull/278): Update module logo, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### eslint-config-prestashop

* [#2](https://github.com/PrestaShop/eslint-config/pull/2): Advise to install eslint with the rules, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Viewed products block

* [#13](https://github.com/PrestaShop/ps_viewedproduct/pull/13): Fix critical error with previous version of Prestashop. Thank you [@Matt75](https://github.com/Matt75)
* [#15](https://github.com/PrestaShop/ps_viewedproduct/pull/15): Deploy v1.2.1 of ps_viewedproduct, by [@matks](https://github.com/matks)


### Docker Internet Images

* [#24](https://github.com/PrestaShop/docker-internal-images/pull/24): Create one employee per language & enable URL rewriting, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Changes in Documentation

* [#186](https://github.com/PrestaShop/docs/pull/186): Import component docs. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @Matt75, @rokaszygmantas, @sarjon, @tomas862, @TysonAndre, @YosraAk, @zessx!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
