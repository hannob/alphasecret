what?
-----

GIMP has an unexpected behavior that when "deleting" content from an image
with an alpha channel it will not actually delete the content, it will just
be marked transparent.

This can have the unintended sideeffect of leaking information if you use
GIMP to remove private parts of an image, e.g. a screenshot.

With this script you can go through a list of images (e.g. from a Twitter
data export) and check images that might have such hidden content.

background
----------

* Discussion on Gitlab https://gitlab.gnome.org/GNOME/gimp/issues/4487
* Twitter discussion by Will Dormann https://twitter.com/wdormann/status/1215746766659837953
* Article on Golem.de (German) https://forum.golem.de/kommentare/security/alphakanal-gimp-verraet-geheimnisse-in-bildern/132613,list.html

misc
----

Written by Hanno Böck, https://hboeck.de

License: The Unlicense (meaning do with it whatever you like)
