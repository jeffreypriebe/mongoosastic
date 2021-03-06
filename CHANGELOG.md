2.1.1 / 2015-03-28
===================

  * added gulp, jshint and jscs
  * example fixed and dependencies updated

2.1.0 / 2015-03-21
===================

  * added multihost connection feature [#56](https://github.com/mongoosastic/mongoosastic/issues/56)
  * updates to README
  * lots of smalls code cleaning
  * Added highlight feature [#51](https://github.com/mongoosastic/mongoosastic/issues/51)
  * added full CHANGELOG.md

2.0.10 / 2015-03-19
===================

  * updated elasticsearch dependency. changed bulk config
  * Dependecies updated

2.0.9 / 2015-03-19
==================

  * Increased timeout for travis environment
  * Update .travis.yml
    testing conf.
  * added timeout env variable for travis to wait on index deletion

2.0.8 / 2015-03-17
==================

  * fixed timeout for bulk test
  * Merge pull request [#40](https://github.com/mongoosastic/mongoosastic/issues/40) from srfrnk/patch-1
    Patch 1 - fixed
  * Merge pull request [#47](https://github.com/mongoosastic/mongoosastic/issues/47) from guumaster/master
    small patch for nested array schemas
  * Merge pull request [#53](https://github.com/mongoosastic/mongoosastic/issues/53) from gazsp/master
    Fixes [#49](https://github.com/mongoosastic/mongoosastic/issues/49)
  * Fixes [#49](https://github.com/mongoosastic/mongoosastic/issues/49)
  * small patch for nested array schemas
  * wrong value used... now should be better.
  * fixed commit
  * allow debugging the calls made by elasticsearch client.
    added ability to send {log:"trace"} in options to enable logging

2.0.6 / 2014-12-11
==================

  * Merge pull request [#35](https://github.com/mongoosastic/mongoosastic/issues/35) from jitowix/master
    add settings when index is created
  * add settings when index is created

2.0.5 / 2014-11-21
==================

  * Merge pull request [#30](https://github.com/mongoosastic/mongoosastic/issues/30) from nicolasmccurdy/mention-estruncate
    In documentation files, rename "truncate" to "esTruncate"
  * In documentation files, rename "truncate" to "esTruncate"

2.0.4 / 2014-11-10
==================

  * Merge pull request [#27](https://github.com/mongoosastic/mongoosastic/issues/27) from ignlg/feature/serialize-cast-bulk
    Serialize on bulk calls. Serialize: this = full model.
  * Serialize on bulk calls. Serialize: this = full model.

2.0.3 / 2014-11-10
==================

  * Merge pull request [#26](https://github.com/mongoosastic/mongoosastic/issues/26) from b96705008/master
    get rid of "continue" when encounter objectid (issue [#12](https://github.com/mongoosastic/mongoosastic/issues/12))
  * get rid of "continue" when encounter objectid
  * remove unstable node testing, broken for now

2.0.2 / 2014-11-05
==================

  * Treat null query like undefined

2.0.1 / 2014-11-02
==================

  * Merge pull request [#23](https://github.com/mongoosastic/mongoosastic/issues/23) from sascha/master
    'protocol' and 'auth' options are ignored
  * 'protocol' and 'auth' options are ignored
    This fixes an issue, where the 'protocol' and 'auth' options were ignored.
  * Merge pull request [#21](https://github.com/mongoosastic/mongoosastic/issues/21) from mongoosastic/feature/official-driver
    Feature/official driver
  * Add changelog

2.0.0 / 2014-10-30
==================

  * updates for travis
  * longer delay for bulk test
  * significant version bump
  * formatting
  * Add gitter badge
  * Update query interface
  * refresh readme
  * don't stop bulk options with synchronize
  * refactor bulk api
  * uppercase README
  * Break out docs
  * remove elastical dependency
  * All tests passing
  * had to scale back abstraction on search
  * Close to fixing geo test
  * first pass at integrating elasticsearch driver
  * remove semicolons from mongoosastic.js

1.0.2 / 2014-10-28
==================

  * Document geo_shape

1.0.1 / 2014-10-28
==================

  * Add documentation about bulk api

1.0.0 / 2014-10-28
==================

  * big api changes, big version bump
  * Merge pull request [#17](https://github.com/mongoosastic/mongoosastic/issues/17) from mongoosastic/albanm/feature/bulk-and-array-indexing
    Albanm/feature/bulk and array indexing
  * resolve conflicts
  * use containEql instead of include
  * Merge pull request [#16](https://github.com/mongoosastic/mongoosastic/issues/16) from mongoosastic/remove-river-code
    remove river code
  * Merge pull request [#14](https://github.com/mongoosastic/mongoosastic/issues/14) from mongoosastic/nlko-geo_shape
    Nlko geo shape
  * Merge pull request [#15](https://github.com/mongoosastic/mongoosastic/issues/15) from mongoosastic/cubuzoa/feature/hydrate-hits
    Cubuzoa/feature/hydrate hits
  * remove river code
  * Update hydrated tests to conform to api
  * Get first level of hits field
    Provided fix for etting first level `hits` field of search results when
    used hydrate
  * Correct enveloppe test
    Enveloppe corners were in wrong order resulting in a bad test.
  * Add ES 1.0 support for geo shape tests
  * Added testfor geo_shape and updated manual
  * Add test for undefined object field in the path prior of its use
  * Correct boost test field (support ES 0.9 and 1.0).
    In my tests, the mapping format returned by the getMapping function is
    not the same between 0.90.11 and 1.0
  * Keep geo_* types in the mapping
    Prior, only geo_point were kept in the mapping.
  * Update readme.md
    More dynamic version info

0.6.1 / 2014-10-24
==================

  * Update badge
  * Update repo info in package.json

0.6.0 / 2014-10-14
==================

  * remove outdated river info
  * add more node versions to travis
  * Merge pull request [#128](https://github.com/mongoosastic/mongoosastic/issues/128) from marsanla/patch-3
    Add elasticsearch client
  * Merge pull request [#120](https://github.com/mongoosastic/mongoosastic/issues/120) from antoineverger/master
    Add the esTruncate static method to remove all documents from an index
  * Add elasticsearch client
    Add elasticsearch client to avoid duplicate instances and call from model plugin.
  * Documentation for the truncate static method
  * Centralise the "warmup" timeout value in the config to make it easier to adjust it
  * Add the feature to pre-process a field before indexing
  * Add the esTruncate static method to remove all documents from an index
  * bump semver
  * Merge pull request [#119](https://github.com/mongoosastic/mongoosastic/issues/119) from antoineverger/master
    Add the settings to create mapping.

0.5.0 / 2014-09-23
==================

  * Add the settings to create mapping.
    First step to have a better configuration of the index settings.
  * update readme to reflect version

0.4.1 / 2014-08-28
==================

  * Merge pull request [#116](https://github.com/mongoosastic/mongoosastic/issues/116) from sascha/feature/id-in-subdocuments
    '_id' and/or 'id' properties in subdocuments
  * Merge pull request [#115](https://github.com/mongoosastic/mongoosastic/issues/115) from danteata/master
    fixed configuration setup example
  * '_id' and 'id' in subdocuments
    Added the possibility to have properties called '_id' or 'id' within subdocuments.
  * fixed configuration setup example
  * Update semver to reflect api change
  * Merge pull request [#111](https://github.com/mongoosastic/mongoosastic/issues/111) from astro/refresh
    expose index refresh

0.4.0 / 2014-08-18
==================

  * Update version, could be some breaking changes

0.3.0 / 2014-08-15
==================

  * Merge pull request [#113](https://github.com/mongoosastic/mongoosastic/issues/113) from aschmid/master
    fixed issue where object properties where ignored by serialize
  * fixed issue where object properties where ignored by serialize
  * Merge pull request [#99](https://github.com/mongoosastic/mongoosastic/issues/99) from xren/master
    Emit the error when doc.save() fails during synchronization
  * Merge pull request [#100](https://github.com/mongoosastic/mongoosastic/issues/100) from clippPR/master
    fixing this bug (hopefully) - https://github.com/jamescarr/mongoosastic/...
