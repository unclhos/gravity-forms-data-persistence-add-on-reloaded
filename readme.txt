=== Gravity Forms Data Persistence Add-On Reloaded===
Contributors: unclhos
Tags: gravity, form, data, field, persistence, add-on, addon, plugin, plug-in, extension
Requires at least: 2.9.2
Tested up to: 3.9.1
Stable tag: 3.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin makes your Gravity Forms data-persistent.

== Description ==

Consider this scenario:

a) Your site uses multipage <a href="http://www.gravityforms.com/" target="_blank">Gravity Forms</a>.
b) Your user logs in to the site and starts filling up a 5-step form.
c) During the 3rd step, the user leaves without completely finishing the form.
d) Some days later, the user comes back and logs in to see that his inputs are all gone!

This happens because Gravity Forms by default does not save partially submitted forms.

Our plugin resolves this issue. Simple!

== Installation ==


<h4>Installation</h4>

1. Upload extracted folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Do I need to pay for this plugin as we do for Gravity Forms? =

No, this is an absolutely free add-on.

= Do you have any client support? =

We don't provide a dedicated support, but we will try our best to reply you back.

== Changelog ==

= 3.1 =
1. Updated hook for javascript to work where form settings were moved to.
2. Added an option to clear persistence for a user after they have submitted the form.
3. Prepended functions names per wordpress.org's request to avoid conflicts with other plugins.
4. Removed sql delete query in favor of using GF's class method.

= 3.0 =
Copy of orginal plugin by asthait