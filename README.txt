README
------

For the updated XSLT language syntax to work, you'll need to delete
TextMate's built-in XSL language syntax. To do this, open the bundle
editor (Bundles->Bundle Editor->Show Bundle Editor) and go to the XML
bundle. Now find the XSL language definition (has an gray icon before it
with an 'L').

MAKE SURE YOU HAVE SELECTED THE **XSL** DEFINITION.

YOU WILL STILL NEED THE _XML_ definition for this update to function.
Once you have selected the **XSL** definition, click the '-' sign at the
bottom of the list to "delete" it. It still physically resides in the
   /Applications/TextMate.app/Contents/SharedSupport/Bundles
folder, but a modified copy has been placed in
   ~/Library/Application Support/TextMate/Bundles/XML.tmbundle
without the XSL language definition.

This allows the updated definition to take precedence over TextMate's
included definition.

For further information about this bundle, please contact:
Ross Williams
Hannon Hill Corporation
ross.williams@hannonhill.com