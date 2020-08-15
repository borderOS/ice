# Glacier - SSB Manager with a Store
## Copyright
(C) 2020 -- PizzaLovingNerd <pizzalovingnerd@teknik.io>

Released under GNU General Public License version 2

## Description
Application to easily add and remove Chromium site specific
browsers in Debian and Ubuntu based Linux distributions. It
was originally created for Peppermint OS Ice and is now used
as the default SSB application in Peppermint OS since the
two branches of the OS merged for Peppermint Two. Since
Peppermint 5, Ice has supported Google Chrome.
Ice now supports Chrome, Chromium, Firefox, Vivaldi, Brave,
and GNOME Web. Chrome, Chromium, and Vivaldi SSB's can now be
completely isolated from each other (or use the shared master
browser profile) Firefox and GNOME Web SSB's are always
isolated.

Glacier is a fork of ice with a store to easily discover and add
new SSBs. It is creatored by an ice contributor who wanted to add
an ice store, but it got rejected from mainline ice due to
security reasons.

## Dependencies
Glacier depends on one of the above browsers being installed.
It's also possible to use it with any build of Google Chrome
however this is something that is hard coded into the app
and will need to be manually changed if one wishes to use it
in such a manner.

Glacier also depends on git to pull in icons and metadata for
each SSB.

## Usage
Glacier creates .desktop files in ~/.local/share/applications
and removes them from the same directory. Ice doesn't remove
downloaded icons, rather it overwrites them in the case that
the user adds back an SSB after removing it. In the event
that an icon is not available when attempting to download,
a stock version of the Ice icon will be used instead. The
user has the ability to specify any local icon should they
so choose.

This application does not use a standard means of applying
translations. It handles it's own translations by itself
using it's own means of doing so. If you would like to
contribute translations (please do), then please contact me
and I will make sure you have the necessary details for
doing so.

Ice was originally written for Python 2.6.x and GTK+2. For
version 4.0.0 in April 2014 it was ported to Python 3.x.x
and GTK+3. In 2020, Ice was given a redesign with CSDs to
make it more compact, and work better on smaller screens such
as Linux phones. In August of 2020, Ice was forked into glacier.

## Contact details
Thank you for your interest in Ice. If you wish to contact
me for any reason, please do so via email using the address
listed at the beginning of this document.
