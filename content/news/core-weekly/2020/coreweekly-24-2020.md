---
layout: post
aliases: ["/news/coreweekly-24-2020"]
title:  "PrestaShop Core Weekly - Week 24 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-06-18
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 8th to Sunday 14th of June 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [95 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-06-08..2020-06-14) have been created in the project repositories;
- [82 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-06-08..2020-06-14), including [30 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-06-08..2020-06-14) on the core;
- [124 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-06-08..2020-06-14) in the project repositories;
- [162 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-06-08..2020-06-14), including [146 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-06-08..2020-06-14).
        


## Code changes in the 'develop' branch


### Core
* [#19260](https://github.com/PrestaShop/PrestaShop/pull/19260): Fix order payment duplication depending on order state configuration. Thank you [@erouvier29](https://github.com/erouvier29)
* [#18883](https://github.com/PrestaShop/PrestaShop/pull/18883): Fix BO - New currency page . Thank you [@PululuK](https://github.com/PululuK)
* [#18116](https://github.com/PrestaShop/PrestaShop/pull/18116): Avoid crash because of image timeout, by [@matks](https://github.com/matks)


### Back office
* [#19655](https://github.com/PrestaShop/PrestaShop/pull/19655): Use setFieldsToUpdate() in UpdateProductBasicInformationHandler. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19648](https://github.com/PrestaShop/PrestaShop/pull/19648): Number extractor service. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19580](https://github.com/PrestaShop/PrestaShop/pull/19580): Remove pagination on Modules to update List, by [@Progi1984](https://github.com/Progi1984)
* [#19525](https://github.com/PrestaShop/PrestaShop/pull/19525): Fixed used route for checking notifications in BO, by [@Progi1984](https://github.com/Progi1984)
* [#19510](https://github.com/PrestaShop/PrestaShop/pull/19510): Fix Missing required fields in import . Thank you [@PululuK](https://github.com/PululuK)
* [#19453](https://github.com/PrestaShop/PrestaShop/pull/19453): Help on textarea (twig) show 2 times. Thank you [@clotaire202](https://github.com/clotaire202)
* [#19289](https://github.com/PrestaShop/PrestaShop/pull/19289): [BO] Fixed Email subject translation. Thank you [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul)
* [#19286](https://github.com/PrestaShop/PrestaShop/pull/19286):  [BO] Backup Controller : Improvements. Thank you [@PululuK](https://github.com/PululuK)
* [#19102](https://github.com/PrestaShop/PrestaShop/pull/19102): Fixed error when no Memcached servers are available., by [@Progi1984](https://github.com/Progi1984)
* [#18954](https://github.com/PrestaShop/PrestaShop/pull/18954): Wrong value for tpl_vars['back']  in AdminController::renderForm. Thank you [@manudas](https://github.com/manudas)
* [#18937](https://github.com/PrestaShop/PrestaShop/pull/18937): Wrong redirection when using the quick search for a category (Second). Thank you [@PululuK](https://github.com/PululuK)
* [#18622](https://github.com/PrestaShop/PrestaShop/pull/18622): Remove call to profile.prestashop.com, by [@matks](https://github.com/matks)
* [#18510](https://github.com/PrestaShop/PrestaShop/pull/18510): Fix "The stock counter is not updated when actions on cart products are performed ". Thank you [@arouiadib](https://github.com/arouiadib)
* [#17819](https://github.com/PrestaShop/PrestaShop/pull/17819): Split configuration forms into single form management, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#17651](https://github.com/PrestaShop/PrestaShop/pull/17651): Update tinymce from 4.0.16 to 4.9.8, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#16876](https://github.com/PrestaShop/PrestaShop/pull/16876): Support ip subnet in maintenance mode. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Front office
* [#19538](https://github.com/PrestaShop/PrestaShop/pull/19538): Add displayNewsletterRegistration hook in classic. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#19534](https://github.com/PrestaShop/PrestaShop/pull/19534): Front side validation problem on the number of characters in a password. Thank you [@florian-202](https://github.com/florian-202)
* [#18904](https://github.com/PrestaShop/PrestaShop/pull/18904): FO: show browser-native error messages during payment selection step in checkout. Thank you [@patrickmyh](https://github.com/patrickmyh)
* [#17322](https://github.com/PrestaShop/PrestaShop/pull/17322): Don't log bots anymore. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#17123](https://github.com/PrestaShop/PrestaShop/pull/17123): Fix default country and country detection. Thank you [@mvorisek](https://github.com/mvorisek)


### Installer
* [#19213](https://github.com/PrestaShop/PrestaShop/pull/19213): Prefix parameter in CLI is not interpreted if it's empty, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.7.x' branch


### Back office
* [#19597](https://github.com/PrestaShop/PrestaShop/pull/19597): Add order table empty state, by [@atomiix](https://github.com/atomiix)
* [#19582](https://github.com/PrestaShop/PrestaShop/pull/19582): Order products pagination, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#19725](https://github.com/PrestaShop/PrestaShop/pull/19725): Functional tests - Increase timeout after disabling a category, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#19653](https://github.com/PrestaShop/PrestaShop/pull/19653): Functional tests - Switch tests to playwright (instead of puppeteer), by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.6.x' branch


### Core
* [#19010](https://github.com/PrestaShop/PrestaShop/pull/19010): Added missing required_once for Datas class, by [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### Wire payment module
* [#52](https://github.com/PrestaShop/ps_wirepayment/pull/52): Validate composer.json, by [@Progi1984](https://github.com/Progi1984)
* [#51](https://github.com/PrestaShop/ps_wirepayment/pull/51): Bump version to 2.1.0 and Improve project, by [@Progi1984](https://github.com/Progi1984)
* [#50](https://github.com/PrestaShop/ps_wirepayment/pull/50): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Changes in developer documentation
* [#568](https://github.com/PrestaShop/docs/pull/568): Typos. Thank you [@awurth](https://github.com/awurth)
* [#567](https://github.com/PrestaShop/docs/pull/567): Use actionFrontControllerSetMedia if you want to add js and css, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#566](https://github.com/PrestaShop/docs/pull/566): Manufacturer - Wrong API call string. Thank you [@LorisB](https://github.com/LorisB)
* [#565](https://github.com/PrestaShop/docs/pull/565): Document smarty extensions, by [@eternoendless](https://github.com/eternoendless)
* [#564](https://github.com/PrestaShop/docs/pull/564): Update docs after playwright switch, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#563](https://github.com/PrestaShop/docs/pull/563): Update symfony service/controller declaration about Symfony DI. Thank you [@zalexki](https://github.com/zalexki)
* [#561](https://github.com/PrestaShop/docs/pull/561): Fix typo in project-modules.md. Thank you [@ksaandev](https://github.com/ksaandev)
* [#560](https://github.com/PrestaShop/docs/pull/560): Update value_objects.md. Thank you [@marcoguido](https://github.com/marcoguido)
* [#559](https://github.com/PrestaShop/docs/pull/559): List all available PrestaShop CLI commands, by [@Progi1984](https://github.com/Progi1984)
* [#556](https://github.com/PrestaShop/docs/pull/556): Add doc for Webservice language parameter, by [@jolelievre](https://github.com/jolelievre)
* [#550](https://github.com/PrestaShop/docs/pull/550): Add FAQ about overriding the product cover, by [@jolelievre](https://github.com/jolelievre)


### Email subscription module
* [#58](https://github.com/PrestaShop/ps_emailsubscription/pull/58): Bump version to 2.6.0 and Improve project, by [@Progi1984](https://github.com/Progi1984)
* [#49](https://github.com/PrestaShop/ps_emailsubscription/pull/49): Add an hook for newsletter registration/unregistration. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Order Notifications on the Favicon
* [#18](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/18): Release 2.1.0, by [@Matt75](https://github.com/Matt75)
* [#16](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/16): Update devtools, by [@Matt75](https://github.com/Matt75)
* [#15](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/15): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)
* [#13](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/13): Remove useless third party and clean module code, by [@Matt75](https://github.com/Matt75)


### PS Cleaner module
* [#50](https://github.com/PrestaShop/pscleaner/pull/50): Release 2.1.0, by [@Progi1984](https://github.com/Progi1984)
* [#49](https://github.com/PrestaShop/pscleaner/pull/49): Bump version to 2.1.0, by [@Progi1984](https://github.com/Progi1984)
* [#48](https://github.com/PrestaShop/pscleaner/pull/48): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)
* [#46](https://github.com/PrestaShop/pscleaner/pull/46): Project Improvements, by [@Progi1984](https://github.com/Progi1984)
* [#45](https://github.com/PrestaShop/pscleaner/pull/45): Fixed check of the status of checkboxes, by [@Progi1984](https://github.com/Progi1984)


### Live translation
* [#9](https://github.com/PrestaShop/ps_livetranslation/pull/9): Added the way to disable Crowdin Popup (BO/FO), by [@Progi1984](https://github.com/Progi1984)


### OnBoarding
* [#63](https://github.com/PrestaShop/welcome/pull/63): Remove vendor folder, by [@matks](https://github.com/matks)
* [#62](https://github.com/PrestaShop/welcome/pull/62): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Shop search
* [#8](https://github.com/PrestaShop/statssearch/pull/8): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#7](https://github.com/PrestaShop/statssearch/pull/7): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Sales and orders
* [#13](https://github.com/PrestaShop/statssales/pull/13): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#12](https://github.com/PrestaShop/statssales/pull/12): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Registrations statistics modules
* [#8](https://github.com/PrestaShop/statsregistrations/pull/8): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#7](https://github.com/PrestaShop/statsregistrations/pull/7): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Product details
* [#15](https://github.com/PrestaShop/statsproduct/pull/15): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#14](https://github.com/PrestaShop/statsproduct/pull/14): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Registered customer information
* [#9](https://github.com/PrestaShop/statspersonalinfos/pull/9): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#8](https://github.com/PrestaShop/statspersonalinfos/pull/8): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Visitors origin
* [#6](https://github.com/PrestaShop/statsorigin/pull/6): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/statsorigin/pull/5): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Newsletter
* [#7](https://github.com/PrestaShop/statsnewsletter/pull/7): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#6](https://github.com/PrestaShop/statsnewsletter/pull/6): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Visitors online
* [#13](https://github.com/PrestaShop/statslive/pull/13): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#12](https://github.com/PrestaShop/statslive/pull/12): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Stats Dashboard
* [#15](https://github.com/PrestaShop/statsforecast/pull/15): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#14](https://github.com/PrestaShop/statsforecast/pull/14): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Browsers and operating systems
* [#10](https://github.com/PrestaShop/statsequipment/pull/10): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#9](https://github.com/PrestaShop/statsequipment/pull/9): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Carrier distribution
* [#6](https://github.com/PrestaShop/statscarrier/pull/6): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/statscarrier/pull/5): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best vouchers
* [#7](https://github.com/PrestaShop/statsbestvouchers/pull/7): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#6](https://github.com/PrestaShop/statsbestvouchers/pull/6): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best suppliers
* [#6](https://github.com/PrestaShop/statsbestsuppliers/pull/6): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/statsbestsuppliers/pull/5): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best manufacturers
* [#6](https://github.com/PrestaShop/statsbestmanufacturers/pull/6): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/statsbestmanufacturers/pull/5): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best customers
* [#12](https://github.com/PrestaShop/statsbestcustomers/pull/12): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#11](https://github.com/PrestaShop/statsbestcustomers/pull/11): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best categories
* [#7](https://github.com/PrestaShop/statsbestcategories/pull/7): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#6](https://github.com/PrestaShop/statsbestcategories/pull/6): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Search engine keywords
* [#11](https://github.com/PrestaShop/sekeywords/pull/11): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#10](https://github.com/PrestaShop/sekeywords/pull/10): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Social Follow module
* [#23](https://github.com/PrestaShop/ps_socialfollow/pull/23): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#22](https://github.com/PrestaShop/ps_socialfollow/pull/22): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Search Bar module
* [#19](https://github.com/PrestaShop/ps_searchbar/pull/19): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#18](https://github.com/PrestaShop/ps_searchbar/pull/18): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Main menu module
* [#33](https://github.com/PrestaShop/ps_mainmenu/pull/33): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#32](https://github.com/PrestaShop/ps_mainmenu/pull/32): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Language selector
* [#18](https://github.com/PrestaShop/ps_languageselector/pull/18): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#17](https://github.com/PrestaShop/ps_languageselector/pull/17): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Featured products
* [#26](https://github.com/PrestaShop/ps_featuredproducts/pull/26): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#25](https://github.com/PrestaShop/ps_featuredproducts/pull/25): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Customer data privacy block
* [#18](https://github.com/PrestaShop/ps_dataprivacy/pull/18): Fix outdated license headers, by [@matks](https://github.com/matks)


### Custom text
* [#40](https://github.com/PrestaShop/ps_customtext/pull/40): Fix outdated license headers, by [@matks](https://github.com/matks)


### Customer "Sign in" link
* [#20](https://github.com/PrestaShop/ps_customersignin/pull/20): Fix outdated license headers, by [@matks](https://github.com/matks)


### Customer account links
* [#25](https://github.com/PrestaShop/ps_customeraccountlinks/pull/25): Fix outdated license headers, by [@matks](https://github.com/matks)


### Cross-selling
* [#11](https://github.com/PrestaShop/ps_crossselling/pull/11): Fix outdated license headers, by [@matks](https://github.com/matks)


### Contact informations module
* [#34](https://github.com/PrestaShop/ps_contactinfo/pull/34): Fix outdated license headers, by [@matks](https://github.com/matks)


### Check payment
* [#32](https://github.com/PrestaShop/ps_checkpayment/pull/32): Fix outdated license headers, by [@matks](https://github.com/matks)


### Category tree links
* [#34](https://github.com/PrestaShop/ps_categorytree/pull/34): Fix outdated license headers, by [@matks](https://github.com/matks)


### Google Sitemap module
* [#137](https://github.com/PrestaShop/gsitemap/pull/137): Fix outdated license headers, by [@matks](https://github.com/matks)


### Simple HTML table display
* [#10](https://github.com/PrestaShop/gridhtml/pull/10): Fix outdated license headers, by [@matks](https://github.com/matks)


### NVD3 Charts
* [#10](https://github.com/PrestaShop/graphnvd3/pull/10): Fix outdated license headers, by [@matks](https://github.com/matks)


### Dashboard Trends
* [#28](https://github.com/PrestaShop/dashtrends/pull/28): Fix outdated license headers, by [@matks](https://github.com/matks)


### Core Weekly Generator tool
* [#38](https://github.com/PrestaShop/core-weekly-generator/pull/38): adding new component to the list, by [@ttoine](https://github.com/ttoine)
* [#37](https://github.com/PrestaShop/core-weekly-generator/pull/37): Bump websocket-extensions from 0.1.3 to 0.1.4. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop on Docker
* [#17](https://github.com/PrestaShop/docker-ci/pull/17): Update whole repo + add PHP 7.3, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Dashboard Goals
* [#20](https://github.com/PrestaShop/dashgoals/pull/20): Fix outdated license headers, by [@matks](https://github.com/matks)


### Dashboard Activity module
* [#20](https://github.com/PrestaShop/dashactivity/pull/20): Fix outdated license headers, by [@matks](https://github.com/matks)


### Contact Form
* [#43](https://github.com/PrestaShop/contactform/pull/43): Fix outdated license headers, by [@matks](https://github.com/matks)


### Catalog statistics
* [#11](https://github.com/PrestaShop/statscatalog/pull/11): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#10](https://github.com/PrestaShop/statscatalog/pull/10): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Catalog evaluation
* [#15](https://github.com/PrestaShop/statscheckup/pull/15): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#14](https://github.com/PrestaShop/statscheckup/pull/14): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Best-selling products
* [#6](https://github.com/PrestaShop/statsbestproducts/pull/6): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/statsbestproducts/pull/5): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Data mining for statistics
* [#12](https://github.com/PrestaShop/statsdata/pull/12): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#11](https://github.com/PrestaShop/statsdata/pull/11): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Available quantities
* [#12](https://github.com/PrestaShop/statsstock/pull/12): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#11](https://github.com/PrestaShop/statsstock/pull/11): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Visits and Visitors
* [#8](https://github.com/PrestaShop/statsvisits/pull/8): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#7](https://github.com/PrestaShop/statsvisits/pull/7): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### PrestaShop Specifications
* [#122](https://github.com/PrestaShop/prestashop-specs/pull/122): Update product images specs, by [@colinegin](https://github.com/colinegin)
* [#103](https://github.com/PrestaShop/prestashop-specs/pull/103): Create multistore general specs, by [@marionf](https://github.com/marionf)


### Link list
* [#92](https://github.com/PrestaShop/ps_linklist/pull/92): Update license headers, by [@Progi1984](https://github.com/Progi1984)
* [#90](https://github.com/PrestaShop/ps_linklist/pull/90): Bump version to 3.2.0 and Improve project, by [@Progi1984](https://github.com/Progi1984)
* [#89](https://github.com/PrestaShop/ps_linklist/pull/89): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Theme customization
* [#28](https://github.com/PrestaShop/ps_themecusto/pull/28): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Share Buttons module
* [#41](https://github.com/PrestaShop/ps_sharebuttons/pull/41): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Email Alerts module
* [#54](https://github.com/PrestaShop/ps_emailalerts/pull/54): Release 2.2.0, by [@Progi1984](https://github.com/Progi1984)


### Example modules
* [#20](https://github.com/PrestaShop/example-modules/pull/20): Demodoctrine module, by [@jolelievre](https://github.com/jolelievre)


### Prestashop UI Kit
* [#93](https://github.com/PrestaShop/prestashop-ui-kit/pull/93): Update errors of input group to use the exact same workflow of bootstrap, by [@NeOMakinG](https://github.com/NeOMakinG)


### Auto Upgrade module
* [#332](https://github.com/PrestaShop/autoupgrade/pull/332): Reverse arrays and use array_pop instead of array_shift, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@boubkerbribri](https://github.com/boubkerbribri), [@awurth](https://github.com/awurth), [@PierreRambaud](https://github.com/PierreRambaud), [@LorisB](https://github.com/LorisB), [@eternoendless](https://github.com/eternoendless), [@Matt75](https://github.com/Matt75), [@matks](https://github.com/matks), [@zalexki](https://github.com/zalexki), [@zuk3975](https://github.com/zuk3975), [@ttoine](https://github.com/ttoine), [@ksaandev](https://github.com/ksaandev), [@marcoguido](https://github.com/marcoguido), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@colinegin](https://github.com/colinegin), [@dependabot[bot]](https://github.com/apps/dependabot), [@kerin444](https://github.com/kerin444), [@atomiix](https://github.com/atomiix), [@jolelievre](https://github.com/jolelievre), [@juraj1000](https://github.com/juraj1000), [@jf-viguier](https://github.com/jf-viguier), [@florian-202](https://github.com/florian-202), [@PululuK](https://github.com/PululuK), [@clotaire202](https://github.com/clotaire202), [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul), [@erouvier29](https://github.com/erouvier29), [@manudas](https://github.com/manudas), [@patrickmyh](https://github.com/patrickmyh), [@NeOMakinG](https://github.com/NeOMakinG), [@arouiadib](https://github.com/arouiadib), [@marionf](https://github.com/marionf), [@mvorisek](https://github.com/mvorisek)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
