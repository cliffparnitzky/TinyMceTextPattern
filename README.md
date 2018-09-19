[![Latest Version on Packagist](http://img.shields.io/packagist/v/cliffparnitzky/tiny-mce-text-pattern.svg?style=flat)](https://packagist.org/packages/cliffparnitzky/tiny-mce-text-pattern)
[![Installations via composer per month](http://img.shields.io/packagist/dm/cliffparnitzky/tiny-mce-text-pattern.svg?style=flat)](https://packagist.org/packages/cliffparnitzky/tiny-mce-text-pattern)
[![Installations via composer total](http://img.shields.io/packagist/dt/cliffparnitzky/tiny-mce-text-pattern.svg?style=flat)](https://packagist.org/packages/cliffparnitzky/tiny-mce-text-pattern)

Contao Extension: TinyMceTextPattern
====================================

Special TinyMCE plugin that matches special patterns in the text and applies formats or executed commands on these text patterns.

The sources of this plugin could be found [here](http://www.tinymce.com/wiki.php/Plugin:textpattern).


Installation
------------

Install the extension via composer: [cliffparnitzky/tiny-mce-text-pattern](https://packagist.org/packages/cliffparnitzky/tiny-mce-text-pattern).

If you prefer to install it manually, download the latest release here: https://github.com/cliffparnitzky/TinyMceTextPattern/releases


Tracker
-------

https://github.com/cliffparnitzky/TinyMceTextPattern/issues


Compatibility
-------------

- Contao version >= 4.4.0


Dependency
----------

- To load this plugin and add it to the configuration the extension [[TinyMcePluginLoader]](https://github.com/cliffparnitzky/TinyMcePluginLoader) has to be installed.


Screenshot
----------

![Screenshot](screenshot.jpg)


Additional information
----------------------

### Special notes

There is nothing special to pay attention to.

### Available patterns

- `*text*` ... format text **italic**
- `**text**` ... format text **bold**
- `# text` ... format text as **h1**
- `## text` ... format text as **h2**
- `### text` ... format text as **h3**
- `#### text` ... format text as **h4**
- `##### text` ... format text as **h5**
- `###### text` ... format text as **h6**
- `1. text` ... start creating an **ordered list**
- `* text` ... start creating an **unordered list**
- `- text` ... start creating an **unordered list**

### Information in the wiki

#### Create a new ...

* [Creating a new plugin](https://github.com/cliffparnitzky/TinyMcePluginLoader/wiki/Creating-a-new-plugin)
* [Creating a new bundle](https://github.com/cliffparnitzky/TinyMcePluginLoader/wiki/Creating-a-new-bundle)
* [Creating a new setup](https://github.com/cliffparnitzky/TinyMcePluginLoader/wiki/Creating-a-new-setup)

#### Installation hints
* [Install manually](https://github.com/cliffparnitzky/TinyMcePluginLoader/wiki/Install-manually)

#### Bug report hints

* [Report a bug](https://github.com/cliffparnitzky/TinyMcePluginLoader/wiki/Report-a-bug)