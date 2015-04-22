QcmStandardEdition
===========================

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/avoo/qcm-standard/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/avoo/qcm-standard/?branch=master)
[![Build Status]
(https://scrutinizer-ci.com/g/avoo/qcm-standard/badges/build.png?b=master)](https://scrutinizer-ci.com/g/avoo/qcm-standard/build-status/master)
[![Latest Stable Version](https://poser.pugx.org/avoo/qcm-standard-edition/v/stable)](https://packagist.org/packages/avoo/qcm-standard-edition)
[![License](https://poser.pugx.org/avoo/qcm-standard-edition/license)](https://packagist.org/packages/avoo/qcm-standard-edition)

This is a full fonctionnal QCM application based on Symfony 2 and Sylius

Installation with composer
--------------------------

Use:

``` shell
composer create-project avoo/qcm-standard-edition path/
```

In yout project repertory `cd path/` run the installer

``` shell
php app/console qcm:install
```

and follow the instructions.


Documentation
-------------

This application integrates:
* [QcmCoreBundle](https://github.com/avoo/QcmCoreBundle) based on [SyliusResourceBundle](https://github.com/Sylius/SyliusResourceBundle).
* [QcmAdminBundle](https://github.com/avoo/QcmAdminBundle) is a basic administration sample.
* [QcmPublicBundle](https://github.com/avoo/QcmPublicBundle) is a basic client sample.


Credits
-------

* Jérémy Jégou <jejeavo@gmail.com>


License
-------

This bundle is released under the MIT license. See the complete license in the bundle:

[License](https://github.com/avoo/qcm-standard/blob/master/LICENSE)
