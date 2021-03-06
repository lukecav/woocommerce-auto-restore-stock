=== WooCommerce Auto Restore Stock ===
Contributors: Kloon
Tags: WooCommerce, stock, inventory, restore, cancelled, refunded
Requires at least: 4.6
Tested up to: 4.8.2
Stable tag: 1.0.1
License: MIT
License URI: https://opensource.org/licenses/MIT

Automatically restore your WooCommerce inventory/stock for orders that was cancelled or refunded.

== Description ==

WooCommerce Auto Restore Stock will automatically restore your WooCommerce inventory/stock for orders that was placed and refunded or cancelled.

The inventory/stock restore is triggered when the order goes from on-hold, processing, completed to either cancelled or refunded status.

When WooCommerce Auto Restore Stock restores the inventory/stock it will also add order notes to the order in question to show the adjusted values and to indicate that inventory/stock was restored.

== Installation ==

1. Upload `woocommerce-auto-stock-restore` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Cancel or Refund a completed, processing or on-hold order to make the inventory/stock restore.

== Changelog ==

= 1.0.1 =
* Added woocommerce_auto_stock_restored action

= 1.0.0 =
* First release
