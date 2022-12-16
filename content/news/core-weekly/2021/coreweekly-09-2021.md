---
layout: post
aliases: ["/news/coreweekly-09-2021"]
title:  "PrestaShop Core Weekly - Week 9 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-03-08
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 1st to Sunday 7th of March 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

We enter the month of March, and this is the last month before April when we expect the feature freeze to happen!

Multiple projects for 1.7.8 have delivered major milestones last week:

[Virtual product files](https://github.com/PrestaShop/PrestaShop/pull/23386) are now managed in the new Product Page being built, as well as improvements for handling [suppliers for product with combinations](https://github.com/PrestaShop/PrestaShop/pull/23284).

The Back Office maintenance page is now [the first Symfony Back Office page using the new Multistore checkboxes interface](https://github.com/PrestaShop/PrestaShop/pull/22379) to manage multistore settings.

We also would like to applause the merge of PR [#20288](https://github.com/PrestaShop/PrestaShop/pull/20288) which is the Back Office page "Customers > Outstanding" migrated to Symfony by contributor [@ks129](https://github.com/ks129)!

## Releases

* [phpstan-prestashop](https://github.com/PrestaShop/phpstan-prestashop): [1.1.0](https://github.com/PrestaShop/phpstan-prestashop/releases/tag/1.1.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [68 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-03-01..2021-03-07) have been created in the project repositories;
- [71 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-03-01..2021-03-07), including [8 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-03-01..2021-03-07) on the core;
- [80 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-03-01..2021-03-07) in the project repositories;
- [114 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-03-01..2021-03-07), including [69 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-03-01..2021-03-07).


## Code changes in the 'develop' branch


### Core
* [#23451](https://github.com/PrestaShop/PrestaShop/pull/23451): Update phpstan to 0.12.80, by [@matks](https://github.com/matks)
* [#23443](https://github.com/PrestaShop/PrestaShop/pull/23443): Fixed save of translation message. Thank you [@agostinofiscale](https://github.com/agostinofiscale)
* [#23407](https://github.com/PrestaShop/PrestaShop/pull/23407): Helperlist optimization, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#21125](https://github.com/PrestaShop/PrestaShop/pull/21125): Introduce ContextLoadHelper to load legacy context in Commands, by [@matks](https://github.com/matks)


### Back office
* [#23510](https://github.com/PrestaShop/PrestaShop/pull/23510): Fix visibility of const OutstandingGridDefinitionFactory::GRID_ID, by [@matks](https://github.com/matks)
* [#23507](https://github.com/PrestaShop/PrestaShop/pull/23507): Fix search icon height, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23425](https://github.com/PrestaShop/PrestaShop/pull/23425): Additional checks for var existence in Admin Features controller. Thank you [@kpodemski](https://github.com/kpodemski)
* [#23409](https://github.com/PrestaShop/PrestaShop/pull/23409): Allow module exception to be displayed to make debugging easier, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#23405](https://github.com/PrestaShop/PrestaShop/pull/23405): Make sure array are correctly filled in Customer class, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23386](https://github.com/PrestaShop/PrestaShop/pull/23386): Introduce UpdateVirtualProductFileCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23284](https://github.com/PrestaShop/PrestaShop/pull/23284): Implement SetCombinationSuppliers & RemoveAllCombinationSuppliers commands. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23234](https://github.com/PrestaShop/PrestaShop/pull/23234): Translations - ThemeExporter : Use array of directories when getting catalog, by [@sowbiba](https://github.com/sowbiba)
* [#23146](https://github.com/PrestaShop/PrestaShop/pull/23146): Adjust default BO theme styles to new-theme styles, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23020](https://github.com/PrestaShop/PrestaShop/pull/23020): Add consistency to page blocks in the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22379](https://github.com/PrestaShop/PrestaShop/pull/22379): Multistore checkboxes on maintenance configuration pages, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#21243](https://github.com/PrestaShop/PrestaShop/pull/21243): Simplified the Administration form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#20288](https://github.com/PrestaShop/PrestaShop/pull/20288): Migrate "Customers > Outstanding". Thank you [@ks129](https://github.com/ks129)


### Front office
* [#23473](https://github.com/PrestaShop/PrestaShop/pull/23473): Make sure key exists before using it, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23406](https://github.com/PrestaShop/PrestaShop/pull/23406): Check if id_country exists before using the result of the array, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests
* [#23539](https://github.com/PrestaShop/PrestaShop/pull/23539): Disable temporarily phpstan extension, by [@matks](https://github.com/matks)
* [#23522](https://github.com/PrestaShop/PrestaShop/pull/23522): Introduce phpstan for prestashop v1.1 with 3 new Rules: ClassConstantsMustHaveVisibilityRule, UseTypeHintForNewMethodsRule, UseTypedReturnForNewMethodsRule, by [@matks](https://github.com/matks)
* [#23494](https://github.com/PrestaShop/PrestaShop/pull/23494): Fix click on toggles on nightly develop, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23490](https://github.com/PrestaShop/PrestaShop/pull/23490): Use GA ubuntu 18.04 for sanity and integration tests, by [@matks](https://github.com/matks)
* [#23489](https://github.com/PrestaShop/PrestaShop/pull/23489): Improve integration.yml GA file name, by [@matks](https://github.com/matks)
* [#23463](https://github.com/PrestaShop/PrestaShop/pull/23463): Rename PHPStan exclude class list, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch


### Front office
* [#23388](https://github.com/PrestaShop/PrestaShop/pull/23388): Fix product list width on home and search page, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23519](https://github.com/PrestaShop/PrestaShop/pull/23519): Fix local sort for shop url on multistore, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23503](https://github.com/PrestaShop/PrestaShop/pull/23503): Add test 'Check links in header page FO'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23471](https://github.com/PrestaShop/PrestaShop/pull/23471): Backport test 'Check footer links'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23464](https://github.com/PrestaShop/PrestaShop/pull/23464): Add test  'Filter, sort and pagination shop urls'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23452](https://github.com/PrestaShop/PrestaShop/pull/23452): Add test - Check product block in order page BO. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Circuit breaker
* [#39](https://github.com/PrestaShop/circuit-breaker/pull/39): Migrated from Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Wishlist block module
* [#103](https://github.com/PrestaShop/blockwishlist/pull/103): Fixed call to vendor/autoload.php, by [@Progi1984](https://github.com/Progi1984)
* [#102](https://github.com/PrestaShop/blockwishlist/pull/102): Add assets, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#100](https://github.com/PrestaShop/blockwishlist/pull/100): Fix getting cover. Thank you [@kpodemski](https://github.com/kpodemski)


### PrestaShop on Docker
* [#19](https://github.com/PrestaShop/docker-ci/pull/19): Improve readme file and remove PHP7.0 , by [@PierreRambaud](https://github.com/PierreRambaud)
* [#18](https://github.com/PrestaShop/docker-ci/pull/18): Add image for PHP 7.4, by [@PierreRambaud](https://github.com/PierreRambaud)


### PrestonBot
* [#115](https://github.com/PrestaShop/prestonbot/pull/115): Migrated from TravisCI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Changes in developer documentation
* [#877](https://github.com/PrestaShop/docs/pull/877): Fix module send example directory. Thank you [@nenes25](https://github.com/nenes25)
* [#876](https://github.com/PrestaShop/docs/pull/876): Fix typo in contribution guidelines, by [@matks](https://github.com/matks)


### Customer reassurance block module
* [#142](https://github.com/PrestaShop/blockreassurance/pull/142): Bump webpack from 5.24.2 to 5.24.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#141](https://github.com/PrestaShop/blockreassurance/pull/141): Bump css-loader from 5.1.0 to 5.1.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#140](https://github.com/PrestaShop/blockreassurance/pull/140): Bump @babel/core from 7.13.1 to 7.13.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#360](https://github.com/PrestaShop/ps_facetedsearch/pull/360): Bump chai from 4.3.1 to 4.3.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#359](https://github.com/PrestaShop/ps_facetedsearch/pull/359): Bump webpack from 5.24.2 to 5.24.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#358](https://github.com/PrestaShop/ps_facetedsearch/pull/358): Bump chai from 4.3.0 to 4.3.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#357](https://github.com/PrestaShop/ps_facetedsearch/pull/357): Bump @babel/preset-env from 7.13.8 to 7.13.9. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#356](https://github.com/PrestaShop/ps_facetedsearch/pull/356): Bump css-loader from 5.1.0 to 5.1.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#355](https://github.com/PrestaShop/ps_facetedsearch/pull/355): Bump @babel/preset-env from 7.13.5 to 7.13.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#354](https://github.com/PrestaShop/ps_facetedsearch/pull/354): Bump @babel/register from 7.13.0 to 7.13.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#353](https://github.com/PrestaShop/ps_facetedsearch/pull/353): Bump @babel/core from 7.13.1 to 7.13.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop PHPStan extension
* [#14](https://github.com/PrestaShop/phpstan-prestashop/pull/14): Handle multiple loads of same file through PHPConfigurationFileLoader, by [@matks](https://github.com/matks)
* [#13](https://github.com/PrestaShop/phpstan-prestashop/pull/13): Fix extension.neon indentation, by [@matks](https://github.com/matks)
* [#12](https://github.com/PrestaShop/phpstan-prestashop/pull/12): Improve documentation for UseTypedReturnForNewMethodsRule, by [@matks](https://github.com/matks)
* [#11](https://github.com/PrestaShop/phpstan-prestashop/pull/11): Introduce UseTypeHintForNewMethodsRule, by [@matks](https://github.com/matks)
* [#9](https://github.com/PrestaShop/phpstan-prestashop/pull/9): Introduce UseTypedReturnForNewMethodsRule, by [@matks](https://github.com/matks)


### User documentation landing page
* [#36](https://github.com/PrestaShop/user-documentation-landing/pull/36): chore(deps-dev): bump eslint from 7.20.0 to 7.21.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#35](https://github.com/PrestaShop/user-documentation-landing/pull/35): fix(deps): bump core-js from 3.9.0 to 3.9.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### GDPR module
* [#138](https://github.com/PrestaShop/psgdpr/pull/138): Modify GitHub Action PHP CS Fixer to not depend on prestashopcorp, by [@matks](https://github.com/matks)
* [#137](https://github.com/PrestaShop/psgdpr/pull/137): Apply license headers from native modules, by [@matks](https://github.com/matks)
* [#134](https://github.com/PrestaShop/psgdpr/pull/134): Bump prestashop/php-dev-tools from 3.4 to 3.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop Specifications
* [#208](https://github.com/PrestaShop/prestashop-specs/pull/208): Move wishlist specs into the modules repo, by [@marionf](https://github.com/marionf)
* [#188](https://github.com/PrestaShop/prestashop-specs/pull/188): Create specs for ecotax, by [@marionf](https://github.com/marionf)


### Prestashop UI Kit
* [#138](https://github.com/PrestaShop/prestashop-ui-kit/pull/138): Fix select2 initialization on storybook, by [@NeOMakinG](https://github.com/NeOMakinG)


### Decimal
* [#15](https://github.com/PrestaShop/decimal/pull/15): Migrate to Coveralls & Added support versions, by [@Progi1984](https://github.com/Progi1984)


### PrestaShop English User Documentation
* [#2](https://github.com/PrestaShop/user-documentation-en/pull/2): Delete duplicate content to clean user-documentation-en repository . Thank you [@Julievrz](https://github.com/Julievrz)


### Prestashop Shop Creator tool
* [#5](https://github.com/PrestaShop/prestashop-shop-creator/pull/5): Add composer 2 compatibility and use new faker lib. Thank you [@davidglezz](https://github.com/davidglezz)


## Where to start contributing?

What about fixing [a label incorrectly displayed](https://github.com/PrestaShop/PrestaShop/issues/23216) in the Back Office Create an order page ? This is a bug report submitted last month, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@NeOMakinG](https://github.com/NeOMakinG), [@matks](https://github.com/matks), [@PierreRambaud](https://github.com/PierreRambaud), [@nenes25](https://github.com/nenes25), [@boubkerbribri](https://github.com/boubkerbribri), [@dependabot[bot]](https://github.com/apps/dependabot), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@kpodemski](https://github.com/kpodemski), [@agostinofiscale](https://github.com/agostinofiscale), [@marionf](https://github.com/marionf), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@Julievrz](https://github.com/Julievrz), [@zuk3975](https://github.com/zuk3975), [@sowbiba](https://github.com/sowbiba), [@davidglezz](https://github.com/davidglezz), [@matthieu-rolland](https://github.com/matthieu-rolland), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@ks129](https://github.com/ks129)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
