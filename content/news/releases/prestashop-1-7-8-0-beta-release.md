---
layout: post
aliases: ["/news/prestashop-1-7-8-0-beta-release"]
slug: "prestashop-1-7-8-0-beta-release"
title:  "PrestaShop 1.7.8.0 beta is open for feedback!"
subtitle: "You can download it and test it"
date: 2021-06-01
authors: [ PrestaShop ]
image: /assets/images/2021/06/banner-178-beta.png 
icon: icon-leaf
tags:
 - version
 - beta
 - minor
 - releases
 - "1.7.8"
 - "1.7"
---

The first Beta version of PrestaShop 1.7.8.0 is now ready for you to test!

![1.7.8.0 Beta is available!](/assets/images/2021/06/banner-178-beta.png )

We are very happy to announce today the release of the beta version of 1.7.8.
This version includes many features and bug fixes, we count on you to test the Beta and report any bugs you encounter.

Main new features are: the redesign of the translation system that facilitates the export and the translation of your modules and themes, a new header for multistore allowing to configure the different stores more easily and quickly, and many other improvements.

With more than 1,340 merged Pull Requests and 242 bug fixes, including 15 major and 5 Topwatcher (issues that are followed by more than 5 people), this is one of our biggest releases yet!

Also, a big thank you to our 163 contributors without whom we would not have had this beautiful version. And a warm welcome to the 93 new contributors for their first contribution.

This Beta release is a great opportunity for you to start working with it before we release a stable version. Go download and install this Beta version as a test store, either on your machine or your web hosting, then play with it – and give us your feedback! We need you to test this new version of PrestaShop.

