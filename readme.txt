=== Mandrill for bbPress subscriptions ===
Contributors: tareq1988
Donate Link: http://tareq.wedevs.com/donate/
Tags: bbpress, notification, reply, email, email-reply
Requires at least: 3.3
Tested up to: 5.4
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Send bbPress replies via Mandrill inbound mail

== Description ==

Send bbPress replies via Mandrill inbound mail. This is an add-on for [bbPress Subscription](https://github.com/rmccue/bbPress-Reply-by-Email) plugin by [Ryan McCue](https://github.com/rmccue)


= Usage =

1. Firstly install bbPress [bbPress Subscriptions](https://github.com/rmccue/bbPress-Reply-by-Email) plugin
2. Install this plugin.
3. Set `Mandrill` as `Messaging Handler` in plugin option
4. Set your `Reply-to Address`. e.g. `reply+%1$d-%2$s@yourdomain.com`
5. Based on the *Reply-to* address, set your **Route** in [Mandrill App inbound dashboard](https://mandrillapp.com/inbound).
6. Using this example address here, the route would be `reply+*@inbound.yourdomain.com*` *(set your domain mx record first)*
7. Set the webhook to `http://example.com/wp-admin/admin-post.php?action=bbsub`
8. You are set to go!

= Contribute =
This may have bugs and lack of many features. If you want to contribute on this project, you are more than welcome. Please fork the repository from [Github](https://github.com/tareq1988/bbpress-reply-by-email-mandrill).

= Author =
Brought to you by [Tareq Hasan](http://tareq.wedevs.com) from [weDevs](http://wedevs.com)

= Donate =
Please [donate](http://tareq.wedevs.com/donate/) for this awesome plugin to continue it's development to bring more awesome features.


== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Frequently Asked Questions ==

Nothing here yet


== Changelog ==

= 0.1 =
Initial version released


== Upgrade Notice ==

Nothing here
