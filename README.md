# [Foundation](http://foundation.zurb.com)

Foundation is the most advanced responsive front-end framework in the world. You can quickly prototype and build sites or apps that work on any kind of device with Foundation, which includes layout constructs (like a fully responsive grid), elements and best practices.

To get started, check out <http://foundation.zurb.com/docs>


## Quickstart

To get going with Foundation you can:

  * [Download the latest release](http://foundation.zurb.com/releases/latest.zip)
  * [Install with Bower](http://bower.io): `bower install foundation`

## What's included?

```
foundation/
├── css/
│   ├── foundation.css
│   ├── foundation.min.css
├── js/
│   ├── foundation.js
│   └── foundation.min.js
└── index.html
```

## Documentation

Foundation uses [Assemble.io](http://assemble.io) and [Grunt](http://gruntjs.com/) to generate it's [documentation pages](http://foundation.zurb.com/docs). Documentation can also be run from your local computer:

<<<<<<< HEAD
WordPress (Versions marked 3/20/13)

* [WP-Forge](http://themeawesome.com/responsive-wordpress-theme/) by Thomas E. Vasquez using Foundation 4.3.1
* [NARGA](http://www.narga.net/narga-core/) by Nguyễn Đình Quân using Foundation version 4
* [Reactor](https://github.com/awtheme/reactor) by Anthony Wilhelm using Foundation version 4
* [Reverie](http://themefortress.com/reverie/) by Zhen using Foundation version 4
* [Corner Stone](https://github.com/thewirelessguy/cornerstone) by [Stephen Mullen](https://twitter.com/wirelessguyuk) using Foundation version v4.09
* [required+ Themes](http://themes.required.ch/) by required+ using Foundation version 3.25
* [Yeti](https://github.com/modlearning/Yeti) by Modular Learning using Foundation version 3.2
* [Starter Theme](https://github.com/drewsymo/Foundation) by Drew Morris using Foundation version 3
* [WP-Foundation](http://320press.com/wp-foundation/features/) by 320press using Foundation version 3
* [f415](https://github.com/javorszky/f415) by Gabor Javorszky
* [Basey](https://github.com/zslabs/basey-theme) by Zach Schnackel 
=======
### View documentation locally
>>>>>>> refs/remotes/origin/5.0-wip

You'll want to clone the Foundation repo first and install all the dependencies. You can do this using the following commands:

```
git clone git@github.com:zurb/foundation.git
cd foundation
npm install -g grunt-cli
npm install
```

Then just run `grunt` and the documentation will be compiled:

```
foundation/
├── dist/
│   └── ...
├────── docs/
│       └── ...
```

<<<<<<< HEAD
Alfred

* [Foundation Alfred](https://github.com/joshmedeski/foundation-alfred) by Josh Medeski (@joshmedeski)

Jekyll

* [Foundation 4 SASS](https://github.com/rememberlenny/Jekyll-Foundation-SASS) by [Leonard Bogdonoff](http://twitter.com/rememberlenny)
* [Foundation 3 CSS](https://github.com/groovemonkey/jekyll-foundation-base) by [Dave Cohen](https://github.com/groovemonkey)

PyroCMS

* [PyroYeti - PyroCMS Theme](https://github.com/pyrosuit/PyroYeti) by [Arnold Mwumva Ford](https://twitter.com/fordarnold) , Meridian Softech

Django

* [A foundation theme for the Pinax](http://pypi.python.org/pypi/pinax-theme-foundation) by Christopher Clarke, Kwesi Aguillera & Lendl Smith

MODX

* [Flexibility Theme](http://flexibilitymodx.com/) by Menno Pietersen

.NET

* [NuGet Package for ASP.Net MVC](http://www.nuget.org/packages/Foundation3_MVC4) by Edward Charbeneau, @EdCharbeneau
* [Kartris E-commerce](http://www.kartris.com/) by Cactusoft Ltd.

Middleman

* [Middleman Skeleton](https://github.com/axyz/middleman-zurb-foundation) by [Andrea Moretti](https://twitter.com/axyz)
* [Middleman Foundation 4.x Template](https://github.com/mattolson/middleman-zurb-template) by [Matt Olson](http://mattolson.com)

Magento

* [Magento & Foundation](https://github.com/nandroid/MagentoFoundation) by Nandroid
* [Waterlee Boilerplate](https://github.com/zeljkoprsa/waterlee-boilerplate) by Jake Sharp

Meteor

* [Meteor Package for Foundation](https://atmosphere.meteor.com/package/foundation) by Eric Wallace
* [Foundation Smart Package](https://atmosphere.meteor.com/package/zurb-foundation)

Python

* [Pyramid Scaffold](https://github.com/ppinette/pyramid_foundation) by Parker Pinette

CodeIgniter

* [Responsive CodeIgniter BoilerPlate](https://github.com/meridiansoftech/meridian_ci_codebase) by [Arnold Mwumva Ford](https://twitter.com/fordarnold) , Meridian Softech

Shopify

* [Foundationify Shopify Theme](https://github.com/lukebussey/foundationify) by Luke Bussey

SilverStripe

* [Foundation Silverstripe Theme](https://github.com/ryanwachtl/silverstripe-foundation) by [Ryan Wachtl](https://github.com/ryanwachtl)

Orchard

  * [Foundation Theme for Orchard CMS](https://foundationorchardcms.codeplex.com/)

Other Implementations

* [Mobile First](https://github.com/adamfairhead/mobile-first-foundation) by Adam Fairhead
* [Less Version](https://github.com/justinmarsan/FoundationLess) by Justin Marsan
* [Less with Color Scheme](https://github.com/matalin/FoundationLess) by Matalin Hatchard

Editors

* [Textmate/Sublime Text2 Bundle](https://github.com/liamr/Zurb-Foundation-Textmate-Bundle) by Liam R, @liamr

Templates

* [Desktop, Tablet and Phone Grid PSD Templates](http://foundation.zurb.com/files/foundation-psd-templates.zip ) by Bruce Abel at Portfolio Creative Services Group
* [HAML Web Templates](https://github.com/pbonnell/foundation_templates_haml) by Peter Bonnell

Rapid Prototyping

* [ditbi](https://github.com/roblevintennis/ditbi) by Rob Levin [4 Minute Demo Video](http://www.youtube.com/watch?v=ERgFCJFpq5E)
* [Serve Foundation - Rapid Prototyping with Serve](https://github.com/bomberstudios/serve-foundation)

Grid Generator

* [Experimental Grid Generator](http://www.gridlover.net/foundation/) courtesy of [Ville Vanninen](http://foolproof.me)

Grid Displayer

* [Grid displayer bookmarklet](http://alefeuvre.github.com/foundation-grid-displayer/) by [Antoine Lefeuvre](http://twitter.com/jiraisurfer)
* [Responsive Design Bookmarklet](http://responsive.victorcoulon.fr/) by [Victor Coulon](https://twitter.com/_victa)
* [Vertical Rhythm Grid Bookmarklet](http://gridwax.gs/) by [Kevin Altman](http://twitter.com/itg)

Modular Scale

* [Modular Scale](https://github.com/scottkellum/modular-scale) by Mason Wendell and Scott Kellum

Ruby on Rails Sass Gems

* [Foundation Icons 2](https://github.com/zaiste/foundation-icons-sass-rails) by J. P. Nowak

Yeoman Generator

* [Yeoman 1.0-Foundation 4](https://github.com/lkbgift/foundation4-yeoman) by [Leonard Bogdonoff](http://twitter.com/lkbcc)
* [Yeoman-Foundation](https://npmjs.org/package/yeoman-foundation) by Vincent Mac
* [Generator-Foundation-Ext](https://github.com/jamesakers/generator-foundation-ext) by James Akers

Gökhan Karaca

* 2013-11-17 - Marge to master

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
=======
Copyright (c) 2013 ZURB, inc.
>>>>>>> refs/remotes/origin/5.0-wip
