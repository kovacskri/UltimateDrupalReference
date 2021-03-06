# Ultimate Drupal Reference
When it comes to [Drupal](https://www.drupal.org/), there are a lot of videos, blog posts and general how-to's out there.  
While some of them are good, others are in need of improvement and a few of them are simply outdated.

This project will try to list you the **best, most promising and most efficient** resources that you might need when developing a Drupal site.  
**Important: This project will focus on Drupal 8 only!** 

At last but not least, every kind of of contribution is **welcome**!  
Fork it, create pull requests or simply add new issues!

## Table of contents
- [Installing Drupal](#installing-drupal)
- [Distributions](#distributions)
- [Modules](#modules)
  - [Commerce](#commerce)
  - [Content](#content)
  - [Developer tools](#developer-tools)
  - [Forms](#forms)
  - [Media](#media)
  - [Multilingualism](#multilingualism)
  - [Multisite](#multisite)
  - [SEO / Analytics](#seo--analytics)
  - [Security](#security)
  - [Site building](#site-building)
  - [Site navigation](#site-navigation)
  - [Social media](#social-media)
  - [User & Roles management](#user--roles-management)
  - [Views](#views)
- [Themes](#themes)
  - [Frontend themes](#frontend-themes)
  - [Admin themes](#admin-themes)
- [Video tutorials](#video-tutorials)
- [Drupal PaaS](#drupal-paas)
- [Credits](#credits)
- [License](#license)

## Local environment
In order to be able to run Drupal on your machine, you need a webserver with PHP and a SQL database server.
Please check the [official requirements page](https://www.drupal.org/docs/8/system-requirements) for more details.

If you prefer working with a VM, check following alternatives:
- [Docker](https://hub.docker.com/_/drupal/)
- [Drupal VM](https://www.drupalvm.com/)

## Installing Drupal
For details, please check the [official installation page](https://www.drupal.org/docs/8/install).   It is, however, **recommended** to use [https://getcomposer.org/](Composer) whenever possible.  
Check the [Composer template for Drupal projects](https://github.com/drupal-composer/drupal-project) to install Drupal quickly via Composer.

## Distributions
While Drupal 8 Core comes with lots of functionality already, the strength of Drupal lies in its extensibility.  
Distributions are full copies of Drupal that include Drupal Core, along with additional software such as themes, modules, libraries, and installation profiles.  
They're handy if you *really* just want to have a quick start with Drupal.
- [Druppio](https://www.drupal.org/project/druppio_small_business_distribution)
- [Lighting](https://www.drupal.org/project/lightning)
- [Open Social](https://www.drupal.org/project/social)
- [Thunder](https://www.drupal.org/project/thunder)
- [Varbase](https://www.drupal.org/project/varbase)
- .. and many more on [drupal.org](https://www.drupal.org/project/project_distribution)

## Modules

### Commerce
- [Drupal Commerce](https://www.drupal.org/project/commerce) - Drupal Commerce is used to build eCommerce websites and applications of all sizes.

### Content
- [Address](https://www.drupal.org/project/address) - Provides functionality for storing, validating and displaying international postal addresses.
- [Automatic Entity Label](https://www.drupal.org/project/auto_entitylabel) - Automatic Entity Label is a small and efficient module that allows hiding of entity label fields. To prevent empty labels it can be configured to generate the label automatically by a given pattern.
- [Corresponding Entity References](https://www.drupal.org/project/cer) - CER keeps reference fields in sync. If you have two entities that refer to each other using Entity Reference (or some other kind of reference field), it saves you the trouble of double-editing your entities in order to have them point at each other.
- [Default Content for D8](https://www.drupal.org/project/default_content) - The Default content module gives your module and install profile a way to ship default content as well as configuration.
- [Disable Messages](https://www.drupal.org/project/disable_messages) - Gives a site owner options to disable specific messages shown to end users.
- [D8 Editor Advanced link](https://www.drupal.org/project/editor_advanced_link) - Enhances the link Dialog in D8 CKEditor.
- [External Links](https://www.drupal.org/project/extlink) - External Links is a small module used to differentiate between internal and external links.
- [Field Formatter Class](https://www.drupal.org/project/field_formatter_class) - Allows site administrators to add classes to the outer HTML wrapper for any field display, so that CSS and Javascript can target them.
- [Iframe](https://www.drupal.org/project/iframe) - A custom field, which lets you add a complete iframe to your content types; including Src-URL, setting width and height, optionally a title above, and optionally a target attribute.
- [Image formatter link to image style](https://www.drupal.org/project/image_formatter_link_to_image_style) - This module provides an additional formatter for image core field, to link to an image style.
- [Office Hours](https://www.drupal.org/project/office_hours) - Defines a 'weekly office hours' field type, allowing you to specify when a location is open or closed.
- [Scheduler](https://www.drupal.org/project/scheduler) - Scheduler gives content editors the ability to schedule nodes to be published and unpublished at specified dates and times in the future.

### Developer tools
- [Config Ignore](https://www.drupal.org/project/config_ignore) - This module is a tool to let you keep the configuration you want, in place.
- [Configuration Split](https://www.drupal.org/project/config_split) - Enables you to create different configuration sets for a site.
- [Devel](https://www.drupal.org/project/devel) - A suite of modules containing fun for module developers and themers.
- [Environment Indicator](https://www.drupal.org/project/environment_indicator) - This module will help you to keep sane while working on your different environments by adding a configurable color bar to each one of your environments.
- [Hacked!](https://www.drupal.org/project/hacked) - This module scans the currently installed Drupal, contributed modules and themes, re-downloads them and determines if they have been changed.
- [Stage File Proxy](https://www.drupal.org/project/stage_file_proxy) - Stage File Proxy saves you time and disk space by sending requests to your development environment's files directory to the production environment and making a copy of the production file in your development site.

### Forms
- [Better Login](https://www.drupal.org/project/betterlogin) - Fancy and extendable login forms for Drupal.
- [CAPTCHA](https://www.drupal.org/project/captcha) - A CAPTCHA is a challenge-response test most often placed within web forms to determine whether the user is human.
- [Chosen](https://www.drupal.org/project/chosen) - Chosen uses the Chosen jQuery plugin to make your `<select>` elements more user-friendly.
- [Client-side hierarchical select](https://www.drupal.org/project/cshs) - A simple client-side hierarchical select widget for taxonomy terms.
- [Clientside Validation](https://www.drupal.org/project/clientside_validation) - This module adds clientside validation to all forms and webforms.
- [Honeypot](https://www.drupal.org/project/honeypot) - Honeypot uses both the honeypot and timestamp methods of deterring spam bots from completing forms on your Drupal site.
- [Prepopulate](https://www.drupal.org/project/prepopulate) - The Prepopulate module allows fields in most forms to be pre-populated from the $_REQUEST variable.
- [reCAPTCHA](https://www.drupal.org/project/recaptcha) - Uses the Google reCAPTCHA web service to improve the CAPTCHA system. It is tough on bots and easy on humans.
- [Webform](https://www.drupal.org/project/webform) - Webform is the module for making forms and surveys in Drupal.

### Media
- [Blazy](https://www.drupal.org/project/blazy) - Provides integration with bLazy to lazy load and multi-serve images to save bandwidth and server requests. The user will have faster load times and save data usage if they don't browse the whole page.
- [Image Optimize (or ImageAPI Optimize)](https://www.drupal.org/project/imageapi_optimize) - This is a toolkit for ImageAPI. It requires imageapi_gd or imageapi_imagemagick or any ImageAPI toolkit to work.
- [Media](https://www.drupal.org/project/media) - The Media module provides an extensible framework for managing files and multimedia assets, regardless of whether they are hosted on your own site or a 3rd party site - it is commonly referred to as a 'file browser to the internet'.
- [PhotoSwipe](https://www.drupal.org/project/photoswipe) - Use PhotoSwipe to display picture galleries on your Drupal website. This Javascript lightbox library offers very nice mobile browsing features (in particular swiping to the next picture)!
  - Note: As for the `1.0-beta3` release, it needs to be [patched](https://www.drupal.org/files/issues/path-capitals-for-composer-2855483-2.patch) when installed with Composer
- [Slick Carousel](https://www.drupal.org/project/slick) - Slick is a powerful and performant slideshow/carousel solution leveraging Ken Wheeler's Slick carousel.
  - Also make sure to check out it's sub modules such as e.g. [Slick Paragraphs](https://www.drupal.org/project/slick_paragraphs) or [Slick Entity Reference](https://www.drupal.org/project/slick_entityreference)
- [Video](https://www.drupal.org/project/video) - Video module allows you to upload video in any format, play video in any format, transcode video to H.246, Theora, VP8(Web compatible formats) using Zencoder or FFMPEG automatically creates video thumbnails, copy and deliver videos from cloud file systems like Amazon S3.
- [Video Embed Field](https://www.drupal.org/project/video_embed_field) - Video Embed field creates a simple field type that allows you to embed videos from YouTube and Vimeo and show their thumbnail previews simply by entering the video's url.

### Multilingualism
- [Language Cookie](https://www.drupal.org/project/language_cookie) - Adds an extra "Cookie" field to the Language Negotiation settings, allowing the language to be set according to a cookie.

### Multisite
- [Domain Access](https://www.drupal.org/project/domain) - The Domain Access project is a suite of modules that provide tools for running a group of affiliated sites from one Drupal installation and a single shared database.

### SEO / Analytics
- [Google Analytics](https://www.drupal.org/project/google_analytics) - Adds the Google Analytics web statistics tracking system to your website.
- [Metatag](https://www.drupal.org/project/metatag) - The Metatag module allows you to automatically provide structured metadata, aka "meta tags", about a website.
- [Pathauto](https://www.drupal.org/project/pathauto) - The Pathauto module automatically generates URL/path aliases for various kinds of content (nodes, taxonomy terms, users) without requiring the user to manually specify the path alias.
- [Piwik Web Analytics](https://www.drupal.org/project/piwik) - Adds the Piwik web statistics tracking system to your website.
- [Redirect](https://www.drupal.org/project/redirect) - Manage custom site redirects.
- [Simple XML sitemap](https://www.drupal.org/project/simple_sitemap) - Every webpage needs an automatic XML sitemap generator for SEO reasons. This module aims to be a replacement for the xmlsitemap module for Drupal 8.

### Security
- [Password Reset Landing Page (PRLP)](https://www.drupal.org/project/prlp) - The Password Reset Landing Page "PRLP" module enhances the original password reset landing page by letting a user set their new password at the same time they "log in" using the one-time-login link.
- [Password Strength](https://www.drupal.org/project/password_strength) - The Password Strength module provides realistic password strength measurement and server-side enforcement for Drupal sites using pattern-matching and entropy calculation.
- [Persistent Login](https://www.drupal.org/project/persistent_login) - The Persistent Login module provides a "Remember Me" option on the user login form.
- [Protected Pages](https://www.drupal.org/project/protected_pages) - Protected Pages modules allows the administrator to secure any page in your website by password.
- [Rabbit Hole](https://www.drupal.org/project/rabbit_hole) - Rabbit Hole is a module that adds the ability to control what should happen when an entity is being viewed at its own page.
- [Shield](https://www.drupal.org/project/shield) - PHP Authentication shield. It creates a simple shield for the site with Apache authentication.

### Site building
- [Admin Toolbar](https://www.drupal.org/project/admin_toolbar) - The Admin Toolbar intends to improve the default Drupal Toolbar (the administration menu at the top of your site) to transform it into a drop-down menu, providing a fast access to all administration pages.
- [Block Group](https://www.drupal.org/project/blockgroup) - This module extends the standard Drupal block system with block groups. Each block group provides a new block as well as a corresponding region. Child blocks can be moved into any group region.
- [Custom Search](https://www.drupal.org/project/custom_search) - This module alters the default search box in many ways. If you need to have options available like in advanced search, but directly in the search box, this module is for you.
- [Easy Breadcrumb](https://www.drupal.org/project/easy_breadcrumb) - The Easy Breadcrumb module provides a plug-and-play block to be embedded in your pages, typically at some place near the page's header.
- [Entity Browser](https://www.drupal.org/project/entity_browser) - The goal of this module is to provide a generic entity browser/picker/selector.
- [Field Group](https://www.drupal.org/project/field_group) - Fieldgroup will, as the name implies, group fields together. All fieldable entities will have the possibility to add groups to wrap their fields together.
- [GraphQL](https://www.drupal.org/project/graphql) - This module lets you craft and expose a GraphQL schema for Drupal 8.
- [Linkit - Enriched linking experience](https://www.drupal.org/project/linkit) - Linkit provides an easy interface for internal and external linking with wysiwyg editors by using an autocomplete field.
- [Menu Breadcrumb](https://www.drupal.org/project/menu_breadcrumb) - This module allows you to use the menu the current page belongs to for the breadcrumb, generating breadcrumbs from the titles of parent menus.
- [Menu Link Attributes](https://www.drupal.org/project/menu_link_attributes) - This module allows you to add attributes to your menu links.
- [Menu Link Weight](https://www.drupal.org/project/menu_link_weight) - This module replaces the standard numeric weight dropdown widget for menu links in the node form with a tabledrag widget that lists all children for the selected parent.
- [Paragraphs](https://www.drupal.org/project/paragraphs) - Paragraphs is the new way of content creation! It allows you — Site Builders — to make things cleaner so that you can give more editing power to your end-users.
  - Also check out [Paragraphs Edit](https://www.drupal.org/project/paragraphs_edit)
- [Search Autocomplete](https://www.drupal.org/project/search_autocomplete) - This module allows you to add autocomplete functionality to virtually any fields of a Drupal site. During the input, the field will be expanded and offers a list of suggestions before you start the search.
- [Simple hierarchical select](https://www.drupal.org/project/shs) - Simple hierarchical select defines a new form widget for taxonomy fields to select a term by "browsing" through the vocabularies hierarchy.
- [Token](https://www.drupal.org/project/token) - Provides additional tokens not supported by core (most notably fields), as well as a UI for browsing tokens.
- [Vertical Tabs Config](https://www.drupal.org/project/vertical_tabs_config) - This module allows you to hide and re-order vertical tabs on add/edit node pages depending on content type and role.

### Site navigation
- [Responsive and off-canvas menu](https://www.drupal.org/project/responsive_menu) - This module integrates the mmenu jQuery plugin with Drupal's menu system with the aim of having an off-canvas mobile menu and a horizontal menu at wider widths.

### Social media
- [Ridiculously Responsive Social Sharing Buttons](https://www.drupal.org/project/rrssb) - Social sharing buttons that you can drop into any website with attractive SVG-based icons, small download, and browser compatibility. No 3rd-party scripts.

### User & Roles management
- [Group](https://www.drupal.org/project/group) - The Group module allows you to create arbitrary collections of your content and users on your site and grant access control permissions on those collections.
- [Permissions by Term](https://www.drupal.org/project/permissions_by_term) - The Permissions by Term module extends Drupal by functionality for restricting access to single nodes via taxonomy terms.
- [RoleAssign](https://www.drupal.org/project/roleassign) - RoleAssign specifically allows site administrators to further delegate the task of managing user's roles while withholding the Administer permissions permission.
- [Taxonomy access fix](https://www.drupal.org/project/taxonomy_access_fix) - This module adds more specific Taxonomy permissions.

### Views
- [Better Exposed Filters](https://www.drupal.org/project/better_exposed_filters) - The Better Exposed Filters module replaces the Views' default single- or multi-select boxes with radio buttons or checkboxes, respectively.
- [DraggableViews](https://www.drupal.org/project/draggableviews) - DraggableViews makes rows of a view "draggable" which means that they can be rearranged by Drag'n'Drop.
- [Views Reference Field](https://www.drupal.org/project/viewsreference) - This field in conjunction with the Paragraphs module, makes for a very powerful content management system, allowing addition of just about any kind of content into an entity page.

## Themes

### Frontend themes
- [Bootstrap](https://www.drupal.org/project/bootstrap) - This base theme bridges the gap between Drupal and the Bootstrap Framework.
- [Drupal8 Zymphonies Theme](https://www.drupal.org/project/drupal8_zymphonies_theme) - Drupal8 Zymphonies Theme is the first Zymphonies Drupal 8 Free Responsive Theme which has many new features.
- [ZURB Foundation](https://www.drupal.org/project/zurb_foundation) - Zurb Foundation for Drupal is the official implementation of the framework by the same name.

### Admin themes
- [Adminimal - Responsive Administration Theme](https://www.drupal.org/project/adminimal_theme) - A modern and minimalist design that makes administration an easy and fun experience.
  - Also install [Adminimal Admin Toolbar](https://www.drupal.org/project/adminimal_admin_toolbar) when using this theme.

## Video tutorials
- [Rendering & caching: a journey through the layers](https://www.youtube.com/watch?v=MQGUzubY35I)
- [Decouple your Twig from PHP and make Frontenders happy!](https://www.youtube.com/watch?v=Z4gMLSD5MAU)

## Drupal PaaS
When it comes to hosting a Drupal site, you can always use any server which supports the system requirements.
However, there are a few Drupal specialized PaaS hosting options you might want to consider as well.

- [Acquia Cloud](https://cloud.acquia.com/)
- [amazee.io](https://www.amazee.io/)
- [Pantheon](https://pantheon.io/)
- [Platform.sh](https://platform.sh/)

## Drupal Community
If you wish to get more involved with the Drupal community, or want to get in contact with Drupal developers, you can use the following platforms.
- [Drupal.org](https://www.drupal.org) - The main hub of the Drupal community. News, discussions about the development of Drupal core, official documentation, seeking aid 
with specific modules, job marketplace and everything Drupal.
- [Slack](https://www.drupal.org/slack) - A list of Drupal related Slack channels.
- [Meetups](https://www.meetup.com/topics/drupal/) - Participate in Drupal meetups in your area and meet the community face to face.

## Credits
- [David Pacassi Torrico](https://www.drupal.org/u/dpacassi) - Project maintainer
- [Liip](https://www.liip.ch/) - Support

## License
```
MIT License

Copyright (c) 2018 David Pacassi Torrico

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
