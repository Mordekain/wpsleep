=== wpSleep ===
Contributors: stalkerX
Tags: Post, page, posts, ad, admin, ads, custom, date, events, time, control, snippet
Requires at least: 2.5
Tested up to: 3.1
Stable tag: trunk

wpSleep puts text parts delayed offline.


== Description ==
*wpSleep* allows you to create posts in advance have them automatically publish when you'd like. You can then set when different parts of a post are viewable.


= Features =
* No database necessary
* Fast carrying out, as there is only a modicom of code
* No admin panel required - time specification are directly within the post


= Mode of operation =
Add the short code `&#91;wpsleep&#93;` to the desired location in your post.


= Examples =
* `&#91;wpsleep start="31.12.2010 09:00"&#93;`This section is now offline, but from 31.12.2010 9 am for everyone viewable`&#91;/wpsleep&#93;`
* `&#91;wpsleep start="07.10.2010 09:00" end="08.10.2010" alt="Alt text"&#93;`This section is only for a few hours viewable, the rest of the time you see the alternative text`&#91;/wpsleep&#93;`


= Documentation =
* [Plugin documentation in german](http://playground.ebiene.de/316/wpsleep-wordpress-plugin-zeitliche-steuerung-der-bestandteile-eines-artikels/ "wpSleep")
* [Plugin documentation in english](http://playground.ebiene.de/498/wordpress-plugin-wpsleep-time-control-for-parts-of-a-post/ "wpSleep")
* [Follow us on Twitter for updates](http://twitter.com/wpSEO "wpSEO on Twitter")
* [Other author plugins](http://wordpress.org/extend/plugins/profile/stalkerx "Other author plugins")
* [Author page](http://ebiene.de "Author page")


== Changelog ==
= 0.6 =
* Timezone support
* German translation

= 0.5 =
* The *visible* flag is set, if the hidden part is visible. You can use this variable in your template.

= 0.4 =
* Support for alternative text

= 0.3 =
* Attributes for start- and end timing can now be specified as time of day only, which offers daily repeat

= 0.2 =
* Start date is no manditory field anymore. Start and enddate can be specified at will

= 0.1 =
* *wpSleep* goes online


== Installation ==
1. Download *wpSleep* plugin
1. Unzip the archive
1. Upload the folder *wpsleep* into *../wp-content/plugins/*
1. Go to tab *Plugins*
1. Activate *wpSleep*
1. Please use your formatted plugin shortcode
1. Ready