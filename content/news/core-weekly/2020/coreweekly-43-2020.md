---
layout: post
aliases: ["/news/coreweekly-43-2020"]
title:  "PrestaShop Core Weekly - Week 43 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-10-26
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 19th to Sunday 25th of October 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages


### 1.7.7.0 Release Candidate 1 status

The QA team is still running the test campaign on the second build for [**Release Candidate 1**](https://github.com/PrestaShop/PrestaShop/issues/18647).

A major issue has been found in this build: [a change made from the Back-Office in an order that does not use the default currency results in the details of this order being displayed with the wrong currency symbol](https://github.com/PrestaShop/PrestaShop/issues/21566) [#21566](https://github.com/PrestaShop/PrestaShop/issues/21566).

Since this issue is located into the "View an Order" Back-Office page, it has been decided that a third build, created after the bug has been fixed, will be necessary. However, this 3rd build test campaign will only target the "Order" Back-Office pages; other areas of the software will not be tested again as they have already been verified during the current test campaign.

**If no other issues are reported, 1.7.7.0 Release Candidate 1 should be delivered by the end of this week.**

### A new external maintainer

The maintainer team welcomed another new member that is not an employee of the PrestaShop Company: [@pululuk](https://github.com/pululuk), who [opened his first Pull Request for the project](https://github.com/PrestaShop/PrestaShop/pull/15706) over a year ago, was granted the maintainer status after [he submitted his application](https://github.com/PrestaShop/open-source/issues/46) on October 2nd. Another major milestone for the project and a warm welcome for him!

### Notable progress on Continuous Integration

Thanks to [@Progi1984](https://github.com/Progi1984), our Continous Integration is now analyzing PrestaShop code under [level 3 of PHPStan](https://github.com/PrestaShop/PrestaShop/pull/21241). PHPStan has been recognized as a quality vector for PHP projects and we hope it will greatly benefit PrestaShop.

### Composer v2 is released

You might have noticed it, the package Manager for PHP [Composer version 2 has been released](https://blog.packagist.com/composer-2-0-is-now-available/)! Some packages and projects need an update to be compatible with it and PrestaShop is no exception. We achieved compatibility with Composer v2 [this morning](https://github.com/PrestaShop/PrestaShop/pull/21609) so you can use this new version when contributing!

## Releases

* [welcome](https://github.com/PrestaShop/welcome) module: [v6.0.3](https://github.com/PrestaShop/welcome/releases/tag/v6.0.3)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [66 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-10-19..2020-10-25) have been created in the project repositories;
- [46 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-10-19..2020-10-25), including [7 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-10-19..2020-10-25) on the core;
- [104 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-10-19..2020-10-25) in the project repositories;
- [76 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-10-19..2020-10-25), including [66 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-10-19..2020-10-25).



## Code changes in the 'develop' branch


### Core
* [#21537](https://github.com/PrestaShop/PrestaShop/pull/21537): Fix typo in Product Object code. Thank you [@PululuK](https://github.com/PululuK)
* [#21499](https://github.com/PrestaShop/PrestaShop/pull/21499): Fixed PHPDoc, by [@Progi1984](https://github.com/Progi1984)
* [#21464](https://github.com/PrestaShop/PrestaShop/pull/21464): index.html  does not exist in INSTALL.txt. Thank you [@okom3pom](https://github.com/okom3pom)


### Back office
* [#21511](https://github.com/PrestaShop/PrestaShop/pull/21511): Remove unused webpack and npm files in admin-dev, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21400](https://github.com/PrestaShop/PrestaShop/pull/21400): Introduce ProductPackUpdater & add behats for packing combinations. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21397](https://github.com/PrestaShop/PrestaShop/pull/21397): Introduce ProductTagUpdater & RemoveAllAssociatedProductTags & RemoveAllAssociatedAttachments command. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21253](https://github.com/PrestaShop/PrestaShop/pull/21253): Rename product price fields labels, by [@marionf](https://github.com/marionf)
* [#21110](https://github.com/PrestaShop/PrestaShop/pull/21110): Use ProductRepository in AddProductHandler. Thank you [@zuk3975](https://github.com/zuk3975)


### Front office
* [#21513](https://github.com/PrestaShop/PrestaShop/pull/21513): Change classic readme in order to avoid missunderstanding, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21490](https://github.com/PrestaShop/PrestaShop/pull/21490): Title tag required to make html 5 valid. Thank you [@taoufiqaitali](https://github.com/taoufiqaitali)
* [#21485](https://github.com/PrestaShop/PrestaShop/pull/21485): Prevent page freeze because off multiple add to cart clicks. Thank you [@kpodemski](https://github.com/kpodemski)


### Tests
* [#21589](https://github.com/PrestaShop/PrestaShop/pull/21589): Fix fail on sanity tests on travis, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21580](https://github.com/PrestaShop/PrestaShop/pull/21580): Update view customer selectors, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21570](https://github.com/PrestaShop/PrestaShop/pull/21570): Upgrade playwright to v1.5.1, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21569](https://github.com/PrestaShop/PrestaShop/pull/21569): Use ubuntu Latest for PHPStan GA, by [@matks](https://github.com/matks)
* [#21517](https://github.com/PrestaShop/PrestaShop/pull/21517): Add test 'Tax rules bulk actions'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21498](https://github.com/PrestaShop/PrestaShop/pull/21498): Fix test 'Download sample file', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21241](https://github.com/PrestaShop/PrestaShop/pull/21241): PHPStan (Level 3), by [@Progi1984](https://github.com/Progi1984)

## Code changes in the '1.7.7.x' branch


### Core
* [#21449](https://github.com/PrestaShop/PrestaShop/pull/21449): Update modules (blockreassurance/dashtrends/ps_checkpayment/welcome), by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#21523](https://github.com/PrestaShop/PrestaShop/pull/21523): Several fixes found via PHPStan while mergin to develop, by [@jolelievre](https://github.com/jolelievre)
* [#21447](https://github.com/PrestaShop/PrestaShop/pull/21447): Synchronize OrderDetail with Cart when removing a voucher, by [@PierreRambaud](https://github.com/PierreRambaud)


### Front office
* [#21507](https://github.com/PrestaShop/PrestaShop/pull/21507): Build core assets, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#21544](https://github.com/PrestaShop/PrestaShop/pull/21544): Fix image name for CRUD title test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21532](https://github.com/PrestaShop/PrestaShop/pull/21532): Update behat and gerkhin to allow debugging in PHPStorm, by [@jolelievre](https://github.com/jolelievre)
* [#21512](https://github.com/PrestaShop/PrestaShop/pull/21512): Add tests 'Helper card' for catalog pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21508](https://github.com/PrestaShop/PrestaShop/pull/21508): Add test 'CRUD search engines', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21505](https://github.com/PrestaShop/PrestaShop/pull/21505): Add test pagination stores, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21497](https://github.com/PrestaShop/PrestaShop/pull/21497): Improve behat config which did not use appropriate format for paths, by [@jolelievre](https://github.com/jolelievre)
* [#21481](https://github.com/PrestaShop/PrestaShop/pull/21481): Add test 'Sort and pagination price rule'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Reminder module
* [#26](https://github.com/PrestaShop/ps_reminder/pull/26): Update short description and logo . Thank you [@Julievrz](https://github.com/Julievrz)


### Customer data privacy block module
* [#22](https://github.com/PrestaShop/ps_dataprivacy/pull/22): Update short description and logo . Thank you [@Julievrz](https://github.com/Julievrz)


### Customer account links module
* [#32](https://github.com/PrestaShop/ps_customeraccountlinks/pull/32): Update short description and logo. Thank you [@Julievrz](https://github.com/Julievrz)


### Customer "Sign in" link module
* [#27](https://github.com/PrestaShop/ps_customersignin/pull/27): Update short description and logo. Thank you [@Julievrz](https://github.com/Julievrz)


### Custom text module
* [#48](https://github.com/PrestaShop/ps_customtext/pull/48): Update short description and logo . Thank you [@Julievrz](https://github.com/Julievrz)


### Currency selector
* [#21](https://github.com/PrestaShop/ps_currencyselector/pull/21): Update short description and logo . Thank you [@Julievrz](https://github.com/Julievrz)


### Contact informations module
* [#41](https://github.com/PrestaShop/ps_contactinfo/pull/41): Update short description and logo . Thank you [@Julievrz](https://github.com/Julievrz)


### Changes in developer documentation
* [#786](https://github.com/PrestaShop/docs/pull/786): Remove references to the Starter Theme, by [@eternoendless](https://github.com/eternoendless)
* [#784](https://github.com/PrestaShop/docs/pull/784): Add a link to the classic theme on the starter theme doc page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#780](https://github.com/PrestaShop/docs/pull/780): Explain 90 day trial period for new maintainers, by [@matks](https://github.com/matks)
* [#779](https://github.com/PrestaShop/docs/pull/779): Update Hugo to latest version 0.76.5, by [@eternoendless](https://github.com/eternoendless)
* [#770](https://github.com/PrestaShop/docs/pull/770): Add hooks to cart modal - crosseling and promotion. Thank you [@PululuK](https://github.com/PululuK)
* [#733](https://github.com/PrestaShop/docs/pull/733): Correcting the legacy front services scope. Thank you [@moncef-essid](https://github.com/moncef-essid)


### Faceted search module
* [#243](https://github.com/PrestaShop/ps_facetedsearch/pull/243): Bump sass-loader from 10.0.3 to 10.0.4. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#242](https://github.com/PrestaShop/ps_facetedsearch/pull/242): Bump webpack from 4.44.2 to 5.2.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#236](https://github.com/PrestaShop/ps_facetedsearch/pull/236): Bump mocha from 8.1.3 to 8.2.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#235](https://github.com/PrestaShop/ps_facetedsearch/pull/235): Bump @babel/core from 7.12.1 to 7.12.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#234](https://github.com/PrestaShop/ps_facetedsearch/pull/234): Bump @babel/cli from 7.12.0 to 7.12.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#233](https://github.com/PrestaShop/ps_facetedsearch/pull/233): Bump @babel/preset-env from 7.12.0 to 7.12.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#232](https://github.com/PrestaShop/ps_facetedsearch/pull/232): Bump @babel/node from 7.10.5 to 7.12.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Contact Form module
* [#55](https://github.com/PrestaShop/contactform/pull/55): Update short description and logo. Thank you [@Julievrz](https://github.com/Julievrz)
* [#54](https://github.com/PrestaShop/contactform/pull/54): Implement empty listener for registerGDPRConsent hook, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Category tree links module
* [#41](https://github.com/PrestaShop/ps_categorytree/pull/41): Update short description and logo. Thank you [@Julievrz](https://github.com/Julievrz)


### Nightly board
* [#48](https://github.com/PrestaShop/nightly-board/pull/48): Change variance into vs last execution, by [@NeOMakinG](https://github.com/NeOMakinG)


### Wishlist block module
* [#93](https://github.com/PrestaShop/blockwishlist/pull/93): set stats by shop id. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#92](https://github.com/PrestaShop/blockwishlist/pull/92): Fix the help link. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#91](https://github.com/PrestaShop/blockwishlist/pull/91): Fix menu. Thank you [@pablopolyte](https://github.com/pablopolyte)


### PrestaShop Specifications
* [#159](https://github.com/PrestaShop/prestashop-specs/pull/159): add specs for features, brands and tax rules in the add / edit product page, by [@marionf](https://github.com/marionf)


### Cash on delivery module
* [#33](https://github.com/PrestaShop/ps_cashondelivery/pull/33): Update short description and logo. Thank you [@Julievrz](https://github.com/Julievrz)


### OnBoarding module
* [#88](https://github.com/PrestaShop/welcome/pull/88): Release 6.0.3, by [@Progi1984](https://github.com/Progi1984)
* [#87](https://github.com/PrestaShop/welcome/pull/87): Fix wrong conditions on steps, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#81](https://github.com/PrestaShop/welcome/pull/81): Bump node-sass from 4.13.1 to 4.14.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#77](https://github.com/PrestaShop/welcome/pull/77): Bump node-sass from 3.13.1 to 4.13.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Product Comments module
* [#74](https://github.com/PrestaShop/productcomments/pull/74): Implement empty listener for registerGDPRConsent hook, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Gamification module
* [#72](https://github.com/PrestaShop/gamification/pull/72): Fix gamification PNG Error on NGINX. Thank you [@davidglezz](https://github.com/davidglezz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@Julievrz](https://github.com/Julievrz), [@eternoendless](https://github.com/eternoendless), [@dependabot[bot]](https://github.com/apps/dependabot), [@matks](https://github.com/matks), [@NeOMakinG](https://github.com/NeOMakinG), [@pablopolyte](https://github.com/pablopolyte), [@marionf](https://github.com/marionf), [@PululuK](https://github.com/PululuK), [@jolelievre](https://github.com/jolelievre), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@Progi1984](https://github.com/Progi1984), [@taoufiqaitali](https://github.com/taoufiqaitali), [@kpodemski](https://github.com/kpodemski), [@matthieu-rolland](https://github.com/matthieu-rolland), [@okom3pom](https://github.com/okom3pom), [@PierreRambaud](https://github.com/PierreRambaud), [@zuk3975](https://github.com/zuk3975), [@moncef-essid](https://github.com/moncef-essid), [@davidglezz](https://github.com/davidglezz)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
