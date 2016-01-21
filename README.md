# m2-foggyline-slider

### Installation

```sh
$ composer config repositories.koncz-m2-foggyline-slider git https://github.com/ksz2013/m2-foggyline-slider.git
$ composer require koncz/m2-foggyline-slider:dev-master
```

Manually:

Copy the zip into app/code/Foggyline/Slider directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable Foggyline_Slider --clear-static-content
$ php bin/magento setup:upgrade
```