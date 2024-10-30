=== Config Interface ===
Author URI: http://iehsan.ir
Contributors: iEhsan.ir
Tags: wp-config.php, wp-config, config wordpress, how to config wordpress, ehsaan, wordpress editor
Requires at least: 4.0
Tested up to: 4.3
Stable Tag: 1.1
License: GNU Version 2 or Any Later Version

Edit your WordPress basic configuration with style

== Description ==

Config Interface is an user interface for editing WP-Config.php with style, utilities fields and graphical interface to edit that file safe.

Features of plugin include:

* Graphical interface for editing
* Short description and suggestion for each field
* Compatible with WordPress network
* Restore the backup after saving file
* Regenerate salt nonces through WordPress official API

**Follow this plugin on [GitHub](https://github.com/EhsaanF/wp-config-interface)**

**Want to report a bug, suggest something, or see an option is missing? Raise an issue on [GitHub issue tracker](https://github.com/EhsaanF/wp-config-interface/issues)**

**Languages**

1. English
2. Persian

Would you like to help translate the plugin into more languages? [Here is how!](https://github.com/EhsaanF/wp-config-interface#translations)

== Installation ==

1. Activate the plugin
2. Go to Settings > Edit wp-config.php
3. Apply every configuration you want!

== Frequently Asked Questions ==

= How secure is this plugin? =

I tried to patch every possible bug to block foreign and unauthorized requests to edit the file. This plugin reviewed by security experts.
But if you downloaded this plugin from somewhere else than WordPress.org, there is a danger about your salt nonces or your WordPress get controlled
by unauthorized users.

= It corrupted my site! How can I fix it back? =

If plugin edited wp-config.php in wrong way, there is a chance to fix your site. Config Interface never edits your wp-config.php without creating a backup.

This backup is available at your WordPress installation directory as `wp-config.backup.php`. You can use this file to return your latest wp-config.php.

= No changes applied, but it says wp-config.php updated. =

This problem has several reasons. One of them is your PHP Version. The plugin needs PHP >= 5.4 for working perfectly.

== Screenshots ==

1. General tab
2. If wp-config.php won't be writable, plugin will give you new wp-config.php for applying by yourself.
3. Security tab
4. Misc tab

== Changelog ==
= 1.1, 25 September, 2015 =
* New: `SUBDOMAIN_INSTALL` option
* New: Tables prefix option
* Fixed: Some strings didn't have text domain.
* Tweak: Squished a bug when multisite is enabled and options won't save.

= 1.0, 1 September, 2015 =
* Initial release