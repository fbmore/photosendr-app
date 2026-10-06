# Demo print images: used by the worker, not by this site

The photosendr-views worker (`DEMO_IMAGES` in print.js) serves these as the
photos of the `demo` share's print orders: the order page's thumbnails, and
what Prodigi's sandbox downloads. No page here links to them, so they look
unused. Removing or renaming them breaks every demo print order, which is
what happened when the shot-*.png screenshots they used to point at were
dropped from the site.

1800x1200 JPEGs: a 6x4 print at 300 dpi.
