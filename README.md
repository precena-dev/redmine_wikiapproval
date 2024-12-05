Redmine Wikiapproval Macro Plugin
==================================

This plugin provides a macro for marking revisions of wiki pages as approved and displaying the approval status.

Requirements
------------

Redmine 3.0.x, 3.1.x, 4.0.x or 4.1.x
Other versions are not tested but may work.

Installation
------------
1. Download archive and extract to /your/path/to/redmine/plugins/
2. Restart Redmine

Login to Redmine and go to Administration->Plugins. You should now see 'Redmine Wikiapproval'. Enjoy!

Usage
------------
Anywhere, ideally on top, on a wiki page include the macro {{approvepage}} to display the approved state of the page or page revision.

When saving changes to a wiki page add a comment text starting with the word "Freigegeben:" to the comment to approve a page.
