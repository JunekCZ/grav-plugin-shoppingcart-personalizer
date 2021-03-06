# [Grav](http://getgrav.org) Shoppingcart Personalizer

**If you encounter any issues, please don't hesitate
to [report
them](https://github.com/leotiger/grav-plugin-shoppingcart-personalizer/issues).**

> The Personalizer Add-On for [Shoppingcart](https://github.com/flaviocopes/grav-plugin-shoppingcart)

## What does this add-on plugin offer?

This add-on has two purposes, one is to show people how to write add-ons for the shoppingcart plugin and the second one
is to offer some enhancements and fixes for the shoppingcart plugin itself. Apart from this plugin I offer a second add-on
paying a small fee, the Shopping Cart Notify Add-On. The Shopping Cart Notify Add-On offers task automizations and multi-language
support and additional features.

## Introduction

At the time of publishing, GRAV offers two plugins to create and run online shops inside of a GRAV website and the only native
solution that does not require third party services is the former mentioned shoppingcart plugin that provides a good starting 
point for developers but not for site owners and administrators as it comes without many of the most basic features expected, e.g.
stock management, country restriction, single product, service vs. shippable product, etc. The incomplete list of features comprised in the Shoppingcart Personalizer Add-on includes

* stock configuration
* automatic stock updates with multi-language support
* maximum quantity of a product allowed in cart
* quantity steps for products
* minimum cart amount
* minimum free shipping amount
* configure dedicated store email
* checkout email confirmation
* support for unique products (nice for artists, etc.)
* mark product as service product (service products need no shipping)
* editable product id in admin
* show remove button in checkout cart if desired
* optionally remove existing product (necessary in the context of product variations)
* grouped product variations and configurations with pricing, stock, customer input
* stock updates for variations with multi-language support
* quantity / configuration steps for variations
* reflect configured variations and configuration in cart
* display variation (group) image on selection of variation if configured
* customer file uploads for products (once cart has been checked-out)
* email notification on customer personalizations
* display variation customizations (uploads, text) in frontend and backend
* add details order page to administration 
* display terms and conditions link and load in modal if bootstrapper / bootstrap support is available in the theme
* show add to cart button in catalogue pages
* display decimal separator as comma
* option to equalize image sizes
* define product image
* define catalogue image
* show multiple product images
* restrict countries (moved-in from notify as this is a quite essential feature, an out of the box feature)
* activate fancybox support for item images
* background colors for image containers (defaults to transparent)
* refactor javascript to allow optimized js load in the body region
* fix shoppingcart configuration injection problem
* inject checkout form into shoppingcart checkout page (related with configuration injection)
* improved theme integration possibilities allowing to specify the base templates that product pages shall extend (defaults to default)
* provide product configuration in an own tab in admin
* Compatible with existing add-ons for Shoppingcart

Addtionally I've prepared a fork of the shoppingcart plugin that includes more options for the checkout
form configuration adding support for textarea, re-captcha, etc. A Pull Request for the shoppingcart plugin, v.1.2.2 is
placed but you may update your shoppingcart plugin using the [fork](https://github.com/leotiger/grav-plugin-shoppingcart) as long as the proposals are not integrated into the shoppingcart plugin. But don't worry, this plugin mitigates problems of the shoppingcart plugin by refactoring many of its core functions.

The Shoppingcart-Notify Add-on allows you to:

* checks product availablility if checkout is called
* adds additional security checks server-side to prevent cart manipulations in the front-end
* sends confirmation email to customer with customizable template
* offers basic mailchimp integration (will be improved and enhanced)
* enhanced stock management with multi-language support
* digital downloads
* etc.

The Shoppingcart-Notify plugin will be soon available online and it will show up in the add-on section.

## Theme support tested

The plugin was tested with the antimatter and the quark theme. It also works on our propietary theme Studio.

## Complementary plugins

* [Breadcrumbs](https://github.com/getgrav/grav-plugin-breadcrumbs) 
* [Bootstrapper](https://github.com/getgrav/grav-plugin-bootstrapper)

## Further customization

You can customize the look and feel in several ways:

* by adding your own css definitions in your theme, etc.
* by copying the templates to your theme and maintain modified versions there

If you modify templates you do it at your own risk as you may break things.

## Language support

The plugin includes as of v0.9.4 of language definitions for English, German, Catalan and Spanish. Help with translation is highly appreciated.

## Installation

Installing the Shoppingcart Personalizer plugin can be done in three ways. The GPM (Grav Package Manager) installation method enables you to quickly and easily install the plugin with a simple terminal command, while the manual method enables you to do so via a zip file.

If you install manually please assure yourself that the plugin folder inside /user/plugins directory is named shoppingcart-personalizer. The manual install method requires
that you already dispose of the shoppingcart plugin in your GRAV instance.

The third method is through the Administration Panel.

### Administration Panel Installation (Preferred)

The simplest way to install this plugin is via the [Grav Admininitration Panel](https://learn.getgrav.org/admin-panel/plugins). Once inside of the Plugins section click ADD and select the 
Shoppingcart Personalizer for installation. This will install dependencies as well.


### GPM Installation

Another simple way to install this plugin is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's terminal (also called the command line).  From the root of your Grav instance type:

    bin/gpm install shoppingcart-personalizer

This will install the Shoppingcart Personlizer plugin into your `/user/plugins` directory within Grav. Its files can be found under `/your/site/grav/user/plugins/shoppingcart-personalizer`.

## Help

Help can be obtained via the [issue section](https://github.com/leotiger/grav-plugin-shoppingcart-personalizer/issues) but we cannot guarantee to answer in a timely or exhaustive fashion.
It will sometimes take some days to obtain responses and we will only answer to general problems. 
Site specific integration problems will not be addressed in the issue section.
If you have dedicated, site-specific integration neeeds, you may quote for support and we will send you an offer.

## Demo

You can see both add-ons (Personalizer and Notify) in action on [Tessa](https://www.tessa.es).

## Credits

Thanks to @flaviocopes for the [Shoppingcart plugin](https://gravcart.com/).
 
This plugin includes the [Jquery Fancybox](http://fancyapps.com/fancybox/3/) plugin. You can activate support in the configuration of the plugin.

## Known Issues

Hopefully this plugin will obtain some feedback and suggestions. I will try to enhance the plugin with additional
basic features in the future as I believe that GRAV needs better support for e-commerce.