If you find regressions compared to previous versions, please create an [issue on Github](https://github.com/PrestaShop/PrestaShop/issues/new/choose) to help us make it stable more quickly.

**Remember, this beta version is pre-release software and is expected to have bugs. Do not use it in your production shop!**

## New features & improvements

### Translations

- The translation feature has been revamped, adding the possibility to export back-office, front-office, email, themes, and module translations.

![The new translation export](/assets/images/2021/06/translation-export.png)


- Modules using the [new translation system](https://devdocs.prestashop.com/1.7/modules/creation/module-translation/new-system/) introduced in 1.7.6 can now distribute their own translation files in the XLF format.
Users can use the export tool to migrate from legacy PHP catalogue to XLF catalogue

### Multistore

#### New Multistore header

One of the main difficulties for the merchants using the multistore was to know which store they were configuring in the back-office and this was bringing a lot of configuration errors.

This is why a new back-office header has been added. Its color can be customized for each shop or group of shop(s) in the multistore parameters. It makes it easier for the merchants to know which shop or group they are configuring and therefore avoid configuration mistakes.

![The new multistore header](/assets/images/2021/06/multistore_header.png)

#### New specific settings drop-down

This drop-down is displayed in the "all shops" context and group contexts. It allows the user to see which settings have been customized in one or several specific shops. Therefore the settings that will not be overridden following a change made in "all shops" or in a group context are easier to spot.

For now, it has been implemented only in the Maintenance page of the back-office.

![The new multistore specific setting drop down](/assets/images/2021/06/Specific_settings_drop_down_multistore.png)

#### Checkboxes

Checkboxes are displayed in a specific shop context and a group context.

They are displayed before each field/toggle/parameter and allow merchants to apply specific settings to a store or a group of shops. Merchants just need to select the parameter to modify, bring their modifications, and then save.

For now, they have been implemented only in the Maintenance page of the back-office.

#### Linklist module

Many users reported that the [linklist module](https://github.com/PrestaShop/ps_linklist) was not [compliant with multistore](https://github.com/PrestaShop/PrestaShop/issues/9795), as it was quite important for their activity to be able to feature different links in the footer depending on the shop.

This is why it was decided to make a new version (v5.0.0) of this module to make it [compatible with multistore](https://github.com/PrestaShop/ps_linklist/pull/114) and it was achieved thanks to the great work of [Krystian Podemski](https://github.com/kpodemski) :pray:

### Experimental features

PrestaShop 1.7.8 introduces Experimental features (also known as "Feature flags"). This technique, widely used in the sofware world, provides curious or adventurous users the option to test out new features that aren't stable enough for general use yet. This allows developers to experiment, get feedback, and iterate more quickly – without ever altering the user's experience nor the system's stability. You can enable and disable experimental features in Advanced Parameters > Experimental Features.

![The new Experimental features page](/assets/images/2021/06/experimental-features.png)

### Back-office Product page

The product page has undergone a major rehaul, but it is unfortunately still not ready for prime time. However, thanks to the Experimental Features introduced in 1.7.8, power users can now test its exciting new features right now! Once activated, merchants can manage their products using both the regular and the Experimental product page, and compare them side by side.

The experimental product page is due to replace the current one in the next PrestaShop version. Please do test it out and give us your feedback!

Here are the features that you can test now:

- **Significantly speedier combination management**

The list of combinations is now paginated, providing a significant performance improvement for products with lots of combinations.

- **Find combination by attributes**
 
This can help merchants to find the right combination quickly, especially when there are lots of them.

- **Bulk suppression in the image manager**

Merchants can remove images from the product easily (which is especially useful when the product features a large number of images). 

- **Replace an image**

It is no longer necessary to remove, add, then re-assign an image.

### Improvements of the UI Kit

- PrestaShop back-office UI Kit has been improved to have a solid Design System with adjustment of alert colors, font size, buttons contrasts, and an enhancement of the responsiveness. [#16587](https://github.com/PrestaShop/PrestaShop/issues/16587) [#22358](https://github.com/PrestaShop/PrestaShop/issues/22358) [#104](https://github.com/PrestaShop/prestashop-ui-kit/pull/104)

![the new mobile improvements](/assets/images/2021/06/mobile-improvements.png)


### Front-Office improvements

- Improvements of classic theme images width, accessibility and some [lighthouse](https://developers.google.com/web/tools/lighthouse) KPI [#23352](https://github.com/PrestaShop/PrestaShop/issues/23352) [#20775](https://github.com/PrestaShop/PrestaShop/pull/20775)
- The implementation of Native Lazy Loading on theme Classic ([see the complete detail of the feature](https://build.prestashop.com/news/journey-to-improve-the-time-to-interactive-metric/)) [#19549](https://github.com/PrestaShop/PrestaShop/issues/19549)
- The label ‘Out of Stock’ is displayed on Catalog pages [#21105](https://github.com/PrestaShop/PrestaShop/issues/21105)
- The images on the Product Page can now be swiped on mobile for Classic theme [#20431](https://github.com/PrestaShop/PrestaShop/issues/20431)
- The subcategories are displayed on Categories pages [#10407](https://github.com/PrestaShop/PrestaShop/issues/10407)
- Return a 404 response when user visits product page for a product that does not exist [#21330](https://github.com/PrestaShop/PrestaShop/pull/21330/)

### Back-Office improvements

- TinyMCE mobile theme is enabled in the back-office [#23225](https://github.com/PrestaShop/PrestaShop/issues/23225)
- The overrides active in a shop are displayed in the Informations tab [#21368](https://github.com/PrestaShop/PrestaShop/issues/21368)
- A new order internal note is available in the Order View Page [#14753](https://github.com/PrestaShop/PrestaShop/issues/14753)
- Back-office users can upload custom avatars [#18653](https://github.com/PrestaShop/PrestaShop/issues/18653)

## Notable fixes

### **Topwatchers:**

- When Clear cache button was clicked twice, the user would see an error page [#11105](https://github.com/PrestaShop/PrestaShop/issues/11105) (Major)
- Profiler was not compatible with hooks and module [#9659](https://github.com/PrestaShop/PrestaShop/issues/9659)
- Double click on "Add to cart" on the product page FO was freezing the page [#9634](https://github.com/PrestaShop/PrestaShop/issues/9634) (Major)
- Select the payment method if only one available by default [#11435](https://github.com/PrestaShop/PrestaShop/issues/11435)
- Wrong translations of back-office menu tabs [#9816](https://github.com/PrestaShop/PrestaShop/issues/9816)

### Major bugs:

**Front-Office**

- When a product had a specific price applied and was discounted by unit, the discount displayed on the product page was false [#16163](https://github.com/PrestaShop/PrestaShop/issues/16163)
- Guest Order Tracking redirected to shop Homepage when Friendly URLs were disabled [#20194](https://github.com/PrestaShop/PrestaShop/issues/20194)
- An error was displayed on checkout when Legal compliance module was installed [#12509](https://github.com/PrestaShop/PrestaShop/issues/12509)
- Checkout slowdown when many orders were made with a Guest account [#16584](https://github.com/PrestaShop/PrestaShop/issues/16584)
- Ecotax was displayed tax excl. instead of tax incl. [#18835](https://github.com/PrestaShop/PrestaShop/issues/18835)
- Confirmation button on Checkout should be disabled if Terms and conditions are not approved [#19161](https://github.com/PrestaShop/PrestaShop/issues/19161)

**Back-Office**

- An exception was thrown when adding an invalid parameter to the Language form and "No picture" image [#22500](https://github.com/PrestaShop/PrestaShop/issues/22500)
- In Back-Office, some of the JavaScript code relied on form field's ids and attributes that were modified in 1.7.8 [#21819](https://github.com/PrestaShop/PrestaShop/issues/21819)
- When creating a customer account, the number of characters was only checked browser-side [#19505](https://github.com/PrestaShop/PrestaShop/issues/19505)
- It was possible to create a catalog price rule with percentage value greater than 100% [#19013](https://github.com/PrestaShop/PrestaShop/issues/19013)
- A bug in TinyMCE 4.0.16 was creating errors, fixed by upgrading TinyMCE to 4.9.8 [#11011](https://github.com/PrestaShop/PrestaShop/issues/11011)
- Unit price was reset to 0 upon activating/disabling or duplicating products from the Product List [#10792](https://github.com/PrestaShop/PrestaShop/issues/10792)
- Installing PrestaShop with SSL was complex because some settings were not acknowledged [#10482](https://github.com/PrestaShop/PrestaShop/issues/10482)

**WebServices**

- The id_group_shop was shared instead of id_shop_group in webservice parameter [#19566](https://github.com/PrestaShop/PrestaShop/issues/19566)

**Distribution**

- `.docker` folder should not be inside release zip [#22233](https://github.com/PrestaShop/PrestaShop/issues/22233)


## Notable technical improvements

**Hooks**
- New hooks into Presenters, allowing to enrich the data built by these services [#11125](https://github.com/PrestaShop/PrestaShop/issues/11125)
- New mechanism to extend TinyMCE configuration [#19408](https://github.com/PrestaShop/PrestaShop/issues/19408)
- New hooks for cart modal - crosseling and promotion [#17709](https://github.com/PrestaShop/PrestaShop/issues/17709)
- Ability to enable and disable Hooks [#20848](https://github.com/PrestaShop/PrestaShop/issues/20848)
- Allow override of checkoutProcess construction [#19848](https://github.com/PrestaShop/PrestaShop/issues/19848)

**Tooling**
- Apply [PHPStan](https://phpstan.org/) level 4 [#16471](https://github.com/PrestaShop/PrestaShop/issues/16471)
- Use a custom PHPStan extension for PrestaShop [#22728](https://github.com/PrestaShop/PrestaShop/issues/22728)
- Apply ESLint to themes and Classic Theme folders [#20080](https://github.com/PrestaShop/PrestaShop/pull/20080)
- Apply ESLint to default back-office Theme [#22998](https://github.com/PrestaShop/PrestaShop/issues/22998)
- Apply StyleLint to default back-office Theme [#22885](https://github.com/PrestaShop/PrestaShop/issues/22885)

**Theme**
- Remove microdata in HTML flow and replace by JSON-LD for Classic theme [#22867](https://github.com/PrestaShop/PrestaShop/issues/22867)
- CSS classes / element attributes selectors now prefixed by `js-` [#14346](https://github.com/PrestaShop/PrestaShop/issues/14346)
- Add selectors mapping so themes can override it [#20002](https://github.com/PrestaShop/PrestaShop/pull/20002)
- Update jQuery from 3.4.1 to 3.5.1 [#23122](https://github.com/PrestaShop/PrestaShop/pull/23122)

**Other**
- Fix sessions cookies SameSite bug [#22711](https://github.com/PrestaShop/PrestaShop/issues/22711)
- Enabled High DPI support in ImageRetriever [#19798](https://github.com/PrestaShop/PrestaShop/issues/19798)
- Make the back-office menu translatable through the translation interface and fix many translation problems when installing other languages [#9762](https://github.com/PrestaShop/PrestaShop/issues/9762)
- There is no more legacy back-office service container, the Symfony container is now available everywhere: [#14995](https://github.com/PrestaShop/PrestaShop/issues/14995)
- New Webservices endpoint to manage and download Attachments [#12728](https://github.com/PrestaShop/PrestaShop/pull/12728)
- The UI Kit source files are now imported [#18396](https://github.com/PrestaShop/PrestaShop/pull/18396)
- Update jQuery from 3.4.1 to 3.5.1 on default BO theme [#23122](https://github.com/PrestaShop/PrestaShop/pull/23122)
- Update BO theme style in legacy pages to match the UI kit [#22435](https://github.com/PrestaShop/PrestaShop/issues/22435)
- Introduce Javascript component loading through window.prestashop [#20591](https://github.com/PrestaShop/PrestaShop/pull/20591)


## Dependencies and Software compatibility

- Add blockwishlist v2.0.0 as native module [#23617](https://github.com/PrestaShop/PrestaShop/pull/23617)
- Remove archived modules from the ZIP [#23617](https://github.com/PrestaShop/PrestaShop/pull/23617)
- Update CLDR to latest version 38 (2020-10-28) [#21678](https://github.com/PrestaShop/PrestaShop/issues/21678)
- Enable use of Composer 2.0 [#20986](https://github.com/PrestaShop/PrestaShop/issues/20986)
- Enable compatibility for PHP 7.4 [#16477](https://github.com/PrestaShop/PrestaShop/issues/16477)

## Symfony migration

See the new pages migrated in Symfony, we are now about 65% of the Back-Office pages migrated.

- International > Locations > Zones
- International > Locations > Add new / edit zone

## Download

You can download PrestaShop 1.7.8.0 beta here:  

{{< cta "https://download.prestashop.com/download/releases/prestashop_1.7.8.0-beta.1.zip" >}}Download PrestaShop 1.7.8.0 beta now!{{< /cta >}}


## How to help test 1.7.8

Your feedback on this beta is essential. The more regressions you find right now, the fewer bugs there will be on the final release, which means fewer patch versions and fewer problems on your (or your customer's) online store. 

You must:

- Install it and test that there is no regression compared to the 1.7.7 version
- If you develop modules or themes, test them on this version
- Test the auto-upgrade module through the [local archive channel](https://devdocs.prestashop.com/1.7/development/upgrade-module/channels/#archive). You just have to upload the zip into `admin/autoupgrade/download`
- [Report regressions on GitHub](https://github.com/PrestaShop/PrestaShop/issues) (read how to [report issues](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/))
- Fix regressions by creating a [pull request](https://github.com/PrestaShop/PrestaShop/compare) (read the [contribution guidelines](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/))

If you have any questions about the version and its features, feel free to share them on [the PrestaShop open source project's Slack](https://join.slack.com/t/prestashop/shared_invite/zt-dkmbz5qf-I~FlEWwmRUOXunc5ui0Ucg).

## Known issues 

- [When the catalog is exported the metadata is missing](https://github.com/PrestaShop/PrestaShop/issues/24716)
- [When reducing the screen in the order page, the icon of error, confirmation, warning messages is broken](https://github.com/PrestaShop/PrestaShop/issues/24695)
- [An error is displayed in the console when adding a discount on the Add New Order Page](https://github.com/PrestaShop/PrestaShop/issues/24556)
- [On the Add new Order page when I change the product quantity, the page freezes](https://github.com/PrestaShop/PrestaShop/issues/24554)
- [When we add an order note with invalid data, an update successful alert is displayed](https://github.com/PrestaShop/PrestaShop/issues/24534)
- [When adding a product into a new invoice in the Order Page, the block product new invoice info is not displayed](https://github.com/PrestaShop/PrestaShop/issues/24533)
- [The Invoice details on the Order Preview is missing the address mail of the customer](https://github.com/PrestaShop/PrestaShop/issues/24482) 
- [When Adding a new theme, an error 404 is displayed in the console](https://github.com/PrestaShop/PrestaShop/issues/24468) 
- [When the client uses another address for the invoice as a guest, we are redirected to the Information step instead of the Shipping method step](https://github.com/PrestaShop/PrestaShop/issues/24465)
- [When an account is created, an exception is displayed when the first name and/or last name fields contain invalid characters](https://github.com/PrestaShop/PrestaShop/issues/24464)
- [When browsing a disabled category, an error is displayed](https://github.com/PrestaShop/PrestaShop/issues/24370)
- [The scrollbar is missing in the new multistore dropdown](https://github.com/PrestaShop/PrestaShop/issues/24333)
- [The warning message is empty when we try to remove a customer from a specific price](https://github.com/PrestaShop/PrestaShop/issues/24142)
- [The summary and description fields of the Product Page form allow more characters than the defined limit](https://github.com/PrestaShop/PrestaShop/issues/24131)
- [When running a CLI command prestashop:update:sql-upgrade-file-hooks-listing and prestashop:update:configuration-file-hooks-listing, an error is displayed](https://github.com/PrestaShop/PrestaShop/issues/24023)
- [The new Multistore header is not displayed on Product Add / Edit page](https://github.com/PrestaShop/PrestaShop/issues/23937)
- [When modifying a translation of Email Body, an error is displayed](https://github.com/PrestaShop/PrestaShop/issues/23878)
- [When searching for a translation through the interface, the « leaves » of the tree that do not include the searched term are not disabled](https://github.com/PrestaShop/PrestaShop/issues/23876)
- [An error is displayed in the browser console when creating a category](https://github.com/PrestaShop/PrestaShop/issues/23365)
- [Cannot add an official currency to a non-official language from the CLDR](https://github.com/PrestaShop/PrestaShop/issues/22545)
- [The block to promote the discounts is removed after adding a cart rule on Checkout](https://github.com/PrestaShop/PrestaShop/issues/21961)
- [The Menu Page should be disabled in the Back-Office](https://github.com/PrestaShop/PrestaShop/issues/21107)
