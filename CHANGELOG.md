# WebJET CMS changes

## webjet-v1.1-SNAPSHOT

- change `NekoHtml` to `org.htmlunit` version
- removed dependency to vulnerable `xercesImpl`
- use `shade` plugin to bundle `org.eclipse.core.runtime` classes (copyied to SRC folder), so we don't need to import all (not used) dependencies of `runtime` package
- changed `htmlheader.xsl` to simple version to just show color difference without JS/CSS code

## webjet-v1.0-SNAPSHOT

Initial release of original fork for WebJET CMS:

- `TagToString` - use `Prop` object for text output