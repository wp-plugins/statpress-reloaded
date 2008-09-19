=== Plugin Name ===
Contributors: matrixagent, danielelippi
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=paypal%40matrixagents%2eorg&item_name=Dodge%20this%21&no_shipping=1&no_note=1&tax=0&currency_code=EUR&lc=DE&bn=PP%2dDonationsBF&charset=UTF%2d8
Tags: stats, statistics, widget, admin, sidebar, visits, visitors, pageview, referrer, spy
Requires at least: 2.0.2
Tested up to: 2.6.2
Stable Tag: 1.4.4

This plugin shows you real time statistics about your blog. It collects information about visitors, spiders, search keywords, feeds, browsers, OS etc.


== Description ==

This plugin (previously known as StatPress) shows you real time statistics about your blog. It collects information about visitors, spiders, search keywords, feeds, browsers, OS etc.

Once the plugin StatPress has been activated it immediately starts to collect information.
Using StatPress you can see your visitors actions while they are surfing your blog or check which are the preferred pages, posts and categories.
In the Dashboard menu you will find the StatPress page where you could look up the statistics (overview or detailed).
StatPress also includes a widget you can add to a sidebar (or easy PHP code if you can't use widgets!).

= Multilanguage =
StatPress speaks English, Italian, Spanish, French, German, Russian, Norwegian, Dutch, Brazilian, Turkish, Swedish!
Could you translate StatPress in your language? Please contact me!

= What's new? =
StatPress is alive again! Since the original author, Danielle Lippi, seems to have stopped working on it, i'm dealing with it - thank you, GPL. ;)
This first release contains two bug fixes and many new browser agents, search engines and spider definitions. More to come!

The changelog is at "Other Notes".

= DB Table maintenance =

StatPress can automatically delete older records to allow the insertion of newer records when your space is limited.

= StatPress Widget / StatPress_Print function =

The widget is customizable. These are the available variables:

* %thistotalvisits% - this page, total visits
* %since% - Date of the first hit
* %visits% - Today visits
* %totalvisits% - Total visits
* %os% - Operative system
* %browser% - Browser
* %ip% - IP address
* %visitorsonline% - Counts all online visitors
* %usersonline% - Counts logged online visitors
* %toppost% - The most viewed Post
* %topbrowser% - The most used Browser
* %topos% - The most used O.S.
* %thistotalpages%
* %pagestoday%

Now you could add these values everywhere! StatPress offers a new PHP function *StatPress_Print()*.
* i.e. StatPress_Print("%totalvisits% total visits.");
Put it whereever you want the details to be displayed in your template. Remember, as this is PHP, it needs to be surrounded by PHP-Tags!


== Installation ==

Upload "wp-statpress" directory in wp-content/plugins/ . Then just activate it on your plugin management page.
That's it, you're done!


= Update =

* Deactivate StatPress plugin (no data lost!)
* Override "wp-statpress" directory in wp-content/plugins/
* Re-activate it on your plugin management page
* In the Dashboard click "StatPress", then "StatPressUpdate" and wait until it will add/update db's content

Update from within Wordpress Admin Panel does work, too. But don't forget to run "StatPressUpdate" afterwards!

== Frequently Asked Questions ==

= Where can I get help? =

Please visit my <a href="http://blog.matrixagents.org/statpress-reloaded/">blog entry about StatPress Reloaded<a/> for information on how to contact me.


== Screenshots ==
&middot; <a href="http://blog.matrixagents.org/wp-content/uploads/2008/09/overview.jpg"> Overview</a><br>
&middot; <a href="http://blog.matrixagents.org/wp-content/uploads/2008/09/details.jpg"> Details</a><br>
&middot; <a href="http://blog.matrixagents.org/wp-content/uploads/2008/09/widget.jpg">Widget</a><br>
&middot; <a href="http://blog.matrixagents.org/wp-content/uploads/2008/09/spy.jpg">Spy</a><br>
&middot; <a href="http://blog.matrixagents.org/wp-content/uploads/2008/09/search.jpg">Search</a><br>


== Updates ==


*Update from 0.1 to 0.2*

* Layout update
* iPhone and other new defs

*Update from 0.2 to 0.3 (15 Jul 2007)*

* Rss Feeds support!
* Layout update
* New defs

*Update from 0.3 to 0.4 (14 Sep 2007)*

* Customizable widget
* New defs

*Update from 0.4 to 0.5 (25 Sep 2007)*

* New "Overview"
* New defs

*Update from 0.5 to 0.5.2 (3 Oct 2007)*

* Solved (rare) compatibility issues - Thanks to Carlo A.

*Update from 0.5.2 to 0.5.3 (4 Oct 2007)*

* Solved setup compatibility issues - Thanks to Andrew

*Update from 0.5.3 to 0.6 (17 Oct 2007)*

* New interface layout
* Export to CSV
* MySQL table size in Overview

*Update from 0.6 to 0.7 (22 Oct 2007)*

* Unique visitors
* New graphs (and screenshots)

*Update from 0.7 to 0.7.1 (27 Oct 2007)*

* (one time) Automatically database table creation

*Update from 0.7.1 to 0.7.2 (30 Oct 2007)*

* Now "Last Pages" and "Pages" sections don't count spiders hits - Thanks to Maddler
* Page title decoded
* New spider defs - Thanks to Maddler

*Update from 0.7.2 to 0.7.3 (8 Nov 2007)*

* New IP banning (new file def/banips.dat)
* Functions updated, bugs resolved - Thanks to Maddler
* New "Overview"
* Updated defs

*Update from 0.7.3 to 0.7.4 (12 Nov 2007)*

* New Spy section
* Updated defs

*Update from 0.7.4 to 0.7.5 (14 Nov 2007)*

* New gfx look
* Updated defs

*Update from 0.7.5 to 0.7.6 (25 Nov 2007)*

* New SEARCH section!
* New StatPress_Print() function

*Update from 0.7.6 to 0.7.7 (28 Nov 2007)*

* New SEARCH section!
* New Options panel
* (Optionally) StatPress collects data about logged users
* New Widget variables: VISITORSONLINE and USERSONLINE

*Update from 0.7.7 to 0.8 (3 Dec 2007)*

* "Automatically delete visits older than..." option

*Update from 0.8 to 0.9 (10 Dec 2007)*

* Added search by IP
* New IP lookup service: hostip.info (spy with flags!)
* New spiders
* "Support" link in dashboard

*Update from 0.8 to 0.9.5 (16 Dec 2007)*

* Multilanguage (support English and Italian... could you help me?)
* Spy links fixed
* Update Overview graph with optional num.of days
* Update queries slashed

*Update from 0.9.5 to 0.9.6 (17 Dec 2007)*

* Spanish translation (Thanks to nv1962)

*Version 1.0*

* WP Date and Time settings support (UTC + timezone offset)

*Version 1.1*

* Time settings patch

*Version 1.2*

* French translation (Thanks to Joel Remaud)
* German translation (Thanks to Martin Bartels)
* Russian translation (Thanks to Aleksandr)
* Portuguese/Brazilian translation (Thanks to gmcosta)
* New option: Minimum "capability" to view stats
* Some Overview update
* 20071225: Dutch translation (Thanks to Matthijs www.hethaagseblog.nl)

*Version 1.2.1*

* Norwegian translation (Thanks to Selveste Radiohode)

*Version 1.2.2 (2 Jan 2008)*

* Resolved some bugs

*Version 1.2.3 (16 Jan 2008)*

* Two Turkish translation (Thanks to Singlemen http://berkant.info/blog/?p=618 and Resat)
* Swedish translation (Thanks to Bjšrn Felten)
* Path independent (Thanks to Christian Heim)
* Some new widget variables
* Some fixes

*Version 1.2.4 (10 Feb 2008)*

* New widget: TopPosts
* "Overview" optimization (Thanks to nexia)
* Security patch (Thanks to livibetter)
* .def updates

*Version 1.2.5 (14 Feb 2008)*

* New option "Do not collect spiders visits"
* Compatibility issue: remove jdmonthname() func
* New Last spiders table
* Selectable fields delimiter in CSV export

*Version 1.2.6 (20 Feb 2008)*

* TopPosts widget new href links (Thanks Flip and Frank)
* .def updates (Thanks to GT)
* Interface fixes

*Version 1.2.7 (27 Feb 2008)*

* New menu layout (top level)
* Updated TopPosts widget code (Thanks to crashdumpfr)
* New hook "send_headers"
* Js, plugins and themes doesn't count
* New spiders (Thanks to M66B)

*Version 1.2.8 (27 Feb 2008)*

* Some Feed issues resolved

*Version 1.2.9 (8 Mar 2008)*

* Feed issues resolved (Thanks to Frank http://www.webtlk.com )
* Comment Feeds support

*Version 1.2.9.1 (16 Apr 2008)*

* Search works again!
* defs updated (Thanks to all forum users!)

*Version 1.2.9.2 (23 Jun 2008)*

* XSS vulnerability patch (Thanks to rogeriopvl blog.rogeriopvl.com)

*Version 1.4 (13 Sep 2008)*

* Bugfix for broken "page viewed" link when using permalinks
* Sometimes Firefox' referrer-strings were not properly decoded
* Updated definition files (Chrome, baby!)

*Version 1.4.1 (13 Sep 2008)*

* Links to your blog on "Spy"-page also were broken when using permalinks -> fixed.
* First tiny beginnings of speed improvement (Thanks to bfowle - http://www.morgan-howard.com/ )
* Updated definition files (Chrome does work now, thanks to trm96 - http://trm96.com/ )
* Hopefully got rid of unnecessary additional root dir in ZIP-download from WP.org

*Version 1.4.2 (18.09.2008)*

* Added %thistotalpages% (total number of pageloads since StatPress was installed) and %pagestoday% (total number of pageloads today) to the variables. (Thanks to Pupazz - http://this-world-is.boldlygoingnowhere.org/andinet/wordpress/ )
* Beginning to fix teh feed recognition - not done yet, though. (Thanks to TheChrisD - http://www.thechrisd.com/ )
* Again fixing the "page viewed" links - dude, this was some really messed up code!
* New definitions

*Version 1.4.3 (19.09.2008)*

* Fixed problem with some variables not being replaced properly (Thanks to Robert@PNG - http://www.trupela.com/ )

*Version 1.4.4 (19.09.2008)*

* Since 1.4.2 there was a function used that didn't work properly with php versions below 5.1.2
* Definitions
