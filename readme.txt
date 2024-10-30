=== LDAP-Integration ===
Contributors: Alex1602
Donate link: 
Tags: ldap, authentication, login, active directory, adLDAP
Requires at least: 3.3
Tested up to: 3.5.1
Stable tag: stable
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Having a single login is a must in large organizations. This plugin allows you to integrate WordPress with LDAP for each site.

== Description ==

Having a single login for every service is a must in large organizations. This plugin allows you to integrate WordPress with LDAP for each individual site. You can create different base dn's for every site and still have only one list of users.

First of all this plugin is based upon the [simple LDAP Login](http://wordpress.org/plugins/simple-ldap-login/installation/) I made some changes which I think are handy.

When you want to manage multiple single wordpress installations, password management becomes crucial. When someone's password has been cracked you would have to change it everywhere wouldn't it be simpler to just edit it on one place.

= Feature request =

Do you have an idea to make this plugin better, please let me know leave a message here or email me alex[at]alex-dekker.nl.

= Donate? =
If you want to donate please email me.

== Installation ==

1. Upload `ldap-integration` folder to the `/wp-content/plugins/` directory
1. Or upload the zip file to your wordpress plugin section
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently asked questions ==

= Other than Wordpress, what does my system require? =

1. PHP 5
2. A LDAP server like openldap or active directory 
3. PHP must be configured/compiled with ldap support! 

= How do I know what the correct settings are? =

I have tried to make the settings as self-explanatory as possible. If you are struggling figuring them out, you may need to speak with your LDAP administrator. I realize this is an obnoxious response, but there is no good, fail proof way to help you discover these settings. A good place to start, if you're feeling daring, might be to use ADSIEdit for Windows and Active Directory, or GQ for Linux and OpenLDAP.

= It's still not working, what other things can I try? =

If you are confident your settings are correct and it still does not work, it may be time to check for port or firewall issues. If your LDAP server is running on a non-standard port or an obsolete version of the LDAP protocol you are going to have issues. Port 389 is the port this plugin, and nearly every other LDAP enabled software expects. They are also expecting protocol version 3. If you are using an old version of LDAP or running a non-standard port you may need to modify the code that the plugin runs or update your LDAP installation.

Unfortunately I can't be relied upon to assist with these types of requests. I chose not to support these scenarios because they are infrequent and because they confuse everyone else.

= It's still not working! How can I get help? = 
There are two ways. You can post a comment on my blog (http://alex-dekker.nl/) or you can e-mail me: alex[at]alex-dekker.nl. I'll do my best to get you up and running!

== Screenshots ==

1. 
2. 

== Changelog ==

= Version 1.0 =

* Original release.

== Upgrade notice ==

New features will be added in time.