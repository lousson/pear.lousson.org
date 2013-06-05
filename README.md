Lousson: PEAR-Channel
=====================

This repository contains the source files of the Lousson Project's PEAR
channel at http://pear.lousson.org/


Synopsis
--------

Registering the channel:

	pear channel-discover pear.lousson.org

Listing available packages:

	pear remote-list -c lousson

Installing a package:

	pear install lousson/package_name

Installing a specific version/stability:

	pear install lousson/package_name-1.4.0
	pear install lousson/package_name-alpha


Other Resources
---------------

Receiving updates via feed:

	http://pear.lousson.org/feed.xml

Browsing the source-code:

	http://github.com/lousson/


Notes
-----

The Lousson PEAR Channel is powered by Pirum (http://pirum.sensiolabs.org/)
and GitHub Organization & Project Pages, with custom DNS resolution (see
http://help.github.com/articles/setting-up-a-custom-domain-with-pages for
more information).


