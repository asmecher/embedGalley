# embedGalley
EmbedGalley plugin automatically converts a JATS XML galley to embedded HTML, which is shown on the abstract page.


NOTE: the current version is broken. It seems that Request::getBaseUrl() returns sometimes values that cause trouble in $stylesheet->load(). Probably fixed by defining a baseurl in config.inc for all journals.

The plugin is using some code and XSL files from https://github.com/PeerJ/jats-conversion. Thank you!

The plugin was created by The Federation of Finnish Learned Societies.

TODO
- support for other citation formats
- allow custom CSS
- add back links to references

