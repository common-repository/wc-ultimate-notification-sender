=== Ultimate Notification Sender for WooCommerce ===
Contributors: masumwp
Tags: Woocommerce Notification, Telegram with Woocommerce, Telegram Bot Notification, Telegram WordPress
Requires at least: 5.8
Tested up to: 6.6
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Receive real-time notifications on Telegram for new orders in your WooCommerce store.

== Description ==

This plugin enables WooCommerce store owners to receive notifications on Telegram for new orders, helping them stay updated on their store activities. The Ultimate Notification Sender for WooCommerce provides a seamless way to integrate your WooCommerce store with Telegram for order notifications.

== Features ==

- Sends real-time notifications to Telegram whenever a new order is placed on your WooCommerce store.
- Sends notifications for various order statuses, including:
  - New Orders
  - Order Processing
  - Order Completed
  - Order Cancelled
  - Order Refunded
- Easy setup process: simply install the plugin, enter your Telegram API token and chat ID, and start receiving notifications.
- Customizable message format to suit your preferences.
- Lightweight and efficient, ensuring minimal impact on your store's performance.
- Modular structure: each notification type is implemented in separate files for easier management and extensibility.

== Installation ==

1. Upload the `unsfw` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Navigate to the plugin settings page (located under the WooCommerce menu in the WordPress dashboard) and enter your Telegram API token and chat ID.
4. Save your settings, and you're all set!

== Frequently Asked Questions ==

= How do I obtain a Telegram API token? =
You can create a bot and obtain the API token by following the instructions provided by Telegram. Visit [Creating a new bot](https://core.telegram.org/bots#creating-a-new-bot) for detailed steps.

= How do I get my Telegram chat ID? =

**Open Telegram:** Launch the Telegram app on your device.  
**Search for the Bot:** In the search bar, type **@RawDataBot**.  
**Start a Chat:** Select the bot from the search results and click on the **Start** button to initiate a conversation.  
**Retrieve Your Chat ID:** The bot will send you a response containing raw data. Look for the **chat** section in the response, where you will find your Telegram chat ID.

== Changelog ==
= 1.0.2 =
* Fixed Bug
= 1.0.1 =
* Added notifications for various WooCommerce order statuses: New Orders, Order Processing, Order Completed, Order Cancelled, and Order Refunded.
* Improved message formatting for clarity and customization.
* Enhanced modular structure for easier maintenance and future feature additions.

= 1.0 =
* Initial release
