# Awesome Yii Framework

A curated list of awesome Yii Framework extensions, tutorials and other nice things.
Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) and other [awesome lists](https://github.com/sindresorhus/awesome).

## ToC

* [Yii 2.*](#yii-2)
* [Yii 1.*](#yii-1)

---
## Official Resources

* [Official site](http://yiiframework.com/)
* [Official community](http://www.yiiframework.com/community/)

---
# Yii 2.*

## Tutorials

* The definive guide to Yii2:  [HTML](http://stuff.cebe.cc/yii2docs/guide-README.html), [PDF](http://stuff.cebe.cc/yii2-guide.pdf) (work in progress).
* [Try Yii2](https://github.com/iJackUA/try-yii2) - Vagrant VM + Ansible provisioning = Complete readymade virtual server Yii2 playground.


## Project structure examples

* Official [basic](http://www.yiiframework.com/doc-2.0/guide-apps-basic.html) and [advanced](http://www.yiiframework.com/doc-2.0/guide-apps-advanced.html) structures. [Code](https://github.com/yiisoft/yii2/tree/master/apps).
* [Minimal Application Template](https://github.com/samdark/yii2-minimal) by samdark.
* [Practical Application Template](https://github.com/kartik-v/yii2-app-practical) by kartik-v (and its variations ["A"](https://github.com/kartik-v/yii2-app-practical-a) and ["B"](https://github.com/kartik-v/yii2-app-practical-b)).
* [Demo blog on AngularJS with server-side Yii2 Rest API](https://github.com/githubjeka/angular-yii2) by githubjeka.

## Extensions

### Widgets / GUI

* [kartik-v/yii2-widgets](https://github.com/kartik-v/yii2-widgets) - Collection of useful widgets.
* [Krajee Yii Extensions](http://demos.krajee.com/) - a collection of extensions & modules.
* [Lepture Markdown editor](https://github.com/iJackUA/yii2-lepture-markdown-editor-widget) - a markdown editor you really want.

### Social

* [kartik-v/yii2-social](https://github.com/kartik-v/yii2-social) - a module for embedding social plugins and widgets.
* [Kudos](https://github.com/iJackUA/yii2-kudos-widget) - widget for Svbtle style Kudos.

### Geo / Maps

* [2amigos/yii2-leaflet-library](https://github.com/2amigos/yii2-leaflet-library) - extension library to display interactive maps with Leaflet.

### Database

* [yii2-arangodb](https://github.com/DevGroup-ru/yii2-arangodb) - ArangoDB integration for the Yii2 : Connection, Query, ActiveRecord, Migrations.
* [2amigos/yii2-taggable-behavior](https://github.com/2amigos/yii2-taggable-behavior) - behavior functions for tagging.
* [2amigos/yii2-translateable-behavior](https://github.com/2amigos/yii2-translateable-behavior) - handles ActiveRecord's attribute translations.

### File System

* [2amigos/yii2-file-upload-widget](https://github.com/2amigos/yii2-file-upload-widget) - handles a BlueImp jQuery File Upload plugin.

### Other

* [2amigos/yii2-qrcode-helper](https://github.com/2amigos/yii2-qrcode-helper) - helper allows you to render QrCode.
* [monitorbacklinks/yii2-wordpress](https://github.com/monitorbacklinks/yii2-wordpress) - a component for integration with Wordpress CMS via XML-RPC API.

## CMS (Yii based)

* Not known.

## Tools and integrations

* Not known.

## Books

* Larry Ulman has a [plan to update his Yii book](http://www.larryullman.com/2012/09/12/yii-2-and-the-yii-book/) for Yii2 after its release.
* [Yii2 Cookbook](https://github.com/samdark/yii2-cookbook/blob/master/book/README.md) by samdark (work in progress).

---
# Yii 1.*

## Tutorials

* For sure you should start with [official guides](http://www.yiiframework.com/tutorials/).
* [Yii 1.1: How to learn Yii?!](http://www.yiiframework.com/wiki/268/how-to-learn-yii) - Bring some learning flow recommendation.
* [A longer series on installing, using, and customizing the Yii framework](http://www.larryullman.com/series/learning-the-yii-framework/) by Larry Ulman.
* [Under the Hood of Yii’s Component Architecture](http://www.sitepoint.com/yii-under-the-hood-1/) (3 parts) - must read to get deep understanding of what Components are in Yii.

## Project structure examples

* [Yiinitializr](http://yiinitializr.2amigos.us/) - a project template generator. Has 3 options - basic, intermediate and advanced.
* [YiiBoilerplate](https://github.com/clevertech/YiiBoilerplate) - structure for enterprise-grade websites. Vagrant, test and static code analysis tool inside.
* [crisu83/yii-app](https://github.com/crisu83/yii-app) - advanced structure, Vagrant and basic set of extensions inside.
* [YiiBackboneBoilerplate](https://github.com/clevertech/YiiBackboneBoilerplate) - the flexibility of YiiBoilerplate with a twist for BackboneJS applications.


## Extensions

### Widgets / GUI

* [YiiBooster](http://yiibooster.clevertech.biz/) - a collection of Bootstrap based widgets.
* [YiiWheels](http://yiiwheels.2amigos.us/) - like a YiiBooster, but with more optimized approach.
* [YiiStrap](http://www.getyiistrap.com/) - the ultimate Twitter Bootstrap extension for Yii.
* [YiiFoundation](https://github.com/2amigos/yiifoundation) -  extension library for ZURB Foundation Framework.

### Database

* [MongoYii](https://github.com/Sammaye/MongoYii) - a Yii MongoDB ORM.

### Input

* [Imperavi redactor widget](https://github.com/yiiext/imperavi-redactor-widget) - Imperavi Redactor WYSIWYG widget (OEM-licensed for Yii).
* [X-editable](https://github.com/vitalets/x-editable-yii) - bundle of widgets and server-side component for creating editable elements in Yii application.

### Image

* [crisu83/yii-image](https://github.com/crisu83/yii-image) - image versioning and manipulation.

### Authentication / RBAC

* [yii-auth](https://github.com/Crisu83/yii-auth) - web UI for Yii's authorization manager.
* [yii-eauth](https://github.com/Nodge/yii-eauth) - allows to authenticate users by the OpenID, OAuth 1.0 and OAuth 2.0 providers.

### Scaffolding

* [giix](https://github.com/rcoelho/giix) - gii extended.
* [yii-caviar](https://github.com/crisu83/yii-caviar) - next generation code generation for Yii.

### Template

* [Twig renderer](https://github.com/yiiext/twig-renderer) - allows to use [Twig](http://twig.sensiolabs.org/) template engine in views.
* [Smarty renderer](https://github.com/yiiext/smarty-renderer) - allows you to use [Smarty 3](http://www.smarty.net/) templates in views.
* [Fenom renderer](https://bitbucket.org/RSol/rfenomviewrender) - allows to use [Fenom](https://github.com/bzick/fenom) template engine in views.
* [Quicky renderer](https://github.com/yiiext/quicky-renderer) -  allows to use [Quicky](https://github.com/kakserpom/quicky) template engine in views.
* [Haml renderer](https://github.com/delfit/yii-haml) - allows to use [Haml](http://en.wikipedia.org/wiki/Haml) in views.

### Debug

* [Yii2 debug panel port](https://github.com/zhuravljov/yii2-debug) - debug panel for Yii 1.1 (ported from Yii 2).
* [Debug toolbar](http://www.yiiframework.com/extension/yii-debug-toolbar/) - a configurable set of panels that display various debug information about the current request/response.
* [Db profiler](https://github.com/samdark/yii-db-profiler) - Yii profiler adjusted to deal with MySQL performance optimizations.

### API

* [RESTFullYii](https://github.com/evan108108/RESTFullYii) - full HTTP verb support for resources, the ability to offset, limit, sort, filter and manipulate related data.

### Other

* [EAV behavior](https://github.com/yiiext/eav-behavior) - implements entity-attribute-value pattern.
* [Nested Set Behavior](https://github.com/yiiext/nested-set-behavior) - AR models behavior that allows to work with nested sets tree.
* [Activerecord relation behavior](https://github.com/yiiext/activerecord-relation-behavior) - put together the awesomeness of many yii extensions that aim to improve saving of related records.

## CMS (Yii based)

* [Phundament](http://www.phundament.com/) - universal HTML5 Application Boilerplates.
* [Yupe](http://yupe.ru/en) - simple, lite and easy. Uses Yii, Twitter Bootstrap and jQuery.
* [CiiMS](https://github.com/charlesportwoodii/CiiMS) - a high performance CMS blogging platform designed to be easy to use.
* [yiicms](https://github.com/magefad/yiicms) - easy CMS with the basic modules and extensions to start.
* [Craft](http://buildwithcraft.com/) - very slick commercial CMS with a free plan.

## Tools and integrations

* [YiiStorm](http://plugins.jetbrains.com/plugin/?webide&pluginId=7182) - Yii framework integration for PhpStorm.

## Books

* ["Yii Application Development Cookbook"](http://yiicookbook.org/) by Alexander Makarov.
* ["Web Application Development with Yii and PHP"](http://www.packtpub.com/web-application-development-with-yii-and-php-second-edition/book) by Jeffrey Winesett.
* ["The Yii Book"](http://yii.larryullman.com/) by Larry Ulman.
* ["Yii Rapid Application Development Hotshot"](http://www.packtpub.com/yii-rapid-application-development-hotshot/book) by Lauren J. O'Meara, James R. Hamilton III.
* ["Beginning Yii \[Video\]"](http://www.packtpub.com/beginning-yii-php-framework/video) by Chris Backhouse.

---
# Communities

* [http://yiinewsletter.com](http://yiinewsletter.com/) - the best Yii tips, tricks, and tools delivered to your inbox.
* [http://yiiframework.ru](http://yiiframework.ru/) - Russian-speaking community.

