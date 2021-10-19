<p align="center">
E-COMMERCE LARAVEL VUE JS
</p>



## Topics
1. [Introduction](#introduction)
2. [Documentation](#documentation)
3. [Requirements](#requirements)
4. [Installation & Configuration](#installation-and-configuration)
5. [License](#license)
6. [Security Vulnerabilities](#security-vulnerabilities)
7. [Modules](#modules)
8. [Miscellaneous](#miscellaneous)

### Introduction

It packs in lots of features that will allow your E-Commerce business to scale in no time:

* Multiple Channels, Locale, Currencies.
* Built-in Access Control Layer.
* Beautiful and Responsive Storefront.
* Descriptive and Simple Admin Panel.
* Admin Dashboard.
* Custom Attributes.
* Built on Modular Approach.
* Support for Multiple Store Themes.
* Multistore Inventory System.
* Orders Management System.
* Customer Cart, Wishlist, Product Reviews.
* Simple, Configurable, Group, Bundle, Downloadable and Virtual Products.
* Price rules (Discount) inbuilt.
* Theme (Velocity).
* CMS Pages.
* Check out [these features and more](https://bagisto.com/features/).

**For Developers**:
Take advantage of two of the hottest frameworks used in this project -- Laravel and Vue.js -- both of which have been used in Bagisto.

### Documentation



### Requirements

* **SERVER**: Apache 2 or NGINX.
* **RAM**: 3 GB or higher.
* **PHP**: 7.3 or higher.
* **For MySQL users**: 5.7.23 or higher.
* **For MariaDB users**: 10.2.7 or Higher.
* **Node**: 8.11.3 LTS or higher.
* **Composer**: 1.6.5 or higher.

### Installation and Configuration

**1. You can install Bagisto by using the GUI installer.**

##### a. Download zip from the link below:

[Download the latest release](https://github.com/bagisto/bagisto/releases/latest)

##### b. Extract the contents of zip and execute the project in your browser:

~~~
http(s)://example.com
~~~

**2. Or you can install Bagisto from your console.**

##### Execute these commands below, in order

~~~
1. composer create-project bagisto/bagisto
~~~

~~~
2. php artisan bagisto:install
~~~

**To execute Bagisto**:

##### On server:

Warning: Before going into production mode we recommend you uninstall developer dependencies.
In order to do that, run the command below:

> composer install --no-dev

~~~
Open the specified entry point in your hosts file in your browser or make an entry in hosts file if not done.
~~~

##### On local:

~~~
php artisan serve
~~~


**How to log in as admin:**

> *http(s)://example.com/admin/login*

~~~
email:admin@example.com
password:admin123
~~~

**How to log in as customer:**

*You can directly register as customer and then login.*

> *http(s)://example.com/customer/register*

