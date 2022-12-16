---
layout: post
aliases: ["/news/coreweekly-week-32-2018"]
slug: "coreweekly-week-32-2018"
title:  "PrestaShop Core Weekly - Week 32 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-08-16 15:40:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 6th to Sunday 12th of August 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Hello dear PrestaShop enthusiasts!

In the middle of August a lot of people are off for Summer holidays, doing something else than coding: it means less code reviews and less pull requests. However if you look carefully, you will see that the current work is now focused on 1.7.5. Some good news: the Google Sitemap module is coming back!.


## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#9244](https://github.com/PrestaShop/PrestaShop/pull/9244): Fixed Apache Optimization. Thank you [@Pedrock](https://github.com/Pedrock)
* [#9404](https://github.com/PrestaShop/PrestaShop/pull/9404): Add gsitemap, by [@eternoendless](https://github.com/eternoendless)
* [#9424](https://github.com/PrestaShop/PrestaShop/pull/9424): Issues templates, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back Office

* [#8690](https://github.com/PrestaShop/PrestaShop/pull/8690): Improved performance of Product List page, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9397](https://github.com/PrestaShop/PrestaShop/pull/9397): Update style of forms on new pages, by [@eternoendless](https://github.com/eternoendless)
* [#9399](https://github.com/PrestaShop/PrestaShop/pull/9399): Fix ajax in 500 in product page, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9410](https://github.com/PrestaShop/PrestaShop/pull/9410): Improve grid search and reset buttons. Thank you [@sarjon](https://github.com/sarjon)


### Front Office

* [#9417](https://github.com/PrestaShop/PrestaShop/pull/9417): FO: override CustomerAddressForm->submit method more easily. Thank you [@azisyus](https://github.com/azisyus)
* [#9429](https://github.com/PrestaShop/PrestaShop/pull/9429): Add formatted field file_size_formatted in attachments, by [@jolelievre](https://github.com/jolelievre)


### Tests

* [#9412](https://github.com/PrestaShop/PrestaShop/pull/9412): Avoid composer authentication issues, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Install

* [#9409](https://github.com/PrestaShop/PrestaShop/pull/9409): Symfony requirements file now compatible with PHP 7.2, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9411](https://github.com/PrestaShop/PrestaShop/pull/9411): Indian Localization improved . Thank you [@adhavalboy](https://github.com/adhavalboy)
* [#9425](https://github.com/PrestaShop/PrestaShop/pull/9425): Fix step name retrieved in the installer, by [@rGaillard](https://github.com/rGaillard)


## Code changes in modules, themes & tools

### Faceted navigation block

* [#36](https://github.com/PrestaShop/ps_facetedsearch/pull/36): Fixed order in implode. Thank you [@sadlyblue](https://github.com/sadlyblue)


### Amazon Payments

* [#79](https://github.com/PrestaShop/amzpayments/pull/79): v2.2.5. Thank you [@paeddl](https://github.com/paeddl)
* [#80](https://github.com/PrestaShop/amzpayments/pull/80): v3.2.5. Thank you [@paeddl](https://github.com/paeddl)


### PrestaShop on Docker

* [#133](https://github.com/PrestaShop/docker/pull/133): Add PrestaShop 1.7.4.2, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### PrestaShop Cleaner

* [#24](https://github.com/PrestaShop/pscleaner/pull/24): Truncate the attribute table also. Thank you [@sadlyblue](https://github.com/sadlyblue)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @adhavalboy, @azisyus, @paeddl, @Pedrock, @sarjon, @sadlyblue!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
