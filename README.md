# magento2-weltpixel-mobiledetect

### Installation

With composer:

```sh
$ composer config repositories.weltpixel-magento2-weltpixel-mobiledetect git https://github.com/Weltpixel/magento2-weltpixel-mobiledetect.git
$ composer require weltpixel/magento2-weltpixel-mobiledetect:dev-master
```

Manually:

Copy the zip into the app/code/WeltPixel/MobileDetect directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable WeltPixel_MobileDetect --clear-static-content
$ php bin/magento setup:upgrade
```
