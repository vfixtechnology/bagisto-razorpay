# Nexus Theme for Bagisto by Vfix Technology

A premium, high-performance theme for Bagisto e-commerce platform with modern design and seamless integration.
## Installation

1. Install the package via Composer:

```php
composer require vfixtechnology/bagisto-nexus-theme
```

2. Register the Nexus theme to service provider in Bootstrap/providers.php:
 ```php
  Vfixtechnology\NexusTheme\Providers\NexusThemeServiceProvider::class,
 ```
The theme will automatically:

Install required npm dependencies

Build frontend assets

Register itself in Bagisto's theme system

3. Activate the theme in Admin Panel:
Go to Configure/Payment Methods
Configure → Themes → Shop Themes → Select "Nexus"

4. Clear caches (recommended):
 ```php
php artisan optimize:clear
 ```


## Support This Project

If you find this package useful, please consider showing your support by:

⭐ Giving the repository a star on GitHub  
📣 Sharing it with your developer community  
🐛 Reporting any issues you encounter  

Your support helps maintain and improve this project for everyone.

#### For any help or customization, visit https://www.vfixtechnology.com or email us info@vfixtechnology.com
