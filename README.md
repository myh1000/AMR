[![Coverage Status](https://coveralls.io/repos/AllMangasReader-dev/AMR/badge.png)](https://coveralls.io/r/AllMangasReader-dev/AMR) [![Code Climate](https://codeclimate.com/github/AllMangasReader-dev/AMR.png)](https://codeclimate.com/github/AllMangasReader-dev/AMR) [![Build Status](https://travis-ci.org/AllMangasReader-dev/AMR.svg?branch=develop)](https://travis-ci.org/AllMangasReader-dev/AMR)

AMR (All Mangas Reader)
===
AllMangasReader developer branch has the lastest changes made
to the AllMangasReader Chrome Extension.

This version of AllMangasReader offers support for a few more sites such as KissManga, etc.

Get the lastest stable version from http://allmangasreader.com,
also get support on our forums in http://allmangasreader.com/forum

PLUGINS
-------------
* jQuery UI
* jQuery
* prettyPhoto
* SimpleModal
* Treeview
  
INSTALLATION
-------------

1. Clone the git repository
```shell
git clone https://github.com/myh1000/AMR.git
```
2. Pull the submodules
```shell
git submodule update --init --recursive --remote
```
3. Go to the extension list.
4. Activate "Developers Mode"
5. Click "Load unpacked extension…"
6. Look for the folder with the extension and enjoy

BUGS
-------------
All bugs from the current developing version should be
reported under GitHub.

KNOW BUGS
----------
No chart generation in the Personal Statistics page,
due using Google Visualization API hasn't changed to
comply with manifest v2 rules as can be seen here:
https://code.google.com/p/google-visualization-api-issues/issues/detail?id=978

See COPYING and file headers for license info
