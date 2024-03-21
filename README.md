# Magento 2 Cookie Banner

This Magento 2 module integrates a consent cookiebanner and lets Tag Manager know what the selected options are.
This module uses the [Yireo Google Tag manager module](https://github.com/yireo/Yireo_GoogleTagManager2)

## Installation
- `composer require starringjane/cookie-banner`
- `bin/magento module:enable StarringJane_CookieBanner`
- `bin/magento setup:upgrade`

## Configuration
1. Enable the Yireo tag manager module
2. `bin/magento config:set --lock-config web/cookie/cookie_restriction	1`
3. `bin/magento cache:clean`

## License
[MIT](LICENSE)

---
