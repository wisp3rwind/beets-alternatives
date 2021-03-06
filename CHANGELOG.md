Change Log
==========

## v0.9.0 - 2018-11-24
* The package is now on PyPI
* Require at least beets v1.4.7
* Update album art in alternatives when it changes
* Python 3 support (Python 2.7 continuous to be supported)
* Support the format aliases defined by the convert plugin ('wma' and 'vorbis'
  with current beets)
* Bugfix: Explicitly write tags after encoding instead of relying on the
  encoder to do so
* Bugfix: If the `formats` config option is modified, don't move files if the
  extension would change, but re-encode

## v0.8.2 - 2015-05-31
* Fix a bug that made the plugin crash when reading unicode strings
  from the configuration

## v0.8.1 - 2015-05-30
* Require beets v1.3.13 and drop support for all older versions.
* Embed cover art when converting items

## v0.8.0 - 2015-04-14
First proper release
