---
layout: post
aliases: ["/news/coreweekly-26-2021"]
title:  "PrestaShop Core Weekly - Week 26 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-07-05
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 28th of June to Sunday 4th of July 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [Linklist](https://github.com/PrestaShop/ps_linklist) module: [v5.0.3](https://github.com/PrestaShop/ps_linklist/releases/tag/v5.0.3)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [55 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-06-28..2021-07-04) have been created in the project repositories;
- [40 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-06-28..2021-07-04), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-06-28..2021-07-04) on the core;
- [80 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-06-28..2021-07-04) in the project repositories;
- [90 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-06-28..2021-07-04), including [60 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-06-28..2021-07-04).


## Code changes in the 'develop' branch


### Core
* [#25187](https://github.com/PrestaShop/PrestaShop/pull/25187): Replace getmanufacturerLink with getManufacturerLink. Thank you [@Sinepel](https://github.com/Sinepel)
* [#25147](https://github.com/PrestaShop/PrestaShop/pull/25147): Do not strict type for compatibility reason, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#24985](https://github.com/PrestaShop/PrestaShop/pull/24985): In dev mode, hooks must not swallow exceptions. Thank you [@lmeyer1](https://github.com/lmeyer1)


### Back office
* [#25153](https://github.com/PrestaShop/PrestaShop/pull/25153): Make color picker global in back office, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#25152](https://github.com/PrestaShop/PrestaShop/pull/25152): Fix selectors map not being set in experimental product combinations page. Thank you [@zuk3975](https://github.com/zuk3975)
* [#25089](https://github.com/PrestaShop/PrestaShop/pull/25089): Fixed replaced image in product page. Thank you [@NoZTurn](https://github.com/NoZTurn)
* [#25087](https://github.com/PrestaShop/PrestaShop/pull/25087): Fix form label alignment, switch precision and alignment. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25085](https://github.com/PrestaShop/PrestaShop/pull/25085): Kick border radius of the middle button of search bar, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25072](https://github.com/PrestaShop/PrestaShop/pull/25072): BO: Product Form V2 : Show inactive categories in the category tree. Thank you [@e-gaulue](https://github.com/e-gaulue)
* [#24982](https://github.com/PrestaShop/PrestaShop/pull/24982): Fix getting products count on category list. Thank you [@kpodemski](https://github.com/kpodemski)
* [#24658](https://github.com/PrestaShop/PrestaShop/pull/24658): Deprecate Domain\SpecificPrice namespace. Thank you [@zuk3975](https://github.com/zuk3975)


### Front office
* [#25151](https://github.com/PrestaShop/PrestaShop/pull/25151): Remove useless 50x.html pages in classic. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#24656](https://github.com/PrestaShop/PrestaShop/pull/24656): Introduce ability to version Media. Thank you [@samberrry](https://github.com/samberrry)
* [#24437](https://github.com/PrestaShop/PrestaShop/pull/24437): Add "recycled packaging" in order_conf and new_order mail and on order summary page and order confirmation page. Thank you [@okom3pom](https://github.com/okom3pom)


### Web services
* [#22969](https://github.com/PrestaShop/PrestaShop/pull/22969): Fixed API inconsistent return format of JSON. Thank you [@Kyaary](https://github.com/Kyaary)


### Tests
* [#25196](https://github.com/PrestaShop/PrestaShop/pull/25196): Removed phpunit-controllers tests, by [@Progi1984](https://github.com/Progi1984)
* [#25127](https://github.com/PrestaShop/PrestaShop/pull/25127): Migrated some Legacy Tests to Integration/Unit Tests, by [@Progi1984](https://github.com/Progi1984)


## Code changes in the '1.7.8.x' branch


### Core
* [#25141](https://github.com/PrestaShop/PrestaShop/pull/25141): Upgrade ps_linklist to 5.0.3, by [@sowbiba](https://github.com/sowbiba)


### Front office
* [#25101](https://github.com/PrestaShop/PrestaShop/pull/25101): Fix RTL issues on material icons on FO, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#25128](https://github.com/PrestaShop/PrestaShop/pull/25128): Functional tests - Add js doc for 'Advanced parameters' pages. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25108](https://github.com/PrestaShop/PrestaShop/pull/25108): Functional tests - Refacto 'Orders > Shopping carts' tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25104](https://github.com/PrestaShop/PrestaShop/pull/25104): Functional tests - Refacto 'Orders > Delivery slips' tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24995](https://github.com/PrestaShop/PrestaShop/pull/24995): Functional tests - Add Js doc for catalog pages. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#1062](https://github.com/PrestaShop/docs/pull/1062): Add new ColorPicker component, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#1059](https://github.com/PrestaShop/docs/pull/1059): Improve introduction, move cache section to core/architecture, by [@eternoendless](https://github.com/eternoendless)
* [#1057](https://github.com/PrestaShop/docs/pull/1057): Fixed grammar. Thank you [@sadeqush](https://github.com/sadeqush)
* [#1044](https://github.com/PrestaShop/docs/pull/1044): Update the multistore form documentation, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#977](https://github.com/PrestaShop/docs/pull/977): Move Module Configuration doc to Component Storage doc page, by [@matks](https://github.com/matks)


### Customer reassurance block module
* [#229](https://github.com/PrestaShop/blockreassurance/pull/229): Bump version to 5.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#228](https://github.com/PrestaShop/blockreassurance/pull/228): Bump mini-css-extract-plugin from 1.6.2 to 2.0.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#227](https://github.com/PrestaShop/blockreassurance/pull/227): Bump webpack from 5.41.0 to 5.41.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#226](https://github.com/PrestaShop/blockreassurance/pull/226): Bump mini-css-extract-plugin from 1.6.1 to 1.6.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#225](https://github.com/PrestaShop/blockreassurance/pull/225): Bump webpack from 5.40.0 to 5.41.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#224](https://github.com/PrestaShop/blockreassurance/pull/224): Bump mini-css-extract-plugin from 1.6.0 to 1.6.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#90](https://github.com/PrestaShop/user-documentation-landing/pull/90): fix(deps): bump actions/setup-node from 2.1.5 to 2.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#89](https://github.com/PrestaShop/user-documentation-landing/pull/89): fix(deps): bump core-js from 3.15.1 to 3.15.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#88](https://github.com/PrestaShop/user-documentation-landing/pull/88): chore(deps-dev): bump babel-jest from 27.0.5 to 27.0.6. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#87](https://github.com/PrestaShop/user-documentation-landing/pull/87): chore(deps-dev): bump prettier from 2.3.1 to 2.3.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Email subscription module
* [#82](https://github.com/PrestaShop/ps_emailsubscription/pull/82): Bump version to v2.7.0, by [@atomiix](https://github.com/atomiix)
* [#81](https://github.com/PrestaShop/ps_emailsubscription/pull/81): Fix php8 compatibility, by [@atomiix](https://github.com/atomiix)


### Main menu module
* [#53](https://github.com/PrestaShop/ps_mainmenu/pull/53): Bump version to v2.3.0, by [@atomiix](https://github.com/atomiix)
* [#52](https://github.com/PrestaShop/ps_mainmenu/pull/52): Fix PHP 8 compatibility, by [@atomiix](https://github.com/atomiix)
* [#51](https://github.com/PrestaShop/ps_mainmenu/pull/51): Fix Cannot access protected property `HelperForm::$fields_form`. Thank you [@okom3pom](https://github.com/okom3pom)
* [#24](https://github.com/PrestaShop/ps_mainmenu/pull/24): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Faceted search module
* [#462](https://github.com/PrestaShop/ps_facetedsearch/pull/462): Bump webpack from 5.41.0 to 5.41.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#461](https://github.com/PrestaShop/ps_facetedsearch/pull/461): Bump webpack from 5.40.0 to 5.41.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### presthubot
* [#34](https://github.com/PrestaShop/presthubot/pull/34): Bump league/flysystem from 1.1.3 to 1.1.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#33](https://github.com/PrestaShop/presthubot/pull/33): Use AUTH_ACCESS_TOKEN for GH API, by [@matks](https://github.com/matks)


### Prestashop UI Kit
* [#164](https://github.com/PrestaShop/prestashop-ui-kit/pull/164): Fix spinner colors. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#162](https://github.com/PrestaShop/prestashop-ui-kit/pull/162): Improve prestashop switch design and alignment. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#161](https://github.com/PrestaShop/prestashop-ui-kit/pull/161): Change helpbox icon, by [@NeOMakinG](https://github.com/NeOMakinG)


### Links list module
* [#130](https://github.com/PrestaShop/ps_linklist/pull/130): Bump version 5.0.3, by [@sowbiba](https://github.com/sowbiba)
* [#129](https://github.com/PrestaShop/ps_linklist/pull/129): Release 5.0.3, by [@sowbiba](https://github.com/sowbiba)
* [#128](https://github.com/PrestaShop/ps_linklist/pull/128): Replace `!defined('_CAN_LOAD_FILES_')` by `!defined('_PS_VERSION_')`, by [@matks](https://github.com/matks)


### LocalizationFiles
* [#10](https://github.com/PrestaShop/LocalizationFiles/pull/10): Add a Pull Request template, by [@matks](https://github.com/matks)
* [#8](https://github.com/PrestaShop/LocalizationFiles/pull/8): Reset Germany tax rates. Thank you [@micka-fdz](https://github.com/micka-fdz)


### Product details statistics module
* [#23](https://github.com/PrestaShop/statsproduct/pull/23): Missing deleteds attributes names in product stats module . Thank you [@PululuK](https://github.com/PululuK)


### Example modules
* [#64](https://github.com/PrestaShop/example-modules/pull/64): Multistore forms module example, by [@matthieu-rolland](https://github.com/matthieu-rolland)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matthieu-rolland](https://github.com/matthieu-rolland), [@Progi1984](https://github.com/Progi1984), [@PierreRambaud](https://github.com/PierreRambaud), [@dependabot[bot]](https://github.com/apps/dependabot), [@Sinepel](https://github.com/Sinepel), [@atomiix](https://github.com/atomiix), [@eternoendless](https://github.com/eternoendless), [@Hlavtox](https://github.com/Hlavtox), [@zuk3975](https://github.com/zuk3975), [@jf-viguier](https://github.com/jf-viguier), [@sadeqush](https://github.com/sadeqush), [@okom3pom](https://github.com/okom3pom), [@sowbiba](https://github.com/sowbiba), [@matks](https://github.com/matks), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@NeOMakinG](https://github.com/NeOMakinG), [@NoZTurn](https://github.com/NoZTurn), [@e-gaulue](https://github.com/e-gaulue), [@lmeyer1](https://github.com/lmeyer1), [@kpodemski](https://github.com/kpodemski), [@micka-fdz](https://github.com/micka-fdz), [@PululuK](https://github.com/PululuK), [@samberrry](https://github.com/samberrry), [@Kyaary](https://github.com/Kyaary), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
