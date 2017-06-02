Entity Clean plugin for Tiny Tiny RSS
=====================================

Description
-----------

Plugin for Tiny Tiny RSS that cleans up named HTML entities, converting them to numeric so they are XML friendly.

Simply runs a big search-and-replace to change (case insensitive) any named HTML entity to the equivalent number, with the exception of the XML standard ones (quot, amp, apos, lt, gt) - taken from https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references.

Use case - if you see this sort of message in the feed errors:

`error: LibXML error 26 at line x (column x): Entity 'xxxx' not defined`

Installation
------------

1. Create a folder `entityclean` in the `plugins` folder of your installation.
2. Copy the code for this plugin into that folder.
3. Enable the plugin in the Tiny Tiny RSS preferences.
4. Reload feeds and the plugin will clean them.

License
-------

Apache 2.0

See the LICENSE file for full details.
