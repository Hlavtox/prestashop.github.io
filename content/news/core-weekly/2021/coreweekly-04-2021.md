---
layout: post
aliases: ["/news/coreweekly-04-2021"]
title:  "PrestaShop Core Weekly - Week 4 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-02-01
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 25th to Sunday 31th of January 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [Eslint-config](https://github.com/PrestaShop/eslint-config): [v0.1.0](https://github.com/PrestaShop/eslint-config/releases/tag/0.1.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [69 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-01-25..2021-01-31) have been created in the project repositories;
- [68 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-01-25..2021-01-31), including [25 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-01-25..2021-01-31) on the core;
- [62 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-01-25..2021-01-31) in the project repositories;
- [110 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-01-25..2021-01-31), including [68 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-01-25..2021-01-31).



## Code changes in the 'develop' branch


### Core
* [#22975](https://github.com/PrestaShop/PrestaShop/pull/22975): Add breakline rule of ESLint, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22966](https://github.com/PrestaShop/PrestaShop/pull/22966): Faster checkout - depth of 0 means unlimited. Thank you [@mvorisek](https://github.com/mvorisek)
* [#22746](https://github.com/PrestaShop/PrestaShop/pull/22746): PHP sessions are not correctly configured, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#23030](https://github.com/PrestaShop/PrestaShop/pull/23030): Fix duplicate id on floating button, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23003](https://github.com/PrestaShop/PrestaShop/pull/23003): Update Symfony debug toolbar link to developer documentation, by [@matks](https://github.com/matks)
* [#22996](https://github.com/PrestaShop/PrestaShop/pull/22996): Align labels to right and space on red star, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22988](https://github.com/PrestaShop/PrestaShop/pull/22988): Hide shop name on mobile, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22986](https://github.com/PrestaShop/PrestaShop/pull/22986): Integrate product quantities form and related command. Thank you [@zuk3975](https://github.com/zuk3975)
* [#22984](https://github.com/PrestaShop/PrestaShop/pull/22984): Remove header button on mobile and push these into new floating btn, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22955](https://github.com/PrestaShop/PrestaShop/pull/22955): Fix product image form display in mobile view. Thank you [@itsvahid](https://github.com/itsvahid)
* [#22921](https://github.com/PrestaShop/PrestaShop/pull/22921): Product page SEO tab, by [@jolelievre](https://github.com/jolelievre)
* [#22888](https://github.com/PrestaShop/PrestaShop/pull/22888): Change create order buttons position and wording, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22772](https://github.com/PrestaShop/PrestaShop/pull/22772): Swap default theme sass files to scss, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22662](https://github.com/PrestaShop/PrestaShop/pull/22662): Fix buttons height on mobile on order view page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21878](https://github.com/PrestaShop/PrestaShop/pull/21878): Simplified add language form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Front office
* [#23006](https://github.com/PrestaShop/PrestaShop/pull/23006): Fix product search by ISBN. Thank you [@Seb33300](https://github.com/Seb33300)
* [#22945](https://github.com/PrestaShop/PrestaShop/pull/22945): Fix product list hover and overflow on catalog mode, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22813](https://github.com/PrestaShop/PrestaShop/pull/22813): Remove box-shadows from classic theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22417](https://github.com/PrestaShop/PrestaShop/pull/22417): Add breadcrumb rich data on the frontpage. Thank you [@tswfi](https://github.com/tswfi)


### Tests
* [#23049](https://github.com/PrestaShop/PrestaShop/pull/23049): Fix nightly 29/01/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23037](https://github.com/PrestaShop/PrestaShop/pull/23037): Fix nightly 28/01/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22967](https://github.com/PrestaShop/PrestaShop/pull/22967): Delete parameters.yml.travis. Thank you [@mvorisek](https://github.com/mvorisek)


## Code changes in the '1.7.7.x' branch


### Core
* [#22768](https://github.com/PrestaShop/PrestaShop/pull/22768): Exclude gifts from getOrderTotal when selected ONLY_PRODUCTS, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#22997](https://github.com/PrestaShop/PrestaShop/pull/22997): Fix compare function of dashboard's calendar, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22947](https://github.com/PrestaShop/PrestaShop/pull/22947): Fix Shopping Cart page in BO throwing an exception, by [@atomiix](https://github.com/atomiix)


### Front office
* [#23024](https://github.com/PrestaShop/PrestaShop/pull/23024): Fixed BreadcrumbList Rich Result on FrontOffice, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#22985](https://github.com/PrestaShop/PrestaShop/pull/22985): Add test 'Set required fields for address page'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22954](https://github.com/PrestaShop/PrestaShop/pull/22954): Add test 'Sort shop groups'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22953](https://github.com/PrestaShop/PrestaShop/pull/22953): Add test 'Filter, sort and paginaion shops'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22925](https://github.com/PrestaShop/PrestaShop/pull/22925): Add test 'Add and delete shop URL'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Customer reassurance block module
* [#116](https://github.com/PrestaShop/blockreassurance/pull/116): Bump mini-css-extract-plugin from 1.3.4 to 1.3.5. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#115](https://github.com/PrestaShop/blockreassurance/pull/115): Bump webpack from 5.17.0 to 5.18.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#114](https://github.com/PrestaShop/blockreassurance/pull/114): Bump friendsofphp/php-cs-fixer from 2.18.1 to 2.18.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#113](https://github.com/PrestaShop/blockreassurance/pull/113): Bump webpack from 5.16.0 to 5.17.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#852](https://github.com/PrestaShop/docs/pull/852): Some typos. Thank you [@kpodemski](https://github.com/kpodemski)
* [#851](https://github.com/PrestaShop/docs/pull/851): Improvements in Installation -> Configuration. Thank you [@kpodemski](https://github.com/kpodemski)
* [#850](https://github.com/PrestaShop/docs/pull/850): Add warning on registerJavascript / registerStylesheet about potential collisions, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#849](https://github.com/PrestaShop/docs/pull/849): Add open source project FAQ, by [@eternoendless](https://github.com/eternoendless)


### Prestashop UI Kit
* [#134](https://github.com/PrestaShop/prestashop-ui-kit/pull/134): Fix behavior of switch button if yes is checked and switch disabled, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#131](https://github.com/PrestaShop/prestashop-ui-kit/pull/131): Fix focus and active on select2 group, by [@NeOMakinG](https://github.com/NeOMakinG)


### Translation Files repository
* [#18](https://github.com/PrestaShop/TranslationFiles/pull/18): Add Esperanto language. Thank you [@Julievrz](https://github.com/Julievrz)


### Faceted search module
* [#313](https://github.com/PrestaShop/ps_facetedsearch/pull/313): Bump webpack from 5.17.0 to 5.18.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#310](https://github.com/PrestaShop/ps_facetedsearch/pull/310): Bump webpack from 5.16.0 to 5.17.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#21](https://github.com/PrestaShop/user-documentation-landing/pull/21): chore(deps-dev): bump eslint-config-prestashop from 0.0.2 to 0.1.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#20](https://github.com/PrestaShop/user-documentation-landing/pull/20): chore(deps-dev): bump @nuxtjs/pwa from 3.3.4 to 3.3.5. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop-modules
* [#442](https://github.com/PrestaShop/PrestaShop-modules/pull/442): Remove archived modules, by [@PierreRambaud](https://github.com/PierreRambaud)


### Eslint configuration
* [#4](https://github.com/PrestaShop/eslint-config/pull/4): Bump to 0.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#3](https://github.com/PrestaShop/eslint-config/pull/3): Add auto breakline rules, by [@NeOMakinG](https://github.com/NeOMakinG)


### Core Weekly Generator tool
* [#72](https://github.com/PrestaShop/core-weekly-generator/pull/72): Add phpstan extension to coreteam.py listing, by [@matks](https://github.com/matks)


### Featured products module
* [#35](https://github.com/PrestaShop/ps_featuredproducts/pull/35): Not used "id_carrier" parameter. Thank you [@moncef-essid](https://github.com/moncef-essid)


### PrestaShop Specifications
* [#202](https://github.com/PrestaShop/prestashop-specs/pull/202): Update the specs for empty search results. Thank you [@Julievrz](https://github.com/Julievrz)
* [#197](https://github.com/PrestaShop/prestashop-specs/pull/197): Add #9561 warning notification, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#196](https://github.com/PrestaShop/prestashop-specs/pull/196): Add #19200 improvement to the Order page specifications, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#195](https://github.com/PrestaShop/prestashop-specs/pull/195): Update theme & logo specs, by [@marionf](https://github.com/marionf)
* [#190](https://github.com/PrestaShop/prestashop-specs/pull/190): Add information to the Webservice specifications, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#187](https://github.com/PrestaShop/prestashop-specs/pull/187): Create specs for customer service dashboard, by [@marionf](https://github.com/marionf)
* [#186](https://github.com/PrestaShop/prestashop-specs/pull/186): Specify the Customer Settings pages, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### PHP Developer Tools
* [#47](https://github.com/PrestaShop/php-dev-tools/pull/47): Remove PrettyCI configuration file and references, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#377](https://github.com/PrestaShop/autoupgrade/pull/377): Add more upgrade tests and switch to Github actions, by [@atomiix](https://github.com/atomiix)


### Wishlist block module
* [#96](https://github.com/PrestaShop/blockwishlist/pull/96): Remove cover query for ps1770. Thank you [@pablopolyte](https://github.com/pablopolyte)


### Links list module
* [#108](https://github.com/PrestaShop/ps_linklist/pull/108): Prepare data for required fields. Thank you [@kpodemski](https://github.com/kpodemski)


### Product details statistics module
* [#20](https://github.com/PrestaShop/statsproduct/pull/20): Use the good column for the stats. Thank you [@okom3pom](https://github.com/okom3pom)


### Email subscription module
* [#74](https://github.com/PrestaShop/ps_emailsubscription/pull/74): Cleaned in module code. Thank you [@moncef-essid](https://github.com/moncef-essid)


### Banner module
* [#12](https://github.com/PrestaShop/ps_banner/pull/12): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Customer "Sign in" link module
* [#15](https://github.com/PrestaShop/ps_customersignin/pull/15): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Search Bar module
* [#10](https://github.com/PrestaShop/ps_searchbar/pull/10): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@dependabot[bot]](https://github.com/apps/dependabot), [@jolelievre](https://github.com/jolelievre), [@NeOMakinG](https://github.com/NeOMakinG), [@kpodemski](https://github.com/kpodemski), [@Progi1984](https://github.com/Progi1984), [@Julievrz](https://github.com/Julievrz), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@Seb33300](https://github.com/Seb33300), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@PierreRambaud](https://github.com/PierreRambaud), [@zuk3975](https://github.com/zuk3975), [@mvorisek](https://github.com/mvorisek), [@moncef-essid](https://github.com/moncef-essid), [@itsvahid](https://github.com/itsvahid), [@atomiix](https://github.com/atomiix), [@pablopolyte](https://github.com/pablopolyte), [@LouiseBonnard](https://github.com/LouiseBonnard), [@okom3pom](https://github.com/okom3pom), [@marionf](https://github.com/marionf), [@tswfi](https://github.com/tswfi), [@JevgenijVisockij](https://github.com/JevgenijVisockij)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
