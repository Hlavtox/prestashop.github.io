---
layout: post
aliases: ["/news/coreweekly-05-2021"]
title:  "PrestaShop Core Weekly - Week 5 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-02-08
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 1st to Sunday 7th of February 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Have you read ["PHP, Scalability & Filesystems"](https://build.prestashop.com/news/PHP-scalability-and-filesystem/) that was published last week on this blog?

This is the third article of the [performance series](https://build.prestashop.com/news/performance-and-prestashop/) started in 2020 by [@djodjo3](http://github.com/djodjo3) who is Lead DevOps at PrestaShop company. This article is about PHP, scalability and its impact on the filesystem.

In the meantime, the Pull Request for a new [multishop header search mechanism](https://github.com/PrestaShop/PrestaShop/pull/21593) by [@matthieu-rolland](https://github.com/matthieu-rolland) has been merged, it's one important milestone for the [new multishop header for migrated pages](https://github.com/PrestaShop/PrestaShop/issues/19300) project for PrestaShop 1.7.8.

Also a v5.0.0 version is [being](https://github.com/PrestaShop/autoupgrade/pull/376) [prepared](https://github.com/PrestaShop/autoupgrade/pull/374) for module [autoupgrade](https://github.com/PrestaShop/autoupgrade) with some fixes related to upgrades from PrestaShop 1.6 to PrestaShop 1.7.7.


## Releases

* [ps_dataprivacy](https://github.com/PrestaShop/ps_dataprivacy): [v2.0.1](https://github.com/PrestaShop/ps_dataprivacy/releases/tag/v2.0.1)
* [Traces](https://github.com/PrestaShop/traces): [v5.2.1](https://github.com/PrestaShop/traces/releases/tag/v5.2.1)
* [ps_themecusto](https://github.com/PrestaShop/ps_themecusto): [v1.2.1](https://github.com/PrestaShop/ps_themecusto/releases/tag/v1.2.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [66 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-02-01..2021-02-07) have been created in the project repositories;
- [47 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-02-01..2021-02-07), including [12 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-02-01..2021-02-07) on the core;
- [81 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-02-01..2021-02-07) in the project repositories;
- [95 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-02-01..2021-02-07), including [73 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-02-01..2021-02-07).



## Code changes in the 'develop' branch


### Core
* [#23153](https://github.com/PrestaShop/PrestaShop/pull/23153): Swap count() && is_array() pattern to avoid PHP7.2+ warning. Thank you [@morgoth6](https://github.com/morgoth6)
* [#23055](https://github.com/PrestaShop/PrestaShop/pull/23055): Add EAN13 and MPN to combinations data. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#23034](https://github.com/PrestaShop/PrestaShop/pull/23034): Update stylelint with breakline rule and run fix with it, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21593](https://github.com/PrestaShop/PrestaShop/pull/21593): Multishop search mechanism for header, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#23092](https://github.com/PrestaShop/PrestaShop/pull/23092): Fix fields width when view is disabled on product page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23088](https://github.com/PrestaShop/PrestaShop/pull/23088): Introduce Product Feature value command, by [@jolelievre](https://github.com/jolelievre)
* [#23076](https://github.com/PrestaShop/PrestaShop/pull/23076): Add deprecation notice on $location of Product and Combination. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23052](https://github.com/PrestaShop/PrestaShop/pull/23052): Improve responsivity of customer block in order admin. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#23044](https://github.com/PrestaShop/PrestaShop/pull/23044): Manage product redirection in SEO tab, by [@jolelievre](https://github.com/jolelievre)
* [#22919](https://github.com/PrestaShop/PrestaShop/pull/22919): Fix spacing, padding and bugs on responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22886](https://github.com/PrestaShop/PrestaShop/pull/22886): Add stylelint on default BO theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22743](https://github.com/PrestaShop/PrestaShop/pull/22743): Integrate suppliers form in product options. Thank you [@zuk3975](https://github.com/zuk3975)
* [#22148](https://github.com/PrestaShop/PrestaShop/pull/22148): Fix specific prices redution form. Thank you [@PululuK](https://github.com/PululuK)


### Front office
* [#23074](https://github.com/PrestaShop/PrestaShop/pull/23074): Stylise list in product short description of quickview, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23073](https://github.com/PrestaShop/PrestaShop/pull/23073): Fix product description lists color on FO, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23121](https://github.com/PrestaShop/PrestaShop/pull/23121): Fix tests after merge 177x to develop 02/02/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23090](https://github.com/PrestaShop/PrestaShop/pull/23090): Change author name for pull request triggered by cron, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.7.x' branch


### Core
* [#23139](https://github.com/PrestaShop/PrestaShop/pull/23139): Update pear/archive_tar to 1.4.12, by [@matks](https://github.com/matks)


### Back office
* [#22980](https://github.com/PrestaShop/PrestaShop/pull/22980): Replaced hooks `displayAdminList<Before|After>` with `displayAdminGridTable<Before|After>`, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#23144](https://github.com/PrestaShop/PrestaShop/pull/23144): Add test - Check footer links on FO. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23023](https://github.com/PrestaShop/PrestaShop/pull/23023): Add test 'Carrier options - order by ascending/descending '. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23004](https://github.com/PrestaShop/PrestaShop/pull/23004): Add test 'Languages pagination'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Customer reassurance block module
* [#122](https://github.com/PrestaShop/blockreassurance/pull/122): Bump webpack from 5.20.1 to 5.20.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#121](https://github.com/PrestaShop/blockreassurance/pull/121): Bump webpack from 5.20.0 to 5.20.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#120](https://github.com/PrestaShop/blockreassurance/pull/120): Bump webpack from 5.19.0 to 5.20.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#119](https://github.com/PrestaShop/blockreassurance/pull/119): Bump webpack-cli from 4.4.0 to 4.5.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#118](https://github.com/PrestaShop/blockreassurance/pull/118): Bump @babel/core from 7.12.10 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#117](https://github.com/PrestaShop/blockreassurance/pull/117): Bump webpack from 5.18.0 to 5.19.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#324](https://github.com/PrestaShop/ps_facetedsearch/pull/324): Bump webpack from 5.20.1 to 5.20.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#323](https://github.com/PrestaShop/ps_facetedsearch/pull/323): Bump chai from 4.2.0 to 4.3.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#322](https://github.com/PrestaShop/ps_facetedsearch/pull/322): Bump webpack from 5.20.0 to 5.20.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#321](https://github.com/PrestaShop/ps_facetedsearch/pull/321): Bump webpack from 5.19.0 to 5.20.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#320](https://github.com/PrestaShop/ps_facetedsearch/pull/320): Bump @babel/core from 7.12.10 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#319](https://github.com/PrestaShop/ps_facetedsearch/pull/319): Bump @babel/cli from 7.12.10 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#318](https://github.com/PrestaShop/ps_facetedsearch/pull/318): Bump @babel/register from 7.12.10 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#317](https://github.com/PrestaShop/ps_facetedsearch/pull/317): Bump @babel/preset-env from 7.12.11 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#316](https://github.com/PrestaShop/ps_facetedsearch/pull/316): Bump @babel/node from 7.12.10 to 7.12.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#314](https://github.com/PrestaShop/ps_facetedsearch/pull/314): Bump webpack from 5.18.0 to 5.19.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#312](https://github.com/PrestaShop/ps_facetedsearch/pull/312): Bump eslint-config-prestashop from 0.0.2 to 0.1.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#302](https://github.com/PrestaShop/ps_facetedsearch/pull/302): Fix migration from blocklayered, by [@atomiix](https://github.com/atomiix)
* [#301](https://github.com/PrestaShop/ps_facetedsearch/pull/301): Fix how to use url_name parameter in features and attributes, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#300](https://github.com/PrestaShop/ps_facetedsearch/pull/300): Optimize price search, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#295](https://github.com/PrestaShop/ps_facetedsearch/pull/295): Always sort by id_product when there is similar result, by [@PierreRambaud](https://github.com/PierreRambaud)


### Customer "Sign in" link module
* [#32](https://github.com/PrestaShop/ps_customersignin/pull/32): Bump version to 2.0.4 and add badge in README, by [@matks](https://github.com/matks)


### Search Bar module
* [#29](https://github.com/PrestaShop/ps_searchbar/pull/29): Bump version to 2.1.1 and add badge in README, by [@matks](https://github.com/matks)


### Banner module
* [#27](https://github.com/PrestaShop/ps_banner/pull/27): Add latest github version badge in readme, by [@matks](https://github.com/matks)
* [#26](https://github.com/PrestaShop/ps_banner/pull/26): Bump version to v2.1.1 and add prepend-autoloader false, by [@matks](https://github.com/matks)


### Gamification module
* [#78](https://github.com/PrestaShop/gamification/pull/78): Fixed path for badge images on migrated pages, by [@Progi1984](https://github.com/Progi1984)


### QA nightly results
* [#54](https://github.com/PrestaShop/QANightlyResults/pull/54): Bump illuminate/database from 6.20.13 to 6.20.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Traces
* [#17](https://github.com/PrestaShop/traces/pull/17): Exclude Prestashop 1.5 from analysis, by [@Progi1984](https://github.com/Progi1984)
* [#16](https://github.com/PrestaShop/traces/pull/16): Do not ignore archived projects, by [@PierreRambaud](https://github.com/PierreRambaud)


### Prestashop UI Kit
* [#136](https://github.com/PrestaShop/prestashop-ui-kit/pull/136): Adjust floating button style according to design team, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#135](https://github.com/PrestaShop/prestashop-ui-kit/pull/135): Add floating button to storybook, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#132](https://github.com/PrestaShop/prestashop-ui-kit/pull/132): Add migrate to the UIKit, by [@NeOMakinG](https://github.com/NeOMakinG)


### User documentation landing page
* [#23](https://github.com/PrestaShop/user-documentation-landing/pull/23): chore(deps-dev): bump sass from 1.32.5 to 1.32.6. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#22](https://github.com/PrestaShop/user-documentation-landing/pull/22): chore(deps-dev): bump eslint from 7.18.0 to 7.19.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#853](https://github.com/PrestaShop/docs/pull/853): min version compat for tinymce config override. Thank you [@kpodemski](https://github.com/kpodemski)
* [#624](https://github.com/PrestaShop/docs/pull/624): How to release PS, part 1, by [@matks](https://github.com/matks)


### PrestaShop-modules
* [#443](https://github.com/PrestaShop/PrestaShop-modules/pull/443): Remove 1.6 modules, by [@Progi1984](https://github.com/Progi1984)


### Auto Upgrade module
* [#378](https://github.com/PrestaShop/autoupgrade/pull/378): Fix phpstan tests, by [@atomiix](https://github.com/atomiix)
* [#376](https://github.com/PrestaShop/autoupgrade/pull/376): Clear cache before enabling theme, by [@atomiix](https://github.com/atomiix)
* [#374](https://github.com/PrestaShop/autoupgrade/pull/374): Fix error with private method and upgrade. Thank you [@nenes25](https://github.com/nenes25)


### Wishlist block module
* [#97](https://github.com/PrestaShop/blockwishlist/pull/97): Fix stats cache per shop id. Thank you [@pablopolyte](https://github.com/pablopolyte)


### PrestonBot
* [#113](https://github.com/PrestaShop/prestonbot/pull/113): Use Bux fix label instead of Bug, by [@atomiix](https://github.com/atomiix)


### OnBoarding module
* [#100](https://github.com/PrestaShop/welcome/pull/100): Bump eslint-config-prestashop from 0.0.2 to 0.1.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Example modules
* [#41](https://github.com/PrestaShop/example-modules/pull/41): Fix composer autoloader configuration for demosymfonyform, by [@matks](https://github.com/matks)
* [#35](https://github.com/PrestaShop/example-modules/pull/35): Rewrite demoextendsymfonyform1 module without CQRS, by [@matks](https://github.com/matks)


### Google Analytics module
* [#85](https://github.com/PrestaShop/ps_googleanalytics/pull/85): Update HookDisplayOrderConfirmation.php. Thank you [@Shoprunners](https://github.com/Shoprunners)


### Customer data privacy block module
* [#25](https://github.com/PrestaShop/ps_dataprivacy/pull/25): Release 2.0.1, by [@Progi1984](https://github.com/Progi1984)


### Theme customization module
* [#37](https://github.com/PrestaShop/ps_themecusto/pull/37): Release 1.2.1, by [@Progi1984](https://github.com/Progi1984)


## Where to start contributing?

What about [redirecting the customer to Product page after he created an account on Front Office](https://github.com/PrestaShop/PrestaShop/issues/18762)? This is a feature request submitted last year by a contributor, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@morgoth6](https://github.com/morgoth6), [@dependabot[bot]](https://github.com/apps/dependabot), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@matks](https://github.com/matks), [@Progi1984](https://github.com/Progi1984), [@PululuK](https://github.com/PululuK), [@Amin-Hosseini](https://github.com/Amin-Hosseini), [@NeOMakinG](https://github.com/NeOMakinG), [@PierreRambaud](https://github.com/PierreRambaud), [@jolelievre](https://github.com/jolelievre), [@kpodemski](https://github.com/kpodemski), [@zuk3975](https://github.com/zuk3975), [@atomiix](https://github.com/atomiix), [@Hlavtox](https://github.com/Hlavtox), [@pablopolyte](https://github.com/pablopolyte), [@Shoprunners](https://github.com/Shoprunners), [@nenes25](https://github.com/nenes25), [@matthieu-rolland](https://github.com/matthieu-rolland)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
