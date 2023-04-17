# Magento 2 Module MgtWizards FreeShippingNotification

    ``mgtwizards/module-freeshippingnotification``

-   [Main Functionalities](#markdown-header-main-functionalities)
-   [Installation](#markdown-header-installation)
-   [Configuration](#markdown-header-configuration)
-   [Specifications](#markdown-header-specifications)

## Main Functionalities

Magento 2 module to display the remaining amount to get free shipping, at cart page.

Module available to download here: https://mgt-wizards.com/free-shipping-notification-for-magento-2

![alt text](https://github.com/mgtwizards/m2-freeshippingnotification/blob/main/preview.jpeg?raw=true)

## Installation

\* = in production please use the `--keep-generated` option

### Type 1: Zip file

-   Unzip the zip file in `app/code/MgtWizards/FreeShippingNotification`
-   Enable the module by running `php bin/magento module:enable MgtWizards_FreeShippingNotification`
-   Apply database updates by running `php bin/magento setup:upgrade`\*
-   Flush the cache by running `php bin/magento cache:flush`

## Configuration

Once installed, check settings at Stores/Configuration/MgtWizards section.
