---
layout: post
aliases: ["/news/coreweekly-49-2020"]
title:  "PrestaShop Core Weekly - Week 49 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-12-08
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 30th of November to Sunday 6th of December 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

In case you did not see it, [PrestaShop 1.7.7.0](https://build.prestashop.com/news/prestashop-1-7-7-0-available/) was released last week!

Note that if you plan on upgrading your shop to 1.7.7 and your current version is below 1.7.6 you need the latest version ([v4.11.0](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.11.0)) of the autoupgrade module.

As usual, it is recommended to be careful before starting to update your website to the latest version:

- Backup your database and your files
- Test the update on a testing or pre production server
- If everything is fine, then update on the production environment

Following the early adoption of PrestaShop 1.7.7, [some bug reports](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aopen+is%3Aissue+label%3AAutoupgrade+label%3A1.7.7.0) have been submitted about upgrade issues. The maintainer and QA team are all hands on deck exploring and fixing these issues.

If you notice issues with PrestaShop 1.7.7.0, you can [report it on GitHub](https://github.com/PrestaShop/PrestaShop/issues) and go even further by submitting a [pull request](https://github.com/PrestaShop/PrestaShop/compare) to help fix it!

## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop): [PrestaShop 1.7.7.0](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.7.0)
* [productcomments](https://github.com/PrestaShop/productcomments) module: [v4.2.1](https://github.com/PrestaShop/productcomments/releases/tag/v4.2.1)
* [autoupgrade](https://github.com/PrestaShop/autoupgrade) module: [v4.11.0](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.11.0)
* [welcome](https://github.com/PrestaShop/welcome) module: [v6.0.4](https://github.com/PrestaShop/welcome/releases/tag/v6.0.4)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [74 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-11-30..2020-12-06) have been created in the project repositories;
- [76 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-11-30..2020-12-06), including [39 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-11-30..2020-12-06) on the core;
- [96 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-11-30..2020-12-06) in the project repositories;
- [109 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-11-30..2020-12-06), including [97 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-11-30..2020-12-06).



## Code changes in the 'develop' branch


### Core
* [#22212](https://github.com/PrestaShop/PrestaShop/pull/22212): Fix missing comma in 1.7.8.0 update script, by [@eternoendless](https://github.com/eternoendless)
* [#22183](https://github.com/PrestaShop/PrestaShop/pull/22183): Fix phpDoc in Db. Thank you [@ksaandev](https://github.com/ksaandev)
* [#21075](https://github.com/PrestaShop/PrestaShop/pull/21075): Improve admin logs . Thank you [@PululuK](https://github.com/PululuK)


### Back office
* [#22167](https://github.com/PrestaShop/PrestaShop/pull/22167): Add UpdateCombinationPrices command. Thank you [@zuk3975](https://github.com/zuk3975)
* [#22132](https://github.com/PrestaShop/PrestaShop/pull/22132): Add UpdateCombinationOptionsCommand [product page migration]. Thank you [@zuk3975](https://github.com/zuk3975)
* [#22102](https://github.com/PrestaShop/PrestaShop/pull/22102): Fix payment layout broken on small screens, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22079](https://github.com/PrestaShop/PrestaShop/pull/22079): Use the same condition as it is in ShopUrlType, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22073](https://github.com/PrestaShop/PrestaShop/pull/22073): Adjust container of positions page and alert size, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21972](https://github.com/PrestaShop/PrestaShop/pull/21972): Change wrongs growls used into success one, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21939](https://github.com/PrestaShop/PrestaShop/pull/21939): Fix number increase and validate button position on stock page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21468](https://github.com/PrestaShop/PrestaShop/pull/21468): Add event and object assign to symfony routes JS side, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21309](https://github.com/PrestaShop/PrestaShop/pull/21309): Restore See More & See less for the Module Manager, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#21234](https://github.com/PrestaShop/PrestaShop/pull/21234): Simplified customer preferences. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#20125](https://github.com/PrestaShop/PrestaShop/pull/20125): Multistore: assign a color to a shop group, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Front office
* [#22076](https://github.com/PrestaShop/PrestaShop/pull/22076): Add new column template for displayLeft/Right hook, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21996](https://github.com/PrestaShop/PrestaShop/pull/21996): Update logo name without shop name. Thank you [@jeckyl](https://github.com/jeckyl)


### Installer
* [#22234](https://github.com/PrestaShop/PrestaShop/pull/22234): Remove .docker folder on Release. Thank you [@okom3pom](https://github.com/okom3pom)
* [#22207](https://github.com/PrestaShop/PrestaShop/pull/22207): Put invoice customization products on one line, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#22225](https://github.com/PrestaShop/PrestaShop/pull/22225): Bump PHP version for GitHub Actions to php7.4, by [@matks](https://github.com/matks)
* [#22194](https://github.com/PrestaShop/PrestaShop/pull/22194): Delete unused function on the linkchecker, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22184](https://github.com/PrestaShop/PrestaShop/pull/22184): Fix step sorting by date in test "Sort and pagination cart rules", by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Core
* [#22182](https://github.com/PrestaShop/PrestaShop/pull/22182): Update pear/archive_tar to 1.4.11, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22178](https://github.com/PrestaShop/PrestaShop/pull/22178): Set numeric_iso_code & precision in currency from CLDR when upgrading, by [@atomiix](https://github.com/atomiix)
* [#22174](https://github.com/PrestaShop/PrestaShop/pull/22174): Use displayHeader hook instead of Header, by [@atomiix](https://github.com/atomiix)
* [#22164](https://github.com/PrestaShop/PrestaShop/pull/22164): Fix upgrade script from < 1.7.6.0 to 1.7.7.0, by [@atomiix](https://github.com/atomiix)
* [#22146](https://github.com/PrestaShop/PrestaShop/pull/22146): Remove --classmap-authoritative when building release, by [@atomiix](https://github.com/atomiix)
* [#21988](https://github.com/PrestaShop/PrestaShop/pull/21988): Fix order detail total amount update when rounding is per item, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#22191](https://github.com/PrestaShop/PrestaShop/pull/22191): Validate currency localized names, by [@jolelievre](https://github.com/jolelievre)
* [#22189](https://github.com/PrestaShop/PrestaShop/pull/22189): Trigger input when a predefined message is applied, by [@Progi1984](https://github.com/Progi1984)
* [#22101](https://github.com/PrestaShop/PrestaShop/pull/22101): Fix product selections when creating/updating tags, by [@atomiix](https://github.com/atomiix)
* [#22099](https://github.com/PrestaShop/PrestaShop/pull/22099): Fix employee filter for the Logs page, by [@atomiix](https://github.com/atomiix)
* [#22077](https://github.com/PrestaShop/PrestaShop/pull/22077): Create Order - Fix remove cart rule when amount is not reached, by [@sowbiba](https://github.com/sowbiba)
* [#22059](https://github.com/PrestaShop/PrestaShop/pull/22059): Add Payments block refresher - Refresh when product is added or removed from Order, by [@sowbiba](https://github.com/sowbiba)
* [#22028](https://github.com/PrestaShop/PrestaShop/pull/22028): Update out of stock mail wording, by [@jolelievre](https://github.com/jolelievre)
* [#21992](https://github.com/PrestaShop/PrestaShop/pull/21992): Make customer note TYPE_STRING instead of TYPE_HTML, by [@atomiix](https://github.com/atomiix)
* [#21980](https://github.com/PrestaShop/PrestaShop/pull/21980): Fixed the error message for a combination with a min quantity for sale, by [@Progi1984](https://github.com/Progi1984)
* [#21568](https://github.com/PrestaShop/PrestaShop/pull/21568): Fixed in Create Order the update of cart rules when changing adress , by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#22103](https://github.com/PrestaShop/PrestaShop/pull/22103): Display combination image in product pack list, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#22209](https://github.com/PrestaShop/PrestaShop/pull/22209): Backport fix on UI sort tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22198](https://github.com/PrestaShop/PrestaShop/pull/22198): Add static cache resets, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#22172](https://github.com/PrestaShop/PrestaShop/pull/22172): Backport UI tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22012](https://github.com/PrestaShop/PrestaShop/pull/22012): Fix random fails in travis CI, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#821](https://github.com/PrestaShop/docs/pull/821): Fix typo front controller page, by [@matks](https://github.com/matks)
* [#820](https://github.com/PrestaShop/docs/pull/820): Add informations about the mail() method not being used anymore, by [@atomiix](https://github.com/atomiix)
* [#819](https://github.com/PrestaShop/docs/pull/819): Fix refund code example for Prestashop 1.7.6. Thank you [@yannicka](https://github.com/yannicka)
* [#816](https://github.com/PrestaShop/docs/pull/816): Document Autoupgrade module CLI and channels, by [@matks](https://github.com/matks)
* [#772](https://github.com/PrestaShop/docs/pull/772): More informations about migrating from 1.6. Thank you [@kpodemski](https://github.com/kpodemski)


### Faceted search module
* [#274](https://github.com/PrestaShop/ps_facetedsearch/pull/274): Fixed invalid composer.json, by [@Progi1984](https://github.com/Progi1984)
* [#273](https://github.com/PrestaShop/ps_facetedsearch/pull/273): Fix PHPStan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#270](https://github.com/PrestaShop/ps_facetedsearch/pull/270): Bump webpack from 5.8.0 to 5.9.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop contributors website
* [#32](https://github.com/PrestaShop/TopContributors/pull/32): Merge develop into master, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#31](https://github.com/PrestaShop/TopContributors/pull/31): Add copy link button on contributors, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#30](https://github.com/PrestaShop/TopContributors/pull/30): Merge develop into master, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#29](https://github.com/PrestaShop/TopContributors/pull/29): Hide email domain and hide roles if no roles are provided, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#28](https://github.com/PrestaShop/TopContributors/pull/28): Rebase develop, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#27](https://github.com/PrestaShop/TopContributors/pull/27): Merge develop into master, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#26](https://github.com/PrestaShop/TopContributors/pull/26): Modify CI and fix eslint, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25](https://github.com/PrestaShop/TopContributors/pull/25): Merge develop into master, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#24](https://github.com/PrestaShop/TopContributors/pull/24): Prepare improvements and add contributor modal, by [@NeOMakinG](https://github.com/NeOMakinG)


### OnBoarding module
* [#96](https://github.com/PrestaShop/welcome/pull/96): Use master instead of current branch for release drafter, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#95](https://github.com/PrestaShop/welcome/pull/95): Release 6.0.4, by [@Progi1984](https://github.com/Progi1984)
* [#94](https://github.com/PrestaShop/welcome/pull/94): Bump version to 6.0.4, by [@Progi1984](https://github.com/Progi1984)
* [#93](https://github.com/PrestaShop/welcome/pull/93): Do not override the link smarty variable, by [@atomiix](https://github.com/atomiix)
* [#92](https://github.com/PrestaShop/welcome/pull/92): Bump expose-loader from 0.7.5 to 1.0.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#72](https://github.com/PrestaShop/welcome/pull/72): Bump file-loader from 0.8.5 to 0.11.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Quality Assurance module
* [#10](https://github.com/PrestaShop/ps_qualityassurance/pull/10): Run Travis on node 12, by [@matks](https://github.com/matks)
* [#9](https://github.com/PrestaShop/ps_qualityassurance/pull/9): Fix mispelled toggle, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#372](https://github.com/PrestaShop/autoupgrade/pull/372): Improve README, by [@matks](https://github.com/matks)
* [#371](https://github.com/PrestaShop/autoupgrade/pull/371): Add LICENSE file, by [@matks](https://github.com/matks)
* [#370](https://github.com/PrestaShop/autoupgrade/pull/370): Add some badges in README, by [@matks](https://github.com/matks)
* [#368](https://github.com/PrestaShop/autoupgrade/pull/368): Fix license headers, by [@matks](https://github.com/matks)
* [#367](https://github.com/PrestaShop/autoupgrade/pull/367): Removed config_fr.xml & Fixed licenses, by [@Progi1984](https://github.com/Progi1984)
* [#366](https://github.com/PrestaShop/autoupgrade/pull/366): Release 4.11.0, by [@Progi1984](https://github.com/Progi1984)
* [#365](https://github.com/PrestaShop/autoupgrade/pull/365): Bump version to 4.11.0, by [@Progi1984](https://github.com/Progi1984)
* [#364](https://github.com/PrestaShop/autoupgrade/pull/364): Check for version instead of if file exists, by [@atomiix](https://github.com/atomiix)
* [#363](https://github.com/PrestaShop/autoupgrade/pull/363): Revert "Test upgrades for PS1.7 with php7.1", by [@matks](https://github.com/matks)


### Product Comments module
* [#86](https://github.com/PrestaShop/productcomments/pull/86): Release 4.2.1, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#85](https://github.com/PrestaShop/productcomments/pull/85): Fix phpstan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#84](https://github.com/PrestaShop/productcomments/pull/84): Bump symfony/css-selector from 3.4.46 to 3.4.47. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#83](https://github.com/PrestaShop/productcomments/pull/83): Bump version to 4.2.1, by [@Progi1984](https://github.com/Progi1984)
* [#78](https://github.com/PrestaShop/productcomments/pull/78): Redirect after noabuseComment submit to prevent resubmit on page reload. Thank you [@Oksydan](https://github.com/Oksydan)
* [#77](https://github.com/PrestaShop/productcomments/pull/77): Fix: Product grade update after product page being updated. Thank you [@Oksydan](https://github.com/Oksydan)


### Theme customization module
* [#38](https://github.com/PrestaShop/ps_themecusto/pull/38): Fix phpstan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#35](https://github.com/PrestaShop/ps_themecusto/pull/35): Bump version to 1.2.1, by [@Progi1984](https://github.com/Progi1984)


### Customer account links module
* [#33](https://github.com/PrestaShop/ps_customeraccountlinks/pull/33): Fix phpstan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)


### Cross-selling module
* [#20](https://github.com/PrestaShop/ps_crossselling/pull/20): Fix phpstan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)


### Shopping cart module
* [#72](https://github.com/PrestaShop/ps_shoppingcart/pull/72): Fix phpstan configuration, by [@PierreRambaud](https://github.com/PierreRambaud)


### Docker images
* [#250](https://github.com/PrestaShop/docker/pull/250): Add finale release for 1.7.7.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### Customer reassurance block module
* [#85](https://github.com/PrestaShop/blockreassurance/pull/85): Bump symfony/css-selector from 3.4.37 to 3.4.47. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer data privacy block module
* [#24](https://github.com/PrestaShop/ps_dataprivacy/pull/24): Bump version to 2.0.1, by [@Progi1984](https://github.com/Progi1984)


### Catalog statistics module
* [#16](https://github.com/PrestaShop/statscatalog/pull/16): Bump version to 2.0.2, by [@Progi1984](https://github.com/Progi1984)


### Links list module
* [#104](https://github.com/PrestaShop/ps_linklist/pull/104): Add another template for displayLeft/Right column hook, by [@NeOMakinG](https://github.com/NeOMakinG)


### Google Analytics module
* [#66](https://github.com/PrestaShop/ps_googleanalytics/pull/66): Add tracking of cancelled orders. Thank you [@Hlavtox](https://github.com/Hlavtox)


### Performance project
* [#2](https://github.com/PrestaShop/performance-project/pull/2): Reworks. Thank you [@djodjo3](https://github.com/djodjo3)


## Where to start contributing?

What about adding [tracking number informations on Order Page](https://github.com/PrestaShop/PrestaShop/issues/19200)? This is an idea suggested in May, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@atomiix](https://github.com/atomiix), [@Progi1984](https://github.com/Progi1984), [@okom3pom](https://github.com/okom3pom), [@NeOMakinG](https://github.com/NeOMakinG), [@boubkerbribri](https://github.com/boubkerbribri), [@PierreRambaud](https://github.com/PierreRambaud), [@eternoendless](https://github.com/eternoendless), [@matthieu-rolland](https://github.com/matthieu-rolland), [@jolelievre](https://github.com/jolelievre), [@ksaandev](https://github.com/ksaandev), [@zuk3975](https://github.com/zuk3975), [@dependabot[bot]](https://github.com/apps/dependabot), [@yannicka](https://github.com/yannicka), [@sowbiba](https://github.com/sowbiba), [@jeckyl](https://github.com/jeckyl), [@Oksydan](https://github.com/Oksydan), [@kpodemski](https://github.com/kpodemski), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@PululuK](https://github.com/PululuK), [@Hlavtox](https://github.com/Hlavtox), [@djodjo3](https://github.com/djodjo3)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
