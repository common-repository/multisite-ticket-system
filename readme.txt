===  Multisite Ticket System ===
Contributors: merleM_157
Tags: multisite, multisite network, ticketsystem, ticketsupport, ticket, tickets, support, network admin, super admin
Requires at least: 4.4
Tested up to: 4.8.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Ticket support system for multisite network.

== Description ==

Multisite Ticket System is a plugin for WordPress Multisite Network. Super Admin receives tickets and manages settings (categories and e-mail addresses). Administrators of the sites (only) can submit tickets. The plugin also provides comment sections for updating tickets.

There are a lot of WordPress Ticket System plugins out there, but rarely ones (or none) that are intended for improved communication between Super Admin and Site Administrators in a Multisite Network. 
This is all the more convenient if your organization manages many regional groups throughout the country or in general manages many sites that are administered by different people with diverse kinds of WordPress knowledge, especially by people with zero knowledge of WordPress. In these cases, the Super Admin is able to help more efficiently through this ticket system, e.g. instead of managing requests via e-mail.
It means in effect that the ticket system is used in the backend (Dashboard) and doesn't provide e.g. contact forms in the frontend (actual website / blog) for visitors. That what makes it rather interesting - a plugin for improved support in multisite networks.

The plugin has been developed in German, but English translation files are provided (US, GB, AU).

Since there has been quite a few changes in WordPress itself, the plugin has been tested now in WP version 4.4, 4.4.2, and 4.8.2, but of course it is possible that it works in older versions as well. Test / Use at your own risk! (And maybe contact me, too, I am happy to make this plugin compatible for as many versions as possible.)

== Installation ==

Note: This plugin is intended for multisite networks and won't activate in single WP installations. It wouldn't be of much use otherwise anyway.
However, if you're fascinated by this plugin and wish to use it in a single WP installation, feel free to contact me.

1. Upload the plugin files to the '/wp-content/plugins/plugin-name' directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Enjoy the extended support feature!


== Screenshots ==

1. Tickets overview in Network Admin

2. Settings overview in Network Admin

3. Tickets overview in Site Admin

4. Create a ticket in Site Admin

5. View a selected ticket

6. View the comment section

== Changelog ==

= 1.0 =
* Deprecated function get_currentuserinfo swapped for wp_get_current_user()
* Added language files for en_AU (Australia)

= 0.5 =
* This is the first version ever, so no changes have been made so far. But I am eager to improve this plugin and optimize its features!


