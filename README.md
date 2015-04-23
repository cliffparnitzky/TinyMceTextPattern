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

- min. Contao version: >= 3.3.0
- max. Contao version: <  3.5.0


Dependency
----------

- To load this plugin and add it to the configuration the extension [[TinyMcePluginLoader]](https://github.com/cliffparnitzky/TinyMcePluginLoader) has to be installed.


Screenshot
----------

![Screenshot](screenshot.jpg)


Available patterns
------------------

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