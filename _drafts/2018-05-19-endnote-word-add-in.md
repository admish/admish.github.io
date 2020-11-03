---
title: EndNote Word add-in
layout: post
date: 2017-04-22T16:43:00.000+00:00
sub_heading: ''
tags: []
banner_image: ''
related_posts: []

---
Clearing up common error after installing Endnote on OS X.

> \*\*Word was unable to load an add-in\*\*

> Your add-in isn't compatible with this version of Word. 

> Please contact the add-in provider for an update.

> (EndNote CWYW Word 2016.bundle)

\* Start by quitting Word altogether.\[^1\]

\* Open a Finder window.

\* Navigate to \`/Library/Application Support/Microsoft/Office365/User Content/Startup/Word\`

  \* Click \*\*Go\*\* from the menu bar and select \*\*Go to Folder...\*\* and paste the above path

\* Delete the file \*\*EndNote CWYW Word 2016.bundle\*\* 

\* Relaunch Word and open a document

!\[Image of error window\](/uploads/2018/05/19/endnote_add-in.png "Image of error window")

\[^1\]:\[ref.\]([http://community.thomsonreuters.com/t5/EndNote-How-To/Your-add-in-isn-t-compatible-with-this-version-of-Word/td-p/132195](http://community.thomsonreuters.com/t5/EndNote-How-To/Your-add-in-isn-t-compatible-with-this-version-of-Word/td-p/132195 "http://community.thomsonreuters.com/t5/EndNote-How-To/Your-add-in-isn-t-compatible-with-this-version-of-Word/td-p/132195"))