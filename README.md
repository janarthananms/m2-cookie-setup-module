Adzapier Cookie Consent Magento 2 Extension
=====================
Magento 2 Extension for the [Adzapier Cookie Consent Javascript plugin](https://www.Adzapier.com/cookieconsent).

Facts
-----
- version: 1.0.0
- [Extension on GitHub](https://github.com/janarthananms/m2-cookie-setup-module)
- [Download Latest](https://github.com/janarthananms/m2-cookie-setup-module/archive/master.zip)

Description
-----------
The Adzapier Cookie Consent Magento 2 Extension provides a quick and easy way to add a cookie consent popup powered by Adzapier's Cookie Consent javascript plugin. 

Requirements
------------

Compatibility
-------------
- Magento >= 2.1

Composer Installation Instructions
-------------------------

1. Add the extension via composer

    `composer require adzapier/m2-cookie-setup-module`

2. Run Composer Update

    `composer update adzapier/m2-cookie-setup-module`

3. Enable the module

    `bin/magento module:enable Adzapier_Cookiesetup`

4. Run upgrade and flush caches

    * `bin/magento setup:upgrade`
    
    * `bin/magento cache:flush`

Customization 
--------------
You can configure the cookie consent pop up within the magento admin at Admin -> Store -> Adzapier GDPR CCPA -> Adzapier GDPR CCPA compliance

Supported Customization Options
-------------
1. Enable : **Yes/No**
2. Insert JS Code : **Insert the copied script from Adzapier Portal here and save it to publish the cookie banner on your website**

Support
-------
If you have any issues with this extension, open an issue on [GitHub]([https://github.com/janarthananms/m2-cookie-setup-module/issues]).

Contribution
------------
Any contribution is highly appreciated. The best way to contribute code is to open a [pull request on GitHub](https://github.com/janarthananms/m2-cookie-setup-module/pulls).



Licence
-------
[MIT License](https://github.com/janarthananms/m2-cookie-setup-module/blob/master/LICENSE)

Copyright
---------
(c) 2022 Adzapier
