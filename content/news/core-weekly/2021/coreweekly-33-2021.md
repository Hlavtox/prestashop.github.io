---
layout: post
aliases: ["/news/coreweekly-33-2021"]
title:  "PrestaShop Core Weekly - Week 33 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-08-26
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 16th to Sunday 22th of August 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

[PrestaShop 1.7.7.7](https://build.prestashop.com/news/prestashop-1-7-7-7-maintenance-release/) was released on Thursday 19th of August 2021. This maintenance release fixes 1 critical regression and 1 minor regression.

Interestingly, while the `1.7.7.x` branch was getting this new release, the `8.1.x` branch of PHP was also getting a [third beta](https://www.php.net/archive/2021.php#2021-08-19-1).

Small reminder, the next session of public demonstration from the maintainers team will happen [**Wednesday 1st of September 2021 at 4pm CEST**](https://www.youtube.com/watch?v=9oEBquMz008).


## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop): [1.7.7.7](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.7.7)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [46 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-08-16..2021-08-22) have been created in the project repositories;
- [37 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-08-16..2021-08-22), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-08-16..2021-08-22) on the core;
- [37 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-08-16..2021-08-22) in the project repositories;
- [50 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-08-16..2021-08-22), including [45 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-08-16..2021-08-22).



## Code changes in the 'develop' branch


### Core
* [#25636](https://github.com/PrestaShop/PrestaShop/pull/25636): Restore Carrier class history, by [@eternoendless](https://github.com/eternoendless)
* [#25572](https://github.com/PrestaShop/PrestaShop/pull/25572): Do not upgrade module on module installation process, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25563](https://github.com/PrestaShop/PrestaShop/pull/25563): Deprecate FrameworkBundleAdminController::overviewAction, by [@eternoendless](https://github.com/eternoendless)
* [#21227](https://github.com/PrestaShop/PrestaShop/pull/21227): Refactor ObjectModel::existsInDatabase. Thank you [@PululuK](https://github.com/PululuK)


### Back office
* [#25573](https://github.com/PrestaShop/PrestaShop/pull/25573): Remove unused-var in AdminImportController. Thank you [@nenes25](https://github.com/nenes25)
* [#25548](https://github.com/PrestaShop/PrestaShop/pull/25548): Set template for customization in div, by [@Progi1984](https://github.com/Progi1984)
* [#25491](https://github.com/PrestaShop/PrestaShop/pull/25491): Fix actionAdminOrdersTrackingNumberUpdate. Thank you [@ytilotti](https://github.com/ytilotti)
* [#25442](https://github.com/PrestaShop/PrestaShop/pull/25442): Fix module uninstallation from the Module Manager, by [@kpodemski](https://github.com/kpodemski)


### Front office
* [#25567](https://github.com/PrestaShop/PrestaShop/pull/25567): Use `_DB_PREFIX_` constant instead of ps_ in SQL queries. Thank you [@idnovate](https://github.com/idnovate)
* [#25460](https://github.com/PrestaShop/PrestaShop/pull/25460): Fix missing row element and additional padding. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#23803](https://github.com/PrestaShop/PrestaShop/pull/23803): Fix static vars not using scss vars on new-theme and classic, by [@NeOMakinG](https://github.com/NeOMakinG)


### Installer
* [#25596](https://github.com/PrestaShop/PrestaShop/pull/25596): Provide full stack trace when install fails, by [@eternoendless](https://github.com/eternoendless)


### Tests
* [#25580](https://github.com/PrestaShop/PrestaShop/pull/25580): Add class to identify pagination block on product page, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.8.x' branch


### Core
* [#25613](https://github.com/PrestaShop/PrestaShop/pull/25613): Fix missing hook behavior when using array return, by [@kpodemski](https://github.com/kpodemski)


### Back office
* [#25557](https://github.com/PrestaShop/PrestaShop/pull/25557): Fix floating button spacing on migrated pages, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25386](https://github.com/PrestaShop/PrestaShop/pull/25386): Fixed selector call for enabling back the confirmation modal when changing the currency by default, by [@Progi1984](https://github.com/Progi1984)
* [#25205](https://github.com/PrestaShop/PrestaShop/pull/25205): Moved addresses block in BO Customer Page, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#25665](https://github.com/PrestaShop/PrestaShop/pull/25665): Load medium size thumbnail on click on FO product page instead of large, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#25635](https://github.com/PrestaShop/PrestaShop/pull/25635): Fix html lang attribute to use the locale instead of ISO code, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25192](https://github.com/PrestaShop/PrestaShop/pull/25192): Make searchbar full width on md and xs, by [@NeOMakinG](https://github.com/NeOMakinG)


## Code changes in the '1.7.7.x' branch


### Core
* [#25630](https://github.com/PrestaShop/PrestaShop/pull/25630): Bump version to 1.7.7.7, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#25634](https://github.com/PrestaShop/PrestaShop/pull/25634): Do not use name in admin_orders_display_customization_image_route, by [@PierreRambaud](https://github.com/PierreRambaud)


### Front office
* [#25629](https://github.com/PrestaShop/PrestaShop/pull/25629): Use `_DB_PREFIX_` constant instead of ps_ in SQL queries, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in modules, themes & tools


### Faceted search module
* [#494](https://github.com/PrestaShop/ps_facetedsearch/pull/494): Bump mocha from 9.0.2 to 9.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#493](https://github.com/PrestaShop/ps_facetedsearch/pull/493): Bump eslint-plugin-import from 2.24.0 to 2.24.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#492](https://github.com/PrestaShop/ps_facetedsearch/pull/492): Bump webpack from 5.50.0 to 5.51.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer reassurance block module
* [#257](https://github.com/PrestaShop/blockreassurance/pull/257): Bump webpack from 5.50.0 to 5.51.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#256](https://github.com/PrestaShop/blockreassurance/pull/256): Bump eslint-plugin-import from 2.24.0 to 2.24.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#255](https://github.com/PrestaShop/blockreassurance/pull/255): Bump webpack-cli from 4.7.2 to 4.8.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#254](https://github.com/PrestaShop/blockreassurance/pull/254): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#125](https://github.com/PrestaShop/welcome/pull/125): Bump eslint-plugin-import from 2.24.0 to 2.24.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation sources
* [#1130](https://github.com/PrestaShop/docs/pull/1130): Add a missing s to a sentence, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#1128](https://github.com/PrestaShop/docs/pull/1128): Update tools-for-theme-designers. Thank you [@WebHelpersPau](https://github.com/WebHelpersPau)
* [#1127](https://github.com/PrestaShop/docs/pull/1127): Update good module practices. Thank you [@Thymotep](https://github.com/Thymotep)
* [#1126](https://github.com/PrestaShop/docs/pull/1126): Improve a little overriding module page, by [@matks](https://github.com/matks)


### Changes in developer documentation site
* [#6](https://github.com/PrestaShop/devdocs-site/pull/6): Add Submodules Sync badge in README, by [@matks](https://github.com/matks)


### Docker images
* [#272](https://github.com/PrestaShop/docker/pull/272): Release 1.7.7.7, by [@PierreRambaud](https://github.com/PierreRambaud)


### User documentation landing page
* [#108](https://github.com/PrestaShop/user-documentation-landing/pull/108): chore(deps-dev): bump sass from 1.37.5 to 1.38.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#107](https://github.com/PrestaShop/user-documentation-landing/pull/107): fix(deps): bump core-js from 3.16.1 to 3.16.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Core Weekly Generator tool
* [#101](https://github.com/PrestaShop/core-weekly-generator/pull/101): Bump url-parse from 1.5.1 to 1.5.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop contributors website
* [#55](https://github.com/PrestaShop/TopContributors/pull/55): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Buy button lite module
* [#53](https://github.com/PrestaShop/ps_buybuttonlite/pull/53): Bump color-string from 1.5.3 to 1.6.0 in /app. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### TranslationTools Bundle
* [#100](https://github.com/PrestaShop/TranslationToolsBundle/pull/100): Fix license headers and add LICENSE.md file, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@eternoendless](https://github.com/eternoendless), [@matthieu-rolland](https://github.com/matthieu-rolland), [@dependabot[bot]](https://github.com/apps/dependabot), [@PierreRambaud](https://github.com/PierreRambaud), [@WebHelpersPau](https://github.com/WebHelpersPau), [@Thymotep](https://github.com/Thymotep), [@matks](https://github.com/matks), [@NeOMakinG](https://github.com/NeOMakinG), [@kpodemski](https://github.com/kpodemski), [@boubkerbribri](https://github.com/boubkerbribri), [@nenes25](https://github.com/nenes25), [@idnovate](https://github.com/idnovate), [@Progi1984](https://github.com/Progi1984), [@ytilotti](https://github.com/ytilotti), [@Hlavtox](https://github.com/Hlavtox), [@PululuK](https://github.com/PululuK)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
