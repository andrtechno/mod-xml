mod-xml
===========
Module for xml.xml CORNER CMS

[![Latest Stable Version](https://poser.pugx.org/panix/mod-xml/v/stable)](https://packagist.org/packages/panix/mod-xml) [![Total Downloads](https://poser.pugx.org/panix/mod-xml/downloads)](https://packagist.org/packages/panix/mod-xml) [![Monthly Downloads](https://poser.pugx.org/panix/mod-xml/d/monthly)](https://packagist.org/packages/panix/mod-xml) [![Daily Downloads](https://poser.pugx.org/panix/mod-xml/d/daily)](https://packagist.org/packages/panix/mod-xml) [![Latest Unstable Version](https://poser.pugx.org/panix/mod-xml/v/unstable)](https://packagist.org/packages/panix/mod-xml) [![License](https://poser.pugx.org/panix/mod-xml/license)](https://packagist.org/packages/panix/mod-xml)


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist panix/mod-xml "*"
```

or add

```
"panix/mod-xml": "*"
```

to the require section of your `composer.json` file.

Add to web config.
```
'modules' => [
    'xml' => ['class' => 'panix\mod\xml\Module'],
],
```
