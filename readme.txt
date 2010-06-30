=== Plugin Name ===
Tags: plugins, multisite, 3.0, wpmu, network, super admin,
Contributors: itx
Donate link: http://itx.web.id/donate/
Requires at least: 3.0
Tested up to: 3.0
Stable tag: trunk

Exclude plugins from appearing in plugins menu for normal user in WordPress multisite.

== Description ==

WordPress 3.0 multisite allow us only to show or hide all of the plugins from normal user, 
nothing else. If we want to allow all users to use some simple plugins, while hiding the 
'super' plugins only for Super Admins or VIP users, we have to activate the plugin for all
network in order to make it work. Or else, we have to make them visible by all.

This is why we need Exclude Plugins. Exclude Plugins will exclude plugins from appearing
in plugins menu for normal user in WordPress multisite. This way, some plugins (excluded
plugins) will be available only for Super Admins, while other plugins (included plugins)
will be available for normal user.

If you're **not** using [network mode](http://codex.wordpress.org/Create_A_Network) in WordPress 3.0, you definitely *don't* need this plugin.

For questions and bug report, please visit [Exclude Plugins page](http://itx.web.id/wordpress/plugins/exclude-plugins/).

== Installation ==

You can use the built in installer and upgrader, or you can install the plugin manually:
1. Download the plugin
2. Upload and extract the contents of exclude-plugins.zip to wp-content/plugins/ folder. You should get a folder called exclude-plugins.
3. Activate the Plugin in WP-Admin.
4. Goto Super Admin > Options > Menu Settings then enable administration menus for plugins.
5. Goto Plugins > Exclude Plugins to configure.

== Screenshots ==

1. Exclude Plugins admin interface.

== Frequently Asked Questions ==

For questions and bug report, please visit [Exclude Plugins page](http://itx.web.id/wordpress/plugins/exclude-plugins/).

== Changelog ==

= 1.1 =
* First Public Release
