![kreytricks_header](/files/img/Kreytricks_header.png)

# Kreytricks
[![Build Status](https://travis-ci.org/kreytricks/kreytricks.svg?branch=master)](https://travis-ci.org/kreytricks/Kreytricks) [![License](http://img.shields.io/:license-lgpl-green.svg)](https://tldrlegal.com/license/gnu-lesser-general-public-license-v2.1-(lgpl-2.1))

Contribution-focused winetricks fork

This fork is true rolling-release where recommended method to sync with upstream is to use git.

# Maintainance
This fork is unmaintained by design
- Issues that are winetricks-related are directed to upstream
- Merge request are reviewed by the community based on CONTRIBUTING.md

# Tests
The tests need `bashate`, `checkbashisms`, and `shellcheck>=0.4.4` installed.
Makefile supports a few test targets:

* check - runs './tests/winetricks-tests quick' (without first clearing $WINETRICKS_CACHE)
* shell-checks - runs './tests/shell-checks'
* test - runs './tests/winetricks-tests full' (and clears $WINETRICKS_CACHE first)
* xvfb-check - runs './tests/winetricks-tests xvfb-check' (without first clearing $WINETRICKS_CACHE first)
