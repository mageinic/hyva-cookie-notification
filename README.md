# Hyvä Cookie Notification

**Hyvä Cookie Notification is a part of MageINIC Cookie Notification extension that adds Hyvä features.** This extension extends Cookie Notification definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-cookie-notification

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Cookie Notification requires installing [MageINIC Cookie Notification](https://github.com/mageinic/cookie-notification) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/cookie-notification
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
