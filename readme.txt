=== Plugin Name ===
Contributors: bizappay
Tags: payment gateway, Malaysia, online banking
Requires at least: 4.3
Tested up to: 4.9
Stable tag: 3.0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Bizappay payment gateway for WooCommerce. 

== Description ==

Bizappay Payment Gateway plugin for WooCommerce. This plugin enable online payment using online banking (for Malaysian banks only). Currently bizappay is only available for businesses that reside in Malaysia.

== Installation ==

1. Make sure that you already have WooCommerce plugin installed and activated.
2. From your Wordpress admin dashboard, go to menu 'Plugins' and 'Add New'.
3. Key in 'Bizappay' in the 'Search Plugins' field and press enter.
4. It will display the plugin and press intall.
5. Activate the plugin through the 'Plugins' screen in WordPress.
6. Go to menu WooCommerce > settings > Payments and fill in your merchant id and secret key. You can retrieve the merchant id and secret key from Bizappay Dashboard at https://www.bizappay.com 
7. Make sure the 'Enable this payment gateway' is ticked. Click on 'Save changes' button.
8. In Bizappay Dashboard make sure you key in your return URL and callback URL as http://your_domain/checkout/ and choose 'Read response and send email if error' for callback response, finally press Save. Please leave the 'Return URL Parameters' field empty.

== Frequently Asked Questions ==

= Do I need to sign up with Bizappay in order to use this plugin? =

Yes, we require info such as merchant id and secret key that is only available after you sign up with Bizappay.

= Can I use this plugin without using WooCommerce? =

No.

= What currency does it support? =

Currently Bizappay only support Malaysian Ringgit (RM).

= What if I have some other question related to Bizappay? =

Please open a ticket by log in to Bizappay Dashboard and look for menu support.

== Changelog ==

= 1.0.0 =
* initial release

