Changelog
---------

Versions
========

1. **RISE** master branch will be following the **Jupyter** codebase.

2. There is also "released" tagged [branches](https://github.com/damianavila/RISE/releases)
compatible with previous IPython versions:

    *  1.x tag compatible with **IPython** 1.x series
    *  2.x tag compatible with **IPython** 2.x series
    *  3.x tag compatible with **IPython** 3.x series
    *  3.x.1 tag also compatible with `notebook` 4.x series, but using old installation mechanism
    *  4.0.0b1 tag compatible with the `notebook` 4.2 and above, beta release, please test and report any issues
    *  5.0.0 tag compatible with `notebook` >= 5.0.0
    *  5.1.0 tag compatible with `notebook` >= 5.0.0
    *  5.2.0 tag compatible with `notebook` >= 5.0.0
    *  5.3.0 tag compatible with `notebook` >= 5.5.0

3. With **Jupyter** landing we will provide a conda and pip-installable packages too

**NOTE**: We will only maintain the latest released version.

Changes
=======

* 5.3.0

  * Auto enable nbextension when installing with pip (https://github.com/damianavila/RISE/pull/342)
  * Making rise compliant with nbextensions_configurator (https://github.com/damianavila/RISE/pull/344)
  * Documentation general review, fixes and improvements (https://github.com/damianavila/RISE/pull/347)
  * Mixup between `note` and `notes` (https://github.com/damianavila/RISE/pull/372)
  * Keep `?` from popping up keyboard shortcuts (https://github.com/damianavila/RISE/pull/373)
  * Create shortcut to go to the configurator (https://github.com/damianavila/RISE/pull/376)
  * General review of `setup.py` (https://github.com/damianavila/RISE/pull/387)

* 5.2.0

  * Source code cleanup and normalization (https://github.com/damianavila/RISE/pull/311)
  * Add some docs updates (https://github.com/damianavila/RISE/pull/312)
  * Add sidebar for all doc pages (https://github.com/damianavila/RISE/pull/314)
  * Improve customization reference docs (https://github.com/damianavila/RISE/pull/318)
  * Set new defaults for ``auto_select`` and ``start_slideshow_at`` options (https://github.com/damianavila/RISE/pull/323)
  * Refactor actions and fix wide toolbar button (https://github.com/damianavila/RISE/pull/324)
  * Update docs deployment instructions (https://github.com/damianavila/RISE/pull/325) and (https://github.com/damianavila/RISE/pull/326)
  * Make the output observer aware of the scrolling needs (https://github.com/damianavila/RISE/pull/327)
  * Add basic usage gif into the docs (https://github.com/damianavila/RISE/pull/328)
  * Fix list not correctly displayed in docs (https://github.com/damianavila/RISE/pull/338)
  * Add disable and removal section, add note about browser zoom in/out, add PDF export section and add a real changelog for 5.1.1 (https://github.com/damianavila/RISE/pull/339)

Previous lazy changelogs:

* 5.1.0: https://github.com/damianavila/RISE/milestone/5?closed=1
* 5.0.0: https://github.com/damianavila/RISE/milestone/4?closed=1
* 4.x series: https://github.com/damianavila/RISE/milestone/1?closed=1
